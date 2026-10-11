# Ingredient Gathering

Script name: `alchemy`

Gathers and prepares a remedy ingredient. With `forage` it walks to the forage room for that herb (your town's, or the **Forage override room** on the Character page) and forages until the herb container holds the amount wanted. With `prepare` it takes the raw herb to a press or grinder room at the remedies society and makes the dried or crushed form, as many as wanted. Both words together do one after the other.

```
.alchemy aloe forage prepare 25
.alchemy belradi forage
.alchemy aloe prepare
```

The ingredient can be any part of its name. The number is how many to end up with; without one, the Alchemy page's quantities are used. Foraging needs the Outdoorsmanship ranks the herb asks for and a hand free.

## How to start it

Type `.alchemy` followed by the words it takes.

ingredient [forage] [prepare] [quantity]

Example:

```
.alchemy aloe forage prepare 25
```

In Master Train, pick **Alchemy Ingredients** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Crafting](/studio/crafting.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-alchemy-herb-quantity"></span>**Forage quantity** | A number, at least 1. | 6 | Global, or each character |
| <span id="setting-alchemy-forage-override-room"></span>**Forage room override** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| <span id="setting-alchemy-forage-type"></span>**Forage style** |  | (not set) | Global, or each character |
| <span id="setting-alchemy-forage-override-town"></span>**Forage town override** |  | (not set) | Global, or each character |
| <span id="setting-alchemy-prep-quantity"></span>**Preparation quantity** | A number, at least 1. | 25 | Global, or each character |
| <span id="setting-alchemy-herb-storage"></span>**Raw herb storage** |  | (not set) | Global, or each character |


# Remedies

Script name: `remedy`

Native port of remedy.lic.

## How to start it

Type `.remedy` followed by the words it takes.

remedies chapter recipe herb1 herb2 catalyst container noun, or continue ...

Example:

```
.remedy remedies 1 "blister cream" aloe na "coal nugget" mortar cream
```

In Master Train, pick **Remedies** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Crafting](../studio/crafting.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Alchemy room** | Work orders walk here before mixing remedies (Lich's alchemy_room). Blank or 0 mixes where the character stands. A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| **Prepared herb container** | The container the remedy step takes prepared herbs from. | (not set) | Global, or each character |
| **Water and alcohol to keep** | Before a remedies work order the one stack of water and the one stack of alcohol in the crafting bag are topped up with whole tens from the alchemy stock shop, never past this number (a stack holds 100). 100 means 91 to 100 after the top-up. A number, at least 10, at most 100. | 100 | Global, or each character |


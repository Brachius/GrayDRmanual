# Remedies

Script name: `remedy`

Makes one remedy in the mortar or bowl, the same way Lich's remedy script did it hand for hand. It buys nothing: the work-order script keeps water, alcohol and the coal nugget stocked, so run it from Work Orders unless you have everything already.

```
.remedy remedies 1 "blister cream" aloe na "coal nugget" mortar cream
.remedy continue na "coal nugget" mortar cream
```

In order: the word `remedies`, the chapter, the recipe in quotes, the first herb, the second herb or `na` when the recipe has none, the catalyst, the container (mortar, or a bowl; a cauldron answers for a bowl), and the noun of the finished item. `continue` carries on with a remedy already started. The finished item ends in your left hand.

## How to start it

Type `.remedy` with the words shown above.

In Master Train, pick **Remedies** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Crafting](/studio/crafting.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-crafting-alchemy-room"></span>**Alchemy room** | Work orders walk here before mixing remedies (Lich's alchemy_room). Blank or 0 mixes where the character stands. A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| <span id="setting-crafting-herb-container"></span>**Prepared herb container** | The container the remedy step takes prepared herbs from. | (not set) | Global, or each character |
| <span id="setting-crafting-water-alcohol-keep"></span>**Water and alcohol to keep** | Before a remedies work order the one stack of water and the one stack of alcohol in the crafting bag are topped up with whole tens from the alchemy stock shop, never past this number (a stack holds 100). 100 means 91 to 100 after the top-up. A number, at least 10, at most 100. | 100 | Global, or each character |


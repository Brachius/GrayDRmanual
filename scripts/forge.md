# Forging

Script name: `forge`

Forging at an anvil: blacksmithing, armorsmithing and weaponsmithing. It reads the book, gets the ingot and the tools from your crafting bag and belt (the Gear page lists them), works the forge (fuel, bellows, hammer, tongs, grindstone, slack tub, oil), and finishes the piece the way you asked. It renews the private forge rental when it runs low, stamps the piece when **Stamp finished goods** is on, and puts the leftover ingot away.

What to type:

```
.forge weaponsmithing 1 "a metal throwing dagger" bronze dagger
.forge armorsmithing 3 "some metal gauntlets" steel gauntlets log
.forge instructions bronze dagger
.forge temper dagger
.forge balance dagger       (also: hone, lighten, reinforce)
.forge resume weaponsmithing dagger
```

The book word comes first, then the chapter number, the recipe name in quotes, the metal, and the noun the finished item will have. A finish word is optional and may go first or last: `hold` keeps the piece in hand (the default), `log` puts it in the work-order logbook, `stow` puts it away, `trash` throws it out. `skip` skips restocking oil and fuel. `resume` carries on with a piece already started.

What you need: the forging tools on your belt or in the crafting bag, an ingot of the metal named, and enough coin on hand for fuel and oil. The Crafting page holds the bag, the belt and the stamping choice; the Forging settings there hold the rest.

## How to start it

Type `.forge` followed by the words it takes.

Book type + chapter + recipe + metal + noun, or an enhancement + noun; finish word optional.

Example:

```
.forge weaponsmithing 1 "a metal throwing dagger" bronze dagger
```

In Master Train, pick **Forging** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Crafting](/studio/crafting.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-crafting-deed-own-ingot"></span>**Deed the leftover own ingot** | Yes or No. | No | Global, or each character |
| <span id="setting-crafting-forge-rental"></span>**Forge rental** | Yes only when this character rents a workroom. Sew Yes or No. | No | Global, or each character |
| <span id="setting-crafting-forge-use-private-forge"></span>**Forge walks to the private forge** | Yes or No. | No | Global, or each character |
| <span id="setting-crafting-use-own-ingot-type"></span>**Own-ingot metal for workorders (blank = buy stock)** |  | (blank) | Global, or each character |
| <span id="setting-crafting-forge-private-forge-cost-platinum"></span>**Private forge rental platinum** | Rental price in local platinum. GrayDR converts this amount to copper only at the payment boundary. A number, at least 0. | 0.5 | Global, or each character |
| <span id="setting-crafting-use-private-forge"></span>**Smith uses the private forge** | Yes or No. | No | Global, or each character |
| <span id="setting-gear-adjustable-tongs"></span>**Tongs are adjustable (convert to shovel)** | Yes or No. | No | Global, or each character |


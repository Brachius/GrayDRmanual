# Crafting

Configuration Studio page **Crafting**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Settings every crafting script shares (the crafting bag, the town, stamping, the magic floor), then the belts, outfitting, forging, shaping, engineering and work order settings.

Scripts that read these settings: [Ingredient Gathering](../scripts/alchemy.md), [Craft Training](../scripts/craft.md), [Enchanting](../scripts/enchant.md), [Forging](../scripts/forge.md), [Remedies](../scripts/remedy.md), [Shaping](../scripts/shape.md), [Work Orders](../scripts/workorders.md).

## Shared Crafting Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Alchemy room** | Work orders walk here before mixing remedies (Lich's alchemy_room). Blank or 0 mixes where the character stands. A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| **Craft training rooms** | A list of room names. | (not set) | Global, or each character |
| **Crafting bag** | The container holding tools | (blank) | Global, or each character |
| **Crafting magic mana floor** | A number, at least 0, at most 100. | 40 | Global, or each character |
| **Crafting town override** |  | (blank) | Global, or each character |
| **Deed the leftover own ingot** | Yes or No. | No | Global, or each character |
| **Enchanting room override** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| **Harness instead of cambrinth when Arcana is locked** | Yes or No. | No | Global, or each character |
| **Items fetched from the crafting bag** | A list. | (not set) | Global, or each character |
| **Khazar's cube worn piece** |  | (blank) | Global, or each character |
| **Master crafting book item** | Exact item text | (blank) | Global, or each character |
| **Maximum crafting mindstate** | A number, at least 0, at most 34. | 31 | Global, or each character |
| **Own-ingot metal for workorders (blank = buy stock)** |  | (blank) | Global, or each character |
| **Prepared herb container** | The container the remedy step takes prepared herbs from. | (not set) | Global, or each character |
| **Rank-tier recipe overrides** |  |  | Global, or each character |
| **Stamp finished goods** | Yes or No. | No | Global, or each character |
| **Train Sorcery while crafting** | Yes or No. | No | Global, or each character |
| **Water and alcohol to keep** | Before a remedies work order the one stack of water and the one stack of alcohol in the crafting bag are topped up with whole tens from the alchemy stock shop, never past this number (a stack holds 100). 100 means 91 to 100 after the top-up. A number, at least 10, at most 100. | 100 | Global, or each character |

## Outfitting Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Private outfitting room override** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |

## Forging Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Allow Sorcery while forging** | Yes or No. | No | Global, or each character |
| **Forge rental** | Yes only when this character rents a workroom. Sew Yes or No. | No | Global, or each character |
| **Forge walks to the private forge** | Yes or No. | No | Global, or each character |
| **Private forge rental platinum** | Rental price in local platinum. GrayDR converts this amount to copper only at the payment boundary. A number, at least 0. | 0.5 | Global, or each character |
| **Smith uses the private forge** | Yes or No. | No | Global, or each character |

## Engineering Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Private engineering room (0 = public shaping rooms)** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |

## Workorder Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Accepted recipes per discipline** | Optional recipe-name allow-lists. Leave a discipline unset to accept all of its work-order recipes. |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Blacksmithing** | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Armorsmithing** | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Weaponsmithing** | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Tailoring** | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Shaping** | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Carving** | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Tinkering** | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Remedies** | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Artificing** | A list. | (not set) | Global, or each character |
| **Carving material family** | Choices: stone, bone. | stone | Global, or each character |
| **Heal at safe room before starting** | Yes or No. | No | Global, or each character |
| **Keep leftover materials** | Yes or No. | No | Global, or each character |
| **Maximum order size accepted** | A number, at least 1. | 2 | Global, or each character |
| **Minimum order size accepted** | A number, at least 1. | 2 | Global, or each character |
| **Platinum kept on hand for stock** | Whole platinum kept on hand for crafting materials. When a crafting script is short it goes to the bank, deposits all, and withdraws this much platinum (more only when one purchase costs more). A number, at least 1. | 1 | Global, or each character |
| **Repair tools after each order** | Yes or No. | No | Global, or each character |
| **Repair with own brush and oil** | Yes or No. | No | Global, or each character |
| **Skip crafting above this mindstate** | A number, at least 0, at most 34. | 34 | Global, or each character |
| **Tools never sent for repair** | A list. | (not set) | Global, or each character |
| **Work order difficulty** | Choose one default for every discipline, then enable only the discipline overrides that should differ. |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **All disciplines** _(required)_ | Choices: challenging, easy, hard. | challenging | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Blacksmithing override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Armorsmithing override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Weaponsmithing override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Tailoring override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Shaping override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Carving override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Tinkering override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Remedies override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Artificing override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| **Work order stock materials** | Stock material bought for each crafting family. Defaults match the original workorders script. |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Fabric** | Choices: Burlap — 10 yards, Linen — 10 yards, Wool — 10 yards, Silk — 10 yards. | Burlap — 10 yards | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Knitting material** | Choices: Yarn — 100 yards, Thread — 100 yards. | Yarn — 100 yards | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Forging metal stock** | Choices: Bronze — 5 volumes, Bronze — 50 volumes, Bronze — 100 volumes, Bronze — 200 volumes, Steel — 10 volumes, Steel — 50 volumes, Steel — 100 volumes, Steel — 200 volumes, Iron — 50 volumes, Iron — 100 volumes, Iron — 200 volumes, Tin — 50 volumes, Tin — 100 volumes. | Bronze — 5 volumes | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Mechanism metal stock** | Choices: Bronze — 5 volumes, Bronze — 50 volumes, Bronze — 100 volumes, Bronze — 200 volumes, Steel — 10 volumes, Steel — 50 volumes, Steel — 100 volumes, Steel — 200 volumes, Iron — 50 volumes, Iron — 100 volumes, Iron — 200 volumes, Tin — 50 volumes, Tin — 100 volumes. | Bronze — 5 volumes | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Wood** | Choices: Pine — 5 volumes, Maple — 5 volumes, Balsa — 10 volumes. | Maple — 5 volumes | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Stone** | Choices: Alabaster — 3 volumes, Granite — 3 volumes, Marble — 3 volumes. | Alabaster — 3 volumes | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Bone** | Choices: Deer bone — 10 volumes, Wolf bone — 10 volumes. | Wolf bone — 10 volumes | Global, or each character |

## Other Crafting Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Forage quantity** | A number, at least 1. | 6 | Global, or each character |
| **Forage room override** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| **Forage style** |  | (not set) | Global, or each character |
| **Forage town override** |  | (not set) | Global, or each character |
| **Preparation quantity** | A number, at least 1. | 25 | Global, or each character |
| **Raw herb storage** |  | (not set) | Global, or each character |
| **Tongs are adjustable (convert to shovel)** | Yes or No. | No | Global, or each character |


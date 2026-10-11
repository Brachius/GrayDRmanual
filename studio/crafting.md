# Crafting

Configuration Studio page **Crafting**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Settings every crafting script shares (the crafting bag, the town, stamping, the magic floor), then the belts, outfitting, forging, shaping, engineering and work order settings.

Scripts that read these settings: [Ingredient Gathering](/scripts/alchemy.md), [Craft Training](/scripts/craft.md), [Enchanting](/scripts/enchant.md), [Forging](/scripts/forge.md), [Remedies](/scripts/remedy.md), [Shaping](/scripts/shape.md), [Work Orders](/scripts/workorders.md).

## Shared Crafting Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-crafting-alchemy-room"></span>**Alchemy room** | Work orders walk here before mixing remedies (Lich's alchemy_room). Blank or 0 mixes where the character stands. A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| <span id="setting-crafting-training-rooms"></span>**Craft training rooms** | A list of room names. | (not set) | Global, or each character |
| <span id="setting-crafting-crafting-container"></span>**Crafting bag** | The container holding tools | (blank) | Global, or each character |
| <span id="setting-crafting-training-spells-mana-threshold"></span>**Crafting magic mana floor** | A number, at least 0, at most 100. | 40 | Global, or each character |
| <span id="setting-crafting-force-crafting-town"></span>**Crafting town override** |  | (blank) | Global, or each character |
| <span id="setting-crafting-deed-own-ingot"></span>**Deed the leftover own ingot** | Yes or No. | No | Global, or each character |
| <span id="setting-crafting-enchanting-room"></span>**Enchanting room override** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| <span id="setting-crafting-use-harness-when-arcana-locked"></span>**Harness instead of cambrinth when Arcana is locked** | Yes or No. | No | Global, or each character |
| <span id="setting-crafting-crafting-items-in-container"></span>**Items fetched from the crafting bag** | A list. | (not set) | Global, or each character |
| <span id="setting-crafting-cube-armor-piece"></span>**Khazar's cube worn piece** |  | (blank) | Global, or each character |
| <span id="setting-crafting-master-crafting-book"></span>**Master crafting book item** | Exact item text | (blank) | Global, or each character |
| <span id="setting-crafting-craft-max-mindstate"></span>**Maximum crafting mindstate** | A number, at least 0, at most 34. | 31 | Global, or each character |
| <span id="setting-crafting-use-own-ingot-type"></span>**Own-ingot metal for workorders (blank = buy stock)** |  | (blank) | Global, or each character |
| <span id="setting-crafting-herb-container"></span>**Prepared herb container** | The container the remedy step takes prepared herbs from. | (not set) | Global, or each character |
| <span id="setting-crafting-craft-overrides"></span>**Rank-tier recipe overrides** |  |  | Global, or each character |
| <span id="setting-crafting-mark-crafted-goods"></span>**Stamp finished goods** | Yes or No. | No | Global, or each character |
| <span id="setting-crafting-training-spells-enable-sorcery"></span>**Train Sorcery while crafting** | Yes or No. | No | Global, or each character |
| <span id="setting-crafting-water-alcohol-keep"></span>**Water and alcohol to keep** | Before a remedies work order the one stack of water and the one stack of alcohol in the crafting bag are topped up with whole tens from the alchemy stock shop, never past this number (a stack holds 100). 100 means 91 to 100 after the top-up. A number, at least 10, at most 100. | 100 | Global, or each character |

## Outfitting Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-crafting-outfitting-room"></span>**Private outfitting room override** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |

## Forging Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-crafting-training-spells-enable-sorcery-forging"></span>**Allow Sorcery while forging** | Yes or No. | No | Global, or each character |
| <span id="setting-crafting-forge-rental"></span>**Forge rental** | Yes only when this character rents a workroom. Sew Yes or No. | No | Global, or each character |
| <span id="setting-crafting-forge-use-private-forge"></span>**Forge walks to the private forge** | Yes or No. | No | Global, or each character |
| <span id="setting-crafting-forge-private-forge-cost-platinum"></span>**Private forge rental platinum** | Rental price in local platinum. GrayDR converts this amount to copper only at the payment boundary. A number, at least 0. | 0.5 | Global, or each character |
| <span id="setting-crafting-use-private-forge"></span>**Smith uses the private forge** | Yes or No. | No | Global, or each character |

## Engineering Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-crafting-engineering-room"></span>**Private engineering room (0 = public shaping rooms)** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |

## Workorder Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-workorders-recipes"></span>**Accepted recipes per discipline** | Optional recipe-name allow-lists. Leave a discipline unset to accept all of its work-order recipes. |  | Global, or each character |
| <span id="setting-workorders-recipes-blacksmithing"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Blacksmithing** | A list. | (not set) | Global, or each character |
| <span id="setting-workorders-recipes-armorsmithing"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Armorsmithing** | A list. | (not set) | Global, or each character |
| <span id="setting-workorders-recipes-weaponsmithing"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Weaponsmithing** | A list. | (not set) | Global, or each character |
| <span id="setting-workorders-recipes-tailoring"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Tailoring** | A list. | (not set) | Global, or each character |
| <span id="setting-workorders-recipes-shaping"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Shaping** | A list. | (not set) | Global, or each character |
| <span id="setting-workorders-recipes-carving"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Carving** | A list. | (not set) | Global, or each character |
| <span id="setting-workorders-recipes-tinkering"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Tinkering** | A list. | (not set) | Global, or each character |
| <span id="setting-workorders-recipes-remedies"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Remedies** | A list. | (not set) | Global, or each character |
| <span id="setting-workorders-recipes-artificing"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Artificing** | A list. | (not set) | Global, or each character |
| <span id="setting-workorders-carving-material-type"></span>**Carving material family** | Choices: stone, bone. | stone | Global, or each character |
| <span id="setting-workorders-force-heal"></span>**Heal at safe room before starting** | Yes or No. | No | Global, or each character |
| <span id="setting-workorders-retain-crafting-materials"></span>**Keep leftover materials** | Yes or No. | No | Global, or each character |
| <span id="setting-workorders-max-items"></span>**Maximum order size accepted** | A number, at least 1. | 2 | Global, or each character |
| <span id="setting-workorders-min-items"></span>**Minimum order size accepted** | A number, at least 1. | 2 | Global, or each character |
| <span id="setting-workorders-cash-on-hand-platinum"></span>**Platinum kept on hand for stock** | Whole platinum kept on hand for crafting materials. When a crafting script is short it goes to the bank, deposits all, and withdraws this much platinum (more only when one purchase costs more). A number, at least 1. | 1 | Global, or each character |
| <span id="setting-workorders-repair"></span>**Repair tools after each order** | Yes or No. | No | Global, or each character |
| <span id="setting-workorders-repair-own-tools"></span>**Repair with own brush and oil** | Yes or No. | No | Global, or each character |
| <span id="setting-workorders-craft-max-mindstate"></span>**Skip crafting above this mindstate** | A number, at least 0, at most 34. | 34 | Global, or each character |
| <span id="setting-workorders-no-repair-tools"></span>**Tools never sent for repair** | A list. | (not set) | Global, or each character |
| <span id="setting-workorders-diff"></span>**Work order difficulty** | Choose one default for every discipline, then enable only the discipline overrides that should differ. |  | Global, or each character |
| <span id="setting-workorders-diff-default"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **All disciplines** _(required)_ | Choices: challenging, easy, hard. | challenging | Global, or each character |
| <span id="setting-workorders-diff-blacksmithing"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Blacksmithing override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| <span id="setting-workorders-diff-armorsmithing"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Armorsmithing override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| <span id="setting-workorders-diff-weaponsmithing"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Weaponsmithing override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| <span id="setting-workorders-diff-tailoring"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Tailoring override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| <span id="setting-workorders-diff-shaping"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Shaping override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| <span id="setting-workorders-diff-carving"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Carving override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| <span id="setting-workorders-diff-tinkering"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Tinkering override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| <span id="setting-workorders-diff-remedies"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Remedies override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| <span id="setting-workorders-diff-artificing"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Artificing override** | Choices: challenging, easy, hard. | challenging | Global, or each character |
| <span id="setting-workorders-materials"></span>**Work order stock materials** | Stock material bought for each crafting family. Defaults match the original workorders script. |  | Global, or each character |
| <span id="setting-workorders-materials-fabric-type"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Fabric** | Choices: Burlap — 10 yards, Linen — 10 yards, Wool — 10 yards, Silk — 10 yards. | Burlap — 10 yards | Global, or each character |
| <span id="setting-workorders-materials-knit-type"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Knitting material** | Choices: Yarn — 100 yards, Thread — 100 yards. | Yarn — 100 yards | Global, or each character |
| <span id="setting-workorders-materials-metal-type"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Forging metal stock** | Choices: Bronze — 5 volumes, Bronze — 50 volumes, Bronze — 100 volumes, Bronze — 200 volumes, Steel — 10 volumes, Steel — 50 volumes, Steel — 100 volumes, Steel — 200 volumes, Iron — 50 volumes, Iron — 100 volumes, Iron — 200 volumes, Tin — 50 volumes, Tin — 100 volumes. | Bronze — 5 volumes | Global, or each character |
| <span id="setting-workorders-materials-mechanism-ingot-type"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Mechanism metal stock** | Choices: Bronze — 5 volumes, Bronze — 50 volumes, Bronze — 100 volumes, Bronze — 200 volumes, Steel — 10 volumes, Steel — 50 volumes, Steel — 100 volumes, Steel — 200 volumes, Iron — 50 volumes, Iron — 100 volumes, Iron — 200 volumes, Tin — 50 volumes, Tin — 100 volumes. | Bronze — 5 volumes | Global, or each character |
| <span id="setting-workorders-materials-wood-type"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Wood** | Choices: Pine — 5 volumes, Maple — 5 volumes, Balsa — 10 volumes. | Maple — 5 volumes | Global, or each character |
| <span id="setting-workorders-materials-stone-type"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Stone** | Choices: Alabaster — 3 volumes, Granite — 3 volumes, Marble — 3 volumes. | Alabaster — 3 volumes | Global, or each character |
| <span id="setting-workorders-materials-bone-type"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Bone** | Choices: Deer bone — 10 volumes, Wolf bone — 10 volumes. | Wolf bone — 10 volumes | Global, or each character |

## Other Crafting Settings

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-alchemy-herb-quantity"></span>**Forage quantity** | A number, at least 1. | 6 | Global, or each character |
| <span id="setting-alchemy-forage-override-room"></span>**Forage room override** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| <span id="setting-alchemy-forage-type"></span>**Forage style** |  | (not set) | Global, or each character |
| <span id="setting-alchemy-forage-override-town"></span>**Forage town override** |  | (not set) | Global, or each character |
| <span id="setting-alchemy-prep-quantity"></span>**Preparation quantity** | A number, at least 1. | 25 | Global, or each character |
| <span id="setting-alchemy-herb-storage"></span>**Raw herb storage** |  | (not set) | Global, or each character |
| <span id="setting-gear-adjustable-tongs"></span>**Tongs are adjustable (convert to shovel)** | Yes or No. | No | Global, or each character |


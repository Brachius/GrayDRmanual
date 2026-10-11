# Work Orders

Script name: `workorders`

Request, craft, bundle, and turn in crafting-society work orders, exactly like workorders.lic.

## How to start it

Type `.workorders` followed by the words it takes.

Discipline plus optional repair, turnin, or continue (resume the order the logbook is already tracking).

Words it understands: `blacksmithing`, `armorsmithing`, `weaponsmithing`, `tailoring`, `shaping`, `carving`, `tinkering`, `remedies`, `artificing`, `repair`, `turnin`, `continue`.

Example:

```
.workorders tailoring
```

In Master Train, pick **Work Orders** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Crafting](/studio/crafting.md):

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
| <span id="setting-crafting-outfitting-room"></span>**Private outfitting room override** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
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


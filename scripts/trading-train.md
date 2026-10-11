# Trading Training

Script name: `trading-train`

Sells the profit pouches and runs Mags's nuloe-stem task loop. Services the Trader kiosk first when one is configured.

## How to start it

Type `.trading-train` in the game window.

In Master Train, pick **Trading Training** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Trading Training](/studio/trading-train.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-trading-train"></span>**Trader pouch and task training** |  |  | Global, or each character |
| <span id="setting-activities-trading-train-guild"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Guild** _(required)_ |  | Trader | Global, or each character |
| <span id="setting-activities-trading-train-profit-pouch-adjectives"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Profit-pouch adjectives** _(required)_ | A list. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-profit-pouch-containers"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Profit-pouch containers** _(required)_ | A list. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-bags-to-open-and-close"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Loot bags opened and restored** _(required)_ | A list. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-gem-buyer-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Gem buyer room** _(required)_ | A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-gem-buyer-entry"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Gem buyer entry command** _(required)_ |  | go door | Global, or each character |
| <span id="setting-activities-trading-train-mags-name"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Task NPC** _(required)_ |  | mags | Global, or each character |
| <span id="setting-activities-trading-train-mags-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Mags room** _(required)_ | A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-forage-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Nuloe forage room** _(required)_ | A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-combat-abort-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Combat-abort room** _(required)_ | A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-task-container"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Nuloe-stem container** _(required)_ |  | backpack | Global, or each character |
| <span id="setting-activities-trading-train-training-pouch"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Training pouch** _(required)_ |  | suede pouch | Global, or each character |
| <span id="setting-activities-trading-train-training-pouch-source"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Unappraised-pouch container** _(required)_ |  | backpack | Global, or each character |
| <span id="setting-activities-trading-train-training-pouch-processed"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Appraised-pouch container** _(required)_ |  | haversack | Global, or each character |
| <span id="setting-activities-trading-train-finesse-spell"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Finesse spell** _(required)_ | Spell used here, the same block as a Buffs spell. |  | Global, or each character |
| <span id="setting-activities-trading-train-finesse-spell-name"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Spell name** | Full spell name such as Blend or Essence of Yew. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-finesse-spell-mana"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Preparation mana** | Mana placed directly into the spell preparation. For a tattoo enter the tattoo's fixed base mana. A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-finesse-spell-cambrinth"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Cambrinth charge amounts** | Ordered mana amounts charged into the shared Magic cambrinth item before each cast. A list. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-finesse-spell-symbiosis"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Use Symbiosis** | Prepare the selected Symbiosis with this training spell. Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-finesse-spell-tattoo"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Cast from tattoo** | Invoke this spell from a tattoo instead of preparing it normally. Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-finesse-spell-abbrev"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Custom abbreviation** _(advanced)_ | Optional spell abbreviation override. Leave unset to derive it from packaged spell data. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-finesse-spell-use-auto-mana"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Use automatic mana** _(advanced)_ | Advanced legacy option. The persistent trainer normally requires this to remain No. Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-finesse-spell-ritual"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Ritual spell** _(advanced)_ | Mark a ritual spell that requires ritual preparation behavior. Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-finesse-spell-runestone"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Runestone** _(advanced)_ | Exact runestone item used to cast this spell. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-enabled"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Trader kiosk - keep a kiosk up and sell through it** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Kiosk room (a cast MOVES the kiosk here)** | A number, at least 1. | 2030017 | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-markup"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Kiosk markup percent (5 percent steps from -10 to 80)** | A number, at least -10, at most 80. | -10 | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-reserve-plats"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Kiosk platinum Kronars to keep in reserve** | A number, at least 0. | 200 | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-refill-threshold-plats"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Kiosk top-up only when the reserve is short by more than this many plats** | A number, at least 0. | 0 | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-bank-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Kiosk bank room for Kronars (Crossing)** | A number, at least 1. | 19104 | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-refresh-when-below-minutes"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Kiosk refresh when fewer minutes than this remain** | A number, at least 5. | 60 | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-tessera-container"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Container the tessera lives in** |  | backpack | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-furrier-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Furrier room for crystalline bundles** | A number, at least 1. | 2014542 | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-spell"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Kiosk spell (Prosperity in Absentia)** | Spell used here, the same block as a Buffs spell. |  | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-spell-name"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Spell name** | Full spell name such as Blend or Essence of Yew. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-spell-mana"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Preparation mana** | Mana placed directly into the spell preparation. For a tattoo enter the tattoo's fixed base mana. A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-spell-cambrinth"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Cambrinth charge amounts** | Ordered mana amounts charged into the shared Magic cambrinth item before each cast. A list. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-spell-symbiosis"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Use Symbiosis** | Prepare the selected Symbiosis with this training spell. Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-spell-tattoo"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Cast from tattoo** | Invoke this spell from a tattoo instead of preparing it normally. Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-spell-abbrev"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Custom abbreviation** _(advanced)_ | Optional spell abbreviation override. Leave unset to derive it from packaged spell data. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-spell-use-auto-mana"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Use automatic mana** _(advanced)_ | Advanced legacy option. The persistent trainer normally requires this to remain No. Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-spell-ritual"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Ritual spell** _(advanced)_ | Mark a ritual spell that requires ritual preparation behavior. Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-trading-train-kiosk-spell-runestone"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **Runestone** _(advanced)_ | Exact runestone item used to cast this spell. | (not set) | Global, or each character |


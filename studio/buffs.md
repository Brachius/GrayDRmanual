# Buffs

Configuration Studio page **Buffs**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

The Barbarian abilities activated for training, and the Buffs pre-hunt choices.

Scripts that read these settings: [Barbarian Magic](/scripts/barb-magic.md), [Combat Trainer](/scripts/combat-trainer.md).

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-barb-magic"></span>**Barbarian training abilities** |  |  | Global, or each character |
| <span id="setting-activities-barb-magic-abilities"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Abilities in activation order** _(required)_ | A list. | (not set) | Global, or each character |
| <span id="setting-activities-barb-magic-sit-to-meditate"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Sit for meditations** | Yes or No. | No | Global, or each character |
| <span id="setting-magic-buff-configuration"></span>**Buff configuration** | The one shared buff list used by the Buffs activity, pre-hunt buffing, and Combat Trainer's in-combat buff maintenance. |  | Global, or each character |
| <span id="setting-magic-buff-configuration-inner-fire-threshold"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Inner Fire threshold** | Minimum Inner Fire percentage before Barbarian non-spell buffs are attempted. A number, at least 0. | (not set) | Global, or each character |
| <span id="setting-magic-buff-configuration-sets"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Buff sets** | Named buff lists. A spell buff fills in mana/recast/cambrinth as needed; a Barbarian ability is just its name with everything else left unset. A table of name and value pairs (value: Buff set). | (not set) | Global, or each character |
| <span id="setting-activities-buffing-room"></span>**Buffing room** | Room used whenever scripts travel somewhere to apply buffs, including pre-hunt buffing. Enter a GrayDR room UID or configured name such as safe_room or magic_room. Must be a room on the map. | (blank) | Global, or each character |
| <span id="setting-barb-buffs-inner-fire-threshold"></span>**Barbarian buff inner-fire minimum** _(Barbarian only)_ | Combat waits until the Barbarian has at least this much inner fire before activating abilities from the shared Buffs list, leaving enough reserve for their ongoing costs. | (not set) | Global, or each character |
| <span id="setting-buff-spell-mana-threshold"></span>**In-combat buff mana minimum** | Combat waits until mana reaches this percentage before refreshing spells from the shared Buffs list. | (not set) | Global, or each character |
| <span id="setting-osrel-amount"></span>**Osrel Meraud infusion mana** _(Cleric only)_ | Mana infused into Osrel Meraud during upkeep. This setting is used only by Clerics. A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-osrel-mana-threshold"></span>**Osrel Meraud mana threshold** _(Cleric only)_ | Wait until personal mana is above this percentage before infusing Osrel Meraud during combat. A number, at least 0, at most 100. | (not set) | Global, or each character |
| <span id="setting-osrel-no-harness"></span>**Skip harnessing for Osrel Meraud** _(Cleric only)_ | Choose Yes to infuse Osrel Meraud without first harnessing mana. Choose No to harness the configured infusion amount. Yes or No. | (not set) | Global, or each character |
| <span id="setting-osrel-favor-god"></span>**Osrel Meraud favor deity** _(Cleric only)_ | Exact deity or aspect whose favor orb is consumed to create Osrel Meraud. This is separate from the general favor deity; Master Train obtains a new orb for this deity when needed. | (not set) | Global, or each character |


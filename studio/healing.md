# Healing

Configuration Studio page **Healing**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Healing routes and the Empath's plant, First Aid charts, Healme, Medic Check, Rezz and the safe room.

Scripts that read these settings: [First Aid](../scripts/first-aid.md), [Healme](../scripts/healme.md), [Medic Check](../scripts/medic-check.md), [Rezz](../scripts/rezz.md), [Safe Room Healing](../scripts/safe-room.md).

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Anatomy compendium noun** | Exact noun used when textbook mode is disabled. | compendium | Global, or each character |
| **Anatomy textbook noun** | Exact noun used in GET, OPEN, TURN, and STUDY commands. | textbook | Global, or each character |
| **Bleeding partner character** | When set, skip chart study and run Tendother on this character for ten seconds. | (not set) | Global, or each character |
| **Bleeding partner room** | Stable GrayDR room ID used only when a bleeding partner is configured. A number, at least 1. Must be a room on the map. | (not set) | Global, or each character |
| **Effective Scholarship modifier** | Subtract this value from Scholarship rank when selecting eligible charts. Leave unset to use the normal rank scaling. | (not set) | Global, or each character |
| **Empath medic routine** |  |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Guild** _(required)_ |  | Empath | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Empath plant room** _(required)_ | Room where the vela'tohr plant is kept. Patients come here and the plant is tended here. A number, at least 1. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing room** _(required)_ | A number, at least 1. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Patients in priority order** _(required)_ | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing spell set** _(required)_ |  | medic_check | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Recovery spell set** _(required)_ |  | medic_recovery | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Plant spell set** _(required)_ |  | medic_plant | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Plant recast interval** | A number, at least 1, at most 120. | 5 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Stop plant health score** | A number, at least 1. | 250 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Resume plant health score** | A number, at least 0. | 100 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Fountain health score** | A number, at least 1. | 250 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum vitality percent** | A number, at least 1, at most 100. | 70 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum mana percent** | A number, at least 0, at most 100. | 40 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Medic cast settings** _(required)_ |  |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **use_harness_when_arcana_locked** | Yes or No. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **custom_spell_prep** |  | (not set) | Global, or each character |
| **Empath plant room** | Room number or room name where the Empath keeps the vela'tohr plant. Hospital healing goes there first and falls back to Quentin. Leave blank to go straight to Quentin. Must be a room on the map. | (blank) | Global, or each character |
| **Empath self-healing** |  |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum vitality percent** | A number, at least 0, at most 100. | 60 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum wound severity** | A number, at least 0, at most 13. | 0 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Wounds tended while preparing** | A number, at least 0. | 1 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Wounds healed between perceives** | A number, at least 1. | 3 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Debug output** | Yes or No. | No | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing spells** _(required)_ | A table of name and value pairs. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing cast settings** _(required)_ |  |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **use_harness_when_arcana_locked** | Yes or No. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **custom_spell_prep** |  | (not set) | Global, or each character |
| **Healing plant adjectives** | Semicolon-delimited adjectives. | vela'tohr; swaying | Global, or each character |
| **Healing plant nouns** | Semicolon-delimited nouns. | briar; bush; plant; shrub; thicket; thornbush | Global, or each character |
| **Maximum charts per run** | Study at most this many eligible charts, from hardest to easiest. A number, at least 0. | 25 | Global, or each character |
| **Rezz** |  |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Resurrection mana (also the infuse amount at full mana)** | A number, at least 5, at most 50. | 30 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Rejuvenation mana (the nimbus colour follows the mana; 40 reached silver)** | A number, at least 5, at most 100. | 40 | Global, or each character |
| **Safe-room healing policy** |  |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Character guild** _(required)_ |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Wound score threshold** | A number, at least 0. | 7 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **PC Empath room** | A number, at least 0. | 0 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Preferred PC Empath** |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Items dropped in the exchange room** | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Items retrieved from the exchange room** | A list. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Try a divine charm first** | Yes or No. | No | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Send Necromancers to NPC healing** | Yes or No. | No | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Use Devour for Necromancer healing** | Yes or No. | No | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Stored material container** |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Devour mana threshold** | A number, at least 0, at most 100. | 40 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **NPC-healing platinum** | Whole platinum on hand before visiting the NPC healer. When short: bank, deposit all, withdraw this much platinum. A number, at least 1. | 1 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **NPC Empath room** | A number, at least 1. | 2014200 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing bank room** | A number, at least 1. | 2014101 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Bank NPC** |  | Dokoras | Global, or each character |
| **Separate First Aid instrument** | When set, First Aid does not start the Performance script. Leave unset to play the zills while studying (they are cleaned first when they need it). | (not set) | Global, or each character |
| **Study Tome while healing** | Yes or No. | No | Global, or each character |
| **Use anatomy textbook** | Use the configured textbook. When disabled, use a compendium. Yes or No. | Yes | Global, or each character |


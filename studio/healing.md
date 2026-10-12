# Healing

Configuration Studio page **Healing**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Healing routes and the Empath's plant, First Aid charts, Healme, Medic Check, Rezz and the safe room.

Scripts that read these settings: [First Aid](/scripts/first-aid.md), [Healme](/scripts/healme.md), [Medic Check](/scripts/medic-check.md), [Rezz](/scripts/rezz.md), [Safe Room Healing](/scripts/safe-room.md).

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-first-aid-compendium-type"></span>**Anatomy compendium noun** | Exact noun used when textbook mode is disabled. | compendium | Global, or each character |
| <span id="setting-activities-first-aid-textbook-type"></span>**Anatomy textbook noun** | Exact noun used in GET, OPEN, TURN, and STUDY commands. | textbook | Global, or each character |
| <span id="setting-activities-first-aid-bleed-bot"></span>**Bleeding partner character** | When set, skip chart study and run Tendother on this character for ten seconds. | (not set) | Global, or each character |
| <span id="setting-activities-first-aid-bleed-bot-room"></span>**Bleeding partner room** | Stable GrayDR room ID used only when a bleeding partner is configured. A number, at least 1. Must be a room on the map. | (not set) | Global, or each character |
| <span id="setting-activities-first-aid-scholarship-modifier"></span>**Effective Scholarship modifier** | Subtract this value from Scholarship rank when selecting eligible charts. Leave unset to use the normal rank scaling. | (not set) | Global, or each character |
| <span id="setting-activities-medic-check"></span>**Empath medic routine** |  |  | Global, or each character |
| <span id="setting-activities-medic-check-guild"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Guild** _(required)_ |  | Empath | Global, or each character |
| <span id="setting-activities-medic-check-healing-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing room** _(required)_ | Where patients are healed and the Empath recovers. The plant room is the Healing page's Empath plant room (one field for Medic Check, Medic Plant and hospital healing; Josh 2026-10-11). A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-activities-medic-check-patients"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Patients in priority order** _(required)_ | A list. | (not set) | Global, or each character |
| <span id="setting-activities-medic-check-healing-waggle-set"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing spell set** _(required)_ |  | medic_check | Global, or each character |
| <span id="setting-activities-medic-check-recovery-waggle-set"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Recovery spell set** _(required)_ |  | medic_recovery | Global, or each character |
| <span id="setting-activities-medic-check-plant-waggle-set"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Plant spell set** _(required)_ |  | medic_plant | Global, or each character |
| <span id="setting-activities-medic-check-plant-recast-roisaen"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Plant recast interval** | A number, at least 1, at most 120. | 5 | Global, or each character |
| <span id="setting-activities-medic-check-plant-max-health-score"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Stop plant health score** | A number, at least 1. | 250 | Global, or each character |
| <span id="setting-activities-medic-check-plant-resume-health-score"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Resume plant health score** | A number, at least 0. | 100 | Global, or each character |
| <span id="setting-activities-medic-check-plant-foc-health-score"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Fountain health score** | A number, at least 1. | 250 | Global, or each character |
| <span id="setting-activities-medic-check-plant-min-vitality-percent"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum vitality percent** | A number, at least 1, at most 100. | 70 | Global, or each character |
| <span id="setting-activities-medic-check-mana-threshold"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum mana percent** | A number, at least 0, at most 100. | 40 | Global, or each character |
| <span id="setting-activities-medic-check-cast"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Medic cast settings** _(required)_ |  |  | Global, or each character |
| <span id="setting-activities-medic-check-cast-use-harness-when-arcana-locked"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **use_harness_when_arcana_locked** | Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-medic-check-cast-custom-spell-prep"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **custom_spell_prep** |  | (not set) | Global, or each character |
| <span id="setting-activities-empath-plant-room"></span>**Empath plant room** | Room number or room name where the Empath keeps the vela'tohr plant. Hospital healing goes there first and falls back to Quentin. Leave blank to go straight to Quentin. Must be a room on the map. | (blank) | Global, or each character |
| <span id="setting-activities-healme"></span>**Empath self-healing** |  |  | Global, or each character |
| <span id="setting-activities-healme-health-threshold"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum vitality percent** | A number, at least 0, at most 100. | 60 | Global, or each character |
| <span id="setting-activities-healme-severity-threshold"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum wound severity** | A number, at least 0, at most 13. | 0 | Global, or each character |
| <span id="setting-activities-healme-max-wounds-to-tend-while-prep-spells"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Wounds tended while preparing** | A number, at least 0. | 1 | Global, or each character |
| <span id="setting-activities-healme-max-wounds-to-heal-between-perceives"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Wounds healed between perceives** | A number, at least 1. | 3 | Global, or each character |
| <span id="setting-activities-healme-debug"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Debug output** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-healme-spells"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing spells** _(required)_ | A table of name and value pairs. | (not set) | Global, or each character |
| <span id="setting-activities-healme-cast"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing cast settings** _(required)_ |  |  | Global, or each character |
| <span id="setting-activities-healme-cast-use-harness-when-arcana-locked"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **use_harness_when_arcana_locked** | Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-healme-cast-custom-spell-prep"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **custom_spell_prep** |  | (not set) | Global, or each character |
| <span id="setting-activities-healing-plant-adjectives"></span>**Healing plant adjectives** | Semicolon-delimited adjectives. | vela'tohr; swaying | Global, or each character |
| <span id="setting-activities-healing-plant-nouns"></span>**Healing plant nouns** | Semicolon-delimited nouns. | briar; bush; plant; shrub; thicket; thornbush | Global, or each character |
| <span id="setting-activities-first-aid-number-of-charts"></span>**Maximum charts per run** | Study at most this many eligible charts, from hardest to easiest. A number, at least 0. | 25 | Global, or each character |
| <span id="setting-activities-rezz"></span>**Rezz** |  |  | Global, or each character |
| <span id="setting-activities-rezz-rezz-mana"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Resurrection mana (also the infuse amount at full mana)** | A number, at least 5, at most 50. | 30 | Global, or each character |
| <span id="setting-activities-rezz-rejuv-mana"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Rejuvenation mana (the nimbus colour follows the mana; 40 reached silver)** | A number, at least 5, at most 100. | 40 | Global, or each character |
| <span id="setting-activities-safe-room-healing"></span>**Safe-room healing policy** |  |  | Global, or each character |
| <span id="setting-activities-safe-room-healing-guild"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Character guild** _(required)_ |  | (not set) | Global, or each character |
| <span id="setting-activities-safe-room-healing-health-threshold"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Wound score threshold** | A number, at least 0. | 7 | Global, or each character |
| <span id="setting-activities-safe-room-healing-pc-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **PC Empath room** | A number, at least 0. | 0 | Global, or each character |
| <span id="setting-activities-safe-room-healing-pc-empath"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Preferred PC Empath** |  | (not set) | Global, or each character |
| <span id="setting-activities-safe-room-healing-give-items"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Items dropped in the exchange room** | A list. | (not set) | Global, or each character |
| <span id="setting-activities-safe-room-healing-take-items"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Items retrieved from the exchange room** | A list. | (not set) | Global, or each character |
| <span id="setting-activities-safe-room-healing-use-divine-charm"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Try a divine charm first** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-safe-room-healing-force-necromancer"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Send Necromancers to NPC healing** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-safe-room-healing-use-devour"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Use Devour for Necromancer healing** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-safe-room-healing-harvest-container"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Stored material container** |  | (not set) | Global, or each character |
| <span id="setting-activities-safe-room-healing-devour-mana-threshold"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Devour mana threshold** | A number, at least 0, at most 100. | 40 | Global, or each character |
| <span id="setting-activities-safe-room-healing-withdraw-platinum"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **NPC-healing platinum** | Whole platinum on hand before visiting the NPC healer. When short: bank, deposit all, withdraw this much platinum. A number, at least 1. | 1 | Global, or each character |
| <span id="setting-activities-safe-room-healing-npc-healer-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **NPC Empath room** | A number, at least 1. | 2014200 | Global, or each character |
| <span id="setting-activities-safe-room-healing-npc-bank-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing bank room** | A number, at least 1. | 2014101 | Global, or each character |
| <span id="setting-activities-safe-room-healing-npc-bank-name"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Bank NPC** |  | Dokoras | Global, or each character |
| <span id="setting-activities-first-aid-instrument-name"></span>**Separate First Aid instrument** | When set, First Aid does not start the Performance script. Leave unset to play the zills while studying (they are cleaned first when they need it). | (not set) | Global, or each character |
| <span id="setting-activities-tome-while-healing"></span>**Study Tome while healing** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-first-aid-use-textbook"></span>**Use anatomy textbook** | Use the configured textbook. When disabled, use a compendium. Yes or No. | Yes | Global, or each character |


# Magic

Configuration Studio page **Magic**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Everything spellcasting scripts share: cambrinth, harnessing, the ritual focus, the training spell for each magic skill, the buff list, and the Astrology trainer's settings.

Scripts that read these settings: [Astrology Training](../scripts/astrology.md), [Scroll Manage](../scripts/scroll-manage.md), [Summoning Training](../scripts/summoning.md), [Walking Astrology](../scripts/walkingastro.md).

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Analyze the divination tool after every prediction** | Only useful for prediction tracking; no in-game benefit. Yes or No. | No | Global, or each character |
| **Astral plane training (circle 100+)** | Moongate travel between two astral-plane locations for the "ways" task. Needs the bescort companion script, not yet ported. |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Home location (bescort ways name)** |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Training destination (bescort ways name)** |  | (not set) | Global, or each character |
| **Astrology training tasks** | Tasks cycled in order until Astrology is mind-locked. Choices are observe, rtr, weather, events, attunement, ways. A list. | observe, rtr, weather, attunement | Global, or each character |
| **Cambrinth capacity** | Maximum mana the configured cambrinth item can hold. Every spellcasting script uses this same capacity. A number, at least 0. | 0 | Global, or each character |
| **Cambrinth item** | The exact item name every spellcasting script uses when charging and invoking cambrinth. Leave blank to cast without cambrinth. | (blank) | Global, or each character |
| **Cambrinth stored in container** | Choose Yes when this character keeps the cambrinth item in a container instead of wearing it. Casting and combat scripts then get the cambrinth before charging and put it away after invoking. Choose No when the cambrinth is worn. Yes or No. | No | Global, or each character |
| **Divination bones storage** | Where the bones live when they are used for predictions (leave blank for none). |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Container** |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Tied to (item name)** |  | (not set) | Global, or each character |
| **Divination tool** | Charts, bones, mirror, bowl, or prism used for predictions (leave the name blank for none). |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Tool name (adjective + noun)** |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Container it lives in** |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Tied to the container** | Yes or No. | No | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Worn instead of stored** | Yes or No. | No | Global, or each character |
| **Do not observe while these scripts run** | Script names that must not be interrupted by a telescope observation. A list. | alchemy, astrology, athletics, bescort, burgle, buff, carve, combat-trainer, craft, enchant, faskinner, first-aid, forge, go2, hunting-buddy, mech-lore, performance, pick, remedy, safe-room, sew, shape, smelt, smith, steal, study-art, tinker, workorders | Global, or each character |
| **Force cambrinth use** | Choose Yes to use configured cambrinth charges even when the spell could be prepared without them. Yes or No. | No | Global, or each character |
| **Force predict future** | Use "predict future" even when a divination tool or bones are configured. Yes or No. | No | Global, or each character |
| **Harness when Arcana is locked** | Choose Yes to allow spellcasting scripts to harness mana when Arcana can no longer gain experience. Yes or No. | No | Global, or each character |
| **Invoke exact amount** | Choose Yes to invoke only the amount requested by the spell instead of draining all mana held by the cambrinth item. Yes or No. | No | Global, or each character |
| **Mana harnessing** | Choose Yes to let the scripts harness mana and send RELEASE MANA. Choose No (the default) and no script harnesses or releases mana; the harness settings below and in the hunt then do nothing. Yes or No. | No | Global, or each character |
| **Pool level needed to predict** | Minimum understanding level (0-10) a pool needs before the trainer predicts from it. Ignored when full pools are required. A number, at least 0, at most 10. | 1 | Global, or each character |
| **Predict even when Astrology is above mind state 25** | Keeps predicting for passive tool bonding; pair with partial pools off. Yes or No. | No | Global, or each character |
| **Predict from partial pools** | Predict as soon as an observation adds to a pool, not only when the pool is full. Yes or No. | No | Global, or each character |
| **Predict only from full pools** | Require a complete (level 10) understanding of a pool before predicting from it. Yes or No. | No | Global, or each character |
| **Predict with the divination tool or bones** | Use the configured divination bones or tool (Astrology page) for predictions instead of "predict future". Yes or No. | No | Global, or each character |
| **Ritual focus** | The one item every ritual spell is focused through (Embrace of the Vela'Tohr, Perseverance of Peri'el, Bloodthorns, Read the Ripples, Persistence of Mana). Buffs, magic training, healing and the hunt all use it. Leave the noun blank to cast rituals without a focus. |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Adjective** | The item's adjective, for example platinum. Leave blank when it has none. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Noun** | The item's noun, for example owl. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Stored in container** | No: the item is worn (remove, invoke, wear). Yes: it is kept in a container (get, invoke, stow). Yes or No. | No | Global, or each character |
| **Runestone storage container** | Exact adjective and noun of the container holding runestones. | (blank) | Global, or each character |
| **Scroll spells to keep** | One spell per row, by its exact name or its abbreviation (for example Ethereal Shield or ES). A scroll for a spell in this list is stacked in the white folio, then the black folio when the white one is full. Every other scroll goes in the bucket. An empty list refuses to sort at all, so nothing is thrown away by accident. A list. | (not set) | Global, or each character |
| **Startup delay (seconds)** | Seconds to wait before the first observation, so the script can start with the others. A number, at least 0. | 0 | Global, or each character |
| **Summoning maximum mindstate** | Never train Summoning past this mind state, whatever the increment says. A number, at least 0, at most 34. | 28 | Global, or each character |
| **Summoning target increment** | How many mind states Summoning should gain in one run before the step ends. A number, at least 1, at most 34. | 17 | Global, or each character |
| **Utility, Warding, Sorcery, and Augmentation training** | Configure one training spell for each magic skill. Open a named trainer to edit its normal fields; uncommon controls stay under Advanced options. |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Training room** | GrayDR room UID or configured room name used by all three magic trainers, such as safe_room or magic_room. Leave blank to retain the current compatibility room. Must be a room on the map. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Mana threshold** _(advanced)_ | Wait until personal mana reaches this percentage before the next training cast. A number, at least 0, at most 100. | 40 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Concentration threshold** _(advanced)_ | Wait until concentration reaches this percentage before the next training cast. A number, at least 0, at most 100. | 80 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Harness when Arcana is locked** _(advanced)_ | Allow these trainers to harness mana after Arcana can no longer gain experience. Yes or No. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Custom preparation command** _(advanced)_ | Advanced replacement for the normal PREPARE command for these trainers. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Release buff set after** _(advanced)_ | The one trainer that releases the "Cast before" buff set when it finishes; the other trainers leave the buffs up. Only spells showing in Active Spells are released (a fissure is not). Leave unset to release nothing. Choices: Utility, Warding, Sorcery, Augmentation. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Release before training** | Spells every magic trainer (utility, ward, sorcery, aug) releases at its start when Active Spells shows them, before its buffs and first cast. A listed spell that is not up is skipped. Use it for wards or other spells the training spell cannot stack with. A list of spell names. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Training spells** | One spell configuration for each trainer. The internal Utility, Warding, Sorcery, and Augmentation keys are supplied automatically; aug-train uses the Augmentation entry. A table of name and value pairs. | (not set) | Global, or each character |


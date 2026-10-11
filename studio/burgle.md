# Burgle

Configuration Studio page **Burgle**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Burgling homes: the starting room, how to get in, what to search, what to keep, and where the loot goes.

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-burgle-room"></span>**Burgle starting room** | Native GrayDR room number where BURGLE is started. A number, at least 0, at most 999999999. | 0 | Each character |
| <span id="setting-activities-burgle-entry"></span>**Burgle entry method** | lockpick, rope, cycle, prioritylockpick, or priorityrope. | prioritylockpick | Each character |
| <span id="setting-activities-burgle-use-lockpick-ring"></span>**Use lockpick ring for Burgle** | Use the configured worn lockpick ring for lockpick entry. Turn off to retrieve a loose lockpick instead. Yes or No. | Yes | Each character |
| <span id="setting-activities-burgle-rope-adjective"></span>**Burgle rope adjective** | Adjective used for rope entry. | heavy | Each character |
| <span id="setting-activities-burgle-loot-container"></span>**Burgle loot container** | Container used before leaving the burgled home. | (blank) | Each character |
| <span id="setting-activities-burgle-loot-action"></span>**Burgle loot action** | pawn, keep, drop, bin, or trashcan. | pawn | Each character |
| <span id="setting-activities-burgle-max-searches"></span>**Burgle maximum searches** | Maximum SEARCH commands per caper. A number, at least 0, at most 20. | 2 | Each character |
| <span id="setting-activities-burgle-max-priority-mindstate"></span>**Burgle priority mindstate** | Priority entry methods favor their named skill through this mindstate. A number, at least 0, at most 34. | 26 | Each character |
| <span id="setting-activities-burgle-safe-mode"></span>**Burgle safe mode** | Stop searching immediately when warning footsteps are heard. Yes or No. | Yes | Each character |
| <span id="setting-activities-burgle-retry"></span>**Retry empty Burgle searches** | Retry a room search that did not produce loot, within the search limit. Yes or No. | No | Each character |
| <span id="setting-activities-burgle-stealth-inside"></span>**Use stealth inside Burgle homes** | Re-hide before each search and sneak while advancing through the home. Yes or No. | Yes | Each character |
| <span id="setting-activities-burgle-room-blacklist"></span>**Burgle room blacklist** | Semicolon-separated room names not to search. | (blank) | Each character |
| <span id="setting-activities-burgle-item-whitelist"></span>**Burgle keep list** | Semicolon-separated loot descriptions always kept. | (blank) | Each character |
| <span id="setting-activities-burgle-prioritize-rooms"></span>**Burgle priority rooms** | Semicolon-separated, case-sensitive room names to search first. | (blank) | Each character |
| <span id="setting-activities-burgle-room-priority-type"></span>**Burgle room priority order** | any uses discovery order; inorder uses the configured order. | any | Each character |
| <span id="setting-activities-burgle-pawn-room"></span>**Burgle pawnshop room override** | Optional native GrayDR destination used when Burgle loot action is pawn. Leave blank or 0 to use the pawnshop from the current service area. A number, at least 0, at most 999999999. | 0 | Each character |
| <span id="setting-activities-burgle-bin-room"></span>**Burgle thief-bin room override** | Optional native GrayDR destination used when Burgle loot action is bin. Leave blank or 0 to use the current service area's thief bin; only a live Thief can use it. A number, at least 0, at most 999999999. | 0 | Each character |
| <span id="setting-activities-burgle-worn-trashcan"></span>**Burgle worn trashcan** | Worn trash container used by the trashcan loot action. | (blank) | Each character |
| <span id="setting-activities-burgle-worn-trashcan-verb"></span>**Burgle trashcan activation verb** | Required for trashcan loot; applied twice after placing loot in the worn trashcan. | (blank) | Each character |


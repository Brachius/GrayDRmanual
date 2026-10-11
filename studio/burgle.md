# Burgle

Configuration Studio page **Burgle**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Burgling homes: the starting room, how to get in, what to search, what to keep, and where the loot goes.

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Burgle starting room** | Native GrayDR room number where BURGLE is started. A number, at least 0, at most 999999999. | 0 | Each character |
| **Burgle entry method** | lockpick, rope, cycle, prioritylockpick, or priorityrope. | prioritylockpick | Each character |
| **Use lockpick ring for Burgle** | Use the configured worn lockpick ring for lockpick entry. Turn off to retrieve a loose lockpick instead. Yes or No. | Yes | Each character |
| **Burgle rope adjective** | Adjective used for rope entry. | heavy | Each character |
| **Burgle loot container** | Container used before leaving the burgled home. | (blank) | Each character |
| **Burgle loot action** | pawn, keep, drop, bin, or trashcan. | pawn | Each character |
| **Burgle maximum searches** | Maximum SEARCH commands per caper. A number, at least 0, at most 20. | 2 | Each character |
| **Burgle priority mindstate** | Priority entry methods favor their named skill through this mindstate. A number, at least 0, at most 34. | 26 | Each character |
| **Burgle safe mode** | Stop searching immediately when warning footsteps are heard. Yes or No. | Yes | Each character |
| **Retry empty Burgle searches** | Retry a room search that did not produce loot, within the search limit. Yes or No. | No | Each character |
| **Use stealth inside Burgle homes** | Re-hide before each search and sneak while advancing through the home. Yes or No. | Yes | Each character |
| **Burgle room blacklist** | Semicolon-separated room names not to search. | (blank) | Each character |
| **Burgle keep list** | Semicolon-separated loot descriptions always kept. | (blank) | Each character |
| **Burgle priority rooms** | Semicolon-separated, case-sensitive room names to search first. | (blank) | Each character |
| **Burgle room priority order** | any uses discovery order; inorder uses the configured order. | any | Each character |
| **Burgle pawnshop room override** | Optional native GrayDR destination used when Burgle loot action is pawn. Leave blank or 0 to use the pawnshop from the current service area. A number, at least 0, at most 999999999. | 0 | Each character |
| **Burgle thief-bin room override** | Optional native GrayDR destination used when Burgle loot action is bin. Leave blank or 0 to use the current service area's thief bin; only a live Thief can use it. A number, at least 0, at most 999999999. | 0 | Each character |
| **Burgle worn trashcan** | Worn trash container used by the trashcan loot action. | (blank) | Each character |
| **Burgle trashcan activation verb** | Required for trashcan loot; applied twice after placing loot in the worn trashcan. | (blank) | Each character |


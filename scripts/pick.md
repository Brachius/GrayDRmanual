# Lockbox Picking

Script name: `pick`

Disarms and picks the boxes from the configured box sources, walking to the picking room first when one is set. Words: `refill` (only refill the lockpicks), `all` (ignore mind lock), `stand`, `quick`, `normal`, `careful` or `blind` (the assumed difficulty), `source=container`, `debug`.

## How to start it

Type `.pick` in the game window.

In Master Train, pick **Pick** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Locksmithing](../studio/locksmithing.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Assumed picking difficulty** | Optional quick normal or careful mode that skips trap and lock difficulty identification. A script argument overrides this value; leave blank to identify normally. | (blank) | Global, or each character |
| **Balance lockpick container** | Choose Yes to balance mixed loose lockpicks in the configured ring or container during picking. Yes or No. | No | Global, or each character |
| **Blacklisted box container** | Container where Pick places boxes carrying a blacklisted trap. Leave blank to use ordinary discard handling. | (blank) | Global, or each character |
| **Bulk-fill box gems** | Choose Yes to bulk-fill the worn box-picking pouch before individual special-loot handling. When No Pick still bulk-fills if no special-loot destinations are configured. Yes or No. | No | Global, or each character |
| **Disarm careful threshold** | Trap difficulty at or above this value uses CAREFUL. A number, at least 0, at most 16. | 5 | Global, or each character |
| **Disarm normal threshold** | Lowest trap difficulty disarmed without a speed modifier. A number, at least 0, at most 16. | 2 | Global, or each character |
| **Dismantling style** | Optional word appended to DISMANTLE after an emptied box such as salvage. Leave blank to use the game's ordinary dismantling action. | (blank) | Global, or each character |
| **Financed gemshop NPC override** | Optional gem buyer name for replacement box-picking pouches. Leave blank to use the NPC at the closest reachable financed gem shop. | (blank) | Global, or each character |
| **Financed gemshop room override** | Optional native GrayDR room UID for replacement box-picking pouches. Leave blank or 0 to use the closest reachable financed gem shop. A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| **Harvest trap components** | Choose Yes to harvest reusable components from successfully disarmed traps before opening the box. Yes or No. | No | Global, or each character |
| **Lockpick refill NPC override** | Optional locksmith name used in status text. Leave blank to use the NPC from the resolved current-town service record. | (blank) | Global, or each character |
| **Lockpick service town override** | Optional town-name override. Leave blank to resolve the nearest coherent town service area from the current room; the selected town supplies the bank currency lockpick shop NPC and prices. | (blank) | Global, or each character |
| **Lockpick shop room override** | Optional native GrayDR room UID for the locksmith. Leave blank or 0 to use the resolved current-town locksmith. A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| **Lockpick type override** | Optional exact lockpick style sold by the resolved locksmith. Leave blank to use that town's ordinary default; Pick reports the resolved town when an override is unavailable. | (blank) | Global, or each character |
| **Pick careful threshold** | Lock difficulty at or above this value uses CAREFUL. A number, at least 0, at most 16. | 7 | Global, or each character |
| **Pick normal threshold** | Lowest lock difficulty picked without a speed modifier. A number, at least 0, at most 16. | 4 | Global, or each character |
| **Picking buff bot character** | Character name asked for the configured picking buff before box work. Leave blank to make no remote request. | (blank) | Global, or each character |
| **Picking buff request** | Request token sent to the picking buff character; used only when a buff-bot character is configured. | hol | Global, or each character |
| **Refill bank room override** | Optional native GrayDR room UID used to withdraw lockpick money. Leave blank or 0 to use the bank and currency from the same resolved service town. A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| **Skeleton key item** | Exact adjective and noun of the skeleton key Pick should use. Leave blank when skeleton-key use is disabled. | (blank) | Global, or each character |
| **Skip lockpick refill** | Choose Yes to prevent Pick from buying lockpicks after a run or when started with the refill argument. Yes or No. | No | Global, or each character |
| **Tend own wounds** | Choose Yes to let Pick tend wounds caused by trap work when its normal safety checks permit. Yes or No. | No | Global, or each character |
| **Too-hard box container** | Container where Pick places boxes above the configured trap-difficulty cutoff. Leave blank to use ordinary discard handling. | (blank) | Global, or each character |
| **Trap blacklist** | Semicolon-delimited trap names. | (blank) | Global, or each character |
| **Trap component container** | Exact container receiving harvested trap components. Leave blank when trap harvesting is disabled. | (blank) | Global, or each character |
| **Trap greylist** | Semicolon-delimited trap names. | (blank) | Global, or each character |
| **Trash empty boxes** | Choose Yes to put dismantled or emptied boxes into the configured trash container instead of normal disposal. Yes or No. | No | Global, or each character |
| **Use lockpick ring or stacker** | Choose Yes to pick directly from the configured worn lockpick ring or stacker. Choose No to retrieve loose lockpicks from the configured container. Yes or No. | Yes | Global, or each character |
| **Use skeleton key** | Choose Yes to try the configured skeleton key before ordinary lockpicks. Yes or No. | No | Global, or each character |
| **Use Thief GLANCE** | Optional override for using GLANCE to skip trap and lock identification. Leave unset to enable it automatically for a Thief of circle 13 or higher. Yes or No. | (not set) | Global, or each character |


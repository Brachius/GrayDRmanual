# First Aid

Script name: `first-aid`

Train First Aid and Scholarship from anatomy charts.

## How to start it

Type `.first-aid` followed by the words it takes.

Leave blank for First Aid, or choose Scholarship or Both.

Words it understands: `scholarship`, `both`.

In Master Train, pick **First Aid** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Healing](../studio/healing.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Anatomy compendium noun** | Exact noun used when textbook mode is disabled. | compendium | Global, or each character |
| **Anatomy textbook noun** | Exact noun used in GET, OPEN, TURN, and STUDY commands. | textbook | Global, or each character |
| **Bleeding partner character** | When set, skip chart study and run Tendother on this character for ten seconds. | (not set) | Global, or each character |
| **Bleeding partner room** | Stable GrayDR room ID used only when a bleeding partner is configured. A number, at least 1. Must be a room on the map. | (not set) | Global, or each character |
| **Effective Scholarship modifier** | Subtract this value from Scholarship rank when selecting eligible charts. Leave unset to use the normal rank scaling. | (not set) | Global, or each character |
| **Maximum charts per run** | Study at most this many eligible charts, from hardest to easiest. A number, at least 0. | 25 | Global, or each character |
| **Separate First Aid instrument** | When set, First Aid does not start the Performance script. Leave unset to play the zills while studying (they are cleaned first when they need it). | (not set) | Global, or each character |
| **Use anatomy textbook** | Use the configured textbook. When disabled, use a compendium. Yes or No. | Yes | Global, or each character |


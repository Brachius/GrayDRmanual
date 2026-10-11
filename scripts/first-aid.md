# First Aid

Script name: `first-aid`

Trains First Aid, Scholarship or both from anatomy charts: it gets the textbook (or the compendium when **Use anatomy textbook** is off), opens it, turns to the hardest charts you can learn from and studies them, up to **Maximum charts per run**. The zills play while you study unless **Separate First Aid instrument** says otherwise. With a **Bleeding partner** set it skips the charts and tends that character instead.

```
.first-aid
.first-aid scholarship
.first-aid both
```

The book nouns and the chart count are on the Healing page under First Aid. It stops at mind lock. The warning about First Aid learning poorly is only printed during a named hunt, never on the main hunt.

## How to start it

Type `.first-aid` with the words shown above.

Words it understands: `scholarship`, `both`.

In Master Train, pick **First Aid** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Healing](/studio/healing.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-first-aid-compendium-type"></span>**Anatomy compendium noun** | Exact noun used when textbook mode is disabled. | compendium | Global, or each character |
| <span id="setting-activities-first-aid-textbook-type"></span>**Anatomy textbook noun** | Exact noun used in GET, OPEN, TURN, and STUDY commands. | textbook | Global, or each character |
| <span id="setting-activities-first-aid-bleed-bot"></span>**Bleeding partner character** | When set, skip chart study and run Tendother on this character for ten seconds. | (not set) | Global, or each character |
| <span id="setting-activities-first-aid-bleed-bot-room"></span>**Bleeding partner room** | Stable GrayDR room ID used only when a bleeding partner is configured. A number, at least 1. Must be a room on the map. | (not set) | Global, or each character |
| <span id="setting-activities-first-aid-scholarship-modifier"></span>**Effective Scholarship modifier** | Subtract this value from Scholarship rank when selecting eligible charts. Leave unset to use the normal rank scaling. | (not set) | Global, or each character |
| <span id="setting-activities-first-aid-number-of-charts"></span>**Maximum charts per run** | Study at most this many eligible charts, from hardest to easiest. A number, at least 0. | 25 | Global, or each character |
| <span id="setting-activities-first-aid-instrument-name"></span>**Separate First Aid instrument** | When set, First Aid does not start the Performance script. Leave unset to play the zills while studying (they are cleaned first when they need it). | (not set) | Global, or each character |
| <span id="setting-activities-first-aid-use-textbook"></span>**Use anatomy textbook** | Use the configured textbook. When disabled, use a compendium. Yes or No. | Yes | Global, or each character |


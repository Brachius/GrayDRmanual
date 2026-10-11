# Locksmithing

Script name: `locksmithing`

Trains Locksmithing on boxes you own: the daily training box and the consumable keepsake and jewelry boxes, which it takes in the order set under **Locksmithing training boxes** on the Locksmithing page (consumables first when that is ticked). Lockpicks come from the **Lockpick holder**. Loot from a consumable box goes in the loot container named there. It stops at mind lock. `.locksmithing once` picks a single box, which the combat scripts use between fights.

## How to start it

Type `.locksmithing` followed by the words it takes.

Use once to perform one trainer pick for combat-training integration.

Example:

```
.locksmithing once
```

In Master Train, pick **Locksmithing** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Locksmithing](/studio/locksmithing.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-locksmithing"></span>**Locksmithing training boxes** |  |  | Global, or each character |
| <span id="setting-activities-locksmithing-training-box-list"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Daily training boxes** | A list. | (not set) | Global, or each character |
| <span id="setting-activities-locksmithing-consumable-lockboxes"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Consumable training boxes** | A list. | (not set) | Global, or each character |
| <span id="setting-activities-locksmithing-prioritize-consumable-lockboxes"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Use consumable boxes first** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-locksmithing-pick-live-boxes"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Pick live boxes before training** | Yes or No. | Yes | Global, or each character |
| <span id="setting-activities-locksmithing-picking-worn-lockbox"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Daily boxes are worn** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-locksmithing-use-lockpick-ring"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Use a worn lockpick ring** | Yes or No. | Yes | Global, or each character |
| <span id="setting-activities-locksmithing-sell-loot"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Sell loot after live boxes** | Yes or No. | Yes | Global, or each character |
| <span id="setting-activities-locksmithing-safe-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Return room after selling** | A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-activities-locksmithing-loot-container"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Consumable-box container** |  | (not set) | Global, or each character |


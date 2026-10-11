# Safe Room Healing

Script name: `safe-room`

Select configured PC Empath, self-healing, NPC, or Necromancer healing routes.

## How to start it

Type `.safe-room` followed by the words it takes.

Use skip to remain in the current room or force to run healing logic without visible wounds.

Example:

```
.safe-room force
```

In Master Train, pick **Safe Room Healing** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Healing](../studio/healing.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
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


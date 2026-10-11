# Astrology Training

Script name: `astrology`

Train Moon Mage Astrology by observing the heavens, predicting from full pools, and running Read the Ripples, exactly like astrology.lic.

## How to start it

Type `.astrology` followed by the words it takes.

Optional "rtr" runs only the Read the Ripples vision cycle.

Example:

```
.astrology rtr
```

In Master Train, pick **Astrology training** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Magic](../studio/magic.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Astral plane training (circle 100+)** | Moongate travel between two astral-plane locations for the "ways" task. Needs the bescort companion script, not yet ported. |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Home location (bescort ways name)** |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Training destination (bescort ways name)** |  | (not set) | Global, or each character |
| **Astrology training tasks** | Tasks cycled in order until Astrology is mind-locked. Choices are observe, rtr, weather, events, attunement, ways. A list. | observe, rtr, weather, attunement | Global, or each character |
| **Divination bones storage** | Where the bones live when they are used for predictions (leave blank for none). |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Container** |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Tied to (item name)** |  | (not set) | Global, or each character |
| **Divination tool** | Charts, bones, mirror, bowl, or prism used for predictions (leave the name blank for none). |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Tool name (adjective + noun)** |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Container it lives in** |  | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Tied to the container** | Yes or No. | No | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Worn instead of stored** | Yes or No. | No | Global, or each character |
| **Force predict future** | Use "predict future" even when a divination tool or bones are configured. Yes or No. | No | Global, or each character |
| **Pool level needed to predict** | Minimum understanding level (0-10) a pool needs before the trainer predicts from it. Ignored when full pools are required. A number, at least 0, at most 10. | 1 | Global, or each character |
| **Predict only from full pools** | Require a complete (level 10) understanding of a pool before predicting from it. Yes or No. | No | Global, or each character |


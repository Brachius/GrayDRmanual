# Astrology Training

Script name: `astrology`

Moon Mage Astrology: cycles the tasks under **Astrology training tasks** on the Magic page (observe, rtr, weather, events, attunement, ways) until Astrology reaches mind state 32, predicting from every pool that is ready after each pass. Observing uses the telescope from the Combat page settings; predicting uses the divination tool or bones from the Magic page when **Predict with the divination tool or bones** is on. `.astrology rtr` only casts Read the Ripples and observes its visions.

## How to start it

Type `.astrology` followed by the words it takes.

Optional "rtr" runs only the Read the Ripples vision cycle.

Example:

```
.astrology rtr
```

In Master Train, pick **Astrology training** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Magic](/studio/magic.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-astral-plane-training"></span>**Astral plane training (circle 100+)** | Moongate travel between two astral-plane locations for the "ways" task. Needs the bescort companion script, not yet ported. |  | Global, or each character |
| <span id="setting-activities-astral-plane-training-train-source"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Home location (bescort ways name)** |  | (not set) | Global, or each character |
| <span id="setting-activities-astral-plane-training-train-destination"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Training destination (bescort ways name)** |  | (not set) | Global, or each character |
| <span id="setting-activities-astrology-training"></span>**Astrology training tasks** | Tasks cycled in order until Astrology is mind-locked. Choices are observe, rtr, weather, events, attunement, ways. A list. | observe, rtr, weather, attunement | Global, or each character |
| <span id="setting-activities-divination-bones-storage"></span>**Divination bones storage** | Where the bones live when they are used for predictions (leave blank for none). |  | Global, or each character |
| <span id="setting-activities-divination-bones-storage-container"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Container** |  | (not set) | Global, or each character |
| <span id="setting-activities-divination-bones-storage-tied"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Tied to (item name)** |  | (not set) | Global, or each character |
| <span id="setting-activities-divination-tool"></span>**Divination tool** | Charts, bones, mirror, bowl, or prism used for predictions (leave the name blank for none). |  | Global, or each character |
| <span id="setting-activities-divination-tool-name"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Tool name (adjective + noun)** |  | (not set) | Global, or each character |
| <span id="setting-activities-divination-tool-container"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Container it lives in** |  | (not set) | Global, or each character |
| <span id="setting-activities-divination-tool-tied"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Tied to the container** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-divination-tool-worn"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Worn instead of stored** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-astrology-force-visions"></span>**Force predict future** | Use "predict future" even when a divination tool or bones are configured. Yes or No. | No | Global, or each character |
| <span id="setting-activities-astrology-pool-target"></span>**Pool level needed to predict** | Minimum understanding level (0-10) a pool needs before the trainer predicts from it. Ignored when full pools are required. A number, at least 0, at most 10. | 1 | Global, or each character |
| <span id="setting-activities-astrology-use-full-pools"></span>**Predict only from full pools** | Require a complete (level 10) understanding of a pool before predicting from it. Yes or No. | No | Global, or each character |


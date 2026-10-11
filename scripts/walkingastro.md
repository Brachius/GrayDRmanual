# Walking Astrology

Script name: `walkingastro`

Astrology on the side while you hunt or craft: about every three and a half minutes, or when the last observation is pondered, it buffs, takes the telescope out, centres it on a constellation for the time of day, peers, and predicts when a pool is full. Runs until you stop it with `.k walkingastro`. The scripts it must never interrupt are listed under **Do not observe while these scripts run** on the Magic page. `debug` prints each decision.

## How to start it

Type `.walkingastro` followed by the words it takes.

Optional "debug" prints the toggle states and each decision.

Example:

```
.walkingastro debug
```

In Master Train, pick **Walking astrology** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Magic](/studio/magic.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-walkingastro-analyze-divination-tool"></span>**Analyze the divination tool after every prediction** | Only useful for prediction tracking; no in-game benefit. Yes or No. | No | Global, or each character |
| <span id="setting-activities-walkingastro-no-use-scripts"></span>**Do not observe while these scripts run** | Script names that must not be interrupted by a telescope observation. A list. | alchemy, astrology, athletics, bescort, burgle, buff, carve, combat-trainer, craft, enchant, faskinner, first-aid, forge, go2, hunting-buddy, mech-lore, performance, pick, remedy, safe-room, sew, shape, smelt, smith, steal, study-art, tinker, workorders | Global, or each character |
| <span id="setting-activities-walkingastro-predict-regardless-of-mindstate"></span>**Predict even when Astrology is above mind state 25** | Keeps predicting for passive tool bonding; pair with partial pools off. Yes or No. | No | Global, or each character |
| <span id="setting-activities-walkingastro-use-partial-pools"></span>**Predict from partial pools** | Predict as soon as an observation adds to a pool, not only when the pool is full. Yes or No. | No | Global, or each character |
| <span id="setting-activities-walkingastro-use-tools"></span>**Predict with the divination tool or bones** | Use the configured divination bones or tool (Astrology page) for predictions instead of "predict future". Yes or No. | No | Global, or each character |
| <span id="setting-activities-walkingastro-startup-delay"></span>**Startup delay (seconds)** | Seconds to wait before the first observation, so the script can start with the others. A number, at least 0. | 0 | Global, or each character |


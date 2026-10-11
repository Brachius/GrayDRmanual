# Performance

Script name: `performance`

Plays your worn instrument (**Performance worn instrument**, normally zills) until Performance reaches the goal. It cleans the instrument with the cleaning cloth when the game says it is dirty or damp, and takes off the hand armor named on the Performance page when a held instrument is used.

```
.performance
.performance 25
.performance noclean
.performance checksong
```

The number is the mind state to stop at, 1 to 34; without one, **Performance mindstate goal** is used. `noclean` skips the cleaning, `checksong` only checks which song is playing and stops.

## How to start it

Type `.performance` followed by the words it takes.

Choose a mindstate goal from 1 to 34. noclean and checksong are also available.

Words it understands: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`, `15`, `16`, `17`, `18`, `19`, `20`, `21`, `22`, `23`, `24`, `25`, `26`, `27`, `28`, `29`, `30`, `31`, `32`, `33`, `34`, `noclean`, `checksong`.

Example:

```
.performance 31
```

In Master Train, pick **Performance** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Performance](/studio/performance.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-performance-hand-armor"></span>**Hand armor to remove** | Required only when a held instrument is configured. | (blank) | Global, or each character |
| <span id="setting-activities-performance-held-instrument"></span>**Held instrument** | Optional instrument that must be removed and held to play. | (blank) | Global, or each character |
| <span id="setting-activities-performance-while-healing"></span>**Perform while healing** | Yes or No. | No | Global, or each character |


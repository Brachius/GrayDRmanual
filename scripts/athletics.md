# Athletics

Script name: `athletics`

Trains Athletics to a goal and comes back. The route is the **Athletics route** setting or the word you type: `wyvern`, `xalas`, `undergondola` or `cliffs` climb that route; `stationary` practises in place with the rope (**Carry a climbing rope** and its adjective are on the Athletics page); with no word and the route on auto, it picks by your ranks (cliffs under 540, wyvern above). Below 850 ranks the undergondola is not the best choice and it says so.

```
.athletics
.athletics wyvern
.athletics max
.athletics stationary skip_magic
```

Without `max` the goal is 15 mind states up, capped at 29; `max` goes to 32 of 34. `skip_magic` skips the buffs first. Between passes it checks for stuns, bleeding and the AFK emergency exit, never mid-pass. What you hold while climbing is listed under **Athletics held items**; it is taken out first and stowed after.

## How to start it

Type `.athletics` with the words shown above.

Words it understands: `max`, `stationary`, `skip_magic`, `wyvern`, `xalas`, `undergondola`, `cliffs`.

In Master Train, pick **Athletics** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Athletics](/studio/athletics.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-athletics-town"></span>**Athletics town** |  | (blank) | Global, or each character |
| <span id="setting-activities-athletics-avoid-justice"></span>**Avoid justice areas** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-athletics-have-climbing-rope"></span>**Carry a climbing rope** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-athletics-climbing-rope-adjective"></span>**Climbing rope adjective** |  | climbing | Global, or each character |
| <span id="setting-activities-athletics-climbing-target"></span>**Climbing target** |  | practice rope | Global, or each character |
| <span id="setting-activities-athletics-outdoorsmanship-rooms"></span>**Outdoorsmanship room IDs** | Semicolon-delimited stable room IDs. | (blank) | Global, or each character |
| <span id="setting-activities-athletics-swimming-target"></span>**Swimming target** |  | river | Global, or each character |


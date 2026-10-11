# AFK Monitor

Configuration Studio page **AFK Monitor**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

What the AFK Monitor does when the character is left alone: the vitality line that logs out, departing after death, and how many justice complaints are allowed. The monitor never sends beside another script; when it must act it stops the others first.

Scripts that read these settings: [AFK Monitor](../scripts/afk.md).

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Depart automatically after death** | Yes or No. | No | Global, or each character |
| **Depart command type** |  | item | Global, or each character |
| **Justice complaints before logout** | A number, at least 0. | 4 | Global, or each character |
| **Vitality/spirit logout threshold** | Under this vitality or spirit percent the AFK Monitor stops every other script and logs out. While a Hunt with its own Stop hunting below vitality is running, the Hunt leaves combat instead and the AFK Monitor stands down until the hunt is over. A number, at least 0, at most 100. | 0 | Global, or each character |


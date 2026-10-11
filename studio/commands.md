# Commands

Configuration Studio page **Commands**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

How a typed line becomes a script run: the dot prefix, the names that work without it, and your own short words.

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Script prefix** | Typing this prefix before a name runs that script (for example .master-train). Leave empty to disable. | . | Global |
| **Bare commands** | Space-separated script names that run without the prefix, like game commands (default: go2). Pick names the game will never use; remove a name here if the game ever claims it. | go2 | Global |
| **Bare-word aliases** | Semicolon-separated name=expansion pairs. Typing the bare name runs the full expansion (for example spot=go2 2030; home=go2 10028). | (blank) | Global |


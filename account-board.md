# Account Board

The Account Board is one window that shows every character at a glance. It reads the session logs GrayDR writes; it never touches the game or the GrayDR windows, so it can stay open all day and costs nothing.

Open it with **Launch Account Board**.

## What you see

One tile per character. Each tile shows:

- **Connected** or **DISCONNECTED**, with how long since the last game traffic. A window that is open but silent says so ("NO TRAFFIC for ...", "frozen or dropped?").
- **Doing**: the Master Train activity in progress, or "no master-train activity in the recent log".
- **Last command**: the last thing sent to the game and when.
- **Warnings**, **Errors**, **Fatal (a script died)**, **Disconnects and reconnects**: counts of what the log has recorded since the character logged in.

The window title line says when the board last read the logs and how many characters are connected.

## Controls

| Control | What it does |
|---|---|
| Update | Reads the logs again now. |
| Auto-update every N s | Reads them on a timer. |
| Notifications | On a tile: opens that character's kept warnings, errors, script deaths and disconnects. The button says how many are new. Inside: Delete selected, Copy selected, Copy all, Clear. |
| Clear all notifications | Empties every character's kept list. |
| Hide | On a tile: takes that character off the board. The **Hidden** menu shows "Show X again" for each hidden one. |

Hidden characters and the auto-update setting are remembered beside your profile, so they survive a new package.

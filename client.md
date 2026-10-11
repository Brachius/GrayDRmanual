# The GrayDR window

One window per character. The big pane is the story window: every line from the game is painted the moment it arrives, in order, and every command you type is echoed when it is sent. Nothing is held back or grouped.

## Menus

**File**

| Item | What it does |
|---|---|
| Connect | Opens the connection wizard. |
| Connect from SAL (with Lich)... | Connects through Lich from a Simutronics launch file. |
| Disconnect | Drops the game connection. Nothing reconnects after this. |
| Run Engine Lua... | Picks a script file by hand and runs it. Normal scripts are started by typing their name; this is for a file that is not in the scripts folder. |
| Stop Engine Lua | Stops the script started that way. |
| Exit | Closes this window. |

**Settings**

| Item | What it does |
|---|---|
| Highlight Text | Colour, sound and timer rules for lines you want to notice. Tabs: General, Text, Timer, Alert. A highlight can match the whole row, the start of a line, a regular expression, part of a word, and can ignore case. Alert plays a sound. Timer starts a countdown when the line appears. The Alert tab also has sounds for health below a level, death, stun, bleeding and webbed. |
| Window Appearance | Fonts and colours for the main window, the dock windows and the command line. |
| Alter Text | Three lists: Substitute replaces text as it arrives, Link turns text into something you can click, Ignore hides lines. Each entry can be switched on and off. |
| Configuration Studio | Every GrayDR and script setting. See [Configuration Studio](/studio.md). |

**Window**

| Item | What it does |
|---|---|
| Save Layout | Saves where the side windows are. |
| Lock Windows | Stops the side windows from being dragged. |
| Sessions Launcher... | The saved logins. See [Getting started](/getting-started.md). |
| Main-Thread Profiler Log | A timing log for diagnosing a slow interface. Leave it off unless asked. |

**Profile**: Create Profile and Load Profile. **Help**: User Guide (this manual) and About.

## Side windows

Each one can be dragged to where you like, and the layout is kept with Save Layout.

| Window | Shows |
|---|---|
| Room | The room name, description, things and people here, and the exits. |
| Thoughts | Thoughts, and chat from the LNet network when it is connected. |
| Experience | Every skill with its rank and mind state. |
| Conversations | Speech and whispers. |
| Spells | Active spells with their time left. |
| Active Scripts | Every script running in this window. "No GrayDR scripts running" when idle. |
| Arrivals, Deaths, Atmospherics, Combat, Familiar, Group | The game's own streams of that kind. |

Right-click the story window for **Copy**, **Appearance**, and **Unstuck**. Unstuck clears a jammed command queue; use it when GrayDR stops sending what you type.

## The map picture

Type `.map` to open the community map picture for the area you are in. You are drawn on it when the map knows your room, and clicking a room on the picture walks you there.

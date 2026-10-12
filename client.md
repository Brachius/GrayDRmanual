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

## The map window

Type `.map` to open the map for the area you are in. It opens beside the game and follows you as you walk. You are ringed on it, and clicking any room walks you there. You do not have to hit the tiny square: a click near a room counts, and the pointing hand shows whenever you are close enough.

**Dragging.** Drag the map to slide it. It stays where you leave it; only moving to a new room centres it on you again. **Where I am** brings it back to your room.

**Typing.** Keys typed with the map in front go to the game, so `n` and Enter walk you without clicking back on the game window.

**The next map.** The **Next:** row under the buttons has one button per map that joins the one on show. Press one to see that map, whole, then click a room on it to walk there. The same maps also appear as small yellow boxes beside the rooms whose exits lead onto them, where the data knows the spot; hover one for the map's name. The window comes back to your own map, at full size, when you arrive, or when you press Where I am.

**Dashed squares.** A dashed square near your room is a place the artist drew but the community data never recorded: a cottage yard behind "go gate", a stable, a shop. Only the ones one move from where you stand are shown, so the picture stays clean, and they follow you as you walk. The square starts on the side the exit points, which usually lands on the artist's block. Clicking it walks you there like any other square. If it missed the block, drag it onto the block and GrayDR remembers the spot for every character from then on (the file is `logs\map-room-boxes.json`). Standing in such a room keeps you on the same map, ringed on its dashed square.

**Areas with no picture.** About a quarter of the game has no community picture. There the window draws its own map from the travel data: one square per room, lines for the exits, and the move written on the line when it is not a plain direction (`climb ladder`, `go gate`, `up`). Hover a square for its name. Rooms on the edge of the drawing that belong to a picture are outlined yellow with the picture's name beside them; click the name to open that picture. The **Drawn** button shows this drawn version even where a picture exists.

**Blue and grey rooms.** Water rooms are blue and dark rooms are grey. The map data knows neither, so GrayDR learns them from the game: a line starting "You wade", "You splash" or "You swim" marks the room you arrive in as water, the lazy-circles answer to a bare `swim` marks the room you are in, and the darkness line marks the room you then light up and look at. Blue squares on the community pictures are read as water too. The marks live in one file shared by every character, so a room one character has waded into shows blue for all of them.

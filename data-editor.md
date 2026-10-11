# Data Editor

The Data Editor edits the game facts the scripts rely on: spells and the lines that prove a cast worked, hunting zones, the answers the game gives to commands, crafting tool lists, and the travel map. Open it with **Launch Data Editor**.

Scripts read these files the next time they start. Nothing is written until you press **SAVE CHANGES** (Ctrl+S); a changed tab is marked with a star. **Reload** (F5) reads the files again and drops unsaved changes. Every save keeps a backup copy of the file it replaces.

On every tab except Map: the list on the left holds the entries; **New...**, **Rename...** and **Delete** manage them; the search box finds names and lines; double-click a row to change it. Names must be in small letters.

## Spells

Every spell a script may cast. A spell that is not here stops the script that tries to cast it, because it has nothing to recognise.

For each spell: the guild, the skill it trains, the abbreviation PREPARE takes, the default mana, the mana type, whether it is prepared or targeted, when a buff is recast, and the game lines:

- **Lines that mean the cast worked**: the line the game prints when the spell lands. Keep only the part that stays the same.
- **Lines seen when recast while still up**, **Failure lines of this spell only**, **Lines meaning it cannot work in this hunting area**, and the **Wear-off line**.

Flags: cast at a creature, cyclic, ritual, harmless, metaspell, fired by the game by itself, **Release after training** (the magic trainers release it at the end; needs a wear-off line), and the **Release word** when the spell's name does not work for RELEASE.

Two more lists on this tab: **Abilities (Barbarian)** (forms, berserks and meditations, with the command that starts each and the line that shows it started and ended) and **Khri names (Thief)**, plus **Add-on lines** for symbiosis and orb links.

## Hunting zones

Each zone is a name and a list of room numbers, in the order the hunt tries them. Use the zone name in a character's hunting settings exactly as written. A zone name may hold letters, digits, _ and - only.

## Command answers

For every game command a script sends: the lines that mean it worked, the lines that mean the game refused, the lines that ask for it to be sent again to confirm, and whether silence is a real answer. A command whose answer is not here stops the script that sent it. Paste the game line; for several, one per row.

## Zasele keep list

For the Hollow Eve Zasele tasks: the materials to keep, who holds each material family, and the deed words asked for.

## Crafting tools

For each craft, the tools it needs and the tools used only if the character owns them. The Notes list is for your own reference.

## Map

The Map tab fixes travel without anyone's help. Use the **Show** box to pick a section.

### Problems

Every link that failed during a walk, grouped by link, with how many times it failed, when, which character hit it, the command the walker sent and what the game answered. For each one:

- **Fix with this command**: type the command that works (in game words, like `go gate` or `climb wall`) and the link is corrected.
- **Bench this link**: travel stops using it.
- **Ignore**: the failures are forgotten.
- **Another chance**: a link that was benched earlier is put back in play.

### Links

Change or add any link by hand. Pick the **From room** and **To room** by number or by a word from the name, type the **Link command**, and **Add link** or **Change this link**. The **Requires** row names what the move needs, in one of two shapes: `Athletics at least 100` (a skill and the rank), or `Citizenship is Zoluren` (a fact that must match). **Dark room** marks the arrival room as one that needs a light to show its exits. A room the map does not have yet is added with the link.

### Walks

Rows recorded while you walked with `.automap` on. Each row is one move: the room you left, every command you sent between the two rooms, the room you arrived in with its name and exits, and how many times the game answered darkness on the way.

The box **The room arrived in is dark (needs a light)** is ticked for you when the walk had a darkness answer and the last command was not a move, which is what a dark room looks like when you walk in, light up, and the room appears. Tick or untick it yourself if the recorder got it wrong.

**Link command** starts out holding every command from the row, joined by semicolons. Before you add the row, cut it down to the move alone: the light, look and snuff commands you typed are in there too, and whatever is in the box becomes the link. A row that caught a stray command from a running script is trimmed the same way.

**Add to map** puts the move on the map as a link, adds the room if it is new, and marks it dark when the box is ticked. **Drop** forgets the row.

### Crossings

A crossing is a move with a wait or an answer in it. Pick the kind, fill in the commands and the game's own lines, give it a name like `shard-ferry-north`, and **Add this crossing**: the block is written to the crossings file and the link between the two rooms points at it.

| Kind | Fields |
|---|---|
| Ferry or barge | Board command, the line when you are aboard, the line when the boat is away, the line when it pulls in, the line when the ride is over, the exit command, whether the game puts you off by itself, longest wait in minutes. |
| Search, then go | First command (search, open armoire), the line when the way is open, the move command. |
| Gate, guard or toll | Move command, the line when you pass, the line when you are refused and one word for why (citizenship, fare, guild), an optional second-try command and the line that asks for it. |
| Slow passage | Move command, the line when you arrive, longest wait in seconds. |

### Apply

Saves everything, then rebuilds the travel map and puts it into every GrayDR package. GrayDR must be closed first; Apply refuses while a game window or Engine Host is running. It takes a minute or two and writes a report, map-report.txt, in the package folder, saying what went in and what was refused.

## Mapping a new area

1. Carry a light, but keep it out. Type `.automap` in the game window.
2. Walk the area by hand, one exit at a time, every exit you want on the map.
3. When a move answers with darkness, you are in a dark room: light your light so the room appears (that is what records it, exits and all, with the dark mark), then put the light out before you move on. Never walk with the light lit, or dark rooms go on the map as ordinary ones.
4. Type `.automap stop`.
5. Close GrayDR. Open the Data Editor, Map tab, **Walks**. For each row, cut the link command down to the move itself, check the dark box, and add it; drop the rows you do not want.
6. If a move needs a skill, open **Links**, pick the link, fill in **Requires**, and change it.
7. If a move is a ferry, a searched entrance, a gate or a slow passage, make it a crossing under **Crossings**.
8. Press **Apply**. Read map-report.txt. Start GrayDR.

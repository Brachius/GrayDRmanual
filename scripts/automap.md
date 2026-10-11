# automap

Script name: `automap`

Records the moves you make by hand so the Data Editor can put them on the travel map, dark rooms included. Nothing is sent to the game.

- `.automap` starts recording from the room you are in.
- `.automap status` says how many moves are recorded so far, how many were through the dark, and how many commands are waiting since the last room.
- `.automap stop` ends it and says what was recorded.

**How to walk an area.** Have a way to make light, but keep it off. Walk one exit at a time. In a lit room the recorder notes the move you sent, the room you arrived in, its name and its exits.

When a move answers with darkness, you are in a dark room. Light up however you do it (a lantern, a gaethzen orb, a spell), then type `look` (or just `l`). The look is what shows the room, and that is the moment the recorder writes it down: its number, its name, its exits, and a mark that it is a dark room. Put the light out, then take the next exit. Do not walk around lit: a lit room never answers with darkness, so the recorder would write it down as an ordinary room.

Each move becomes one row on the Data Editor's Map tab, under Walks, where **Add all** puts the whole walk on the map in one go; the editor keeps the move and drops the light and look commands by itself. See [Data Editor, Walks](/data-editor.md#walks).

## How to start it

Type `.automap` in the game window.

## Settings

This script has no settings of its own. Shared pages such as [Character](/studio/character.md), [Magic](/studio/magic.md) and [Crafting](/studio/crafting.md) may still apply.

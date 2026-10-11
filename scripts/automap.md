# automap

Script name: `automap`

Records the moves you make by hand so the Data Editor can put them on the travel map, dark rooms included. Nothing is sent to the game.

- `.automap` starts recording from the room you are in.
- `.automap status` says how many moves are recorded so far, how many were through the dark, and how many commands are waiting since the last room.
- `.automap stop` ends it and says what was recorded.

**How to walk an area.** Carry a light but keep it out. Walk one exit at a time. In a lit room the recorder notes the move you sent, the room you arrived in, its name and its exits.

When a move answers with darkness ("You will need a light source" or the like), you are in a dark room. Light your light: the room now appears, and the recorder writes it down with its exits and a mark that it was reached through the dark. Put the light out before you move on, so the next dark room answers with darkness too. Do not walk around with the light lit: a lit light hides the darkness answer, and a dark room then goes on the map as an ordinary room.

Each move becomes one row on the Data Editor's Map tab, under Walks. A row holds every command sent between the two rooms, so the light and look commands are in it beside the move. See [Data Editor, Walks](/data-editor.md#walks).

## How to start it

Type `.automap` in the game window.

## Settings

This script has no settings of its own. Shared pages such as [Character](/studio/character.md), [Magic](/studio/magic.md) and [Crafting](/studio/crafting.md) may still apply.

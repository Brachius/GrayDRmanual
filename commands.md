# Typed commands

Everything you type goes to the game, except lines that start with a dot. A dot line goes to GrayDR.

## Starting scripts

Type a dot, the script's name, and any words it takes:

```
.workorders tailoring
.buffs hunt
.go2 bank
```

`go2` also works without the dot, because it is listed under **Bare commands** on the Studio's Commands page. You can list more script names there, and you can give a word of your own a meaning under **Bare-word aliases** (for example `home=go2 10028`, so typing `home` walks home).

Adding the word `cascade` after a script's name starts it on every logged-in character at once, with the remaining words as its arguments:

```
.deed-sort cascade
.buffs cascade hunt
```

## Stopping and listing

| Type | What happens |
|---|---|
| `.list` | Lists the scripts running in this window. `.list all` includes the hidden helper scripts. |
| `.k name`, `.kill name`, `.stop name` | Stops that one script at once. |
| `.k` with no name | Stops the walk in progress and go2; with no walk running, stops the script started most recently. |
| `.k travel` | Stops the walk in progress only. |
| `.ka`, `.killall`, `.stopall` | Stops every script and any walk at once. Scripts marked no-kill-all in `.list` survive. |
| `.kd` | Like `.ka`, but stops the no-kill-all scripts too. |
| `.gk name` | Graceful stop: the script finishes what it is in the middle of, puts things back, and ends. |
| `.gka` | Graceful stop for every script in this window. |
| `.gka master-train` | Master Train finishes its current activity completely, then everything winds down. |
| `.gka cascade` | Graceful stop on every logged-in character. |
| `.quit` | Logs this character out. `.quit close` also closes the window. `.quit cascade` logs everyone out; `.quit cascade close` closes every window too. |

A stop from `.gk` or `.gka` is the safe one: a crafting script finishes the piece, a hunt leaves combat and re-wears its gear. `.k` is the emergency stop.

## Master Train

Master Train runs your whole training routine, card by card, as set up on the Studio's Master Train page.

| Type | What happens |
|---|---|
| `.master-train` or `.master-train run` | Resumes the saved routine from where it stopped. |
| `.master-train fresh` | Starts the routine from the first card. |
| `.master-train 4` | Starts at card 4 and continues from there. |
| `.master-train list` | Lists every card with its number. |
| `.master-train status` | Says what it is doing, which card, which cycle. |
| `.master-train skip` | Skips the current card at the next safe moment. |
| `.master-train stop` | Stops it. |
| `.master-train reset` | Forgets the saved position; the next run starts at card 1. |
| `.master-train handoff-test` | For the giver in a handoff pair: one test handoff with a full or spare pouch. |
| `.master-train automana` | For each magic trainer in the routine, raises the spell's mana until it backfires, settles one below, and saves it. Needs empty hands. |
| `.master-train help` | Prints this list in the window. |

## Other dot commands

| Type | What happens |
|---|---|
| `.map` | Opens the map picture for your area. A word after it is ignored for now. |
| `.automap` | Starts recording your hand walk for the Data Editor's Map tab. `.automap stop` ends it, `.automap status` says what is recorded so far. See [Data Editor](/data-editor.md#walks). |
| `.logger` | Says which logs are on. `.logger normal on`, `.logger error off`, `.logger debug on` switch them. `.logger open` opens the log folder. `.logger path` shows it; `.logger path C:\somewhere` moves it. |
| `.chat connect`, `.chat disconnect` | Joins or leaves the LNet chat network. Chat appears in the Thoughts window. |
| `.chat who` | Who is on. |
| `.chat to Name message` | A private message. `::Name message` is the short form. |
| `.chat reply message` | Answers the last private message. |
| `.chat tune channel`, `.chat untune channel` | Joins or leaves a channel. |
| `.chat password word` | Reserves this character's name on LNet. Put the same word in the Studio's **Chat: LNet password** field afterwards. |
| `.memory` | Prints what is using memory in this window. |
| `.testdc` | Drops the game link on purpose, to test automatic reconnect. |
| `.weargear` | Puts the standard gear set back on from wherever the pieces are. `.weargear name` uses another set. |
| `.validate` | Checks this character's whole configuration against the data files and prints every value that cannot be right. Sends nothing to the game. |
| `.plat 30 dok` | Converts an amount between Dokoras, Kronars and Lirums. Sends nothing to the game. |
| `.lichroom` | Shows this room's Lich map number, or converts a number either way. |

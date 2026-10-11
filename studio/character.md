# Character

Configuration Studio page **Character**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Who this character is and how GrayDR treats the connection: home town, citizenship, subscription, the safe room and named rooms, the trash bin, automatic reconnect, and LNet chat.

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Preferred home town** | Home town used by travel and town activities for this character. Choices: Not set, Arthe Dale, Crossing, Knife Clan, Darkling Wood, Dirge, Fayrin's Rest, Chyolvea, Leth Deriel, Shard, Steelclaw Clan, Stone Clan, Tiger Clan, Wolf Clan, Riverhaven, Rossman's Landing, Therenborough, Langenfirth, Fornsted, Hvaral, Ratha, Aesry, Mer'Kresh, Throne City, Hibarnhvidar, Raven's Point, Boar Clan, Fang Cove, Muspar'i, Ain Ghazal, Hara'jaal. | (blank) | Each character |
| **Safe room** | Character-wide GrayDR room UID used whenever a script or Master Train entry refers to safe_room. A number, at least 0, at most 999999999. Must be a room on the map. | 0 | Each character |
| **Named rooms** | Define reusable names for GrayDR room UIDs. Enter a name such as enchanting_room here once, then use that name in any Master Train Room field. Built-in names such as safe_room, magic_room, engineering_room, outfitting_room, and picking_room resolve from their existing settings without being repeated here. A table of name and value pairs (value: GrayDR room UID). | (not set) | Each character |
| **Trash bin room** | Room number of the room with the trash bin, for example 2026011. Scripts walk there to throw things away; the first use is memory orbs that could not be used. Leave at 0 for none. Set this together with the trash bin name. A number, at least 0, at most 999999999. | 0 | Each character |
| **Trash bin name** | What the trash bin in that room is called, as the game takes it in PUT MY ORB IN <name>, for example bucket. | (blank) | Each character |
| **Subscription tier** | Account type used by travel, banking, selling, and training. Choices: F2P, Standard, Premium. | Standard | Each character |
| **Prime client controls at login** | Run wrayth-prime automatically at login. It sends the Wrayth/StormFront client controls that unlock the game's larger typeahead queue, then exits. No gameplay commands are sent. Turn this off only to run a login without the larger queue. Yes or No. | Yes | Each character |
| **Print experience gains** | Print a line in the story window each time a skill's mind state goes up, such as First Aid(+2). Warnings about a skill that is learning poorly are printed whether this is on or off. Yes or No. | Yes | Each character |
| **Typeahead** | Number of movement commands allowed ahead of game output. Use 0 for careful movement. | 0 | Each character |
| **Citizenship** | Province citizenship used when choosing restricted travel crossings. Choices: Not set, Zoluren, Therengia, Ilithi, Qi'Reshalia, Forfedhdar. | (blank) | Each character |
| **Shard thief password** | The password the Shard Thieves' Guild door asks for. Leave blank on characters who don't use that guild. | (blank) | Each character |
| **Connection: reconnect automatically** | After an unexpected disconnect, log this character back in from the saved session, run reconnect-recovery, and restart master-train if it was running. A typed quit/exit, Disconnect, Exit, or closing GrayDR never reconnects. Yes or No. | No | Each character |
| **Connection: reconnect grace (seconds)** | Seconds to wait before the first reconnect attempt; the game refuses an immediate re-login while the character is still counted as logged in. Later attempts wait 2x, 3x, ... this long. A number, at least 0, at most 3600. | 45 | Each character |
| **Connection: reconnect attempts** | Maximum reconnect attempts per disconnect before giving up and leaving the window in its disconnected state. A number, at least 0, at most 100. | 5 | Each character |
| **Connection: reconnects allowed per hour** | How many times this character may be reconnected automatically within one hour. When the limit is reached it stays disconnected and says so. 0 = no limit. A number, at least 0, at most 100. | 0 | Each character |
| **Chat: connect to LNet at startup** | Connect this character to the LNet chat network (lnet.lichproject.org) when it logs in. Messages appear in the Thoughts window. Chat only: other players' requests for your location, skills or health are always answered with nothing. .chat connect / .chat disconnect switch it during a session. Yes or No. | No | Each character |
| **Trash container** | Exact adjective and noun of the character's general trash container. Spellcasting uses it for spent runestones. Leave blank to use ordinary disposal behavior. | (blank) | Global, or each character |
| **Chat: LNet password** | Optional. LNet names are first come, first served. Type .chat password <word> once to reserve this character's name, then put the same word here so every login uses it. Stored in plain text, as Lich does. | (blank) | Each character |
| **Trash container activation verb** | Optional verb run after putting trash in the character's container, for example TURN. Leave blank when the container needs no activation. | (blank) | Global, or each character |


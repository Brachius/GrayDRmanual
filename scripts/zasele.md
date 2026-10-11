# Zasele Tasks (Hollow Eve)

Script name: `zasele`

The Hollow Eve task loop with Seamstress Zasele on Andreshlew, one loop: drop the outfitting tools at Catrox for repair, dolphin to the island, find Zasele and hand over the pieces until she gives the woven sack, go to the dock and one room west to the barrel (coins out, gems into the hunt pouch, a kept material deeded into the duffel bag, the rest into the barrel), find Zasele again and ask for the next task, back to the mainland, tickets back from Catrox, bank, buy the burlap, rat-pelt leather or yarn, lighthouse, make the pieces, and again.

A full gem pouch is swapped for a spare and handed to Jang at the Crossing dock, who sells it. Which materials are kept, who holds each family and the deed words are in the Data Editor's Zasele keep list. Stop it with `.gka`.

`.zasele repair` only drops the outfitting tools at Catrox; the loop collects the tickets.

**The class at the lighthouse.** While everyone makes pieces, one character teaches and the rest listen, so the time counts twice. On the Events page under Zasele, **Teacher** names who teaches (Brachius) and **Skill taught** names the skill (Locksmithing; it does not have to be one anyone is training). The teacher, at the lighthouse, invites every student standing there with TEACH; the first one to LISTEN opens the class, and from then on nobody needs an invite: the teacher tells every student's script the class is open, and a student arriving at the lighthouse just listens. When the game ends the class (the teacher left, or "stop teach"), the students are told and wait for the next invite. All of it happens between the scripts' own crafting commands; nothing is sent while someone is away from the lighthouse or the teacher is not in the room. Leave **Teacher** blank for no class.

## How to start it

Type `.zasele` followed by the words it takes.

Nothing for the loop. "repair" drops the outfitting tools at Catrox (the loop collects the tickets).

In Master Train, pick **Zasele Tasks** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Events](/studio/events.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-zasele-deed-container"></span>**Deed container** | Where sack deeds go (game noun). Everyone has a duffel bag. | duffel bag | Global, or each character |
| <span id="setting-activities-zasele-meeting-room"></span>**Pouch handoff room** | Where full gem pouches change hands (room number). Default is the Crossing docks south end. A number, at least 0. Must be a room on the map. | 10190 | Global, or each character |
| <span id="setting-activities-zasele-pouch-seller"></span>**Pouch seller** | The character who takes full gem pouches and sells them at the gem shop. | Jang | Global, or each character |
| <span id="setting-activities-zasele-teach-skill"></span>**Skill taught** | The skill the teacher teaches, as TEACH takes it, for example Locksmithing. It does not have to be a skill anyone is training. | Locksmithing | Global, or each character |
| <span id="setting-activities-zasele-teacher"></span>**Teacher** | The character who teaches a class at the lighthouse while everyone makes pieces. That character invites the students there (TEACH); the others listen (LISTEN TO). Leave blank for no class. | Brachius | Global, or each character |


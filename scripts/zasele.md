# Zasele Tasks (Hollow Eve)

Script name: `zasele`

The Hollow Eve task loop with Seamstress Zasele on Andreshlew, one loop: drop the outfitting tools at Catrox for repair, dolphin to the island, find Zasele and hand over the pieces until she gives the woven sack, go to the dock and one room west to the barrel (coins out, gems into the hunt pouch, a kept material deeded into the duffel bag, the rest into the barrel), find Zasele again and ask for the next task, back to the mainland, tickets back from Catrox, bank, buy the burlap, rat-pelt leather or yarn, lighthouse, make the pieces, and again.

A full gem pouch is swapped for a spare and handed to Jang at the Crossing dock, who sells it. Which materials are kept, who holds each family and the deed words are in the Data Editor's Zasele keep list. Stop it with `.gka`.

`.zasele repair` only drops the outfitting tools at Catrox; the loop collects the tickets.

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


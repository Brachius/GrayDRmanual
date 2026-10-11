# Rezz

Script name: `rezz`

Cleric resurrection of a dead player in the room: perceive the body, Rejuvenation, Vigil, Resurrection, then Soul Bonding and the gesture, each cast at the name by hand because the game refuses to autocast them. `.rezz` with no name raises every body in the room; `.rezz Croflux` raises one. The mana for Resurrection and Rejuvenation is under **Rezz** on the Healing page.

## How to start it

Type `.rezz` in the game window.

In Master Train, pick **Rezz** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Healing](/studio/healing.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-rezz"></span>**Rezz** |  |  | Global, or each character |
| <span id="setting-activities-rezz-rezz-mana"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Resurrection mana (also the infuse amount at full mana)** | A number, at least 5, at most 50. | 30 | Global, or each character |
| <span id="setting-activities-rezz-rejuv-mana"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Rejuvenation mana (the nimbus colour follows the mana; 40 reached silver)** | A number, at least 5, at most 100. | 40 | Global, or each character |


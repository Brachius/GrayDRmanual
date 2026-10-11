# AFK Monitor

Script name: `afk`

Watch an idle character; answer idle warnings, dodge justice, escape traps, and log out on death or low vitality. It never sends beside another script - when it must act it stops the other scripts first, then acts alone.

## How to start it

Type `.afk` in the game window.

In Master Train, pick **AFK Monitor** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [AFK Monitor](/studio/afk.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-afk-depart-on-death"></span>**Depart automatically after death** | Yes or No. | No | Global, or each character |
| <span id="setting-activities-afk-depart-type"></span>**Depart command type** |  | item | Global, or each character |
| <span id="setting-activities-afk-justice-threshold"></span>**Justice complaints before logout** | A number, at least 0. | 4 | Global, or each character |
| <span id="setting-activities-afk-health-threshold"></span>**Vitality/spirit logout threshold** | Under this vitality or spirit percent the AFK Monitor stops every other script and logs out. While a Hunt with its own Stop hunting below vitality is running, the Hunt leaves combat instead and the AFK Monitor stands down until the hunt is over. A number, at least 0, at most 100. | 0 | Global, or each character |


# Healme

Script name: `healme`

Heals the configured Empath's wounds, scars, vitality, poison and disease. A number sets the severity to heal from; `debug` prints each decision.

## How to start it

Type `.healme` in the game window.

In Master Train, pick **Healme** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Healing](../studio/healing.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Empath self-healing** |  |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum vitality percent** | A number, at least 0, at most 100. | 60 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum wound severity** | A number, at least 0, at most 13. | 0 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Wounds tended while preparing** | A number, at least 0. | 1 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Wounds healed between perceives** | A number, at least 1. | 3 | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Debug output** | Yes or No. | No | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing spells** _(required)_ | A table of name and value pairs. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing cast settings** _(required)_ |  |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **use_harness_when_arcana_locked** | Yes or No. | (not set) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **custom_spell_prep** |  | (not set) | Global, or each character |


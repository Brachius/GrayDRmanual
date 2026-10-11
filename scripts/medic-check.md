# Medic Check

Script name: `medic-check` (also starts as `medic_check`)

Heal configured patients, maintain the bonded plant, and recover in the healing room.

## How to start it

Type `.medic-check` in the game window.

In Master Train, pick **Medic Check** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Healing](/studio/healing.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-medic-check"></span>**Empath medic routine** |  |  | Global, or each character |
| <span id="setting-activities-medic-check-guild"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Guild** _(required)_ |  | Empath | Global, or each character |
| <span id="setting-activities-medic-check-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Empath plant room** _(required)_ | Room where the vela'tohr plant is kept. Patients come here and the plant is tended here. A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-activities-medic-check-healing-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing room** _(required)_ | A number, at least 1. | (not set) | Global, or each character |
| <span id="setting-activities-medic-check-patients"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Patients in priority order** _(required)_ | A list. | (not set) | Global, or each character |
| <span id="setting-activities-medic-check-healing-waggle-set"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Healing spell set** _(required)_ |  | medic_check | Global, or each character |
| <span id="setting-activities-medic-check-recovery-waggle-set"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Recovery spell set** _(required)_ |  | medic_recovery | Global, or each character |
| <span id="setting-activities-medic-check-plant-waggle-set"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Plant spell set** _(required)_ |  | medic_plant | Global, or each character |
| <span id="setting-activities-medic-check-plant-recast-roisaen"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Plant recast interval** | A number, at least 1, at most 120. | 5 | Global, or each character |
| <span id="setting-activities-medic-check-plant-max-health-score"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Stop plant health score** | A number, at least 1. | 250 | Global, or each character |
| <span id="setting-activities-medic-check-plant-resume-health-score"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Resume plant health score** | A number, at least 0. | 100 | Global, or each character |
| <span id="setting-activities-medic-check-plant-foc-health-score"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Fountain health score** | A number, at least 1. | 250 | Global, or each character |
| <span id="setting-activities-medic-check-plant-min-vitality-percent"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum vitality percent** | A number, at least 1, at most 100. | 70 | Global, or each character |
| <span id="setting-activities-medic-check-mana-threshold"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Minimum mana percent** | A number, at least 0, at most 100. | 40 | Global, or each character |
| <span id="setting-activities-medic-check-cast"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Medic cast settings** _(required)_ |  |  | Global, or each character |
| <span id="setting-activities-medic-check-cast-use-harness-when-arcana-locked"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **use_harness_when_arcana_locked** | Yes or No. | (not set) | Global, or each character |
| <span id="setting-activities-medic-check-cast-custom-spell-prep"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ &nbsp;&nbsp;&nbsp;&nbsp;↳ **custom_spell_prep** |  | (not set) | Global, or each character |


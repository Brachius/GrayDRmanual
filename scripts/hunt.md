# Hunt

Script name: `hunt`

Hunts: walks to the hunting zone, finds a room with creatures, and runs the combat engine there with the weapons, armor, spells and abilities from the [Combat page](/studio/combat.md). It leaves for the reasons set on that page: a skill threshold reached, low vitality, bleeding, the time limit, the encumbrance limit, the boxes limit, a familiar drag, Burgle becoming ready, or a manual stop. In Master Train each reason can start its own activities ([Hunt Results](/studio.md#the-master-train-page)).

`.hunt` runs the main hunt, the character's own settings. A named hunt, with its own values on the Combat page, is run from a Master Train Hunt card that names it.

## How to start it

Type `.hunt` in the game window.

In Master Train, pick **Hunt** as the activity and put the same words in its Arguments box.

## Settings

This script has no settings of its own. Shared pages such as [Character](/studio/character.md), [Magic](/studio/magic.md) and [Crafting](/studio/crafting.md) may still apply.

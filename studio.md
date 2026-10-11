# Configuration Studio

Every setting GrayDR and its scripts use lives here. Open it from the Settings menu of a game window, or with **Launch Configuration Studio** when no window is open. [One page per settings page](/studio/README.md) lists every field.

## How it is laid out

The left-hand list has two groups.

- **GLOBAL SETTINGS**: one value for every character. The Commands page and the Memory diagnostics page are here, and so is the global copy of every setting that can be set either way.
- **CHARACTER SETTINGS**: values for the character chosen in the **Character** box at the top. Two pages here are built differently: [Gear](#the-gear-page) and [Master Train](#the-master-train-page).

A setting that can be set either way shows on both sides. The character's own value wins; if the character has none, the global value is used; if there is no global value either, the default applies. A setting the character has set is shown in bold with a **Customized** marker, and the field says where its value comes from.

**Search settings...** filters the pages as you type. The box under it picks what the search looks at: fields shown on the pages (the default), every field, or only hidden fields. Hidden only, with nothing typed, lists everything you have hidden.

## Hunts

The **Hunt** box beside the character picks which settings you are editing:

- **Main hunt (character settings)**: the character's own values.
- A named hunt: its own layer on top of the character's values. Anything you do not change in the hunt comes from the character.

**Add hunt...** makes a named hunt. It starts as a copy of the main hunt's combat settings as they are now and is on its own from then on. **Rename...** and **Remove** do what they say. Master Train runs a named hunt with a Hunt card whose hunt name is that hunt.

## Guild

The **Guild** box appears when GrayDR has not yet seen this character's guild in play. Set it once; guild-specific pages and fields are shown only for characters of that guild.

## Saving

Nothing is written until you press **Save Changes**. Save runs a **Configuration check** first: a value that cannot be right (a room that is not on the map, a spell the Data Editor does not know, a required field left blank) is listed, and you choose Save anyway or go back.

**Overwrite settings from YAML** re-reads the whole settings file from disk and drops anything you have not saved. It is for when the file was changed outside the Studio.

A saved change is read by the next script that starts. Running scripts keep the values they started with.

## Hiding and ordering fields

Every field has a **Hide** button: hide it on this page for every character, or only for this one. **Organize fields...** at the top of each page brings hidden fields back and lets you reorder the fields you have set. Required fields cannot be hidden.

## The Gear page

Everything the character owns that scripts pick up, wear, swap, or send for repair, in one place. Scripts never guess gear; if it is not on this page, they do not know it exists.

Categories: **Weapons**, **Armor**, **Shields**, **Brawling** (no-damage items; parry devices are the exception), **Other**, and **Crafting tools**. Each row is one item with its **Description**, **Adjective** and **Noun** (exactly as the game takes them), the **Container** it is kept in, whether it is a **Swap** item (a weapon that changes form), and **Repair**: derived (the usual rule for its category), always, or never.

**Tool belts** lists each belt by **Name** and the **Belt** noun used in game commands, so crafting scripts can tie tools to the right belt.

**Add item** and **Add belt** add a blank row; **Remove selected** removes one.

**Autodetect from game** needs a connected window for this character. It sweeps the inventory (expect a few seconds of roundtime) and fills the categories from what it finds. Review the result, then Save.

Two buttons on other pages read from this one: **Auto-fill standard gear set** on the Gear Sets page copies every armor, shield and brawling item into the set called standard, and **Auto-fill weapon training from gear** on the Combat page appraises each weapon in the live game to learn which skill it trains and fills the Weapon training table.

## The Master Train page

Master Train is the one script that runs your whole day. This page is its routine: a list of cards, run top to bottom.

Each card has:

- a **Main Activity**: any script, chosen from the list, with its **Arguments** (the same words you would type after the script's name) and **Script Options...** for the script's own settings;
- an optional **Room**: a room number or a named room from the Character page to walk to first;
- **Before** and **After** lists: activities run before and after the main one, in order;
- **Move Up**, **Move Down**, **Remove**.

A card whose main activity is **Hunt** has more:

- the hunt name: Main hunt, or one of the named hunts;
- **Use Tarantula for this Hunt** and a **Tarantula Cutoff...**: skills that stop the tarantula once they reach a mind state, while the hunt itself goes on;
- **Hunt Results**: what to do when the hunt ends for a particular reason. Reasons: Bleeding, Low vitality, Manual stop, Encumbrance limit, Familiar drag, High skills threshold, Low skills threshold, Burgle is ready, Maximum boxes reached, Required moons unavailable, Time expired, and Any other result. Each handler runs its own list of activities, then either continues the routine, **Hunt again** (repeats this card), or **Quit game** (sends QUIT and stops Master Train).

At the top: **Loop entire training routine** starts again at the first card after the last one finishes, and **Resume saved position after restart** continues from the saved card after Master Train or GrayDR is restarted.

Type `.master-train list` in a game window to see the cards with their numbers. [Typed commands](/commands.md#master-train) has every Master Train command.

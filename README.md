# GrayDR manual

GrayDR is a DragonRealms front end with its own script engine built in. It replaces Lich: the scripts run inside GrayDR, every setting lives in the Configuration Studio, and the game data the scripts rely on is edited in the Data Editor.

This manual is rebuilt every time a new GrayDR package is made, so the settings tables always match the GrayDR you are running.

## Chapters

1. [Getting started](/getting-started.md): the package folder, logging in, profiles.
2. [The GrayDR window](/client.md): menus, the side windows, highlights, text alterations, appearance.
3. [Typed commands](/commands.md): starting and stopping scripts, go2, and every dot command GrayDR understands.
4. [Scripts](/scripts/README.md): one page per script, with what it does, what to type, and its settings.
5. [Configuration Studio](/studio.md): how the Studio works, the Gear page, the Master Train page, and [one page per settings page](/studio/README.md).
6. [Data Editor](/data-editor.md): spells, hunting zones, command answers, crafting tools, and the Map tab for fixing travel.
7. [Account Board](/account-board.md): one window that watches every logged-in character.

## Reading the settings tables

Every settings table has the same four columns.

| Column | Meaning |
|---|---|
| Setting | The label exactly as the Configuration Studio shows it. Type part of it in the Studio's search box to jump to it. |
| What it does | The help text shown under the field in the Studio, plus what kind of value it takes. |
| Default | What GrayDR uses when you have not set anything. |
| Applies to | **Each character**: set it per character. **Global**: one value for everyone. **Global, or each character**: a global value that any character can override. |

A row marked _(advanced)_ is folded away in the Studio until you open the advanced options. A row marked _(Thief only)_ or similar is shown only for characters of that guild.

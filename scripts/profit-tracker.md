# Profit Tracker

Script name: `profit-tracker`

Reports what hunting, crafting and burgling have earned. The recording itself runs in the background while the tracker is enabled on the Profit Tracker page.

## How to start it

Type `.profit-tracker` in the game window.

In Master Train, pick **Profit Tracker** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Profit Tracker](../studio/profit-tracker.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Enable Profit Tracker** | Automatically run the protected background collector and record financial activity in the shared profile ledger. Yes or No. | Yes | Each character |
| **Runtime Heartbeat Seconds** | How often active activity runtimes are durably checkpointed so a disconnect loses at most this much timing data. A number, at least 10, at most 300. | 60 | Each character |
| **Gem pouch owners** | Who owns each pouch color. When Jang sells a pouch, the money counts toward the owner of that color. Ground is the pouch a character fills while hunting, box is the one filled from picked boxes. Add a row for a new character or color. A color with no row is recorded under Jang as unassigned. A list. | {"color" => "black", "owner" => "Brachius", "pouch" => "ground"}, {"color" => "burlap", "owner" => "Brachius", "pouch" => "box"}, {"color" => "blue", "owner" => "Alaint", "pouch" => "ground"}, {"color" => "canvas", "owner" => "Alaint", "pouch" => "box"}, {"color" => "fuzzy", "owner" => "Tirax", "pouch" => "ground"}, {"color" => "dotted", "owner" => "Tirax", "pouch" => "box"}, {"color" => "green", "owner" => "Jang", "pouch" => "ground"}, {"color" => "oxhide", "owner" => "Jang", "pouch" => "box"}, {"color" => "indigo", "owner" => "Dehaka", "pouch" => "ground"}, {"color" => "paisley", "owner" => "Dehaka", "pouch" => "box"}, {"color" => "purple", "owner" => "Braxa", "pouch" => "ground"}, {"color" => "patchwork", "owner" => "Braxa", "pouch" => "box"} | Global, or each character |


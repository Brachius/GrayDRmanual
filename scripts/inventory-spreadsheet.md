# Inventory Spreadsheet

Script name: `inventory-spreadsheet`

Records the carried, eddy and vault items and writes a CSV for Google Sheets. Words: `status`, `resume` (continue a vault restore), `stop-cleanup`, `help`.

## How to start it

Type `.inventory-spreadsheet` in the game window.

In Master Train, pick **Inventory Spreadsheet** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Inventory](/studio/inventory.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Inventory spreadsheet** |  |  | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Where to write the CSV and saved scans** | Folder for the CSV and each character's saved scan. Leave blank to use the project data folder. | (blank) | Global, or each character |
| &nbsp;&nbsp;&nbsp;&nbsp;↳ **Shard Carousel room** | The room the vault booths open from. Only change this if the Carousel moves. A number, at least 1. | 19282 | Global, or each character |


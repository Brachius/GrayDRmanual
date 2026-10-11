# Inventory Spreadsheet

Script name: `inventory-spreadsheet`

Records everything you carry, wear, keep in the eddy and keep in the vault, and writes a CSV you can open in Google Sheets. The vault pass takes items out to read them and puts them back.

```
.inventory-spreadsheet                 carried, worn and vault
.inventory-spreadsheet inventory       carried and worn only
.inventory-spreadsheet vault           vault only
.inventory-spreadsheet vault-scan      rummage the vault, move nothing
.inventory-spreadsheet categories weapon,registered
.inventory-spreadsheet pouches         (also: autoloot, containers, quantities)
.inventory-spreadsheet export          write the CSV
.inventory-spreadsheet status          where it is
.inventory-spreadsheet resume          carry on putting the vault back after a stop
.inventory-spreadsheet stop-cleanup
```

Options: `--limit=N`, `--match=TEXT`, `--skip-special`, `--skip-categories`, `--carousel=ROOM`.

## How to start it

Type `.inventory-spreadsheet` in the game window.

In Master Train, pick **Inventory Spreadsheet** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Inventory](/studio/inventory.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-activities-inventory-spreadsheet"></span>**Inventory spreadsheet** |  |  | Global, or each character |
| <span id="setting-activities-inventory-spreadsheet-data-directory"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Where to write the CSV and saved scans** | Folder for the CSV and each character's saved scan. Leave blank to use the project data folder. | (blank) | Global, or each character |
| <span id="setting-activities-inventory-spreadsheet-carousel-room"></span>&nbsp;&nbsp;&nbsp;&nbsp;↳ **Shard Carousel room** | The room the vault booths open from. Only change this if the Carousel moves. A number, at least 1. | 19282 | Global, or each character |


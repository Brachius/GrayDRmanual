# Loot

Configuration Studio page **Loot**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Selling: the town, the bank and currency exchange, metals and stones, trap components, the bank bot, and how much platinum to keep.

Scripts that read these settings: [Combat Trainer](/scripts/combat-trainer.md), [Sell Loot](/scripts/sell-loot.md).

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Autoloot material container** |  | (blank) | Global, or each character |
| **Autoloot metals** | Yes or No. | No | Global, or each character |
| **Bank bot character** |  | (blank) | Global, or each character |
| **Bank bot platinum kept on hand** | Whole platinum kept on you when tipping the rest of your coin to the bank bot. A number, at least 0. | 0 | Global, or each character |
| **Bank bot room** | A number, at least 0. Must be a room on the map. | 0 | Global, or each character |
| **Exchange all currencies** | On exchanges every foreign currency into the town's own, whatever the three boxes below say. Off lets the boxes choose. Yes or No. | Yes | Global, or each character |
| **Exchange Dokoras** | Used only when Exchange all currencies is off. Yes or No. | No | Global, or each character |
| **Exchange Kronars** | Used only when Exchange all currencies is off. The town's own currency is never exchanged, so this does nothing in a Kronar town. Yes or No. | No | Global, or each character |
| **Exchange Lirums** | Used only when Exchange all currencies is off. Yes or No. | No | Global, or each character |
| **Ignored metals and stones** | Semicolon-delimited material names. | (blank) | Global, or each character |
| **Kiosk markup accepted (percent)** | The kiosk markup, as a percentage, that this character accepts. Enter -10 for -10%. The kiosk quotes its markup when the bundle is offered; with Strict markup off any quote at or below this number is accepted, so 0 accepts 0, -5 and -10. A quote outside that is not our kiosk and the bundle is sold at the furrier instead. A number, at least -10, at most 80. | 0 | Global, or each character |
| **Leave gem pouch open** | Yes or No. | No | Global, or each character |
| **Metal and stone containers** | Semicolon-delimited container names. | (blank) | Global, or each character |
| **Sell bundles to the Trader kiosk** | When on, a full skin bundle is taken to the kiosk room first and offered to the kiosk. If no kiosk stands there, its quoted markup is not the one accepted below, or it cannot pay for the whole bundle, the bundle is sold at the furrier as usual. Leave this off for the Trader who owns the kiosk. Yes or No. | No | Global, or each character |
| **Sell metals and stones** | Yes or No. | No | Global, or each character |
| **Sell trap components** | Yes or No. | No | Global, or each character |
| **Selling town** |  | (blank) | Global, or each character |
| **Skip bank** | Yes or No. | No | Global, or each character |
| **Skip currency exchange** | Yes or No. | No | Global, or each character |
| **Strict markup** | When on, the kiosk must show exactly the accepted markup and nothing lower. When off, anything at or below the accepted markup is fine. Yes or No. | No | Global, or each character |
| **Trader kiosk room** | The room number where the Trader kiosk stands. A number, at least 0. Must be a room on the map. | 2030017 | Global, or each character |
| **Use bank bot** | Yes or No. | No | Global, or each character |
| **Autoloot** | Turn on if this character wears an autolooter (a lootbag, lootbelt or similar item that grabs loot the moment a corpse is searched). When on, the script trusts the Autoloot items list below and never sends a stow for anything the autolooter takes. When off, every lootable item named in the game's "was carrying" line is stowed by hand right after the search. Nothing on the ground is ever scanned for either way. Yes or No. | No | Global, or each character |
| **Autoloot items** | The categories your autolooter is set to take (AUTOLOOT in game shows them). Pick from the fixed list; ALL means every category is on. Anything named in a corpse's "was carrying" line whose category is listed here is treated as already in your bag. A category NOT listed is treated as left on the ground, so a lootable item of that kind gets one stow. The script can tell gems, boxes, scrolls, metals (nuggets and bars) and coins apart by name; herbs, weapons, ammunition and armor cannot be told apart from other treasure, so they follow the ITEMS setting. A list. | (not set) | Global, or each character |
| **Sell loose gem-pouch contents** | Open the configured hunting pouch and sell each gem. Yes or No. | No | Each character |
| **Platinum kept after selling** | Local platinum left on hand after exchange and banking. A number, at least 0, at most 100000. | 20 | Each character |


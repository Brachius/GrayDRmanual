# Scripts

Every script, grouped the way the Configuration Studio groups their settings. Start a script by typing its name after a dot in the game window, for example `.workorders tailoring`. [Typed commands](/commands.md) covers starting, stopping and listing scripts.

## AFK Monitor

| Script | Start with | What it does |
|---|---|---|
| [AFK Monitor](/scripts/afk.md) | `.afk` | Watch an idle character; answer idle warnings, dodge justice, escape traps, and log out on death or low vitality. |

## Magic

| Script | Start with | What it does |
|---|---|---|
| [Astrology Training](/scripts/astrology.md) | `.astrology` | Train Moon Mage Astrology by observing the heavens, predicting from full pools, and running Read the Ripples, exactly like astrology.lic. |
| [Attunement Training](/scripts/attune-train.md) | `.attune-train` | Mind locks Attunement by rotating through the concentration rooms. |
| [Augmentation Magic Training](/scripts/aug-train.md) | `.aug-train` | Train Augmentation magic using the script-owned spell configuration (the Augmentation entry under Training spells); stops at mind lock like utility-train and ward-train. |
| [Moon Mage Perceive](/scripts/moon-perc.md) | `.moon-perc` | One Attunement pass over the Moon Mage perceive targets; skipped when Attunement is mind locked. |
| [Scroll Manage](/scripts/scroll-manage.md) | `.scroll-manage` | Sort loose spell scrolls from the backpack and the chest in the backpack into the two eternity scroll folios, exactly like the custom scroll-manage Lich script. |
| [sorcery-train](/scripts/sorcery-train.md) | `.sorcery-train` | Trains Sorcery with the Sorcery entry under Training spells on the Magic page, the same way utility-train, ward-train and aug-train train their skills. |
| [Summoning Training](/scripts/summoning.md) | `.summoning` | Train Warrior Mage Summoning by summoning and breaking weapons, then focusing the pathway. |
| [trader-perc](/scripts/trader-perc.md) | `.trader-perc` | One Attunement pass over the Trader perceive targets (mana, planets, illusion). |
| [Utility Magic Training](/scripts/utility-train.md) | `.utility-train` | Train Utility magic using the script-owned spell configuration. |
| [Walking Astrology](/scripts/walkingastro.md) | `.walkingastro` | Train Astrology in the background while hunting or crafting - observe through the telescope whenever the sky is visible and predict when a pool fills, exactly like walkingastro.lic. |
| [Warding Magic Training](/scripts/ward-train.md) | `.ward-train` | Train Warding magic using the script-owned spell configuration. |

## Combat

| Script | Start with | What it does |
|---|---|---|
| [Combat Trainer](/scripts/combat-trainer.md) | `.combat-trainer` | The combat engine on its own, in the room you are standing in: it fights what is here with the weapons, armor, spells and abilities from the Combat page, without walking anywhere. |
| [Hunt](/scripts/hunt.md) | `.hunt` | Hunts: walks to the hunting zone, finds a room with creatures, and runs the combat engine there with the weapons, armor, spells and abilities from the Combat page. |

## Training

| Script | Start with | What it does |
|---|---|---|
| [Appraisal Training](/scripts/appraisal-train.md) | `.appraisal-train` | Trains Appraisal by assessing a fiddle in The Broken Blade hallway until mind locked, playing the zills meanwhile so Performance trains too. |
| [collect](/scripts/collect.md) | `.collect` | Walks to the collecting room and collects rocks until both Outdoorsmanship and Perception are done learning: mind locked, or at their rank cap. |
| [crystal-arcana](/scripts/crystal-arcana.md) | `.crystal-arcana` | Gazes into the worn sanowret crystal once, for Arcana. |
| [master-train](/scripts/master-train.md) | `.master-train` | Runs your whole training routine, card by card, as set up on the Studio's Master Train page. |
| [Memory Orbs](/scripts/memory-orbs.md) | `.memory-orbs` | Invokes or studies memory orbs and puts the orbs that were not used back in their container. |
| [Scholarship Training](/scripts/scholarship-train.md) | `.scholarship-train` | Studies a tailoring book page by page, a Tome of Lore first, with a song playing alongside until Performance is mind locked. |
| [Yiamura](/scripts/yiamura.md) | `.yiamura` | Operates a worn yiamura: `.yiamura raise`, `point`, `observe`, `invoke` or `reset`. |
| [Yiamura Claim](/scripts/yiamura-claim.md) | `.yiamura-claim` | Collect the knowledge the yiamura's observer gathered during a hunt (OBSERVE MY YIAMURA). |

## Buffs

| Script | Start with | What it does |
|---|---|---|
| [Barbarian Magic](/scripts/barb-magic.md) | `.barb-magic` | Activate an ordered list of Barbarian abilities for training. |
| [buffs](/scripts/buffs.md) | `.buffs` | Casts a named buff set once. |

## Trading

| Script | Start with | What it does |
|---|---|---|
| [kiosk](/scripts/kiosk.md) | `.kiosk` | The Trader kiosk. |
| [Trading Training](/scripts/trading-train.md) | `.trading-train` | Sells the profit pouches and runs Mags's nuloe-stem task loop. |

## Healing

| Script | Start with | What it does |
|---|---|---|
| [First Aid](/scripts/first-aid.md) | `.first-aid` | Train First Aid and Scholarship from anatomy charts. |
| [Healme](/scripts/healme.md) | `.healme` | Heals the configured Empath's wounds, scars, vitality, poison and disease. |
| [hospital-heal](/scripts/hospital-heal.md) | `.hospital-heal` | Heals at the Empath's plant room when one is configured on the Healing page, otherwise at Quentin's hospital. |
| [Medic Check](/scripts/medic-check.md) | `.medic-check` | Heal configured patients, maintain the bonded plant, and recover in the healing room. |
| [Medic Plant](/scripts/medic-plant.md) | `.medic-plant` | Maintains and fully drains the Empath's bonded vela'tohr plant in the medic room. |
| [Rezz](/scripts/rezz.md) | `.rezz` | Cleric resurrection of a dead player in the room (rezz [player]). |
| [Safe Room Healing](/scripts/safe-room.md) | `.safe-room` | Select configured PC Empath, self-healing, NPC, or Necromancer healing routes. |
| [tendme](/scripts/tendme.md) | `.tendme` | Tends your own wounds: only parasites, lodged objects and bleeders that are safe to tend, most severe first. |
| [tendother](/scripts/tendother.md) | `.tendother` | Binds another character's wounds and keeps the bandages up for their run: `.tendother Name`. |

## Crafting

| Script | Start with | What it does |
|---|---|---|
| [Ingredient Gathering](/scripts/alchemy.md) | `.alchemy` | Native port of alchemy.lic forage and preparation workflows. |
| [Carving](/scripts/carve.md) | `.carve` | Native port of carve.lic. |
| [Craft Training](/scripts/craft.md) | `.craft` | Native rank-tier training port of craft.lic; knitting delegates to Sew. |
| [Enchanting](/scripts/enchant.md) | `.enchant` | Native port of enchant.lic with sigil/fount/imbue handling. |
| [Forging](/scripts/forge.md) | `.forge` | Blacksmithing, armorsmithing, and weaponsmithing crafting, tempering, and enhancements, exactly like forge.lic and smith.lic. |
| [Make Steel](/scripts/makesteel.md) | `.makesteel` | Buy iron and coal, smelt steel ingots, optionally refine them, exactly like makesteel.lic. |
| [Mix calculator](/scripts/mixcalc.md) | `.mixcalc` | Volumes of pure metal and magic ingot for a 67/33 mix of a given size. |
| [Remedies](/scripts/remedy.md) | `.remedy` | Native port of remedy.lic. |
| [Tailoring](/scripts/sew.md) | `.sew` | Sew, knit, or enhance tailoring items exactly like sew.lic, including consumable restocking and rental renewal. |
| [Shaping](/scripts/shape.md) | `.shape` | Shape wood items exactly like shape.lic, including consumable restocking by chapter, assembly parts, and bow enhancements. |
| [Smelt](/scripts/smelt.md) | `.smelt` | Work a loaded crucible until the metal is mixed, exactly like smelt.lic. |
| [smith](/scripts/smith.md) | `.smith` | The forging path work orders use per item: finds the recipe by name, buys the parts and optionally the ingot, walks to an anvil or the private forge (renewing the rental when it runs low), restocks oil, casts the smith buff set, then forges, with optional stamp and enhancement passes and scrap disposal. |
| [Spin Thread](/scripts/spin.md) | `.spin` | Buy fibers and spin them into thread at a town tailoring society. |
| [Tinkering](/scripts/tinker.md) | `.tinker` | Native port of tinker.lic including mechanisms and bow enhancements. |
| [Weave Cloth](/scripts/weave-cloth.md) | `.weave-cloth` | Weave two thread items into cloth at a town tailoring society. |
| [Work Orders](/scripts/workorders.md) | `.workorders` | Request, craft, bundle, and turn in crafting-society work orders, exactly like workorders.lic. |

## Loot

| Script | Start with | What it does |
|---|---|---|
| [pouch-appraisal](/scripts/pouch-appraisal.md) | `.pouch-appraisal` | Appraises the training gem pouches from the pouch source container and moves each finished one to the staging container, as set on the Gem Pouches page. |
| [Sell Loot](/scripts/sell-loot.md) | `.sell-loot` | Sell configured loot and perform optional banking. |

## Locksmithing

| Script | Start with | What it does |
|---|---|---|
| [Locksmithing](/scripts/locksmithing.md) | `.locksmithing` | Train Locksmithing with daily and consumable training boxes. |
| [Lockbox Picking](/scripts/pick.md) | `.pick` | Disarms and picks the boxes from the configured box sources, walking to the picking room first when one is set. |

## Athletics

| Script | Start with | What it does |
|---|---|---|
| [Athletics](/scripts/athletics.md) | `.athletics` | Train Athletics using a selected route or stationary mode. |

## Checks

| Script | Start with | What it does |
|---|---|---|
| [configprobe](/scripts/configprobe.md) | `.configprobe` | Prints the configuration values the combat scripts depend on, for pasting into a bug report. |
| [engine-text-wait-report](/scripts/engine-text-wait-report.md) | `.engine-text-wait-report` | A test script: sends LOOK and reports the room's exits. |
| [haul-to-2014100](/scripts/haul-to-2014100.md) | `.haul-to-2014100` | A test walk to the Crossing south ferry dock by way of the ferry. |
| [haul-to-241002](/scripts/haul-to-241002.md) | `.haul-to-241002` | A test walk to the Crossing south ferry dock by way of the ferry. |
| [lichroom](/scripts/lichroom.md) | `.lichroom` | Translates between GrayDR room numbers and Lich map numbers. |
| [plat](/scripts/plat.md) | `.plat` | Money converter. |
| [Profit Tracker](/scripts/profit-tracker.md) | `.profit-tracker` | Reports what hunting, crafting and burgling have earned. |
| [profit-tracker-service](/scripts/profit-tracker-service.md) | `.profit-tracker-service` | The background half of the Profit Tracker. |
| [validate](/scripts/validate.md) | `.validate` | Checks this character's whole configuration against the data files (skill names, spells, the map, activities, the gear list, hunting zones, crafting tools) and prints every value that cannot be right. |
| [wrayth-prime](/scripts/wrayth-prime.md) | `.wrayth-prime` | Sends the client controls that unlock the game's larger typeahead queue, then exits. |

## Utilities

| Script | Start with | What it does |
|---|---|---|
| [autoaccept](/scripts/autoaccept.md) | `.autoaccept` | Waits for anyone to offer you something, accepts it, stows it from the right hand, and waits for the next offer. |
| [Chain](/scripts/chain.md) | `.chain` | Run scripts and game commands one after another, separated by a pipe. |
| [Multi](/scripts/multi.md) | `.multi` | Repeat an ordered mixture of game commands and child scripts. |
| [Reconnect Recovery](/scripts/reconnect-recovery.md) | `.reconnect-recovery` | Put a reconnected character back in order before Master Train resumes. |
| [Wait](/scripts/wait.md) | `.wait` | Pause a script sequence for a number of seconds. |

## Tarantula

| Script | Start with | What it does |
|---|---|---|
| [Tarantula](/scripts/tarantula.md) | `.tarantula` | Consume eligible field experience with a biomechanical tarantula or harvester spider. |

## Events

| Script | Start with | What it does |
|---|---|---|
| [Deed Sorting (Hollow Eve)](/scripts/deed-sort.md) | `.deed-sort` | Hand sack deeds to their keepers, then rebuild each keeper's register into full-size deeds. |
| [Zasele Tasks (Hollow Eve)](/scripts/zasele.md) | `.zasele` | Seamstress Zasele's sewing and knitting tasks on Andreshlew, turned in for woven sacks. |

## Performance

| Script | Start with | What it does |
|---|---|---|
| [Performance](/scripts/performance.md) | `.performance` | Train Performance with the configured instrument. |

## Theurgy

| Script | Start with | What it does |
|---|---|---|
| [autofavor](/scripts/autofavor.md) | `.autofavor` | Favors in a loop. |
| [carve-bead](/scripts/carve-bead.md) | `.carve-bead` | Carves a prayer bead for the Theurgy page's aspect. |
| [favor](/scripts/favor.md) | `.favor` | Gets a favor: the temple puzzle for one orb, then the altar. |
| [om](/scripts/om.md) | `.om` | Creates and loads an Osrel Meraud from one exact deity favor orb. |
| [Theurgy](/scripts/theurgy.md) | `.theurgy` | Train Theurgy using configured rituals |
| [tithe](/scripts/tithe.md) | `.tithe` | Puts the tithe in the almsbox, as set on the Theurgy page. |

## Inventory

| Script | Start with | What it does |
|---|---|---|
| [Inventory Spreadsheet](/scripts/inventory-spreadsheet.md) | `.inventory-spreadsheet` | Records the carried, eddy and vault items and writes a CSV for Google Sheets. |

## Burgle

| Script | Start with | What it does |
|---|---|---|
| [burgle](/scripts/burgle.md) | `.burgle` | Burgles a home: enters by lockpick or rope, searches the rooms, keeps or sells the loot, as set on the Studio's Burgle page. |

## Gear

| Script | Start with | What it does |
|---|---|---|
| [repair-dropoff](/scripts/repair-dropoff.md) | `.repair-dropoff` | Drops worn armour and shield with the repairer by REPAIR ALL, hands over every other gear item that is not marked never for repair, and stows every ticket. |
| [repair-pickup](/scripts/repair-pickup.md) | `.repair-pickup` | Gives every repair ticket back, waits when a repair is not ready, stores returned gear (tied for belt tools, stowed otherwise), and wears everything from the worn-gear sack, which must report empty before it is thrown in the repairer's bucket. |
| [weargear](/scripts/weargear.md) | `.weargear` | Puts a gear set back on from wherever the pieces are. |

## Handoff

| Script | Start with | What it does |
|---|---|---|
| [handoff-receive](/scripts/handoff-receive.md) | `.handoff-receive` | The receiver's side of a handoff when his Master Train is not running. |
| [handofftest](/scripts/handofftest.md) | `.handofftest` | A real handoff with the receiver, on demand, from an idle giver: full pouches from the configured container, the scroll chest, and the boxes, exactly as Master Train's own handoff does it. |

## Travel

| Script | Start with | What it does |
|---|---|---|
| [automap](/scripts/automap.md) | `.automap` | Records the moves you make by hand so the Data Editor can put them on the travel map, dark rooms included. |
| [go2](/scripts/go2.md) | `.go2` | Walks you to a room. |


# Scripts

Every script, grouped the way the Configuration Studio groups their settings. Start a script by typing its name after a dot in the game window, for example `.workorders tailoring`. [Typed commands](/commands.md) covers starting, stopping and listing scripts.

## AFK Monitor

| Script | Start with | What it does |
|---|---|---|
| [AFK Monitor](/scripts/afk.md) | `.afk` | Watch an idle character; answer idle warnings, dodge justice, escape traps, and log out on death or low vitality. |

## Magic

| Script | Start with | What it does |
|---|---|---|
| [Astrology Training](/scripts/astrology.md) | `.astrology` | Moon Mage Astrology: cycles the tasks under **Astrology training tasks** on the Magic page (observe, rtr, weather, events, attunement, ways) until Astrology reaches mind state 32, predicting from every pool that is ready after each pass. |
| [Attunement Training](/scripts/attune-train.md) | `.attune-train` | Mind locks Attunement by walking the concentration rooms in turn and perceiving in each. |
| [Augmentation Magic Training](/scripts/aug-train.md) | `.aug-train` | Train Augmentation magic using the script-owned spell configuration (the Augmentation entry under Training spells); stops at mind lock like utility-train and ward-train. |
| [Moon Mage Perceive](/scripts/moon-perc.md) | `.moon-perc` | One round of the Moon Mage perceives for Attunement: mana, moons, planets, psychic, transduction, perception and moonlight. |
| [Scroll Manage](/scripts/scroll-manage.md) | `.scroll-manage` | Sort loose spell scrolls from the backpack and the chest in the backpack into the two eternity scroll folios, exactly like the custom scroll-manage Lich script. |
| [sorcery-train](/scripts/sorcery-train.md) | `.sorcery-train` | Trains Sorcery with the Sorcery entry under Training spells on the Magic page, the same way utility-train, ward-train and aug-train train their skills. |
| [Summoning Training](/scripts/summoning.md) | `.summoning` | Warrior Mage Summoning: summons a weapon, breaks it, burns the leftover charge with pathway focus, and repeats until the mind state goal. |
| [trader-perc](/scripts/trader-perc.md) | `.trader-perc` | One round of the Trader perceives for Attunement: mana, planets and illusion. |
| [Utility Magic Training](/scripts/utility-train.md) | `.utility-train` | Trains Utility magic with the spell set under **Training spells**, Utility, on the Magic page: it walks to the training room, casts the spell again and again at the mana the trainer has settled on, charging and invoking the cambrinth when one is configured, and stops at mind lock. |
| [Walking Astrology](/scripts/walkingastro.md) | `.walkingastro` | Astrology on the side while you hunt or craft: about every three and a half minutes, or when the last observation is pondered, it buffs, takes the telescope out, centres it on a constellation for the time of day, peers, and predicts when a pool is full. |
| [Warding Magic Training](/scripts/ward-train.md) | `.ward-train` | Trains Warding the same way Utility training works, with the Warding entry under **Training spells** on the Magic page. |

## Combat

| Script | Start with | What it does |
|---|---|---|
| [Combat Trainer](/scripts/combat-trainer.md) | `.combat-trainer` | The combat engine on its own, in the room you are standing in: it fights what is here with the weapons, armor, spells and abilities from the Combat page, without walking anywhere. |
| [Hunt](/scripts/hunt.md) | `.hunt` | Hunts: walks to the hunting zone, finds a room with creatures, and runs the combat engine there with the weapons, armor, spells and abilities from the Combat page. |

## Training

| Script | Start with | What it does |
|---|---|---|
| [Appraisal Training](/scripts/appraisal-train.md) | `.appraisal-train` | Appraisal to mind lock: walks to The Broken Blade hallway and assesses a fiddle over and over, playing the zills between assesses until Performance is mind locked too. |
| [collect](/scripts/collect.md) | `.collect` | Walks to the collecting room and sends COLLECT ROCK PRACTICE until both Outdoorsmanship and Perception are done learning: mind locked, or at their rank cap. |
| [crystal-arcana](/scripts/crystal-arcana.md) | `.crystal-arcana` | Gazes into the worn sanowret crystal once, for Arcana. |
| [master-train](/scripts/master-train.md) | `.master-train` | Runs your whole training routine, card by card, as set up on the Studio's Master Train page. |
| [Memory Orbs](/scripts/memory-orbs.md) | `.memory-orbs` | Invokes or studies memory orbs and puts the orbs that were not used back in their container. |
| [Scholarship Training](/scripts/scholarship-train.md) | `.scholarship-train` | Studies your tailoring book page by page, a Tome of Lore first when the character has one, with a song playing alongside until Performance is mind locked. |
| [Yiamura](/scripts/yiamura.md) | `.yiamura` | Operates a worn yiamura: `.yiamura raise`, `point`, `observe`, `invoke` or `reset`. |
| [Yiamura Claim](/scripts/yiamura-claim.md) | `.yiamura-claim` | Collects what the yiamura's observer gathered during the hunt with OBSERVE MY YIAMURA, as a step of its own after the hunt's skills have drained: a Master Train after-step, or by hand. |

## Buffs

| Script | Start with | What it does |
|---|---|---|
| [Barbarian Magic](/scripts/barb-magic.md) | `.barb-magic` | Activates the Barbarian abilities listed under **Barbarian training abilities** on the Buffs page, in that order: forms, roars, berserks and meditations, sitting for the meditations when **Sit for meditations** is on. |
| [buffs](/scripts/buffs.md) | `.buffs` | Casts a named buff set once. |

## Trading

| Script | Start with | What it does |
|---|---|---|
| [kiosk](/scripts/kiosk.md) | `.kiosk` | The Trader kiosk. |
| [Trading Training](/scripts/trading-train.md) | `.trading-train` | Trader training: services the Trader kiosk first when one is set up (the crystalline pouches it taps sell with the rest), sells the profit pouches, then runs Mags's nuloe-stem task loop until the skill is done. |

## Healing

| Script | Start with | What it does |
|---|---|---|
| [First Aid](/scripts/first-aid.md) | `.first-aid` | Trains First Aid, Scholarship or both from anatomy charts: it gets the textbook (or the compendium when **Use anatomy textbook** is off), opens it, turns to the hardest charts you can learn from and studies them, up to **Maximum charts per run**. |
| [Healme](/scripts/healme.md) | `.healme` | Empath self-healing: works through your wounds, scars, poison and disease with your healing spells, and brings vitality back, in the order of severity. |
| [hospital-heal](/scripts/hospital-heal.md) | `.hospital-heal` | Heals at the Empath's plant room when one is configured on the Healing page, otherwise at Quentin's hospital. |
| [Medic Check](/scripts/medic-check.md) | `.medic-check` | The Empath's rounds, run from Master Train or by hand: walk to the healing room, LOOK, heal every patient on the list who is there, tend the bonded plant, recover, then LOOK and heal again so anyone who arrived meanwhile is caught before leaving. |
| [Medic Plant](/scripts/medic-plant.md) | `.medic-plant` | Maintains and fully drains the Empath's bonded vela'tohr plant in the medic room. |
| [Rezz](/scripts/rezz.md) | `.rezz` | Cleric resurrection of a dead player in the room: perceive the body, Rejuvenation, Vigil, Resurrection, then Soul Bonding and the gesture, each cast at the name by hand because the game refuses to autocast them. |
| [Safe Room Healing](/scripts/safe-room.md) | `.safe-room` | Gets you healed, the way the Healing page's **Safe-room healing policy** says: by a player Empath in the safe room, by yourself (Empath self-healing), by an NPC, or the Necromancer way. |
| [tendme](/scripts/tendme.md) | `.tendme` | Tends your own wounds: only parasites, lodged objects and bleeders that are safe to tend, most severe first. |
| [tendother](/scripts/tendother.md) | `.tendother` | Binds another character's wounds and keeps the bandages fresh for as long as they stay: `.tendother Jang`. |

## Crafting

| Script | Start with | What it does |
|---|---|---|
| [Ingredient Gathering](/scripts/alchemy.md) | `.alchemy` | Gathers and prepares a remedy ingredient. |
| [Carving](/scripts/carve.md) | `.carve` | Carves a stone or bone piece with the carving tools from your belt and bag. |
| [Craft Training](/scripts/craft.md) | `.craft` | Rank-tier crafting training for one discipline: it picks the item that fits your ranks, buys the stock for it, walks to your training room (**Craft training rooms** on the Crafting page, or the safe room), makes the piece with the discipline's own script, and throws the result away. |
| [Enchanting](/scripts/enchant.md) | `.enchant` | Makes one artificing piece: lays the sigils on the base item with the burin, uses the fount, and imbues with your wand or rod. |
| [Forging](/scripts/forge.md) | `.forge` | Forging at an anvil: blacksmithing, armorsmithing and weaponsmithing. |
| [Make Steel](/scripts/makesteel.md) | `.makesteel` | Makes steel ingots. |
| [Mix calculator](/scripts/mixcalc.md) | `.mixcalc` | A calculator, nothing is sent to the game. |
| [Remedies](/scripts/remedy.md) | `.remedy` | Makes one remedy in the mortar or bowl, the same way Lich's remedy script did it hand for hand. |
| [Tailoring](/scripts/sew.md) | `.sew` | Tailoring: sewing cloth and leather, knitting, and the armor enhancements (seal, reinforce, lighten). |
| [Shaping](/scripts/shape.md) | `.shape` | Engineering: shaping wood into lumber items and arrow shafts, the bow enhancements, and crafting from instructions. |
| [Smelt](/scripts/smelt.md) | `.smelt` | Works a crucible you have already loaded until the metal is thoroughly mixed: it stirs with the stirring rod, turns the clumps, pushes the bellows when the fire flickers, and adds fuel with the shovel or the tongs when it asks for it. |
| [smith](/scripts/smith.md) | `.smith` | The all-in-one forging run that work orders use for each item, and that you can run yourself: it finds the recipe by name, buys the parts and (with `buy`) the ingot, walks to an anvil or your private forge, restocks oil, casts your smith buff set, then forges. |
| [Spin Thread](/scripts/spin.md) | `.spin` | Buys fibers at the tailoring society and spins them into one thread item on the society's spinning wheel. |
| [Tinkering](/scripts/tinker.md) | `.tinker` | Tinkering: bolts, darts, mechanisms and the bow enhancements, with consumable restocking. |
| [Weave Cloth](/scripts/weave-cloth.md) | `.weave-cloth` | Takes two thread items you are carrying to a tailoring-society loom and weaves them into one cloth item. |
| [Work Orders](/scripts/workorders.md) | `.workorders` | Work orders from start to finish: asks the discipline's NPC for an order, buys the stock, makes each item with the discipline's own script, bundles the pieces into the logbook, turns it in, and can repair the tools afterwards. |

## Loot

| Script | Start with | What it does |
|---|---|---|
| [pouch-appraisal](/scripts/pouch-appraisal.md) | `.pouch-appraisal` | Appraises the training gem pouches from the pouch source container and moves each finished one to the staging container, as set on the Gem Pouches page. |
| [Sell Loot](/scripts/sell-loot.md) | `.sell-loot` | Sells what the hunt brought back and banks the money: the skin bundle at the tannery (or to the Trader kiosk when that is on), the gems from the hunting pouch at the gem shop, metals and stones when **Sell metals and stones** is on, and trap components; then the currency exchange and the bank, keeping **Platinum kept after selling** on hand. |

## Locksmithing

| Script | Start with | What it does |
|---|---|---|
| [Locksmithing](/scripts/locksmithing.md) | `.locksmithing` | Trains Locksmithing on boxes you own: the daily training box and the consumable keepsake and jewelry boxes, which it takes in the order set under **Locksmithing training boxes** on the Locksmithing page (consumables first when that is ticked). |
| [Lockbox Picking](/scripts/pick.md) | `.pick` | Disarms and picks the boxes from the configured box sources, walking to the picking room first when one is set. |

## Athletics

| Script | Start with | What it does |
|---|---|---|
| [Athletics](/scripts/athletics.md) | `.athletics` | Trains Athletics to a goal and comes back. |

## Checks

| Script | Start with | What it does |
|---|---|---|
| [configprobe](/scripts/configprobe.md) | `.configprobe` | Prints the settings the combat scripts depend on, so they can be pasted into a report when something is wrong. |
| [engine-text-wait-report](/scripts/engine-text-wait-report.md) | `.engine-text-wait-report` | A test script: sends LOOK and reports the room's exits. |
| [haul-to-2014100](/scripts/haul-to-2014100.md) | `.haul-to-2014100` | A test walk to the Crossing south ferry dock by way of the ferry. |
| [haul-to-241002](/scripts/haul-to-241002.md) | `.haul-to-241002` | A test walk to the Crossing south ferry dock by way of the ferry. |
| [lichroom](/scripts/lichroom.md) | `.lichroom` | Translates between GrayDR room numbers and Lich map numbers, for reading old Lich scripts or notes. |
| [plat](/scripts/plat.md) | `.plat` | Money converter. |
| [Profit Tracker](/scripts/profit-tracker.md) | `.profit-tracker` | Shows what hunting, crafting and burgling have earned. |
| [profit-tracker-service](/scripts/profit-tracker-service.md) | `.profit-tracker-service` | The recorder half of the Profit Tracker. |
| [validate](/scripts/validate.md) | `.validate` | Checks this character's whole configuration against the data files (skill names, spells, the map, activities, the gear list, hunting zones, crafting tools) and prints every value that cannot be right. |
| [wrayth-prime](/scripts/wrayth-prime.md) | `.wrayth-prime` | Sends the client controls that unlock the game's larger typeahead queue, then exits. |

## Utilities

| Script | Start with | What it does |
|---|---|---|
| [autoaccept](/scripts/autoaccept.md) | `.autoaccept` | Waits for anyone to offer you something, accepts it, stows it from the right hand, and waits for the next offer. |
| [Chain](/scripts/chain.md) | `.chain` | Runs steps one after another, separated by a pipe. |
| [Multi](/scripts/multi.md) | `.multi` | Repeats a list of game commands and scripts in order. |
| [Reconnect Recovery](/scripts/reconnect-recovery.md) | `.reconnect-recovery` | The clean-up GrayDR runs by itself after it reconnects a character that was dropped mid-script, before Master Train resumes. |
| [Wait](/scripts/wait.md) | `.wait` | Pauses for the number of seconds you give, then waits out any roundtime still running. |

## Tarantula

| Script | Start with | What it does |
|---|---|---|
| [Tarantula](/scripts/tarantula.md) | `.tarantula` | The biomechanical tarantula or harvester spider that eats field experience. |

## Events

| Script | Start with | What it does |
|---|---|---|
| [Deed Sorting (Hollow Eve)](/scripts/deed-sort.md) | `.deed-sort` | The Hollow Eve deed-sorting party. |
| [Zasele Tasks (Hollow Eve)](/scripts/zasele.md) | `.zasele` | The Hollow Eve task loop with Seamstress Zasele on Andreshlew, one loop: drop the outfitting tools at Catrox for repair, dolphin to the island, find Zasele and hand over the pieces until she gives the woven sack, go to the dock and one room west to the barrel (coins out, gems into the hunt pouch, a kept material deeded into the duffel bag, the rest into the barrel), find Zasele again and ask for the next task, back to the mainland, tickets back from Catrox, bank, buy the burlap, rat-pelt leather or yarn, lighthouse, make the pieces, and again. |

## Performance

| Script | Start with | What it does |
|---|---|---|
| [Performance](/scripts/performance.md) | `.performance` | Plays your worn instrument (**Performance worn instrument**, normally zills) until Performance reaches the goal. |

## Theurgy

| Script | Start with | What it does |
|---|---|---|
| [autofavor](/scripts/autofavor.md) | `.autofavor` | Favors in a loop. |
| [carve-bead](/scripts/carve-bead.md) | `.carve-bead` | Carves a prayer bead for your immortal's aspect with the carving knife from the Theurgy page. |
| [favor](/scripts/favor.md) | `.favor` | Gets a favor: the temple puzzle for one orb, then the altar. |
| [om](/scripts/om.md) | `.om` | Creates and loads an Osrel Meraud from one exact deity favor orb, never a bare GET MY ORB that could pick a memory orb instead. |
| [Theurgy](/scripts/theurgy.md) | `.theurgy` | Cleric Theurgy training: the rituals and communes for your immortal's aspect, with the prayer mat, incense, holy water and the other supplies from the **Ritual supply container**, restocked when they fall below the level set on the Theurgy page. |
| [tithe](/scripts/tithe.md) | `.tithe` | Puts the tithe in the almsbox named under **Tithe almsbox** on the Theurgy page. |

## Inventory

| Script | Start with | What it does |
|---|---|---|
| [Inventory Spreadsheet](/scripts/inventory-spreadsheet.md) | `.inventory-spreadsheet` | Records everything you carry, wear, keep in the eddy and keep in the vault, and writes a CSV you can open in Google Sheets. |

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
| [handoff-receive](/scripts/handoff-receive.md) | `.handoff-receive` | The receiver's half of a handoff when his Master Train is not running. |
| [handofftest](/scripts/handofftest.md) | `.handofftest` | A real handoff with the receiver, on demand, from an idle giver: full pouches from the configured container, the scroll chest, and the boxes, exactly as Master Train's own handoff does it. |

## Travel

| Script | Start with | What it does |
|---|---|---|
| [automap](/scripts/automap.md) | `.automap` | Records the moves you make by hand so the Data Editor can put them on the travel map, dark rooms included. |
| [go2](/scripts/go2.md) | `.go2` | Walks you to a room. |


# Combat

Configuration Studio page **Combat**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Every Combat Trainer and Hunt setting: weapons and the skills they train, armor rotation, combat spells, abilities, retreat and stop rules, hunting zones and buddies, loot. Named hunts override any of these for one hunt.

Scripts that read these settings: [Combat Trainer](/scripts/combat-trainer.md).

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Weapon training** | a hash of weapon skills and the weapons used to train them. They must be defined in gear A table of name and value pairs. | (not set) | Global, or each character |
| **Aim fillers** | Combat settings A table of name and value pairs. | (not set) | Global, or each character |
| **Aim fillers stealth** | list of actions to take while aiming when stealth still needs to be trained A table of name and value pairs. | (not set) | Global, or each character |
| **Aiming trainables** | a - list of weapon skills to pull out and use in offhand while waiting for a crossbow to aim. Make sure they're light! A list. | (not set) | Global, or each character |
| **Always use maneuvers** | If true, keep using Charged Maneuvers regardless of field exp Yes or No. | (not set) | Global, or each character |
| **Ambush** | ambush enemies instead of backstab. After recent backstab changes this may be useless Yes or No. | (not set) | Global, or each character |
| **Ambush location** | when ambushing, what body part to target. After recent backstab changes this may be useless | (not set) | Global, or each character |
| **Ambush choke weapons** | Weapon skills to train with Ambush Choke, separated by commas. While one of these is up the hunt hides and sends "ambush choke" instead of a normal attack. Any weapon works; needs Ambush Choke learned. Stops once Backstab is mind locked and starts again when it drops, unless Backstab past mindlock is on. | (not set) | Global, or each character |
| **Ambush stun weapons** | Weapon skills to train with Ambush Stun, separated by commas. While one of these is up the hunt hides and sends "ambush stun" instead of a normal attack. Needs Ambush Stun learned and a blunt weapon. Stops once Backstab is mind locked and starts again when it drops, unless Backstab past mindlock is on. | (not set) | Global, or each character |
| **Armor exp training max threshold** | Thresholds in mind-states at which point hunting-buddy considers the 'stop_on' skills to be done training and will end the hunt. You can specify a different threshold per skillset. | (not set) | Global, or each character |
| **Astrology prediction skills** _(Moon Mage only)_ | Hash of skills to use for each prediction. A table of name and value pairs. | (not set) | Global, or each character |
| **Attack overrides** | use attack overrides for main hand attacks A table of name and value pairs. | (not set) | Global, or each character |
| **Aura frequency** _(Trader only)_ | Trader only - enables starlight management - how many seconds in between checking starlight auras in combat | (not set) | Global, or each character |
| **Autoloot container** | Name of autoloot container for Combat Trainer | (not set) | Global, or each character |
| **Autoloot gems** | Set to true if you have gems autolooted Yes or No. | (not set) | Global, or each character |
| **Avtalia array** _(Trader only)_ | Trader-use avtalia.lic to build a list of avtalia cambrinth. A table of name and value pairs. | (not set) | Global, or each character |
| **Backstab** _(Thief only)_ | name of the weapon skill in weapon_training you want to use to backstab. This can also be a list such as - Small Edged - Small Blunt | (not set) | Global, or each character |
| **Backstab past mindlock** _(Thief only)_ | Useful for farming with backstab Yes or No. | (not set) | Global, or each character |
| **Balance regen threshold** | Minimum balance to perform certain actions (currently only whirlwind) solidly balanced | (not set) | Global, or each character |
| **Barb famine healing** _(Barbarian only)_ | Requires health_threshold (will use below this number) and inner_fire_threshold (will use if ABOVE this number) - Leave empty if unused! A table of name and value pairs. | (not set) | Global, or each character |
| **Battle cries** _(Barbarian, Bard only)_ | Barbarian Roars or Bardic Screams to use in combat at enemies. A battle cry will be chosen from this list in sequential order unless overridden by `battle_cry_cycle`. You can refine criteria for when and what to roar/scream, similar to configuring `offensive_spells`. target_enemy: optional name of critter to roar/scream at, default is who you're facing/engaged min_threshold: optional, number of critters that must be in room before use this ability, default 1 max_threshold: optional, number of critters that above which you won't use this ability, default infinity command: optional, customize the exact phrase to perform the scream/roar A list. | (not set) | Global, or each character |
| **Battle cry cooldown** _(Barbarian, Bard only)_ | The number of seconds to wait between battle cries. | (not set) | Global, or each character |
| **Battle cry cycle** _(Barbarian, Bard only)_ | The script will cycle through roaring/screaming in this order. By default, you'll roar/scream in a round-robin order as defined in `battle_cries:`. Use this optional setting to further refine the specific order you'd like to roar/scream in. Most useful if you have multiple screams/roars to use. A list. | (not set) | Global, or each character |
| **Bonebug** _(Necromancer only)_ | Controls bonebug behavior in Combat Trainer. | (not set) | Global, or each character |
| **Box-hunt start threshold** | Used only by Hunt entries configured as box-collection hunts. The Hunt runs when the character carries this many locked boxes or fewer; it is skipped when carrying more. This does not limit ordinary box looting. | (not set) | Global, or each character |
| **Maximum boxes carried** | Maximum total locked boxes to carry. Combat counts boxes already carried, loots until reaching this total, then leaves additional boxes. Leave blank to always loot boxes. A box-collection Hunt also ends when this total is reached. A number, at least 0. | (not set) | Global, or each character |
| **Use charged maneuvers** | No switches the whole charged-maneuver feature off for this character: the maneuver list below is ignored, "Charged Maneuver" in training abilities does nothing, and the Bow/dual-load conflict check is skipped. Yes (the default) keeps the Lich behavior. Native GrayDR switch; Lich has no equivalent. Yes or No. | Yes | Global, or each character |
| **Charged maneuvers** | Trains Expertise with these maneuvers - set "Charged Maneuver" in your training_abilities with an associated cooldown A table of name and value pairs. | (not set) | Global, or each character |
| **Check discern timer in hours** | used with use_auto_mana. How often it will check discerns in hours. Lower circle/ranks should check more often. i.e., checking every 24 hours | (not set) | Global, or each character |
| **Combat analyze retry count** | how many times to retry a failed analyze when using Analyze in training_abilities | (not set) | Global, or each character |
| **Combat spell timer** | Timer for casting combat_spell_training. Edit with extreme caution - too little can cause other casting to be ignored. | (not set) | Global, or each character |
| **Combat spell training** | Controls combat spell training behavior in Combat Trainer. A table of name and value pairs. | (not set) | Global, or each character |
| **Combat spell training max threshold** | only use combat_spell_training spells when there are more than this many mobs in combat. | (not set) | Global, or each character |
| **Combat teaching skill** | what to teach to any of your hunting buddies while in combat. Must be a combat-related skill | (not set) | Global, or each character |
| **Combat trainer action count** | how many actions to do if you dont hit the mindstate goal before swapping weapons | (not set) | Global, or each character |
| **Combat trainer focus threshold** | minimum mindstate threshold (for all weapons being trained) to begin focussing on single weapons to minimise weapon switching. default is 0 which means feature is not active. Change to 10 or higher to activate. | (not set) | Global, or each character |
| **Combat trainer gain check** | roughly number of consecutive mainhand attack rounds that need to not gain mindstate (34/34, mob too low or constant misses) before a weapon switch is forced or blacklisted default is 0 (off). If activated, suggest value of 5 to start | (not set) | Global, or each character |
| **Combat trainer gear set** | Controls combat trainer gear set behavior in Combat Trainer. | (not set) | Global, or each character |
| **Combat trainer herbs allowhands** | Setting to override combat-trainer skipping herbs that require a hand to use while in combat Yes or No. | (not set) | Global, or each character |
| **Combat trainer ignore weapon mindstate** | Tells Ct to ignore mindstates, allowing one to farm whilst mindlocked, or with capped weapons Yes or No. | (not set) | Global, or each character |
| **Combat trainer loop tick** | seconds to pause at the end of each main combat loop tick. Lower = faster reaction, higher = less idle CPU usage. Default 0.1. | (not set) | Global, or each character |
| **Combat trainer magic gain check** | roughly number of consecutive spell casts of a single skill (e.g. Targeted Magic)that need to not gain mindstate (mob too low) before it is blacklisted. | (not set) | Global, or each character |
| **Combat trainer offhand gain check** | roughly number of consecutive offhand attack rounds that need to not gain mindstate (34/34, mob too low or constant misses) before a weapon switch is forced or blacklisted default is 0 (off). If activated, suggest value of 2 to start | (not set) | Global, or each character |
| **Combat trainer offhand trainables** | Optional feature to preference using aiming_trainables on the offhand ONLY, to reduce competition from aiming_trainables using mainhand attacks It is contingent on combat_trainer_focus_threshold being active. Yes or No. | (not set) | Global, or each character |
| **Combat trainer target increment** | how many mindstates to use a weapon for | (not set) | Global, or each character |
| **Combat trainer use yiamura** | Whether to use a yiamura in combat Yes or No. | (not set) | Global, or each character |
| **Combat training abilities target** | How high in mind-states to train training_abilities before skipping them. | (not set) | Global, or each character |
| **Custom hunting zones** | Controls custom hunting zones behavior in Combat Trainer. | (not set) | Global, or each character |
| **Custom loot type** | treasure/equipment/all? What LOOT type to use for mobs | (not set) | Global, or each character |
| **Custom spell prep** | Controls custom spell prep behavior in Combat Trainer. | (not set) | Global, or each character |
| **Cycle armors** | List of armor types and corresponding items from gear to rotate for training purposes. | (not set) | Global, or each character |
| **Cycle armors hysteresis** | Choose Yes to keep the currently worn armor when every configured armor skill is trained. Choose No to swap back to the Default armor type. Yes or No. | (not set) | Global, or each character |
| **Cycle armors regalia** | A list of armor skills for trader regalia casting. | (not set) | Global, or each character |
| **Cycle armors time** | How often, in seconds, to check for cycle_armors swapping. | (not set) | Global, or each character |
| **Cyclic no release** | List of cyclic spells that won't get released by scripts when generally releasing cyclics A list. | (not set) | Global, or each character |
| **Damaris weapon sets** | Controls damaris weapon sets behavior in Combat Trainer. | (not set) | Global, or each character |
| **Dance actions** | actions to take while dancing. A list. | (not set) | Global, or each character |
| **Dance actions stealth** | list of actions to take while dancing when stealth still needs to be trained A list. | (not set) | Global, or each character |
| **Dance skill** | What weapon skill to use while dancing | (not set) | Global, or each character |
| **Dance threshold** | Defines the number of monsters you will keep in combat with you by performing 'dance actions' or attacking with only 'harmless: true' spells. 0 means kill everything. | (not set) | Global, or each character |
| **Default armor type** | Works with cycle_armors, regalia, and hysteresis.  Which armor type to use when all others on your list are trained. | (not set) | Global, or each character |
| **Default stance** | Stance combat-trainer will go into when first starting up, before combat logic starts | (not set) | Global, or each character |
| **Dirt stacker** | Controls dirt stacker behavior in Combat Trainer. | (not set) | Global, or each character |
| **Dissect and butcher** _(Necromancer only)_ | Attempts to Necromancer dissect after butchering. Yes or No. | (not set) | Global, or each character |
| **Dont stalk** | don't stalk when Stealth is in training_abilities: Yes or No. | (not set) | Global, or each character |
| **Doublestrike trainables** | When prioritizing doublestrike maneuvers, this is the list of melee one-handed skills that when equipped in your mainhand you want to attempt a doublestrike with another listed weapon skill equipped in your offhand, assuming they aren't the same item (e.g. ristes). This setting is necessary if you use twohanded staves or polearms so that you can opt them out of doublestrike attempts because they will fail because the weapon itself requires two hands. If you're able to use the weapon for an aiming trainable then it's suitable to be a doublestrike trainable. This separate setting gives you control, however, to use different weapons for aiming and doublestrike purposes. A list. | (not set) | Global, or each character |
| **Dual load** | Controls dual load behavior in Combat Trainer. Yes or No. | (not set) | Global, or each character |
| **Dump item count** | items to wait for before junking | (not set) | Global, or each character |
| **Dump junk** | dump junk when braiding or other training actions that generate junk. Yes or No. | (not set) | Global, or each character |
| **Dynamic dance skill** | dynamic_dance_skill true means auto-adjust your dance_skill based on your lowest-trained weapons Yes or No. | (not set) | Global, or each character |
| **Egg** | Define the noun to turn on egg usage in combat. Cooldown is 15 minutes. | (not set) | Global, or each character |
| **Empty hunting room messages** | A list of possible messages to say when you enter a room and don't see anyone. Sample messages below if you want to add to your yaml. A list. | (not set) | Global, or each character |
| **Fatigue regen action** | action to take when fatigued | (not set) | Global, or each character |
| **Fatigue regen threshold** | percent threshold below which it uses your fatigue_regen_action until you are rested | (not set) | Global, or each character |
| **Favor goal** | Number of favors to shoot for. | (not set) | Global, or each character |
| **Favor god** | Specify your favor god. | (not set) | Global, or each character |
| **Favor orb rub frequency** | how often to rub a stored favor orb in combat | (not set) | Global, or each character |
| **Firing delay** | Delay for shooting aimed weapons. | (not set) | Global, or each character |
| **Flame expertise training threshold** _(Barbarian only)_ | Minimum EXP to maintain for use with analyze combos. Will Flame if your Expertise is below this threshold. | (not set) | Global, or each character |
| **Flame inner fire threshold** _(Barbarian only)_ | Minimum inner fire to trigger analyze flame use | (not set) | Global, or each character |
| **Forage item** | If you choose forage method, you'll want to select a custom item for best learning rate. | (not set) | Global, or each character |
| **Force unhide** | unhides after using the Stealth training_abilities Yes or No. | (not set) | Global, or each character |
| **Have telescope** _(Moon Mage only)_ | Do you have a telescope? Yes or No. | (not set) | Global, or each character |
| **Combat logout health threshold** | During Combat Trainer, send EXIT when vitality falls below this percentage. During Hunt, first issue AVOID ALL and EXIT to leave the hunting area. This is separate from AFK Monitor's vitality/spirit logout threshold. | (not set) | Global, or each character |
| **Hide type** | switch to hide_type: stalk to use slip stalk | (not set) | Global, or each character |
| **Hunting buddies** | a list of friends who hunt in the same zones. If you both add each other to this list you may share a room together. A list. | (not set) | Global, or each character |
| **Hunting buddies max** | Max number of hunting buddies you want in room with you | (not set) | Global, or each character |
| **Hunting disable room descriptions** | Controls hunting disable room descriptions behavior in Combat Trainer. | (not set) | Global, or each character |
| **Hunting info** | The hunt entries this character runs, in order. Each entry is one hunt with its zone(s), how long to stay, and the skills that end it early. "Add item" on the Hunting info row creates a new entry with these fields ready to fill in. A named hunt (Hunt picker at the top) can carry its own copy of this list. A list. | (not set) | Global, or each character |
| **Hunting nemesis** | A list of nemesis or people you do not want to hunt with. A list. | (not set) | Global, or each character |
| **Hunting room max searches** | When unable to find a room to hunt in, hunting-buddy will run back to a safe room and wait 20-40 seconds before returning to the hunting zone to look for a room again. How many times should hunting-buddy revist the area to look for a suitable hunting room before ultimately giving up? Note, this is not the number of physical rooms to be checked. This is the number of times to wait then revisit the area to find a room. | (not set) | Global, or each character |
| **Hunting room min mana** | Minimum perc mana to look for in a hunting room. If hunting_room_strict_mana is true, then it will skip a hunt if it can't find the mana | (not set) | Global, or each character |
| **Hunting room strict mana** | Controls hunting room strict mana behavior in Combat Trainer. Yes or No. | (not set) | Global, or each character |
| **Ignored npcs** | NPCs to ignore in combat, WM familiars are a common one. Without ignoring them you may appraise them. A list. | (not set) | Global, or each character |
| **Import constructs list** | Controls import constructs list behavior in Combat Trainer. | (not set) | Global, or each character |
| **Import undeads list** | Controls import undeads list behavior in Combat Trainer. | (not set) | Global, or each character |
| **Khri adaptation** _(Thief only)_ | Thief only - use khri adaptation Can use PUNCTURE, SLICE, IMPACT, FIRE, COLD, or ELECTRIC, delay type or type delay slice, slice, etc | (not set) | Global, or each character |
| **Kneel khri** _(Thief only)_ | Thief only - kneel to activate khri With sufficient skill, you can activate while standing Yes or No. | (not set) | Global, or each character |
| **Last rites** _(Cleric only)_ | perform last_rites or not? Yes or No. | (not set) | Global, or each character |
| **Left hand free** | Keep left hand free during Bow for aiming_trainables Yes or No. | (not set) | Global, or each character |
| **Loot bodies** | loot bodies after killing them Yes or No. | (not set) | Global, or each character |
| **Loot delay** | Delay for looting bodies, in seconds | (not set) | Global, or each character |
| **Loot specials** | define a special way to handle certain loot. See Sarvatt-setup A list. | (not set) | Global, or each character |
| **Lootables** | List of lootable items in base-items.yaml. Do not change. You can add lootables via loot_additions. | (not set) | Global, or each character |
| **Lore exp training max threshold** | Controls lore exp training max threshold behavior in Combat Trainer. | (not set) | Global, or each character |
| **Magic exp training max threshold** | Controls magic exp training max threshold behavior in Combat Trainer. | (not set) | Global, or each character |
| **Maneuver rush engage only** | Controls maneuver rush engage only behavior in Combat Trainer. Yes or No. | (not set) | Global, or each character |
| **Maneuver rush shield** | If "Charged Maneuver" is set in your training_abilities, or `pounce_to_engage: true`, this setting determines which shield you will equip to your offhand to rush to engage enemies with. This can be the same as your arm-worn shield, or perhaps a larger one that you pull out of a container just for this maneuver. This must match the "{adjective} {noun}" of the same item in your gear: section. | (not set) | Global, or each character |
| **Maneuver rush skip retreat** | Set to true to avoid retreating if already at melee. Yes or No. | (not set) | Global, or each character |
| **Maneuver rush to engage** | Toggle use of Maneuver Rush to engage (when it is available) Yes or No. | (not set) | Global, or each character |
| **Manipulate only to train** _(Empath only)_ | manipulate only to train empathy, or always manipulate when above the threshold. Yes or No. | (not set) | Global, or each character |
| **Manipulate threshold** _(Empath only)_ | how many mobs should be in combat with you before you start empath-manipulation. | (not set) | Global, or each character |
| **Meditation pause timer** | Used to set a pause timer for barbarian meditations. This number should go down with a chakrel, circles, and stats... When buff or combat-trainer scripts are activating meditations, this is how many seconds to wait for it to activate. | (not set) | Global, or each character |
| **Necro corpse priority** _(Necromancer only)_ | Controls necro corpse priority behavior in Combat Trainer. | (not set) | Global, or each character |
| **Necro force rituals** _(Necromancer only)_ | force rituals regardless of mindstates Yes or No. | (not set) | Global, or each character |
| **Necro redeemed** _(Necromancer only)_ | redeemed tag only allows dissect ritual Yes or No. | (not set) | Global, or each character |
| **Necro siphon vit threshold** _(Necromancer only)_ | vitality threshold for performing SV as defined in necromancer_healing below. | (not set) | Global, or each character |
| **Necromancer healing** _(Necromancer only)_ | defines wound thresholds and spells for healing. Interacts with thanatology settings. Consume Flesh requires thanatology - heal: true see Melborne-setup for examples. A table of name and value pairs. | (not set) | Global, or each character |
| **Offensive spell cycle** | offensive_spell_cycle is a list of offensive_spells names in the order you want to cast them. Most useful if you have multiple TM or DEBIL spells to cast A list. | (not set) | Global, or each character |
| **Offensive spell mana threshold** | don't cast offensive/buff/combat_training spells unless you have more than this much mana. | (not set) | Global, or each character |
| **Offensive spells** | The spells Combat Trainer casts at enemies, in order. "Add item" creates a spell entry with its fields ready to fill in. Name, skill, and mana are the ones every entry needs; the rest are optional. A list. | (not set) | Global, or each character |
| **Offhand thrown** | allow throwing offhand weapons Yes or No. | (not set) | Global, or each character |
| **OST use waggle** | Controls ost use waggle behavior in Combat Trainer. | (not set) | Global, or each character |
| **Paladin use badge** _(Paladin only)_ | Controls paladin use badge behavior in Combat Trainer. Yes or No. | (not set) | Global, or each character |
| **Paladin use mana glyph** _(Paladin only)_ | Controls paladin use mana glyph behavior in Combat Trainer. Yes or No. | (not set) | Global, or each character |
| **Permashocked** _(Empath only)_ | if you are permashocked, this setting will it apply it to all hunts, no longer needing construct Yes or No. | (not set) | Global, or each character |
| **Pounce on cooldown** _(Ranger only)_ | Toggle to use Pounce ability (for rangers) every time it is available Yes or No. | (not set) | Global, or each character |
| **Pounce to engage** _(Ranger only)_ | Toggle to use Pounce ability (for Rangers) instead of engage (when it is off cooldown) Yes or No. | (not set) | Global, or each character |
| **Prep scaling factor** | used with use_auto_mana. Multiplies your discern limit by this number to get a safe mana amount. | (not set) | Global, or each character |
| **Prioritize maneuver doublestrike** | If "Charged Maneuver" is set in your training_abilities, this setting will attempt doublestrikes by temporarily wielding a "doublestrike trainable" in your offhand when you're holding a "doublestrike trainable" in your main hand. If this is false then doublestrikes are only attempted if you are a Barbarian using whirlwind. If you already use "aiming trainables" to train multiple weapons when using a ranged weapon, then this is a complementary setting to train multiple melee weapons. Yes or No. | (not set) | Global, or each character |
| **Prioritize offensive spells** | Default setting is combat_spell_training: will take priority over offensive_spells: Yes or No. | (not set) | Global, or each character |
| **Priority defense** | Set a priority defense skill name to always use 100% of that defense when it's legal for your weapon. | (not set) | Global, or each character |
| **Priority weapons** | List of weapon skills to focus training on. A list of weapon skill names. | (not set) | Global, or each character |
| **Release cyclic on low mana** | release any cyclic on low mana Yes or No. | (not set) | Global, or each character |
| **Release cyclic threshold** | release any cyclic when below this mana threshold | (not set) | Global, or each character |
| **Retreat threshold** | retreat and avoid combat if fighting this many monsters or more. | (not set) | Global, or each character |
| **Roar helm noun** _(Barbarian only)_ | Set the noun of your roar helm to use scream helm before roars. | (not set) | Global, or each character |
| **Safety concentration minimum** | Controls safety concentration minimum behavior in Combat Trainer. | (not set) | Global, or each character |
| **Safety escape health threshold** | Controls safety escape health threshold behavior in Combat Trainer. | (not set) | Global, or each character |
| **Stop hunting below vitality** | Vitality percent. When your vitality falls under this number the hunt leaves at once, retreats before anything else, skips the last kill, puts weapons away, runs the hunt row's after scripts and walks to the safe room. Master Train sees it as the hunt result Low vitality. While a hunt with this set is running, the AFK Monitor leaves low vitality to the hunt instead of logging out. 0 turns it off. A number, at least 0, at most 100. | 0 | Global, or each character |
| **Segue prep on stop** | Controls segue prep on stop behavior in Combat Trainer. | (not set) | Global, or each character |
| **Segue spell on stop** | Set a cyclic spell to segue to instead of releasing a cyclic when combat-trainer ends. Bard only setting. Must know how to segue. Strongly recommended to use a justice safe spell. Works best when the chosen spell is also in cyclic_no_release: Use the cyclic spell abbrevation. E.g. botf. The segue command's parser doesn't like full spell names. | (not set) | Global, or each character |
| **Sell loot skip bank** | Controls sell loot skip bank behavior in Combat Trainer. Yes or No. | (not set) | Global, or each character |
| **Skip last kill** | When combat-trainer is ending, kill the last mob or not, you will potentially lose ammo if you don't Yes or No. | (not set) | Global, or each character |
| **Sliver recast delay** _(Moon Mage only)_ | Controls sliver recast delay behavior in Combat Trainer. | (not set) | Global, or each character |
| **Stance override** | Override automatic handling of your stances during combat. | (not set) | Global, or each character |
| **Stances** | Skill-specific stances when training these weapon types. Uses same keys as `weapon_training:` setting. Ignored if `stance_override:` is set. A table of name and value pairs. | (not set) | Global, or each character |
| **Stealth attack aimed action** | any special ranged aimed attack to use from stealth | (not set) | Global, or each character |
| **Stomp to engage** _(Barbarian only)_ | Toggle to use War Stomp instead of engage (when it is available) Yes or No. | (not set) | Global, or each character |
| **Stop hunting if bleeding** | Stop the hunt the moment you start bleeding so you can get healed before you bleed out - no tending in combat. A heal-over-time spell (Empath Heal/Regenerate, Necromancer Devour) heals bleeds, so while one is active the hunt does NOT stop on the bleed alone; it only stops once your vitality (health %) has also fallen below safety_escape_health_threshold (default 80). With no heal-over-time active, the hunt stops as soon as you bleed. Yes or No. | (not set) | Global, or each character |
| **Stop on familiar drag** | When true, will stop the hunt when a familiar drags you from combat when stunned. False means it will return you to the room drug from Yes or No. | (not set) | Global, or each character |
| **Stop on high threshold** | sets the mindstates required for hunting-buddy.lic's stop_on skills | (not set) | Global, or each character |
| **Stop on low threshold** | Controls stop on low threshold behavior in Combat Trainer. | (not set) | Global, or each character |
| **Stop to burgle** | Global toggle to cause hunting buddy to stop a hunt short when the burgle timer hits. Note there is also a per-hunt toggle that goes in hunting_info that one is stop_on_burgle_cooldown. Yes or No. | (not set) | Global, or each character |
| **Strict weapon stance** | When true then weapon stances are strictly respected as listed in your yaml or base.yaml settings. When false then combat-trainer will dynamically determine your stance based on which of the first two listed skills has the lowest learning rate and rank. For example, if Bow lists Evasion &gt; Shield &gt; Parry, when strict weapon stance is false then combat-trainer may switch that to Shield &gt; Evasion &gt; Parry if shield has the lower learning rate/rank than Evasion. This dynamic selection optimizes learning, but may be dangerous for characters who are uphunting or have disparate defense ranks. For historical reasons, this setting defaults to false although intuitively you'd expect it to be true. Yes or No. | (not set) | Global, or each character |
| **Stun skill** | what skill the ambush stun trains. | (not set) | Global, or each character |
| **Stun weapon** | what weapon and weapon skill to use with ambush stun | (not set) | Global, or each character |
| **Stun weapon skill** | Controls stun weapon skill behavior in Combat Trainer. | (not set) | Global, or each character |
| **Summoned weapons** | settings for WM or MM summoned weapons. See Dartellum-setup or Crannach-setup A list. | (not set) | Global, or each character |
| **Summoned weapons adjective** | Controls summoned weapons adjective behavior in Combat Trainer. | (not set) | Global, or each character |
| **Summoned weapons element** | Controls summoned weapons element behavior in Combat Trainer. | (not set) | Global, or each character |
| **Summoned weapons ingot** | Controls summoned weapons ingot behavior in Combat Trainer. | (not set) | Global, or each character |
| **Survival exp training max threshold** | Controls survival exp training max threshold behavior in Combat Trainer. | (not set) | Global, or each character |
| **Symbiosis learning threshold** | Controls symbiosis learning threshold behavior in Combat Trainer. | (not set) | Global, or each character |
| **Telescope name** _(Moon Mage only)_ | Noun of your telescope. | (not set) | Global, or each character |
| **Telescope storage** _(Moon Mage only)_ | Container for telescope storage. A table of name and value pairs. | (not set) | Global, or each character |
| **Tessera mindstates** _(Trader only)_ | The Trading mindstate threshold below which (or equal to) you will use your tessera. | (not set) | Global, or each character |
| **Thanatology** _(Necromancer only)_ | Necromancer setting for harvesting body parts. A table of name and value pairs. | (not set) | Global, or each character |
| **Tk ammo** _(Moon Mage only)_ | what item to get and then drop for use with TKT/TKS | (not set) | Global, or each character |
| **Training abilities** | Ordered in-combat training abilities. Choose the exact runtime ability name, then keep its cooldown and optional skill check on the same row. A list. | (not set) | Global, or each character |
| **Training spell mana threshold** | Controls training spell mana threshold behavior in Combat Trainer. | (not set) | Global, or each character |
| **Training spells combat sorcery** | Controls training spells combat sorcery behavior in Combat Trainer. Yes or No. | (not set) | Global, or each character |
| **Use analyze combos** | use the analyze combos to train for all guilds, brawling analyze isn't supported Yes or No. | (not set) | Global, or each character |
| **Use barb combos** _(Barbarian only)_ | This is deprecated, instead switch to use_analyze_combos Yes or No. | (not set) | Global, or each character |
| **Use harness when arcana locked** | Spellcasting (and Khri) settings Yes or No. | (not set) | Global, or each character |
| **Use overrides for aiming trainables** | use attack overrides for aiming trainable skills Yes or No. | (not set) | Global, or each character |
| **Use stealth attacks** | use_stealth_attacks true will train stealth by hiding and attacking/backstabbing from stealth. Thieves also use backstab: below Yes or No. | (not set) | Global, or each character |
| **Stealth attacks stop when this skill locks** | Hiding before attacks keeps going until this skill reaches your combat training abilities target, then the hunt fights in the open. Stealth is the usual choice. Pick Backstab for a Thief whose Stealth is far above the creatures and never locks, so hiding stops once Backstab is learned instead. Choices: Stealth, Backstab. | Stealth | Global, or each character |
| **Use stealth ranged** | decides if you want to hide/train stealth by snipe/poach Yes or No. | (not set) | Global, or each character |
| **Use weak attacks** | avoid damaging attacks in combat - useful when training against mobs that don't spawn well. Doesn't work right with whirlwind. Yes or No. | (not set) | Global, or each character |
| **Using light crossbow** | allow melee offhand weapon training while aiming crossbow in aiming_trainables Yes or No. | (not set) | Global, or each character |
| **War stomp on cooldown** _(Barbarian only)_ | Toggle to use War Stomp ability (for Barbarians) every time it is available Yes or No. | (not set) | Global, or each character |
| **Warhorn** _(Barbarian only)_ | Noun of your warhorn. | (not set) | Global, or each character |
| **Warhorn cooldown** _(Barbarian only)_ | Set the cooldown of your warhorn in seconds. Default is 20 minutes. Some horns are 15. | (not set) | Global, or each character |
| **Water holder** | Your water holder. | (not set) | Global, or each character |
| **Weapon exp training max threshold** | Controls weapon exp training max threshold behavior in Combat Trainer. | (not set) | Global, or each character |
| **Whirlwind trainables** | list of weapon skills to use with whirlwind. See Chuno-setup A list of weapon skill names. | (not set) | Global, or each character |
| **Zombie** _(Necromancer only)_ | zombie settings. Making a zombie in combat requires a waggle set called 'zombie' with CFB in it. A table of name and value pairs. | (not set) | Global, or each character |


Changelog for Survival eXtreme Collection
=========================================

0.3.14
------

* Play a sound if a hero dies, so players listening but AFK know a message has paused the game
* Random heroes are chosen from a “good” subset, and a player will never get an Ulf at random
* Rename the hardest difficulty “Unwinnable”
* The framework supports arbitrary numbers of both player and AI sides
* The per-turn `SXC_INCOME_BONUS_10` is still limited to the first 10 AI sides’ leaders

0.3.13
------

* SXC Maze: in revive mode, moved the respawn point closer to the shop
* SXC Extend: moved the difficulty label near to the start location
* New macros `SXC_ENEMY_BOSS_LOC` and `SXC_ENEMY_GUARD_3_LOC` which take `location_id`s
* Use `map_file` instead of `map_data`

0.3.12
------

* Even on maps with Ageless Era AI units, allow the host to choose an era for player units
* All healing abilities will be recognised, and become megacures or minorcures
* All regeneration abilities will be recognised, and become megaregen or minorregen
* Revive mode now gives a full heal, but costs a bit more than a shop heal even in rookie mode
* SXC Braveheart: made it possible to have a “spare” side for late-joining players
* SXC Mermaid’s Lake, Pursuit and System also have the AI ignoring the “spare” side
* Begin adding a “madder than mad” difficulty
* Sell red potions in every shop; this might be reverted depending on feedback
* Add a couple of Dunefolk to the SXC Default Low Level Era
* Fix missing images in the story screens, and skip the screen that just showed the SXC version

0.3.11
------

* Released by ccX, as there hadn't been an official upload to 1.18
* Merge the fixes from 0.3.3.1
* Fix some of the missing images in the story screens

0.3.4 through 0.3.10
--------------------

* Released by ccX, as there hadn't been an official upload to 1.18
* Fixed some healing abilities not turning into megacures nor minorcures
* Sell potions in every shop by default
* Increase the difficulty for all levels

0.3.3.1
-------

Probably the final upload to 1.16, released after 0.3.4.

* SXC Cursed Land: fixed for compatibility with Ageless Era 4.31
* SXC Slaughter: fixed missing sounds and images, edited text, compatibilty with AE 4.34

0.3.3
-----

* Fixed: Wesnoth 1.16 automatically added loyal overlays to almost all enemies
* The silver crowns of enemy guards are now easy to see again
* Mobile bosses now have a red crown instead

0.3.2
-----

* Fix megaregen and megacures with Wesnoth 1.16.
* SXC Infernal: fixed a warning about redefining a macro from SXC Storm Castle

0.3.1
-----

* Remembered to update the `SXC_VERSION` macro

0.3.0
-----

* This is the first version for Wesnoth 1.16.
* Maps with AE enemies require AE eras, for compatibilty with 1.16's disabling of inactive add-ons.
* Use 1.14's new names for Dunefolk units, 1.16 drops support for the old names.
* Update the Lua function that does a dirty translation of "melee or ranged" to the non-deprecated 1.16 version.
* Added tags "cooperative" and "survival" for searching in the add-on manager, and for Wesnoth 1.16's tag filter

0.2.129
-------

* Add SXC Infernal
* Fix a deprecation warning about `[option]message=`
* Remove the macros for unbalanced maps
* Minor dialogue improvement in SXC Mermaid's Lake
* Update shroud when buying vision (movement, movement costs, speedy)

0.2.128
-------

* Recognise Ageless Era's "precision" weapon special
* Play a sound before showing messages on Rumble and Ramblin

0.2.127
-------

* Fix recruited creeps' upkeep (the "loyal" trait wasn't applied effectively in Wesnoth 1.14)
* Show the number of strike trainings remaining (closes #28)
* Re-add the "earned gold" info to the right-click difficulty menu
* Add a warning about selling duplicate weapons
* Update unit type names for the Dune Scorcher
* Update SXC Mythos' unit type names to match AE 4.24.0
* Fix Spooky Forest's leaders talking in their death events
* Remove the random low-level era (has been broken for a while)
* Improve code readability (various refactoring changes)

0.2.126
-------

* Fix the income bonus for killing enemy bosses (broken in 0.2.123)
* Correct some spelling and grammar, edit the rookie wall-of-text help
* Remove text about SXCR-only weapon special limits
* Fix the image path for arcane attacks' halo images
* Simplify the Cornucopia, as there's no point dropping it
* Refactor the potion handling code
* Fix the line length in the terrain training table
* More changes to make the cached (preprocessed) version smaller

0.2.125
-------

* Refactor to make the cached (preprocessed) version smaller
* Add an "Xtreme + Revive" option
* Add MiE Vampires' specials to the drains and plagues list
* Add Medusa's sculpts (petrify) to the abilities to remove

0.2.124
-------

* Fix revive creating multiple clones

0.2.123
-------

* Add SXC Pursuit, based on the map from Northern Rebirth
* Update the list of plague and drain abilities for Ageless 4.20
* Ask "melee or ranged" in the player's language
* Update AI recruitment settings for Wesnoth 1.14
* Support up to 6 AI sides (as used on Pursuit)
* Spooky Forest in revive mode, respawn near a different shop
* Spooky Forest fix a bug with Pokey, if zombies are killed at the start
* Rename Pressure to Mermaid's Lake

0.2.122
-------

* Fix megacures for Ageless Era 4.20
* Add macros for adding halos to bosses with dark aura and death aura
* Add the halos on SXC Adventure

0.2.121
-------

* The master branch is now for Wesnoth 1.14
* In revive mode, add a note about respawning to the death messages
* Fix for the WML error in Mountains of Doom (an event lacked a name)
* Include the version in the names of Slaughter and Storm Castle
* Make Pressure's south-west sluice guard visible from the start
* Fix some comments and spelling errors

0.2.120+dune
------------

* Branch for Wesnoth 1.13/1.14
* Merge 0.2.119+dune and 0.2.120

0.2.120
-------

* Bugfixes for SXC on Wesnoth 1.14
* Fix for AI leaders being assigned random faction's recruit lists
* Fix for fearless ability having no effect
* Fix for being able to buy fearless twice

0.2.119
-------

* Text and text formatting improvements from SXCR
* Revive support and extra help in rookie mode
* Fix ability upgrades (megacures etc) not working on Wesnoth 1.13.x
* Remove buggy code related to the fearless trait
* Fix for shop graphics glitch on SXC Advanced

0.2.118+dune
------------

* Branch for Wesnoth 1.13/1.14
* Use the Dunefolk's new unit ids
* Change a 1.12 leadership macro to the 1.13.2 version

0.2.118
-------

* Non-flying units can train for deep water and unwalkable terrain
* Fix for shop graphics glitch on SXC Isars Crossfire
* Recognise more AE abilities that now upgrade to megaregen
* Added updated versions of SXC Slaughter and SXC Pressure
* Maps now have per-map descriptions when creating a game
* Maps that need Ageless Era now say that at the start of their description
* Solved some WML warnings that were displayed with less than 5 players

0.2.117
-------

* Support most of Ageless Era's healing and regeneration
* AE abilities upgrade to megacures, minorcures and megaregen
* Remove AE's sculpts (petrify for two turns) ability
* Fixes for shop graphics glitches on several maps
* Prevent trapping a player with SXC Light Cave's terrain changes

0.2.116
-------

* Make terrain modifications immediately update the shroud
* Update map SXC CursedLand for Ageless changes
* Remove delay in showing "player x stands at shop"
* Moving on to the shop can no longer be undone
* Remove unused files

0.2.115
-------

* (and 0.2.115x) Update for EoM and EoMa prefix changes

0.2.114
-------

* (or earlier) Ported to Wesnoth 1.12

0.2.112
-------

* Fixed small typo in macros

0.2.111
-------

* Updated map SXC Wizard of War
* Changed price of some abilities

0.2.110
-------

* Updated map SXC Ramblin

0.2.109
-------

* Updated map SXC Attack
* Changed behavior of enemy leaders (they can attack again)

0.2.108
-------

* Updated map SXC Attack
* Updated map SXC Wizard of War

0.2.107
-------

* Updated map SXC Simple
* Updated map SXC Attack

0.2.106
-------

* Updated map SXC Rumble
* Updated map SXC Isars Crossfire

0.2.105
-------

* Updated map SXC Classic
* Added Ghast to recruit lists for undead AI sides

0.2.104
-------

* Fixed lua error in maps containing Drake Gladiator and Drake Slasher

0.2.103
-------

* Level 0 units disabled in low level era because they are choosed too often by random

0.2.102
-------

* Fixed 80% terrain defense for mounted units

0.2.101
-------

* Updated map SXC Curve
* Added temporary fix for mounted units getting 80% defense in forest

0.2.100
-------

* Fixed Lieutenant and Halberdier in recruit lists

0.2.99
------

* Updated map SXC Figure

0.2.98
------

* Fixed Deathblade in recruit lists

0.2.97
------

* Updated map SXC Chambers
* Added map SXC SpoOky Spiral

0.2.96
------

* Fixed fake leaders sometimes recognized as real leaders and using normal side gold for recruiting

0.2.95
------

* Fixed Giant Spider in recruit lists

0.2.94
------

* Updated map SXC Chambers

0.2.93
------

* Fixed fake leaders moving from keep and never returning back
* Updated map SXC Chambers

0.2.92
------

* Updated map SXC Chambers

0.2.91
------

* Updated map SXC Mythos

0.2.90
------

* Fixed bug in ability Megaregenerates causing extra hitpoints from yellow/blue potions was lost when poisoned
* Updated map SXC Mythos

0.2.89
------

* Updated map SXC Mythos

0.2.88
------

* Fixed macro for disabling recruting for players

0.2.87
------

* Updated map SXC Attack
* Updated map SXC Extend

0.2.86
------

* Updated map SXC Figure
* Updated map SXC Extend

0.2.85
------

* Updated map SXC Figure

0.2.84
------

* Updated map SXC Figure
* Updated map SXC WizardOfWar

0.2.83
------

* Updated map SXC Figure
* Fixed DWARFPLATE event

0.2.82
------

* Updated map SXC Spiral
* Updated map SXC Figure

0.2.81
------

* Updated map SXC Spiral

0.2.80
------

* Updated map SXC Rush
* Updated map SXC Spiral

0.2.79
------

* Changed difficuty settings to more correspond with actual macros and map settings

0.2.78
------

* Updated maps affected by incorrect leader respawns when they are still alive
* Updated map SXC Rush

0.2.77
------

* Updated map SXC Channels
* Updated map SXC Rush
* Added fake side macros, include leader, gold, income, recruit list from AI side leader or own, recruiting at start of turn

0.2.76
------

* Updated map SXC Channels

0.2.75
------

* Updated map SXC Channels

0.2.74
------

* Updated map SXC Channels

0.2.73
------

* Updated map SXC MountainsOfDoom

0.2.72
------

* Updated map SXC MountainsOfDoom

0.2.71
------

* Updated map SXC MountainsOfDoom

0.2.70
------

* Updated map SXC IsleOfTheDead
* Updated map SXC WizardOfWar
* Updated map SXC MountainsOfDoom
* Level 0 units added back to SXC Default Low Level Era and all selectable units are also possible to get in random selection

0.2.69
------

* Updated map SXC IsleOfTheDead

0.2.68
------

* Updated map SXC IsleOfTheDead

0.2.67
------

* Added special SXC Default Random Low Level Era with antiduplicates macro (all randomly selected units, that match the same unit type with lower side number, are at start automatically replaced with different unit, not matching any other unit controled by any other player and result is logged)
* Updated map SXC IsleOfTheDead
* Updated map SXC CursedLand

0.2.66
------

* Updated map SXC CursedLand
* Updated map SXC Adventure

0.2.65
------

* Updated map SXC CursedLand

0.2.64
------

* Updated map SXC CursedLand

0.2.63
------

* Updated map SXC CursedLand
* Updated map SXC Wizard of War

0.2.62
------

* Updated map SXC CursedLand
* Updated map SXC Wizard of War

0.2.61
------

* Updated map SXC Wizard of War
* Updated map SXC Trapped
* Map names are now displayed in lobby without underscores in the name for all people who have installed the same addon version

0.2.60
------

* Updated map SXC Trapped
* Fixed some image positions for shop

0.2.59
------

* Updated map SXC Simple

0.2.58
------

* Updated map SXC Simple

0.2.57
------

* Updated map SXC Ramblin
* Some other small fixes

0.2.56
------

* Fixed RingOfDarkness event
* Updated map SXC Ramblin
* Updated map SXC System

0.2.55
------

* Updated map SXC System

0.2.54
------

* Updated map SXC System

0.2.53
------

* Updated map SXC System
* Added macros for ability removal
* Added ability Hide

0.2.52
------

* Updated map SXC Isar's Crossfire
* Updated map SXC Stronghold

0.2.51
------

* Updated map SXC Stronghold

0.2.50
------

* Updated map SXC Rumble

0.2.49
------

* Updated map SXC Rumble (this one was very hard to balance and required lot of testing after every change)
* Fixed some minor bugs

0.2.48
------

* Added macros for ghostlike units
* Updated map SXC Rumble
* Updated map SXC SpoOky's Forest

0.2.47
------

* Fixed macro for turn limit
* Updated time limit for some maps
* Added cashstop variables for sides 6 and 7 in map SXC Rumble
* SXC version is now displayed also in map name

0.2.46
------

* Updated map SXC Rumble

0.2.45
------

* Fixed wrong variable name in melee damage upgrades for weapon price calculation

0.2.44
------

* Updated map SXC Light Cave

0.2.43
------

* Updated map SXC Light Cave
* Updated all macros checking for enemy leaders to match with `role="big_boss"` instead with `canrecruit="yes"` to support fake leaders in future
* Limited number of recruits for faster calculations on enemy turns later in game - when ai side has more than 30 recruits (guards are not included in this calculation), leader can only recruit 1 more unit in that turn

0.2.42
------

* Updated map SXC Maze

0.2.41
------

* Fixed description for Leadership
* Fixed Cloak function

0.2.40
------

* All maps that are not balanced yet are now moved into unbalanced directory to help people who are experiencing problems with loading the addon (in Windows). Maps that are not yet adapted to new macros don't have properly set variables and advance checking events and are moved into the unbalanced directory and are not active for playing.

0.2.39
------

* Updated map SXC Curve

0.2.38
------

* Fixed bugs in macros
* Changes in upgrades for damage and strikes
* Updated map SXC Classic

0.2.37
------

* Updated map SXC Classic

0.2.36
------

* Updated map SpoOky's Forest

0.2.35
------

* Changed sx trait
* Updated map SpoOky's Forest

0.2.34
------

* Fixed bug in shop macros
* Removed drakes, merfolk and nagas from random selection until all maps will be balanced

0.2.33
------

* Updated map SpoOky's Forest

0.2.32
------

* Updated map SpoOky's Forest
* Removed Level 0 units from era

0.2.31
------

* Updated map SpoOky's Forest

0.2.30
------

* Updated map SpoOky's Forest

0.2.29
------

* Updated map SpoOky's Forest

0.2.28
------

* Added testing version of map SpoOky's Forest
* Original side macros moved into deprecated

0.2.27
------

* Changed all remaining unit macros and updated affected maps (SXC Advanced, SXC Adventure, SXC BraveHeart) to work with them
* Changed side definition macros for both player and ai sides (this also allows to set side colors in scenario to better visible colors in multiplayer chat) and used in (SXC Advanced, SXC Adventure, SXC BraveHeart) to test before marking original macros as deprecated

0.2.26
------

* Changed unit macros and updated affected maps (SXC Advanced, SXC Adventure, SXC BraveHeart) to work with them

0.2.25
------

* Fixed most item macros
* Updated weapon specials
* Changed and added some unit macros

0.2.24
------

* Fixed some item macros
* Fixed image of last shop in SXC Adventure
* Updated SXC BraveHeart

0.2.23
------

* Fixed some unit macros
* Updated SXC BraveHeart

0.2.22
------

* Fixed some unit macros

0.2.21
------

* Updated SXC BraveHeart

0.2.20
------

* Updated SXC Adventure
* Changed berserk from shop to 10 rounds

0.2.19
------

* Updated SXC Adventure and SXC BraveHeart maps

0.2.18
------

* More unit macros moved to deprecated, new macros are more universal
* Macros in SXC Advenced, SXC Adventure and SXC Chambers replaced by new macros
* Changed shop images in SXC Adventure and SXC Chambers
* Changed impassable mountains in snowy area into snowy impassable mountains in SXC Chambers map

0.2.17
------

* Changed attacks of roaming bosses in SXC Advanced map

0.2.16
------

* Changed roaming bosses and fixed specials on ai9 in SXC Advanced map

0.2.15
------

* Abilities Ambush, Nightstalk and Submerge are removed because AI is ignoring them.
* Added macro for changing weapon damage type on leaders
* Changed weapons and added weapon specials for bosses in SXC Advenced map
* Changed look of shops in SXC Advanced map to buildings instead of signpost

0.2.14
------

* Fixed bug causing that unit was not checked at start of scenario

0.2.13
------

* Natural unit's attacks with damage type energy and force are now replaced with fire and impact
* Natural unit's abilities Concealment and Teleport are now removed because there is not use for them in SXCollection maps and removing them enables to see other abilities in the list

0.2.12
------

* Changed desert area in SXC Adventure map
* Fixed fearless on units without availability=musthave for maximum unit level

0.2.11
------

* Added new macros for enemy
* Changed SXC Adventure map to reflect changes in macros

0.2.10
------

* Added `SXC_ENEMY_LEADER_SPECIALS` macro
* Disabled 125 gold bonus for enemy leaders on player's unit death
* Changed SXC Adventure map

0.2.9
------

* Fixed some bugs in macros
* Mountains in snowy areas changed to snowy mountains
* Changed speed of roaming bosses in SXC Advanced map

0.2.8
------

* More changes in SXC Advanced map
* Some macros marked as deprecated and replaced by more powerful macros

0.2.7
------

* Changed price for strikes

0.2.6
------

* Changed weapons and damage for enemy leaders in SXC Advanced map
* Changed recruit lists for enemies in SXC Advanced map

0.2.5
------

* Automatic terrain defense adjusting for units with too low (less than 40%) or too high (greater than 80%) terrain defense
* Fixed some items macros

0.2.4
------

* Fixed wrong informations about abilities in shop
* Armor is now recalculated to help units with bad default armor but also to lower armor on units with too high armor, which also enables better
* selection of needed armor for players. Total positive armor is now 240 after buying all possible upgrades.

0.2.3
------

* Fixed dropping items on players death
* Changed ability macro definition names for compatibility with default abilities and weapon specials macro names
* Changed prices for terrain training to help units with very bad movement to have the additional upgrades bit less expensive

0.2.2
------

* Due to changes in engine in 1.8.x are now native unit's abilities replaced only after reaching maximum level
* Changed amount and prices of buyable movement based on speed of the unit
* Fixed incorrect displaying of icons in terrain training shop section
* Fixed sound file name for flaming dart

0.2.1
------

* Fixed ability soulstealer

0.2.0
------

* Renamed back to SXCollection and fixed informations about version in the code

SXCollective 0.0.0 - 0.19.0 maintained by pkz

0.1.5
------

* Adjusted AI recruitment patterns in SXC BraveHeart and SXC Classic again

0.1.4
------

* Adjusted AI recruitment patterns in SXC BraveHeart and SXC Classic

0.1.3
------

* Fixed minor bugs in guards sides and moving bosses health in SXC BraveHeart

0.1.2
------

* First AI recruits appear on map already at start of first turn so players must not wait 2 turns before they attack in SXC BraveHeart
* Fixed Ability shop functionality for fearless and skirmisher

0.1.1
------

* Added some guards and adjusted armor of AI bosses in SXC BraveHeart map

0.1.0
------

* Fixed bug in ability Leadership, available in shop, causing 100% increase of power for owner of any level, should be 20% for owner at any level
* Added more moving bosses waves and increased their strenght and adjusted income for AI, include some kill events providing support gold to AI in SXC BraveHeart

0.0.69
------

* Changed starting gold for all sides in SXC BraveHeart to 800 gold
* Adjusted AI settings to SXC default for SXC BraveHeart and SXC Classic

0.0.68
------

* Changed AI8 and AI9 leader's weapons and health points, moving bosses strenght and starting brutal value from -5 to -10 and two events will change it +5 each, so it's then basically as if it had starting value 0 in SXC Classic. This is special setting for this map, because players start at longer distance from shop and mostly they can't reach shop before turn 2 or 3.

0.0.67
------

* Changed moving bosses health points in SXC MountainsOfDoom
* Changed Abilities shop section functions (default abilitity is replaced with bought one if it's based on same type of ability, i.e. megaregenerates replaces regenerates)

0.0.66
------

* Changed recruitment paterns for leaders, decreased brutal and added some kill events simulating revenge by increasing gold for AI in SXC MountainsOfDoom
* Lowered price for terrain training from 30 to 25 gold

0.0.65
------

* Changed speed of Winged Daemon moving bosses in SXC IsleOfTheDead
* Changed all AI leaders attacks and most guards in SXC MountainsOfDoom for better balance
* Added macro, automatically replacing default steadfast ability with `sxc_steadfast`

0.0.64
------

* Added new macros for enemy leader modifications and changes applied in SXC IsleOfTheDead, SXC CursedLand and SXC WizardOfWar

0.0.63
------

* Added new macros for enemy guards allowing adding weapons and changes applied in SXC IsleOfTheDead map for testing

0.0.62
------

* Added new macros for enemy modification and applied in SXC IsleOfTheDead map for testing

0.0.61
------

* Changes some settings in SXC Classic to achieve better playability

0.0.60
------

* Fixed music list macro
* Changed damage/strikes of AI7 to AI9 leaders to gain better game speed in SXC CursedLand

0.0.59
------

* Changed damage/strikes of AI8 and AI9 and some guards to gain better speed while calculating attack results in SXC WizardOfWar

0.0.58
------

* Fixed bug in sx trait, causing adding 1 MP with every AMLA/level up

0.0.57
------

* Lowered starting brutal variable and disabled Armageddon Drake in SXC WizardOfWar
* Lowered price for Megacures from 200 to 125 gold

0.0.56
------

* Changed `SX_ENEMY_UPGRADE` macro - creeps now get extra weapon only while they don't have own weapon for that range
* All units get +1MP at start with sx trait

0.0.55
------

* Fixed not displayed weapon damage - strikes immediatelly after buying weapon
* Changed AI settings for both players and AI
* Updated map SXC Slaughter

0.0.54
------

* Movement upgrade in `SX_ENEMY_UPGRADE` macro changed from percentual to additional basis
* Fixed 1 or 2 HP misscalculated health of some moving bosses and guards in SXC CursedLand and SXC WizardOfWar

0.0.53
------

* Changed `SX_ENEMY_UPGRADE` macro to better suit current shop and gold system
* Changed moving bosses, guards and AI leaders in SXC CursedLand and SXC WizardOfWar for better balanced gameplay

0.0.52
------

* Fixed minor syntax errors in pkz's map SXC Slaughter
* Changed AI settings for SXC WizardOfWar
* Fixed minor syntax error in object and effect tags in SXCmacros.cfg

0.0.51
------

* Added SXC Default Low Level Era

0.0.50
------

* Changed resistance of moving bosses and Draugs changed to Death Knights in SXC WizardOfWar
* Changed resistance of moving bosses in SXC IsleOfTheDead
* Added pkz's map SXC Slaughter

0.0.49
------

* Changed AI leader's attacks, damage and resistance in SXC IsleOfTheDead

0.0.48
------

* Fixed graphics for potions in inventory

0.0.47
------

* Fixed position of Spectre guard at position 32,15, recruit list for AI9 and added 125 gold chest at position 32,27 in SXC WizardOfWar
* Fixed path to file from icon/deep-water.png to icons/deep-water.png in SXCmacros.cfg

0.0.46
------

* Changed attacks of AI9's guards, added 2 new guards and added trigger to ring at 11,27 opening short way to western shop in SXC WizardOfWar

0.0.45
------

* Added some new guards and changed bosses and recruitments of AI on map SXC WizardOfWar

0.0.44
------

* Increased resistances of spawning moving bosses in SXC Cursed Land for gaining more challenge

0.0.43
------

* Fixed 100% defense in undefined terrains (to 50%), defined should stay untouched

0.0.42
------

* Found another plague type attack and together with all found summon ability variations added into sx trait for automatical removing

0.0.41
------

* Unit "BM Wood's Druid" caused error while loading saved game. Fixed by removing unit from recruit list

0.0.40
------

* Changed power of attacks for moving bosses in SXC CursedLand
* `SX_xxx_ARMY_BUFF` macros was unexpectedly used from another map, causing enemy leaders to recruit wrong unit types. Macros are now fixed by
* specifying name of map in their name
* Removed unwanted `unstore_unit` tag from `SX_ARMORY_LIMIT` macro

0.0.39
------

* Changed wepaons of AI8 and AI9 leaders in SXC CursedLand for harder elimination

0.0.38
------

* Changed colors for Hide/Show options
* Fixed bug in spawning units for AI9 in SXC CursedLand
* Added plague(BM Bloodborn) into forbidden attack specials (trait sx)

0.0.37
------

* Changed difficulty setting for brutal variable and gold amount gained from killed enemy units

0.0.36
------

* Hide menus applied also for Weapons shop and Specials shop

0.0.35
------

* Sorted Enhancements menu, removed ability to buy mixed melee and ranged damage/strike in one option
* Fixed bug in Weapon specials shop (player needed to have +1 more gold than is the price of the special)
* While buying or canceling movement training, moves left in that turn will change too (that will allow to leave shop hex even with 0 moves left, except situation, when player can't buy more movement)

0.0.34
------

* Fixed bug in Enhancements shop menu

0.0.33
------

* Added undo function for Enhancements shop menu

0.0.32
------

* Added function to hide melee or ranged upgrades in shop menu

0.0.31
------

* Changed attacks and health points of all bosses and guards in SXC CursedLand for more challenge

0.0.30
------

* Fixed bug in shop (+3 melee strikes showed 200 gold price but 210 gold was paid off)
* Fixed bug in SXC CursedLand (wrong position for trigger opening 4th shop)

0.0.29
------

* Added completely new map SXC CursedLand
* Adjusted macros for guardians

0.0.28
------

* Added new forbidden attack into sx trait, fixed damage and strikes for AI 8

0.0.27
------

* Changed macro for guardians to better suit needs in new maps and accordingly changed this part in all previously included maps

0.0.26
------

* Fixed bug causing players not gaining money while selling specials from weapons

0.0.25
------

* Fixed wrong calculation for weapons prices, caused by change in weapons between Wesnoth versions 1.6 and 1.6.1 (they are now affected directly by [effect] tag, in version 1.6 it was only in [modifications]). This version should now work fine in Wesnoth version 1.6.1

0.0.24
------

* About 85% of all macros were completely rewritten from scratch.
* New shop system, droppable items and potions, weapon based specials, new abilities, sellable weapons and specials and much more.
* This version of SXCollection only works correctly in Wesnoth 1.6

0.0.23
------

* Disabled recruitment for all players

0.0.22
------

* Undefined terrain defenses causing 99% defense changed to game default 50%
* Enemy recruits have now changed attack more close to standard damage-attacks ratio

0.0.21
------

* Corrected macro calculating maximum upgrades for resistances
* Changed Terrain training shop macro and added ability to buy terrain training for canyon terrain

0.0.20
------

* Changed procedure for resistance changes from `apply_to=resistance` to `[store_unit]` variable for shop and items

0.0.19
------

* Fixed right-click menu for using potions, now it is available in all included maps
* Added 2 s delay to see selected difficulty before information about player comming on shop hex

0.0.18
------

* Changed procedure for defense changes from `apply_to=defense` to `[store_unit]` variable with checking minimum and maximum defense limit
* Extra hitpoints from yellow and blue potions are now transfered also while unit reaches experience to advance, so that is not wasted by using it in wrong time

0.0.17
------

* Fixed bug from original macro causing that function upgrading enemy units was applicated 2x after reaching brutal 140 and 3x after brutal 160

0.0.16
------

* Fixed bug causing error while loading saved game. Source of this was different handling of constants and variables passed to macros. All affected items were duplicated to achieve correct variable names of items.

0.0.15
------

* Added new functions and rebuilded structure of shop menu
* Fixed bug causing access to shop for any unit on map while players leader is on shop hex

0.0.14
------

* Fixed amount of gold dropped by killed moving bosses
* Hint before first shopping has now greater size of font and red color in first line

0.0.13
------

* Fixed bug in shop macro. Undo after checking attack result should be now functional again

0.0.12
------

* Changed shop macro to send message to all players while player steps on Shop
* Shop is now accessible by rigth button click and selecting Enter shop

0.0.11
------

* Moving bosses now can drop items (also on the same hex), while they are killed, seems functional now
* Function is now implemented in SXC BraveHeart, SXC Classic and SXC WizardOfWar

0.0.10
------

* Further changes in abilities of bosses in SXC BraveHeart and SXC Classic
* Spawned moving bosses now can drop items on their death while defined in scenario (still buggy so unused yet)
* Added guards over rings in SXC Classic and moving bosses on respective side now appear behind them
* Added trait loyal to all enemy creeps

0.0.9
-----

* Changed abilities of bosses in SXC BraveHeart and SXC Classic
* Changed respawns in SXC BraveHeart and SXC Classic to be triggered only if bosses are killed too fast at start of game, except undead boss
* Added automatic labels redrawing at start of new turn in case any player clears all labels
* Changed location of images for menu icons from images/ into proper location in images/icons/ directory

0.0.8
-----

* Fixed bug in SXC BraveHeart - bosses respawn event at turn 22 was accidentally deleted in 0.0.7
* Value of `passive_leaders` for all AIs in SXC BraveHeart and SXC Classic changed to `passive_leader=no`
* Added proper icons for potions in context menu

0.0.7
-----

* Changed macros for more items and potions
* Changed bosses in SXC Classic for better challenge

0.0.6
-----

* Fixed chest button event changing terrain in SXIsleOfTheDead and SXMountainsOfDoom (wrong conversion of terrain letter to new version)
* Changed macros for chests and rings
* Changed names of scenarios for better identification in multiplayer lobby

0.0.5
-----

* Fixed bug causing some people freezing computer while displaying objectives dialog after getting control

0.0.4
-----

* Added maps SXIsleOfTheDead and SXMountainsOfDoom from SXAddonPack 1.18b for Wesnoth 1.2 by Mabuse
* Switched to macros from 2.56c2 version of SXAddonPack by Mabuse
* Changed bosses in SXBraveHeart for better challenge

0.0.3
-----

* Added improved map SXWizardOfWar from SXAddonMaps 1.2 by Mabuse

0.0.2
-----

* Added map SXClassic from the same version of SurvivalXtreme

0.0.1
-----

* First release with SXBraveHeart map from SurvivalXtreme for Wesnoth 1.2.x and macros from SurvivalXtreme 2.08b

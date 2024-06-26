SurvivalXtreme Collection
=========================

A set of individual scenarios where 1-5 players cooperate to defeat the computer-controlled forces.
This is an add-on for the game [Wesnoth](https://www.wesnoth.org/).

As of 0.3.12, the `master` branch is for Wesnoth 1.18.

In-game description (for the add-ons server)
--------------------------------------------

Collection of SurvivalXtreme maps. In SurvivalXtreme you don't recruit, but can enhance your leader during the game. You get gold, extra moves and an extra attack for every enemy you kill. All players cooperate against the AI, and most maps are for up to five players.

Many of these maps are balanced for play with characters from the SXC Default Low-Level Era. Some maps require all players to have Ageless Era installed, as the AI will use units from that era even if the players' units are from the default era.

This pack also contains some abandoned scenarios in the 'unbalanced' directory, the aim of this is to collect the maps which could be turned back in to playable scenarios. To enable these maps, you need to edit the add-on.

Addon moved to Wesnoth v1.12 by ChaosRider, and currently maintained by Octalot. If you find bugs, please comment in the forum thread, or pm Octalot.

Adding your own maps
====================

Making a new map requires you to learn some WML, but for SXC a lot of it is cut-and-paste. The simplest of the existing WML files is `scen_def/SXC_Curve.cfg`, and then there's some standard copy-and-paste for "when a player moves to hex x,y, change some impassible terrain to walkable terrain".

As long as all players have the SXC add-on, only the player creating the game needs to have the .cfg and .map files for the new map. That data is transferred to all players when the game starts, so the game can continue even if the host with the original files disconnects.

If your own .cfg and .map files are in the SXCollection folder, they'll get deleted if the add-on updates. There's an explanation of how to put them in a separate add-on in a [post in the forum thread](https://r.wesnoth.org/p690726); doing that also means you could easily upload it to the add-ons server.

Customising the macros
======================

This isn't needed for creating extra maps, but as the code is GPL'd you're also able to copy the macros into you own add-on and customise them. If you do that, please find the two lines that are `id=sxc_shared_events`, and change those to a unique ID. Wesnoth's engine might load the wrong version if two add-ons have resources with the same id.

Feedback
========

Please use either Github's issue tracker, or [Wesnoth's forums](https://forums.wesnoth.org/viewtopic.php?f=15&t=31221)

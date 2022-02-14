Labirinth Game Boy game changelog
=====

# dev-platformer (unreleased)

* Prepared bonus Arcade platformer scene layout and props
	* Platformer type scenes collisons are broken, waiting for Chris to repair it: https://github.com/chrismaltby/gb-studio/issues/997

## v 1.0.3 (2022-02-13)

* Color fixes
* Arcade background update

# v 1.0.2 (2021-01-25)

* Restored save/load system
	* New game/continue on start screen
	* Save/load/restart in-game

## v 1.0.1 (2021-01-06)

* Version with save / load capability released

## v 1.0  (2021-01-06)

* Game release

## script-dev (2021-01-06)

* Game internals and important mechanics
	* Completely rewritten HUDs code from 'if's to 'switch'
	* Disabled faulty save/load system (waiting for GB Studio bugfix)
	* Difficulty choice - easy (7 good deeds) and hard (all 11 good deeds)
* Other changes
	* Music change when Cookie is reunited with Mayor
	* Mallard acceptance bugfix
	* Minor dialogues fixes
	* Palletes fixes
	* Title screen restored
* Deployed formats
	* Original Game Boy ROM
	* Game Boy Color ROM
	* Pocket file
	* Web version

## release candidate (2021-01-05)

* In-game changes and fixes
	* Receiving Duck now only on condition of giving information to Jenna
	* Extended options with Bobby in Arcade
	* Minor dialog fixes
	* Fixed major teleport glitch in Village
	* Fixed minor graphic glitch in East Village
	* Fixed minor graphic glitch in East Village and mistake in Dungeon
	* Some recolors in CGB version

* Other changes
	* New file names
	* Manual
	* Updated box art

## beta 2 (2022-01-04)

* Update player hitbox
* Redone teleport triggers
* Village background glitch fix
* Minor changes to Town map
* Upgraded coins system
* Other bugfixes
* End credits

## beta 1 (2022-01-04)

* New Town sublocation: Arcade
	* Bobby + videogames interaction
* Cutscenes
	* Hat opening sequence + player sprite swap
	* Museum reunion outro
* HUD efficiency changes
* New music tracks (thanks [Mr. V](https://victorvaldez.itch.io/gb-studio-tracks-vol-1)!)
* Updated backgrounds and sprites
	* New player sprite (thanks [route1rodent](https://route1rodent.itch.io/16x16-rpg-character-sprite-sheet)!)
	* Bobby sprite (thanks [0x72](https://0x72.itch.io/2bitcharactergenerator)!)
	* Redone title screen
* Files cleanup


## alpha 0.9 (2022-01-02)

* Added achievement count + HUD
* Added Town location + Bakery
	* Added Betty, Hobo, and Good Deeds Fairy
* Added Castle location + cellars sublocation
	* Added Corrupt curator interaction
* Added Duck interaction
	* Rhonda interaction expanded
	* Variable for Town girl interaction
* Added ending mechanics
* New Hornets solution without fire (also actually affects Rowan interaction now)
* Extended Stephen the Skeleton meeting action
* Added Hedgehog and Squirrell
* Replaced and added several sprites (thanks [MonkeyImage](https://monkeyimage.itch.io/world-tilesets-remastered), [GamebowGames](https://gamebowgames.itch.io/16x16-small-animals-for-use-with-gbstudio), and more!)
* Background graphics and palettes fixes
* Optimizing

## alpha 0.8 (2021-12-29)

* Added East village houses sublocations + field sublocation
	* Added Tina interaction
	* Added Granny interaction
	* Added Sally interaction
	* Added Rhonda interaction
* Added Jenna's hut location + interaction
* New hut interior graphics (thanks [GumpyFunction](https://gumpyfunction.itch.io/)!)
* New actor sprites (thanks [Wintonson](https://wintonson.itch.io/gb-studio-sprites)!)
* New splashscreen for end sequence
* More color works
* Bugfixes for nasty 2 collisions

## alpha 0.7 (2021-12-28)

* Added Blacksmith Tony's forge location + interaction
* Added City location (no interactions)
* Added Cave hobo interaction
	* Variable for Town hobo interaction
* Added Money HUD
* Fixed a severe fail in save & load system
* Added new music tracks (thanks [AJ Booker](https://ajbooker.itch.io/fantasypack)!)
* Minor enhancements
	* Fire wiseman teaching failsafe
	* Dialog fixes
	* Color work
	* Background art fixes
	* Version numbering on title screen

## alpha 0.6 (2021-12-26)

* Save & load system
* Initial color work
* Box art
* New locations
	* East
	* East village placeholder
	* Cave
* Minor enhancements
	* Animated Hornets
	* Forest hut background
	* Healing hut background
	* Intro sequence background
* Bugfixes: Doctor, Forest hut

## alpha 0.5 (2021-12-23)

* Added Road east location with clearing sublocation
* Health system expanded
  * Added Health status HUD (thanks [Pearacidic](https://gbstudiocentral.com/tips/basics-creating-a-hud/)!)
  * Added death handling
  * Rewritten Healing hut interactions
	* Added Doctor actor
  * Added Food by the fire healing interaction
* Added intro  sequence
* Updated graphics for Village sublocations (thanks [Jeremias19](https://jeremias19.itch.io/)!)
* Updated various UI elements
* Updated various collisions, dialogues _et al_

## alpha 0.4 (2021-12-22)

* Finished the Forest location
  * Added Cemetery sublocation
  * Added Forest hut sublocation
  * Added Ghosts movement in horizontal Forest
  * Added Slaying Ghosts subquest
* Added money
  * Meaningful interaction added: Forrester
* Expanded Mayor interaction
* Various minor tweaks to actors and triggers

## alpha 0.3 (2021-12-22)

* Initial release - playable game deployed to [itch.io](https://godai78.itch.io/labirinth)
* Temporary graphics used, by Chris Maltby, Rekkimaru
* Initial health system introduced w/ health points interactions
* Locations introduced: Labyrinth, Meadow, Village, Forest (only semi-done)
* Meaningful interactions: Stephen the Skeleton, Fire Wiseman, Ladder Saleswoman, Village Soldier, Village Mayor
* Quests introduced: Fire spell, Hornet nest, Lost hamster, Obtaining pass

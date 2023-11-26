# Stardew Valley Multiplayer Time Mod

This is a modified version of MultiplayerTime [[github](https://github.com/MaciejMarkuszewski/StardewValleyMod)] [[Nexus](https://www.nexusmods.com/stardewvalley/mods/2543)].

Like the original, this pauses time in multiplayer if all players on the server would be paused. This version additionally slows down time when _some_ (but not all) players on the server would be paused, proportional to the number of players paused. For example, with 3 players where one player should be paused, time will go at 2/3 the normal rate. With 4 players and 3 paused, time will go at 1/4 speed.


## Installation

Install the dependencies listed below, then download the mod files from the github releases, unzip, and add it to your mods folder. Note that I have only released it on github, as I do not like that Nexus requires logging in to download anything.

All players on the server need the mod installed for it to work. However, as long as the host uses this version, other players can use the original version of the mod and it will still work. (at least with version 4.2 of the original mod, shown as version 1.7 in Nexus. May stop working with future updates) I do not think both versions can be installed at the same time for a single player, though I haven't tested this case.


### Dependencies:
 - [SMAPI](https://smapi.io/)
 - [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098)

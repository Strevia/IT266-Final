
This is the complete source code for Quake 2, version 3.19, buildable with
visual C++ 6.0.  The linux version should be buildable, but we haven't
tested it for the release.

The code is all licensed under the terms of the GPL (gnu public license).  
You should read the entire license, but the gist of it is that you can do 
anything you want with the code, including sell your new version.  The catch 
is that if you distribute new binary versions, you are required to make the 
entire source code available for free to everyone.

The primary intent of this release is for entertainment and educational 
purposes, but the GPL does allow commercial exploitation if you obey the 
full license.  If you want to do something commercial and you just can't bear 
to have your source changes released, we could still negotiate a separate 
license agreement (for $$$), but I would encourage you to just live with the 
GPL.

All of the Q2 data files remain copyrighted and licensed under the 
original terms, so you cannot redistribute data from the original game, but if 
you do a true total conversion, you can create a standalone game based on 
this code.

Thanks to Robert Duffy for doing the grunt work of building this release.

John Carmack
Id Software

--- Phillip Nissen Mod---
This is a mod for Quake 2 that adds several mechanics from Among Us, Town of Salem, and other similiar style games to Quake 2. 
To install, create a new folder in your Quake2 installation pnissen. Place the generated /game/release/gamex86.dll file in the pnissen folder inside Quake 2.
In addition, place the "credits" file in the root of this folder into the pnissen folder to see the in-game help screen. Added features include:
- GHOST MODE: If you die during a death match, you enter ghost mode. In ghost mode, you can fly around the map and watch the other players.
- VOTING: You can begin a vote by typing the command "vote start". During an ongoing vote, any player can type "vote <number>" to vote for a player. A vote can be ended by typing the command "vote end". Once a vote ends, the player with the most votes will die.
- ROLES: Five roles have been added. To assume a role, type the command "role <number>". To activate a role, type the command "role activate", or press r. The roles added include:
    1. Mafioso, who can kill non-town players.
    2. Sheriff, who can attempt to arrest a player. If this player is a mafioso, they will die. If the player is town, the sheriff will die.
    4. Veteran, who can go on "alert". While on alert, any player who interacts with the veteran will die, and the veteran cannot be killed.
    6. Doctor, who can heal a player. While a player is healed, they cannot be attacked.
    8. Investigator, who can investigate a player. This will tell the investigator whether the player is good or evil.
(Note with roles: 0 is considered a generic town role, while odd numbers between 3 and 7 are considered generic mafia roles).
- MINIGAMES: Five minigames have been added. These can be played via the command "mini <name_of_minigame>". These include:
    files: Stand still and wait for a file to be downloaded and then uploaded. This minigame succeeds once the file is fully uploaded, and fails if the player moves before then.
    code: A code will appear on screen consisting of the letters M and N. Type them in the correct order to succeed. This minigame fails if the player types an incorrect key.
    temp: A desired temperature and a current temeprature will appear on screen. Using the M key to make the current temperature go up, and N key to make it go down, make them equal. This minigame has no failure condition.
    fuel: Empty the fuel gauge by pressing M the desired number of times. This minigame does not fail.
    count: Press M the correct number of times, then press N to confirm. Fails if M is pressed an incorrect number of times.


Barony Acorns README: February 9, 2025
The Acorns fork of Barony is available on github here: https://github.com/NutNibbler/BaronyAcorns

This version of Barony has expanded availability of options for modders to adjust elements in the game, through a new format of gameplaymodifiers.json
 - NEW(Feb 14, 2025): Inter-floor values have been split into a new file "globals.json", purpose of this new file is to allow creators to make map packs without overriding gameplay elements. 
 
Note that vanilla mods should still work with this version of Barony, however complex mods that use their own .exe file(like this one) 
    or require special files, won't work.
 - Vanilla Mods that should work: Map packs, Item mods, and Monster mods.
 - Vanilla mods that are liable to have issues: Mods that use the gameplaymodifiers.json file, or the en.txt language file(Acorns adds new lines to the english language pack).

Barony Acorns IS NOT compatible with crossplay, console, or Epic clients. This version of barony is STRICTLY limited to Steam, LAN, or splitscreen 
    play. There are currently no plans to implement crossplay or Epic compatibility due to complications with app certificates.

Upon starting this version of Barony it may get flagged by antivirus due to a lack of a certificate, just run anyways.

For details on what Barony Acorns changes, check KEYCHANGES.txt in the github. Note that this mod intends to serve as a foundation 
    for modders to create their own mods with additional customization. Installing just this mod wont change the gameplay too much.

Install Instructions:
     - Subcribe to BaronyAcorns in the Steam workshop.
     - Option 1:
        - Move BaronyAcorns.exe to the main directory of your Barony installation.
     - Option 2:
        - Create a copied installation of Barony and add this copy as "BaronyModded" or something similar as a custom game in your Steam library.
        - Move the BaronAcorns mod folder to this copied installation, and replace the barony.exe file with the BaronyAcorns.exe provided.
     - Open BaronyAcorns and ensure you always have the BaronyAcorns mod loaded, advised to keep this mod at load order 1. If you dont load this mod, the client will crash on starting a game.
        - As long as BaronyAcorns is in load order 1: additional mods will overwrite the default settings of BaronyAcorns.
    
MODDERS: 
     - A sample of the new gameplaymodifiers.json is inside the mod folder
        - Find the mod folder at *steam directory*/steamapps/workshop/content/371970/3424603038
        - Using the /jsonexportgameplaymodifiers command in-game will generate the new gameplaymodifiers sample in the Barony data directory
        
     - A sample of the new globals.json is inside the mod folder.
        - Location of this file in within the same directory as gameplaymodifiers.json
        - Using the /jsonexportglobals command in-game will generate a new globals sample with the values from your current run.
        
     - The secretrooms.txt file is also located in the mod folder.
        - Any custom secretrooms.txt files must be placed inside the /maps directory of your mod.
     
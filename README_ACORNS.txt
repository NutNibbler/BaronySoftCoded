Barony Acorns README: February 9, 2025
The Acorns fork of Barony is available on github here: https://github.com/NutNibbler/BaronyAcorns

This version of Barony has expanded availability of options for modders to adjust elements in the game, through a new format of gameplaymodifiers.json

Note that vanilla mods should still work with this version of Barony, however complex mods that use their own .exe file(like this one) 
    or require special files, won't work.

Barony Acorns IS NOT compatible with crossplay, console, or Epic clients. This version of barony is STRICTLY limited to Steam, LAN, or splitscreen 
    play. There are currently no plans to implement crossplay or Epic compatibility due to complications with app certificates.

Upon starting this version of Barony it may get flagged by antivirus due to a lack of a certificate, just run anyways.

For details on what Barony Acorns changes, check KEYCHANGES.txt in the github. Note that this mod intends to serve as a foundation 
    for modders to create their own mods with additional customization. Installing just this mod wont change the gameplay.

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
     - A sample of the new gameplaymodifiers.json is at
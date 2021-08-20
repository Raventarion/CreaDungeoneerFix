# CreaDungeoneerFix

Helloo, I recently got back to the game and got to the topic of the customs from the dungeoneer having disappeared,
since I couldn't find mods or fixes for it, I did it myself.

Imma talk about what I found, so if you just want the method, it's below.

First of all, the thing really was disabled by default, idk the reason (bugs maybe) but it was supposed to be unlocked by placing a silvan idol.
I originally wanted to make a mod but i'm too lazy,
so I just modified the game files to try making it unlock after beating a boss/placing the idol but idk how to do it hehe.
It's just enabled by default with this fix
The code for it was all there so I just had to remove the "#" for comments since it's python.
Then i just followed the former idea and copy-pasted some new parameters:

-higher discounts for all 4 idols (+ the lantern) (0.85 instead of 0.9)

-added those as request dialogue in the en.locale file so they can remind you what they want

-added/ctrl+c/v the detection lines for the idols in the dungeoneer files

-nerfed the price of system/dungeoneer tho since it's kinda op imo (now, without discount it's 4.6K for a max stats dungeon and around 2k with (shouldn't be too much of a problem with some auri trees and scaffoldings (not my method btw))

That's about it for the dungeoneer adventure,
I still have a mystery to solve which is one of the last additions from the dev "Recovery packs are now combined when placed next to each other" this thing bugged and now i got a bag on my map but it's invisible in the world and i know it has items in it :I
I'll see if i can find a solution for this bug.

METHOD I recommend doing a backup of the core folder before doing this :D

Extract the files and replace/overwrite in their respective folders:

-gamefolder/mods/core/locale for en.locale

-gamefolder/mods/core/ui for dungeoneer1.py (remove the "1")

-gamefolder/mods/core/system for dungeoneer2.py (remove the "2")

-gamefolder/mods/core/npc for dungeoneer.ce

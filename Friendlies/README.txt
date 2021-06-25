Friendlies

Dependencies:
RRR Core and RRR NPCs by neurodr0me https://www.nexusmods.com/valheim/mods/671 & https://www.nexusmods.com/valheim/mods/687
MobAILib by Barg and Morg (RagnarsRokare) https://www.nexusmods.com/valheim/mods/1188
Spawn That by ASharpPen https://www.nexusmods.com/valheim/mods/453

To make Friendlies follow you through portals, check out Teleport Wolves: https://www.nexusmods.com/valheim/mods/217

Installation:
Install dependencies.
Delete/Backup old Friendlies files.
Drop BepInEx folder from download into Valheim folder and overwrite. 

Uninstallation:
Delete Friendlies.dll and FriendliesAI.dll from Valheim/BepInEx/plugins
Delete 'friendliesNpcs' folder from Valheim/BepInEx/config 

NpcAI:
- Current version is a refactored combination of RagnarsRokare Fixer&Worker AIs, along with their other behaviors (Fightng,Eating,Searching). 
- NPCs will walk around trying to repair things when Idle.
- If they have been taught how, they will also try to refill different things in the game. This includes smelters, torches, braziers, kilns,
	windmills, spinning wheels, and blast furnaces.
- NPCs are taught to do tasks by setting them to follow you, then by you filling the thing you want them to learn. You'll see their progress
	updating in the top left of your screen.


Companions:
- Multiple different companions, loosely balanced around Black Forest/Swamp
- Do not spawn in naturally, meant to be able to pick if/who you want in your game

Below are the current companions, in parenthesis is the name used to spawn them.

Groot (Groot):
- Scaled down version of The Elder, minus all the particles and groud shaking
- Uses 2 custom attacks, a slightly modified version of neuro's Thornweaver attack, and the troll ground slam

Trundle (Trundle):
- A Troll based off Leauge of Legends champion Trundle (WIP)

Ashe (RRRN_Ashe):
- An NPC based off League of Legends champion Ashe
- Has 4 custom attacks based off her ingame abilities

Necromancer (RRRN_Necromancer):
- Spawns custom mini skeletons

Dvoarah (RRRN_Dvorah):
- Spawns custom mini squitos 

Mage (RRRN_Mage):
- Has a couple custom magical attacks

Dwarf (RRRN_Dwarf):
- Just a Dwarf

Freki (Freki) and Geri (Geri)
- 2 large wolves that were said to accompany Odin before Huginn and Muninn

NEW Freki (DarkWolf) and Geri (LightWolf)
- Custom models!!!
- Custom animation controller !!

Eir (RRRN_Eir) 
- The goddess Eir, goddess of healing and protection
- May have been a valkyrie
- Can heal and shield allies

Known Issues:
- Some text still refers to Greylings, this is hardcoded into MobAILib and I'm gonna need to figure out patches a little better before I can overwrite it.
- Some projectiles will throw errors from CombatOverhaul to the log. These just mean C.O.'s changes arent being applied to the custom attacks, which is 100% okay.
- With nothing to do, will sometimes walk back and forth between opening container and the smelter (looking for things to put in the smelter).
- Sometimes Ore will not appear in NPC's hand while they carry it (I think it just happens when theres something in their left hand?), though Coal seems to always show.
	- The Ore is there and will get put in Smelter, its just not visible in the hand.
- Sometimes Npcs throw the last Ore/Coal of their current assignment on the ground instead of putting it into the smelter.

Planned Features:
- Robust config options
- More assignments/tasks/behaviors
- More companions & attacks 
- Possibly events to spawn in Companions at certain milestones when enabled 

Special Thanks / Contributors:
- Config for Spawn That and all the original NPC configs were done by Grisch (PlasticRat), big thanks for letting me take over this platform!
- Big thanks to the authors of all the dependency mods! Would (literally) not be possible without them. 
- Especially neurodr0me, ASharpPen, Barg and Morg
- Thanks to the rest of Valheim Modding Community for support and help :)

Contact Info:
- You can find me @shadow84 on the Valheim modding discord (link on RRR Core Nexus page, see above)
- If you have ideas/feedback/reports feel free to @ me in an appropriate channel there
- If you're interested in contributing (actually doing something, not just ideas) you can add and PM me
# ARCOMM SPTFika Mod Repo  

## SPT, Fika, and Mod Installation  
1. Install Escape from Tarkov  

1. Download the SPTarkov installer and install it.  
https://wiki.sp-tarkov.com/Installation_Guide  

1. Download the Project Fika installer and install it.  
https://wiki.project-fika.com/installing-fika/before-installing-fika  

1. Set the server in the SPT Launcher  
Run the SPT Launcher  
Click on the settings button in the top right  
Click the Developer Mode checkbox  
Set the URL to ARCOMM Tarkov server URL (found in Discord)  
Uncheck the Developer Mode checkbox  
Close the the SPT Launcher  

1. Install OvGME  
https://repo.arcomm.co.uk/tarkov/ovgme_1_7_4_setup_64.exe  

1. Create a folder for your mods  
It doesn't matter where you make it, but I like to put it in the main SPT folder.  
Call it something like Tarkov Mods  

1. Configure OvGME  
Create a new configuration, call it something like Tarkov-Mods  
Set the Configuration Root folder to be your main SPT folder, where the EscapeFromTarkov.exe file is.  
Set the Configuration Mods folder to be the Tarkov Mods folder you previously made.  
Optionally set a backup folder.  

1. Click on this link to download the mods  
https://github.com/Drofseh/SPTFika-Mod-Repo/archive/refs/heads/main.zip  

1. Extract main.zip into your Tarkov Mods folder  
*Do not* extract each mod zip, they should stay zipped up.  

1. Download this mod that's too big to fit on github  
https://repo.arcomm.co.uk/tarkov/HollywoodFX.zip  
Do not extract it, intead place it in the Tarkov Mods folder you previously made.  

1. Download the Archived Bundles  
https://repo.arcomm.co.uk/tarkov/ArchivedBundles.zip  
Extract it do your main SPT folder.  
This is step is optional, but will make joining the server for the first time much much faster (because you won't need to download them from the server).  

1. Activate the mods  
Verify the mods show up in OvGME, they should all have a version number.  
Click on Mods -> Enable -> All  

## Difference fron live EFT:

### Inventory and Items:
- "Can't be dropped in raid" restrictions are removed.  
- A lockpicking item can be used to unlock doors via a minigame.  
- Add battlebelts that can be worn in the armband slot to provide extra inventory space.  
- Add button to container UI to transfer item into stash containers that already contain the same item.  
- Add items that can repair the max durability of items.  
- Additional tag colours added, for a total of 27 colours.  
- Adds in game links to the Tarkov wiki to item and quest descriptions.  
- Allow all bots to have an armband slot.  
- Ammo and money stack sizes increased significantly.  
- Ammo stacks background colour is based on pen value of the ammo.  
- An encomberance bar shows the current weight carried, as well as the marks at which the player is considered overweight at at which walking will drain stamina.  
- Armoured rigs can be worn with armour vests.  
- Backpack stacking limit increased to 25 deep.  
- Backpacks and containers don't have item restrictions.  
- Brighter lasers  
- Container tags can be given keywords to automatically sort items into them, eg. `@o money;` would automatically have money put into it.  
- Displays highest price each trader pay is shown in item descriptions.  
- Enhanced ammo loading list.  
- FOV has been fixed for optics, and there is a keybind added for toggle zoom like Arma.  
- Fix for item attributes not being updated while the inspection window is open.  
- Highest trader price and approximate flea price is shown item tooltips.  
- Improvements to thermal scopes.  
- Item in the inventory can be used from any container.  
- Keys and keycards have infinite uses.  
- Magazine UI ammo count will show the specific types and order of ammunition in the magazine.  
- Many restrictions around wearing different types of headgear have been removed.  
- New key storage containers with 1 slot for each unique key.  
- Open containers such a drawers can be searched without having to close them first.  
- PMC and player scav pockets made larger.  
- Pistols can go in primary weapons slots, SMG can go in pistols slots (will be upgraded in the future to allow any weapon in any of the 4 slots).  
- Port of content from the v1.0 release to SPT.  
- Restrictions on bringing items into raids are removed.  
- Repairing no longer reduced maximum durability.  
- Some container sizes adjusted.  
- Time to examine item reduced 99%.  
- Various QOL and UI fixes.  
- Weapon heating reduced 90%.  
- Weapon info screen will display the number of kills and headshots made by that specific weapon.  
- Weapon malfunction and misfire chances reduced 90%.  
- Weapons can be equiped directly from the weapon rack.  
- When in the weapon modding UI clicking and draggin on the white dots can reposition some weapon mods, such as moving optics forward or backward on a rail.  
- When in the weapon modding UI hovering the mouse over a part will show a tooltip of what stats will change if the part is added.  
- When inspecting ammo the UI will show additional, previously hidden, attributes.  

### Hideout:
- A Transfer Items button is added to hideout modules that will contribute items in stash to that construction module.  
- Add some recipes to the hideout, remove other (like arena crates).  
- Air filter, water filter, and fuel consumption all reduced.  
- Bitcoin production sped up.  
- Hideout construction no longer requires trader standing or found-in-raid items.  
- Hideout modules are displayed in a vertical list split into two categories.  
- Hideout regeneration of energy, hydration, and health removed.  
- Scav Case and Cultist Circle timers reduced.  
- Stash sizes are increased.  
- Workout QTE has been made easier.  

### Traders:
- A skip option can been added to trader quest UI to skip arduous quest requirements.  
- Clothing apparel from all faction is available to be purchased by all factions.  
- Clothing apparel purchase requirements removed (except for money).  
- Collector may be started at level 1.  
- Delay for new quests removed.  
- Insurance returns much faster and has a higher return chance.  
- Items for quests don't need to be found-in-raid.  
- Items sold by traders are considered found-in-raid.  
- Many tweaks to Ref to make his quests work better when playing solo or coop without arena.  
- Minimum durability of weapons and armour sold by traders increased.  
- Returned insurance is held by insurer for a much longer time.  
- Tasks have expanded text to give more info about the task.  
- The task list has several improvements to sorting and performance.  

### Loot:
- Airdrops frequency and contents increased.  
- Overall amount of loot increased.  

### Players:
- 10 new skills have been added, including lockpicking.  
- Max health, energy, and hydration increased.  
- Skill fatigue functionally eliminated.  
- Skill progression sped up.  
- Stamina and stamina regen increased.  
- XP gain increased.  

### Raids:
- A ballistic arc it shown when prepping to throw a grenade , much like ACE's Advanced Throwing in Arma.  
- AI armour and weapon minimum durability increased.  
- Add RUAF bot faction. Patrolling squads of 2 to 8 Russian soldiers will shoot USEC on sight.  
- Add UNTAR bot faction. Squads of UN soldiers will patrol the map.  
- Add keybind to highlight loot with glowing icons.  
- Add the ability to shoot open locked doors (requires specific weapons and ammo).  
- All randomized extracts are always available.  
- Ammo loading can be done when outside of the inventory and while walking around.  
- Armour, backpack, paracord restrictions are removed from extracts.  
- BTR inventory size increased.  
- Better 2D maps on the map tab plus minimap.  
- Bots will stop and loot items, containers, and corpses as they walk around.  
- Car/Co-Op extraction restrictions removed.  
- Co-Op extractions changed to Paid extractions.  
- Enable Labyrinth to be selected on the map screen.  
- Expanded bot waypoints allow them to navigate more areas of the maps.  
- FX overhaul.  
- Ground Zero beginner level is now 40.  
- Healing auto cancels when body part cannot be treated anymore.  
- Healing items will continue to heal until cancelled.  
- Hostility of PMCs adjusted depending on relative faction membership.  
- Insurance works inside Labs  
- Locked doors can be kicked open by using the breach action multiple times in quick succession.  
- Non-locked doors will randomly start open or closed.  
- Other scavs and scav bosses are peaceful to scav players by default.  
- Quiting from the menu counts as a Run Through extraction.  
- Raid timers extended by 720 minutes.  
- Running into an unlocked door with enough momentum will knock it open.  
- SAIN AI combat system overhaul  
- Scav run cooldown reduced.  
- Scav runs allowed in Labs  
- Seasonal events disabled.  
- Seasons will automatically rotate over time.  
- Select which spawn point to enter the map at.  
- Some items, such as fuel containers will automatically change weight depending on how full they are.  
- Time to plant markers, cameras, etc reduced significantly.  
- Transit Inventory size increased.  

### Flea Market:
- Accessible at level 1.  
- Purchased items are considered found-in-raid.  
- Non-found-in-raid items may be sold.  
- Item blacklist restrictions removed.  
- Fees removed.  
- Item minimum condition increased.  

# > Installation Instructions here <  
https://github.com/U5B/MonumentaRP-NoOptiFine/wiki/Installing-Resource-Pack  

### Other Information  
Made for 1.18.2 Fabric  
Built on Monumenta RP v3.6.0  
  
**Contributors:**  
usb#3568  
Vladomeme#2984 (Literally the maintainer of this resourcepack now)  
Noelle#7956 (Resource Pack Lead, helped with finding solutions to bugs)  
fron#0019 (Reporting a bunch of bugs)  
JuceDoesThings#2020 (Messing with villager models to not be headless)  

**Changes:**  
Moved /assets/optifine/mob to /assets/minecraft/textures/entity  
Moved /assets/minecraft/optifine/cem to /assets/dorianpb/cem  
Fixed untextured parrots in guis (path for parrots was moved) [Thanks fron#0019 and Noelle#7956]  
Fixed untextured crossbows, bows, and guns (model overrides were not set properly)  
Fixed various items (including tesseracts) that specified texture in .properties file while actually using multiple textures in linked model (removed texture assignment from .properties)  
Fixed Giant model (added model parts identical to vanilla)  
Fixed Villager model by adding missing uv elements (ignored by optifine for some reason) and mirroring some up/down uv elements (CEM bug)  
Added texture files for entities with different states (angry wolfs, bees etc.)  
Fixed all broken paths (paths using non-vanilla allowed characters)

**Broken Things:**  
Tridents are not textured with the latest version of CIT Resewn (Could use old version linked in the wiki above)  
  
**Thanks to the Monumenta RP creators for making the pack and having to deal with OptiFine jank.**  

# 1.0.17
!!! Breaking change to Calcified Limestone !!!

### Calcified Mineral Soil (previously Calcified Limestone)
- Now produced by bone mealing Moist Mineral Soil (previously made by bone mealing Limestone)
- Moist Mineral Soil is made from Clay, Mineral Bed & Pulverized Lapis (previously introduced for the Mineralis ritual)
- Mineral Bed is converted from Limestone with a Pure Daisy  

### The rest
- Fixed a bug where 1000mb salt recipe did not take 4x salt block. The recipe is now 1x salt block -> 250mb molten salt. Now you will need about 3 maxed out Chemical Crystallizers turning Gaseous Brine into salt to keep up. This also reinforces the idea that the breeder reactor will barely break even on power production.  
- Dense Chlorophyll Sap now takes 24 nature singularities (previously 32).
- Added a recipe to clone a lightwell, using marble and a resonating gem.
- Fixed a typo on a creative screen that appears in a generated structure in dimension 5.
- Added Snocks playthrough to the community chapter in the manual
- Added a mention of automating Red Canyon Dust sifting in the "Slow Down kid" chapter
- Added a page for the endgame chapters recommending the player to also automate Electrum/Electrum wires.  


# 1.0.16
!!! This update contains recipe updates to the Industrial Assembler. (yes again, sorry it should be the last time) !!!

### Machine Parts in Industrial Assembler/Engineers workbench
- Some recipes have been "flattened" in the engineers workbench. Since shift clicking recipes that had itemstacks with a count higher than one was buggy. This is mostly a visual/technical change.
- For example device frames took a stack of 4 tin plates before, now it takes 4 individual tin plates.
- Since the engineerings workbench just has 4 input slots, the glass requirement from the device frame has been removed in the Engineers Workbench and Industrial Assembler. In a similar fashion, to only have 6 ingredients in the Engineers Workbench, Redstone Conductance Coils now take only one Iron Rod instead of 2.
- Machine Frames now takes 3 Redstone Blocks per frame, to ensure redstone keeps being a coveted resource until you get the World Wyrms. (From 10.125 redstone per frame to 28.125 redstone per frame)

### Redstone singularities
- Redstone Singularities now take 512 blocks instead of 1024 blocks. This change is to prevent buggy interactions with AE2 once you start using larger stack sizes in processing recipes. (Filling the 4x4 grid in the Extended Pattern Processing Pattern Terminal with 64x stacks of Redstone Blocks worked, but its hard to figure out the issue if you don't know large stacksizes can cause issues)

- Doubled the amount of Redstone Singularities you need to birth the Venerated World Wyrm (this comes out to the same cost as before)
- Doubled the amount of Redstone Singularities you need for a Stellar Singularity (this comes out to the same cost as before)
- Superheated frames still take only one Redstone Singularity. So it now costs 512 Redstone Blocks instead of 1024 Redstone Blocks 

### The rest
- Disabled problematic Metal Chests upgrades. For example "Diamond to Obsidian Chest Upgrade" could upgrade vanilla chests straight to Obsidian.
- End Steel blocks now correctly melts to Molten End Steel instead of Electrical End Steel (Magma Crucible only).

### Manual
- Pack manual: Clarified that its Diesel Generators, not IF Biodiesel Generators you can use for alternative power.
- Pack manual: Mention that 128 channels also apply to ME Controller faces, Quantum Bridges, and P2P Tunnels in the pages describing AE2 functionality.  


# 1.0.15
- Ascending larvae is now much cheaper on milk and reagents. No longer requires resonating gems
- After ascending larvae, you now have to pupate it before it can be made into a World Wyrm.
- Pupating takes 5 buckets of wyrm milk, a bunch of silky/clothy materials, 64 growth reagent, and 20 resonating gems.
- Added Rich Slag ore tripling for Cobalt/Ardite/Uranium
- Added call to action text when unlocking the final advancement, telling the player to consider reviewing the pack on moddex.gg
- Added page in first book chapter, mentioning that you can review the pack on moddex.gg  


# 1.0.14
- Disable Pigiron Alloying
- Added renewable Red canyon Dust recipe in the Altar of Cosmic Transmutation
- Added renewable Dark Water recipe in the Dark Steel Fluid Mixer
- Remove uncrafting recipes for Enderium/Signalum in the Centrifugal Seperator (GH Issue #8)
- Added recrafting recipe for Spot Loaders. 8 Spot Loaders -> 1 Chunk Loader
- Added Steves Carts Reborn (Heavily configured to only allow a basic treefarm)
- Added a cart called the Treecutter 3000. This is a premade steves cart which can be used to have a Wood Farm.
- Added recipe for the Treecutter 3000 in the Industrial Assembler.
- Added new book entry called "A Happy Happy Treefarm" to the end of the 3rd Simulation.
- Remove Diamond Block -> Mana Diamond from the Mana Pool recipe pool. (Only made with Infused Diamonds)
- Remove recipes for all non-white conveyor belts.
- Added Chisel Group for conveyor belts
- Added Chisel Group for Pneumaticcraft Plastics  


# 1.0.13
!!! This update contains recipe updates to the Industrial Assembler, and to Crafting Components / Crafting storages. !!!

The following recipes have received a 4x output/input treatment, to make bulk crafting more easy, and make the assembler feel better:
Vacuum Tubes, Circuit Boards, Iron/Steel Components, Machine/Device Frames, Servos, Conductance Coils, Capacitors and Transistors.
If attached to an AE2 interface, the processing patterns need to be updated.

Since I update these recipes, I also added a redstone balancing pass. Which makes these recipes take redstone blocks instead of redstone dust (usually was around 4 dust)

- 1k, 4k, 16k and 64k Crafting Storages now take components instead of metal chests. The metal chests have been moved into Storage Component recipes instead (GH Issue #5)
- Recipes for 4k, 16k, 64k Storage Components updated to match the cost of Crafting Storages. Since Crafting Storages can be uncrafted into components. (GH Issue #5)
- This generally make disks more easily craftable. At the cost of more iron/gold/diamonds.

- Added recipe from Quarry -> Clearing quarry (GH issue #6)  


# 1.0.12
- Added Twinkling Star. You get 8 Twinkling star per Infused Radiant Star.
- Every crafting table recipe that required a Infused Radiant Star now requires a Twinkling Star instead. (Including Beacons)
- Pure Daisy now takes one Twinkling Star to craft, in addition to the 4 white petals.
- Simulation 4 mastery token now takes 4 Twinkling Star instead of one Infused Radiant Star (halved requirements)

- Disable Horologium rituals
- Add tooltips to Ritual Pedestal and related attuned crystals to inform the player that some rituals are disabled.
- Added new item: Moist Mineral Soil. After turning Limestone into a Mineral Bed with a Pure Daisy. Mineral Soil is crafted with Wet Clay and Lapis Lazuli Powder
- Fixed ore outputs of Mineralis to be everything in the first simulation. - Lapis Ore + Aluminum Ore (GH issue #4)
- Mineralis Ritual now converts Moist Mineral Soil into ores (instead of stone) (GH issue #4)
- Added tooltip to Ritual pedestal that mentions this change. As well as a tooltip to the Moist Mineral Soil

- Moved Arcane Ashes recipe from Hellfire Forge to Luminous Crafting Table
- Added Atlas tooltip to the Divination Sigil to inform the user it can be used to read LP from the players network
- Added Simulation 2 QoL Page mentioning the Storage Scanner  


# 1.0.11
This update contains recipe updates. If you have them automated with AE2 you will need to update your patterns.
Changed recipes: Kinetic Dynamo, Leadstone fluxduct, Storage Scanner

- [Patchouli page] Remove 4x casings from building materials you need to build the Altar of Blessings.
- Kinetic Dynamo now requires 2 blocks of redstone instead of 2 redstone dust.
- Leadstone fluxduct now requires Redstone Blocks instead of Redstone Dust.
- Leadstone fluxduct now requires 2 Lead Gears instead of 4 Lead Ingots.
- Small change to Storage Scanner recipe again. Take a RFTools Machine Base instead of RFTools Machine Frame. (So its usable as soon as you have your first power gen)
- Locked recipes now show the required ingredients in JEI, even if you don't have the knowledge yet. (GH issue #3)
- Fixed the structure in simulation 3 that gave the wrong kind of Thermal Foundation Coils.
- Removed Drying Rack requirement in Mass Drying Chamber, since Modular Machinery confuses between Item Rack and Drying Rack in its building materials list. If you had them placed it will still work. Schematica have been updated.
- Modular Machinery input hatches can now be crafted into output hatches, and vice versa.
- Fused Quartz can now be used to make Hardened glass.  


# 1.0.10
- Fixed magma crucible melting recipes for plastic/meat (GH issue #1)
- Added a new recipe for the Meat feeder
- Reanimated World Wyrms now required a Meat Feeder filled with meat in addition to its previous components
- Added patchouli QoL page about the Meat Feeder in simulation 4 chapter.
- Added tooltip on Mob Slaughter Factory so it shows up in JEI when you search for 'liquid meat'
- Pigs now drop pigskin, which can be turned into leather with a drying rack
- Added Mass Drying Chamber recipe for pigskin -> leather
- The chests that appear on the floating islands in simulation 1 can now contain leather/wool. (To alleviate possible passive animal scarcity)
- Remove long drying recipe (8m 30s) that turned cooked meat into Leather
- New recipe for the RFToools Storage Scanner. Can now be crafted earlier (Near the end of sim2)
- Fixed some recipes taking ender pearls and not also accepting troll eyes. (Redstone transmitter/receiver, Elevators of all colors) (GH issue #2)
- Elevators is now only 1 recipe, switching between colors is done with the Chisel  


# 1.0.9
- Added Jamez28 playthrough to Lets Play category in Book of Truth
- Added pack discord link to the new 'Community' chapter in the book
- Moved lets play links to the community chapter, instead of in the book of truth.  


# 1.0.8
- Removed options.txt file from modpack overrides
- Added OptionsEnforcer. It will set reasonable defaults, but only on the first launch after the pack is installed
- Fixed portals being able to be formed in 2x2 shapes  


# 1.0.7
- Fixed a typo in first patchouli category (infomation).
- Removed clock/compass recipes in the induction furnace. They did not work
- Renamed Altar of Cosmic Transmutation to Altar of Cosmic Transmutation
- Redid how Ardite and Cobalt ore is produced in the Altar of Cosmic Transmutation. It now takes an attuned lens (correct color), 1 rich slag instead of 4. The base input ores are now Copper/Silver instead of Iron for both ores.
- Reworded Step 8 in lunar plane so it is less confusing. Step 8 is now all about cosmic transmutation. Step 9 has been added to talk about the blessed portal stone (most of it was previously in step 8).  


# 1.0.6
- Fixed external heater recipe (Used for blast furnace preheaters)
- Added extra page to the "String & Sifting step", which explains how you get dust, the first siftable.  


# 1.0.5
- Added Atlas lip to linking tool that reiterates that crystals need a clear view of the sky.
- Added Magma Crucible melting recipes for all Deeb Mob Learning matter. They melt into essence.
- Bumped gamestage books to 1.0.3. Should remove the occasional crash from reading books  


# 1.0.4
- Add patchouli cryosim fork that adds JEI keybinds inside the book (Bookmark/Recipes/Uses)
- Mention the JEI keybinds in the introduction chapter in the modpack manual.  


# 1.0.3
- Fixed patchouli page unlock bug
- Redid a structure in sim2
- Added new structure to sim5  


# 1.0.2
- Added Aroma backup
- Bumped vintagefix to 0.7
- Enable rightclick stack crafting from craftingtweaks
- Added repair recipe for stone pickaxe, in case the player spawn in a cave in the first simulation
- Added options.txt override to get some reasonable defaults
- Added loading screen GIF and menu music  


# 1.0.1
- Added a recipe for the dark steel template
- Normal world wyrm no longer grants lapis
- Added some initial video chapters to the Book of Truth  


# 1.0.0
Base core experience

**Note: This mod is currently in beta. Additions may be limited for certain mods. (eg very few mobs for Hostile Neural Networks compat) Some features may also only be partially complete.**

Are you tired of having to install 7 different datapacks packaged as mods just so you can strip all the wood in your modpack using Farmer's Delight? Do you wish you could use Mekanism with more modded ores? Do you want to use ProjectE without having to manually set the EMC values for every item a mod adds because it doesn't use vanilla crafting? Well, you're in luck!

This mod adds integration between multiple Minecraft mods mostly in the form of recipes, for example the Immersive Engineering Metal Press for rods from Modern Industrialization and Gregtech, or Ars Nouveau manipulation essence for various modded stone types. It's basically just a datapack with load conditions so only one file is needed for any combination of mods. Currently the mod is at over 3,200 recipes and growing! (next update: at least 3,700)

**Only the recipes for the mods installed will be loaded, so there won't be any broken or empty recipes.**

Note that each addition may not be included with every mod combination, but I intend to add as much cross-compatability as possible.

I will also try to retain compatability with as many of the mods as possible, but due to the large number of mods, substantial updates to those mods may break compatability. See the [wiki](https://github.com/Mogwump/recipe-integration-mod/wiki/Feature-list) for which mods are supported and which ones are high/medium/low priority. May be outdated from time to time.

For now, all recipes are in the data folder of the mod, and can thus be changed with KubeJS or similar tools. I may implement config options in the future though.

This mod shouldn't hurt performance any more than just using a few more kilo/megabytes of RAM, as any mod/datapack does anyway, since it doesn't add any functions or anything similar - just recipes (and tags and data maps).

## Current mods + features

<details>
<summary>Current list of supported mods</summary>

**Bold** mods have features implemented by this mod.

Regular mods are fully compatible with one or more features

_Italic_ mods are partially compatible with one or more features or only have very minor compatability features, for example Randomium blacklist/whitelist tags.

- [A Cold Day In The Nether](https://modrinth.com/mod/a-cold-day-in-the-nether)
- [Actually Additions](https://modrinth.com/mod/actually-additions)
- [_Advanced AE_](https://modrinth.com/mod/advancedae)
- [Advent Of Ascension](https://modrinth.com/mod/adventofascension)
- [**The Aether**](https://modrinth.com/mod/aether)
- [**Alloy Smelter**](https://modrinth.com/mod/alloy-smelter)
- [Allthemodium](https://www.curseforge.com/minecraft/mc-mods/allthemodium)
- [_Applied Energistics 2_](https://modrinth.com/mod/ae2)
- [Ars Elemental](https://www.curseforge.com/minecraft/mc-mods/ars-elemental)
- [**Ars Nouveau**](https://modrinth.com/mod/ars-nouveau)
- [Atmospheric](https://modrinth.com/mod/atmospheric)
- [Autumnity](https://modrinth.com/mod/autumnity)
- [Biomes O Plenty](https://modrinth.com/mod/biomes-o-plenty)
- [**Confluence**](https://modrinth.com/mod/confluence)
- [**Create**](https://modrinth.com/mod/create)
- [Create: Aquatic Ambitions](https://modrinth.com/mod/create-aquatic-ambitions)
- [**Create Crafts & Additions**](https://modrinth.com/mod/createaddition)
- [Create: Deep Dark](https://modrinth.com/mod/create-deep-dark)
- [Create: Garnished](https://modrinth.com/mod/create-garnished)
- [Create: Northstar - Redux](https://modrinth.com/mod/northstar-redux)
- [Deep Aether](https://modrinth.com/mod/deep-aether)
- [Deeper And Darker](https://modrinth.com/mod/deeperdarker)
- [DivineRPG](https://modrinth.com/mod/divinerpg)
- [**Electrodynamics**](https://modrinth.com/mod/electrodynamics)
- [_End's Phantasm_](https://modrinth.com/mod/ends-phantasm)
- [_Ender Zoology_](https://modrinth.com/mod/ender-zoology)
- [**Energized Power**](https://modrinth.com/mod/energized-power)
- [_Eternal Nether_](https://modrinth.com/mod/eternal-nether)
- [Eternal Starlight](https://modrinth.com/mod/eternal-starlight)
- [Evilcraft](https://modrinth.com/mod/evilcraft)
- [**Ex Deorum**](https://modrinth.com/mod/ex-deorum)
- [Extreme Reactors](https://modrinth.com/mod/extreme-reactors)
- [**Farmer's Delight**](https://modrinth.com/mod/farmers-delight)
- [Forbidden And Arcanus](https://modrinth.com/mod/forbidden-arcanus)
- [**Fossils and Archaeology Legacy**](https://modrinth.com/mod/fossils-and-archaeology-legacy)
- [GTCEu Modern](https://modrinth.com/mod/gregtechceu-modern)
- [Gregicality Rocketry](https://modrinth.com/mod/gcyr)
- [**Hostile Neural Networks**](https://www.curseforge.com/minecraft/mc-mods/hostile-neural-networks)
- [IceAndFire Community Edition](https://modrinth.com/mod/iceandfire-ce)
- [**Immersive Engineering**](https://modrinth.com/mod/immersiveengineering)
- [Industrial Upgrade](https://modrinth.com/mod/industrialupgrade) (I might purposefully deprecate this. If you look at the item IDs and tags you will understand why.)
- [**Integrated Dynamics**](https://modrinth.com/mod/integrated-dynamics)
- [Lands Of Icaria](https://modrinth.com/mod/lands-of-icaria)
- [Luminax](https://modrinth.com/mod/luminax)
- [_MEGA Cells_](https://modrinth.com/mod/mega)
- [**Mekanism**](https://modrinth.com/mod/mekanism)
- [**Modern Industrialization**](https://modrinth.com/mod/modern-industrialization)
- [**Mystical Agriculture**](https://modrinth.com/mod/mystical-agriculture)
- [Nature's Spirit](https://modrinth.com/mod/natures-spirit)
- [_Northstar Redux_](https://modrinth.com/mod/northstar-redux)
- [**Occultism**](https://modrinth.com/mod/occultism)
- [Oh The Biomes We've Gone](https://modrinth.com/mod/oh-the-biomes-weve-gone)
- [**Oritech**](https://modrinth.com/mod/oritech)
- [**PneumaticCraft: Repressurized**](https://modrinth.com/mod/pneumaticcraft-repressurized)
- [Powah](https://modrinth.com/mod/powah)
- [**Productive Trees**](https://modrinth.com/mod/productivetrees)
- [**Project E**](https://www.curseforge.com/minecraft/mc-mods/projecte)
- [**Randomium**](https://modrinth.com/mod/randomium-ore)
- [Regions Unexplored](https://modrinth.com/mod/regions-unexplored)
- [RFTools Base](https://modrinth.com/mod/rftools-base)
- [Silent's Gems](https://modrinth.com/mod/silents-gems)
- [Silent Gear](https://modrinth.com/mod/silent-gear)
- [Stellaris](https://modrinth.com/mod/stellaris)
- [**The Bumblezone**](https://modrinth.com/mod/the-bumblezone)
- [The Undergarden](https://modrinth.com/mod/the-undergarden)
- [**Tough As Nails**](https://modrinth.com/mod/tough-as-nails)
- [Twilight Forest](https://www.curseforge.com/minecraft/mc-mods/the-twilight-forest)
- [**Umbra Poor Ores**](https://modrinth.com/mod/umbra-poor-ores)
- [**Useful Machinery**](https://modrinth.com/mod/useful-machinery)
- [Vanilla Backport](https://modrinth.com/mod/vanillabackport)
- [_YUNG's Cave Biomes_](https://modrinth.com/mod/yungs-cave-biomes)

Coming next update:

- [_Advanced Netherite_](https://modrinth.com/mod/advanced-netherite)
- [Environmental](https://modrinth.com/mod/environmental)
- [[Let's Do] BloomingNature](https://modrinth.com/mod/lets-do-bloomingnature)
- [[Let's Do] Vinery](https://modrinth.com/mod/lets-do-vinery)
- [_L\_Ender's Cataclysm_](https://modrinth.com/mod/l_enders-cataclysm)
- [Would](https://modrinth.com/mod/would)

</details>

<details>
<summary>Current list of features</summary>

Note that some features use tags, whereas others use items so certain features may only be for select mods. For more info, check out the wiki (coming soon).

- Aether freezing for modded ice blocks
- Aether placement ban for some modded torches/lanterns
- Alloy Smelter recipes for smelting from various mods
- Ars Nouveau essence water/powder snow bucket crafting for modded buckets
- Ars Nouveau Scry Ritual for modded ores
- Ars Nouveau Manipulation essence crafting for various modded stone types
- Clayworks kiln recipes for modded smooth sandstone (more blocks coming soon)
- Confluence sell values for modded items (some IDs, some tags)
- Create decorative copper block stonecutting recipes
- Create pressing for various modded plates
- Create Crafts & Additions charging for copper de-ozidixation (coming next update)
- Create Crafts & Additions rolling for modded rods
- Energized Power compressor for more modded plates
- Energized power crystal growth chamber for ae2 certus quartz
- Energized Power filtration plant for some modded ores
- Energized Power plant growth chamber for modded flowers (coming next update) (more mods + crops coming soon)
- Energized Power pulverizer for dusts from ores/raw ores
- Energized Power sawmill for modded logs to planks
- Ex Deorum hammer crushing for modded blocks
- Farmer's Delight cutting board log/wood stripping
- Farmer's Delight milk bottle/milk bucket crafting for modded buckets
- Fossils & Archaeology Legacy ancient axe bonus for modded logs
- Hostile Neural Networks data models for modded mobs
- Immersive Engineering arc furnace for more modded ores
- Immersive Engineering Garden Cloche for modded flowers and crops (more mods coming soon)
- Immersive Engineering metal press for: gears, rods, plates (wires coming soon)
- Immersive Engineering sawmill for planks from logs/wood
- Integrated Dynamics mechanical squeezer + squeezer for ores
- Mekanism chemical injection chamber for oxidizing modded copper blocks (coming next update)
- Mekanism combiner recipes for waxing modded blocks (coming next update)
- Mekanism crusher ingot -> dust
- Mekanism enrichment chamber ore processing
- Mekanism Sawmill (mostly logs-> planks currently)
- Modern Industrialization cutting machine for logs -> planks
- Modern Industrialization wax crafting with modded copper blocks
- Modern Industrialization deepslate to regular ore crafting
- Modern Industrialization macerator recipes for ore to raw
- Modern Industrialization packer recipes for some modded blocks
- Mystical Agriculture water/fire/cow essence bucket crafting for modded buckets
- Occultism crusher for more modded ores
- Oritech pulverizer for modded ores
- PneumaticCraft Electrostatic Compressor blocks
- Productive Trees sawmill for more mods that add wood types
- Project E EMC values for various modded items (configured to adjust emc accordingly if base items emc values are changed, using the default recipes)
- Project E philosopher's stone world transmutation for modded blocks
- Randomium blacklist/whitelist for some modded items
- The Bumblezone queen bee colour randomizer trades
- Tough As Nails tags for some modded items and blocks
- Umbra Poor Ores bucket crafting with modded buckets
- Useful Machinery crusher for ores
- Useful Machinery compacting

As well as a few additional tags for various mods like AE2, Northstar, Create.

To see which features support which mods out of the compatability list, visit the [feature list](https://github.com/Mogwump/recipe-integration-mod/wiki/Feature-list) on the wiki. (Currently outdated, will update soon)

</details>


## Planned mod support

<details>
<summary>Planned mod support</summary>

Support for some mods here may be dependent on the mods updating and/or being able to add custom recipes using the mod's features. At the time of writing this, Botania has not updated to 1.21+ yet, and there are plenty of Create addons that haven't updated to 1.21+

- [Apotheosis](https://www.curseforge.com/minecraft/mc-mods/apotheosis) (gems might be put into a separate mod to avoid scope creep)
- [AvaritiaNeo](https://modrinth.com/mod/avaritianeo)
- [Botania](https://modrinth.com/mod/botania) (dependent on update)
- [Create Ore Excavation](https://modrinth.com/mod/create-ore-excavation)
- [Dynamic Trees](https://modrinth.com/mod/dynamictrees)
- [Farming for Blockheads](https://modrinth.com/mod/farming-for-blockheads)
- [GuideME](https://modrinth.com/mod/guideme)
- [JAOPCA](https://modrinth.com/mod/jaopca) (Both using items from JAOPCA and not loading certain recipes when also installed)
- [JourneyMap](https://modrinth.com/mod/journeymap)
- various Let's Do mods?
- [Loot Integrations](https://www.curseforge.com/minecraft/mc-mods/loot-integrations) (maybe)
- [Ore Growth](https://modrinth.com/mod/ore-growth)
- [Origins](https://modrinth.com/mod/origins)
- [Patchouli](https://modrinth.com/mod/patchouli)
- [Quark](https://modrinth.com/mod/quark)
- [Research'd](https://modrinth.com/mod/researchd) (maybe)
- [Research Station](https://modrinth.com/mod/research-station) (maybe - unlikely)
- [Serene Seasons](https://modrinth.com/mod/serene-seasons)
- [Thaumcraft 7](https://www.reddit.com/r/feedthebeast/comments/1kq9h7z/thaumcraft_7_trailer_and_ama/) (To be released)
- [Teleport Circles](https://modrinth.com/mod/teleport-circles) (Maybe - it would be alternate structure files for mods like Towers Of The Wild, which has support for waystones, and possibly some others but this is unlikely and would probably be in a separate mod)
- [Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap)
- More various Create addons


As well as many additional features for the currently supported mods, including but not limited to:


- Evilcraft infinite water bucket crafting for modded buckets
- Modern Industrialization unpacker recipes
- Modern Industrialization copper waxing and oxidizing recipes
- Ore Growth compatability with various mods
- Origins tags for modded items and blocks
- Serene Seasons compat for modded crops
- Umbra Poor Ores small water/lava bucket crafting for modded buckets
- Various mossy block crafting recipes using modded vines
- Trial spawner configurations with modded mobs (1.21.2+)
- Trim materials for modded ingots and gems

</details>

## Q/A:

<details>
<summary>Q/A</summary>

> What versions are supported?

Currently Neoforge 1.21 and above, but for best results, you should use 1.21.4 and above. Please don't report any bugs about recipes being incorrectly loaded if this only happens on versions before 1.21.4. >99% of features/recipes should be fine though, and this could only ever happen with specific mod combinations and mods that don't use tags correctly or that use them weirdly.

> Server or client?

The majority of stuff is server-side, but it can be installed on either. Currently, the only client-side feature is for Hostile Neural Networks compat (the language files for mob descriptions, which it will work without), which is currently EXTREMELY incomplete. I plan to eventually add Xaero's and Journeymap compat for some modded mobs though.

> What's the difference between this, AlmostUnified, JAOPCA, or ProjectE integration?

[AlmostUnified](https://modrinth.com/mod/almost-unified) merges recipes where there are the same type of material. For example, if mod 1 adds tin plates made with machine 1, and mod 2 adds tin plates made with machine 2, AlmostUnified merges those to only use one of the items that can be made from either machine. However, if mod 2 also adds lead plates made with machine 2, you will not be able to use machine 1 to make lead plates. This mod fixes that problem by adding as much cross-compatability as possible. I recommend installing AlmostUnified along with this mod since I have excluded recipes for materials if they already exist in a mod.

[JAOPCA](https://modrinth.com/mod/jaopca) does a better job at unifying ore processing than this mod, since it adds new items for each material (clumps, shards, dust, etc) so it can add more features than this mod and each ore can be used everywhere. It only focuses on ore unification though, and this mod also adds recipes for wood types with various sawmills, as well as plenty of other features. I plan on adding full JAOPCA compatability in the future. Currently if you install JAOPCA alongside this mod, there'll be duplicate recipes, possibly with different ratios, but they'll both work.


[ProjectE Integration](https://modrinth.com/mod/projecte-integration) is fairly obvious in that it only focuses on ProjectE, however it does a better job at it than this mod does, since it reads every recipe whilst this mod is just a datapack configured with the default recipe ratios. It is required on both the server and client, so updating the server-side mod would require updating the client-side mod as well (most likely. I haven't tested how it behaves with different versions of the mod)

> Any chance of a fabric port?

Unlikely. Definitely not in the immediate future. It would require changing literally thousands of files, so don't expect a port any time soon unless it's a complete rewrite. For now, I will support fabric mods through Sinytra.

> Can I disable any recipes?

You should be able to overwrite any changes including recipes with datapacks/mods/kubejs/etc, but there are currently no config options. That is something I might implement eventually though. Again, not in the immediate future.

> Can I use this in a modpack?

Yes! Preferably distributed in a format where the mod is downloaded from the modrinth website on each install, such as .mrpack, but this isn't *strictly* necessary if you **really** need to.

> Does this add any new items?

Currently, no. I plan on keeping it this way. If I do decide on adding items, it would likely be in a separate mod.

> Can I fork this and publish it?

Only if it is to a different modloader such as forge, fabric, or quilt. I will try my best to keep this updated and maintained, which should be fairly simple with the current features. I will support some fabric mods through Sinytra, but Sinytra does crash with some mod combinations so feel free to make a fabric port. For more info, read the license on the github.

> Can I contribute to the github?

Sure! Make sure to check the license and contribute to the additions branch. I finally fixed the links to the github so feel free to contribute or even just make suggestions for mod support by making a new issue!

</details>
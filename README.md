# Recipe Integration Mod

### Note: This mod is currently in beta. Additions may be limited for certain mods. (eg very few mobs for Hostile Neural Networks compat) Some features may also only be partially complete.

Are you tired of having to install 7 different datapacks packaged as mods just so you can strip all the wood in your modpack using Farmer's Delight? Do you wish you could use Mekanism with more modded ores? Do you want to use ProjectE without having to manually set the EMC values for every item a mod adds because it doesn't use vanilla crafting? Well, you're in luck!

This mod adds integration between multiple Minecraft mods mostly in the form of recipes, for example the Immersive Engineering Metal Press for GCTEU and MI plates, or Ars Nouveau manipulation essence with Biomes O Plenty sand and sandstone. It's basically just a datapack with load conditions so only one file is needed for any combination of mods.

**Only the recipes for the mods installed will be loaded, so there won't be any broken or empty recipes.**

Note that each addition may not be included with every mod combination, but I intend to add as much cross-compatability as possible.

I will also try to retain compatability with as many of the mods as possible, but due to the large number of mods, substantial updates to those mods may break compatability. See the [wiki](https://github.com/Mogwump/recipe-integration-mod/wiki/Feature-list) for which mods are supported and which ones are high/medium/low priority.

For now, all recipes are in the data folder of the mod, and can thus be changed with KubeJS or similar tools. I may implement config options in the future, but for now the mod's recipes are just .json files.

This mod doesn't add any ticking functions, so it shouldn't hurt performance any more than just using a few more kilo/megabytes of RAM.

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
- [Allthemodium](https://www.curseforge.com/minecraft/mc-mods/allthemodium)
- [_Applied Energistics 2_](https://modrinth.com/mod/ae2)
- [Ars Elemental](https://www.curseforge.com/minecraft/mc-mods/ars-elemental)
- [**Ars Nouveau**](https://modrinth.com/mod/ars-nouveau)
- [_Biomes O Plenty_](https://modrinth.com/mod/biomes-o-plenty)
- [**Confluence**](https://modrinth.com/mod/confluence)
- [**Create**](https://modrinth.com/mod/create)
- [Create: Aquatic Ambitions](https://modrinth.com/mod/create-aquatic-ambitions)
- [**Create Crafts & Additions**](https://modrinth.com/mod/createaddition)
- [Create: Deep Dark](https://modrinth.com/mod/create-deep-dark)
- [Create: Garnished](https://modrinth.com/mod/create-garnished)
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
- [GTCEu Modern](https://modrinth.com/mod/gregtechceu-modern)
- [Gregicality Rocketry](https://modrinth.com/mod/gcyr)
- [**Hostile Neural Networks**](https://www.curseforge.com/minecraft/mc-mods/hostile-neural-networks)
- [**Immersive Engineering**](https://modrinth.com/mod/immersiveengineering)
- [Industrial Upgrade](https://modrinth.com/mod/industrialupgrade)
- [**Integrated Dynamics**](https://modrinth.com/mod/integrated-dynamics)
- [Lands Of Icaria](https://modrinth.com/mod/lands-of-icaria)
- [Luminax](https://modrinth.com/mod/luminax)
- [_MEGA Cells_](https://modrinth.com/mod/mega)
- [**Mekanism**](https://modrinth.com/mod/mekanism)
- [**Modern Industrialization**](https://modrinth.com/mod/modern-industrialization)
- [**Mystical Agriculture**](https://modrinth.com/mod/mystical-agriculture)
- [Occultism](https://modrinth.com/mod/occultism)
- [_Oh The Biomes We've Gone_](https://modrinth.com/mod/oh-the-biomes-weve-gone)
- [**PneumaticCraft: Repressurized**](https://modrinth.com/mod/pneumaticcraft-repressurized)
- [Powah](https://modrinth.com/mod/powah)
- [_Productive Trees_](https://modrinth.com/mod/productivetrees)
- [**Project E**](https://www.curseforge.com/minecraft/mc-mods/projecte)
- [**Randomium**](https://modrinth.com/mod/randomium-ore)
- [Regions Unexplored](https://modrinth.com/mod/regions-unexplored)
- [RFTools Base](https://modrinth.com/mod/rftools-base)
- [Silent's Gems](https://modrinth.com/mod/silents-gems)
- [Stellaris](https://modrinth.com/mod/stellaris)
- [**The Bumblezone**](https://modrinth.com/mod/the-bumblezone)
- [The Undergarden](https://modrinth.com/mod/the-undergarden)
- [**Tough As Nails**](https://modrinth.com/mod/tough-as-nails)
- [Twilight Forest](https://www.curseforge.com/minecraft/mc-mods/the-twilight-forest)

</details>

<details>
<summary>Current list of features</summary>

Note that some features use tags, whereas others use items so certain features may only be for select mods. For more info, check out the wiki (coming soon).

- Ars Nouveau essence water/powder snow bucket crafting for modded buckets
- Ars Nouveau Scry Ritual for modded ores
- Ars Nouveau Manipulation essence crafting for various modded stone types
- Confluence sell values for modded items (some IDs, some tags)
- Create decorative copper block stonecutting recipes
- Create pressing for various modded plates
- Create Crafts & Additions rolling for modded rods
- Energized Power compressor for more modded plates
- Energized power crystal growth chamber for ae2 certus quartz
- Energized Power sawmill for modded logs to planks
- Ex Deorum hammer crushing for modded blocks
- Farmer's Delight cutting board log/wood stripping
- Farmer's Delight milk bottle/milk bucket crafting for modded buckets
- Hostile Neural Networks data models for modded mobs
- Immersive Engineering metal press for: gears, rods (plates, wires + more materials coming soon)
- Immersive Engineering sawmill for planks from logs/wood
- Integrated Dynamics mechanical squeezer + squeezer for ores (more ores coming soon for regular squeezer)
- Modern Industrialization wax crafting with modded copper blocks
- Modern Industrialization deepslate to regular ore crafting
- Mystical Agriculture water/fire/cow essence bucket crafting for modded buckets
- PneumaticCraft Electrostatic Compressor blocks
- Project E EMC values for various modded items (configured to adjust emc accordingly if base items emc values are changed, using the default recipes)
- Project E philosopher's stone world transmutation for modded blocks
- Randomium blacklist/whitelist for some modded items
- The Bumblezone queen bee colour randomizer trades
- Tough As Nails tags for some modded items and blocks
- Useful Machinery crusher for ores

As well as a few minor tags for various mods

To see which features support which mods out of the compatability list, visit the [feature list](https://github.com/Mogwump/recipe-integration-mod/wiki/Feature-list) on the wiki

</details>


## Planned mod support

<details>
<summary>Planned mod support</summary>

Support for some mods here may be dependent on the mods updating and/or being able to add custom recipes using the mod's features. At the time of writing this, Botania has not updated to 1.21+ yet, and there are plenty of Create addons that haven't updated to 1.21+

- [Advanced Netherite](https://modrinth.com/mod/advanced-netherite)
- [AvaritiaNeo](https://modrinth.com/mod/avaritianeo)
- [Botania](https://modrinth.com/mod/botania) (dependent on update)
- [Dynamic Trees](https://modrinth.com/mod/dynamictrees)
- [Fossils and Archaeology Legacy](https://modrinth.com/mod/fossils-and-archaeology-legacy)
- [IceAndFire Community Edition](https://modrinth.com/mod/iceandfire-ce)
- [Ore Growth](https://modrinth.com/mod/ore-growth)
- [Origins](https://modrinth.com/mod/origins)
- [Serene Seasons](https://modrinth.com/mod/serene-seasons)
- [Silent Gear](https://modrinth.com/mod/silent-gear)
- [Umbra Poor Ores](https://modrinth.com/mod/umbra-poor-ores)
- More various Create addons

As well as many additional features for the currently supported mods, including but not limited to:


- Evilcraft infinite water bucket crafting for modded buckets
- Mekanism ore processing for more modded ores
- Mekanism sawmill for different wood types
- Occultism crushing for modded ores
- Ore Growth compatability with various mods
- Origins tags for modded items and blocks
- Serene Seasons compat for modded crops
- Umbra Poor Ores small water/lava bucket crafting for modded buckets
- Various mossy block crafting recipes using modded vines

</details>



## Q/A:
> What versions are supported?

Currently Neoforge 1.20.3 and above, but for best results, you should use 1.21.4 and above. Please don't report any bugs about recipes being loaded when they shouldn't be if this only happens on versions before 1.21.4. >99% of features/recipes should be fine though, and this could only ever happen with specific mod combinations and mods that don't use tags correctly.

> Any chance of a fabric port?

Unlikely, but possible. Definitely not in the immediate future though. It would require changing most of the mod's recipes, so don't expect a port any time soon.

> Can I disable any recipes?

You should be able to overwrite any changes including recipes with datapacks/mods/kubejs/etc, but there are currently no config options. That is something I might implement eventually though.

> Can I use this in a modpack?

Yes! Preferably distributed in a format where the mod is downloaded from the modrinth website on each install, such as .mrpack, but this isn't *strictly* necessary if you **really** need to.

> Does this add any new items?

Currently, no. I plan on keeping it this way, so this mod is only server-side. If I do decide on adding items, it would likely be in a separate mod.

> Can I fork this and publish it?

Only if it is to a different modloader such as forge, fabric, or quilt. I will try my best to keep this updated and maintained, which should be fairly simple with the current features. I will support some fabric mods through Sinytra, but it does crash with some mod combinations so feel free to make a fabric port.

> Can I contribute to the github?

Sure!
# Recipe Integration Mod

### Note: This mod is currently in beta. Additions may be limited for certain mods. (eg very few mobs for Hostile Neural Networks compat) Some features may also only be partially complete.

Are you tired of having to install 7 different datapacks packaged as mods just so you can strip all the wood in your modpack using Farmer's Delight? Do you wish you could use Mekanism with more modded ores? Do you want to use ProjectE without having to manually set the EMC values for every item a mod adds because it doesn't use vanilla crafting? Well, you're in luck!

This mod adds integration between multiple Minecraft mods mostly in the form of recipes, for example the Immersive Engineering Metal Press for GCTEU and MI plates, or Ars Nouveau manipulation essence with Biomes O Plenty sand and sandstone. It's basically just a datapack with load conditions so only one file is needed for any combination of mods.

**Only the recipes for the mods installed will be loaded, so there won't be any broken or empty recipes.**

Note that each addition may not be included with every mod combination, but I intend to add as much cross-compatability as possible.

I will also try to retain compatability with as many of the mods as possible, but due to the large number of mods, substantial updates to those mods may break compatability. See the [wiki](https://github.com/Mogwump/recipe-integration-mod/wiki/Feature-list) for which mods are supported and which ones are high/medium/low priority.

For now, all recipes are in the data folder of the mod, and can thus be changed with KubeJS or similar tools. I may implement config options in the future, but for now the mod's recipes are just .json files.

This mod doesn't add any ticking functions, so it shouldn't hurt performance any more than just using a few more kilo/megabytes of RAM.

## List of features


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
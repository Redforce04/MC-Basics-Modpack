# MC-Basics-Modpack
## About
MC Basics is basic client-side modpack for mc users. It contains some QOL changes and fixes to the main game. 

It has a version for both `Forge` and `Fabric`, and can be installed and launched via `Technic Launcher`, `Curseforge`, or `Manual Installation`. 
Because `Forge` and `Fabric` have different variations in mods, this pack may contain variations between the forge and fabric versions. I have notated these differences accordingly. 

This pack also contains recommended shaders in all installations. I have gathered these via over many years, but this may lead some shaders to be outdated. I have linked the creators below if you would like to manually install the latest versions.

If you have any questions comments or concerns, reach out via the methods outlined below in the `Contact` section. 

## Installation Methods
- Zip files can be found in the Releases tab for `Curseforge`, and `Manual Installation`.
- Technic launcher has the pack released as both `Forge MC Basics` and `Fabric MC Basics`.
- The Curseforge release must be installed manually, as it is not publicly published.


## Installation Help:
- For help with TechnicLauncher release, read [here](https://www.technicpack.net/article/how-to-install-packs.96).
- For help with the Curseforge release, read [here](https://support.curseforge.com/en/support/solutions/articles/9000198501-exporting-and-importing-modpacks).
- For help with the Manual Installation release, read [here](https://apexminecrafthosting.com/how-to-install-mods-on-forge/).


## Mods
### Included Mods:
Mod Name                      | Mod Description                                                                                                                            | Mod Links
------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------
*Appleskin                    | Provides additional hunger and health information in the hotbar. (Server needs a plugin for some of the additional features.)              | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/appleskin), [Github](https://github.com/jmattingley23/AppleSkinSpigot), [Spigot Server Plugin](https://www.spigotmc.org/resources/appleskinspigot.97473/)
Enchantment Descriptions      | Provides descriptions for enchantments.                                                                                                    | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/enchantment-descriptions), [Github](https://github.com/Darkhax-Minecraft/Enchantment-Descriptions)
Just Enough Items (JEI)       | Provides a GUI to view crafting recipes, items, and other item related information.                                                        | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/jei), [Github](https://github.com/mezz/JustEnoughItems)
Just Enough Resources (JER)   | Providers more information for items, such as the ways to attain the item via mining, loot chests, and mob drops.                          | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/just-enough-resources-jer), [Github](https://github.com/way2muchnoise/JustEnoughResources)
Light Overlay                 | Provides a light overlay that allows you to see where mobs can spawn (F7 is the default key-bind).                                         | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/light-overlay), [Github](https://github.com/shedaniel/LightOverlay)
Mouse Tweaks                  | Provides some enhancements to the default mouse system, when interacting with inventories.                                                 | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks), [Github](https://github.com/YaLTeR/MouseTweaks)
*Voicechat                    | Provides a local voicechat feature. You can talk to other nearby players if they also have the mod. (Server must have a plugin installed.) | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat), [Github](https://github.com/henkelmax/simple-voice-chat), [Spigot Server Plugin](https://www.spigotmc.org/resources/simple-voice-chat.93738/)
What The Hell Is This (WTHIT) | Provides tooltips about the blocks that you are looking at.                                                                                | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/wthit), [Github](https://github.com/badasintended/wthit)
* Server dependency required for funtionality of some or all features.

### Included Dependencies:
Mod Name     | Mod Description                                      | Mod Links
-------------|------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------
Architectury | Dependency for Light Overlay.                        | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/architectury-api), [Github](https://github.com/architectury/architectury-api)
Bad Packets  | Dependency for What The Hell Is This (WTHIT).        | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/badpackets), [Github](https://github.com/badasintended/badpackets)
Bookshelf    | Dependency for Enchantment Descriptions.             | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/bookshelf), [Github](https://github.com/Darkhax-Minecraft/Bookshelf)
Cloth Config | Dependency for Light Overlay, and Simple Voice Chat. | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/cloth-config), [Github](https://github.com/shedaniel/cloth-config)
<br>


## Additional Mods:
Due to the different availability of mods for `Forge` and `Fabric`, there are some framework specific mods. These are listed here.


### Fabric Version Additional Mods:
Mod Name        | Mod Description                                                                                | Mod Links
----------------|------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------
Iris            | Allows the rendering of shaders and provides other visual adjustments.                         | [Modrinth](https://modrinth.com/mod/iris), [Website](https://irisshaders.dev/download), [Github](https://github.com/IrisShaders/Iris)
*World Edit CUI | Provides world edit information overlays to players. (Server needs a plugin for this to work.) | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/worldeditcui-fabric), [Github](https://github.com/EngineHub/WorldEditCUI)
Sodium          | A dependency for Iris.                                                                         | [Modrinth](https://modrinth.com/mod/sodium), [Github](https://github.com/CaffeineMC/sodium-fabric)
Fabric API      | The main dependency for all fabric plugins.                                                    | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/fabric-api), [Website](https://fabricmc.net/), [Github](https://github.com/FabricMC/fabric)
* Server dependency required for funtionality of some or all features.


### Forge Version Additional Mods:
Mod Name       | Mod Description                                                                                    | Mod Links
---------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------
Optifine       | Allows the rendering of shaders and provides other visual adjustments. Also allows for zooming in. | [Website](https://optifine.net/home), [Github](https://github.com/sp614x/optifine)
Fast Workbench | Provides features that makes crafting easier and faster. Also fixes crafting related bugs          | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/fastworkbench), [Github](https://github.com/Shadows-of-Fire/FastWorkbench)
Placebo        | Dependency for Fast Workbench.                                                                     | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/placebo), [Github](https://github.com/Shadows-of-Fire/Placebo)



## Shaders:
A list of shaders that are included in the pack.

**Note: Many of the shaders included with the pack may be out of date.** Consider downloading the latest version for the best experience. Although they have been tested, they may cause bugs or issues in `1.20.1`.
More shaders can be found [here](https://shaders.fandom.com/wiki/Shader_Packs).


Shaderpack Name                 | Shaderpack Links
--------------------------------|------------------------
BSL (v8.2.02)                   | [Website](https://bitslablab.com/bslshaders/)
Chocapic13 (v9-beta.2)          | [Curseforge](https://www.curseforge.com/minecraft/shaders/chocapic13-shaders)
Ooceano Shaders (v3.0.1)        | [Curseforge](https://www.curseforge.com/minecraft/shaders/oceano-shaders)
Project Luma (v1.54)            | [Curseforge](https://www.curseforge.com/minecraft/shaders/projectluma)
RRe36-Shader (v10.1)            | [Curseforge](https://www.curseforge.com/minecraft/shaders/rre36s-shader)
SEUS Renewed (v1.0.1)           | [Website](https://www.sonicether.com/)
Slidurs Vibrant Shaders (v1.28) | [Website](https://sildurs-shaders.github.io/)
Sora Shaders (v1.142)           | [Curseforge](https://www.curseforge.com/minecraft/shaders/sora-shaders)



# Contact
If you have an issue with this pack feel free to reach out. You can:
- Create a github issue with any issues, feedback or feature requests.
- Reach out to me over Discord (Redforce04).

<br>
<br>
I hope you enjoy the modpack! <br>
- Redforce04

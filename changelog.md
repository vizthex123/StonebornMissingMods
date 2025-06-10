# Stoneborn: Missing Mods Changelog

A full changelog for every version (and sub-version) of the [resource pack](https://curseforge.com/minecraft/texture-packs/stoneborn-missing-mods).

This one will be updated more often than the CurseForge and Modrinth changelogs.

I increment the version by X.1 whenever I add more mod support, and X.X.1 for minor fixes and/or additions I missed in the last patch (as well as version ports so you can quickly navigate on Modrinth).

Lines appended with a version in brackets (e.g. [1.20] Text Here) denote changes that only apply to that version.

--------------------------------------------------

## v3.0

*Probably gonna be the final update since I've decided this will only be for minor fixes, with mod support being added to [Stoneborn - Modded Compatibility](https://www.curseforge.com/minecraft/texture-packs/stoneborn-modded-compatibility).*

Fixed the in-game icon not matching the CurseForge icon

Fixed the anvil's crafting arrow's negative space being filled in (reported to base Stoneborn's author, hope he fixes it soon (alongside the inventory pixels that are *still* missing ffs))

Moved support for all mods to [Stoneborn - Modded Compatibility](https://www.curseforge.com/minecraft/texture-packs/stoneborn-modded-compatibility)
- Excludes the following mods: Vanilla fixes, Custom Machinery, Masterful Machinery, and Research Lab
- Added minor fixes for Blue Skies and L_Ender's Cataclysm


<br /> <br />

--------------------------------------------------
## v2.3

Added support for Botania's creative tab<br />
Added missing decals to the terminals from Pretty Pipes<br />
Blood Magic's JEI half-arrows are now a solid colour so they look a tad better
Tweaked the progress arrow on Gendustry's Sampler, Imprinter, and Transposer

Fixed Forestry's buttons not being textured<br />
Fixed Thermal Series buttons not using the proper icon colour<br />
Fixed a few incorrect pixels in the JEI Handler for the Thermal Series<br />
Fixed several Railcraft Reborn blocks not using the proper icon colour<br />
Fixed the search and scroll bars not being visible in Pretty Pipes' item terminal

Crafting Tweaks fixes:
- Added missing buttons
- Fixed icons being the wrong colour
- Fixed warning buttons missing their warning icon

Mod support added:
- Brick Hopper
- Golden Hopper
- Wooden Hopper
- Travel Anchors
- Iron Chests: Restocked
- Mekanism's creative tabs (not really possible to cover the rest of the mod since 95% of UIs are done through code ffs)


<br /> <br />

--------------------------------------------------
## v2.2

Finally got support for Quark's Crafter and Feeding Trough working (stupid things are stored in a different file path ffs)

Fixed the Project Bench's inventory slots being hidden
- Also reduced the height of its brick background

Changed the brick background on Crafting Automat to only be behind the crafting area<br />
Changed icon text to be white so it's consistent with other icons
- This affects the following mods: Quark

Removed Spectrum & Trinkets support since they're not working, and I don't use Fabric so idc enough to keep up with it
- If you want Trinkets support, [this pack](https://modrinth.com/resourcepack/trinkets-for-stoneborn) adds it (not sure if it works though - and it's not on CurseForge, for some reason)

Mod support added:
- AdminShop Overhauled
- Research Lab
- Simple Quarry


<br /> <br />

--------------------------------------------------
## v2.1

Changed support list to a support table
- Makes things more readable & scalable

Updated the colour of icons for Quark's buttons<br />
Vastly improved Nature's Aura's Altar JEI tab with a new arrow texture (made by xKeru on the Stoneborn discord server)

Added support for the following mods:<br />
*Requested by TrilleX on the discord server*

- The Aether (only a couple UIs that [Mei's Additions](https://www.curseforge.com/minecraft/texture-packs/stoneborn-meis-additions-for-modded-guis) missed)
- Spectrum (although it's not working for some reason. I don't use fabric and have no clue what's wrong, so if anyone knows why it's not loading in please let me know)
- Spell Engine (also not working because fabric dumb)


<br /> <br />

--------------------------------------------------
## v2.0

Compressed all the files - which is mostly irrelevant for the compressed version that you download, but oh well
- I also tweaked a few random things in various files while doing this (mainly updating a bunch of icons so they're not jet black)

Fixed all button selectors not having the 1-pixel indent<br />
Fixed some selection outlines overriding the button's icon<br />
Fixed the Sky Stone Chest's UI not being coloured gold like it should<br />
Made the long arrow for the Material Stonework Factory's JEI tab match Stoneborn's arrow style<br />
Added a better background for Twilight Forest's uncrafting table (made by The ARASH on the Stoneborn discord server)

Added the brick background to all the Crafting Table and Furnace variants<br />
- Also added Stoneborn's fancy slot highlight system-inator to them

Added support for the following mods:
- Bigger Reactors
- Building Gadgets
- Charging Gadgets
- Chicken Chunks
- Deep Resonance
- EnderIO
- Gendustry: Community Edition
- LaserIO (and the [unofficial extended life](https://www.curseforge.com/minecraft/mc-mods/laserio-uel) port)
- Mining Gadgets
- Pretty Pipes
- Project Red (all modules)
- Quark (Matrix Enchanting table is based on Fr_z_n's pack)
- RFTools (all modules)


<br /> <br />

--------------------------------------------------
## v1.4.2

*I missed more stuff ffs. I hate making tiny hotfixes, man ;-;*

Fixed Crafting Automat's storage slots not rendering<br />
Fixed the Deep Learner slot not being the proper colour

Added support for the following mods that I forgot to add in v1.4:
- AppleSkin (based on Fr_z_n's pack)
- Better Advancements (based on Fr_z_n's pack)
- Cosmetic Armour Reworked (based on Fr_z_n's pack)
- The Twilight Forest


<br /> <br />

--------------------------------------------------
## v1.4.1

*I missed a few things in v1.4, oof*

Added support for the JEI category from Ad Astra: Giselle Addon<br />
Added support for Masterful Machinery


<br /> <br />

--------------------------------------------------
## v1.4

Made the Curios slots for the Deep Learner, Jetpack, and Wallet use the same colours as base Stoneborn does for empty gear slots

Added the brick background to the Crafting Automat's UI
- I plan to add it to other blocks in the next update, but for now I figured I could slap it into this one as a test run

Colourized the text for a few blocks from Lightman's Currency
- Most of the mod doesn't use the proper translation keys, so I might remove this in the future

Colourized the text in Scannable's UIs
- I can't do the main header though. Ah well.

Added support for the following mods:
- Applied Energistics 2 (based on the support added by Fr_z_n's pack)
- Applied Energistics 2 Wireless Terminals
- Curios API
- Dis-Enchanting Table
- Railcraft Reborn
- Roughly Enough Items (based on the support added by Fr_z_n's pack)
- TrashCan (the one by Reedomu)


<br /> <br />

--------------------------------------------------
## v1.3

Fixed Lightman's Currency's wallet UIs not rendering properly if you used newer versions of the mod ([reported by DankestO](https://github.com/vizthex123/StonebornMissingMods/issues/1))

Added support for Forestry: Community Edition


<br /> <br />

--------------------------------------------------
## v1.2

### v1.2 -1.20 only

*There's a lot of mod support I'd like to add, but I'm holding out hope that the modded compat add-on gets ported (since it does a vastly better job for the mods I want to add support for). So, if it doesn't get ported I'll try to add support myself.*

Ported to 1.20.1

Retextured item slots in Malum's JEI tabs
- Sadly, I can't backport this change since the assets either don't exist or are buried somewhere (even the dev wasn't sure about it lol) - but at least they finally match on this version.

Added gold coloured text for Crafting Automat
- I can't do this for every mod (since most re-use the block name, and changing the block's name to gold looks wrong) - but I will try to do it for any mods that use a separate lang line for container UIs.

Mod support added:
- Crafting Tweaks
- Industrial Foregoing Souls
- Maulm (the 2 new JEI tabs that were added)
- Thermal Extra (it's got machines in this version)

<br />

### v1.2 - 1.19 only

Removed Blood Magic support since it's not on this version<br />
Renamed Thermal Systeams' folder to match the mod ID<br />
Colourized the text on Crafting Automat's UI

Mod support added:
- Crafting Tweaks

<br />

### v1.2 - 1.18 only

Fixed the folder for Thermal Systeams not matching its mod ID<br />
Colourized the text on Crafting Automat's UI

Mod support added:
- Crafting Tweaks


<br /> <br />

--------------------------------------------------
## v1.1

### v1.1 - 1.19 only

Ported to 1.19

Updated Extended Crafting support to match its new asset system<br />
Updated the UIs for the Weaver's Workbench and Spirit Pouch [Malum]

Mod support added:
- The Aurorian
- Crafting Automat
- Forestry: Community Edition

<br />

### v1.1 - 1.18 only

Fixed the Basic Table's crafting slots having the wrong textures [Extended Crafting]<br />
Updated the UIs for the Weaver's Workbench and Spirit Pouch [Malum]

Mod support added:
- Crafting Automat


<br /> <br />

--------------------------------------------------
## v1.0

*This update adds all the support I initially planned (in addition to five other mods), so we're finally at v1.0!*

*Feel free to suggest other mods to add support for - just make sure to check if another Stoneborn add-on does it, as this one is meant to cover mods that better add-ons don't do.*

<br />

Fixed the incorrect decal spacing on Thermal Series UIs<br />
Finished Thermal Series support (realized I missed quite a few buttons)<br />
Changed the colour of button icons on Thermal Series and Industrial Foregoing UIs
- If y'all think it was better beforehand, let me know and I can revert it.

<br />

Mod support added:
- Blood Magic
- Botania *(Trinket Case and Flower Pouch UIs)*
- Clayworks
- Hostile Neural Networks
- Lightman's Currency
- Lightman's Currency Tech
- Malum
- Scannable
- Simply Jetpacks 2
- Woodworks


<br /> <br />

--------------------------------------------------
## v0.5

Fixed missing pixels on several progress arrows from Extended Crafting<br />
Fixed filled Extended Crafting's Auto Table arrows not matching their unfilled ones

Mod support added:
- Botania (Botanical Brewery JEI fix)
- FTB Quests (quest reward JEI tab)
- Industrial Foregoing
- Nature's Aura


<br /> <br />

--------------------------------------------------
## v0.1

Initial release cuz I got tired of doing UI textures lol.

Supports Extended Crafting and Thermal Series (plus the Systeams and Extra add-ons).

*Re-uploaded this one shortly afterwards to fix the Blast Chiller's JEI progress bar missing a line of pixels.*
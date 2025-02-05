# Stoneborn: Missing Mods Changelog

A full changelog for every version (and sub-version) of the [resource pack](https://curseforge.com/minecraft/texture-packs/stoneborn-missing-mods).

This one will be updated more often than the CurseForge and Modrinth changelogs.

I increment the version by X.1 whenever I add more mod support, and X.X.1 for minor fixes and/or additions I missed in the last patch.

Lines appended with a version in brackets (e.g. [1.20] Text Here) denote changes that only apply to that version.
--------------------------------------------------

## v1.4.2

*I missed more stuff ffs. I hate making tiny hotfixes, man ;-;*

Fixed Crafting Automat's storage slots not rendering<br />
Fixed the Deep Learner slot not being the proper colour

Added support for the following mods:
- AppleSkin (based on Fr_z_n's pack)
- Better Advancements (based on Fr_z_n's pack)
- Cosmetic Armour Reworked (based on Fr_z_n's pack)
- The Twilight Forest


<br /> <br />

--------------------------------------------------
## v1.4.1

*I missed a few things in v1.4, oof*

Added support for the JEI categories from Ad Astra: Giselle Addon<br />
Added support for Masterful Machinery

<br /> <br />

--------------------------------------------------
## v1.4

### 1.20 only

Made the Curios slots for the Deep Learner, Jetpack, and Wallet use the same colours as Minecraft does for empty gear slots

Added the brick background to the Crafting Automat's UI
- I plan to add it to other blocks in the next update, but for now I figured I could slap it into this one as a test run

Colourized the text for a few blocks from Lightman's Currency
- Most of the mod doesn't use the proper translation keys, so I might remove this in the future

Colourized the text in Scannable's UIs
- I can't do the main header though. Ah well.

Added support for the following mods:
- Applied Energistics 2 (based on the one done by Fr_z_n's pack)
- Applied Energistics 2 Wireless Terminals
- Curios API
- Dis-Enchanting Table
- Railcraft Reborn
- Roughly Enough Items (based on the one done by Fr_z_n's pack)
- TrashCan (by Reedomu)

<br /> <br />

--------------------------------------------------
## v1.3

### 1.20 only

Fixed Lightman's Currency's wallet UIs not rendering properly if you used newer versions of the mod ([reported by DankestO](https://github.com/vizthex123/StonebornMissingMods/issues/1))

Added support for Forestry: Community Edition

<br /> <br />

--------------------------------------------------
## v1.2

### 1.20 only

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
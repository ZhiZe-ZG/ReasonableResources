# Reasonable Resources

A data rebalance mod for Rimworld.

## Features

### Cheaper and Easier Components

* [X] [Change] Fabrication bench need plasteel and gold instead of advanced component.
* [X] [Add] Add bulk recipes for components. This recipe will save 20% of the work amount.

### Recycle Items

* [X] [Fix] Recipe `SmeltApparel` no longer allow `NonSmeltableApparel`.
* [X] [Fix] Recipe `SmeltWeapon`  no longer allow `NonSmeltableWeapons`.
* [X] [Add] Add non smeltable apparel recycle recipe for tailoring benches.
* [X] [Add] Add non smeltable  weapons recycle recipe for smithies.
* [X] [Add] Add components smelt recipe and advanced components smelt recipe.

### Harvest Grass Yield Resources

* [X] [Add] Harvest grass yield 2 hay.
* [X] [Add] Harvest tall grass yield 3 hay. The harvest work of tall grass is a little more than grass.
* [X] [Add] Harvest plant bush yield 4 hay. The harvest work of bush is a little more than tall grass.
* [X] [Add] Harvest plant brambles yield 4 hay. The harvest work of brambles is a little more than tall grass.

## Supported Languages

* [X] English

* [X] Simplified Chinese (简体中文)

## Usage

To use mods, please read [RimWorld Wiki: Modding](https://rimworldwiki.com/wiki/Modding) first.

The mods path usually at your RimWorld's installation path (a folder named "mods"). You can just create a folder under the mods folder and copy files of this projection to it (do not copy git folders like `.git`).

If you are a steam user, you can just subscribe this mod at <https://steamcommunity.com/sharedfiles/filedetails/?id=2475460688>. Steam will download this mod automatically. Both subscribed mods and manually copied mods will appear in the in-game mods management menu. You can distinguish the source of mods in the mods management menu by their icons.

Generally, you need to enable it in the mods management menu after installing the mod.

## About Mod Releasion

This section offer informations to help you release your mod. If you are just a mod user, you can skip this.

As mentioned above, RimWorld can load local file mods as well as steam subscriptions. So, the easiest way to release your mod is release your mod files by any way.

If you want to upload your mod to the Steam Workshop, you must have a RimWorld from Steam. Then open the `Development mode` in `Options` and copy your mod to the local mods path. Open the mods management menu and find your local mod. Click the `Advanced` button and you will see the `Up on Steam Workshop`.

The first time you upload your mod to Steam, you will get a mod id. This is used to identify the mod, so different mods will have different ids. This information is included in the URL of your mod's page on the Steam Workshop.

Next time you release a mod, if you want to update your old mod, instead of releasing the new version as another mod, you can create a file named as `./About/PublishedFileId.txt` under your local mod path and copy your mod id into it. If you still don't know how, check the files in this project.

## To Do

* [X] Update to RimWorld 1.3
* [X] Update to RimWorld 1.4
* [X] Update to RimWorld 1.5
* [X] Harvest grass get resources
* [ ] Bone mod compatibility
* [ ] Mixed resources
* [ ] More component types

## Inspired By

* [Reasonable Components](https://steamcommunity.com/sharedfiles/filedetails/?id=1542915888) `twistedpacifist.ReasonableComponents`
* [Recycle](https://steamcommunity.com/sharedfiles/filedetails/?id=1534883539) `sneaks.recycle`
* [Grass Is Still Hay](https://steamcommunity.com/sharedfiles/filedetails/?id=2193891816) `elkyelky.GrassIsStillHay`

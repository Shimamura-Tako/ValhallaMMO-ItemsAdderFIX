# ValhallaMMO-ItemsadderFIX
Make your ValhallaMMO resource pack no longer conflict with ItemsAdder.

[[中文文档]](README_zhcn.md)

## What is this?
This magical extension allows your ValhallaMMO resource pack to no longer conflict with your ItemsAdder item textures, and also works with other resource packs that use IA (such as the Slimefun resource pack).

Compatible with ValhallaTrinkets and ValhallaMMO Premium, as well as Piles if you're using [Piles-ItemsAdderFIX](https://github.com/Shimamura-Tako/Piles-ItemsAdderFIX).

**Currently, this extension does not support version 1.21.11 because ItemsAdder hasn't been updated to support it yet. this is not an issue on my end.**

## How to use?
0. Download this repository and extract it on your server host

1. Place the `valhallafix` folder in the `contents` directory, execute `/iareload` and `/iazip`, then load the `generated.zip` resource pack

2. Modify the ValhallaMMO resource pack by deleting all files in the `assets/minecraft/items` directory, then load it in the game above `generated.zip`

3. That's it! Now you can freely create any items without worrying about texture conflicts with ValhallaMMO

4. It is recommended to use BungeeResourcepacks or other plugins to send resource packs to players in the correct order.

## I'm encountering an issue!
Please submit an issue in this repository instead of going to ValhallaMMO's repository, because this extension was created by me, not by Athlaeos.

## Why am I having issues using it on versions below 1.21.4?
This extension was initially created for my own server, which runs on version 1.21.8 with ValhallaMMO version 1.7.1 (Premium 1.10.1).

Therefore, you might encounter some minor problems when using it on older server versions (This point needs verification—wait for me to check with Athlaeos).

However, if you really need it for lower versions, try using DeepSeek, ChatGPT, or other AI tools to help you create a compatible version for lower Minecraft versions.

***Support for lower versions added to future plans***

## Future Plans
- ~Compatibility with bow and crossbow~ 12/23/25
- Support 1.19-1.21.1
- Support 1.21.2-1.21.3 *(will anyone actually use this version?)*
- Replace all `textures` methods with `model_path` methods (Probably not, because this isn't mandatory and would require me to rewrite a lot of configs)

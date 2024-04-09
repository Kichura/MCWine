![MCWine Icon](https://i.imgur.com/sykJqfG.png)
# MCWine

MCWine is a fabric-based modpack designed to bring better performance, brand new fixes, more accessibility and a compatibility system to allow players to connect to newer & older servers out of the box.

## Installing This Modpack (Official/Vanilla Method)

1. [**Click here to download the development version,**](https://github.com/Kichura/MCWine/archive/refs/heads/Nightly.zip)
2. Open your Minecraft folder,
3. Open the ZIP-archive you have downloaded from step one,
4. Extract the MCWine-Nightly folder from the ZIP-archive to .minecraft/versions folder, if asked - replace the files,
5. Restart your minecraft launcher,
6. Create a new installation instance by heading to "Installations" and choosing the **+** icon,
7. Choose the version "release MCWine-Nightly" from versions list which should be on the top,
8. Change the game directory from default to .minecraft/versions/MCWine-Nightly folder,
9. Save the instance and attempt to run the instance.

## Installing This Modpack (Prism Launcher Method)

1. [**Click here to download the development version,**](https://github.com/Kichura/MCWine/archive/refs/heads/PrismMC-Nightly.zip)
2. Drag the ZIP-archive to Prism Launcher window; and hit OK in the window that pops up,
3. Double-click that version you just created to launch the modpack.

## Updating Java Version (Optional)

It is recommended that you use [Java 21 (Lite JDK)](https://bell-sw.com/pages/downloads) to allow minecraft to make use of the latest java version.

## JVM Arguments (Optional)

It is recommended that you use these JVM arguments for this modpack:

`-Xms3G -Xmx3G -Dfile.encoding=UTF-8 -Dowo.handshake.disable=true -Dloader.disable_beacon=true -XX:+AlwaysPreTouch -XX:+DisableExplicitGC -XX:+UseShenandoahGC`

*(You can change the ```-Xmx3G``` and ```-Xms3G``` values in order to manage the game RAM on how much to use for Minecraft, But depends on your computer's hardware; Both of those are not needed in Prism Launcher however as it uses it's own configurators for that)*

## Mods + Resource Pack Assets Used For This Pack

Please [check this page](https://github.com/Kichura/MCWine/tree/Nightly/sources/mods_used.md) for a whole list of mods that have been used for this modpack,

For the resource pack list, It can be found [in this page](https://github.com/Kichura/MCWine/tree/Nightly/sources/resources_used.md) instead.

## Special Thanks To

- [FlashyReese](https://github.com/FlashyReese) for helping me create this entire readme document and for the making of Sodium Extras,
- [MrMangoHands](https://github.com/mrmangohands) for helping out with sharing the [lithium configuration codes](https://github.com/CaffeineMC/lithium-fabric/blob/develop/lithium-mixin-config.md),
- [Julienraptor01](https://github.com/Julienraptor01), [ImZxhir](https://github.com/Imzxhir) and [Braxlin](https://github.com/Braxlin) for suggesting mod replacements and other improvements,
- [The ViaVersion Team](https://github.com/ViaVersion/ViaVersion) & [The WineHQ Team](https://www.winehq.org) for inspiring me to create this modpack from the ground-up,
- [The modpack testers](https://pastebin.com/raw/QknQpyZ0) who helped making the modpack better as much as possible,
- [triphora](https://github.com/triphora) for assisting me with publishing MCWine to modrinth.

## Disclaimers

1. It cannot be guaranteed that ViaFabric + ViaBackwards + ViaRewind are allowed on specific servers as they can possibly cause problems with anti-cheat plugins,
2. I do not take any responsibility for any issues caused by this pack - Any action you do is completely on your own,
3. This modpack does not ship with mod menu as most configurations for each mod have been pre-baked. but you can install it regardless,
4. Some mods will possibly contain bugs that can break this client - If you are sensitive to these issues; You can disable the specific mods to play without them,
5. This modpack requires the use of OpenGL 3.3 or higher but if you wish to try and unlock this on your older GPU - [Learn more here,](https://gist.github.com/Kichura/9fa44010d8ed9e5733d258292e327001)
6. Certain keybinds in this modpack have been modified, The new keybinds can be [seen here.](https://github.com/Kichura/MCWine/blob/Nightly/sources/keybinds.md)

## Modrinth Version

This modpack is available on modrinth as a lightweight version, but will not ship with all the mods included in this repository; If you wanna check it out anyways then [click here.](https://modrinth.com/modpack/mcwine)

## License

MCWine is licensed under MIT *(No Attribution)*, a free and open-source license. For more information, please see the [license file.](https://github.com/Kichura/MCWine/blob/Nightly/LICENSE)

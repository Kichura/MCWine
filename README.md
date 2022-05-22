![MCWine Icon](https://i.imgur.com/sykJqfG.png)
# MCWine

MCWine is a fabric-based modpack designed to bring better performance, brand new fixes, more accessibility and a compatibility system to allow players to connect to newer & older servers out of the box.

## Installing this modpack (Official/Vanilla Method)

1. [**Click here to download the development version,**](https://github.com/Kichura/MCWine/archive/refs/heads/Dev.zip)
2. Open your Minecraft folder,
3. Open the zip file you have downloaded from step one,
4. Copy the MCWine-XXXX folder from ZIP to .minecraft/versions folder, if asked - replace the files,
5. Restart your minecraft launcher,
6. Create a new installation instance by heading to "Installations" and choosing the + icon,
7. Choose the version "MCWine-XXXX" from versions list which should be on the top,
8. Change the game directory from default to .minecraft/versions/MCWine-XXXX folder,
9. Make sure the new instance has java 17 or greater selected from the "more options" page,
10. Save the instance and attempt to run the instance.

## Installing this modpack (MultiMC Method)

1. [**Click here to download the development version,**](https://github.com/Kichura/MCWine/archive/refs/heads/MultiMC-Dev.zip)
2. Drag the ZIP into the MultiMC window,
3. Make sure the installed instance has Java 17 or greater installed.

## Updating Java Version (Optional)

It is recommended that you use [Java 19](https://jdk.java.net/19) to allow minecraft to make use of the latest java version.

*Although now requires ```javacheck.jar``` to be deleted as reported in [MCL-18306](https://bugs.mojang.com/browse/MCL-18306). (But if you use MultiMC instead then skip the ```javacheck.jar``` removal requirement)*

## JVM Arguments (Optional)

It is recommended that you use [one of these specific scripts](https://github.com/Kichura/MCWine/tree/Dev/sources/jvm_arguments.md) as your JVM arguments instead of the defaults.

*(You can change the ```-Xmx2G``` including ```-Xms2G``` value from the pastebin in order to manage the game RAM on how much to use for Minecraft, But depends on your computer's hardware; Both of those are not needed in MultiMC however as it uses it's own configurators for that)*

## Mods + Resource Pack assets used for this pack

Please [check this page](https://github.com/Kichura/MCWine/tree/Dev/sources/mods_used.md) for a whole list of mods that have been used for this modpack,

For the resource pack list, It can be found [in this page](https://github.com/Kichura/MCWine/tree/Dev/sources/resources_used.md) instead.

## Special thanks to

- [FlashyReese](https://github.com/FlashyReese) for helping me create this entire readme document,
- [MrMangoHands](https://github.com/mrmangohands) for helping out with sharing the [lithium configuration codes](https://github.com/CaffeineMC/lithium-fabric/blob/1.18.x/dev/src/main/java/me/jellysquid/mods/lithium/common/config/LithiumConfig.java),
- [Julienraptor01](https://github.com/Julienraptor01) for suggesting a mod replacement that improves ToolTips-Scroller mod,
- [robotkoer](https://www.curseforge.com/minecraft/modpacks/fabulously-optimized), [The ViaVersion Team](https://viaversion.com), [The ProtocolSupport Team](https://protocol.support) & [The WineHQ Team](https://www.winehq.org) for inspiring me to create this modpack from the ground-up.

## Disclaimers

1. It cannot be guaranteed that ViaFabric + ViaBackwards are allowed on specific servers as they can possibly cause problems with anti-cheat plugins,
2. I do not take any responsibility for any issues caused by this pack - Any action you do is completely on your own,
3. This modpack does not ship with mod menu as most configurations for each mod have been pre-baked. but you can install it regardless,
4. Some mods will possibly contain bugs that can break this client - If you are sensitive to these issues; You can disable the specific mods to play without them.

## Modrinth Version

This modpack is available on modrinth as a lightweight version, but will not ship with all the mods included in this repository; If you wanna check it out anyways then [click here.](https://modrinth.com/modpack/mcwine)

## License

MCWine is licensed under MIT, a free and open-source license. For more information, please see the [license file](https://github.com/Kichura/MCWine/blob/Dev/LICENSE).

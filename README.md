![MCWine Icon](https://i.imgur.com/sykJqfG.png)
# MCWine

MCWine is a fabric-based modpack designed to bring better performance, brand new fixes, more accessibility and a compatibility system to allow players to connect to newer & older servers out of the box.

## Installing This Modpack (Official/Vanilla Method)

1. [**Click here to download the development version,**](https://github.com/Kichura/MCWine/archive/refs/heads/Dev.zip)
2. Open your Minecraft folder,
3. Open the ZIP-archive you have downloaded from step one,
4. Extract the MCWine-Dev folder from the ZIP-archive to .minecraft/versions folder, if asked - replace the files,
5. Restart your minecraft launcher,
6. Create a new installation instance by heading to "Installations" and choosing the **+** icon,
7. Choose the version "release MCWine-Dev" from versions list which should be on the top,
8. Change the game directory from default to .minecraft/versions/MCWine-Dev folder,
9. Save the instance and attempt to run the instance.

## Installing This Modpack (Prism Launcher Method)

1. [**Click here to download the development version,**](https://github.com/Kichura/MCWine/archive/refs/heads/PrismMC-Dev.zip)
2. Drag the ZIP-archive to Prism Launcher window; and hit OK in the window that pops up,
3. Double-click that version you just created to launch the modpack.

## Updating Java Version (Optional)

It is recommended that you use [Java 20 (Lite JDK)](https://bell-sw.com/pages/downloads) to allow minecraft to make use of the latest java version.

*Although now requires ```javacheck.jar``` to be deleted as reported in [MCL-18306](https://bugs.mojang.com/browse/MCL-18306). (But if you use Prism Launcher instead then skip the ```javacheck.jar``` removal requirement)*

## JVM Arguments (Optional)

It is recommended that you use [one of these specific scripts](https://github.com/Kichura/MCWine/tree/Dev/sources/jvm_arguments.md) as your JVM arguments instead of the defaults.

*(You can change the ```-Xmx3G``` including ```-Xms3G``` value from the list itself in order to manage the game RAM on how much to use for Minecraft, But depends on your computer's hardware; Both of those are not needed in Prism Launcher however as it uses it's own configurators for that)*

## Mods + Resource Pack Assets Used For This Pack

Please [check this page](https://github.com/Kichura/MCWine/tree/Dev/sources/mods_used.md) for a whole list of mods that have been used for this modpack,

For the resource pack list, It can be found [in this page](https://github.com/Kichura/MCWine/tree/Dev/sources/resources_used.md) instead.

## Special Thanks To

- [FlashyReese](https://github.com/FlashyReese) for helping me create this entire readme document,
- [MrMangoHands](https://github.com/mrmangohands) for helping out with sharing the [lithium configuration codes](https://github.com/CaffeineMC/lithium-fabric/blob/1.19.x/dev/lithium-mixin-config.md),
- [Julienraptor01](https://github.com/Julienraptor01) and [ImZxhir](https://github.com/Imzxhir) for suggesting mod replacements and other improvements,
- [The ViaVersion Team](https://github.com/ViaVersion/ViaVersion), [The ProtocolSupport Team](https://github.com/ProtocolSupport/ProtocolSupport) & [The WineHQ Team](https://www.winehq.org) for inspiring me to create this modpack from the ground-up,
- [The modpack testers](https://pastebin.com/raw/QknQpyZ0) who helped making the modpack better as much as possible,
- [triphora](https://github.com/triphora) for assisting me with publishing MCWine to modrinth.

## Disclaimers

1. It cannot be guaranteed that ViaFabric + ViaBackwards + ViaRewind are allowed on specific servers as they can possibly cause problems with anti-cheat plugins,
2. Due to technical limitations with the "enforce-secure-profile" feature from 1.19.1+ servers at this time; This will cause ViaFabric to malfunction with those servers,
3. I do not take any responsibility for any issues caused by this pack - Any action you do is completely on your own,
4. This modpack does not ship with mod menu as most configurations for each mod have been pre-baked. but you can install it regardless,
5. Some mods will possibly contain bugs that can break this client - If you are sensitive to these issues; You can disable the specific mods to play without them,
6. This modpack requires the use of OpenGL 3.3 or higher but if you wish to try and unlock this on your older GPU, [Learn more here](https://gist.github.com/Kichura/9fa44010d8ed9e5733d258292e327001).

## Modrinth Version

This modpack is available on modrinth as a lightweight version, but will not ship with all the mods included in this repository; If you wanna check it out anyways then [click here.](https://modrinth.com/modpack/mcwine)

## License

MCWine is licensed under MIT, a free and open-source license. For more information, please see the [license file.](https://github.com/Kichura/MCWine/blob/Dev/LICENSE)


![MCWine Icon](https://i.imgur.com/sykJqfG.png)
# MCWine
MCWine is a fabric-based modpack designed to bring better performance, brand new fixes and a compatibility system to allow players to connect to older servers out of the box.

### Installing this modpack ([Official/Vanilla Method](https://github.com/Kichura/MCWine/tree/Standard))

Download MCWine as ZIP by navigating to the "Code" button and then pressing "Download ZIP" from there. Then you will be required to drop the main folder (With folder containing it's files such as mods and whatnot) inside that ZIP to your minecraft's versions folder. After this you must reload your minecraft launcher to make a new profile by changing the game directory to the extracted version folder and then changing the version to the modpack itself.

### Installing this modpack ([MultiMC Method](https://github.com/Kichura/MCWine/tree/MultiMC-Standard))

Download MCWine as ZIP by navigating to the "Code" button and then pressing "Download ZIP" from there. After this you must open up your MultiMC launcher -> Click on "Add Instance" and import the ZIP to your MultiMC instance and press OK to confirm the changes.

### Recommended Java Version

It is recommended that you use [AdoptOpenJDK with HotSpot](https://adoptopenjdk.net/?variant=openjdk11&jvmVariant=hotspot) to allow minecraft to make use of the Shenandoah Garbage Collector. For JVM Arguments it is recommended that you use: ```-Xmx3G -XX:+UnlockExperimentalVMOptions -XX:+UseShenandoahGC -XX:+DisableExplicitGC``` as your arguments instead of default (You can change the RAM of ```-Xmx3G``` value if you want more RAM or less to be used, But depends on your computer's hardware) for better results as the Z garbage collector (ZGC) is considered to be memory-hungry in some conditions.

### Alternate MCWine branch

If you believe Sodium or ViaFabric does not work out properly on your computer, Then you can try to fall back to the [Alternate Branch](https://github.com/Kichura/MCWine/tree/Alternate) in order to make use of Canvas + MultiConnect instead. The method of this branch should be identical like the Vanilla method, But if you use MultiMC then you can try this [Alternate MultiMC branch](https://github.com/Kichura/MCWine/tree/MultiMC-Alternate) instead.

### Lite MCWine branch

If you need to acquire a smaller version of this modpack, Then you can [try this branch](https://github.com/Kichura/MCWine/tree/Lite) out for a lite version (For the MultiMC version, [See this page instead](https://github.com/Kichura/MCWine/tree/MultiMC-Lite)).

### The following mods are owned by (Using original names with URLs instead):

- [Audio-Management (Aka Audio Output)](https://www.curseforge.com/minecraft/mc-mods/audio-output) - **Maximumgame**,
- [BrandPacket](https://www.curseforge.com/minecraft/mc-mods/brandpacket) - **liachmodded**,
- [Dynamic-Lights (Aka LambDynamicLights)](https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights) - **LambdAurora**,
- [Fabric-API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) - **asiekierka**, **sfPlayer1**, **modmuss50**,
- [Fabric-LowHealth (Aka Damage Tint)](https://www.curseforge.com/minecraft/mc-mods/damage-tint) - **DeadlyMC_**,
- [Fix-ChatPosition (Aka Chat Up!)](https://www.curseforge.com/minecraft/mc-mods/chat-up) - **gnembon**,
- [Fix-ItemModels (Aka Item Model Fix)](https://www.curseforge.com/minecraft/mc-mods/item-model-fix) - **Pepper_Bell**,
- [Fix-Retina (Aka RetiNO)](https://www.curseforge.com/minecraft/mc-mods/retino) - **juliand665**,
- [Fix-SkyColor (Aka Clear Skies)](https://www.curseforge.com/minecraft/mc-mods/clear-skies) - **grondagthebarbarian**,
- [Fix-ToolTips (Aka ToolTipFix)](https://www.curseforge.com/minecraft/mc-mods/tooltipfix) - **Kyrptonaught**,
- [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) - **jellysquid_**,
- [Persist-Sneaking (Aka Sneaky Screens)](https://www.curseforge.com/minecraft/mc-mods/sneaky-screens) - **haykam**,
- [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor) - **jellysquid_**,
- [Sodium](https://github.com/jellysquid3/sodium-fabric/tree/1.16.x/next) - **jellysquid_**,
- [Tweakeroo](https://www.curseforge.com/minecraft/mc-mods/tweakeroo) - **masady, CFGrafanaStats**,
- [Vanilla-Branding (Aka Branding)](https://github.com/LoganDark/fabric-branding) - **LoganDark**,
- [ViaFabric](https://www.curseforge.com/minecraft/mc-mods/viafabric) - **creeper12312332, KennyTVN**,
- [Zoom (Aka Ok Zoomer)](https://www.curseforge.com/minecraft/mc-mods/ok-zoomer) - **boredomh1**,

- Modpack creator of MCWine - [Kichura](https://github.com/Kichura/MCWine).

### Additional thanks to

- FlashyReese for helping me create this entire readme document,
- LoganDark for telling me how to [resolve](https://github.com/LoganDark/fabric-branding/issues/1) the version string issue for "vanilla" context in F3 screen,  
- MrMangoHands for helping out with sharing the [lithium configuration codes](https://github.com/jellysquid3/lithium-fabric/blob/1.16.x/dev/src/main/java/me/jellysquid/mods/lithium/common/config/LithiumConfig.java),
- [Vanilla Tweaks](https://vanillatweaks.net/picker/resource-packs) for making the "Default+" resource pack possible,
- DragonEggBedrockBreaking for the [absorption heart fix](https://github.com/DragonEggBedrockBreaking/chat-up) to "Chat Up!",
- [Z-8Bit](https://github.com/Z-8Bit) for suggesting a mod replacement for audio reloader.


### Found a bug/issue via MCWine (Mods only)?

Please contact the original authors at github or their discord servers for more details instead of [me](https://github.com/Kichura) as i do NOT own any of the following mods as said above. I also am NOT responsible for any damages or broken mods that are mentioned above in the mods list, You can however choose to contact [me](https://github.com/Kichura) if you believe something is in error and requires a fix for it as soon as possible.

### Where the name "MCWine" comes from

The name "MCWine" is an inspired name from the linux software ["Wine"](https://github.com/wine-mirror/wine) where you can run your favorite windows applications using any older windows version you like on the linux environment without having to emulate them inside a virtual machine utility, Wine also keeps the performance intact thanks to it's compatibility layer; Allowing users to keep up their applications without losing any performance from their real hardware. Thous i chose the name "MCWine" for this entire modpack as a strong reference.

### License

MCWine is licensed under GNU LGPLv3, a free and open-source license. For more information, please see the [license file](https://github.com/Kichura/MCWine/blob/Standard/LICENSE).

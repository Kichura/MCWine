
![MCWine Icon](https://i.imgur.com/sykJqfG.png)
# MCWine
MCWine is a fabric-based modpack designed to bring better performance, brand new fixes and a compatibility system to allow players to connect to older servers out of the box.

(This project may contain bugs via specific mods, If you are sensitive to these kinds of issues; Please use pure vanilla of minecraft instead)

### Installing this modpack ([Official/Vanilla Method](https://github.com/Kichura/MCWine/tree/Standard))

Download MCWine as ZIP by navigating to the "Code" button and then pressing "Download ZIP" from there. Then you will be required to drop the main folder (With folder containing it's files such as mods and whatnot) inside that ZIP to your minecraft's versions folder. After this you must reload your minecraft launcher to make a new profile by changing the game directory to the extracted version folder and then changing the version to the modpack itself.

### Installing this modpack ([MultiMC Method](https://github.com/Kichura/MCWine/tree/MultiMC-Standard))

Download MCWine as ZIP by navigating to the "Code" button and then pressing "Download ZIP" from there. After this you must open up your MultiMC launcher -> Click on "Add Instance" and import the ZIP to your MultiMC instance and press OK to confirm the changes.

### Recommended Java Version

It is recommended that you use [AdoptOpenJDK with HotSpot](https://adoptopenjdk.net/?variant=openjdk16&jvmVariant=hotspot) to allow minecraft to make use of the Z Garbage Collector. For JVM Arguments it is recommended that you use [these specific scripts](https://pastebin.com/raw/0sxGeJ1N) as your arguments instead of default (You can change the RAM of ```-Xmx2G``` value from the pastebin if you want more RAM or less to be used, But depends on your computer's hardware) for better results as the Shenandoah garbage collector (ShenandoahGC) is considered to be memory-hungry in some conditions.

Although this should NOT be confused as this giving out any performance as this is mainly made to manage the garbage collection system for any possible improvement, don't use this if your current configuration is already good to go unless it is poorly maintained.

### Alternate MCWine branch

If you believe Sodium or ViaFabric or Phosphor does not work out properly on your computer, Then you can try to fall back to the [Alternate Branch](https://github.com/Kichura/MCWine/tree/Alternate) in order to make use of Canvas + MultiConnect + Starlight instead. The method of this branch should be identical like the Vanilla method, But if you use MultiMC then you can try this [Alternate MultiMC branch](https://github.com/Kichura/MCWine/tree/MultiMC-Alternate) instead.

### Lite MCWine branch

If you need to acquire a smaller version of this modpack, Then you can [try this branch](https://github.com/Kichura/MCWine/tree/Lite) out for a lite version (For the MultiMC version, [See this page instead](https://github.com/Kichura/MCWine/tree/MultiMC-Lite)).

### The following mods are owned by (Using original names with URLs instead):

- [Alternate-EntityCulling (Aka EntityCulling Fabric/Forge)](https://www.curseforge.com/minecraft/mc-mods/entityculling) - **tr9zw**,
- [Audio-Management (Aka Audio Output)](https://www.curseforge.com/minecraft/mc-mods/audio-output) - **Maximumgame**,
- [BrandPacket](https://www.curseforge.com/minecraft/mc-mods/brandpacket) - **liachmodded**,
- [Dynamic-Lights (Aka LambDynamicLights)](https://modrinth.com/mod/lambdynamiclights) - **LambdAurora**,
- [Fabric-API](https://modrinth.com/mod/fabric-api) - **sfPlayer1**, **modmuss50**,
- [FerriteCore](https://modrinth.com/mod/ferrite-core) - **malte0811**,
- [Fix-Advancements (Aka Advancements Debug)](https://www.curseforge.com/minecraft/mc-mods/advancements-debug) - **thetechnici4n**,
- [Fix-ChatPosition (Aka Chat Up!)](https://www.curseforge.com/minecraft/mc-mods/chat-up) - **gnembon**,
- [Fix-ItemModels (Aka Item Model Fix)](https://www.curseforge.com/minecraft/mc-mods/item-model-fix) - **Pepper_Bell**,
- [Fix-SkyColor (Aka Clear Skies)](https://www.curseforge.com/minecraft/mc-mods/clear-skies) - **grondagthebarbarian**,
- [Fix-ToolTips (Aka ToolTipFix)](https://www.curseforge.com/minecraft/mc-mods/tooltipfix) - **Kyrptonaught**,
- [Horse-Stats (Aka Horse Stats Vanilla)](https://www.curseforge.com/minecraft/mc-mods/horsestatsvanilla) - **TeaJ4y**,
- [LazyDFU](https://modrinth.com/mod/lazydfu) - **astei**,
- [Lithium](https://modrinth.com/mod/lithium) - **CaffeineMC**,
- [LowHealth-Warning (Aka Damage Tint)](https://www.curseforge.com/minecraft/mc-mods/damage-tint) - **DeadlyMC_**,
- [NoFlashing-NightVision (Aka Night Vision flash be gone)](https://www.curseforge.com/minecraft/mc-mods/night-vision-flash-be-gone) - **AshIndigo**,
- [Persist-Sneaking (Aka Sneaky Screens)](https://www.curseforge.com/minecraft/mc-mods/sneaky-screens) - **haykam**,
- [Phosphor](https://modrinth.com/mod/phosphor) - **CaffeineMC**,
- [Sodium](https://github.com/CaffeineMC/sodium-fabric/tree/1.16.x/next) - **CaffeineMC**,
- [Third-Person Maps](https://www.curseforge.com/minecraft/mc-mods/third-person-maps) - **Pepperoni__Jabroni__**,
- [Tweakeroo](https://masa.dy.fi/mcmods/client_mods/?mcver=1.16.4&mod=tweakeroo) - **masady, CFGrafanaStats**,
- [Vanilla-Branding (Aka Branding)](https://github.com/LoganDark/fabric-branding) - **LoganDark**,
- [ViaBackwards](https://github.com/ViaVersion/ViaBackwards/tree/dev) - **KennyTVN**,
- [ViaFabric](https://www.curseforge.com/minecraft/mc-mods/viafabric) - **creeper12312332, KennyTVN**,
- [ViaRewind](https://github.com/ViaVersion/ViaRewind/tree/dev) - **KennyTVN**,
- [Zoom (Aka Ok Zoomer)](https://modrinth.com/mod/ok-zoomer) - **boredomh1**,

- Modpack creator of MCWine - [Kichura](https://github.com/Kichura/MCWine).

### Additional thanks to

- FlashyReese for helping me create this entire readme document,
- LoganDark for telling me how to [resolve](https://github.com/LoganDark/fabric-branding/issues/1) the version string issue for "vanilla" context in F3 screen,  
- MrMangoHands for helping out with sharing the [lithium configuration codes](https://github.com/jellysquid3/lithium-fabric/blob/1.16.x/dev/src/main/java/me/jellysquid/mods/lithium/common/config/LithiumConfig.java),
- [Vanilla Tweaks](https://vanillatweaks.net/picker/resource-packs) & [TheMobCave](https://www.youtube.com/watch?v=9PYpUCo8TKQ) for making the "Default+" resource pack possible,
- DragonEggBedrockBreaking for the [absorption heart fix](https://github.com/DragonEggBedrockBreaking/chat-up) to "Chat Up!",
- [Z-8Bit](https://github.com/Z-8Bit) for suggesting a mod replacement for audio reloader,
- [SalC1](https://salc1.com) & [thgabs](https://www.curseforge.com/minecraft/texture-packs/programmer-art-fix) for making the "Programmer Art+" resource pack possible.


### Found a bug/issue via MCWine (Mods only)?

Please contact the original authors at github or their discord servers for more details instead of me as i do NOT own any of the following mods as said above. I also am NOT responsible for any damages or broken mods that are mentioned above in the mods list, You can however choose to contact me if you believe something is in error and requires a fix for it as soon as possible.

### License

MCWine is licensed under GNU GPLv3, a free and open-source license. For more information, please see the [license file](https://github.com/Kichura/MCWine/blob/Standard/LICENSE).

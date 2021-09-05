![MCWine Icon](https://i.imgur.com/sykJqfG.png)
# MCWine
MCWine is a fabric-based modpack designed to bring better performance, brand new fixes and a compatibility system to allow players to connect to older servers out of the box.

(This project may contain bugs via specific mods, If you are sensitive to these kinds of issues; Please don't use modpack unless you know any better)

### Installing this modpack ([Official/Vanilla Method](https://github.com/Kichura/MCWine/tree/Standard))

Download MCWine as ZIP by navigating to the "Code" button and then pressing "Download ZIP" from there. Then you will be required to drop the main folder (With folder containing it's files such as mods and whatnot) inside that ZIP to your minecraft's versions folder. After this you must reload your minecraft launcher to make a new profile by changing the game directory to the extracted version folder and then changing the version to the modpack itself.

### Installing this modpack ([MultiMC Method](https://github.com/Kichura/MCWine/tree/MultiMC-Standard))

Download MCWine as ZIP by navigating to the "Code" button and then pressing "Download ZIP" from there. After this you must open up your MultiMC launcher -> Click on "Add Instance" and import the ZIP to your MultiMC instance and press OK to confirm the changes.

### Recommended Java Version

It is recommended that you use the built-in Java 16 version to allow minecraft to make use of the latest java version. For nightly builds; See the [Java 17](https://jdk.java.net/17) builds instead, although now requires ```javacheck.jar``` to be deleted as seen in this [clip](https://streamable.com/i3voeu). (But if you use MultiMC instead then skip the ```javacheck.jar``` removal requirement)

For JVM Arguments; It is recommended that you use [one of these specific scripts](https://pastebin.com/raw/ay46r2SJ) from this pastebin as your JVM arguments instead of the defaults. (You can change the RAM of ```-Xmx2G``` value from the pastebin if you want more RAM or less to be used, But depends on your computer's hardware)

*Although this should NOT be confused as this giving out any performance as this is mainly made to manage the garbage collection system for any possible improvement, don't use this if your current configuration is already good to go unless your current java instance runs poorly.*

### Alternate MCWine branch

If you believe some mods don't work well properly on your computer via Standard/Lite, Then you can try to fall back to the [Alternate Branch](https://github.com/Kichura/MCWine/tree/Alternate) in order to make use of alternate mods instead. The installing method for this branch should be the same for standard, beta and lite, But if you use MultiMC then you can try this [Alternate-MultiMC branch](https://github.com/Kichura/MCWine/tree/MultiMC-Alternate) instead.

### Lite MCWine branch

If you need to use a smaller version of this modpack, Then you can [try this branch](https://github.com/Kichura/MCWine/tree/Lite) out for the lite version (For the MultiMC version, [See this page instead](https://github.com/Kichura/MCWine/tree/MultiMC-Lite)).

*This version will not have several fixes built-in to it but will try to help out the performance some.*

### Beta MCWine branch

If you want to take part of the bleeding edge version of MCWine then you can [try this branch out](https://github.com/Kichura/MCWine/tree/Beta) for the latest mod versions including MC's 1.17.x version instead of the previous one, However please note that this can contain more bugs/issues in this branch unlike the other branches for example.

*For the MultiMC version, Please [see this page](https://github.com/Kichura/MCWine/tree/MultiMC-Beta) instead.*

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
- [Hide-Score (Aka NoMoreScore)](https://github.com/ExoPlant/NoMoreScore) - **ExoPlant**,
- [Horse-Stats (Aka Horse Stats Vanilla)](https://www.curseforge.com/minecraft/mc-mods/horsestatsvanilla) - **TeaJ4y**,
- [Iris](https://github.com/IrisShaders/Iris) - **IrisShaders**,
- [Krypton](https://modrinth.com/mod/krypton) - **astei**,
- [LazyDFU](https://modrinth.com/mod/lazydfu) - **astei**,
- [Lithium](https://modrinth.com/mod/lithium) - **CaffeineMC**,
- [LowHealth-Warning (Aka Damage Tint)](https://www.curseforge.com/minecraft/mc-mods/damage-tint) - **DeadlyMC_**,
- [NoFlashing-NightVision (Aka Night Vision flash be gone)](https://www.curseforge.com/minecraft/mc-mods/night-vision-flash-be-gone) - **AshIndigo**,
- [Persist-Sneaking (Aka Sneaky Screens)](https://www.curseforge.com/minecraft/mc-mods/sneaky-screens) - **haykam**,
- [Skip-ExperimentWarning (Aka Here Be No Dragons!)](https://modrinth.com/mod/here-be-no-dragons) - **kb1000**,
- [Sodium](https://github.com/CaffeineMC/sodium-fabric/tree/1.16.x/next) - **CaffeineMC**,
- [Starlight](https://github.com/Spottedleaf/Starlight) - **Spottedleaf**,
- [Third-Person Maps](https://www.curseforge.com/minecraft/mc-mods/third-person-maps) - **Pepperoni__Jabroni__**,
- [Tweakeroo](https://masa.dy.fi/mcmods/client_mods/?mcver=1.16.4&mod=tweakeroo) - **masady, CFGrafanaStats**,
- [Vanilla-Branding (Aka Branding)](https://github.com/IMS212/fabric-branding) - **LoganDark, IMS212**,
- [ViaFabric](https://www.curseforge.com/minecraft/mc-mods/viafabric) - **creeper12312332, KennyTVN**,
- [Zoom (Aka Ok Zoomer)](https://modrinth.com/mod/ok-zoomer) - **boredomh1**,

- Modpack creator of MCWine - [Kichura](https://github.com/Kichura/MCWine).

### Additional thanks to

- FlashyReese for helping me create this entire readme document,
- MrMangoHands for helping out with sharing the [lithium configuration codes](https://github.com/CaffeineMC/lithium-fabric/blob/1.17.x/dev/src/main/java/me/jellysquid/mods/lithium/common/config/LithiumConfig.java),
- [Z-8Bit](https://github.com/Z-8Bit) for suggesting a mod replacement for audio reloader + giving a performance comparison for J16 + J17,
- [robotkoer](https://www.curseforge.com/minecraft/modpacks/fabulously-optimized) & [The ViaVersion Team](https://github.com/ViaVersion) for inspiring me to create this modpack from the ground-up.

### Resource pack references (Default+):

- [Vanilla Tweaks](https://vanillatweaks.net/picker/resource-packs) - Contains most of the tweaks,
- [TheMobCave](https://www.youtube.com/watch?v=9PYpUCo8TKQ) - Replaces default rain,
- [TinyDaggsy](https://www.curseforge.com/minecraft/texture-packs/animated-furnaces) - Re-Animates the furnaces,
- [EpicCOAwesomeKid](https://www.curseforge.com/minecraft/texture-packs/corrected-mob-heads) - Move heads to camera for better view,
- [funkiestcord67](https://www.curseforge.com/minecraft/texture-packs/repaired-enchanting) - Add further romanic for level 6 - 100,
- [ダイヤ二ゲロウ](https://www.curseforge.com/minecraft/texture-packs/half-width-space-restoration) - Restores half-width spaces for japanese,
- [flatjim_](https://www.curseforge.com/minecraft/texture-packs/gui-retextures) - Overhauls the HUD.

### Resource pack references (Programmer Art+):
- [SalC1](https://salc1.com) - Contains most of the tweaks,
- [thgabs](https://www.curseforge.com/minecraft/texture-packs/programmer-art-fix) - Fixes some of the missing assets,
- [Dimbu_](https://www.curseforge.com/minecraft/texture-packs/programmer-plus) - Make nether update & Caves and Cliffs textures programmer art-like.

### Found a bug/issue via MCWine (Mods only)?

Please contact the original authors at github or their specific social medias for more details instead of me as i do NOT own any of the following mods as said above. I also am NOT responsible for any damages or corruptions caused by one or more mods combined, You can however choose to contact me if you believe something is in error and requires a fix for it as soon as possible.

### License

MCWine is licensed under GNU GPLv3, a free and open-source license. For more information, please see the [license file](https://github.com/Kichura/MCWine/blob/Standard/LICENSE).

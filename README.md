
![MCWine Icon](launcher-icon.png)
# MCWine
MCWine is a fabric-based modpack designed to bring better performance including having the ability to connect to older server versions out of the box.

### Installing this modpack (Official/Vanilla Method)

Download MCWine as ZIP by navigating to the "Code" button and then pressing "Download ZIP" from there. Then you will be required to drop the main folder (With folder containing it's files such as mods and whatnot) inside that ZIP to your minecraft's versions folder. After this you must reload your minecraft launcher to make a new profile by changing the game directory to the extracted version folder and then changing the version to the modpack itself.

### Recommended Java Version

It is recommended that you use [AdoptOpenJDK with OpenJ9](https://adoptopenjdk.net/?variant=openjdk11&jvmVariant=openj9) to allow minecraft to make use of the Shenandoah Garbage Collector. For JVM Arguments it is recommended that you use: ```-Xmx3G -XX:+UnlockExperimentalVMOptions -XX:+UseShenandoahGC``` as your arguments instead of default (You can change the RAM of ```-Xmx3G``` value if you want more RAM or less to be used, But depends on your computer's hardware) for better results as the Z garbage collector (ZGC) is considered to be memory-hungry in some conditions.

### Alternate MCWine branches

If you believe sodium does not work out properly on your computer, Then you can try to fall back to the [OptiFabric branch](https://github.com/Kichura/MCWine/tree/OptiFabric) instead to make use of OptiFine instead of sodium. And if you believe MultiConnect does not work out properly instead, Then you can try to fall back to the [ViaFabric branch](https://github.com/Kichura/MCWine/tree/ViaFabric/mods) instead to make use of ViaFabric instead of MultiConnect. You can also combine ViaFabric + OptiFabric if you want both to run at once but you must remove **Sodium**, **Lithium**, **MultiConnect**, **Dynamic-Lights** from your own profile to avoid conflicts.


### The following mods are owned by (Using original names with URLs instead):

- [BrandPacket](https://www.curseforge.com/minecraft/mc-mods/brandpacket) - **liachmodded**,
- [Dynamic-Lights (Aka LambDynamicLights)](https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights) - **LambdAurora**,
- [Fabric-API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) - **asiekierka**, **sfPlayer1**, **modmuss50**,
- [Fabric-AudioReloader (Aka Reload Audio Driver)](https://www.curseforge.com/minecraft/mc-mods/reload-audio-driver-fabric) - **CJMinecraft101**, **JayJay1989BE**,
- [Fabric-FixTooltips (Aka ToolTipFix)](https://www.curseforge.com/minecraft/mc-mods/tooltipfix) - **Kyrptonaught**,
- [Fabric-ItemModelFix (Aka Item Model Fix)](https://www.curseforge.com/minecraft/mc-mods/item-model-fix) - **Pepper_Bell**,
- [Fabric-MoveChat (Aka Chat Up!)](https://www.curseforge.com/minecraft/mc-mods/chat-up) - **gnembon**,
- [Fabric-SkyColorFix (Aka Clear Skies)](https://www.curseforge.com/minecraft/mc-mods/clear-skies) - **grondagthebarbarian**,
- [Fix-Retina (Aka RetiNO)](https://www.curseforge.com/minecraft/mc-mods/retino) - **juliand665**,
- [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) - **jellysquid_**,
- [MultiConnect](https://www.curseforge.com/minecraft/mc-mods/multiconnect) - **EarthComputer**,
- [Persist-Sneaking (Aka Sneaky Screens)](https://www.curseforge.com/minecraft/mc-mods/sneaky-screens) - **haykam**,
- [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor) - **jellysquid_**,
- [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium) - **jellysquid_**,
- [Vanilla-Branding (Aka fabric-branding)](https://github.com/LoganDark/fabric-branding) - **LoganDark**,
- [XLPackets](https://www.curseforge.com/minecraft/mc-mods/xl-packets-fabric) - **tfarecnim**,

- Modpack creator of MCWine - [Kichura](https://github.com/Kichura/MCWine).

### Additional thanks to

- FlashyReese for providing an 1.16.2/1.16.3 version of [sodium](https://github.com/FlashyReese/sodium-fabric) + Helping me create this entire readme document,
- LoganDark for telling me how to [resolve](https://github.com/LoganDark/fabric-branding/issues/1) the version string issue for "vanilla" context in F3 screen,  
- MrMangoHands for helping out with sharing the lithium configuration codes. 


### Found a bug/issue via MCWine (Mods only)?

Please contact the original authors at github or their discord servers for more details instead of [me](https://github.com/Kichura) as i do NOT own any of the following mods as said above.

## G1GC

`-Xms3G -Xmx3G -Dfile.encoding=UTF-8 -Dowo.handshake.disable=true -Dloader.disable_beacon=true -XX:+IgnoreUnrecognizedVMOptions -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -Dusing.aikars.flags=https://mcflags.emc.gs -Daikars.new.flags=true`

## ZGC

`-Xms3G -Xmx3G -Dfile.encoding=UTF-8 -Dowo.handshake.disable=true -Dloader.disable_beacon=true -XX:+UnlockExperimentalVMOptions -XX:+IgnoreUnrecognizedVMOptions -XX:+DisableExplicitGC -XX:+PerfDisableSharedMem -XX:+UseZGC -XX:+ZGenerational -XX:-ZUncommit -XX:ZUncommitDelay=300 -XX:ZCollectionInterval=5 -XX:ZAllocationSpikeTolerance=2.0 -XX:+AlwaysPreTouch -XX:+UseTransparentHugePages -XX:LargePageSizeInBytes=2M -XX:+UseLargePages -XX:+ParallelRefProcEnabled`

## Shenandoah

`-Xms3G -Xmx3G -Dfile.encoding=UTF-8 -Dowo.handshake.disable=true -Dloader.disable_beacon=true -XX:+UnlockExperimentalVMOptions -XX:+IgnoreUnrecognizedVMOptions -XX:+UseShenandoahGC -XX:ShenandoahAllocSpikeFactor=5 -XX:ShenandoahControlIntervalAdjustPeriod=1000 -XX:ShenandoahControlIntervalMax=10 -XX:ShenandoahControlIntervalMin=1 -XX:ShenandoahInitFreeThreshold=70 -XX:ShenandoahGarbageThreshold=25 -XX:ShenandoahGuaranteedGCInterval=300000 -XX:ShenandoahMinFreeThreshold=10 -XX:-ShenandoahRegionSampling -XX:ShenandoahRegionSamplingRate=40`

## Disclaimers

1. For the G1 Garbage Collector JVM script to work; Java 8 or newer is required,

2. For the Z Garbage Collector JVM script to work; Java 21 or newer is required instead,

3. For the Shenandoah Garbage Collector JVM script to work; Java 15 or newer is required instead, *(Doesn't support any JDK variants by Oracle)*

4. The -Xms and -Xmx parts can be modified to your own personal likings in case the Java RAM is insufficient,

5. The JVM arguments list above are not supported by OpenJ9 and instead hotspot must be used.


## Sources Used For The Scripts:

[Paper's G1GC documentation](https://docs.papermc.io/paper/aikars-flags),

[Krusic's ZGC tuning blog](https://krusic22.com/2020/03/25/higher-performance-crafting-using-jdk11-and-zgc),

[FroggeMC's ZGC repository](https://web.archive.org/web/20230318212235/https://github.com/cyberpwnn/MC-Java-Flags/blob/c8b2d7ad633768d85f4a92fe01340f8d52081251/README.md),

[FroggeMC's Shenandoah repository](https://web.archive.org/web/20230318212521/https://github.com/cyberpwnn/MC-Java-Flags/blob/5795d0f6fb6486848157e543c0c5db0a595e0328/README.md).

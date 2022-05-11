## Minimal (G1GC)

`-Xms2G -Xmx2G -XX:+UseG1GC -XX:+DisableExplicitGC`

## Heavy (G1GC)

`-Xms2G -Xmx2G -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -Dusing.aikars.flags=https://mcflags.emc.gs -Daikars.new.flags=true`

## Minimal (ZGC)

`-Xms2G -Xmx2G -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:-UseParallelGC -XX:-UseParallelOldGC -XX:-UseG1GC -XX:+UseZGC -XX:-ZUncommit`

## Heavy (ZGC)

`-Xms2G -Xmx2G -XX:+IgnoreUnrecognizedVMOptions -XX:+UnlockExperimentalVMOptions -XX:+UnlockDiagnosticVMOptions -XX:-OmitStackTraceInFastThrow -XX:+ShowCodeDetailsInExceptionMessages -XX:+DisableExplicitGC -XX:-UseParallelGC -XX:-UseParallelOldGC -XX:+PerfDisableSharedMem -XX:+UseZGC -XX:-ZUncommit -XX:ZUncommitDelay=300 -XX:ZCollectionInterval=5 -XX:ZAllocationSpikeTolerance=2.0 -XX:+AlwaysPreTouch -XX:+UseTransparentHugePages -XX:LargePageSizeInBytes=2M -XX:+UseLargePages -XX:+ParallelRefProcEnabled`

## Disclaimers

1. For the heavy G1 Garbage Collector JVM script to work; Java 8 or newer is required, The -Xms and -Xmx parts can be modified to your own personal likings in case the Java RAM is insufficient,

2. For the heavy Z Garbage Collector JVM script to work; Java 14 or newer is required instead.


## Sources used for the scripts:

[Aikar's G1GC tuning blog](https://aikar.co/2018/07/02/tuning-the-jvm-g1gc-garbage-collector-flags-for-minecraft),

[Krusic's ZGC tuning blog](https://krusic22.com/2020/03/25/higher-performance-crafting-using-jdk11-and-zgc),

[FroggeMC's ZGC repository](https://github.com/FroggeMC/MC-Java-Flags).

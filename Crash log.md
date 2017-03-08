# MC
Contains errors and cofigs of Minecraft

---- Minecraft Crash Report ----
// Would you like a cupcake?

Time: 3/8/17 10:05 AM
Description: Unexpected error

java.lang.NullPointerException: Unexpected error
	at galaxyspace.SolarSystem.core.handler.GSClientTickHandler.onClientTick(Unknown Source)
	at cpw.mods.fml.common.eventhandler.ASMEventHandler_124_GSClientTickHandler_onClientTick_ClientTickEvent.invoke(.dynamic)
	at cpw.mods.fml.common.eventhandler.ASMEventHandler.invoke(ASMEventHandler.java:54)
	at cpw.mods.fml.common.eventhandler.EventBus.post(EventBus.java:140)
	at cpw.mods.fml.common.FMLCommonHandler.onPostClientTick(FMLCommonHandler.java:330)
	at net.minecraft.client.Minecraft.func_71407_l(Minecraft.java:2064)
	at net.minecraft.client.Minecraft.func_71411_J(Minecraft.java:973)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:898)
	at net.minecraft.client.main.Main.main(SourceFile:148)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at org.multimc.onesix.OneSixLauncher.launchWithMainClass(OneSixLauncher.java:236)
	at org.multimc.onesix.OneSixLauncher.launch(OneSixLauncher.java:297)
	at org.multimc.EntryPoint.listen(EntryPoint.java:162)
	at org.multimc.EntryPoint.main(EntryPoint.java:53)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Stacktrace:
	at galaxyspace.SolarSystem.core.handler.GSClientTickHandler.onClientTick(Unknown Source)
	at cpw.mods.fml.common.eventhandler.ASMEventHandler_124_GSClientTickHandler_onClientTick_ClientTickEvent.invoke(.dynamic)
	at cpw.mods.fml.common.eventhandler.ASMEventHandler.invoke(ASMEventHandler.java:54)
	at cpw.mods.fml.common.eventhandler.EventBus.post(EventBus.java:140)
	at cpw.mods.fml.common.FMLCommonHandler.onPostClientTick(FMLCommonHandler.java:330)

-- Affected level --
Details:
	Level name: MpServer
	All players: 1 total; [GCEntityClientPlayerMP['oXLanCeXo'/570, l='MpServer', x=780.52, y=111.04, z=-5154.62]]
	Chunk stats: MultiplayerChunkCache: 441, 441
	Level seed: 0
	Level generator: ID 02 - largeBiomes, ver 0. Features enabled: false
	Level generator options: 
	Level spawn location: World: (0,64,0), Chunk: (at 0,4,0 in 0,0; contains blocks 0,0,0 to 15,255,15), Region: (0,0; contains chunks 0,0 to 31,31, blocks 0,0,0 to 511,255,511)
	Level time: 967416 game time, 1070083 day time
	Level dimension: 0
	Level storage version: 0x00000 - Unknown?
	Level weather: Rain time: 0 (now: false), thunder time: 0 (now: false)
	Level game mode: Game mode: survival (ID 0). Hardcore: false. Cheats: false
	Forced entities: 105 total; [EntitySpider['Spinne'/1792, l='MpServer', x=811.09, y=71.00, z=-5136.91], EntityZombie['Zombie'/1542, l='MpServer', x=853.50, y=77.00, z=-5219.50], EntitySpider['Spinne'/1800, l='MpServer', x=787.50, y=12.00, z=-5171.50], GCEntityClientPlayerMP['oXLanCeXo'/570, l='MpServer', x=6531.70, y=68.62, z=-27879.49], EntityBat['Fledermaus'/2332, l='MpServer', x=799.56, y=18.00, z=-5140.25], EntityZombie['Zombie'/1568, l='MpServer', x=733.50, y=17.00, z=-5134.50], EntityBat['Fledermaus'/1824, l='MpServer', x=701.32, y=20.31, z=-5128.57], EntitySkeleton['Skelett'/1569, l='MpServer', x=837.50, y=16.00, z=-5159.50], EntityBat['Fledermaus'/1825, l='MpServer', x=701.38, y=19.67, z=-5126.81], EntityZombie['Zombie'/1570, l='MpServer', x=838.50, y=16.00, z=-5152.50], EntityCreeper['Creeper'/1571, l='MpServer', x=844.50, y=64.00, z=-5082.50], EntityCartChest['entity.MinecartChest.name'/1316, l='MpServer', x=915.50, y=38.50, z=-5285.50], EntityCreeper['Creeper'/1572, l='MpServer', x=847.50, y=64.00, z=-5083.50], EntityCreeper['Creeper'/1574, l='MpServer', x=844.50, y=64.00, z=-5088.50], EntityZombie['Zombie'/1831, l='MpServer', x=707.31, y=40.00, z=-5122.06], EntitySkeleton['Skelett'/1582, l='MpServer', x=832.50, y=68.00, z=-5170.50], EntitySkeleton['Skelett'/1842, l='MpServer', x=809.50, y=69.00, z=-5118.50], EntityCreeper['Creeper'/1843, l='MpServer', x=815.50, y=69.00, z=-5123.50], EntityZombie['Zombie'/1587, l='MpServer', x=734.50, y=56.00, z=-5102.50], EntityZombie['Zombie'/1588, l='MpServer', x=731.50, y=56.00, z=-5102.50], EntityBat['Fledermaus'/1593, l='MpServer', x=752.56, y=11.41, z=-5209.27], EntityBat['Fledermaus'/1594, l='MpServer', x=741.25, y=15.10, z=-5207.63], EntityBat['Fledermaus'/1601, l='MpServer', x=783.56, y=51.05, z=-5139.72], EntityWolf['Wolf'/1102, l='MpServer', x=772.41, y=106.00, z=-5149.47], EntityWolf['Wolf'/1103, l='MpServer', x=771.50, y=107.00, z=-5150.44], EntityWolf['Wolf'/1104, l='MpServer', x=772.31, y=106.00, z=-5150.69], EntitySpider['Spinne'/1616, l='MpServer', x=832.06, y=70.00, z=-5174.28], EntityWolf['Wolf'/1105, l='MpServer', x=777.88, y=110.00, z=-5151.38], EntityPig['Schwein'/1106, l='MpServer', x=748.45, y=62.94, z=-5163.55], EntityPig['Schwein'/1107, l='MpServer', x=766.91, y=94.00, z=-5131.28], EntityPig['Schwein'/1108, l='MpServer', x=737.09, y=81.00, z=-5130.06], EntitySkeleton['Skelett'/1620, l='MpServer', x=730.50, y=74.00, z=-5108.50], EntityPig['Schwein'/1109, l='MpServer', x=741.63, y=80.00, z=-5193.03], EntityPig['Schwein'/1110, l='MpServer', x=750.69, y=85.00, z=-5194.50], EntityPig['Schwein'/1111, l='MpServer', x=795.94, y=102.00, z=-5203.78], EntityCow['Kuh'/1112, l='MpServer', x=736.75, y=75.00, z=-5108.50], EntityPig['Schwein'/1113, l='MpServer', x=706.94, y=73.00, z=-5153.84], EntityPig['Schwein'/1114, l='MpServer', x=781.50, y=103.00, z=-5226.50], EntityPig['Schwein'/1115, l='MpServer', x=780.50, y=102.00, z=-5228.50], EntityPig['Schwein'/1116, l='MpServer', x=773.97, y=72.00, z=-5092.97], EntitySpider['Spinne'/1628, l='MpServer', x=698.28, y=73.00, z=-5207.47], EntityPig['Schwein'/1118, l='MpServer', x=791.16, y=70.00, z=-5094.03], EntitySheep['Schaf'/1119, l='MpServer', x=709.47, y=74.00, z=-5123.31], EntityCartChest['entity.MinecartChest.name'/1120, l='MpServer', x=834.50, y=33.50, z=-5193.50], EntityPig['Schwein'/1121, l='MpServer', x=733.88, y=70.00, z=-5090.28], EntityPig['Schwein'/1122, l='MpServer', x=720.16, y=71.00, z=-5103.94], EntityCow['Kuh'/1123, l='MpServer', x=702.44, y=73.00, z=-5161.28], EntitySpider['Spinne'/2147, l='MpServer', x=820.00, y=70.00, z=-5140.44], EntityPig['Schwein'/1124, l='MpServer', x=706.81, y=72.00, z=-5206.88], EntityChicken['Huhn'/1125, l='MpServer', x=725.56, y=72.00, z=-5218.59], EntityPig['Schwein'/1126, l='MpServer', x=755.88, y=70.00, z=-5081.41], EntitySkeleton['Skelett'/2150, l='MpServer', x=778.50, y=60.00, z=-5154.50], EntityPig['Schwein'/1127, l='MpServer', x=759.28, y=70.00, z=-5085.50], EntityPig['Schwein'/1131, l='MpServer', x=737.13, y=70.00, z=-5085.69], EntityCartChest['entity.MinecartChest.name'/1134, l='MpServer', x=855.50, y=34.50, z=-5185.50], EntityChicken['Huhn'/1135, l='MpServer', x=810.03, y=65.00, z=-5084.22], EntityChicken['Huhn'/1139, l='MpServer', x=705.44, y=75.00, z=-5231.47], EntityChicken['Huhn'/1140, l='MpServer', x=710.28, y=72.00, z=-5224.28], EntitySkeleton['Skelett'/1910, l='MpServer', x=823.50, y=70.00, z=-5171.50], EntityCartChest['entity.MinecartChest.name'/1143, l='MpServer', x=837.50, y=28.50, z=-5220.50], EntitySquid['Tintenfisch'/2424, l='MpServer', x=842.50, y=46.38, z=-5117.50], EntitySkeleton['Skelett'/2173, l='MpServer', x=701.50, y=72.00, z=-5135.50], EntityCreeper['Creeper'/1919, l='MpServer', x=757.50, y=95.00, z=-5151.50], EntitySkeleton['Skelett'/2175, l='MpServer', x=738.50, y=57.00, z=-5096.50], EntitySkeleton['Skelett'/2176, l='MpServer', x=728.50, y=57.00, z=-5098.06], EntityCow['Kuh'/1153, l='MpServer', x=824.22, y=101.00, z=-5236.84], EntitySkeleton['Skelett'/1414, l='MpServer', x=849.50, y=64.00, z=-5085.50], EntityCreeper['Creeper'/1416, l='MpServer', x=844.88, y=64.00, z=-5084.78], EntityCreeper['Creeper'/1417, l='MpServer', x=856.47, y=63.00, z=-5093.00], EntityPig['Schwein'/1162, l='MpServer', x=710.69, y=66.00, z=-5079.03], EntityZombie['Zombie'/2450, l='MpServer', x=799.50, y=72.00, z=-5125.50], GCEntityClientPlayerMP['oXLanCeXo'/570, l='MpServer', x=780.52, y=111.04, z=-5154.62], EntityTrail['Unbekannt'/1940, l='MpServer', x=780.71, y=110.62, z=-5154.71], EntityZombie['Zombie'/2458, l='MpServer', x=829.50, y=19.00, z=-5195.50], EntitySkeleton['Skelett'/2459, l='MpServer', x=831.50, y=19.00, z=-5199.50], EntitySkeleton['Skelett'/2460, l='MpServer', x=830.50, y=19.00, z=-5198.50], EntityZombie['Zombie'/2461, l='MpServer', x=830.50, y=19.00, z=-5197.50], EntityCreeper['Creeper'/1956, l='MpServer', x=830.53, y=9.27, z=-5162.03], EntityCreeper['Creeper'/1957, l='MpServer', x=733.50, y=57.00, z=-5096.50], EntityCartChest['entity.MinecartChest.name'/1190, l='MpServer', x=881.50, y=34.50, z=-5171.50], EntitySkeleton['Skelett'/1959, l='MpServer', x=851.50, y=75.00, z=-5209.50], EntityCartChest['entity.MinecartChest.name'/1193, l='MpServer', x=885.50, y=32.50, z=-5145.50], EntityCartChest['entity.MinecartChest.name'/1209, l='MpServer', x=894.50, y=32.50, z=-5133.50], EntityBat['Fledermaus'/1978, l='MpServer', x=767.32, y=51.82, z=-5118.53], EntityBat['Fledermaus'/1980, l='MpServer', x=759.54, y=50.00, z=-5128.30], EntityBat['Fledermaus'/1984, l='MpServer', x=764.59, y=50.00, z=-5126.05], EntityBasalz['Basalz'/1744, l='MpServer', x=763.00, y=54.00, z=-5151.69], EntityCartChest['entity.MinecartChest.name'/1236, l='MpServer', x=832.50, y=30.50, z=-5267.50], EntityBat['Fledermaus'/1492, l='MpServer', x=714.03, y=46.10, z=-5162.25], EntitySkeleton['Skelett'/2006, l='MpServer', x=837.50, y=17.00, z=-5139.50], EntityCreeper['Creeper'/1750, l='MpServer', x=744.66, y=98.00, z=-5239.06], EntitySkeleton['Skelett'/2007, l='MpServer', x=766.56, y=54.00, z=-5109.16], EntityZombie['Zombie'/2008, l='MpServer', x=771.13, y=53.00, z=-5105.63], EntityCreeper['Creeper'/1759, l='MpServer', x=855.94, y=64.00, z=-5116.41], EntityCreeper['Creeper'/1760, l='MpServer', x=857.50, y=63.00, z=-5107.50], EntityCartChest['entity.MinecartChest.name'/1249, l='MpServer', x=827.50, y=31.50, z=-5286.50], EntityBlizz['Blizz'/1764, l='MpServer', x=725.50, y=48.00, z=-5103.50], EntityBlizz['Blizz'/1765, l='MpServer', x=725.50, y=48.00, z=-5100.50], EntityCreeper['Creeper'/1766, l='MpServer', x=725.50, y=48.00, z=-5105.50], EntityZombie['Zombie'/1769, l='MpServer', x=712.50, y=75.00, z=-5233.50], EntityBat['Fledermaus'/2026, l='MpServer', x=704.53, y=44.79, z=-5156.69], EntitySkeleton['Skelett'/1516, l='MpServer', x=812.50, y=65.00, z=-5093.50], EntitySkeleton['Skelett'/1517, l='MpServer', x=810.50, y=65.00, z=-5091.50], EntitySkeleton['Skelett'/1533, l='MpServer', x=790.50, y=54.00, z=-5199.50], EntitySkeleton['Skelett'/1535, l='MpServer', x=800.75, y=70.00, z=-5117.31]]
	Retry entities: 0 total; []
	Server brand: fml,forge
	Server type: Non-integrated multiplayer server
Stacktrace:
	at net.minecraft.client.multiplayer.WorldClient.func_72914_a(WorldClient.java:425)
	at net.minecraft.client.Minecraft.func_71396_d(Minecraft.java:2444)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:927)
	at net.minecraft.client.main.Main.main(SourceFile:148)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at org.multimc.onesix.OneSixLauncher.launchWithMainClass(OneSixLauncher.java:236)
	at org.multimc.onesix.OneSixLauncher.launch(OneSixLauncher.java:297)
	at org.multimc.EntryPoint.listen(EntryPoint.java:162)
	at org.multimc.EntryPoint.main(EntryPoint.java:53)

-- System Details --
Details:
	Minecraft Version: 1.7.10
	Operating System: Windows 7 (amd64) version 6.1
	Java Version: 1.8.0_121, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 641001840 bytes (611 MB) / 2045247488 bytes (1950 MB) up to 2863661056 bytes (2731 MB)
	Mod Pack: Unknown / None
	LiteLoader Mods: 1 loaded mod(s)
          - VoxelMap version 1.6.17
	LaunchWrapper: 38 active transformer(s)
          - Transformer: cpw.mods.fml.common.asm.transformers.PatchingTransformer
          - Transformer: optifine.OptiFineClassTransformer
          - Transformer: cpw.mods.fml.common.asm.transformers.MarkerTransformer
          - Transformer: cpw.mods.fml.common.asm.transformers.SideTransformer
          - Transformer: cpw.mods.fml.common.asm.transformers.EventSubscriptionTransformer
          - Transformer: net.minecraftforge.classloading.FluidIdTransformer
          - Transformer: com.arisux.mdxlib.AccessTransformer
          - Transformer: codechicken.lib.asm.ClassHeirachyManager
          - Transformer: codechicken.core.asm.InterfaceDependancyTransformer
          - Transformer: codechicken.core.asm.TweakTransformer
          - Transformer: codechicken.core.asm.DelegatedTransformer
          - Transformer: codechicken.core.asm.DefaultImplementationTransformer
          - Transformer: micdoodle8.mods.miccore.MicdoodleTransformer
          - Transformer: codechicken.nei.asm.NEITransformer
          - Transformer: com.mumfrey.liteloader.launch.LiteLoaderTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.CrashReportTransformer
          - Transformer: cpw.mods.fml.common.asm.transformers.DeobfuscationTransformer
          - Transformer: cpw.mods.fml.common.asm.transformers.AccessTransformer
          - Transformer: net.minecraftforge.transformers.ForgeAccessTransformer
          - Transformer: com.arisux.mdxlib.AccessTransformer
          - Transformer: codechicken.core.asm.CodeChickenAccessTransformer
          - Transformer: cofh.asm.CoFHAccessTransformer
          - Transformer: micdoodle8.mods.miccore.MicdoodleAccessTransformer
          - Transformer: cpw.mods.fml.common.asm.transformers.ModAccessTransformer
          - Transformer: cpw.mods.fml.common.asm.transformers.ItemStackTransformer
          - Transformer: cofh.asm.CoFHClassTransformer
          - Transformer: cpw.mods.fml.common.asm.transformers.TerminalTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.JoinGamePacketTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.ServerChatPacketTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.LiteLoaderEventInjectionTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.LiteLoaderCallbackInjectionTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.MinecraftOverlayTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.LoginSuccessPacketTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.CustomPayloadPacketTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.ServerCustomPayloadPacketTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.ChatPacketTransformer
          - Transformer: com.thevoxelbox.voxelmap.litemod.VoxelMapTransformer
          - Transformer: cpw.mods.fml.common.asm.transformers.ModAPITransformer
	JVM Flags: 3 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xms256m -Xmx3072m
	AABB Pool Size: 0 (0 bytes; 0 MB) allocated, 0 (0 bytes; 0 MB) used
	IntCache: cache: 0, tcache: 0, allocated: 15, tallocated: 103
	FML: MCP v9.05 FML v7.10.99.99 Minecraft Forge 10.13.4.1614 Optifine OptiFine_1.7.10_HD_U_D6 62 mods loaded, 52 mods active
	States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored
	UCHIJA	mcp{9.05} [Minecraft Coder Pack] (minecraft.jar) 
	UCHIJA	FML{7.10.99.99} [Forge Mod Loader] (forge-1.7.10-10.13.4.1614-1.7.10-universal.jar) 
	UCHIJA	Forge{10.13.4.1614} [Minecraft Forge] (forge-1.7.10-10.13.4.1614-1.7.10-universal.jar) 
	UCHIJA	CodeChickenCore{1.0.7.47} [CodeChicken Core] (minecraft.jar) 
	UCHIJA	Micdoodlecore{} [Micdoodle8 Core] (minecraft.jar) 
	UCHIJA	NotEnoughItems{1.0.5.120} [Not Enough Items] (NotEnoughItems-1.7.10-1.0.5.120-universal.jar) 
	UCHIJA	<CoFH ASM>{000} [CoFH ASM] (minecraft.jar) 
	UCHIJA	mdxlib{1.0.0.68} [mdxlib] ([1.7.10-10.13.4.1614-1.7.10][1.0.0.68] mdxlib.jar) 
	UCHIJA	CoFHCore{1.7.10R3.1.4} [CoFH Core] (CoFHCore-[1.7.10]3.1.4-329.jar) 
	UCHIJA	avp{4.0.0.809} [AliensVsPredator] ([1.7.10-10.13.4.1614-1.7.10][4.0.0.809] aliensvspredator.jar) 
	UCHIJA	bspkrsCore{6.15} [bspkrsCore] ([1.7.10]bspkrsCore-universal-6.15.jar) 
	UCHIJA	Treecapitator{1.7.10} [Treecapitator] ([1.7.10]Treecapitator-universal-2.0.4.jar) 
	UCHIJA	IC2{2.2.827-experimental} [IndustrialCraft 2] (industrialcraft-2-2.2.827-experimental.jar) 
	UCHIJA	AdvancedSolarPanel{1.7.10-3.5.1} [Advanced Solar Panels] (Advanced-Solar-Panels-Addon-1.7.10.jar) 
	UCHIJA	ArchimedesShips{1.7.10 v1.7.1} [Archimedes' Ships] (ArchimedesShips-1.7.1.jar) 
	UCHIJA	Backpack{2.0.1} [Backpack] (backpack-2.0.1-1.7.x.jar) 
	UCHIJA	BiblioCraft{1.11.5} [BiblioCraft] (BiblioCraft-Mod-1.7.10.jar) 
	UCHIJA	BuildCraft|Core{7.1.20} [BuildCraft] (buildcraft-7.1.20.jar) 
	UCHIJA	BuildCraft|Robotics{7.1.20} [BC Robotics] (buildcraft-7.1.20.jar) 
	UCHIJA	BuildCraft|Factory{7.1.20} [BC Factory] (buildcraft-7.1.20.jar) 
	UCHIJA	BuildCraft|Transport{7.1.20} [BC Transport] (buildcraft-7.1.20.jar) 
	UCHIJA	BuildCraft|Energy{7.1.20} [BC Energy] (buildcraft-7.1.20.jar) 
	UCHIJA	BuildCraft|Silicon{7.1.20} [BC Silicon] (buildcraft-7.1.20.jar) 
	UCHIJA	BuildCraft|Builders{7.1.20} [BC Builders] (buildcraft-7.1.20.jar) 
	UCHIJA	ThermalFoundation{1.7.10R1.2.6} [Thermal Foundation] (ThermalFoundation-[1.7.10]1.2.6-118.jar) 
	UCHIJA	ThermalExpansion{1.7.10R4.1.5} [Thermal Expansion] (ThermalExpansion-[1.7.10]4.1.5-248.jar) 
	UCHIJA	BuildCraft|Compat{7.1.6} [BuildCraft Compat] (buildcraft-compat-7.1.6.jar) 
	UCHIJA	PTRModelLib{1.0.0} [PTRModelLib] (Decocraft-2.3.3_1.7.10.jar) 
	UCHIJA	props{2.3.3} [Decocraft] (Decocraft-2.3.3_1.7.10.jar) 
	UCHIJA	SlimevoidLib{2.0.4.7} [Slimevoid Library] (SlimevoidLibrary-2.0.4.7.jar) 
	UCHIJA	DynamicTransport{0.1.2.0} [Dynamic Transport] (DynamicTransport-0.1.2.0.jar) 
	UCHIJA	GalacticraftCore{3.0.12} [Galacticraft Core] (GalacticraftCore-1.7-3.0.12.474.jar) 
	UCHIJA	GalacticraftMars{3.0.12} [Galacticraft Planets] (Galacticraft-Planets-1.7-3.0.12.474.jar) 
	UCHIJA	GalaxySpace{1.1.4} [GalaxySpace] (GalaxySpace-1.1.4 STABLE.jar) 
	UCHIJA	GollumCoreLib{2.0.0} [Gollum Core Lib] (Gollum-Core-Lib-1.7.10.jar) 
	UCHIJA	iChunUtil{4.2.2} [iChunUtil] (iChunUtil-4.2.2.jar) 
	UCHIJA	JammyFurniture{5.0.0 [Build Smeagol]} [Jammy Furniture Mod] (Jammy-Furniture-Reborn-Mod-1.7.10.jar) 
	UCHIJA	millenaire{6.0.0} [Millénaire] (millenaire-6.0.0.jar) 
	UCHIJA	MineFactoryReloaded{1.7.10R2.8.1} [MineFactory Reloaded] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJA	MineFactoryReloaded|CompatBuildCraft{1.7.10R2.8.1} [MFR Compat: BuildCraft] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJA	MineFactoryReloaded|CompatForgeMicroblock{1.7.10R2.8.1} [MFR Compat: ForgeMicroblock] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJA	MineFactoryReloaded|CompatIC2{1.7.10R2.8.1} [MFR Compat: IC2] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJA	Railcraft{9.12.2.0} [Railcraft] (Railcraft_1.7.10-9.12.2.0.jar) 
	UCHIJA	MineFactoryReloaded|CompatRailcraft{1.7.10R2.8.1} [MFR Compat: Railcraft] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJA	MineFactoryReloaded|CompatThermalExpansion{1.7.10R2.8.1} [MFR Compat: Thermal Expansion] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJA	TwilightForest{2.3.7} [The Twilight Forest] (twilightforest-1.7.10-2.3.7.jar) 
	UCHIJA	MineFactoryReloaded|CompatTwilightForest{1.7.10R2.8.1} [MFR Compat: TwilightForest] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJA	MineFactoryReloaded|CompatVanilla{1.7.10R2.8.1} [MFR Compat: Vanilla] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJA	NetherOres{1.7.10R2.3.1} [Nether Ores] (NetherOres-[1.7.10]2.3.1-22.jar) 
	UCHIJA	PortalGun{4.0.0-beta-6} [PortalGun] (PortalGun-4.0.0-beta-6.jar) 
	UCHIJA	ThermalDynamics{1.7.10R1.2.1} [Thermal Dynamics] (ThermalDynamics-[1.7.10]1.2.1-172.jar) 
	UCHIJA	tc{4.3.1_007} [Traincraft] (Traincraft-4.3.1_007.jar) 
	UD	MineFactoryReloaded|CompatAppliedEnergistics{1.7.10R2.8.1} [MFR Compat: Applied Energistics] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatAtum{1.7.10R2.8.1} [MFR Compat: Atum] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatBackTools{1.7.10R2.8.1} [MFR Compat: BackTools] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatChococraft{1.7.10R2.8.1} [MFR Compat: Chococraft] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatExtraBiomes{1.7.10R2.8.1} [MFR Compat: ExtraBiomes] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatForestry{1.7.10R2.8.1} [MFR Compat: Forestry] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatProjRed{1.7.10R2.8.1} [MFR Compat ProjectRed] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatSufficientBiomes{1.7.10R2.8.1} [MFR Compat: Sufficient Biomes] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatThaumcraft{1.7.10R2.8.1} [MFR Compat: Thaumcraft] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatTConstruct{1.7.10R2.8.1} [MFR Compat: Tinkers' Construct] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	CoFHCore: -[1.7.10]3.1.4-329
	ThermalFoundation: -[1.7.10]1.2.6-118
	ThermalExpansion: -[1.7.10]4.1.5-248
	MineFactoryReloaded: -[1.7.10]2.8.1-174
	NetherOres: -[1.7.10]2.3.1-22
	ThermalDynamics: -[1.7.10]1.2.1-172
	Launched Version: MultiMC5
	LWJGL: 2.9.1
	OpenGL: GeForce GTX 560 Ti/PCIe/SSE2 GL version 4.5.0 NVIDIA 378.66, NVIDIA Corporation
	GL Caps: Using GL 1.3 multitexturing.
Using framebuffer objects because OpenGL 3.0 is supported and separate blending is supported.
Anisotropic filtering is supported and maximum anisotropy is 16.
Shaders are available because OpenGL 2.1 is supported.

	Is Modded: Definitely; Client brand changed to 'fml,forge'
	Type: Client (map_client.txt)
	Resource Packs: []
	Current Language: Deutsch (Deutschland)
	Profiler Position: N/A (disabled)
	Vec3 Pool Size: 0 (0 bytes; 0 MB) allocated, 0 (0 bytes; 0 MB) used
	Anisotropic Filtering: Off (1)
	OptiFine Version: OptiFine_1.7.10_HD_U_D6
	Render Distance Chunks: 16
	Mipmaps: 0
	Anisotropic Filtering: 1
	Antialiasing: 0
	Multitexture: false
	OpenGlVersion: 4.5.0 NVIDIA 378.66
	OpenGlRenderer: GeForce GTX 560 Ti/PCIe/SSE2
	OpenGlVendor: NVIDIA Corporation
	CpuCount: 2

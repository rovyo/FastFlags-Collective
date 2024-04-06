<h1 align="center"><img src="https://github.com/pizzaboxer/bloxstrap/raw/main/Images/Bloxstrap.png" width="28"/> FastFlags Collective</h1>

<h3 align="center">https://discord.gg/YreqZ7aYmg</h3>

<h6 align="center">https://dsc.gg/fastflags</h6>

<h5 align="center">Merely because this list highlights abusable fast flags doesn't imply we're promoting using them to unfairly impact others' gameplay. Remember, exploiting in Roblox goes against their ToU, and we don't support such activities. For more information, see Roblox's <a href="https://en.help.roblox.com/hc/en-us/articles/203312450-Cheating-and-Exploiting">Cheating and Exploiting</a> policy and <a href="https://en.help.roblox.com/hc/en-us/articles/115004647846-Roblox-Terms-of-Use">Terms of Use</h5>

##### Version: 8.6.2 [4/5/2024]
* **120 Currently Listed**

## How to Use:
1. **Open the [Bloxstrap Menu](https://github.com/pizzaboxer/bloxstrap).**
2. **Navigate to `Fast Flags` >> `Fast Flags Editor` >> `Import Json`.**
3. **Paste in the JSON.**
4. **Save and you're good to go!**
<img src="/assets/tutorial.gif" width="750"/>

 # List Navigation
* **[Rendering](https://github.com/FastFlags/FastFlags-Collective/?tab=readme-ov-file#rendering)**
* **[Graphical](https://github.com/FastFlags/FastFlags-Collective/?tab=readme-ov-file#graphical-settings)**
* **[UI](https://github.com/FastFlags/FastFlags-Collective/?tab=readme-ov-file#user-interface)**
* **[Textures](https://github.com/FastFlags/FastFlags-Collective/tree/textures)**
* **[Physics](https://github.com/FastFlags/FastFlags-Collective/?tab=readme-ov-file#physics)**
* **[Other Flogs](https://github.com/FastFlags/FastFlags-Collective/?tab=readme-ov-file#other-fflags)**
* **[Links](https://github.com/FastFlags/FastFlags-Collective/?tab=readme-ov-file#links)**
* **[FastFlag Community Servers](https://github.com/fastflags/fastflags-collective/?tab=readme-ov-file#fastflag-community-discord-servers)**

<img src="assets/images/bitdancer.png" width="888"/>

### 

<h3 align="center">══════⊹⊱≼≽⊰⊹══════</h3>

<h1 align="center">Lightning Technologies</h1>

### Voxel Lighting
```json
{
	"DFlogDebugRenderForceTechnologyVoxel": "True"
}
```
### Shadowmap Lighting
```json
{
	"FlogDebugForceFutureIsBrightPhase2": "True"
}
```
### Future Lighting
```json
{
	"FlogDebugForceFutureIsBrightPhase3": "True"
}
```

<h1 align="center">Rendering API</h1>

### Metal
###### MacOS Only
```json
{
	"FlogDebugGraphicsPreferMetal": "True"
}
```
### Vulkan
```json
{
	"FlogDebugGraphicsDisableDirect3D11": "True",
	"FlogDebugGraphicsPreferVulkan": "True"
}
```
### OpenGL
```json
{
	"FlogDebugGraphicsDisableDirect3D11": "True",
	"FlogDebugGraphicsPreferOpenGL": "True"
}
```
### Direct X 10
```json
{
	"FlogDebugGraphicsPreferD3D11FL10": "True"
}
```
### Direct X 11
```json
{
	"FlogDebugGraphicsPreferD3D11": "True"
}
```

<h1 align="center">Graphical Settings <sup>& other stuff</sup></h1>

### Draws a circle under avatars
```json
{
	"FlogDebugAvatarChatVisualization": "True",
	"FlogEnableInGameMenuChromeABTest2": "False"
}
```
### HyperThreading
```json
{
	"FlogDebugCheckRenderThreading": "True",
	"FlogRenderDebugCheckThreading2": "True"
}
```
### Maximum threads
```json
{
	"FlogRuntimeMaxNumOfThreads": "2400"
}
```
### Minimum Threads
```json
{
	"FlogTaskSchedulerThreadMin": "3"
}
```
### Smoother Terrain
```json
{
	"FlogDebugRenderingSetDeterministic": "True"
}
```
### Graphics Quality Level
```json
{
	"FlogRomarkStartWithGraphicQualityLevel": "1"
}
```
### Low Quallity Terrain Textures
###### 4 for less quality 16, 32, 64 for higher quality
```json
{
	"FlogTerrainArraySliceSize": "4"
}
```
### Disable Shadows
```json
{
	"FlogRenderShadowIntensity": "0"
}
```
### Preserve rendering quality with display setting
```json
{
	"DFlogDisableDPIScale": "True"
}
```
### Low Graphics Quality w/ Max Render Distance/FRM Quality Levels
###### Explanation: 1-6 Are low graphics, Above 6 are high graphics. Like the 1-21 graphics slider
```json
{
	"DFlogDebugFRMQualityLevelOverride": "1"
}
```

<h4 align="center">FRM Levels</h4>

```
Low

1 = 3
2 = 2
3 = 6

High

4 = 7
5 = 11
6 = 14
7 = 15 
8 = 17
9 = 18
10 = 21
```

### Low Render Distance
###### [FRM](https://github.com/FastFlags/FastFlags-Collective/?tab=readme-ov-file#frm-levels)
```json
{
	"DFlogDebugRestrictGCDistance": "1"
}
```
### Disable Wind
```json
{
	"FlogGlobalWindRendering": "False",
	"FlogGlobalWindActivated": "False"
}
```
### Limits light updates
```json
{
	"FlogRenderLocalLightUpdatesMax": "8",
	"FlogRenderLocalLightUpdatesMin": "6"
}
```
### Disables fade in and fade out animation every light update
```json
{
	"FlogRenderLocalLightFadeInMs": "0"
}
```
### Makes avatars shiny 
###### [everything goes black on <3] ***[DFlogDebugFRMQualityLevelOverride is there to set your graphics to 10, You can change it to anything above 3: [Click here to view](https://github.com/FastFlags/FastFlags-Collective/?tab=readme-ov-file#frm-levels) ]***
```json
{
	"DFlogRenderClampRoughnessMax": "-640000000",
	"DFlogDebugFRMQualityLevelOverride": "6"
}
```
### Disable PostFX
```json
{
	"FlogDisablePostFx": "True"
}
```
### Pause Voxelizer/Disable Baked Shadows
```json
{
	"DFlogDebugPauseVoxelizer": "True"
}
```
### Gray Sky
###### Only applies to games with the default skybox
```json
{
	"FlogDebugSkyGray": "True"
}
```
### Disable Player Shadows
```json
{
	"FlogRenderShadowIntensity": "0"
}
```
### Force LOD on Meshes
```json
{
	"DFlogCSGLevelOfDetailSwitchingDistance": "0",
	"DFlogCSGLevelOfDetailSwitchingDistanceL12": "0",
	"DFlogCSGLevelOfDetailSwitchingDistanceL23": "0",
	"DFlogCSGLevelOfDetailSwitchingDistanceL34": "0"
}
```
### Lighting Attenuation
```json
{
	"FlogNewLightAttenuation": "True"
}
```
### Enable GPULightCulling
###### Combine with [Lighting Attenuation](https://FastFlags/FastFlags-Collective/?tab=readme-ov-file#lighting-attenuation) for better vision
```json
{
	"FlogFastGPULightCulling3": "True"
}
```
### Frame Buffer
###### Explnation: 0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag
```json
{
	"DFlogMaxFrameBufferSize": "4"
}
```
### High Quality Textures 
###### *[1-3]*
```json
{
	"DFlogTextureQualityOverrideEnabled": "True",
	"DFlogTextureQualityOverride": "3"
}
```
### Lower Quality Textures 
###### *[1-3]*
```json
{
	"DFlogPerformanceControlTextureQualityBestUtility": "-1"
}
```
### No avatar textures
```json
{
	"DFlogTextureCompositorActiveJobs": "0"
}
```
### Remove Grass
```json
{
	"FlogFRMMinGrassDistance": "0",
	"FlogFRMMaxGrassDistance": "0",
	"FlogRenderGrassDetailStrands": "0",
	"FlogRenderGrassHeightScaler": "0"
}
```
### Force MSAA 
###### *[0, 1, 2, 4, 8]*
```json
{
	"FlogDebugForceMSAASamples": "4"
}
```
### ShadowMap Bias 
###### ***[Future & ShadowMap]***
```json
{
	"FlogRenderShadowmapBias": "75"
}
```
### Enables Network Debug Tracker menu
##### Instructions: CTRL+F8
```json
{
	"DFlogDebugEnableInterpolationVisualizer": "True"
}
```
### Humanoid Outline
##### Draws an outline around every part and every humanoid
```json
{
	"DFlogDebugDrawBroadPhaseAABBs": "True"
}
```
### Buggy ZPlane Camera *<sup>a.k.a xray</sup>*
```json
{
	"FlogCameraFarZPlane": "1"
}
```
<h1 align="center">User Interface</h1>

### FPS Unlocker in Roblox Menu Settings
```json
{
	"FlogGameBasicSettingsFramerateCap": "True",
	"DFlogTaskSchedulerTargetFps": "0"
}
```
### GUI Hiding Toggles
```json
{
	"FlogUserShowGuiHideToggles": "True",
	"GuiHidingApiSupport2": "True"
}
```
### Darker Dark Theme
```json
{
	"FlogLuaAppUseUIBloxColorPalettes1": "True",
	"FlogUIBloxUseNewThemeColorPalettes": "True"
}
```
### Subscriptions Page
```json
{
	"FlogLuaAppDevSubsEnabled": "True"
}
```
### No Transparency V4 Menu **(2023)**
```json
{
	"FStringInGameMenuModernizationStickyBarForcedUserIds": "UserID"
}
```
### Revert Old Report Menu
```json
{
	"FStringReportAbuseMenuRoactForcedUserIds": "null",
	"FlogEnableReportAbuseMenuRoactABTest2": "False",
	"FlogEnableReportAbuseMenuRoact2": "False",
	"FlogEnableReportAbuseMenuLayerOnV3": "False"
}
```
### Custom MicroProfile Scale
```json
{ "DFlogMicroProfilerDpiScaleOverride":  "100" }
```
### Hides gui
```json
{ "FlogDebugAdornsDisabled":  "True" }
```
### Dont Render UI
```json
{
	"FlogDebugDontRenderUI": "True"
}
```
### Enable Audio Controller
```json
{
	"FlogTrackerLodControllerDebugUI": "True"
}
```
### Disable Autocomplete
```json
{
	"FlogEnableCommandAutocomplete": "False"
}
```
### Chrome UI TopBar
```json
{
	"FlogEnableInGameMenuChrome": "True",
	"FlogEnableReportAbuseMenuRoactABTest2": "True",
	"FlogChromeBetaFeature": "True",
	"FlogEnableInGameMenuChromeABTest2": "True"
}
```
### Pin Chat on Chrome UI
```json
{ "FlogEnableChromePinnedChat":  "True" }
```
### Chrome UI Topbar Removal
```json
{
	"FlogEnableInGameMenuChromeABTest2": "False",
	"FlogEnableReportAbuseMenuRoactABTest2": "False"
}
```
### Disable Bubble Chat
```json
{ "FlogEnableBubbleChatFromChatService":  "False" }
```
### Disable Selfview
```json
{ "FlogCoreGuiTypeSelfViewPresent":  "False" }
```
### Remove VC Beta Badge
```json
{
	"FlogVoiceBetaBadge": "False",
	"FlogTopBarUseNewBadge": "False",
	"FlogEnableBetaBadgeLearnMore": "False",
	"FlogBetaBadgeLearnMoreLinkFormview": "False",
	"FlogControlBetaBadgeWithGuac": "False",
	"FStringVoiceBetaBadgeLearnMoreLink": "null"
}
```
### Hide guis
###### ***Instructions: Replace "ID" with any group ID that you are in.***
| Key combination   | Action                                                                    |
| ----------------- | ------------------------------------------------------------------------- |
| Ctrl + Shift + B  | Toggles GUIs in 3D space (BillboardGuis, SurfaceGuis, etc)                |
| Ctrl + Shift + C  | Toggles game-defined ScreenGuis                                           |
| Ctrl + Shift + G  | Toggles Roblox CoreGuis                                                   |
| Ctrl + Shift + N  | Toggles player names, and other BillboardGuis that show up above a player |
```json
{
	"DFlogCanHideGuiGroupId": "ID"
}
```
### Disable Fullscreen Title Bar
```json
{
	"FlogFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```
### Set Custom Font Size
```json
{
	"FlogFontSizePadding": "1"
}
```

<h1 align="center">Textures</h1>

### Fix Textures
```json
{
	"FlogMSRefactor5": "False"
}
```
### No Textures
```json
{
	"FStringPartTexturePackTable2022": "{\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]}}",
	"FStringPartTexturePackTablePre2022": "{\"glass\":{\"ids\":[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\"color\":[254,254,254,7]}}",
	"FStringTerrainMaterialTable2022": "",
	"FStringTerrainMaterialTablePre2022": "",
	"FlogMSRefactor5": "False"
}
```
<h1 align="center">Physics</h1>


### arsenal fly glitch

![image](https://github.com/FastFlags/FastFlags-Collective/assets/159259392/ee3bfafa-5c6f-4cf5-92ed-bf6bbc597e77)

### real hitbox for real
```json
{
	"FlogHumanoidParallelFixTickleFloor2_PlaceFilter": "True;2573981315;6317172524;4999654929;189707",
	"FlogFixMemoryPriorizationCrash": "True",
	"FlogUGCValidationTorsoThresholdFront": "100",
	"FlogUGCValidationTorsoThresholdSide": "100",
	"FlogUGCValidationTorsoThresholdBack": "100",
	"FlogUGCValidationLeftArmThresholdBack": "23",
	"FlogUGCValidationLeftArmThresholdFront": "25",
	"FlogUGCValidationLeftArmThresholdSide": "40",
	"FlogUGCValidationLeftLegThresholdBack": "40",
	"FlogUGCValidationLeftLegThresholdFront": "40",
	"FlogUGCValidationLeftLegThresholdSide": "36",
	"FlogUGCValidationRightArmThresholdBack": "23",
	"FlogUGCValidationRightArmThresholdFront": "25",
	"FlogUGCValidationRightArmThresholdSide": "40",
	"FlogUGCValidationRightLegThresholdBack": "40",
	"FlogUGCValidationRightLegThresholdFront": "40",
	"FlogUGCValidationRightLegThresholdSide": "38"
}
```

### Remap R6 to R15 Rigs
```json
{
	"FlogRemapAnimationR6ToR15Rig": "True"
}
```
### Disables PGS Solver
###### Projected Gauss-Seidel physics, or PGS physics, is a more reliable but more costly physics solver released in summer of 2015. The solver has a lot less "give" than spring physics, in terms of parts won't want to go into each other at all, making joints less flexible. This allows for parts to have less of a tendency to go through each other. As of October 21, 2015, the joints called glue joints are supported in the system, and will not break under pressure. The solver takes more processing power to work over spring physics, which will cause games to act slower. This solver runs at 240 Hz.
```json
{
	"FlogSimDefaultPGSSolver": "False"
}
```
### Adjust Hip Height Clamps
###### https://www.roblox.com/bundles/63/Mage-Animation-Package
```json
{
	"DFlogHipHeightClamp": "-48"
}
```
### Random High Jumps
###### https://youtu.be/2JkA4hWCAWw
```json
{
	"FlogSimAdaptiveTimesteppingDefault2": "True",
	"DFlogSimHumanoidTimestepModelUpdate": "True"
}
```
### Drunk
```json
{
	"FlogSimAdaptiveTimesteppingDefault2": "True",
	"DFlogSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
	"DFlogSimHumanoidTimestepModelUpdate": "True"
}
```
### No Animations
```json
{
	"DFlogReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```
### Stick unanchored parts to you
##### - = up, + = down
```json
{
	"DFlogSolidFloorPercentForceApplication": "-1000",
	"DFlogNonSolidFloorPercentForceApplication": "-5000"
}
```
### Max Raycast Distance
###### Raycasting is the use of intersection tests to solve problems in ROBLOX. The most common use of raycasting is to determine the first object intersected by a ray. This is done by casting a virtual ray from a certain point in a direction and determining the first surface it intersected with.
###### Break legs collision from 2 to -inf, kinda break camera on values over 3 noclip cam on 3
```json
{
	"DFlogRaycastMaxDistance": "3"
}
```
### Possible Super Jump
```json
{
	"DFlogNewRunningBaseGravityReductionFactorHundredth": "1500"
}
```
<!--
### Change DataSender Rate
###### a.k.a dos not let you load games
```json
{
	"DFlogDataSenderRate": "-1"
}
```
 -->
### Disable Touch Events
```json
{
	"DFlogTouchSenderMaxBandwidthBps": "-1"
}
```
### Fake Lag <sup>DeSync</sup>
```json
{
	"DFlogS2PhysicsSenderRate": "1"
}
```
### Invisible 1
```json
{
	"DFlogS2PhysicsSenderRate": "30"
}
```
### Invisible 2
###### Sets your position to 0,0,0 for the server
```json
{
	"DFlogGameNetPVHeaderTranslationZeroCutoffExponent": "10"
}
```
### Invisible 3
```json
{
	"DFlogPhysicsSenderMaxBandwidthBps": "1",
	"DFlogPhysicsSenderMaxBandwidthBpsScaling": "0"
}
```
### Warp & Slowmotion <sup>Physics FPS cap</sup>
```json
{
	"DFlogMaxMissedWorldStepsRemembered": "1"
}
```
```json
{
	"DFlogMaxMissedWorldStepsRemembered": "1000"
}
```
### Noclip
###### adjust the value so u dont fall through the ground
```json
{
	"DFlogAssemblyExtentsExpansionStudHundredth": "-50"
}
```
### Hip Height
###### Very controllable bounce, only works with negative values, 0 allows you to hover
```json
{
	"DFlogMaxAltitudePDStickHipHeightPercent": "-200"
}
```
### Wallglide
```json
{
	"DFlogUnstickForceAttackInTenths": "-4"
}
```

<h1 align="center">other fflags</h1>

### Disable In-game Advertisements
```json
{
	"FlogAdServiceEnabled": "False"
}
```
### Disable Telemetry 
```json
{
	"FlogDebugDisableTelemetryEphemeralCounter": "True",
	"FlogDebugDisableTelemetryEphemeralStat": "True",
	"FlogDebugDisableTelemetryEventIngest": "True",
	"FlogDebugDisableTelemetryPoint": "True",
	"FlogDebugDisableTelemetryV2Counter": "True",
	"FlogDebugDisableTelemetryV2Event": "True",
	"FlogDebugDisableTelemetryV2Stat": "True"
}
```
### Adjust Scroll Speed
```json
{ "FlogScrollWheelDeltaAmount": "140" }
```
### Surf the web inside of Roblox
###### Click the Beta badge or the 13+ badge to open the webview browser.
```json
{
	"FlogTopBarUseNewBadge": "True",
	"FStringTopBarBadgeLearnMoreLink": "https://google.com/",
	"FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/"
}
```
### Sounds use physical velocity and become distorted
###### <2017
```json
{
	"FlogSoundsUsePhysicalVelocity": "True"
}
```
### Shows the state of a flag
```json
{
	"FStringDebugShowFlagState": "FLAG_HERE"
}
```
###### e.g
```json
{
	"FStringDebugShowFlagState": "DFlogTaskSchedulerTargetFps, ChannelName"
}
```
### MTU 
```json
{
	"DFlogConnectionMTUSize": "MTU_HERE"
}
```
### No Internet Disconnect 
###### *[You will still be kicked but the message wont show.]*
```json
{
	"DFlogDebugDisableTimeoutDisconnect": "True"
}
```
### Quick Game Launch 
###### *[BUGGY]*
```json
{
	"FlogEnableQuickGameLaunch": "True"
}
```
### Allows you to change voice chat distance 
###### default: [Min 7 Max 80]
```json
{
	"DFlogVoiceChatRollOffMinDistance": "7",
	"DFlogVoiceChatRollOffMaxDistance": "80"
}
```
### Disable In-Game Purchases
```json
{
	"DFlogOrder66": "True"
}
```
### Disable Chat
```json
{
	"FlogDebugForceChatDisabled": "True"
}
```
### Limit audios that are being played
```json
{
	"DFlogMaxLoadableAudioChannelCount": "1"
}
```
### Adds an UI in game, which highlights any part player touches (like ground, Meshes etc.). It's a non-functioning UI too. Also adds a blue circle to your humanoid.
```json
{
	"FlogDebugHumanoidRendering": "True"
}
```
### Custom Disconnect Message
```json
{
	"FlogReconnectDisabled": "True",
	"FStringReconnectDisabledReason": "You're stupid and I hate you"
}
```
### Display FPS
```json
{
	"FlogDebugDisplayFPS": "True"
}
```
### Verified Badge
###### Clientsided
```json
{
	"FStringWhitelistVerifiedUserId": "UserID"
}
```
### Verified Badge on everyone
###### Clientsided
```json
{
	"FlogOverridePlayerVerifiedBadge": "True"
}
```
### Applies cool colors to stuff
```json
{
	"FlogDebugDisplayUnthemedInstances": "True"
}
```
### Show Outlined Chunks
```json
{
	"FlogDebugLightGridShowChunks": "True"
}
```
### Remove Disconnect Blur/Loading Blur
```json
{
	"FlogRobloxGuiBlurIntensity": "0"
}
```
### Disable Dynamic Heads Animations
###### https://roblox.fandom.com/wiki/Dynamic_Head
```json
{
	"DFlogAnimationLodFacsDistanceMin": "0",
	"DFlogAnimationLodFacsDistanceMax": "0",
	"DFlogAnimationLodFacsVisibilityDenominator": "0"
}
```
### failsafehumanoid
###### gray avatars
```json
{
	"FlogFailsafeHumanoid_3": "True"
}
```
### Automatically unmutes your mic on join (VC)
```json
{
	"FlogDebugDefaultChannelStartMuted": "False"
}
```
### Overlay that shows what you type 
```json
{
	"FlogDebugTextBoxServiceShowOverlay": "True"
}
```
### opt-out Experience Language
###### Removes the Experience Language option in settings
```json
{
	"FlogV1MenuLanguageSelectionFeaturePerMillageRollout": "0"
}
```
### Disable New Chat Translation Settings
```json
{
	"FlogChatTranslationSettingEnabled3 ": "False"
}
```
### Lets you change the zoom out limit
###### Only applies to games that has not changed the default zoom limit
```json
{
	"FlogCameraMaxZoomDistance": "9999"
}
```
### Limits number of animations being played
```json
{
	"DFlogMaxActiveAnimationTracks": "0"
}
```
### Prevents Remote Events from running
```json
{
	"DFlogRemoteEventSingleInvocationSizeLimit": "1"
}
```
### Mess with voice chat volume
###### default 1000
```json
{
	"DFlogVoiceChatVolumeThousandths": "100000"
}
```
### Removes the head roll limit for face tracking
```json
{
	"DFlogAvatarFaceChatHeadRollLimitDegrees": "360"
}
```
### VR Controller transparency
```json
{
	"FlogVRTouchControllerTransparency": "0"
}
```
### No sounds
```json
{
	"FlogDebugRomarkMockingAudioDevices": "True"
}
```
### local rcc
[?](https://github.com/rsblox/local_rcc)
```json
{
	"FlogDebugLocalRccServerConnection": "True",
	"FlogRefactorPlayerConnect": "False"
}
```
### Exclusive Fullscreen
```json
{
	"FlogHandleAltEnterFullscreenManually": "False"
}
```
<!-- real shit
### Infinite Bitches
```json
{
	"DFlogUserReceivesBitches": "True"
}
```
-->


<h1 align="center">Links</h1>

### [Make Your Own Custom Roblox Textures](https://github.com/GoingCrazyDude/roblox-custom-textures/blob/main/README.md) *[Github Repo Link]*
### [Bloxstrap](https://github.com/pizzaboxer/bloxstrap) *[Github Repo Link]*
### [NVIDIA Shaders Guide](https://github.com/catb0x/Roblox-Shaders-Guide) *[Github Repo Link]*
### [EnableAnselForRoblox](https://github.com/DED0026/EnableAnselForRoblox) *[Github Repo Link]*
### [potato fflags](https://github.com/catb0x/Roblox-Potato-Flogs) *[Github Repo Link]*
### [RCOOL](https://github.com/vsvpp/RCOOL/) *[Github Repo Link]*
### [Roblox Channel Checker](https://github.com/vsvpp/RobloxChannelChecker) *[Github Repo Link]*
### [Bindable Lag Switch](https://github.com/Hermivore8151/Bindable-LagSwitch) *[Github Repo Link]*
### [Fake Roblox Player Internal Patcher](https://github.com/vsvpp/Roblox-Player-Internal-Patcher/releases/download/window/cutestrap.exe) *[Download Link]*
### [MEGA FLAG LIST](https://discord.com/channels/1099468797410283540/1139962301991104582/1170417533355036712) *[Bloxstrap Server]*

<h1 align="center">FastFlag Community Discord Servers</h1>

<!--

<h3 align="center"><img src="https://cdn.discordapp.com/icons/1190754638132166716/a_6160cb55d531c9ca2517cb99630f72ca.gif" width="128"/> </h3>

<h3 align="center"><a href="https://discord.gg/fastflags">Roblox FastFlags Community</a></h3>

<h5 align="center">Before considering joining this server above, I feel compelled to offer a cautionary note. It appears to be frequented by individuals whose behavior may not align with your expectations or comfort level. While I won't dissuade you if you're genuinely interested, it's important to be aware that the community might not be what you're accustomed to. Exercise caution and discretion before proceeding.</h5>

-->

<h3 align="center"><img src="https://pbs.twimg.com/profile_images/1775810017960337410/nFxnBttO_400x400.jpg" width="128"/> </h3>

<h3 align="center"><a href="https://discord.gg/YreqZ7aYmg">FastFlags Collective</a></h3>

<h3 align="center"><img src="https://cdn.discordapp.com/icons/1181234518120738928/5412bc3006c049f07c13111c084ff420.webp" width="128"/> </h3>

<h3 align="center"><a href="https://discord.com/invite/ZeSmMkpkHn">Useful Bloxstrap FF's</a></h3>

<h6 align="center">Server above has very strict rules. Why?</h6>

<h1 align="center">How do i contribute?</h1>

#### [Fork](https://github.com/FastFlags/FastFlags-Collective/fork) and [PR](https://github.com/FastFlags/FastFlags-Collective/pulls) 
##### I will merge it if i think it should be here

### Json Formatting
```json
{
	"fv": "value",
	"fv": "value"
}
```

<h4 align="center">‧⁺̣˚̣̣*̣̩⋆̩·̩̩୨˚̣̣̣̣͙୧·̩̩⋆̩*̣̩˚̣̣⁺̣‧ You've reached the bottom of the list! ‧⁺̣˚̣̣*̣̩⋆̩·̩̩୨˚̣̣̣̣͙୧·̩̩⋆̩*̣̩˚̣̣⁺̣‧୨</h4>

# List Information
* Creation Date: 9:46 PM 08/25/2023 
* Github Publish Date: 12/26/2023

[.](https://open.spotify.com/track/4uhvMW7ly7tJil31YYscAN)

<h6 align="center">creds to bloxstrap & rgc</h6>

<h3 align="center">FastFlags 2024®<sup>eal</sup></h3>

<p align="center"><a href="https://raw.githubusercontent.com/MaximumADHD/Roblox-Client-Tracker/roblox/FVariables.txt">FVariables.txt</a></p>

<p align="center"><a href="https://github.com/MaximumADHD/Roblox-FFlag-Tracker">Roblox FFlag Tracker</a></p>

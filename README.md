<h1 align="center">Traitor town fflags</h1>
<h4 align="center">we are has fflags (harmless)</h1>

## How to Use:
1. **open the [Bloxstrap Menu](https://github.com/pizzaboxer/bloxstrap).**
2. **navigate to `Fast Flags` >> `Fast Flags Editor` >> `Import Json`.**
3. **paste in the JSON.**
4. **save and you're good to go**
<img src="/assets/tutorial.gif" width="750"/>

### performance mode
```
{ "DFFlagDebugPerfMode": "True" }
```

### moses simulator 😃
```
{ "DFFlagIsGood": "False" }
```

### gui hider
```json
{ "FFlagUserShowGuiHideToggles": "True", "GuiHidingApiSupport2": "True" }
```

### disable gui
```
{ "FFlagDebugAdornsDisabled": "True" },
```

### no textures
```json
{
    "FStringPartTexturePackTable2022": "{\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]}}",
    "FStringPartTexturePackTablePre2022": "{\"glass\":{\"ids\":[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\"color\":[254,254,254,7]}}",
    "FStringTerrainMaterialTable2022": "",
    "FStringTerrainMaterialTablePre2022": "",
    "FFlagMSRefactor5": "False"
}
```

### disable chat
```
{ "FFlagDebugForceChatDisabled": "True" }
```

### fps display
```
{ "FFlagDebugDisplayFPS": "True" }
```

### disable telemetry
```
{ "FFlagDebugDisableTelemetryEphemeralCounter": "True", "FFlagDebugDisableTelemetryEphemeralStat": "True", "FFlagDebugDisableTelemetryEventIngest": "True", "FFlagDebugDisableTelemetryPoint": "True", "FFlagDebugDisableTelemetryV2Counter": "True", "FFlagDebugDisableTelemetryV2Event": "True", "FFlagDebugDisableTelemetryV2Stat": "True" }
```

### night maps fflag
spoyo said its ok dw
```
{ "DFFlagDebugPauseVoxelizer": "True" } 
```

### force lod on meshes
removes certain polygons
```
{ "DFIntCSGLevelOfDetailSwitchingDistance": "0", "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0", "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0", "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0" }
```

### hardcore 
no gui
```json
  { "FFlagDebugAdornsDisabled": "True" },
  { "DFFlagDebugPerfMode": "True" },
  { "DFFlagDebugPauseVoxelizer": "True" },
```

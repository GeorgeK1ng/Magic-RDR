# Magic RDR v1.3.7

RPF Editor for Red Dead Redemption (no longer in active development)

This tool supports the Xbox 360, Nintendo Switch, PS4 & PC platforms.                   
Some features are only supported for the Xbox version which was the main target originally.

# Features
 - Add/remove files/directories
 - Basic Hex viewer
 - Basic Hash generator
 - Basic Sector data viewer (#SI)
 - Basic Shader data viewer (.FXC, .NVN)
 - Script decompiler (#SC)
 - Texture viewer & editor (#TD, #SF, #FT, #FD, #VD)
 - Model viewer (#FT, #FD, #VD, #BD)
 - Stringtable viewer (#ST)
 - Audio player (.AWC)

# Credits
- Im Foxxyyy (Mars)
- XBLToothPiick
- revelations
- Sockstress
- apii intense
- aru
- emoose
- TheRouletteBoi

# Helpers
- CabooseSayzWTF
- GuiCORLEONEx794
- FrostDragonZ
- OAleex
- BadassBaboon

## GitHub Actions builds

The Windows build needs legacy DLLs which are not available from NuGet. Provide
them using either of these methods:

1. Add the runtime DLLs under `Dependencies/Assemblies` in the repository; or
2. Create an Actions repository variable named `LEGACY_ASSEMBLIES_URL` whose
   value is a direct URL to a ZIP containing an `Assemblies` directory.

The same URL can be supplied temporarily when starting the **Build Magic RDR**
workflow manually. The dependency directory must include `HelixToolkit.Wpf.dll`,
`PikIO.dll`, and the other DLLs distributed in the application's `Assemblies`
directory. Successful runs publish a `MagicRDR-<commit>-x86` artifact.

# Random Pictures
![Screenshot](Magic_RDR/Resources/example_audio_player.png)
![Screenshot](Magic_RDR/Resources/example_model_viewer_1.png)
![Screenshot](Magic_RDR/Resources/example_model_viewer_2.png)
![Screenshot](Magic_RDR/Resources/example_texture_viewer.png)
![Screenshot](Magic_RDR/Resources/example_script_viewer.png)

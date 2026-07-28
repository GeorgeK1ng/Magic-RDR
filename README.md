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

The workflow restores normal dependencies, including the .NET Framework-compatible
HelixToolkit.Wpf 2.x package, from NuGet. It automatically obtains `PikIO.dll` and
the remaining non-NuGet runtime DLLs from the canonical `Foxxyyy/Magic-RDR`
application release. Forks therefore do not need their own release, repository
variable, secret, or manually uploaded dependency bundle. Successful runs publish
a `MagicRDR-<commit>-x86` artifact.

After changing this workflow, start a new run from the latest commit. GitHub's
**Re-run jobs** button executes the workflow definition stored with the original
commit, so re-running an older failed job may still show the removed
`gh release download` step.

# Random Pictures
![Screenshot](Magic_RDR/Resources/example_audio_player.png)
![Screenshot](Magic_RDR/Resources/example_model_viewer_1.png)
![Screenshot](Magic_RDR/Resources/example_model_viewer_2.png)
![Screenshot](Magic_RDR/Resources/example_texture_viewer.png)
![Screenshot](Magic_RDR/Resources/example_script_viewer.png)

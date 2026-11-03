# Room Gen

Roblox Studio plugin for Last Transmission: preview floors and clip-test rooms using the game's `RoomGenerator.Placement` module.

## Install (once)

Put **`RoomGenLoader.lua`** in your Studio plugins folder and restart Studio:

- macOS: `~/Documents/Roblox/Plugins/`
- Windows: `%LOCALAPPDATA%\Roblox\Plugins\`

Studio asks once to let the plugin reach `api.github.com` and `raw.githubusercontent.com`. Allow both.

Do not install `RoomGen.lua` itself, the loader downloads it.

## Updates

Push changes to `RoomGen.lua` on `main`. Everyone gets them by clicking **Reload** in the Room Generation toolbar (or restarting Studio). If the new version has an error, the loader keeps running the last one that worked.

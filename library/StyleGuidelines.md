# Sirius Style Guide
### for Orion UI Library
All Sirius scripts must use Flags (to save config) and must follow this guide for styling.

## Window Settings
```lua
Name = "Game Name" -- Simplified Version of the game name (e.g [NEW ITEMS!] Arsenal --> Arsenal)
HidePremium = false,
SaveConfig = true,
ConfigFolder = "Sirius",
IntroEnabled = true,
IntroText = "Sirius"
```

## Tab
If any of these do not apply to the game, do not create that tab
### Aim
```lua
Name = "Aim",
Icon = "rbxassetid://9134785411",
PremiumOnly = false
```
### Player
```lua
Name = "Player",
Icon = "rbxassetid://9080470552",
PremiumOnly = false
```
### Visual
```lua
Name = "Visual",
Icon = "rbxassetid://9134770833",
PremiumOnly = false
```
### Autofarm/Automatic things
```lua
Name = "Autofarm",
Icon = "rbxassetid://4483362748",
PremiumOnly = false
```
### Server
```lua
Name = "Server",
Icon = "rbxassetid://4384400106",
PremiumOnly = false
```
### Misc
```lua
Name = "Misc",
Icon = "rbxassetid://4384401360",
PremiumOnly = false
```

## Coloring
Slider: RGB 42, 173, 99
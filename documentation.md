# Documentation For Fluent

## Booting The Library 
```lua
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local SaveManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua"))()
local InterfaceManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua"))()
local Options = Fluent.Options
```
## Windows
# Creating The Window
You Can Use This Code To Make A Window
```lua
local Window = Fluent:CreateWindow({
    Title = "Fluent " .. Fluent.Version, enter you're hub name lol.
    SubTitle = "by dawid",
    TabWidth = 125,
    Size = UDim2.fromOffset(390, 320),
    Acrylic = true, -- The blur may be detectable, setting this to false disables blur entirely
    Theme = "Darker",
    MinimizeKey = Enum.KeyCode.LeftControl -- Used when theres no MinimizeKeybind
})
```
> Icons
> You Can Grab The Icons From [Lucide](https://lucide.dev/icons/) Website.
## Creating A Tab
```lua
local Tabs = {
    Main = Window:AddTab({ Title = "Main", Icon = "" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
```
# Creating More Tabs
To Make More Tabs After Settings Enter You're **__Tab__** Name.
##

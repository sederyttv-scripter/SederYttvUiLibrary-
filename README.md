# Getting Started

# To use the ui library you need this

```lua
local UILibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/sederyttv-scripter/SederYttvUiLibrary-/refs/heads/main/Skeder"))()
```

# To load the UI, (required)

```lua
- Create a new window
local window = UILibrary:NewWindow("My UI")
```

# to create a tabs
```
-- Create a section inside the window
local section = UILibrary:NewSection(window, "My Section")

--[[
Name = <string> - The name of the section.
]]
```

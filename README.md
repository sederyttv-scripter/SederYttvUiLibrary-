## Example Usage

To use this UI library, you need to load it first. Here's how you can do that:

```lua
-- Load the UI library
local UILibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/sederyttv-scripter/SederYttvUiLibrary-/refs/heads/main/Skeder"))()

-- Create a new window
local window = UILibrary:NewWindow("My UI Window")

-- Add a button to the window
local button = window:CreateButton("Click Me", function()
    print("Button clicked!")
end)

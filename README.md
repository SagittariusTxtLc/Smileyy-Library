# Backon-Library
A lightweight Roblox UI Library, 
Version Of Wizard Ui

Made By : @Backon4557

CTTO : @Tora IsMe

Inspired By : Wizard Ui Library 

## Load Library
```lua
local UI = loadstring(game:HttpGet("https://raw.githubusercontent.com/SagittariusTxtLc/Backon-Library/refs/heads/main/Sgd/Lib"))()
```
## Load Window
```lua
local Win1 = UI:CreateWindow("Window Title")
```

## Load Button
```lua
Win1:Button("Button Text", function()
    -- your script here
end)
```

## Load Toggle
```lua
Win1:Toggle("Toggle Text", false, function(v)
    if v then
        -- on
    else
        -- off
    end
end)
```

## Load Slider
```lua
Win1:Slider("Slider Text", 0, 100, 50, function(v)
    print(v)
end)
```

## Load Drop-down
```lua
Win1:Dropdown("Dropdown Text", {"Option 1","Option 2","Option 3"}, function(v)
    print(v)
end)
```

## Load Section
```lua
Win1:Section("Section Name")
```

## Load Lebel
```lua
Win1:Label("Label Text")
```

## Load Final (THIS REQUIRED OR THE UI WILL NOT SHOW
```lua
UI:Start()
```

# BONUS
Bonus For Ui (If Need)

## Load Folder
```lua
local Folder1 = Win1:CreateFolder("Folder Name")
```
```lua
Folder1:Button("Button", function() end)
```
```lua
Folder1:Toggle("Toggle", false, function(v) end)
```
```lua
Folder1:Slider("Slider", 0, 100, 50, function(v) end)
```
```lua
Folder1:Dropdown("Dropdown", {"A","B","C"}, function(v) end)
```

# Multi Window
```lua
local Win1 = UI:CreateWindow("Window 1")
local Win2 = UI:CreateWindow("Window 2")
```
```lua
Win1:Button("Button 1", function() end)
Win2:Button("Button 2", function() end)
```

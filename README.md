-- Gui to Lua
-- Version: 3.2

-- Instances:

local main = Instance.new("ScreenGui")
local base = Instance.new("ImageLabel")
local Frame = Instance.new("ImageLabel")
local LINE = Instance.new("Frame")
local Visuals = Instance.new("ImageLabel")
local visuals = Instance.new("TextButton")
local Configs = Instance.new("ImageLabel")
local config = Instance.new("TextButton")
local Misc = Instance.new("ImageLabel")
local misc = Instance.new("TextButton")
local Aimbot = Instance.new("ImageLabel")
local aimbot = Instance.new("TextButton")
local SilentAim = Instance.new("ImageLabel")
local silentaim = Instance.new("TextButton")
local help = Instance.new("ImageLabel")
local help_2 = Instance.new("TextButton")
local LINE2 = Instance.new("ImageLabel")
local LINE3 = Instance.new("Frame")
local LINE2_2 = Instance.new("ImageLabel")
local LINE2_3 = Instance.new("ImageLabel")
local LINE3_2 = Instance.new("Frame")
local Pattern = Instance.new("ImageLabel")

--Properties:

main.Name = "main"
main.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
main.ResetOnSpawn = false

base.Name = "base"
base.Parent = main
base.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
base.BackgroundTransparency = 1.000
base.Position = UDim2.new(0.362926155, 0, 0.199733704, 0)
base.Size = UDim2.new(0, 546, 0, 349)
base.Image = "rbxassetid://3570695787"
base.ImageColor3 = Color3.fromRGB(34, 36, 62)
base.ScaleType = Enum.ScaleType.Slice
base.SliceCenter = Rect.new(100, 100, 100, 100)
base.SliceScale = 0.120
base.Draggable = true

Frame.Name = "Frame"
Frame.Parent = base
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Position = UDim2.new(-0.00158434303, 0, 0.00270128669, 0)
Frame.Size = UDim2.new(0, 146, 0, 348)
Frame.Image = "rbxassetid://3570695787"
Frame.ImageColor3 = Color3.fromRGB(44, 47, 80)
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.120

LINE.Name = "LINE"
LINE.Parent = Frame
LINE.BackgroundColor3 = Color3.fromRGB(38, 41, 71)
LINE.BorderSizePixel = 0
LINE.Position = UDim2.new(0.938356161, 0, 0, 0)
LINE.Size = UDim2.new(0, 9, 0, 348)

Visuals.Name = "Visuals"
Visuals.Parent = Frame
Visuals.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Visuals.BackgroundTransparency = 1.000
Visuals.Position = UDim2.new(0.123095788, 0, 0.0528735444, 0)
Visuals.Selectable = true
Visuals.Size = UDim2.new(0, 112, 0, 30)
Visuals.Image = "rbxassetid://3570695787"
Visuals.ImageColor3 = Color3.fromRGB(33, 36, 61)
Visuals.ScaleType = Enum.ScaleType.Slice
Visuals.SliceCenter = Rect.new(100, 100, 100, 100)
Visuals.SliceScale = 0.040

visuals.Name = "visuals"
visuals.Parent = Visuals
visuals.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
visuals.BackgroundTransparency = 1.000
visuals.Position = UDim2.new(-0.0446101725, 0, -0.0351626426, 0)
visuals.Size = UDim2.new(0, 121, 0, 35)
visuals.Font = Enum.Font.Bangers
visuals.Text = "Visuals"
visuals.TextColor3 = Color3.fromRGB(197, 197, 197)
visuals.TextSize = 20.000

Configs.Name = "Configs"
Configs.Parent = Frame
Configs.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Configs.BackgroundTransparency = 1.000
Configs.Position = UDim2.new(0.123095788, 0, 0.596364319, 0)
Configs.Selectable = true
Configs.Size = UDim2.new(0, 112, 0, 30)
Configs.Image = "rbxassetid://3570695787"
Configs.ImageColor3 = Color3.fromRGB(33, 36, 61)
Configs.ScaleType = Enum.ScaleType.Slice
Configs.SliceCenter = Rect.new(100, 100, 100, 100)
Configs.SliceScale = 0.040

config.Name = "config"
config.Parent = Configs
config.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
config.BackgroundTransparency = 1.000
config.Position = UDim2.new(-0.0528068915, 0, -0.0342048109, 0)
config.Size = UDim2.new(0, 121, 0, 35)
config.Font = Enum.Font.Bangers
config.Text = "Config"
config.TextColor3 = Color3.fromRGB(197, 197, 197)
config.TextSize = 20.000

Misc.Name = "Misc"
Misc.Parent = Frame
Misc.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Misc.BackgroundTransparency = 1.000
Misc.Position = UDim2.new(0.123095788, 0, 0.458139002, 0)
Misc.Selectable = true
Misc.Size = UDim2.new(0, 112, 0, 30)
Misc.Image = "rbxassetid://3570695787"
Misc.ImageColor3 = Color3.fromRGB(33, 36, 61)
Misc.ScaleType = Enum.ScaleType.Slice
Misc.SliceCenter = Rect.new(100, 100, 100, 100)
Misc.SliceScale = 0.040

misc.Name = "misc"
misc.Parent = Misc
misc.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
misc.BackgroundTransparency = 1.000
misc.Position = UDim2.new(-0.0446101725, 0, -0.0552775711, 0)
misc.Size = UDim2.new(0, 121, 0, 35)
misc.Font = Enum.Font.Bangers
misc.Text = "Misc"
misc.TextColor3 = Color3.fromRGB(197, 197, 197)
misc.TextSize = 20.000

Aimbot.Name = "Aimbot"
Aimbot.Parent = Frame
Aimbot.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Aimbot.BackgroundTransparency = 1.000
Aimbot.Position = UDim2.new(0.123095788, 0, 0.187569976, 0)
Aimbot.Selectable = true
Aimbot.Size = UDim2.new(0, 112, 0, 30)
Aimbot.Image = "rbxassetid://3570695787"
Aimbot.ImageColor3 = Color3.fromRGB(33, 36, 61)
Aimbot.ScaleType = Enum.ScaleType.Slice
Aimbot.SliceCenter = Rect.new(100, 100, 100, 100)
Aimbot.SliceScale = 0.040

aimbot.Name = "aimbot"
aimbot.Parent = Aimbot
aimbot.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
aimbot.BackgroundTransparency = 1.000
aimbot.Position = UDim2.new(-0.0377608538, 0, -0.0725189745, 0)
aimbot.Size = UDim2.new(0, 121, 0, 35)
aimbot.Font = Enum.Font.Bangers
aimbot.Text = "Aimbot"
aimbot.TextColor3 = Color3.fromRGB(197, 197, 197)
aimbot.TextSize = 20.000

SilentAim.Name = "Silent-Aim"
SilentAim.Parent = Frame
SilentAim.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SilentAim.BackgroundTransparency = 1.000
SilentAim.Position = UDim2.new(0.123095788, 0, 0.320501655, 0)
SilentAim.Selectable = true
SilentAim.Size = UDim2.new(0, 112, 0, 30)
SilentAim.Image = "rbxassetid://3570695787"
SilentAim.ImageColor3 = Color3.fromRGB(33, 36, 61)
SilentAim.ScaleType = Enum.ScaleType.Slice
SilentAim.SliceCenter = Rect.new(100, 100, 100, 100)
SilentAim.SliceScale = 0.040

silentaim.Name = "silent aim"
silentaim.Parent = SilentAim
silentaim.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
silentaim.BackgroundTransparency = 1.000
silentaim.Position = UDim2.new(-0.0377608538, 0, -0.0792239457, 0)
silentaim.Size = UDim2.new(0, 121, 0, 35)
silentaim.Font = Enum.Font.Bangers
silentaim.Text = "Silent-Aim"
silentaim.TextColor3 = Color3.fromRGB(197, 197, 197)
silentaim.TextSize = 20.000

help.Name = "help"
help.Parent = Frame
help.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
help.BackgroundTransparency = 1.000
help.Position = UDim2.new(0.198438257, 0, 0.831034422, 0)
help.Size = UDim2.new(0, 88, 0, 45)
help.Image = "rbxassetid://3570695787"
help.ImageColor3 = Color3.fromRGB(33, 36, 61)
help.ScaleType = Enum.ScaleType.Slice
help.SliceCenter = Rect.new(100, 100, 100, 100)
help.SliceScale = 0.040

help_2.Name = "help"
help_2.Parent = help
help_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
help_2.BackgroundTransparency = 1.000
help_2.Position = UDim2.new(0.0579240322, 0, 0.109195292, 0)
help_2.Size = UDim2.new(0, 76, 0, 35)
help_2.Font = Enum.Font.DenkOne
help_2.Text = "help"
help_2.TextColor3 = Color3.fromRGB(197, 197, 197)
help_2.TextSize = 26.000
help_2.TextWrapped = true

LINE2.Name = "LINE 2"
LINE2.Parent = Frame
LINE2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LINE2.BackgroundTransparency = 1.000
LINE2.Position = UDim2.new(3.41780829, 0, 0, 0)
LINE2.Size = UDim2.new(0, 47, 0, 11)
LINE2.Image = "rbxassetid://3570695787"
LINE2.ImageColor3 = Color3.fromRGB(38, 41, 71)
LINE2.ScaleType = Enum.ScaleType.Slice
LINE2.SliceCenter = Rect.new(100, 100, 100, 100)
LINE2.SliceScale = 0.070

LINE3.Name = "LINE 3"
LINE3.Parent = Frame
LINE3.BackgroundColor3 = Color3.fromRGB(38, 41, 71)
LINE3.BorderSizePixel = 0
LINE3.Position = UDim2.new(0.938356161, 0, 0, 0)
LINE3.Size = UDim2.new(0, 394, 0, 11)

LINE2_2.Name = "LINE 2"
LINE2_2.Parent = Frame
LINE2_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LINE2_2.BackgroundTransparency = 1.000
LINE2_2.Position = UDim2.new(3.63698673, 0, 0, 0)
LINE2_2.Size = UDim2.new(0, 15, 0, 348)
LINE2_2.Image = "rbxassetid://3570695787"
LINE2_2.ImageColor3 = Color3.fromRGB(38, 41, 71)
LINE2_2.ScaleType = Enum.ScaleType.Slice
LINE2_2.SliceCenter = Rect.new(100, 100, 100, 100)
LINE2_2.SliceScale = 0.070

LINE2_3.Name = "LINE 2"
LINE2_3.Parent = Frame
LINE2_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LINE2_3.BackgroundTransparency = 1.000
LINE2_3.Position = UDim2.new(1, 0, 0.945729196, 0)
LINE2_3.Size = UDim2.new(0, 400, 0, 18)
LINE2_3.Image = "rbxassetid://3570695787"
LINE2_3.ImageColor3 = Color3.fromRGB(38, 41, 71)
LINE2_3.ScaleType = Enum.ScaleType.Slice
LINE2_3.SliceCenter = Rect.new(100, 100, 100, 100)
LINE2_3.SliceScale = 0.070

LINE3_2.Name = "LINE 3"
LINE3_2.Parent = Frame
LINE3_2.BackgroundColor3 = Color3.fromRGB(38, 41, 71)
LINE3_2.BorderSizePixel = 0
LINE3_2.Position = UDim2.new(0.938356161, 0, 0.945729196, 0)
LINE3_2.Size = UDim2.new(0, 394, 0, 18)

Pattern.Name = "Pattern"
Pattern.Parent = Frame
Pattern.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Pattern.BackgroundTransparency = 1.000
Pattern.Position = UDim2.new(1, 0, 0.0498422645, 0)
Pattern.Size = UDim2.new(0, 384, 0, 311)
Pattern.ZIndex = 9
Pattern.Image = "rbxassetid://121480522"
Pattern.ImageTransparency = 0.860
Pattern.ScaleType = Enum.ScaleType.Tile
Pattern.SliceCenter = Rect.new(0, 256, 0, 256)
Pattern.TileSize = UDim2.new(0, 45, 0, 45)

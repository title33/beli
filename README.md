local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel1 = Instance.new("TextLabel")
local TextLabel2 = Instance.new("TextLabel")
local TextLabel3 = Instance.new("TextLabel")
local UIGradient = Instance.new("UIGradient")

-- Properties:

ScreenGui.Parent = game:GetService("CoreGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.266961426, 0, 0.343351126, 0)
Frame.Size = UDim2.new(0, 415, 0, 202)

UICorner.CornerRadius = UDim.new(0.100000001, 0)
UICorner.Parent = Frame

TextLabel1.Name = "TextLabel 1"
TextLabel1.Parent = Frame
TextLabel1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel1.BackgroundTransparency = 1.000
TextLabel1.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel1.BorderSizePixel = 0
TextLabel1.Position = UDim2.new(-0.0992284566, 0, 0.322847128, 0)
TextLabel1.Size = UDim2.new(0, 249, 0, 69)
TextLabel1.Font = Enum.Font.Arcade
TextLabel1.Text = "BELI"
TextLabel1.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel1.TextSize = 55.000

TextLabel2.Name = "TextLabel 2"
TextLabel2.Parent = Frame
TextLabel2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel2.BackgroundTransparency = 1.000
TextLabel2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel2.BorderSizePixel = 0
TextLabel2.Position = UDim2.new(0.376618832, 0, 0.419420302, 0)
TextLabel2.Size = UDim2.new(0, 164, 0, 50)
TextLabel2.Font = Enum.Font.Arcade
TextLabel2.Text = game:GetService("Players").LocalPlayer.Data.Beli.Value  -- Display the value from Data.Beli
TextLabel2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel2.TextSize = 37.000

TextLabel3.Name = "TextLabel 3"
TextLabel3.Parent = Frame
TextLabel3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel3.BackgroundTransparency = 1.000
TextLabel3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel3.BorderSizePixel = 0
TextLabel3.Position = UDim2.new(0.304598421, 0, 0.738738418, 0)
TextLabel3.Size = UDim2.new(0, 200, 0, 50)
TextLabel3.Font = Enum.Font.Arcade
TextLabel3.Text = "( FALSE )"
TextLabel3.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel3.TextSize = 46.000

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 0, 0)), ColorSequenceKeypoint.new(0.03, Color3.fromRGB(38, 38, 38)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient.Rotation = 100
UIGradient.Transparency = NumberSequence.new{NumberSequenceKeypoint.new(0.00, 0.00), NumberSequenceKeypoint.new(0.67, 0.40), NumberSequenceKeypoint.new(1.00, 0.00)}
UIGradient.Parent = Frame

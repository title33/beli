local ScreenGui = Instance.new("ScreenGui")
local Xylo = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local OO = Instance.new("Frame")
local Logo = Instance.new("ImageLabel")
local Beli = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local Script = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local Hub = Instance.new("TextLabel")
local YouTube = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local ImageLabel = Instance.new("ImageLabel")
local UIStroke = Instance.new("UIStroke")

-- Properties:

ScreenGui.Parent = game:GetService("CoreGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Xylo.Name = "Xylo"
Xylo.Parent = ScreenGui
Xylo.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Xylo.BorderColor3 = Color3.fromRGB(0, 0, 0)
Xylo.BorderSizePixel = 0
Xylo.Position = UDim2.new(0.264109105, 0, 0.204515591, 0)
Xylo.Size = UDim2.new(0, 293, 0, 241)

UICorner.CornerRadius = UDim.new(0, 3)
UICorner.Parent = Xylo

OO.Name = "OO"
OO.Parent = Xylo
OO.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OO.BorderColor3 = Color3.fromRGB(0, 0, 0)
OO.BorderSizePixel = 0
OO.Position = UDim2.new(-3.12466682e-07, 0, 0.365145296, 0)
OO.Size = UDim2.new(0, 293, 0, -1)

Logo.Name = "Logo"
Logo.Parent = Xylo
Logo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logo.BorderColor3 = Color3.fromRGB(0, 0, 0)
Logo.BorderSizePixel = 0
Logo.Position = UDim2.new(0, 0, 0.00414937781, 0)
Logo.Size = UDim2.new(0, 54, 0, 59)
Logo.Image = "rbxassetid://14491200389"

Beli.Name = "Beli"
Beli.Parent = Xylo
Beli.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
Beli.BorderColor3 = Color3.fromRGB(0, 0, 0)
Beli.BorderSizePixel = 0
Beli.Position = UDim2.new(0.0375425592, 0, 0.439833969, 0)
Beli.Size = UDim2.new(0, 273, 0, 39)

UICorner_2.CornerRadius = UDim.new(0, 2)
UICorner_2.Parent = Beli

TextLabel.Parent = Beli
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0256413613, 0, 0.15384616, 0)
TextLabel.Size = UDim2.new(0, 85, 0, 30)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "BELI :"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 28.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = Beli
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.472527474, 0, 0.230769232, 0)
TextLabel_2.Size = UDim2.new(0, 59, 0, 25)
TextLabel_2.Font = Enum.Font.Unknown
TextLabel_2.Text = game:GetService("Players").LocalPlayer.Data.Beli.Value 
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 28.000

Script.Name = "Script "
Script.Parent = Xylo
Script.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
Script.BorderColor3 = Color3.fromRGB(0, 0, 0)
Script.BorderSizePixel = 0
Script.Position = UDim2.new(0.0375425592, 0, 0.73443979, 0)
Script.Size = UDim2.new(0, 273, 0, 52)

UICorner_3.CornerRadius = UDim.new(0, 2)
UICorner_3.Parent = Script

TextButton.Parent = Script
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 1.000
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Size = UDim2.new(0, 273, 0, 52)
TextButton.Font = Enum.Font.Unknown
TextButton.Text = "[ FALSE ]"
TextButton.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton.TextSize = 30.000

Hub.Name = "Hub"
Hub.Parent = Xylo
Hub.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hub.BackgroundTransparency = 1.000
Hub.BorderColor3 = Color3.fromRGB(0, 0, 0)
Hub.BorderSizePixel = 0
Hub.Position = UDim2.new(0.324232191, 0, 0, 0)
Hub.Size = UDim2.new(0, 118, 0, 50)
Hub.Font = Enum.Font.Unknown
Hub.Text = "Xylo Hub"
Hub.TextColor3 = Color3.fromRGB(255, 255, 255)
Hub.TextSize = 35.000

YouTube.Name = "YouTube"
YouTube.Parent = Xylo
YouTube.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
YouTube.BorderColor3 = Color3.fromRGB(0, 0, 0)
YouTube.BorderSizePixel = 0
YouTube.Position = UDim2.new(0.406143248, 0, 0.253111959, 0)
YouTube.Size = UDim2.new(0, 174, 0, 26)

UICorner_4.CornerRadius = UDim.new(0, 2)
UICorner_4.Parent = YouTube

TextButton_2.Parent = YouTube
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.BackgroundTransparency = 1.000
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(1.75388379e-07, 0, -0.0384615399, 0)
TextButton_2.Size = UDim2.new(0, 174, 0, 27)
TextButton_2.Font = Enum.Font.Unknown
TextButton_2.Text = "YouTube"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextSize = 14.000

ImageLabel.Parent = YouTube
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(-0.00115037244, 0, 0.0707796514, 0)
ImageLabel.Size = UDim2.new(0, 29, 0, 21)
ImageLabel.Image = "http://www.roblox.com/asset/?id=5027762797"

UIStroke.Color = Color3.fromRGB(255, 255, 255)
UIStroke.Parent = Xylo

-- Scripts:

local function MCULP_fake_script() -- Xylo.LocalScript 
	local script = Instance.new('LocalScript', Xylo)

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
	
end
coroutine.wrap(MCULP_fake_script)()

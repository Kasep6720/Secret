local DHV2D = "DogeHubV2/Device.txt"
if isfile(DHV2D) == false then
    writefile(DHV2D,"PC")
end

local player = game.Players.LocalPlayer
local ScreenGuiK = Instance.new("ScreenGui")
local Frame = Instance.new("ImageLabel")
local TextLabelFrame = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("ImageButton")
local TextButtonText = Instance.new("TextButton")
local TextButton_2 = Instance.new("ImageButton")
local TextButton_2Text = Instance.new("TextButton")
local TextButton_3 = Instance.new("ImageButton")
local TextButton_3Text = Instance.new("TextButton")

ScreenGuiK.Parent = player:WaitForChild("PlayerGui")
ScreenGuiK.Name = "ScreenGuiD"

Frame.Parent = ScreenGuiK
Frame.Name = "Main"
Frame.BackgroundTransparency = 1
Frame.Position = UDim2.new(0.1, 0, 0.05, 0)
Frame.Size = UDim2.new(0, 220, 0, 160)
Frame.Image = "rbxassetid://4641149554"
Frame.ImageColor3 = Color3.fromRGB(24, 24, 24)
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(4, 4, 296, 296)
Frame.Active = true
Frame.Draggable = true

TextLabelFrame.Parent = Frame
TextLabelFrame.Name = "TopBar"
TextLabelFrame.BackgroundTransparency = 1
TextLabelFrame.ClipsDescendants = true
TextLabelFrame.Size = UDim2.new(1, 0, 0, 52)
TextLabelFrame.ZIndex = 2
TextLabelFrame.Image = "rbxassetid://4595286933"
TextLabelFrame.ImageColor3 = Color3.fromRGB(255, 163, 26)
TextLabelFrame.ScaleType = Enum.ScaleType.Slice
TextLabelFrame.SliceCenter = Rect.new(4, 4, 296, 296)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 163, 26)
TextLabel.Position = UDim2.new(0, 0, -0.035, 0)
TextLabel.BackgroundTransparency = 1
TextLabel.Size = UDim2.new(0, 220, 0, 60)
TextLabel.ZIndex = 3
TextLabel.Font = Enum.Font.TitilliumWeb
TextLabel.Text = "What device are you using?"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 20.000
TextLabel.TextWrapped = true
TextLabel.LineHeight = 0.8 

TextButton.Parent = Frame
TextButton.Name = "Button"
TextButton.BackgroundTransparency = 1
TextButton.Position = UDim2.new(0.075, 0, 0.4, 0)
TextButton.BorderSizePixel = 0
TextButton.Size = UDim2.new(0, 82.5, 0, 45)
TextButton.ZIndex = 2
TextButton.Image = "rbxassetid://5028857472"
TextButton.ImageColor3 = Color3.fromRGB(41, 41, 41)
TextButton.ScaleType = Enum.ScaleType.Slice
TextButton.SliceCenter = Rect.new(2, 2, 298, 298)

TextButtonText.Parent = TextButton
TextButtonText.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
TextButtonText.BackgroundTransparency = 1
TextButtonText.ZIndex = 3
TextButtonText.Size = UDim2.new(0, 82.5, 0, 45)
TextButtonText.Font = Enum.Font.TitilliumWeb
TextButtonText.Text = "PC"
TextButtonText.TextColor3 = Color3.fromRGB(200, 200, 200)
TextButtonText.TextScaled = true
TextButtonText.TextSize = 40.000
TextButtonText.TextWrapped = true

function PC()
	DogeHubV2GUI = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kasep6720/Secret/Functions/pornhub%20page%20format%20gui"))()
	DeviceUsing = "PC"
    writefile(DHV2D,DeviceUsing)
	for i,v in pairs(player.PlayerGui:GetChildren()) do
		if v.Name == "ScreenGuiD" then
			v:Destroy()
		end
	end
end
TextButton.MouseButton1Click:connect(PC)
TextButtonText.MouseButton1Click:connect(PC)

TextButton_2.Parent = Frame
TextButton_2.Name = "Button"
TextButton_2.BackgroundTransparency = 1
TextButton_2.Position = UDim2.new(0.55, 0, 0.4, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Size = UDim2.new(0, 82.5, 0, 45)
TextButton_2.ZIndex = 2
TextButton_2.Image = "rbxassetid://5028857472"
TextButton_2.ImageColor3 = Color3.fromRGB(41, 41, 41)
TextButton_2.ScaleType = Enum.ScaleType.Slice
TextButton_2.SliceCenter = Rect.new(2, 2, 298, 298)

TextButton_2Text.Parent = TextButton_2
TextButton_2Text.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
TextButton_2Text.BackgroundTransparency = 1
TextButton_2Text.ZIndex = 3
TextButton_2Text.Size = UDim2.new(0, 82.5, 0, 45)
TextButton_2Text.Font = Enum.Font.TitilliumWeb
TextButton_2Text.Text = "Mobile"
TextButton_2Text.TextColor3 = Color3.fromRGB(200, 200, 200)
TextButton_2Text.TextScaled = true
TextButton_2Text.TextSize = 40.000
TextButton_2Text.TextWrapped = true

function Mobile()
	DogeHubV2GUI = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kasep6720/Secret/refs/heads/Functions/pornhub%20page%20format%20gui%200.5%20size"))()
	DeviceUsing = "Mobile"
    writefile(DHV2D,"Mobile")
	for i,v in pairs(player.PlayerGui:GetChildren()) do
		if v.Name == "ScreenGuiD" then
			v:Destroy()
		end
	end
end
TextButton_2.MouseButton1Click:connect(Mobile)	
TextButton_2Text.MouseButton1Click:connect(Mobile)

TextButton_3.Parent = Frame
TextButton_3.Name = "Button"
TextButton_3.BackgroundTransparency = 1
TextButton_3.Position = UDim2.new(0.075, 0, 0.75, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Size = UDim2.new(0, 186, 0, 30)
TextButton_3.ZIndex = 2
TextButton_3.Image = "rbxassetid://5028857472"
TextButton_3.ImageColor3 = Color3.fromRGB(41, 41, 41)
TextButton_3.ScaleType = Enum.ScaleType.Slice
TextButton_3.SliceCenter = Rect.new(2, 2, 298, 298)

TextButton_3Text.Parent = TextButton_3
TextButton_3Text.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
TextButton_3Text.BackgroundTransparency = 1
TextButton_3Text.ZIndex = 3
TextButton_3Text.Size = UDim2.new(0, 186, 0, 30)
TextButton_3Text.Font = Enum.Font.TitilliumWeb
TextButton_3Text.Text = "Auto Starting in 5"
TextButton_3Text.TextColor3 = Color3.fromRGB(200, 200, 200)
TextButton_3Text.TextScaled = true
TextButton_3Text.TextSize = 40.000
TextButton_3Text.TextWrapped = true
function AutoStart()
    if TextButton_3.ImageColor3 == Color3.fromRGB(41, 41, 41) then
        TextButton_3.ImageColor3 = Color3.fromRGB(82, 82, 82)
        local timer = 5
        TextButton_3Text.Text = "Auto Starting in 5"
        repeat task.wait(1) timer = timer -1 TextButton_3Text.Text = "Auto Starting in " .. timer until (TextButton_3.ImageColor3 == Color3.fromRGB(41, 41, 41) or timer < 1)
        if TextButton_3.ImageColor3 ~= Color3.fromRGB(41, 41, 41) and player.PlayerGui:FindFirstChild("ScreenGuiD") then
            TextButton_3Text.Text = "Starting"
            task.wait()
            if readfile(DHV2D) == "PC" then PC() elseif readfile(DHV2D) == "Mobile" then Mobile() else writefile(DHV2D,"PC") end
        end
    else
        TextButton_3.ImageColor3 = Color3.fromRGB(41, 41, 41)
    end
    
end
TextButton_3.MouseButton1Click:connect(AutoStart)	
TextButton_3Text.MouseButton1Click:connect(AutoStart)
if TextButton_3.ImageColor3 == Color3.fromRGB(41, 41, 41) then
    AutoStart()
end

repeat task.wait(.5) until DogeHubV2GUI ~= nil

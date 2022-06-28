
-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local FrameScripts = Instance.new("Frame")
local WalkSpeed = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextBox = Instance.new("TextBox")
local UICorner_2 = Instance.new("UICorner")
local SpectateFrame = Instance.new("Frame")
local Prev = Instance.new("TextButton")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local Next = Instance.new("TextButton")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local Status = Instance.new("ImageLabel")
local TextLabel_2 = Instance.new("TextLabel")
local CurrentPlayer = Instance.new("TextLabel")
local Toggle = Instance.new("TextButton")
local soon = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local Infyield = Instance.new("TextButton")
local X = Instance.new("TextButton")
local Open = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderColor3 = Color3.fromRGB(255, 0, 0)
Frame.BorderSizePixel = 3
Frame.Position = UDim2.new(0.271786511, 0, 0.316318065, 0)
Frame.Size = UDim2.new(0, 302, 0, 181)
Frame.Active = true
Frame.Draggable = true

FrameScripts.Name = "FrameScripts"
FrameScripts.Parent = Frame
FrameScripts.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
FrameScripts.BorderColor3 = Color3.fromRGB(255, 0, 0)
FrameScripts.BorderSizePixel = 2
FrameScripts.Position = UDim2.new(0.0687751994, 0, 0.263421655, 0)
FrameScripts.Size = UDim2.new(0, 260, 0, 117)

WalkSpeed.Name = "WalkSpeed"
WalkSpeed.Parent = FrameScripts
WalkSpeed.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
WalkSpeed.BorderColor3 = Color3.fromRGB(255, 0, 0)
WalkSpeed.BorderSizePixel = 2
WalkSpeed.Position = UDim2.new(0.0467718244, 0, 0.40164572, 0)
WalkSpeed.Size = UDim2.new(0.560379922, 0, 0.527514219, 0)

TextButton.Parent = WalkSpeed
TextButton.BackgroundColor3 = Color3.fromRGB(25, 255, 0)
TextButton.Position = UDim2.new(0.3234604, 0, 0.695746005, 0)
TextButton.Size = UDim2.new(0.343825668, 0, 0.172661871, 0)
TextButton.Font = Enum.Font.Cartoon
TextButton.Text = "Set"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner.Parent = TextButton

TextLabel.Parent = WalkSpeed
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Size = UDim2.new(1, 0, 0.179856122, 0)
TextLabel.Font = Enum.Font.Cartoon
TextLabel.Text = "Set Walk Speed"
TextLabel.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextBox.Parent = WalkSpeed
TextBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox.Position = UDim2.new(0.256658584, 0, 0.323741019, 0)
TextBox.Size = UDim2.new(0.484261513, 0, 0.179856122, 0)
TextBox.Font = Enum.Font.Cartoon
TextBox.PlaceholderText = "Enter Walk Speed"
TextBox.Text = "16"
TextBox.TextColor3 = Color3.fromRGB(97, 97, 97)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true

UICorner_2.Parent = TextBox

SpectateFrame.Name = "SpectateFrame"
SpectateFrame.Parent = FrameScripts
SpectateFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SpectateFrame.BackgroundTransparency = 1.000
SpectateFrame.Position = UDim2.new(-0.443044335, 0, 0.00854713935, 0)
SpectateFrame.Size = UDim2.new(1.93490994, 0, 1.94780791, 0)
SpectateFrame.Visible = false

Prev.Name = "Prev"
Prev.Parent = SpectateFrame
Prev.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Prev.BorderColor3 = Color3.fromRGB(255, 0, 0)
Prev.BorderSizePixel = 5
Prev.Position = UDim2.new(0.200000003, 0, 0.75, 0)
Prev.Size = UDim2.new(0.100000001, 0, 0.100000001, 0)
Prev.Font = Enum.Font.GothamBold
Prev.Text = "<"
Prev.TextColor3 = Color3.fromRGB(255, 0, 0)
Prev.TextScaled = true
Prev.TextSize = 14.000
Prev.TextWrapped = true

UIAspectRatioConstraint.Parent = Prev

Next.Name = "Next"
Next.Parent = SpectateFrame
Next.AnchorPoint = Vector2.new(1, 0)
Next.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Next.BorderColor3 = Color3.fromRGB(255, 0, 0)
Next.BorderSizePixel = 5
Next.Position = UDim2.new(0.800000012, 0, 0.75, 0)
Next.Size = UDim2.new(0.100000001, 0, 0.100000001, 0)
Next.Font = Enum.Font.GothamBold
Next.Text = ">"
Next.TextColor3 = Color3.fromRGB(255, 0, 0)
Next.TextScaled = true
Next.TextSize = 14.000
Next.TextWrapped = true

UIAspectRatioConstraint_2.Parent = Next

Status.Name = "Status"
Status.Parent = SpectateFrame
Status.Active = true
Status.AnchorPoint = Vector2.new(0.5, 0.5)
Status.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Status.BackgroundTransparency = 1.000
Status.BorderSizePixel = 5
Status.Position = UDim2.new(0.5, 0, 0.800000012, 0)
Status.Selectable = true
Status.Size = UDim2.new(0.449999988, 0, 0.119999997, 0)
Status.Image = "rbxassetid://3570695787"
Status.ImageTransparency = 0.500
Status.ScaleType = Enum.ScaleType.Slice
Status.SliceCenter = Rect.new(100, 100, 100, 100)
Status.SliceScale = 0.080

TextLabel_2.Parent = Status
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Size = UDim2.new(1, 0, 0.25, 0)
TextLabel_2.Font = Enum.Font.GothamBold
TextLabel_2.Text = "CURRENTLY WATCHING"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

CurrentPlayer.Name = "CurrentPlayer"
CurrentPlayer.Parent = Status
CurrentPlayer.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
CurrentPlayer.BackgroundTransparency = 1.000
CurrentPlayer.Position = UDim2.new(0, 0, 0.25, 0)
CurrentPlayer.Size = UDim2.new(1, 0, 0.75, 0)
CurrentPlayer.Font = Enum.Font.GothamBold
CurrentPlayer.Text = "Player"
CurrentPlayer.TextColor3 = Color3.fromRGB(0, 0, 0)
CurrentPlayer.TextScaled = true
CurrentPlayer.TextSize = 14.000
CurrentPlayer.TextWrapped = true

Toggle.Name = "Toggle"
Toggle.Parent = FrameScripts
Toggle.AnchorPoint = Vector2.new(0, 0.5)
Toggle.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Toggle.BorderColor3 = Color3.fromRGB(255, 0, 0)
Toggle.BorderSizePixel = 3
Toggle.Position = UDim2.new(0.647082746, 10, 0.235762388, 0)
Toggle.Size = UDim2.new(0.273621321, 0, 0.227166489, 0)
Toggle.Font = Enum.Font.GothamBold
Toggle.Text = "Spy"
Toggle.TextColor3 = Color3.fromRGB(255, 0, 0)
Toggle.TextScaled = true
Toggle.TextSize = 14.000
Toggle.TextWrapped = true

soon.Name = "soon"
soon.Parent = FrameScripts
soon.AnchorPoint = Vector2.new(0.5, 0.5)
soon.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
soon.BackgroundTransparency = 0.600
soon.BorderColor3 = Color3.fromRGB(255, 0, 0)
soon.BorderSizePixel = 3
soon.Position = UDim2.new(0.26630196, 0, 0.218333721, 0)
soon.Size = UDim2.new(0, 99, 0, 21)
soon.Font = Enum.Font.SourceSans
soon.Text = "Coming Soon!"
soon.TextColor3 = Color3.fromRGB(255, 0, 0)
soon.TextScaled = true
soon.TextSize = 14.000
soon.TextStrokeTransparency = 0.000
soon.TextWrapped = true

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_3.Position = UDim2.new(0.243377477, 0, 0.0462287329, 0)
TextLabel_3.Size = UDim2.new(0, 153, 0, 22)
TextLabel_3.Font = Enum.Font.SciFi
TextLabel_3.Text = "Spy X"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_3.TextSize = 24.000

TextLabel_4.Parent = Frame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_4.Position = UDim2.new(0.242946595, 0, 0.208336681, 0)
TextLabel_4.Size = UDim2.new(0, 152, 0, 17)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Hmmm What Script You Need?"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_4.TextSize = 14.000

Infyield.Name = "Inf yield"
Infyield.Parent = Frame
Infyield.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Infyield.BorderColor3 = Color3.fromRGB(255, 0, 0)
Infyield.BorderSizePixel = 3
Infyield.Position = UDim2.new(0.662891507, 0, 0.638955653, 0)
Infyield.Size = UDim2.new(0, 70, 0, 34)
Infyield.Font = Enum.Font.SciFi
Infyield.Text = "Infinite Yield"
Infyield.TextColor3 = Color3.fromRGB(255, 0, 0)
Infyield.TextSize = 13.000

X.Name = "X"
X.Parent = Frame
X.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
X.BorderColor3 = Color3.fromRGB(0, 0, 0)
X.Position = UDim2.new(0.872516572, 0, 0.0193370171, 0)
X.Size = UDim2.new(0, 33, 0, 30)
X.Font = Enum.Font.Roboto
X.Text = "X"
X.TextColor3 = Color3.fromRGB(255, 0, 0)
X.TextScaled = true
X.TextSize = 14.000
X.TextWrapped = true

Open.Name = "Open"
Open.Parent = ScreenGui
Open.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Open.BorderColor3 = Color3.fromRGB(255, 0, 0)
Open.BorderSizePixel = 2
Open.Position = UDim2.new(0, 0, 0.350886822, 0)
Open.Size = UDim2.new(0, 46, 0, 42)
Open.Font = Enum.Font.SciFi
Open.Text = "P"
Open.TextColor3 = Color3.fromRGB(255, 0, 0)
Open.TextSize = 46.000

-- Scripts:

local function JQJN_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		wait(0.06)
		script.Parent.Parent.Visible = true
		game.Players.LocalPlayer.character.Humanoid.WalkSpeed = script.Parent.Parent.TextBox.Text
	end)
	
	
end
coroutine.wrap(JQJN_fake_script)()
local function FOMK_fake_script() -- WalkSpeed.LocalScript 
	local script = Instance.new('LocalScript', WalkSpeed)

	local Frame = script.Parent
	
	Frame.Active = true
	
end
coroutine.wrap(FOMK_fake_script)()
local function RXCEH_fake_script() -- FrameScripts.LocalScript 
	local script = Instance.new('LocalScript', FrameScripts)

	local toggle = script.Parent.Toggle
	local frame = script.Parent.SpectateFrame
	local previous = frame.Prev
	local next = frame.Next
	local status = frame.Status.CurrentPlayer
	local camera = game.Workspace.CurrentCamera
	local num = 1
	
	status.Text = game.Players.LocalPlayer.Name
	
	toggle.MouseButton1Click:Connect(function()
		frame.Visible = not frame.Visible
	end)
	
	previous.MouseButton1Click:Connect(function()
		local players = game.Players:GetChildren()
		local max = #players
		num = num - 1
		if num < 1 then
			num = max
		end
		local player = players[num]
		camera.CameraSubject = player.Character.Humanoid
		status.Text = player.Name
	end)
	
	next.MouseButton1Click:Connect(function()
		local players = game.Players:GetChildren()
		local max = #players
		num = num + 1
		if num > max then
			num = 1
		end
		local player = players[num]
		camera.CameraSubject = player.Character.Humanoid
		status.Text = player.Name
	end)
	
	frame.Changed:Connect(function()
		if not frame.Visible then
			camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
			status.Text = game.Players.LocalPlayer.Name
		end
	end)
end
coroutine.wrap(RXCEH_fake_script)()
local function EJNOT_fake_script() -- TextLabel_4.LocalScript 
	local script = Instance.new('LocalScript', TextLabel_4)

	TextLabel_4 = "Hmmm What Script You Need?" --The words that are animated
	
	for i = 1,#TextLabel_4 do
		script.Parent.Text = string.sub(TextLabel_4,1,i)
		wait(0.05) -- the time each words get typed in
	end wait(9999999) script.Parent.Visible = false
end
coroutine.wrap(EJNOT_fake_script)()
local function TBHWRBD_fake_script() -- X.LocalScript 
	local script = Instance.new('LocalScript', X)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(TBHWRBD_fake_script)()
local function BKIGEA_fake_script() -- Open.LocalScript 
	local script = Instance.new('LocalScript', Open)

	local frame = script.Parent.Parent.Frame  -- change “Test” to the name of the frane
	local open = false
	
	script.Parent.MouseButton1Click:Connect(function()
		if frame.Visible == false then
			frame.Visible = true
		end
	end)
	
end
coroutine.wrap(BKIGEA_fake_script)()

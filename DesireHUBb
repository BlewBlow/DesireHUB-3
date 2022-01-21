local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("Desire Hub", "BloodTheme")

local Main = Window:NewTab("Main Tab!")
local Main = Main:NewSection("Main Tab!")
local Combat = Window:NewTab("Combat Tab!")
local Combat = Combat:NewSection("Combat Tab!")
local Teleports = Window:NewTab("Teleports!")
local Teleports = Teleports:NewSection("Teleports!")
local Autofarm = Window:NewTab("Autofarm!")
local Autofarm = Autofarm:NewSection("Autofarm!")
local Autobuy = Window:NewTab("Autobuy!")
local Autobuy = Autobuy:NewSection("Autobuy!")
local Animations = Window:NewTab("Animations!")
local Animations = Animations:NewSection("Animations!")
local Featured = Window:NewTab("Featured!")
local Featured = Featured:NewSection("Featured!")
local Extras = Window:NewTab("Extras!")
local Extras = Extras:NewSection("Extras!")
local Credits = Window:NewTab("Credits!")
local Credits = Credits:NewSection("Credits!")

Main:NewButton("Fly!", "X To Toggle!", function()
loadstring(game:HttpGet("https://pastebin.com/raw/bMR7KE6k"))()
end)
Main:NewButton("Speed", "", function()
			game.Players.LocalPlayer.Character.Humanoid.Name = "Humz"
			game.Players.LocalPlayer.Character.Humz.WalkSpeed = 100
end)
Main:NewButton("JumpPower", "Only Works If Speed Isn't Executed.", function()
			game.Players.LocalPlayer.Character.Humz.Name = "Humz"
			game.Players.LocalPlayer.Character.Humz.JumpPower = 140
end)
Main:NewButton("Anti Slow", "Keybind is B.", function()
			game.Players.LocalPlayer.Character.Humanoid.Name = "Humz"
			game.Players.LocalPlayer.Character.Humz.WalkSpeed = 16
			game.Players.LocalPlayer.Character.Humz.JumpPower = 50
end)
Main:NewButton("God Armor", "Unban 1st.", function()
local ps = game:GetService("Players")
	local lp = ps.LocalPlayer
	local char = lp.Character

	char.BodyEffects.Armor:Destroy()
	char.BodyEffects.Defense:Destroy()

	local Clone1 = Instance.new("IntValue")
	Clone1.Name = "Armor"
	Clone1.Parent = char.BodyEffects

	local Clone2 = Instance.new("NumberValue")
	Clone2.Name = "Defense"
	Clone2.Parent = char.BodyEffects
end)
Main:NewButton("God Block", "Unban 1st.", function()
gsPlayers = game:GetService("Players")
	gsWorkspace = game:GetService("Workspace")
	gsLighting = game:GetService("Lighting")
	gsReplicatedStorage = game:GetService("ReplicatedStorage")
	gsCoreGui = game:GetService("CoreGui")
	gsTween = game:GetService("TweenService")
	gsHttp = game:GetService("HttpService")

	LP = gsPlayers.LocalPlayer
	Mouse = LP:GetMouse()

	repeat wait() until LP.Character:FindFirstChild("BodyEffects")


	for i,v in ipairs(LP.Character:GetDescendants()) do
		if v.Name == "Christmas_Sock" then v:Destroy()
		end
	end

	LP.Character.ChildAdded:Connect(function()
		wait(0.3)
		for i,v in ipairs(LP.Character:GetDescendants()) do
			if v.Name == "Christmas_Sock" then v:Destroy()
			end
		end
	end)


	if LP.Character.BodyEffects:FindFirstChild("Defense") then
		LP.Character.BodyEffects.Defense:Destroy()
		local fucker = Instance.new("NumberValue",LP.Character.BodyEffects)
		fucker.Name = "Defense"
	end

	LP.CharacterAdded:Connect(function()
		repeat wait(0) until LP.Character:FindFirstChild("BodyEffects")
		repeat wait(0) until LP.Character.BodyEffects:FindFirstChild("Defense")
		repeat wait(0) until LP.Backpack:FindFirstChild("Combat")
		repeat wait(0) until LP.Character.BodyEffects:FindFirstChild("Dead")
		repeat wait(0) until LP.Character.BodyEffects:FindFirstChild("SpecialParts")

		LP.Character.ChildAdded:Connect(function()
			wait(0.3)
			for i,v in ipairs(LP.Character:GetDescendants()) do
				if v.Name == "Christmas_Sock" then v:Destroy()
				end
			end
		end)

		if LP.Character.BodyEffects:FindFirstChild("Defense") then
			LP.Character.BodyEffects.Defense:Destroy()
			local fucker = Instance.new("NumberValue",LP.Character.BodyEffects)
			fucker.Name = "Defense"
		end
end)
end)
Main:NewButton("Naked", "", function()
local function inTable(What, Table)
		for Index, Value in pairs(Table) do
			if What == Value then
				return true
			end
		end
		return false
	end

	local removingClasses = {
		"Pants",
		"Shirt",
	}

	for _, Instance in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
		if inTable(Instance.ClassName, removingClasses) or Instance.Name == "" then
			Instance:Destroy()
		end
	end
end)
Main:NewButton("Anonymous", "", function()
game.Players.LocalPlayer.Character.RightUpperLeg:Destroy()
game.Players.LocalPlayer.Character.LeftUpperLeg:Destroy()
wait(.2)
local function inTable(What, Table)
		for Index, Value in pairs(Table) do
			if What == Value then
				return true
			end
		end
		return false
	end

	local removingClasses = {
		"Pants",
		"Shirt",
		"Accessory",
	}

	for _, Instance in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
		if inTable(Instance.ClassName, removingClasses) or Instance.Name == "face" then
			Instance:Destroy()
		end
	end
end)
Main:NewButton("Anti Grab", "", function()
while wait() do
		pcall(function()
			local LocalPlayer = game:GetService("Players").LocalPlayer
			local char = LocalPlayer.Character
			if game.Players.LocalPlayer.Character["GRABBING_CONSTRAINT"] then
				game.Players.LocalPlayer.Character["GRABBING_CONSTRAINT"]:Destroy()
			end
		end)
	end
end)
Main:NewButton("Anti Bag", "", function()
while wait() do
		pcall(function()
			game:GetService("Players").LocalPlayer.Character:FindFirstChild("Christmas_Sock"):Destroy()
		end)
	end
end)
Main:NewButton("Anti Flash", "", function()
while wait() do
		pcall(function()
			game:GetService("Players").LocalPlayer.PlayerGui:FindFirstChild("MainScreenGui"):FindFirstChild("whiteScreen"):Destroy()
		end)
	end
end)
Main:NewButton("Anti Lock", "Keybind is C.", function()
loadstring(game:HttpGet("https://pastebin.com/raw/4SQ2W1Ja"))()
end)
Main:NewButton("Anti Equipment", "", function()
while wait() do
		for _, v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
			if v:IsA("Tool") then
				v.Parent = game:GetService("Players").LocalPlayer.Backpack
			end
		end
	end
end)
Main:NewButton("Bike Fly", "", function()
	local speed = 20
	local old
	local Plr = game.Players.LocalPlayer
	local wheels = {}
	local control = {q=false,e=false,w=false,a=false,s=false,d=false}
	local Mouse = Plr:GetMouse()

	Mouse.KeyDown:connect(function(KEY)
		local key = KEY:lower()
		if control[key] ~= nil then
			control[key]=true
		end
	end)

	Mouse.KeyUp:connect(function(KEY)
		local key = KEY:lower()
		if control[key] ~= nil then
			control[key]=false
		end
	end)

	while game.RunService.Stepped:wait() do
		local seat = (Plr.Character or Plr.CharacterAdded:wait()):WaitForChild("Humanoid").SeatPart
		if Plr.PlayerGui:FindFirstChild("MainScreenGui") and Plr.PlayerGui.MainScreenGui:FindFirstChild("Bar") and Plr.PlayerGui.MainScreenGui.Bar:FindFirstChild("Speed") then
			Plr.PlayerGui.MainScreenGui.Bar.Speed.bar.Size = UDim2.new(speed / 100 * 0.95, 0, 0.83, 0)
		else
			local c = Plr.PlayerGui.MainScreenGui.Bar.HP
			local g = c:Clone()
			g.Name = "Speed"
			g.Position = UDim2.new(0.5, 0, 1, -120)
			g.bar.BackgroundColor3 = Color3.fromRGB(255, 155, 0)
			g.Picture.Image.Image = "rbxassetid://181035717"
			g.TextLabel.Text = "Speed"
			g.Parent = c.Parent
		end
		if seat ~= nil and seat:IsDescendantOf(game.Workspace.Vehicles) then
			if seat ~= old then
				if old then
					old.Vel:Destroy()
					old.Gyro:Destroy()
				end
				old = seat
				for i = 1, 2 do
					if wheels[i] then
						wheels[i][2].Parent = wheels[i][1]
					end
					local wheel = seat.Parent.Wheel
					wheels[i] = {seat.Parent, wheel}
					wheel:remove()
				end
				local gyro = Instance.new("BodyGyro", seat)
				gyro.Name = "Gyro"
				local pos = Instance.new("BodyVelocity", seat)
				pos.Name = "Vel"
				gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
				pos.MaxForce = Vector3.new(9e9, 9e9, 9e9)
			else 
				seat.Gyro.cframe = workspace.CurrentCamera.CoordinateFrame
				local vel = CFrame.new(0, 0, 0)
				if control.w then
					vel = vel * CFrame.new(0, 0, -speed)
				end
				if control.s then
					vel = vel * CFrame.new(0, 0, speed)
				end
				if control.a then
					vel = vel * CFrame.new(-speed, 0, 0)
				end
				if control.d then
					vel = vel * CFrame.new(speed, 0, 0)
				end
				seat.Vel.Velocity = (seat.CFrame*vel).p - seat.CFrame.p
			end
		end
		if control.e and speed<100 then
			speed = speed + 1
		end
		if control.q and speed > 0 then
			speed = speed - 1
		end
	end
end)
Main:NewButton("Headless!", "", function()
pcall(function()
		game.Players.LocalPlayer.Character.Head.Neck:Destroy()
		game.Players.LocalPlayer.Character.UpperTorso.NeckAttachment:Destroy()
		game.Players.LocalPlayer.Character.Humanoid.HealthDisplayDistance = math.huge
		game.Players.LocalPlayer.Character.Humanoid.NameDisplayDistance = math.huge
		game.Players.LocalPlayer.Character.Head.Size = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Character.Head.Massless = true
		game.Players.LocalPlayer.Character.Head.CanCollide = false

		heazd = true

		while heazd == true do 
			pcall(function()  
				game.Players.LocalPlayer.Character.Head.NeckRigAttachment.CFrame = CFrame.new(0, 100000.4736328125, 0)
				game.Players.LocalPlayer.Character.UpperTorso.NeckRigAttachment.CFrame = CFrame.new(0, 100000.4736328125, 0)
				game.Players.LocalPlayer.Character.Head.CFrame = CFrame.new(0, 100000.4736328125, 0)
			end)
			wait()
		end
	end)
end)
Main:NewButton("Free Korblox!", "", function()
game:GetService("Players").LocalPlayer.Character.RightUpperLeg:Destroy()
end)
Main:NewButton("Free Animation Gamepass", "P To Toggle!", function()
	-- // Delete Clones
	for _, v in next, game:GetService("CoreGui"):GetChildren() do
		if (v.Name:match("FreeAnimationPack")) then
			v:Destroy()
		end
	end

	-- // Instances
	local FreeAnimationPack = Instance.new("ScreenGui")
	local AnimationPack = Instance.new("TextButton")
	local Animations = Instance.new("ScrollingFrame")
	local UIListLayout = Instance.new("UIListLayout")
	local Lean = Instance.new("TextButton")
	local Lay = Instance.new("TextButton")
	local Dance1 = Instance.new("TextButton")
	local Dance2 = Instance.new("TextButton")
	local Greet = Instance.new("TextButton")
	local ChestPump = Instance.new("TextButton")
	local Praying = Instance.new("TextButton")
	local Stop = Instance.new("TextButton")
	local UniversalAnimation = Instance.new("Animation")

	-- // Utility
	function stopTracks()
		for _, v in next, game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid"):GetPlayingAnimationTracks() do
			if (v.Animation.AnimationId:match("rbxassetid")) then
				v:Stop()
			end
		end
	end

	function loadAnimation(id)
		if UniversalAnimation.AnimationId == id then
			stopTracks()
			UniversalAnimation.AnimationId = "1"
		else
			UniversalAnimation.AnimationId = id
			local animationTrack = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid"):LoadAnimation(UniversalAnimation)
			animationTrack:Play()
		end
	end

	-- // Properties
	FreeAnimationPack.Name = "FreeAnimationPack"
	FreeAnimationPack.Parent = game.CoreGui
	FreeAnimationPack.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

	AnimationPack.Name = "AnimationPack"
	AnimationPack.Parent = FreeAnimationPack
	AnimationPack.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	AnimationPack.BorderSizePixel = 0
	AnimationPack.Position = UDim2.new(0, 0, 0.388007045, 0)
	AnimationPack.Size = UDim2.new(0, 100, 0, 20)
	AnimationPack.Font = Enum.Font.SourceSansBold
	AnimationPack.Text = "Animations"
	AnimationPack.TextColor3 = Color3.fromRGB(0, 0, 0)
	AnimationPack.TextSize = 18.000
	AnimationPack.MouseButton1Click:Connect(function()
		if (Animations.Visible == false) then
			Animations.Visible = true
		end
	end)

	Animations.Name = "Animations"
	Animations.Parent = AnimationPack
	Animations.Active = true
	Animations.BackgroundColor3 = Color3.fromRGB(102, 102, 102)
	Animations.Position = UDim2.new(-0.104712225, 0, -1.54173493, 0)
	Animations.Size = UDim2.new(0, 120, 0, 195)
	Animations.Visible = false
	Animations.CanvasPosition = Vector2.new(0, 60.0000305)
	Animations.CanvasSize = UDim2.new(0, 0, 1, 235)

	UIListLayout.Parent = Animations
	UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
	UIListLayout.Padding = UDim.new(0, 2)

	Lean.Name = "Lean"
	Lean.Parent = Animations
	Lean.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Lean.Size = UDim2.new(1, 0, 0, 30)
	Lean.Font = Enum.Font.SourceSansBold
	Lean.Text = "Lean"
	Lean.TextColor3 = Color3.fromRGB(0, 0, 0)
	Lean.TextSize = 14.000
	Lean.MouseButton1Click:Connect(function()
		stopTracks()
		loadAnimation("rbxassetid://3152375249")
	end)

	Lay.Name = "Lay"
	Lay.Parent = Animations
	Lay.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Lay.Size = UDim2.new(1, 0, 0, 30)
	Lay.Font = Enum.Font.SourceSansBold
	Lay.Text = "Lay"
	Lay.TextColor3 = Color3.fromRGB(0, 0, 0)
	Lay.TextSize = 14.000
	Lay.MouseButton1Click:Connect(function()
		stopTracks()
		loadAnimation("rbxassetid://3152378852")
	end)

	Dance1.Name = "Dance1"
	Dance1.Parent = Animations
	Dance1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Dance1.Size = UDim2.new(1, 0, 0, 30)
	Dance1.Font = Enum.Font.SourceSansBold
	Dance1.Text = "Dance1"
	Dance1.TextColor3 = Color3.fromRGB(0, 0, 0)
	Dance1.TextSize = 14.000
	Dance1.MouseButton1Click:Connect(function()
		stopTracks()
		loadAnimation("rbxassetid://3189773368")
	end)

	Dance2.Name = "Dance2"
	Dance2.Parent = Animations
	Dance2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Dance2.Size = UDim2.new(1, 0, 0, 30)
	Dance2.Font = Enum.Font.SourceSansBold
	Dance2.Text = "Dance2"
	Dance2.TextColor3 = Color3.fromRGB(0, 0, 0)
	Dance2.TextSize = 14.000
	Dance2.MouseButton1Click:Connect(function()
		stopTracks()
		loadAnimation("rbxassetid://3189776546")
	end)

	Greet.Name = "Greet"
	Greet.Parent = Animations
	Greet.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Greet.Size = UDim2.new(1, 0, 0, 30)
	Greet.Font = Enum.Font.SourceSansBold
	Greet.Text = "Greet"
	Greet.TextColor3 = Color3.fromRGB(0, 0, 0)
	Greet.TextSize = 14.000
	Greet.MouseButton1Click:Connect(function()
		stopTracks()
		loadAnimation("rbxassetid://3189777795")
	end)

	ChestPump.Name = "ChestPump"
	ChestPump.Parent = Animations
	ChestPump.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	ChestPump.Size = UDim2.new(1, 0, 0, 30)
	ChestPump.Font = Enum.Font.SourceSansBold
	ChestPump.Text = "Chest Pump"
	ChestPump.TextColor3 = Color3.fromRGB(0, 0, 0)
	ChestPump.TextSize = 14.000
	ChestPump.MouseButton1Click:Connect(function()
		stopTracks()
		loadAnimation("rbxassetid://3189779152")
	end)

	Praying.Name = "Praying"
	Praying.Parent = Animations
	Praying.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Praying.Size = UDim2.new(1, 0, 0, 30)
	Praying.Font = Enum.Font.SourceSansBold
	Praying.Text = "Praying"
	Praying.TextColor3 = Color3.fromRGB(0, 0, 0)
	Praying.TextSize = 14.000
	Praying.MouseButton1Click:Connect(function()
		stopTracks()
		loadAnimation("rbxassetid://3487719500")
	end)

	Stop.Name = "Stop"
	Stop.Parent = Animations
	Stop.BackgroundColor3 = Color3.fromRGB(255, 112, 112)
	Stop.Size = UDim2.new(1, 0, 0, 30)
	Stop.Font = Enum.Font.SourceSansBold
	Stop.Text = "Stop Animation"
	Stop.TextColor3 = Color3.fromRGB(0, 0, 0)
	Stop.TextSize = 14.000
	Stop.MouseButton1Click:Connect(function()
		stopTracks()
	end)
	--scripts
	local plr = game.Players.LocalPlayer

	plr:GetMouse().KeyDown:Connect(function(K)
		if K == "p" then
			Animations.Visible = false
		end
	end)
end)
Main:NewButton("Q To Tp", "", function()
getgenv().TP = true
    getgenv().Mouse = game:GetService("Players").LocalPlayer:GetMouse()
    
    function Notification(text)
        game:GetService("StarterGui"):SetCore("SendNotification",{
          Title = "Da Hood",
          Text = text,
          Icon = "rbxassetid://0",
          Duration = 3,
        })
    end
    
    
    Mouse.KeyDown:Connect(function(Key)
        if Key == "q" then
          if getgenv().TP == true then
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Mouse.hit.p.X, Mouse.hit.p.Y, Mouse.hit.p.Z)
          end
        end
    end)
end)
Main:NewButton("Fog", "", function()
game:GetService("Lighting").FogEnd = math.huge
end)
Main:NewButton("Unjail!", "", function()
if game:GetService("Players").LocalPlayer.DataFolder.Currency.Value >= 125 then
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-270.94, 20.327, -242.38)
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-270.94, 20.327, -242.38)
		wait()
		fireclickdetector(game:GetService("Workspace").Ignored.Shop["[Key] - $125"].ClickDetector)
		wait(.1)
		fireclickdetector(game:GetService("Workspace").Ignored.Shop["[Key] - $125"].ClickDetector)
		fireclickdetector(game:GetService("Workspace").Ignored.Shop["[Key] - $125"].ClickDetector)
		repeat
			wait()
		until game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("[Key]")
		local Hum = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
		if Hum.Health > 0 then
			key1 = game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("[Key]")
			if key1 then
				Hum:EquipTool(key1)
				for i, v in pairs(game:GetService"Players".LocalPlayer.Character:GetChildren()) do
					if v:isA("Tool") then
						game:GetService("Players").LocalPlayer.Character.Humanoid:EquipTool(key1)
						game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-485.668, 23.631, -285.169)
						v:Activate()
					end
				end
			end
		end
	end
end)
Main:NewButton("Unban!", "", function()
game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health = 0
game:GetService("Players").LocalPlayer.CharacterAdded:Connect(function()
    Instance.new("Folder",game:GetService("Players").LocalPlayer.Character).Name = ("FULLY_LOADED_CHAR")
    game:GetService("Players").LocalPlayer.Character:WaitForChild("BodyEffects"):WaitForChild("Dead"):Remove()
    Instance.new("BoolValue",game:GetService("Players").LocalPlayer.Character:WaitForChild("BodyEffects")).Name = ("Dead")
    repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("BodyEffects"):findFirstChild("Dead")
    game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):WaitForChild("BodyWidthScale").Value = 0.5
    game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):WaitForChild("HeadScale").Value = 1
    game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):WaitForChild("BodyHeightScale").Value = 1
    game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):WaitForChild("BodyDepthScale").Value = 0.5
    game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid"):WaitForChild("BodyTypeScale").Value = 0.01
end)
end)
Main:NewButton("Skinny Unban!", "", function()
game.Players.LocalPlayer.Character.Head:Destroy()
end)
Combat:NewButton("Free Fists", "Q To Toggle!", function()
-- // Variables
	local localPlayer       = game:GetService("Players").LocalPlayer
	local localCharacter    = localPlayer.Character
	local Mouse             = localPlayer:GetMouse()
	local FistControl       = false
	local LeftFist          = localCharacter.LeftHand
	local RightFist         = localCharacter.RightHand

	-- // Services
	local uis = game:GetService("UserInputService")

	-- // Coroutine Loop + Functions
	local loopFunction = function()
		LeftFist.CFrame  = CFrame.new(Mouse.Hit.p)
		RightFist.CFrame = CFrame.new(Mouse.Hit.p)
	end

	local Loop

	local Start = function()
		Loop = game:GetService("RunService").Heartbeat:Connect(loopFunction)
	end

	local Pause = function()
		Loop:Disconnect()
	end

	-- // Hotkeys
	uis.InputBegan:connect(function(Key)
		if (Key.KeyCode == Enum.KeyCode.Q) then
			if (FistControl == false) then
				FistControl = true
				Start()
				pcall(function()
					localCharacter.RightHand.RightWrist:Remove()
					localCharacter.LeftHand.LeftWrist:Remove()
				end)
			elseif (FistControl == true) then
				FistControl = false
				Pause()
				local rightwrist  = Instance.new("Motor6D")
				rightwrist.Name   = "RightWrist"
				rightwrist.Parent = localCharacter.RightHand
				rightwrist.C0     = CFrame.new(1.18422506e-07, -0.5009287, -6.81715525e-18, 1, 0, 0, 0, 1, 0, 0, 0, 1)
				rightwrist.C1     = CFrame.new(3.55267503e-07, 0.125045404, 5.92112528e-08, 1, 0, 0, 0, 1, 0, 0, 0, 1)
				rightwrist.Part0  = localCharacter.RightLowerArm
				rightwrist.Part1  = localCharacter.RightHand

				local leftwrist   = Instance.new("Motor6D")
				leftwrist.Name    = "LeftWrist"
				leftwrist.Parent  = localCharacter.LeftHand
				leftwrist.C0      = CFrame.new(0.000475466368, -0.5009287, 7.59417072e-20, 1, 0, 0, 0, 1, 0, 0, 0, 1)
				leftwrist.C1      = CFrame.new(0.000475821638, 0.125045404, 5.92112528e-08, 1, 0, 0, 0, 1, 0, 0, 0, 1)
				leftwrist.Part0   = localCharacter.LeftLowerArm
				leftwrist.Part1   = localCharacter.LeftHand
			end
		end
	end)
end)
Combat:NewButton("Tool Reach", "", function()
end)
Combat:NewButton("Auto Reload", "", function()
local sucess = nil
	while wait(0.5) do
		for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v:FindFirstChild("Ammo") and v.Ammo.Value ~= 0 then
				v.Parent = game.Players.LocalPlayer.Character
			end
		end
		for ii, vv in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if vv:FindFirstChild("Ammo") and vv.Ammo.Value == 0 then
				game.Players.LocalPlayer.Character.Humanoid:UnequipTools()
			end
		end
		for iii, vvv in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if vvv:FindFirstChild("Ammo") and vvv.Ammo.Value ~= 0 then 
				sucess = true
			end
		end
		if not sucess ==  true then
			for iiii, vvvv in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do 
				if vvvv:FindFirstChild("Ammo") and vvvv.Ammo.Value == 0 then
					game.Players.LocalPlayer.Character.Humanoid:UnequipTools()

					game.ReplicatedStorage.MainEvent:FireServer("Reload", vvvv)
					repeat wait() until vvvv.Ammo.Value ~= 0
				end
			end
		end
		sucess = nil
	end
end)
Combat:NewButton("No Recoil!", "", function()
while wait() do
		if game:GetService("Players").LocalPlayer.Character.BodyEffects.Reload.Value == true then
			game:GetService("Players").LocalPlayer.Character.BodyEffects.Reload.Value = false
		end
	end
end)
Combat:NewButton("Auto Block", "", function()
while wait() do
		game.ReplicatedStorage.MainEvent:FireServer("Block", true)
	end
end)
Combat:NewButton("Silent Block!", "Unban 1st.", function()
local ps = game:GetService("Players")
	local lp = ps.LocalPlayer
	local char = lp.Character

	char.BodyEffects.Armor:Destroy()
	char.BodyEffects.Defense:Destroy()

	local Clone1 = Instance.new("IntValue")
	Clone1.Name = "Armor"
	Clone1.Parent = char.BodyEffects

	local Clone2 = Instance.new("NumberValue")
	Clone2.Name = "Defense"
	Clone2.Parent = char.BodyEffects
	wait()
	while wait() do
		for _, v in next, game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid"):GetPlayingAnimationTracks() do
			if (v.Animation.AnimationId:match("rbxassetid://2788354405")) then
				v:Stop()
			end
		end
	end
	wait()
end)
Combat:NewButton("Aimbot", "", function()
local CC = game:GetService"Workspace".CurrentCamera
	local Plr
	local enabled = false
	local accomidationfactor = 0.165
	local mouse = game.Players.LocalPlayer:GetMouse()
	local placemarker = Instance.new("Part", game.Workspace)
	local guimain = Instance.new("Folder", game.CoreGui)

	function makemarker(Parent, Adornee, Color, Size, Size2)
		local e = Instance.new("BillboardGui", Parent)
		e.Name = "PP"
		e.Adornee = Adornee
		e.Size = UDim2.new(Size, Size2, Size, Size2)
		e.AlwaysOnTop = true
		local a = Instance.new("Frame", e)
		a.Size = UDim2.new(1, 0, 1, 0)
		a.BackgroundTransparency = 0.4
		a.BackgroundColor3 = Color
		local g = Instance.new("UICorner", a)
		g.CornerRadius = UDim.new(50, 50)
		return(e)
	end

	local data = game.Players:GetPlayers()
	function noob(player)
		local character
		repeat wait() until player.Character
		local handler = makemarker(guimain, player.Character:WaitForChild("Head"), Color3.fromRGB(255, 255, 255), 0.3, 3)
		handler.Name = player.Name
		player.CharacterAdded:connect(function(Char) handler.Adornee = Char:WaitForChild("Head") end)

		local TextLabel = Instance.new("TextLabel", handler)
		TextLabel.BackgroundTransparency = 1
		TextLabel.Position = UDim2.new(0, 0, 0, -50)
		TextLabel.Size = UDim2.new(0, 100, 0, 100)
		TextLabel.Font = Enum.Font.SourceSansSemibold
		TextLabel.TextSize = 14
		TextLabel.TextColor3 = Color3.new(1, 1, 1)
		TextLabel.TextStrokeTransparency = 0
		TextLabel.TextYAlignment = Enum.TextYAlignment.Bottom
		TextLabel.Text = "Name: "..player.Name
		TextLabel.ZIndex = 10

		spawn(function()
			while wait() do
				if player.Character then
					TextLabel.Text = player.Name.." | Bounty: "..tostring(player:WaitForChild("leaderstats").Wanted.Value).." | "..tostring(math.floor(player.Character:WaitForChild("Humanoid").Health))
				end
			end
		end)
	end

	for i = 1, #data do
		if data[i] ~= game.Players.LocalPlayer then
			noob(data[i])
		end
	end

	game.Players.PlayerAdded:connect(function(Player)
		noob(Player)
	end)

	spawn(function()
		placemarker.Anchored = true
		placemarker.CanCollide = false
		placemarker.Size = Vector3.new(0.1, 0.1, 0.1)
		placemarker.Transparency = 1
		makemarker(placemarker, placemarker, Color3.fromRGB(0, 0, 255), 0.15, 0)
	end)    

	local UserInputService = game:GetService"UserInputService"

	UserInputService.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton2 then
			enabled = true 
			Plr = getClosestPlayerToCursor()
			guimain[Plr.Name].Frame.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	end)

	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton2 then
			enabled = false
			guimain[Plr.Name].Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		end
	end)

	function getClosestPlayerToCursor()
		local closestPlayer
		local shortestDistance = math.huge

		for i, v in pairs(game.Players:GetPlayers()) do
			if v ~= game.Players.LocalPlayer and v.Character and v.Character:FindFirstChild("Humanoid") and v.Character.Humanoid.Health ~= 0 and v.Character:FindFirstChild("Head") then
				local pos = CC:WorldToViewportPoint(v.Character.PrimaryPart.Position)
				local magnitude = (Vector2.new(pos.X, pos.Y) - Vector2.new(mouse.X, mouse.Y)).magnitude
				if magnitude < shortestDistance then
					closestPlayer = v
					shortestDistance = magnitude
				end
			end
		end
		return closestPlayer
	end

	game:GetService"RunService".Stepped:connect(function()
		if enabled and Plr.Character and Plr.Character:FindFirstChild("Head") then
			placemarker.CFrame = CFrame.new(Plr.Character.Head.Position+(Plr.Character.Head.Velocity*accomidationfactor))
		else
			placemarker.CFrame = CFrame.new(0, 9999, 0)
		end
	end)

	local mt = getrawmetatable(game)
	local old = mt.__namecall
	setreadonly(mt, false)
	mt.__namecall = newcclosure(function(...)
		local args = {...}
		if enabled and getnamecallmethod() == "FireServer" and args[2] == "UpdateMousePos" then
			args[3] = Plr.Character.Head.Position+(Plr.Character.Head.Velocity*accomidationfactor)
			return old(unpack(args))
		end
		return old(...)
	end)
end)
Combat:NewButton("Auto Pick!", "", function()
	local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
	for h, i in pairs(game.Workspace.Ignored.ItemsDrop:GetChildren()) do
		if i.Name == "Part" then
			if i:FindFirstChild("[LockPicker]") or i:FindFirstChild("[Knife]") then
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = i.CFrame
				if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - i.Position).Magnitude <= 50 then
					wait()
				end
			end
		end
	end
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
end)
Combat:NewButton("Auto Armor!", "", function()
local PERCENT_TO_BUY_ARMOR   = 50         --\\ percent of armor left that u want to buy
local COMMAND_TO_STOP_BUYING = ('/e stop') --\\ message to stop buying

------------------------
------------------------

function announce(title,text,time)
    game.StarterGui:SetCore("SendNotification", {
        Title = title;
        Text = text;
        Duration = time;
    })
end


local Stopped = false
local Player = game.Players.LocalPlayer
function Main1()
    while wait() do
        local function AutoArmor()
            local Origin = Player.Character.HumanoidRootPart.CFrame
            local Armor = Player.Character.BodyEffects.Armor
            if Armor.Value <= PERCENT_TO_BUY_ARMOR and Stopped == false then
                repeat
                    wait()    
                    Player.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Ignored.Shop["[Medium Armor] - $1000"].Head.CFrame
                    fireclickdetector(game:GetService("Workspace").Ignored.Shop["[Medium Armor] - $1000"].ClickDetector)
                until Armor.Value == 100 or Player.DataFolder.Currency.Value < 1000
                Player.Character.HumanoidRootPart.CFrame = Origin
            end
        end
        local s,e = pcall(AutoArmor)
    end
end
function Main2()
    Player.Chatted:Connect(function(msg)
        if msg == COMMAND_TO_STOP_BUYING and Stopped == false then
            Stopped = true
            
        end
    end)
end
coroutine.resume(coroutine.create(Main1))
coroutine.resume(coroutine.create(Main2))
end)
Combat:NewButton("Split Granade", "V To Toggle!", function()
local plr = game.Players.LocalPlayer
	local lastpos = plr.Character.HumanoidRootPart.CFrame

	repeat wait()
		plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["[Grenade] - $700"].Head.CFrame
		fireclickdetector(game.Workspace.Ignored.Shop["[Grenade] - $700"].ClickDetector)
	until game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.V)
	plr.Character.HumanoidRootPart.CFrame = lastpos

	for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
		wait(0.05)
		spawn(function()
			if v.Name == "[Grenade]" then
				v.Parent = plr.Character v:Activate() wait(0.1) v:Deactivate() wait(0.1) v:Activate()
			end
		end)
	end
end)
Combat:NewButton("Katana", "Get Knifes!", function()
game.Players.LocalPlayer.Backpack["[Knife]"].GripPos = Vector3.new(1, 0, 0.1)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripForward = Vector3.new(0, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripRight = Vector3.new(0, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripUp = Vector3.new(-1, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character

	game.Players.LocalPlayer.Backpack["[Knife]"].GripPos = Vector3.new(2, 0, 0.1)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripForward = Vector3.new(0, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripRight = Vector3.new(0, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripUp = Vector3.new(-1, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character 

	game.Players.LocalPlayer.Backpack["[Knife]"].GripPos = Vector3.new(3, 0, 0.1)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripForward = Vector3.new(0, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripRight = Vector3.new(0, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripUp = Vector3.new(-1, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character 

	game.Players.LocalPlayer.Backpack["[Knife]"].GripPos = Vector3.new(4, 0, 0.1)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripForward = Vector3.new(0, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripRight = Vector3.new(0, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].GripUp = Vector3.new(-1, 0, 0)
	game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character 
end)
Combat:NewButton("Force Reset!", "", function()
game.Players.LocalPlayer.Character.LeftUpperArm:Destroy()
game.Players.LocalPlayer.Character.RightUpperArm:Destroy()
game.Players.LocalPlayer.Character.LeftUpperLeg:Destroy()
game.Players.LocalPlayer.Character.RightUpperLeg:Destroy()
game.Players.LocalPlayer.Character.Head:Destroy()
game.Players.LocalPlayer.Character.UpperTorso:Destroy()
game.Players.LocalPlayer.Character.HumanoidRootPart:Destroy()
game.Players.LocalPlayer.Character.LeftLowerArm:Destroy()
game.Players.LocalPlayer.Character.RightLowerArm:Destroy()
game.Players.LocalPlayer.Character.LeftLowerLeg:Destroy()
game.Players.LocalPlayer.Character.RightLowerLeg:Destroy()
game.Players.LocalPlayer.Character.LowerTorso:Destroy()
game.Players.LocalPlayer.Character.RightHand:Destroy()
game.Players.LocalPlayer.Character.LeftHand:Destroy()
game.Players.LocalPlayer.Character.RightFoot:Destroy()
game.Players.LocalPlayer.Character.LeftFoot:Destroy()
end)
Combat:NewButton("Tornado", "Get Knifes!", function()
game:GetService("Players").LocalPlayer.Backpack["[Knife]"].GripPos = Vector3.new(2, -5, -1.5)
		game:GetService("Players").LocalPlayer.Backpack["[Knife]"].GripForward = Vector3.new(0, 0, 0)
		game:GetService("Players").LocalPlayer.Backpack["[Knife]"].GripRight = Vector3.new(1, 0, -3)
		game:GetService("Players").LocalPlayer.Backpack["[Knife]"].GripUp = Vector3.new(0, 0, 0)
		game:GetService("Players").LocalPlayer.Backpack["[Knife]"].Parent = game:GetService("Players").LocalPlayer.Character
end)
Combat:NewButton("Fly Gun!", "Equip A Gun 1st.", function()
for _, v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
		if v:isA("Tool") then
			v.GripPos = Vector3.new(10,-10,10)
		end
	end
end)
Teleports:NewButton("Bank", "", function()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-485.668, 23.631, -285.169)
end)
Teleports:NewButton("Boxing Place", "", function()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)
end)
Teleports:NewButton("Police Station", "", function()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-267.637, 21.807, -121.982)
end)
Teleports:NewButton("Admin Base", "", function()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
end)
Teleports:NewButton("Sewers", "", function()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(112.622, -26.212, -277.321)
end)
Teleports:NewButton("Shoe Store", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(workspace.Ignored.Drop:FindFirstChildOfClass("MeshPart").Position)
end)
Teleports:NewButton("Hospital", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(86.518, 21.755, -481.680)
end)
Teleports:NewButton("Phone Store", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-120.121, 22.946, -870.425)
end)
Teleports:NewButton("Taco Shack", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(546.946, 51.061, -493.325)
end)
Teleports:NewButton("Casino", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-879.277, 21.254, -190.199)
end)
Teleports:NewButton("UFO", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.565, 142.926, -690.33)
end)
Teleports:NewButton("Fire Station", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-132.674, 21.280, -145.176)
end)
Teleports:NewButton("Gas Station", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(595.377, 49.000, -264.222)
end)
Teleports:NewButton("Church", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(203.938, 21.75, -98.446)
end)
Teleports:NewButton("Downhill Gunz", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-582, 7.172, -739.015)
end)
Teleports:NewButton("Uphill Gunz", "", function()
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(475.022, 48.005, -603.737)
end)
Autofarm:NewToggle("Autofarm!", "Using Private Server Would Be Smart.", function(state)
end)
for _, v in pairs(workspace.Ignored.Shop:GetChildren()) do
	Autobuy:NewButton(v.name, "", function()
		local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
		local k = game.Workspace.Ignored.Shop[v.Name]
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
		if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
			wait(.2)
			fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
		end
	end)
end
Animations:NewButton("Zombie", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
end)
Animations:NewButton("Werewolf", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"
end)
Animations:NewButton("Astronaut", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
end)
Animations:NewButton("Bubbly", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"
	Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"
	Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"
end)
Animations:NewButton("Cartoony", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
end)
Animations:NewButton("Elder", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=845397899"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"
end)
Animations:NewButton("Knight", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=657595757"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=657568135"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=657552124"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=657564596"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=658409194"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=658360781"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=657600338"
end)
Animations:NewButton("Levitation", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
end)
Animations:NewButton("Mage", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
end)
Animations:NewButton("Ninja", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
end)
Animations:NewButton("Pirate", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
end)
Animations:NewButton("Robot", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
end)
Animations:NewButton("Stylish", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
end)
Animations:NewButton("Superhero", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
end)
Animations:NewButton("Toy", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
end)
Animations:NewButton("Vampire", "", function()
	local Animate = game.Players.LocalPlayer.Character.Animate
	Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"
	Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"
	Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"
	Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"
	Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"
	Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"
	Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"
end)
Extras:NewButton("Play All Sounds! [FE]", "", function()
sounds = {}

	function getSounds(loc)
		if loc:IsA("Sound") then
			table.insert(sounds,loc)
		end
		for _,obj in pairs(loc:GetChildren()) do
			getSounds(obj)
		end
	end

	getSounds(game)

	game.DescendantAdded:connect(function(obj)
		if obj:IsA("Sound") then
			table.insert(sounds,obj)
		end
	end)

	while wait(0.2) do
		for _,sound in pairs(sounds) do
			pcall(function()
				sound:Play()
			end)
		end
	end
end)
Extras:NewButton("Force Drop", "", function()
	game.ReplicatedStorage.MainEvent:FireServer("DropMoney", 10000)
end)
Extras:NewButton("Black Hole", "", function()

end)
Extras:NewButton("Bat Pp", "Get Bat!", function()
local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
	local k = game.Workspace.Ignored.Shop["[Bat] - $250"]
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
	if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
		wait(.2)
		fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
		toolf = game.Players.LocalPlayer.Backpack:WaitForChild("[Bat]")
		toolf.Parent = game.Players.LocalPlayer.Character
		wait()
		game.Players.LocalPlayer.Character:WaitForChild("[Bat]")
		game.Players.LocalPlayer.Character:WaitForChild("[Bat]").Grip = CFrame.new(-2.4000001, -0.699999988, 0, 0, 1, -0, -1, 0, -0, 0, 0, 1)
		game.Players.LocalPlayer.Character:WaitForChild("[Bat]").GripForward = Vector3.new(0, -1, -0)
		game.Players.LocalPlayer.Character:WaitForChild("[Bat]").GripPos = Vector3.new(1.2111, 1.11114, 1.8111)
		game.Players.LocalPlayer.Character:WaitForChild("[Bat]").GripUp = Vector3.new(-500000, 404, 5000000)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
	end
end)
Extras:NewSlider("Money Charger!", "FAKE!", 1000000000, 0, function(value)
game.Players.LocalPlayer.PlayerGui.Framework.CurrencySound:Play()
	game.Players.LocalPlayer.DataFolder.Currency.Value = value
	game.Players.LocalPlayer.PlayerGui.MainScreenGui.MoneyText.Text = "$"..value
	if game.Players.LocalPlayer.Backpack:FindFirstChild("Wallet") then
		game.Players.LocalPlayer.Backpack.Wallet.Handle.BillboardGui.TextLabel.Text = "$"..value
	else
		game.Players.LocalPlayer.Character.Wallet.Handle.BillboardGui.TextLabel.Text = "$"..value
	end
end)
Extras:NewSlider("Bounty Charher!", "FAKE!", 1000000000, 0, function(value)
end)
Extras:NewButton("Mask", "", function()
local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
	local k = game.Workspace.Ignored.Shop["[Surgeon Mask] - $25"]
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
	if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
		wait(.2)
		fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
		toolf = game.Players.LocalPlayer.Backpack:WaitForChild("Mask")
		toolf.Parent = game.Players.LocalPlayer.Character
		wait()
		game.Players.LocalPlayer.Character:WaitForChild("Mask")
		game:GetService("VirtualUser"):ClickButton1(Vector2.new())
		game.Players.LocalPlayer.Character:WaitForChild("In-gameMask")
		game.Players.LocalPlayer.Character["In-gameMask"].Handle:Destroy()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
	end
end)
Extras:NewButton("Invisible Mask", "", function()
local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
	local k = game.Workspace.Ignored.Shop["[Surgeon Mask] - $25"]
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
	if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
		wait(.2)
		fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
		toolf = game.Players.LocalPlayer.Backpack:WaitForChild("Mask")
		toolf.Parent = game.Players.LocalPlayer.Character
		wait()
		game.Players.LocalPlayer.Character:WaitForChild("Mask")
		game:GetService("VirtualUser"):ClickButton1(Vector2.new())
		game.Players.LocalPlayer.Character:WaitForChild("In-gameMask")
		game.Players.LocalPlayer.Character["In-gameMask"].Handle:Destroy()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
	end
end)
Extras:NewButton("Invisible Boombox", "", function()
game:GetService('Players').LocalPlayer.Character['BOOMBOXHANDLE']:Destroy() 
end)
Extras:NewButton("Equip All", "", function()
for _, v in next, game:GetService("Players").LocalPlayer.Backpack:GetChildren() do
		if v:IsA("Tool") then
			v.Parent = game:GetService("Players").LocalPlayer.Character
		end
	end
end)
Extras:NewButton("Tools While Jailed", "", function()
game:GetService("Players").LocalPlayer.Character.BodyEffects.Cuff:Destroy()
end)
Extras:NewButton("Cash Esp!", "", function()
local ESPholder = Instance.new("Folder", game.CoreGui)
	function cham(object)
		if object.Name == "MoneyDrop" then
			local a = Instance.new("BoxHandleAdornment", ESPholder)
			a.Adornee = object
			a.AlwaysOnTop = true
			a.ZIndex = 10
			a.Size = object.Size
			a.Transparency = 0.3
			a.Color = object.BrickColor
			local bill = object:WaitForChild("BillboardGui")
			bill.AlwaysOnTop = true
			bill.Size = UDim2.new(2, 10, 1, 5)
			spawn(function()
				while true do
					if object.Parent.ChildRemoving:wait() == object then
						a:Destroy()
						break
					end
				end
			end)
		end
	end
	for i, v in next, game.Workspace.Ignored.Drop:GetChildren() do
		cham(v)
	end
	game.Workspace.Ignored.Drop.ChildAdded:connect(cham)
end)
Extras:NewButton("Crash Server!", "", function()
local prefixe = "/"

	local Message = (prefixe.. "clean".." "):rep(95999988)

	for i = 1, 750 do
		game.Players:Chat(Message)
	end
end)
Extras:NewKeybind("Toggle GUI", "Hides The Menu", Enum.KeyCode.V, function()
Library:ToggleUI()
end)
Featured:NewButton("Sing ''Super Idol''", "Ib: Destiny", function()
local sound = Instance.new("Sound")
    sound.SoundId = "rbxassetid://7739913941"
    sound.Parent = game:GetService("SoundService")
    sound:Play()
wait(.1)
loadstring(game:HttpGet('https://pastebin.com/raw/rPYUnz5a'))()
end)
Featured:NewButton("Aimlock [Tool]", "", function()
end)
Featured:NewButton("Aimbot [Rclick]", "", function()
local CC = game:GetService"Workspace".CurrentCamera
	local Plr
	local enabled = false
	local accomidationfactor = 0.165
	local mouse = game.Players.LocalPlayer:GetMouse()
	local placemarker = Instance.new("Part", game.Workspace)
	local guimain = Instance.new("Folder", game.CoreGui)

	function makemarker(Parent, Adornee, Color, Size, Size2)
		local e = Instance.new("BillboardGui", Parent)
		e.Name = "PP"
		e.Adornee = Adornee
		e.Size = UDim2.new(Size, Size2, Size, Size2)
		e.AlwaysOnTop = true
		local a = Instance.new("Frame", e)
		a.Size = UDim2.new(1, 0, 1, 0)
		a.BackgroundTransparency = 0.4
		a.BackgroundColor3 = Color
		local g = Instance.new("UICorner", a)
		g.CornerRadius = UDim.new(50, 50)
		return(e)
	end

	local data = game.Players:GetPlayers()
	function noob(player)
		local character
		repeat wait() until player.Character
		local handler = makemarker(guimain, player.Character:WaitForChild("Head"), Color3.fromRGB(255, 255, 255), 0.3, 3)
		handler.Name = player.Name
		player.CharacterAdded:connect(function(Char) handler.Adornee = Char:WaitForChild("Head") end)

		local TextLabel = Instance.new("TextLabel", handler)
		TextLabel.BackgroundTransparency = 1
		TextLabel.Position = UDim2.new(0, 0, 0, -50)
		TextLabel.Size = UDim2.new(0, 100, 0, 100)
		TextLabel.Font = Enum.Font.SourceSansSemibold
		TextLabel.TextSize = 14
		TextLabel.TextColor3 = Color3.new(1, 1, 1)
		TextLabel.TextStrokeTransparency = 0
		TextLabel.TextYAlignment = Enum.TextYAlignment.Bottom
		TextLabel.Text = "Name: "..player.Name
		TextLabel.ZIndex = 10

		spawn(function()
			while wait() do
				if player.Character then
					TextLabel.Text = player.Name.." | Bounty: "..tostring(player:WaitForChild("leaderstats").Wanted.Value).." | "..tostring(math.floor(player.Character:WaitForChild("Humanoid").Health))
				end
			end
		end)
	end

	for i = 1, #data do
		if data[i] ~= game.Players.LocalPlayer then
			noob(data[i])
		end
	end

	game.Players.PlayerAdded:connect(function(Player)
		noob(Player)
	end)

	spawn(function()
		placemarker.Anchored = true
		placemarker.CanCollide = false
		placemarker.Size = Vector3.new(0.1, 0.1, 0.1)
		placemarker.Transparency = 1
		makemarker(placemarker, placemarker, Color3.fromRGB(0, 0, 255), 0.15, 0)
	end)    

	local UserInputService = game:GetService"UserInputService"

	UserInputService.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton2 then
			enabled = true 
			Plr = getClosestPlayerToCursor()
			guimain[Plr.Name].Frame.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	end)

	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton2 then
			enabled = false
			guimain[Plr.Name].Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		end
	end)

	function getClosestPlayerToCursor()
		local closestPlayer
		local shortestDistance = math.huge

		for i, v in pairs(game.Players:GetPlayers()) do
			if v ~= game.Players.LocalPlayer and v.Character and v.Character:FindFirstChild("Humanoid") and v.Character.Humanoid.Health ~= 0 and v.Character:FindFirstChild("Head") then
				local pos = CC:WorldToViewportPoint(v.Character.PrimaryPart.Position)
				local magnitude = (Vector2.new(pos.X, pos.Y) - Vector2.new(mouse.X, mouse.Y)).magnitude
				if magnitude < shortestDistance then
					closestPlayer = v
					shortestDistance = magnitude
				end
			end
		end
		return closestPlayer
	end

	game:GetService"RunService".Stepped:connect(function()
		if enabled and Plr.Character and Plr.Character:FindFirstChild("Head") then
			placemarker.CFrame = CFrame.new(Plr.Character.Head.Position+(Plr.Character.Head.Velocity*accomidationfactor))
		else
			placemarker.CFrame = CFrame.new(0, 9999, 0)
		end
	end)

	local mt = getrawmetatable(game)
	local old = mt.__namecall
	setreadonly(mt, false)
	mt.__namecall = newcclosure(function(...)
		local args = {...}
		if enabled and getnamecallmethod() == "FireServer" and args[2] == "UpdateMousePos" then
			args[3] = Plr.Character.Head.Position+(Plr.Character.Head.Velocity*accomidationfactor)
			return old(unpack(args))
		end
		return old(...)
	end)
end)
Featured:NewButton("Burger Shield", "PATCHED!", function()
local Plr = game.Players.LocalPlayer
	local e = 0
	local p = 0
	local burgercount = 3
	local a = {}
	local radian = math.pi/burgercount
	repeat
		Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["[Hamburger] - $5"].Head.CFrame
		wait(0.5)
		fireclickdetector(game:GetService("Workspace").Ignored.Shop["[Hamburger] - $5"].ClickDetector)
		for i, v in pairs(Plr.Backpack:GetChildren()) do
			if v.Name == "[Hamburger]" then
				e = 0
				for i, v in pairs(a) do
					e = e + 1
				end
				table.insert(a, v)
				v.Parent = Plr.Character
			end
		end
	until e >= burgercount*9
	spawn(function()
		while wait() do
			e = e + 0.01
			if e >= 1 then
				e = -1
			end
		end
	end)
	for i, v in pairs(a) do
		spawn(function()
			while wait() do
				p = 2*(e*math.pi-(radian*i))
				if i <=math.floor(1*burgercount) then
					v.GripPos = Vector3.new(math.sin(p)*5, 0, math.cos(p)*5)
				elseif i <=2*burgercount then
					v.GripPos = Vector3.new(math.sin(p)*5, math.cos(p)*5, 0)
				elseif i <=3*burgercount then
					v.GripPos = Vector3.new(0, math.cos(p)*5, math.sin(p)*5)
				elseif i <=4*burgercount then
					v.GripPos = Vector3.new(math.cos(p)*5, math.sin(p)*5, math.cos(p)*5)
				elseif i <=5*burgercount then
					v.GripPos = Vector3.new(math.cos(p)*5, math.sin(p)*5, -math.cos(p)*5)
				elseif i <=6*burgercount then
					v.GripPos = Vector3.new(math.sin(p)*5, math.cos(p)*5, math.cos(p)*5)
				elseif i <=7*burgercount then
					v.GripPos = Vector3.new(math.sin(p)*5, math.cos(p)*5, -math.cos(p)*5)
				elseif i <=8*burgercount then
					v.GripPos = Vector3.new(math.cos(p)*5, math.cos(p)*5, math.sin(p)*5)
				elseif i <=9*burgercount then
					v.GripPos = Vector3.new(math.cos(p)*5, math.cos(p)*5, math.sin(p)*5)
				end
			end
		end)
	end
	Plr.Character.Humanoid:UnequipTools()
	wait(5)
	for _, burger in pairs(a) do
		burger.Parent = Plr.Character
	end
end)
Featured:NewButton("Burger Galaxy", "PATCHED!", function()
local Plr = game.Players.LocalPlayer
	local lastPos = Plr.Character.HumanoidRootPart.CFrame
	local e = 0
	local p = 0
	local a = {}
	repeat
		Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["[Hamburger] - $5"].Head.CFrame
		wait(0.5)
		fireclickdetector(game:GetService("Workspace").Ignored.Shop["[Hamburger] - $5"].ClickDetector)
		for i, v in pairs(Plr.Backpack:GetChildren()) do
			if v.Name == "[Hamburger]" then
				e = 0
				for i, v in pairs(a) do
					e = e + 1
				end
				table.insert(a, v)
				v.Parent = Plr.Character
			end
		end
	until e >= 100

	for i, v in pairs(a) do
		local p = (i*0.01)+0.50
		v.GripUp = Vector3.new(0, 1, 0)
		if i <=e/2 then
			v.GripPos = Vector3.new(((p^4)*math.cos(18.5*(math.pi*p)))*40, 0, ((p^4)*math.sin(18.5*(math.pi*p)))*40)
		else
			v.GripPos = Vector3.new(((p^4)*math.cos(18.5*(math.pi*p)))*40, 0, ((p^4)*math.sin(18.5*(math.pi*p)))*40)
		end
	end
	Plr.Character.Humanoid:UnequipTools()
	wait(5)
	for _, burger in pairs(a) do
		burger.Parent = Plr.Character
	end
	Plr.Character.HumanoidRootPart.CFrame = lastPos
end)
Featured:NewButton("Chicken Galaxy", "PATCHED!", function()
local Plr = game.Players.LocalPlayer
	local lastPos = Plr.Character.HumanoidRootPart.CFrame
	local e = 0
	local p = 0
	local a = {}
	repeat
		Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["[Chicken] - $7"].Head.CFrame
		wait(0.5)
		fireclickdetector(game:GetService("Workspace").Ignored.Shop["[Chicken] - $7"].ClickDetector)
		for i, v in pairs(Plr.Backpack:GetChildren()) do
			if v.Name == "[Hamburger]" then
				e = 0
				for i, v in pairs(a) do
					e = e + 1
				end
				table.insert(a, v)
				v.Parent = Plr.Character
			end
		end
	until e >= 100

	for i, v in pairs(a) do
		local p = (i*0.01)+0.50
		v.GripUp = Vector3.new(0, 1, 0)
		if i <=e/2 then
			v.GripPos = Vector3.new(((p^4)*math.cos(18.5*(math.pi*p)))*40, 0, ((p^4)*math.sin(18.5*(math.pi*p)))*40)
		else
			v.GripPos = Vector3.new(((p^4)*math.cos(18.5*(math.pi*p)))*40, 0, ((p^4)*math.sin(18.5*(math.pi*p)))*40)
		end
	end
	Plr.Character.Humanoid:UnequipTools()
	wait(5)
	for _, burger in pairs(a) do
		burger.Parent = Plr.Character
	end
	Plr.Character.HumanoidRootPart.CFrame = lastPos
end)
Featured:NewButton("Galaxy", "PATCHED!", function()
local Plr = game.Players.LocalPlayer
	local lastPos = Plr.Character.HumanoidRootPart.CFrame
	local e = 100
	local a, g = {}, {}

	repeat
		Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["[Hamburger] - $5"].Head.CFrame
		wait(0.5)
		fireclickdetector(game:GetService("Workspace").Ignored.Shop["[Hamburger] - $5"].ClickDetector)
		for i, v in pairs(Plr.Backpack:GetChildren()) do
			if v.Name == "[Hamburger]" then
				table.insert(a, v)
				v.Parent = Plr.Character
			end
		end
	until #a >= e/2

	repeat
		Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["[Chicken] - $7"].Head.CFrame
		wait(0.5)
		fireclickdetector(game.Workspace.Ignored.Shop["[Chicken] - $7"].ClickDetector)
		for i, v in pairs(Plr.Backpack:GetChildren()) do
			if v.Name == "[Chicken]" then
				table.insert(g, v)
				v.Parent = Plr.Character
			end
		end
	until #g >= e/2

	for i, v in pairs(a) do
		local p = (i*0.01)+0.50
		v.GripUp = Vector3.new(0, 1, 0)
		v.GripPos = Vector3.new(((p^4)*math.cos(18.5*(math.pi*p)))*40, 0, ((p^4)*math.sin(18.5*(math.pi*p)))*40)
	end

	for i, v in pairs(g) do
		local p = (i*0.01)+0.50
		v.GripUp = Vector3.new(0, 1, 0)
		v.GripPos = Vector3.new(-((p^4)*math.cos(18.5*(math.pi*p)))*40, 0, -((p^4)*math.sin(18.5*(math.pi*p)))*40)
	end

	Plr.Character.Humanoid:UnequipTools()
	wait(5)
	for _, burger in pairs(a) do
		burger.Parent = Plr.Character
	end
	for _, chicken in pairs(g) do
		chicken.Parent = Plr.Character
	end
	Plr.Character.HumanoidRootPart.CFrame = lastPos
end)
Featured:NewButton("RPG Ride", "PATCHED!", function()
	-- SETTINGS --
	local speed = 20
	local turnSpeed = 3
	--------------

	local plr = game.Players.LocalPlayer
	local Mouse = plr:GetMouse()
	local peniscock
	local movers
	local control = {w=false,a=false,s=false,d=false,q=false,e=false}

	game:GetService("RunService").Stepped:connect(function()
		if plr.PlayerGui:FindFirstChild("MainScreenGui") and plr.PlayerGui.MainScreenGui:FindFirstChild("Bar") and plr.PlayerGui.MainScreenGui.Bar:FindFirstChild("Speed") then
			plr.PlayerGui.MainScreenGui.Bar.Speed.bar.Size = UDim2.new(speed / 100 * 0.95, 0, 0.83, 0)
		else
			local c = plr.PlayerGui.MainScreenGui.Bar.HP
			local g = c:Clone()
			g.Name = "Speed"
			g.Position = UDim2.new(0.5, 0, 1, -120)
			g.bar.BackgroundColor3 = Color3.fromRGB(255, 155, 0)
			g.Picture.Image.Image = "rbxassetid://181035717"
			g.TextLabel.Text = "Speed"
			g.Parent = c.Parent
		end
		if peniscock and peniscock.Parent ~= nil then
			setsimulationradius(math.huge^math.huge, math.huge)
			if movers then
				movers[1].Position = (peniscock.CFrame*CFrame.new(0, -speed/20, -2))*CFrame.Angles(math.rad(-90), 0, 0).p
				movers[2].cframe = (peniscock.CFrame*CFrame.new(0, -speed/20, -2))*CFrame.Angles(math.rad(-90), 0, 0)
				if plr.Character.Humanoid.Sit ~= true then
					peniscock = nil
				end
			else
				movers={}
				local bp = Instance.new("BodyPosition", plr.Character.LowerTorso)
				local bg = Instance.new("BodyGyro", plr.Character.LowerTorso)
				bp.P = 1e5
				bp.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
				bg.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
				movers[1], movers[2] = bp, bg
			end
			if control.w then
				peniscock.CFrame = peniscock.CFrame * CFrame.Angles(math.rad(turnSpeed), 0, 0)
			end
			if control.s then
				peniscock.CFrame = peniscock.CFrame * CFrame.Angles(math.rad(-turnSpeed), 0, 0)
			end
			if control.a then
				peniscock.CFrame = peniscock.CFrame * CFrame.Angles(0, 0, math.rad(-turnSpeed))
			end
			if control.d then
				peniscock.CFrame = peniscock.CFrame * CFrame.Angles(0, 0, math.rad(turnSpeed))
			end
		end
		if control.q and speed > 0 then
			speed = speed - 1
		end
		if control.e and speed < 100 then
			speed = speed + 1
		end
	end)

	Mouse.KeyDown:connect(function(KEY)
		local key = KEY:lower()
		if control[key] ~= nil then
			control[key]=true
		end
	end)

	Mouse.KeyUp:connect(function(KEY)
		local key = KEY:lower()
		if control[key] ~= nil then
			control[key]=false
		end
	end)

	game.Workspace.Ignored.ChildAdded:connect(function(child)
		wait()
		if child.Name == "Launcher" and math.abs((child.Position-plr.Character.HumanoidRootPart.Position).Magnitude)<30 then
			plr.Character.Humanoid.Sit = true
			peniscock = child
			child:WaitForChild("BodyVelocity"):Destroy()
			local e = Instance.new("BodyVelocity", child)
			while peniscock and peniscock.Parent ~= nil do
				game.RunService.Stepped:wait()
				e.Velocity = ((child.CFrame * CFrame.new(0, -speed, 0)).p - child.CFrame.p)
			end
			movers[1]:Destroy()
			movers[2]:Destroy()
			movers = nil
		end
	end)
end)
Featured:NewButton("RPG Control", "PATCHED!", function()
-- SETTINGS --
	local speed = 20
	local turnSpeed = 3
	--------------

	local plr = game.Players.LocalPlayer
	local Mouse = plr:GetMouse()
	local peniscock
	local movers
	local control = {w=false,a=false,s=false,d=false,q=false,e=false}

	game:GetService("RunService").Stepped:connect(function()
		if plr.PlayerGui:FindFirstChild("MainScreenGui") and plr.PlayerGui.MainScreenGui:FindFirstChild("Bar") and plr.PlayerGui.MainScreenGui.Bar:FindFirstChild("Speed") then
			plr.PlayerGui.MainScreenGui.Bar.Speed.bar.Size = UDim2.new(speed / 100 * 0.95, 0, 0.83, 0)
		else
			local c = plr.PlayerGui.MainScreenGui.Bar.HP
			local g = c:Clone()
			g.Name = "Speed"
			g.Position = UDim2.new(0.5, 0, 1, -120)
			g.bar.BackgroundColor3 = Color3.fromRGB(255, 155, 0)
			g.Picture.Image.Image = "rbxassetid://181035717"
			g.TextLabel.Text = "Speed"
			g.Parent = c.Parent
		end
		if peniscock and peniscock.Parent ~= nil then
			setsimulationradius(math.huge^math.huge, math.huge)
			if plr.Character.Humanoid.Sit ~= true then
				peniscock = nil
			end
			peniscock.CFrame = CFrame.lookAt(peniscock.CFrame.p, Mouse.Hit.p)*CFrame.Angles(math.rad(90), 0, 0)
		end
		if control.q and speed > 0 then
			speed = speed - 1
		end
		if control.e and speed < 100 then
			speed = speed + 1
		end
	end)

	Mouse.KeyDown:connect(function(KEY)
		local key = KEY:lower()
		if control[key] ~= nil then
			control[key]=true
		end
	end)

	Mouse.KeyUp:connect(function(KEY)
		local key = KEY:lower()
		if control[key] ~= nil then
			control[key]=false
		end
	end)

	game.Workspace.Ignored.ChildAdded:connect(function(child)
		wait()
		if child.Name == "Launcher" and math.abs((child.Position-plr.Character.HumanoidRootPart.Position).Magnitude)<30 then
			local old = game.Workspace.CurrentCamera.CameraSubject
			plr.Character.Humanoid.Sit = true
			game.Workspace.CurrentCamera.CameraSubject = child
			peniscock = child
			child:WaitForChild("BodyVelocity"):Destroy()
			local e = Instance.new("BodyVelocity", child)
			while peniscock and peniscock.Parent ~= nil do
				game.RunService.Stepped:wait()
				e.Velocity = ((child.CFrame * CFrame.new(0, -speed, 0)).p - child.CFrame.p)
			end
			wait(0.5)
			game.Workspace.CurrentCamera.CameraSubject = old
		end
	end)
end)
game.StarterGui:SetCore("SendNotification", {
	Title = "Desire Hub",
	Text = "Welcome To Desire Hub! Copied Discord link to your clipboard. Have Fun!",
	Duration = 10,
})
enabled = true
	spyOnMyself = false
	public = false
	publicItalics = true
	privateProperties = {
		Color = Color3.fromRGB(0, 255, 255),
		Font = Enum.Font.SourceSansBold,
		TextSize = 18
	}
	local StarterGui = game:GetService("StarterGui")
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer or Players:GetPropertyChangedSignal("LocalPlayer"):Wait() or Players.LocalPlayer
	local saymsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("SayMessageRequest")
	local getmsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("OnMessageDoneFiltering")
	local instance = (_G.chatSpyInstance or 0) + 1
	_G.chatSpyInstance = instance

	local function onChatted(p, msg)
		if _G.chatSpyInstance == instance then
			if p == player and msg:lower():sub(1, 4) == "/spy" then
				enabled = not enabled
				wait(0.3)
				privateProperties.Text = "{SPY "..(enabled and "EN" or "DIS").."ABLED}"
				StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
			elseif enabled and (spyOnMyself == true or p ~= player) then
				msg = msg:gsub("[\n\r]", ""):gsub("\t", " "):gsub("[ ]+", " ")
				local hidden = true
				local conn = getmsg.OnClientEvent:Connect(function(packet, channel)
					if packet.SpeakerUserId == p.UserId and packet.Message == msg:sub(#msg - #packet.Message + 1) and (channel == "All" or (channel == "Team" and public == false and Players[packet.FromSpeaker].Team == player.Team)) then
						hidden = false
					end
				end)
				wait(1)
				conn:Disconnect()
				if hidden and enabled then
					if public then
						saymsg:FireServer((publicItalics and "/me " or "").."{SPY} ["..p.Name.."]: "..msg, "All")
					else
						privateProperties.Text = "{SPY} ["..p.Name.."]: "..msg
						StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
					end
				end
			end
		end
	end

	for _, p in ipairs(Players:GetPlayers()) do
		p.Chatted:Connect(function(msg)
			onChatted(p, msg)
		end)
	end
	Players.PlayerAdded:Connect(function(p)
		p.Chatted:Connect(function(msg)
			onChatted(p, msg)
		end)
	end)
	privateProperties.Text = "{SPY "..(enabled and "EN" or "DIS").."ABLED}"
	StarterGui:SetCore("ChatMakeSystemMessage", privateProperties)
	if not player.PlayerGui:FindFirstChild("Chat") then
		wait(3)
	end
	local chatFrame = player.PlayerGui.Chat.Frame
	chatFrame.ChatChannelParentFrame.Visible = true
	chatFrame.ChatBarParentFrame.Position = chatFrame.ChatChannelParentFrame.Position + UDim2.new(UDim.new(), chatFrame.ChatChannelParentFrame.Size.Y)
game:GetService("Players").LocalPlayer:GetMouse().KeyDown:Connect(function(Key)
	if Key == "v" then
		Library:toggleUI()
	end
end)

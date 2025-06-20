-- Gui to Lua
-- Version: 3.2

-- Instances:

local PyEx = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local UIGradient = Instance.new("UIGradient")
local ImageLabel = Instance.new("ImageLabel")
local fly = Instance.new("ImageButton")
local noclip = Instance.new("ImageButton")
local speed = Instance.new("ImageButton")
local spectate = Instance.new("ImageButton")
local TargetSpec = Instance.new("TextBox")
local UICorner_2 = Instance.new("UICorner")
local fling = Instance.new("ImageButton")
local health = Instance.new("ImageButton")
local inv = Instance.new("ImageButton")
local ImageButton = Instance.new("ImageButton")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local UICorner_3 = Instance.new("UICorner")
Instance.new("DragDetector", Frame)

--Properties:

PyEx.Name = "PyEx"
PyEx.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
PyEx.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = PyEx
Frame.Active = true
Frame.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
Frame.BackgroundTransparency = 0.100
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.311172664, 0, 0.163934425, 0)
Frame.Size = UDim2.new(0, 641, 0, 271)

UICorner.CornerRadius = UDim.new(0, 10)
UICorner.Parent = Frame

UIAspectRatioConstraint.Parent = Frame
UIAspectRatioConstraint.AspectRatio = 2.000

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(20, 20, 20)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient.Rotation = -60
UIGradient.Transparency = NumberSequence.new{NumberSequenceKeypoint.new(0.00, 0.10), NumberSequenceKeypoint.new(1.00, 0.10)}
UIGradient.Parent = Frame

ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.293357939, 0, 0.158671588, 0)
ImageLabel.Size = UDim2.new(0, 224, 0, 184)
ImageLabel.Image = "rbxassetid://135337857741051"
ImageLabel.ImageTransparency = 0.700

fly.Name = "fly"
fly.Parent = Frame
fly.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
fly.BackgroundTransparency = 0.900
fly.BorderColor3 = Color3.fromRGB(0, 0, 0)
fly.BorderSizePixel = 0
fly.Position = UDim2.new(0.0664206669, 0, 0.0811808109, 0)
fly.Size = UDim2.new(0, 77, 0, 69)
fly.Image = "rbxassetid://12250990971"

noclip.Name = "noclip"
noclip.Parent = Frame
noclip.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
noclip.BackgroundTransparency = 0.900
noclip.BorderColor3 = Color3.fromRGB(0, 0, 0)
noclip.BorderSizePixel = 0
noclip.Position = UDim2.new(0.0664206669, 0, 0.372693717, 0)
noclip.Size = UDim2.new(0, 77, 0, 69)
noclip.Image = "rbxassetid://76161657191012"

speed.Name = "speed"
speed.Parent = Frame
speed.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
speed.BackgroundTransparency = 0.900
speed.BorderColor3 = Color3.fromRGB(0, 0, 0)
speed.BorderSizePixel = 0
speed.Position = UDim2.new(0.0664206669, 0, 0.656826556, 0)
speed.Size = UDim2.new(0, 77, 0, 69)
speed.Image = "rbxassetid://127633283332495"

spectate.Name = "spectate"
spectate.Parent = Frame
spectate.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
spectate.BackgroundTransparency = 0.900
spectate.BorderColor3 = Color3.fromRGB(0, 0, 0)
spectate.BorderSizePixel = 0
spectate.Position = UDim2.new(0.239852399, 0, 0.0811808109, 0)
spectate.Size = UDim2.new(0, 77, 0, 69)
spectate.Image = "rbxassetid://12668252226"

TargetSpec.Name = "TargetSpec"
TargetSpec.Parent = Frame
TargetSpec.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
TargetSpec.BackgroundTransparency = 0.200
TargetSpec.BorderColor3 = Color3.fromRGB(0, 0, 0)
TargetSpec.BorderSizePixel = 0
TargetSpec.Position = UDim2.new(0.409594089, 0, 0.114391141, 0)
TargetSpec.Size = UDim2.new(0, 200, 0, 50)
TargetSpec.Font = Enum.Font.Nunito
TargetSpec.FontFace.Weight = Enum.FontWeight.SemiBold
TargetSpec.Text = "Player To Spectate"
TargetSpec.TextColor3 = Color3.fromRGB(255, 255, 255)
TargetSpec.TextSize = 20.000

UICorner_2.Parent = TargetSpec

fling.Name = "fling"
fling.Parent = Frame
fling.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
fling.BackgroundTransparency = 0.900
fling.BorderColor3 = Color3.fromRGB(0, 0, 0)
fling.BorderSizePixel = 0
fling.Position = UDim2.new(0.239852399, 0, 0.372693717, 0)
fling.Size = UDim2.new(0, 77, 0, 69)
fling.Image = "rbxassetid://104574410413973"

health.Name = "health"
health.Parent = Frame
health.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
health.BackgroundTransparency = 0.900
health.BorderColor3 = Color3.fromRGB(0, 0, 0)
health.BorderSizePixel = 0
health.Position = UDim2.new(0.239852399, 0, 0.656826496, 0)
health.Size = UDim2.new(0, 77, 0, 69)
health.Image = "rbxassetid://18416638478"

inv.Name = "inv"
inv.Parent = Frame
inv.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
inv.BackgroundTransparency = 0.900
inv.BorderColor3 = Color3.fromRGB(0, 0, 0)
inv.BorderSizePixel = 0
inv.Position = UDim2.new(0.409594089, 0, 0.372693717, 0)
inv.Size = UDim2.new(0, 77, 0, 69)
inv.Image = "rbxassetid://14996669677"

ImageButton.Parent = PyEx
ImageButton.BackgroundColor3 = Color3.fromRGB(28, 46, 58)
ImageButton.BackgroundTransparency = 0.300
ImageButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderSizePixel = 0
ImageButton.Position = UDim2.new(0, 0, 0.403162062, 0)
ImageButton.Size = UDim2.new(0, 117, 0, 100)
ImageButton.Image = "rbxassetid://135337857741051"

UIAspectRatioConstraint_2.Parent = ImageButton
UIAspectRatioConstraint_2.AspectRatio = 1.200

UICorner_3.Parent = ImageButton

-- Scripts:

local function EEJLG_fake_script() -- Frame.main 
	local script = Instance.new('LocalScript', Frame)

	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local ui = script.Parent
	
	local player = Players.LocalPlayer
	local camera = workspace.CurrentCamera
	
	local speed = 0
	local maxspeed = 50
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	
	local bg, bv -- bodygyro, bodyvelocity instances
	local torso -- or UpperTorso reference
	
	local flying = false
	local fast = false
	local noclip = false
	local spectate = false
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local UserInputService = game:GetService("UserInputService")
	
	local player = Players.LocalPlayer
	local camera = workspace.CurrentCamera
	
	local speed = 0
	local maxspeed = 50
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	
	local bg, bv
	local torso
	
	local flying = false
	local flightConnection
	local inputBeganConnection
	local inputEndedConnection
	
	local flingEnabled = false
	local flingConnection = nil
	local FlingAmount = 1000
	local sit = false
	local explode = false
	
	local immortal = false
	local regenConnection = nil
	
	function startFlying()
		if flying then return end
		flying = true
		print("Flying started.")
	
		local character = player.Character
		local humanoid = character and character:FindFirstChildWhichIsA("Humanoid")
		if not character or not humanoid then return end
	
		if humanoid.RigType == Enum.HumanoidRigType.R6 then
			torso = character:WaitForChild("Torso")
		else
			torso = character:WaitForChild("UpperTorso")
		end
	
		bg = Instance.new("BodyGyro", torso)
		bg.P = 9e4
		bg.MaxTorque = Vector3.new(9e9, 9e9, 9e9)
		bg.CFrame = torso.CFrame
	
		bv = Instance.new("BodyVelocity", torso)
		bv.Velocity = Vector3.new(0, 0.1, 0)
		bv.MaxForce = Vector3.new(9e9, 9e9, 9e9)
	
		humanoid.PlatformStand = true
	
		-- Input handling for flight controls
		inputBeganConnection = UserInputService.InputBegan:Connect(function(input, gameProcessed)
			if gameProcessed then return end
			if not flying then return end
	
			if input.KeyCode == Enum.KeyCode.W then ctrl.f = 1 end
			if input.KeyCode == Enum.KeyCode.S then ctrl.b = -1 end
			if input.KeyCode == Enum.KeyCode.A then ctrl.l = -1 end
			if input.KeyCode == Enum.KeyCode.D then ctrl.r = 1 end
		end)
	
		inputEndedConnection = UserInputService.InputEnded:Connect(function(input)
			if not flying then return end
	
			if input.KeyCode == Enum.KeyCode.W then ctrl.f = 0 end
			if input.KeyCode == Enum.KeyCode.S then ctrl.b = 0 end
			if input.KeyCode == Enum.KeyCode.A then ctrl.l = 0 end
			if input.KeyCode == Enum.KeyCode.D then ctrl.r = 0 end
		end)
	
		-- Flight loop
		flightConnection = RunService.RenderStepped:Connect(function()
			if not flying or humanoid.Health <= 0 then return end
	
			local camCF = camera.CFrame
	
			if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
				speed = speed + 0.5 + (speed / maxspeed)
				if speed > maxspeed then speed = maxspeed end
			elseif speed ~= 0 then
				speed = speed - 1
				if speed < 0 then speed = 0 end
			end
	
			if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
				bv.Velocity = (
					(camCF.LookVector * (ctrl.f + ctrl.b)) +
						(camCF.RightVector * (ctrl.r + ctrl.l))
				) * speed
				lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
			elseif speed ~= 0 then
				bv.Velocity = (
					(camCF.LookVector * (lastctrl.f + lastctrl.b)) +
						(camCF.RightVector * (lastctrl.r + lastctrl.l))
				) * speed
			else
				bv.Velocity = Vector3.new(0, 0, 0)
			end
	
			bg.CFrame = camCF
		end)
	end
	
	function stopFlying()
		if not flying then return end
		flying = false
		print("Flying stopped.")
	
		if flightConnection then
			flightConnection:Disconnect()
			flightConnection = nil
		end
	
		if inputBeganConnection then
			inputBeganConnection:Disconnect()
			inputBeganConnection = nil
		end
	
		if inputEndedConnection then
			inputEndedConnection:Disconnect()
			inputEndedConnection = nil
		end
	
		if bg then bg:Destroy() bg = nil end
		if bv then bv:Destroy() bv = nil end
	
		local character = player.Character
		if character and character:FindFirstChildWhichIsA("Humanoid") then
			character.Humanoid.PlatformStand = false
		end
	
		speed = 0
		ctrl = {f = 0, b = 0, l = 0, r = 0}
		lastctrl = {f = 0, b = 0, l = 0, r = 0}
	end
	
	
	function startFast()
		game.Players.LocalPlayer.Character:WaitForChild("Humanoid").WalkSpeed = 100
		fast = true
	end
	
	function endFast()
		game.Players.LocalPlayer.Character:WaitForChild("Humanoid").WalkSpeed = 16
		fast = false
	end
	
	function startNoClip()
		if noclip then return end
		noclip = true
		print("Noclip enabled")
	
		noclipConnection = RunService.Stepped:Connect(function()
			if player.Character then
				for _, part in ipairs(player.Character:GetDescendants()) do
					if part:IsA("BasePart") then
						part.CanCollide = false
					end
				end
			end
		end)
	end
	
	function stopNoClip()
		if not noclip then return end
		noclip = false
		print("Noclip disabled")
	
		if noclipConnection then
			noclipConnection:Disconnect()
			noclipConnection = nil
		end
	
		-- Restore collisions immediately
		if player.Character then
			for _, part in ipairs(player.Character:GetDescendants()) do
				if part:IsA("BasePart") then
					part.CanCollide = true
				end
			end
		end
	end
	
	function spectatePlayer(targetName)
		local targetPlayer = Players:FindFirstChild(targetName)
		if targetPlayer and targetPlayer.Character and targetPlayer.Character:FindFirstChild("Humanoid") then
			camera.CameraSubject = targetPlayer.Character.Humanoid
			print("Now spectating: " .. targetName)
			spectate = true
		else
			warn("Player not found or no character.")
		end
	end
	
	function stopSpectating()
		if player.Character and player.Character:FindFirstChild("Humanoid") then
			camera.CameraSubject = player.Character.Humanoid
			print("Stopped spectating.")
			spectate = false
		end
	end
	
	function startTouchFling()
		if flingEnabled then return end
		flingEnabled = true
		print("Touch Fling enabled")
	
		local character = player.Character
		if not character then return end
		local hrp = character:FindFirstChild("HumanoidRootPart")
		if not hrp then return end
	
		flingConnection = hrp.Touched:Connect(function(hit)
			local blender = hit.Parent and hit.Parent:FindFirstChild("Head")
			if blender and hit.Parent ~= character then
				local bv = Instance.new("BodyVelocity")
				bv.P = 1250
				bv.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
				bv.Velocity = blender.CFrame.LookVector * -FlingAmount
				bv.Parent = blender
	
				if sit then
					local humanoid = hit.Parent:FindFirstChildWhichIsA("Humanoid")
					if humanoid then
						humanoid.Sit = true
					end
				end
	
				game.Debris:AddItem(bv, 0.05)
	
				if explode then
					local ex = Instance.new("Explosion")
					ex.ExplosionType = Enum.ExplosionType.NoCraters
					ex.BlastPressure = 100000
					ex.BlastRadius = 2
					ex.Visible = true
					ex.DestroyJointRadiusPercent = 0
					ex.Position = blender.Position
					ex.Parent = workspace
	
					local humanoid = hit.Parent:FindFirstChildWhichIsA("Humanoid")
					if humanoid then
						humanoid.Health = 0
					end
				end
			end
		end)
	end
	
	function stopTouchFling()
		if not flingEnabled then return end
		flingEnabled = false
		print("Touch Fling disabled")
	
		if flingConnection then
			flingConnection:Disconnect()
			flingConnection = nil
		end
	end
	
	function startImmortality()
		if immortal then return end
		immortal = true
		print("Immortality enabled")
	
		regenConnection = RunService.Heartbeat:Connect(function()
			local character = player.Character
			if character then
				local humanoid = character:FindFirstChildWhichIsA("Humanoid")
				if humanoid then
					if humanoid.Health < 100 then
						humanoid.Health = 100
					end
				end
			end
		end)
	end
	
	function stopImmortality()
		if not immortal then return end
		immortal = false
		print("Immortality disabled")
	
		if regenConnection then
			game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Health = 100
			regenConnection:Disconnect()
			regenConnection = nil
		end
	end
	
	ui.fly.MouseButton1Click:Connect(function()
		if flying then
			stopFlying()
		else
			startFlying()
		end
	end)
	
	ui.speed.MouseButton1Click:Connect(function()
		if fast then
			endFast()
		else
			startFast()
		end
	end)
	
	ui.noclip.MouseButton1Click:Connect(function()
		if noclip then
			stopNoClip()
		else
			startNoClip()
		end
	end)
	
	ui.spectate.MouseButton1Click:Connect(function()
		if spectate then
			stopSpectating()
		else
			local targetName = ui.TargetSpec.Text
			spectatePlayer(targetName)
		end
	end)
	
	ui.fling.MouseButton1Click:Connect(function()
		if flingEnabled then
			stopTouchFling()
		else
			startTouchFling()
		end
	end)
	
	ui.health.MouseButton1Click:Connect(function()
		if immortal then
			stopImmortality()
		else
			startImmortality()
		end
	end)
	
	ui.inv.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/P6DQ5r2K"))()
	end)
end
coroutine.wrap(EEJLG_fake_script)()
local function BLEGX_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	local mainui = script.Parent
	local frame = mainui.Parent.Frame
	local closed = false
	
	mainui.MouseButton1Click:Connect(function()
		if closed then
			frame.Visible = true
			closed = false
		else
			frame.Visible = false
			closed = true
		end
	end)
end
coroutine.wrap(BLEGX_fake_script)()

-- Gui to Lua
-- Version: 3.2

-- Instances:

local MYGUISKID = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local DECALSPAM = Instance.new("TextButton")
local PARTICLES = Instance.new("TextButton")
local JUMPSCARE = Instance.new("TextButton")
local MESSAGE = Instance.new("TextButton")
local KILLALL = Instance.new("TextButton")
local HINT = Instance.new("TextButton")
local MUSIC = Instance.new("TextButton")
local SHUTDOWN = Instance.new("TextButton")
local SKYBOX = Instance.new("TextButton")
local KaaXgui = Instance.new("TextButton")
local cafe = Instance.new("TextButton")

--Properties:

MYGUISKID.Name = "MYGUISKID"
MYGUISKID.Parent = game.StarterGui.MainModule
MYGUISKID.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = MYGUISKID
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 127)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 127)
Frame.BorderSizePixel = 5
Frame.Position = UDim2.new(0.108527742, 0, 0.0979591981, 0)
Frame.Size = UDim2.new(0, 526, 0, 373)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 127)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 127)
TextLabel.BorderSizePixel = 4
TextLabel.Position = UDim2.new(0.00263855211, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 523, 0, 50)
TextLabel.Font = Enum.Font.ArialBold
TextLabel.Text = "??? gui  private"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 30.000

DECALSPAM.Name = "DECALSPAM"
DECALSPAM.Parent = Frame
DECALSPAM.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
DECALSPAM.BorderColor3 = Color3.fromRGB(0, 0, 255)
DECALSPAM.BorderSizePixel = 3
DECALSPAM.Position = UDim2.new(0, 0, 0.231892601, 0)
DECALSPAM.Size = UDim2.new(0, 150, 0, 35)
DECALSPAM.Font = Enum.Font.Arial
DECALSPAM.Text = "DECAL SPAM"
DECALSPAM.TextColor3 = Color3.fromRGB(0, 0, 0)
DECALSPAM.TextSize = 14.000

PARTICLES.Name = "PARTICLES"
PARTICLES.Parent = Frame
PARTICLES.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
PARTICLES.BorderColor3 = Color3.fromRGB(0, 0, 255)
PARTICLES.BorderSizePixel = 3
PARTICLES.Position = UDim2.new(0.315132886, 0, 0.229102179, 0)
PARTICLES.Size = UDim2.new(0, 145, 0, 36)
PARTICLES.Font = Enum.Font.Arial
PARTICLES.Text = "PARTICLES"
PARTICLES.TextColor3 = Color3.fromRGB(0, 0, 0)
PARTICLES.TextSize = 14.000

JUMPSCARE.Name = "JUMPSCARE"
JUMPSCARE.Parent = Frame
JUMPSCARE.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
JUMPSCARE.BorderColor3 = Color3.fromRGB(0, 0, 255)
JUMPSCARE.BorderSizePixel = 3
JUMPSCARE.Position = UDim2.new(0.317460388, 0, 0.417541653, 0)
JUMPSCARE.Size = UDim2.new(0, 147, 0, 36)
JUMPSCARE.Font = Enum.Font.Arial
JUMPSCARE.Text = "JUMPSCARE"
JUMPSCARE.TextColor3 = Color3.fromRGB(0, 0, 0)
JUMPSCARE.TextSize = 14.000

MESSAGE.Name = "MESSAGE"
MESSAGE.Parent = Frame
MESSAGE.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
MESSAGE.BorderColor3 = Color3.fromRGB(0, 0, 255)
MESSAGE.BorderSizePixel = 3
MESSAGE.Position = UDim2.new(-0.00306489971, 0, 0.369641185, 0)
MESSAGE.Size = UDim2.new(0, 151, 0, 37)
MESSAGE.Font = Enum.Font.Arial
MESSAGE.Text = "MESSAGE"
MESSAGE.TextColor3 = Color3.fromRGB(0, 0, 0)
MESSAGE.TextSize = 14.000

KILLALL.Name = "KILL ALL"
KILLALL.Parent = Frame
KILLALL.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
KILLALL.BorderColor3 = Color3.fromRGB(0, 0, 255)
KILLALL.BorderSizePixel = 3
KILLALL.Position = UDim2.new(0.317460388, 0, 0.654653549, 0)
KILLALL.Size = UDim2.new(0, 147, 0, 36)
KILLALL.Font = Enum.Font.Arial
KILLALL.Text = "KILL ALL"
KILLALL.TextColor3 = Color3.fromRGB(0, 0, 0)
KILLALL.TextSize = 14.000

HINT.Name = "HINT"
HINT.Parent = Frame
HINT.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
HINT.BorderColor3 = Color3.fromRGB(0, 0, 255)
HINT.BorderSizePixel = 3
HINT.Position = UDim2.new(-0.00306489971, 0, 0.503216267, 0)
HINT.Size = UDim2.new(0, 154, 0, 35)
HINT.Font = Enum.Font.Arial
HINT.Text = "HINT"
HINT.TextColor3 = Color3.fromRGB(0, 0, 0)
HINT.TextSize = 14.000

MUSIC.Name = "MUSIC"
MUSIC.Parent = Frame
MUSIC.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
MUSIC.BorderColor3 = Color3.fromRGB(0, 0, 255)
MUSIC.BorderSizePixel = 3
MUSIC.Position = UDim2.new(0.313658118, 0, 0.782036662, 0)
MUSIC.Size = UDim2.new(0, 147, 0, 35)
MUSIC.Font = Enum.Font.Arial
MUSIC.Text = "idk sound effect (LOUD)"
MUSIC.TextColor3 = Color3.fromRGB(0, 0, 0)
MUSIC.TextSize = 14.000

SHUTDOWN.Name = "SHUTDOWN"
SHUTDOWN.Parent = Frame
SHUTDOWN.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
SHUTDOWN.BorderColor3 = Color3.fromRGB(0, 0, 255)
SHUTDOWN.BorderSizePixel = 3
SHUTDOWN.Position = UDim2.new(0.00190114067, 0, 0.662198424, 0)
SHUTDOWN.Size = UDim2.new(0, 156, 0, 32)
SHUTDOWN.Font = Enum.Font.Arial
SHUTDOWN.Text = "SHUTDOWN"
SHUTDOWN.TextColor3 = Color3.fromRGB(0, 0, 0)
SHUTDOWN.TextSize = 14.000

SKYBOX.Name = "SKYBOX"
SKYBOX.Parent = Frame
SKYBOX.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
SKYBOX.BorderColor3 = Color3.fromRGB(0, 0, 255)
SKYBOX.BorderSizePixel = 3
SKYBOX.Position = UDim2.new(0.00975561328, 0, 0.817209065, 0)
SKYBOX.Size = UDim2.new(0, 151, 0, 36)
SKYBOX.Font = Enum.Font.Arial
SKYBOX.Text = "SKYBOX"
SKYBOX.TextColor3 = Color3.fromRGB(0, 0, 0)
SKYBOX.TextSize = 14.000

KaaXgui.Name = "KaaX gui"
KaaXgui.Parent = Frame
KaaXgui.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
KaaXgui.BorderColor3 = Color3.fromRGB(0, 0, 255)
KaaXgui.BorderSizePixel = 3
KaaXgui.Position = UDim2.new(0.647832513, 0, 0.229102179, 0)
KaaXgui.Size = UDim2.new(0, 145, 0, 36)
KaaXgui.Font = Enum.Font.Arial
KaaXgui.Text = "KaaX"
KaaXgui.TextColor3 = Color3.fromRGB(0, 0, 0)
KaaXgui.TextSize = 14.000

cafe.Name = "cafe"
cafe.Parent = Frame
cafe.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
cafe.BorderColor3 = Color3.fromRGB(0, 0, 255)
cafe.BorderSizePixel = 3
cafe.Position = UDim2.new(0.640934289, 0, 0.415064305, 0)
cafe.Size = UDim2.new(0, 151, 0, 36)
cafe.Font = Enum.Font.Arial
cafe.Text = "Cafe"
cafe.TextColor3 = Color3.fromRGB(0, 0, 0)
cafe.TextSize = 14.000

-- Module Scripts:

local fake_module_scripts = {}

do -- nil.MainModule
	local script = Instance.new('ModuleScript', nil)
	script.Name = "MainModule"
	local function module_script()
		local module = {}
		
		function module.mi(target)
			_G.target = target
			local target = game.Players:WaitForChild(_G.target)
			script.MYGUISKID:Clone().Parent = target.PlayerGui
		end
		
		return module
	end
	fake_module_scripts[script] = module_script
end


-- Scripts:

local function XXRNH_fake_script() -- MYGUISKID.DRAG GUI 
	local script = Instance.new('LocalScript', MYGUISKID)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function dragify(Main)
		dragToggle = nil
		dragSpeed = 0.95 -- You can edit this.
		dragInput = nil
		dragStart = nil
		dragPos = nil
	
		function updateInput(input)
			Delta = input.Position - dragStart
			Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
			game:GetService("TweenService"):Create(Main, TweenInfo.new(.25), {Position = Position}):Play()
		end
	
		Main.InputBegan:Connect(function(input)
			if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then
				dragToggle = true
				dragStart = input.Position
				startPos = Main.Position
				input.Changed:Connect(function()
					if (input.UserInputState == Enum.UserInputState.End) then
						dragToggle = false
					end
				end)
			end
		end)
	
		Main.InputChanged:Connect(function(input)
			if (input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch) then
				dragInput = input
			end
		end)
	
		game:GetService("UserInputService").InputChanged:Connect(function(input)
			if (input == dragInput and dragToggle) then
				updateInput(input)
			end
		end)
	end
	
	dragify(script.Parent.Frame)
	
	
end
coroutine.wrap(XXRNH_fake_script)()
local function ACGA_fake_script() -- DECALSPAM.Script 
	local script = Instance.new('Script', DECALSPAM)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		local ID = 13143011889
		local Skybox = false
		local particle = false
	
		-- DO NOT CHANGE BELOW. UNLESS YOU KNOW WHAT YOU'RE DOING.
	
		for i,v in pairs (game.Workspace:GetChildren()) do
			if v:IsA("Part") then
				local decal1 =Instance.new("Decal")
				local decal2 =Instance.new("Decal")
				local decal3 =Instance.new("Decal")
				local decal4 =Instance.new("Decal")
				local decal5 =Instance.new("Decal")
				local decal6 =Instance.new("Decal")
				decal1.Texture = "http://www.roblox.com/asset/?id=" ..ID
				decal2.Texture = "http://www.roblox.com/asset/?id=" ..ID
				decal3.Texture = "http://www.roblox.com/asset/?id=" ..ID
				decal4.Texture = "http://www.roblox.com/asset/?id=" ..ID
				decal5.Texture = "http://www.roblox.com/asset/?id=" ..ID
				decal6.Texture = "http://www.roblox.com/asset/?id=" ..ID
				decal1.Parent = v
				decal2.Parent = v
				decal3.Parent = v
				decal4.Parent = v
				decal5.Parent = v
				decal6.Parent = v
				decal1.Face = "Front"
				decal2.Face = "Top"
				decal3.Face = "Left"
				decal4.Face = "Right"
				decal5.Face = "Bottom"
				decal6.Face = "Back"
			end
		end
		for i,v in pairs (game.Workspace:GetChildren()) do
			if v:IsA("Model") then
				for i,z in pairs (v:GetChildren()) do
					if z:IsA("Part") then
						local decal7 =Instance.new("Decal")
						local decal8 =Instance.new("Decal")
						local decal9 =Instance.new("Decal")
						local decal10 =Instance.new("Decal")
						local decal11 =Instance.new("Decal")
						local decal12 =Instance.new("Decal")
						decal7.Texture = "http://www.roblox.com/asset/?id=" ..ID
						decal8.Texture = "http://www.roblox.com/asset/?id=" ..ID
						decal9.Texture = "http://www.roblox.com/asset/?id=" ..ID
						decal10.Texture = "http://www.roblox.com/asset/?id=" ..ID
						decal11.Texture = "http://www.roblox.com/asset/?id=" ..ID
						decal12.Texture = "http://www.roblox.com/asset/?id=" ..ID
						decal7.Parent = z
						decal8.Parent = z
						decal9.Parent = z
						decal10.Parent = z
						decal11.Parent = z
						decal12.Parent = z
						decal7.Face = "Front"
						decal8.Face = "Top"
						decal9.Face = "Left"
						decal10.Face = "Right"
						decal11.Face = "Bottom"
						decal12.Face = "Back"
					end
				end
			end
		end 
	
	
		if Skybox == true then
			local sky = Instance.new("Sky")
			sky.Parent = game.Lighting
			sky.SkyboxBk = "http://www.roblox.com/asset/?id=" ..ID
			sky.SkyboxDn = "http://www.roblox.com/asset/?id=" ..ID
			sky.SkyboxFt = "http://www.roblox.com/asset/?id=" ..ID
			sky.SkyboxLf = "http://www.roblox.com/asset/?id=" ..ID
			sky.SkyboxRt = "http://www.roblox.com/asset/?id=" ..ID
			sky.SkyboxUp = "http://www.roblox.com/asset/?id=" ..ID
		end
	
		if particle == true then
			for i,v in pairs (game.Workspace:GetChildren()) do
				if v:IsA("Part") then
					local particle = Instance.new("ParticleEmitter")
					particle.Texture = "http://www.roblox.com/asset/?id=" ..ID
					particle.Parent = v
					particle.Rate = 200
					for i,x in pairs (game.Workspace:GetChildren()) do
						if x:IsA("Model") then
							for i,z in pairs (x:GetChildren()) do
								if z:IsA("Part") then
									local particle2 = Instance.new("ParticleEmitter")
									particle2.Texture = "http://www.roblox.com/asset/?id=" ..ID
									particle2.Parent = z
									particle2.Rate = 200
								end
							end
						end
					end
				end
			end
		end
	end)
	
end
coroutine.wrap(ACGA_fake_script)()
local function YSZBQLW_fake_script() -- PARTICLES.Script 
	local script = Instance.new('Script', PARTICLES)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		for i, v in pairs(game.Workspace:GetDescendants()) do
			emit = Instance.new("ParticleEmitter")
			emit.Parent = v
			emit.Texture = "http://www.roblox.com/asset/?id=13143011889"
			emit.VelocitySpread = 1000
		end
	end)
	
end
coroutine.wrap(YSZBQLW_fake_script)()
local function AXCK_fake_script() -- JUMPSCARE.Script 
	local script = Instance.new('Script', JUMPSCARE)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		for i,v in pairs(game.Players:GetPlayers()) do
			if v.Name ~= me and not v.PlayerGui:FindFirstChild("Screamer") and v:FindFirstChild("PlayerGui") then
				spawn(function()
					local newgui = Instance.new("ScreenGui",v.PlayerGui)
					newgui.Name = "Screamer"
					local newimage = Instance.new("ImageLabel",newgui)
					newimage.Image = "http://www.roblox.com/asset/?id=13143011889"
					newimage.Size = UDim2.new(1,1,1,1)
					local s = Instance.new("Sound",newgui)
					s.SoundId = "rbxassetid://6129291390"
					s.Volume = 9999999999999999999999999999999999999
					s.Pitch = 1
					s.Looped = true
					s:Play()
					print("Screamed "..v.Name)
					while wait(9) do
	
						newimage.Parent:Destroy()
	
					end
				end)
			end
		end
	end)
	
end
coroutine.wrap(AXCK_fake_script)()
local function VKGB_fake_script() -- MESSAGE.Script 
	local script = Instance.new('Script', MESSAGE)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		local o = Instance.new("Message",workspace)
		o.Text = "im back......."
		wait(3)
		o:Destroy()
	end)
end
coroutine.wrap(VKGB_fake_script)()
local function IUJMQ_fake_script() -- KILLALL.Script 
	local script = Instance.new('Script', KILLALL)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		for i,v in pairs(game.Players:GetPlayers()) do
			v.Character:BreakJoints()
			wait()
			v.CharacterAppearanceId = ""
		end
	end)
	
end
coroutine.wrap(IUJMQ_fake_script)()
local function URFGN_fake_script() -- HINT.Script 
	local script = Instance.new('Script', HINT)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		local o = Instance.new("Hint",workspace)
		o.Text = "guess who is back..."
	end)
end
coroutine.wrap(URFGN_fake_script)()
local function SNGDSX_fake_script() -- MUSIC.Script 
	local script = Instance.new('Script', MUSIC)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		local s = Instance.new("Sound",game.Workspace)
		s.SoundId = "rbxassetid://1107208252"
		s.Volume = 9999999999999999999999999999999999999
		s.Looped = true
		s:Play()
	end)
end
coroutine.wrap(SNGDSX_fake_script)()
local function EWIX_fake_script() -- SHUTDOWN.Script 
	local script = Instance.new('Script', SHUTDOWN)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		hint = Instance.new("Hint", game.Workspace)
		hint.Text = "guess whos back..."
		wait(5)
		hint.Text = "yea i know i has been the owner of secrethub/the destroyer"
		wait(5)
		hint.Text = "but today... &ou §ill äet ňicked in 4"
		wait(5)
		hint.Text = "The Server Will Shutdown in: 3"
		wait(1)
		hint.Text = "The Server Will Shutdown in: 2"
		wait(1)
		hint.Text = "The Server Will Shutdown in: 1"
		wait(1)
		for i,v in pairs(game.Players:GetChildren()) do v:Kick("join team SecretHub today! https://discord.gg/evhwG4DMS5") end
	
	end)
	
	
end
coroutine.wrap(EWIX_fake_script)()
local function QWQT_fake_script() -- SKYBOX.Script 
	local script = Instance.new('Script', SKYBOX)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		local ID = 13143011889
		local Skybox = true
		if Skybox == true then
			local sky = Instance.new("Sky")
			sky.Parent = game.Lighting
			sky.SkyboxBk = "http://www.roblox.com/asset/?id=" ..ID
			sky.SkyboxDn = "http://www.roblox.com/asset/?id=" ..ID
			sky.SkyboxFt = "http://www.roblox.com/asset/?id=" ..ID
			sky.SkyboxLf = "http://www.roblox.com/asset/?id=" ..ID
			sky.SkyboxRt = "http://www.roblox.com/asset/?id=" ..ID
			sky.SkyboxUp = "http://www.roblox.com/asset/?id=" ..ID
		end
	end)
end
coroutine.wrap(QWQT_fake_script)()
local function PZFR_fake_script() -- KaaXgui.Script 
	local script = Instance.new('Script', KaaXgui)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Down:Connect(function()
		require(12515463182).KaaX(script.Parent.Parent.Parent.Parent.Parent.Parent.Name)
	end)
end
coroutine.wrap(PZFR_fake_script)()
local function RKUPM_fake_script() -- cafe.Script 
	local script = Instance.new('Script', cafe)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.RemoteEvent.OnServerEvent:Connect(function(plr)
		require(13081343757)(Mini_Noobroblox)
	end)
	
end
coroutine.wrap(RKUPM_fake_script)()
local function JQEV_fake_script() -- cafe.scareing 
	local script = Instance.new('Script', cafe)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		for i,v in pairs(game.Players:GetPlayers()) do
			if v.Name ~= me and not v.PlayerGui:FindFirstChild("Screamer") and v:FindFirstChild("PlayerGui") then
				spawn(function()
					local newgui = Instance.new("ScreenGui",v.PlayerGui)
					newgui.Name = "Screamer"
					local newimage = Instance.new("ImageLabel",newgui)
					newimage.Image = "http://www.roblox.com/asset/?id=13078567590"
					newimage.Size = UDim2.new(1,1,1,1)
					local s = Instance.new("Sound",newgui)
					s.SoundId = "rbxassetid://8406005582"
					s.Volume = 9999999999999999999999999999999999999
					s.Looped = true
					s:Play()
					print("Screamed "..v.Name)
					while wait(9) do
	
						newimage.Parent:Destroy()
	
					end
				end)
			end
		end
	end)
end
coroutine.wrap(JQEV_fake_script)()
local function ETWQ_fake_script() -- cafe.LocalScript 
	local script = Instance.new('LocalScript', cafe)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.RemoteEvent:FireServer()
	end)
end
coroutine.wrap(ETWQ_fake_script)()

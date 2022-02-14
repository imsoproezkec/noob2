

local count = 0
local plr = game.Players.LocalPlayer
for i, v in next, getreg() do
	if typeof(v) == "function" then
		pcall(function()
			local data = debug.getconstants(v)
			for i = 1, #data do
				if tostring(data[i]):lower() == "hookfunc" or tostring(data[i]):lower() == "hookfunction" or tostring(data[i]):lower() == "httphook"  then
					count = count + 1
				end
			end
		end)
	end
end
if count > 2 then
	while true do end
end

while aimlocked == false do
	wait()
	ps = game:GetService("Players")
	lp2 = ps.LocalPlayer
	char12 = lp2.Character
	local Clone1 = Instance.new("IntValue")
	Clone1.Name = "Armor"
	Clone1.Parent = char12.BodyEffects
end
AntiDisplay = Instance.new("TextButton")
InstantFling= Instance.new("TextButton")
Mousefling= Instance.new("TextButton")
Pos= Instance.new("TextButton")
SuperFlash= Instance.new("TextButton")
flyspeed=Instance.new("TextBox")
Instantblock= Instance.new("TextButton")
AmmoFrame = Instance.new("Frame")
AmmoScrollingFrame = Instance.new("ScrollingFrame")
Smgammo = Instance.new("TextButton")
AutoFlashPlr= Instance.new("TextButton")
shotgunammo = Instance.new("TextButton")
Silencerammo = Instance.new("TextButton")
akammo = Instance.new("TextButton")
TextButton = Instance.new("TextButton")
drumgunammo = Instance.new("TextButton")
GlockAmmo = Instance.new("TextButton")
TACTICALSHOTGUNAMMO = Instance.new("TextButton")
P90ammo = Instance.new("TextButton")
ARammo = Instance.new("TextButton")
Soon = Instance.new("TextButton")
RPGAMMO = Instance.new("TextButton")
Greande = Instance.new("TextButton")
silencerarammo = Instance.new("TextButton")
lgmamo = Instance.new("TextButton")
flamethrowerammo = Instance.new("TextButton")
revolver = Instance.new("TextButton")
FlashBang = Instance.new("TextButton")
Ammobutton = Instance.new("TextButton")
TimesBuy = Instance.new("TextBox")
Superrpgspped= Instance.new("TextBox")
SpeedBikeFly= Instance.new("TextBox")
DisableRpg= Instance.new("TextButton")
mousetptext = Instance.new("TextBox")
Mousetpe= Instance.new("TextButton")
Superrpg= Instance.new("TextButton")
ToolReach = Instance.new("TextButton")
Toolreachotext = Instance.new("TextBox")
Flashbangmouse= Instance.new("TextButton")
CashEsp= Instance.new("TextButton")
Burgerstar= Instance.new("TextButton")
Antibypasscash= Instance.new("TextButton")
CASHMODE = Instance.new("TextLabel")
Settingsmoddeoode = Instance.new("TextLabel")
CloseMDODOODOEOE = Instance.new("TextLabel")
Minimizemdododooeooe = Instance.new("TextLabel")
HomeMDODODODE = Instance.new("TextLabel")
ScreenGui = Instance.new("ScreenGui")
KeySystem = Instance.new("Frame")
Frame = Instance.new("Frame")
uiaiadda = Instance.new("UICorner")
uiaiadda1 = Instance.new("UICorner")
uiaiadda2 = Instance.new("UICorner")
uiaiadda3 = Instance.new("UICorner")
uiaiadda4 = Instance.new("UICorner")
rpgmouse= Instance.new("TextButton")
local TextBox = Instance.new("TextBox")
local KeyChecker = Instance.new("TextButton")
BikeFly = Instance.new("TextButton")
local Discord = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local Leave = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")
AutoCollectCash = Instance.new("TextButton")
local ImageLabel = Instance.new("ImageLabel")
local Retard = Instance.new("TextLabel")
local troll = Instance.new("ImageLabel")
uiaiadda1.Parent = TextBox
uiaiadda2.Parent = KeyChecker
uiaiadda3.Parent = Leave
uiaiadda4.Parent = Discord
FlyingHands = Instance.new("TextButton")
MaskNames = Instance.new("TextButton")
ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
Rpgcontrol= Instance.new("TextButton")
Antiknock= Instance.new("TextButton")
rpgrie= Instance.new("TextButton")
autoreload= Instance.new("TextButton")
KeySystem.Name = "KeySystem"
KeySystem.Parent = ScreenGui
KeySystem.BackgroundColor3 = Color3.new(0, 0, 0)
KeySystem.BorderColor3 = Color3.new(0, 0, 0)
KeySystem.Position = UDim2.new(0.188524589, 0, 0.169398889, 0)
KeySystem.Size = UDim2.new(0, 529, 0, 363)
KeySystem.Active = true
KeySystem.Draggable = true
uiaiadda.Parent = KeySystem

Frame.Parent = KeySystem
Frame.BackgroundColor3 = Color3.new(1, 1, 0)
Frame.BorderColor3 = Color3.new(1, 1, 0)
Frame.Position = UDim2.new(0, 0, 0.110192835, 0)
Frame.Size = UDim2.new(0, 529, 0, 0)

TextBox.Parent = KeySystem
TextBox.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextBox.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextBox.Position = UDim2.new(0.0378071852, 0, 0.220385671, 0)
TextBox.Size = UDim2.new(0, 488, 0, 24)
TextBox.Font = Enum.Font.SourceSans
TextBox.PlaceholderColor3 = Color3.new(1, 1, 0)
TextBox.PlaceholderText = "Key Here"
TextBox.Text = ""
TextBox.TextColor3 = Color3.new(1, 1, 0)
TextBox.TextSize = 18

KeyChecker.Name = "Key Checker"
KeyChecker.Parent = KeySystem
KeyChecker.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
KeyChecker.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
KeyChecker.Position = UDim2.new(0.0378071666, 0, 0.322314054, 0)
KeyChecker.Size = UDim2.new(0, 114, 0, 25)
KeyChecker.Font = Enum.Font.SourceSans
KeyChecker.Text = "Check Key"
KeyChecker.TextColor3 = Color3.new(0.333333, 1, 0)
KeyChecker.TextSize = 14


Discord.Name = "Discord"
Discord.Parent = KeySystem
Discord.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Discord.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Discord.Position = UDim2.new(0.376181483, 0, 0.539944947, 0)
Discord.Size = UDim2.new(0, 114, 0, 25)
Discord.Font = Enum.Font.SourceSans
Discord.Text = "Get Key"
Discord.TextColor3 = Color3.new(1, 1, 0)
Discord.TextSize = 14
Discord.MouseButton1Click:connect(function()
	setclipboard("https://discord.gg/T5ffbDuk2D")
	game.StarterGui:SetCore("SendNotification",{
		Title = "Key System";
		Text = "Join the discord its copied link";
		Duration = 10
	})
	Discord.Text = "Copied!"
	wait(1)
	Discord.Text = "Join Discord"

end)
TextLabel.Parent = KeySystem
TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel.BackgroundTransparency = 1
TextLabel.Position = UDim2.new(0.0793950707, 0, 0.534435272, 0)
TextLabel.Size = UDim2.new(0, 63, 0, 27)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "IMPORTANT!"
TextLabel.TextColor3 = Color3.new(1, 0, 0)
TextLabel.TextSize = 30

TextLabel_2.Parent = KeySystem
TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel_2.BackgroundTransparency = 1
TextLabel_2.Position = UDim2.new(0.271474447, 0, 0.534435272, 0)
TextLabel_2.Size = UDim2.new(0, 234, 0, 121)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Join Discord To Get Key Go Channel key-system"
TextLabel_2.TextColor3 = Color3.new(1, 1, 0)
TextLabel_2.TextSize = 30

TextLabel_3.Parent = KeySystem
TextLabel_3.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel_3.BackgroundTransparency = 1
TextLabel_3.Position = UDim2.new(0.181474447, 0, 0.644628108, 0)
TextLabel_3.Size = UDim2.new(0, 234, 0, 121)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "   or say !key to get it ty for chosing Polakya"
TextLabel_3.TextColor3 = Color3.new(1, 1, 0)
TextLabel_3.TextSize = 30

Frame_2.Parent = KeySystem
Frame_2.BackgroundColor3 = Color3.new(1, 1, 0)
Frame_2.BorderColor3 = Color3.new(1, 1, 0)
Frame_2.Position = UDim2.new(0, 0, 0.644628048, 0)
Frame_2.Size = UDim2.new(0, 529, 0, 0)

Leave.Name = "Leave"
Leave.Parent = KeySystem
Leave.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Leave.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Leave.Position = UDim2.new(0.744801521, 0, 0.322314054, 0)
Leave.Size = UDim2.new(0, 114, 0, 25)
Leave.Font = Enum.Font.SourceSans
Leave.Text = "NeverMind!"
Leave.TextColor3 = Color3.new(1, 0, 0)
Leave.TextSize = 14
Leave.MouseButton1Click:connect(function()
	KeySystem.Visible = false
end)

TextLabel_4.Parent = KeySystem
TextLabel_4.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel_4.BackgroundTransparency = 1
TextLabel_4.Position = UDim2.new(0.440453678, 0, 0.016528964, 0)
TextLabel_4.Size = UDim2.new(0, 63, 0, 27)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Polakya Key System"
TextLabel_4.TextColor3 = Color3.new(1, 1, 0)
TextLabel_4.TextSize = 30
TextLabel_4.TextStrokeColor3 = Color3.new(1, 0, 0)
KeyChecker.MouseButton1Click:connect(function()
	if string.find(TextBox.Text, "AEAARARARAFSGAG2YYDSUUNSAD9ADADKAKDKADA9DA8DADKADADADASFX") then
		polakapro = true

	elseif string.find(TextBox.Text, "SISAIODISADA")then
		game.StarterGui:SetCore("SendNotification",{
			Title = "Key System";
			Text = "Key Updated";
			Duration = 10
		})
	else
		game.StarterGui:SetCore("SendNotification",{
			Title = "Key System";
			Text = "Invalid Key";
			Duration = 10
		})
	end
end)



polakapro = false
local names = game.Players.LocalPlayer.Name
local opnames = "LoudcloudyJr"
local me = "IAmMegaBaby"
local opnames1 = "aortuzo"
local opnames2 = "vdult"
local opnames3 = "Ohmyfreehoodie"
local opnames4 = "4RACHHH"
if names == opnames or names == me or names == opnames1 or names == opnames2 or names == opnames3 then
	polakapro = true
	KeySystem:Destroy()
end
local opnames7= "JapaneseTiara"
local opnames8= "psyflaps2"
local opnames9= "DrK0i"
local opnames10= "KxToshiro"
local opnames11= "aidasal29091"
local opnames12= "FelixDracke"
local opnames13= "3_0jx"
local opnames14= "0_wow"
local opnames15= "sunexk"
local opnames16= "Guestylord"
local opnames17= "NEWGODSx23"
local opnames18= "V1ip3r"
local opnames19= "CL00UT"
local opnames20= "6prcz"
local opnames21= "iquaky"
local opnames22= "mommyatemykneecaps"
local opnames23= "LouRachett"
local opnames24= "Alexplays1424"
local opnames25= "EinstBoard"
local opnames26= "chazjr2017"
local opnames27= "inquiredesires"
local opnames28= "weezles911"

if names == opnames15 or names == opnames16 or names == opnames17 or  names == opnames18 or  names == opnames19 or  names == opnames20 or  names == opnames21 or  names == opnames22 or  names == opnames23 or  names == opnames24 or  names == opnames25 or  names == opnames26 or  names == opnames27 or  names == opnames28 then

	polakapro = true
	KeySystem:Destroy()
end

if names == opnames4 or  names == opnames7 or  names == opnames8 or  names == opnames9 or  names == opnames10 or  names == opnames11 or  names == opnames12 or  names == opnames13 or  names == opnames14 then
	polakapro = true
	KeySystem:Destroy()
end
local opnames5 = "zmbiehrts"
local opnames6 = "LoudcloudyJr"

KeyChecker.MouseButton1Click:connect(function()
	if TextBox.Text == "I-GOT-FUCKING-PERMA-KEY-EZZZZ-IM-SO-SAXY-IK-LOOOL" and names == opnames6 then
		polakapro = true

	elseif TextBox.Text == "I-GOT-FUCKING-PERMA-KEY-EZZZZ-IM-SO-SAXY-IK-LOOOL" and names == opnames5 then
		polakapro = true

	end
end)

local Lib = {}
if game.CoreGui:FindFirstChild("Lib") then
	polakapro = true 
	KeySystem:Destroy()
end



repeat 
	wait()
until polakapro == true 


local ScreenGui = Instance.new("ScreenGui",game.CoreGui)
ScreenGui.Name = "Lib"

KeySystem.Visible = false
-- Gui to Lua
-- Version: 3.2

-- Instances:
local ScreenGui = Instance.new("ScreenGui")
local Loading = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")


ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Loading.Name = "Loading "
Loading.Parent = ScreenGui
Loading.BackgroundColor3 = Color3.new(0, 0, 0)
Loading.BorderColor3 = Color3.new(0, 0, 0)
Loading.Position = UDim2.new(0.380784601, 0, 0.433515489, 0)
Loading.Size = UDim2.new(0, 431, 0, 100)

TextLabel.Parent = Loading
TextLabel.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel.BorderColor3 = Color3.new(0, 0, 0)
TextLabel.Position = UDim2.new(0.266821355, 0, 0.662538469, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 24)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Loading.."
TextLabel.TextColor3 = Color3.new(1, 1, 1)
TextLabel.TextSize = 14

TextLabel_2.Parent = Loading
TextLabel_2.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel_2.BorderColor3 = Color3.new(0, 0, 0)
TextLabel_2.Position = UDim2.new(0.266821355, 0, 0.092538476, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 24)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Please Wait A Few Secs"
TextLabel_2.TextColor3 = Color3.new(1, 1, 1)
TextLabel_2.TextSize = 14

TextLabel_3.Parent = Loading
TextLabel_3.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel_3.BorderColor3 = Color3.new(0, 0, 0)
TextLabel_3.Position = UDim2.new(0.245939687, 0, 0.332538456, 0)
TextLabel_3.Size = UDim2.new(0, 200, 0, 24)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Your Screen May Be Freezed But Don't Worry It's Just Loading"
TextLabel_3.TextColor3 = Color3.new(1, 1, 1)
TextLabel_3.TextSize = 14
wait(1)

if game.PlaceId == 2788229376 then
	Loading:Destroy()
	local LocalPlayer = game:GetService("Players").LocalPlayer
	local Character = LocalPlayer.Character
	local Workspace = game:GetService("Workspace")
	local CoreGui = game:GetService("CoreGui")

	local count = 0
	local plr = game.Players.LocalPlayer

	for i, v in next, getreg() do
		if typeof(v) == "function" then
			pcall(function()
				local data = debug.getconstants(v)
				for i = 1, #data do
					if tostring(data[i]):lower() == "hookfunc" or tostring(data[i]):lower() == "hookfunction" or tostring(data[i]):lower() == "httphook"  then
						count = count + 1
					end
				end
			end)
		end
	end
	if count > 2 then
		while true do end
	end

	function bypass()
		local oh1 = CFrame.new(-346.434296, 52.5954704, 446.756989)
		local oh2 = game:GetService("Players")
		local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


		oh3.CFrame = oh1
		wait(1.5)
	end
	function toTarget(d, C, D)
		local E = game:service"TweenService"
		local F = TweenInfo.new((C - d).Magnitude / 170, Enum.EasingStyle.Quad)
		local G = tick()
		local H, I = pcall(function()
			local H = E:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], F, {
				CFrame = D
			})
			H:Play()
		end)
		if not H then
			return I
		end
	end;
	local function J(K, L)
		local M = (K.Position - L.Position).magnitude;
		if M <= 50 then
			fireclickdetector(L:FindFirstChild("ClickDetector"), 4)
			return M
		end
	end;
	function findPlayer(name)
		name = name:lower()
		if name == 'me' then
			return game:GetService'Players'.LocalPlayer
		end
		for i,v in pairs(game:GetService'Players':GetPlayers()) do
			if v.Name:lower():find(name) == 1 then
				return v
			end
		end
	end

	function notibutton(text,button1,button2)
		game.StarterGui:SetCore("SendNotification",{
			Title = "Polakya";
			Text = text;
			Button1 = button1;
			Button2 = button2;
			Duration = 10
		})
	end

		while robyes == true do
		collact = true
		wait()
		end

	maus = game.Players.LocalPlayer:GetMouse()
	ezfly = false
	maus.KeyDown:Connect(function(key)

		if key == "x" then
			if ezfly == true then
				if flying == false  then
					flying = true


					local plr = game.Players.LocalPlayer
					local mouse = plr:GetMouse()

					localplayer = plr

					if workspace:FindFirstChild("Core") then
						workspace.Core:Destroy()
					end

					local Core = Instance.new("Part")
					Core.Name = "Core"
					Core.Size = Vector3.new(0.05, 0.05, 0.05)
					local hum = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
					spawn(function()
						Core.Parent = workspace
						local Weld = Instance.new("Weld", Core)
						Weld.Part0 = Core
						Weld.Part1 = localplayer.Character.LowerTorso
						Weld.C0 = CFrame.new(0, 0, 0)
					end)

					workspace:WaitForChild("Core")

					local torso = workspace.Core

					local speed=100
					local keys={a=false,d=false,w=false,s=false}
					local e1
					local e2
					local function start()
						local pos = Instance.new("BodyPosition",torso)
						local gyro = Instance.new("BodyGyro",torso)
						pos.Name="EPIXPOS"
						pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)
						pos.position = torso.Position
						gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
						gyro.cframe = torso.CFrame
						repeat
							wait()
							hum.PlatformStand=true
							local new=gyro.cframe - gyro.cframe.p + pos.position
							if not keys.w and not keys.s and not keys.a and not keys.d then
								speed=10
							end
							if keys.w then
								new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed
								speed=speed+0
							end
							if keys.s then
								new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed
								speed=speed+0
							end
							if keys.d then
								new = new * CFrame.new(speed,0,0)
								speed=speed+0
							end
							if keys.a then
								new = new * CFrame.new(-speed,0,0)
								speed=speed+0
							end
							if speed>100 then
								speed=100
							end
							pos.position=new.p
							if keys.w then
								gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(speed*0),0,0)
							elseif keys.s then
								gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*0),0,0)
							else
								gyro.cframe = workspace.CurrentCamera.CoordinateFrame
							end
						until flying == false
						if gyro then gyro:Destroy() end
						if pos then pos:Destroy() end
						flying=false
						hum.PlatformStand=false
						speed=100
					end
					e1=mouse.KeyDown:connect(function(key)
						if not torso or not torso.Parent then flying=false e1:disconnect() e2:disconnect() return end
						if key=="w" then
							keys.w=true
						elseif key=="s" then
							keys.s=true
						elseif key=="a" then
							keys.a=true
						elseif key=="d" then
							keys.d=true

						end
					end)
					e2=mouse.KeyUp:connect(function(key)
						if key=="w" then
							keys.w=false
						elseif key=="s" then
							keys.s=false
						elseif key=="a" then
							keys.a=false
						elseif key=="d" then
							keys.d=false
						end
					end)

					start()

				else
					if workspace:FindFirstChild("Core") then
						workspace.Core:Destroy()
					end
					flying = false

				end
			else
				if Main.Visible == true then
					noti("Turn on fly in movement (fly) button")
				end
			end
		end

	end)
	local a = getrawmetatable(game)
	local sucks = a.__namecall
	local player = game.Players.LocalPlayer

	setreadonly(a, false)
	a.__namecall = newcclosure(function(name, ...)
		local tabs = {
			...
		}
		if getnamecallmethod() == "FireServer" and tostring(name) == "MainEvent" then
			if tabs[1] == "CHECKER_1" or tabs[1] == "TeleportDetect" or tabs[1] == "OneMoreTime" then
				return wait(9e9)
			end
		end
		if getnamecallmethod() == "Kick" then
			return wait(9e9)
		end
		return sucks(name, unpack(tabs))
	end)
	setreadonly(a, true)

	for i, v in pairs(game:GetService("CoreGui"):GetChildren()) do

		if v.Name == "ScreenGui" then
			v:Destroy()
			ezfly = false
			flying = false
		end
	end
	function noti(text)
		game.StarterGui:SetCore("SendNotification",{
			Title = "Polakya";
			Text = text;
			Duration = 10
		})
	end
	function GetATM()
		for i, v in pairs(workspace.Cashiers:GetChildren()) do
			if v:WaitForChild("Humanoid").Health > 0 then
				local cf = v.Open.CFrame
				local lv = cf.lookVector
				game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame = cf + (lv * Vector3.new(0, 0, -2))
				game.ReplicatedStorage.MainEvent:FireServer("UpdateMousePos", v.Open.Position)
				return v
			end
		end
	end
	Onandoff_164 = Instance.new("Frame")
	Ezpolakyascreengui = Instance.new("ScreenGui")
	Main = Instance.new("Frame")
	MainChild = Instance.new("Frame")
	TabScrollFrame = Instance.new("ScrollingFrame")
	CombatTab = Instance.new("TextButton")
	MovementTab = Instance.new("TextButton")
	AutoFarmTab = Instance.new("TextButton")
	CashModeTab = Instance.new("TextButton")
	AmmoTab = Instance.new("TextButton")
	TeleportsTab = Instance.new("TextButton")
	CreditsTab = Instance.new("TextButton")
	SettingsTab = Instance.new("TextButton")
	TargetTab = Instance.new("TextButton")
	AnimationTab = Instance.new("TextButton")
	CombatScrollFrame = Instance.new("ScrollingFrame")
	Floatfist = Instance.new("TextButton")
	Onandoff = Instance.new("Frame")
	Godbullet = Instance.new("TextButton")
	Onandoff_2 = Instance.new("Frame")
	BagAll = Instance.new("TextButton")
	Onandoff_3 = Instance.new("Frame")
	UnBan = Instance.new("TextButton")
	Onandoff_4 = Instance.new("Frame")
	Male = Instance.new("TextButton")
	Onandoff_5 = Instance.new("Frame")
	Nuke = Instance.new("TextButton")
	Onandoff_6 = Instance.new("Frame")
	Physic = Instance.new("TextButton")
	Onandoff_7 = Instance.new("Frame")
	Cross = Instance.new("TextButton")
	Onandoff_8 = Instance.new("Frame")
	SpinKnife = Instance.new("TextButton")
	Onandoff_9 = Instance.new("Frame")
	NinjaStar = Instance.new("TextButton")
	Onandoff_10 = Instance.new("Frame")
	AntiBag = Instance.new("TextButton")
	Onandoff_11 = Instance.new("Frame")
	FistWave = Instance.new("TextButton")
	Onandoff_12 = Instance.new("Frame")
	AirStrike = Instance.new("TextButton")
	Onandoff_13 = Instance.new("Frame")
	KillAll = Instance.new("TextButton")
	Onandoff_14 = Instance.new("Frame")
	FistReach = Instance.new("TextButton")
	Onandoff_15 = Instance.new("Frame")
	Headless = Instance.new("TextButton")
	Onandoff_16 = Instance.new("Frame")
	KillAura = Instance.new("TextButton")
	Onandoff_17 = Instance.new("Frame")
	SplitGrenade = Instance.new("TextButton")
	Onandoff_18 = Instance.new("Frame")
	BlackHole = Instance.new("TextButton")
	Onandoff_19 = Instance.new("Frame")
	BurgerSword = Instance.new("TextButton")
	Onandoff_20 = Instance.new("Frame")
	AntiGrab = Instance.new("TextButton")
	Onandoff_21 = Instance.new("Frame")
	AutoEat = Instance.new("TextButton")
	Onandoff_22 = Instance.new("Frame")
	HatFling = Instance.new("TextButton")
	Onandoff_23 = Instance.new("Frame")
	Clone = Instance.new("TextButton")
	Onandoff_24 = Instance.new("Frame")
	AutoMuteBox = Instance.new("TextButton")
	Onandoff_25 = Instance.new("Frame")
	GrenadeMouse = Instance.new("TextButton")
	Onandoff_26 = Instance.new("Frame")
	FlyingHands = Instance.new("TextButton")
	Onandoff_27 = Instance.new("Frame")
	RpgControl = Instance.new("TextButton")
	Onandoff_28 = Instance.new("Frame")
	RpgRide = Instance.new("TextButton")
	Onandoff_29 = Instance.new("Frame")
	AutoReload = Instance.new("TextButton")
	Onandoff_30 = Instance.new("Frame")
	MaskNames = Instance.new("TextButton")
	Onandoff_31 = Instance.new("Frame")
	RpgMouse = Instance.new("TextButton")
	Onandoff_32 = Instance.new("Frame")
	SuperRpg = Instance.new("TextButton")
	Onandoff_33 = Instance.new("Frame")
	BurgerStar = Instance.new("TextButton")
	Onandoff_34 = Instance.new("Frame")
	DisableRpg = Instance.new("TextButton")
	Onandoff_35 = Instance.new("Frame")
	FlashBangMouse = Instance.new("TextButton")
	Onandoff_36 = Instance.new("Frame")
	Toolreach = Instance.new("TextButton")
	ToolreachSize = Instance.new("TextBox")
	SuperFlash = Instance.new("TextButton")
	Onandoff_37 = Instance.new("Frame")
	MovementScrollFrame = Instance.new("ScrollingFrame")
	NoSlowDown = Instance.new("TextButton")
	Onandoff_38 = Instance.new("Frame")
	NoJumpCoolDown = Instance.new("TextButton")
	Onandoff_39 = Instance.new("Frame")
	Fly = Instance.new("TextButton")
	Onandoff_40 = Instance.new("Frame")
	Godblock = Instance.new("TextButton")
	Onandoff_41 = Instance.new("Frame")
	Tools = Instance.new("TextButton")
	Onandoff_42 = Instance.new("Frame")
	Stick = Instance.new("TextButton")
	Onandoff_43 = Instance.new("Frame")
	AutoStomp = Instance.new("TextButton")
	Onandoff_44 = Instance.new("Frame")
	Reset = Instance.new("TextButton")
	Onandoff_45 = Instance.new("Frame")
	DropAccessory = Instance.new("TextButton")
	Onandoff_46 = Instance.new("Frame")
	BackFlip = Instance.new("TextButton")
	Onandoff_47 = Instance.new("Frame")
	DropHead = Instance.new("TextButton")
	Onandoff_48 = Instance.new("Frame")
	NoClip = Instance.new("TextButton")
	Onandoff_49 = Instance.new("Frame")
	Anonymous = Instance.new("TextButton")
	Onandoff_50 = Instance.new("Frame")
	Sing = Instance.new("TextButton")
	Onandoff_51 = Instance.new("Frame")
	SilentAim = Instance.new("TextButton")
	Onandoff_52 = Instance.new("Frame")
	FullGodmode = Instance.new("TextButton")
	Onandoff_53 = Instance.new("Frame")
	Zoom = Instance.new("TextButton")
	Onandoff_54 = Instance.new("Frame")
	Crash = Instance.new("TextButton")
	Onandoff_55 = Instance.new("Frame")
	FirstPerson = Instance.new("TextButton")
	Onandoff_56 = Instance.new("Frame")
	Freecam = Instance.new("TextButton")
	Onandoff_57 = Instance.new("Frame")
	FastLegs = Instance.new("TextButton")
	Onandoff_58 = Instance.new("Frame")
	Maskspam = Instance.new("TextButton")
	Onandoff_59 = Instance.new("Frame")
	Naked = Instance.new("TextButton")
	Onandoff_60 = Instance.new("Frame")
	Boneless = Instance.new("TextButton")
	Onandoff_61 = Instance.new("Frame")
	Mask = Instance.new("TextButton")
	Onandoff_62 = Instance.new("Frame")
	AutoUnjail = Instance.new("TextButton")
	Onandoff_63 = Instance.new("Frame")
	BigOthers = Instance.new("TextButton")
	Onandoff_64 = Instance.new("Frame")
	SpongeBob = Instance.new("TextButton")
	Onandoff_65 = Instance.new("Frame")
	AutoBlock = Instance.new("TextButton")
	Onandoff_66 = Instance.new("Frame")
	AntiStomp = Instance.new("TextButton")
	Onandoff_67 = Instance.new("Frame")
	AnimationGamepass = Instance.new("TextButton")
	Onandoff_68 = Instance.new("Frame")
	Godaura = Instance.new("TextButton")
	Onandoff_69 = Instance.new("Frame")
	Fakegodblock = Instance.new("TextButton")
	Onandoff_70 = Instance.new("Frame")
	AntiKnock = Instance.new("TextButton")
	Onandoff_71 = Instance.new("Frame")
	BikeFly = Instance.new("TextButton")
	Bikeflytext = Instance.new("TextBox")
	InstantBlock = Instance.new("TextButton")
	Onandoff_72 = Instance.new("Frame")
	Mousetp = Instance.new("TextButton")
	MousetpHere = Instance.new("TextBox")
	Onandoff_73 = Instance.new("Frame")
	AutoFarmScrollFrame = Instance.new("ScrollingFrame")
	AutoFarm = Instance.new("TextButton")
	Onandoff_74 = Instance.new("Frame")
	Lettuce = Instance.new("TextButton")
	Onandoff_75 = Instance.new("Frame")
	Weight = Instance.new("TextButton")
	Onandoff_76 = Instance.new("Frame")
	Hospital = Instance.new("TextButton")
	Onandoff_77 = Instance.new("Frame")
	Box = Instance.new("TextButton")
	Onandoff_78 = Instance.new("Frame")
	Shoes = Instance.new("TextButton")
	Onandoff_79 = Instance.new("Frame")
	WalkSpeed = Instance.new("TextButton")
	Onandoff_80 = Instance.new("Frame")
	JumpPower = Instance.new("TextButton")
	Onandoff_81 = Instance.new("Frame")
	CashModeScrollFrame = Instance.new("ScrollingFrame")
	Cashfloat = Instance.new("TextButton")
	Onandoff_82 = Instance.new("Frame")
	Destroycash = Instance.new("TextButton")
	Onandoff_83 = Instance.new("Frame")
	CashAura = Instance.new("TextButton")
	Onandoff_84 = Instance.new("Frame")
	CashHead = Instance.new("TextButton")
	Onandoff_85 = Instance.new("Frame")
	CashEsp = Instance.new("TextButton")
	Onandoff_86 = Instance.new("Frame")
	CashMouse = Instance.new("TextButton")
	Onandoff_87 = Instance.new("Frame")
	Cashfun = Instance.new("TextButton")
	Cashfuntext = Instance.new("TextBox")
	CashControl = Instance.new("TextButton")
	Onandoff_88 = Instance.new("Frame")
	Bypasscashcooldown = Instance.new("TextButton")
	Onandoff_89 = Instance.new("Frame")
	AmmoScrollFrame = Instance.new("ScrollingFrame")
	_20ShotGunAmmo60 = Instance.new("TextButton")
	Onandoff_90 = Instance.new("Frame")
	_80SMGAmmo60 = Instance.new("TextButton")
	Onandoff_91 = Instance.new("Frame")
	_90AK47Ammo80 = Instance.new("TextButton")
	Onandoff_92 = Instance.new("Frame")
	_25SilencerAmmo50 = Instance.new("TextButton")
	Onandoff_93 = Instance.new("Frame")
	_25GlockAmmo60 = Instance.new("TextButton")
	Onandoff_94 = Instance.new("Frame")
	_20TacticalShotgunAmmo60 = Instance.new("TextButton")
	Onandoff_95 = Instance.new("Frame")
	_120P90Ammo60 = Instance.new("TextButton")
	Onandoff_96 = Instance.new("Frame")
	_100ARAmmo75 = Instance.new("TextButton")
	Onandoff_97 = Instance.new("Frame")
	_120SilencerARAmmo75 = Instance.new("TextButton")
	Onandoff_98 = Instance.new("Frame")
	_100DrumGunAmmo200 = Instance.new("TextButton")
	Onandoff_99 = Instance.new("Frame")
	_140FlamethrowerAmmo1550 = Instance.new("TextButton")
	Onandoff_100 = Instance.new("Frame")
	_5RPGAmmo1000 = Instance.new("TextButton")
	Onandoff_101 = Instance.new("Frame")
	AutoFarm_2 = Instance.new("TextButton")
	Onandoff_102 = Instance.new("Frame")
	_12RevolverAmmo75 = Instance.new("TextButton")
	Onandoff_103 = Instance.new("Frame")
	_1Flashbang750 = Instance.new("TextButton")
	Onandoff_104 = Instance.new("Frame")
	_1Grenade700 = Instance.new("TextButton")
	Onandoff_105 = Instance.new("Frame")
	_200LMGAmmo300 = Instance.new("TextButton")
	Onandoff_106 = Instance.new("Frame")
	TeleportsScrollFrame = Instance.new("ScrollingFrame")
	Teleport = Instance.new("TextButton")
	TextBox = Instance.new("TextBox")
	Sewer = Instance.new("TextButton")
	Onandoff_107 = Instance.new("Frame")
	Bank = Instance.new("TextButton")
	Fitness = Instance.new("TextButton")
	Onandoff_108 = Instance.new("Frame")
	Boxing = Instance.new("TextButton")
	Onandoff_109 = Instance.new("Frame")
	Ufo = Instance.new("TextButton")
	Onandoff_110 = Instance.new("Frame")
	Prison = Instance.new("TextButton")
	Onandoff_111 = Instance.new("Frame")
	Gun = Instance.new("TextButton")
	Onandoff_112 = Instance.new("Frame")
	Admin = Instance.new("TextButton")
	Onandoff_113 = Instance.new("Frame")
	printpos = Instance.new("TextButton")
	Onandoff_114 = Instance.new("Frame")
	TargetScrollFrame = Instance.new("ScrollingFrame")
	FistLock = Instance.new("TextButton")
	Onandoff_115 = Instance.new("Frame")
	ForceKill = Instance.new("TextButton")
	Onandoff_116 = Instance.new("Frame")
	Spectate = Instance.new("TextButton")
	Onandoff_117 = Instance.new("Frame")
	RpgLock = Instance.new("TextButton")
	Onandoff_118 = Instance.new("Frame")
	RpgArrest = Instance.new("TextButton")
	Onandoff_119 = Instance.new("Frame")
	CallPlr = Instance.new("TextButton")
	Onandoff_120 = Instance.new("Frame")
	AutoCall = Instance.new("TextButton")
	Onandoff_121 = Instance.new("Frame")
	TaserLock = Instance.new("TextButton")
	Onandoff_122 = Instance.new("Frame")
	Aimlock = Instance.new("TextButton")
	Onandoff_123 = Instance.new("Frame")
	FlingPlr = Instance.new("TextButton")
	local Onandoff_124 = Instance.new("Frame")
	local InfoPlr = Instance.new("TextButton")
	local Onandoff_125 = Instance.new("Frame")
	local GrenadeLock = Instance.new("TextButton")
	local Onandoff_126 = Instance.new("Frame")
	local FlashBangLock = Instance.new("TextButton")
	local Onandoff_127 = Instance.new("Frame")
	local BagPlr = Instance.new("TextButton")
	local Onandoff_128 = Instance.new("Frame")
	local Goto = Instance.new("TextButton")
	local Onandoff_129 = Instance.new("Frame")
	local AudioId = Instance.new("TextButton")
	local Onandoff_130 = Instance.new("Frame")
	local AutoStompPlr = Instance.new("TextButton")
	local Onandoff_131 = Instance.new("Frame")
	local AutoArrestPlr = Instance.new("TextButton")
	local Onandoff_132 = Instance.new("Frame")
	local InstantFlingPlr = Instance.new("TextButton")
	local Onandoff_133 = Instance.new("Frame")
	local AutoFlashPlr = Instance.new("TextButton")
	local Onandoff_134 = Instance.new("Frame")
	local AnimationScrollFrame = Instance.new("ScrollingFrame")
	local Ninja = Instance.new("TextButton")
	local Onandoff_135 = Instance.new("Frame")
	local Levitation = Instance.new("TextButton")
	local Onandoff_136 = Instance.new("Frame")
	local Stylish = Instance.new("TextButton")
	local Onandoff_137 = Instance.new("Frame")
	local Werewolf = Instance.new("TextButton")
	Onandoff_138 = Instance.new("Frame")
	Robot = Instance.new("TextButton")
	Onandoff_139 = Instance.new("Frame")
	Bubbly = Instance.new("TextButton")
	Onandoff_140 = Instance.new("Frame")
	Cartoony = Instance.new("TextButton")
	Onandoff_141 = Instance.new("Frame")
	SuperHero = Instance.new("TextButton")
	Onandoff_142 = Instance.new("Frame")
	Zombie = Instance.new("TextButton")
	Onandoff_143 = Instance.new("Frame")
	Knight = Instance.new("TextButton")
	local Onandoff_144 = Instance.new("Frame")
	local Mage = Instance.new("TextButton")
	local Onandoff_145 = Instance.new("Frame")
	local Elder = Instance.new("TextButton")
	local Onandoff_146 = Instance.new("Frame")
	local Toy = Instance.new("TextButton")
	local Onandoff_147 = Instance.new("Frame")
	local Astronaut = Instance.new("TextButton")
	local Onandoff_148 = Instance.new("Frame")
	local Pirate = Instance.new("TextButton")
	local Onandoff_149 = Instance.new("Frame")
	local Vampire = Instance.new("TextButton")
	local Onandoff_150 = Instance.new("Frame")
	local Popstar = Instance.new("TextButton")
	local Onandoff_151 = Instance.new("Frame")
	local Patrol = Instance.new("TextButton")
	local Onandoff_152 = Instance.new("Frame")
	local Confident = Instance.new("TextButton")
	local Onandoff_153 = Instance.new("Frame")
	local Sneaky = Instance.new("TextButton")
	local Onandoff_154 = Instance.new("Frame")
	local None = Instance.new("TextButton")
	local Onandoff_155 = Instance.new("Frame")
	local Ghost = Instance.new("TextButton")
	local Onandoff_156 = Instance.new("Frame")
	local Cowboy = Instance.new("TextButton")
	local Onandoff_157 = Instance.new("Frame")
	local Princess = Instance.new("TextButton")
	local Onandoff_158 = Instance.new("Frame")
	local Anthro = Instance.new("TextButton")
	local Onandoff_159 = Instance.new("Frame")
	local CreditsScrollFrame = Instance.new("ScrollingFrame")
	local TextLabel = Instance.new("TextLabel")
	local TextLabel_2 = Instance.new("TextLabel")
	local TextLabel_3 = Instance.new("TextLabel")
	local SettingsScrollFrame = Instance.new("ScrollingFrame")
	local ButtonDraggable = Instance.new("TextButton")
	local Onandoff_160 = Instance.new("Frame")
	local FrameDraggable = Instance.new("TextButton")
	local Onandoff_161 = Instance.new("Frame")
	local NameScript = Instance.new("TextButton")
	TextBox_2 = Instance.new("TextBox")
	RemoveGlows = Instance.new("TextButton")
	Onandoff_162 = Instance.new("Frame")
	RainbowName = Instance.new("TextButton")
	Onandoff_163 = Instance.new("Frame")
	TextLabel_4 = Instance.new("TextLabel")
	Frame = Instance.new("Frame")
	TextLabel_5 = Instance.new("TextLabel")
	Close = Instance.new("TextButton")
	Minimize = Instance.new("TextButton")
	TargetTextbox = Instance.new("TextBox")
	TimesBuy = Instance.new("TextBox")
	BlackGlowingFrame = Instance.new("Frame")
	Whiteglowing = Instance.new("Frame")
	Whiteglowing_2 = Instance.new("Frame")
	FullMinimize = Instance.new("TextButton")
	MINIMIZEBUTTON = Instance.new("TextButton")
	AutoCollectCash = Instance.new("TextButton")
	OnandoffAutoCollectCash = Instance.new("Frame")
	AutoDropCash = Instance.new("TextButton")
	autodropamout = Instance.new("TextBox")
	DropCash = Instance.new("TextButton")
	dropcashamout = Instance.new("TextBox")
	BombMap = Instance.new("TextButton")
	BombMapText = Instance.new("TextBox")

	gsTween = game:GetService("TweenService")




	Ezpolakyascreengui.Parent = game.CoreGui
	Ezpolakyascreengui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

	Main.Name = "Main"
	Main.Parent = Ezpolakyascreengui
	Main.BackgroundColor3 = Color3.new(1, 1, 1)
	Main.BorderColor3 = Color3.new(1, 1, 1)
	Main.Position = UDim2.new(0.0848303363, 0, 0.123861559, 0)
	Main.Size = UDim2.new(0, 804, 0, 43)
	Main.Active = true
	Main.Draggable = true
	glow = Instance.new("ImageLabel")

	MainChild.Name = "MainChild"
	MainChild.Parent = Main
	MainChild.BackgroundColor3 = Color3.new(0, 0, 0)
	MainChild.BorderColor3 = Color3.new(0, 0, 0)
	MainChild.Position = UDim2.new(0, 0, 0.977494359, 0)
	MainChild.Size = UDim2.new(0, 804, 0, 352)

	TabScrollFrame.Name = "TabScrollFrame"
	TabScrollFrame.Parent = MainChild
	TabScrollFrame.Active = true
	TabScrollFrame.BackgroundColor3 = Color3.new(0, 0, 0)
	TabScrollFrame.BorderColor3 = Color3.new(0, 0, 0)
	TabScrollFrame.Position = UDim2.new(0, 0, 0.0681818202, 0)
	TabScrollFrame.Size = UDim2.new(0, 176, 0, 328)

	CombatTab.Name = "CombatTab"
	CombatTab.Parent = TabScrollFrame
	CombatTab.BackgroundColor3 = Color3.new(0, 0, 0)
	CombatTab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	CombatTab.Position = UDim2.new(0.0340909101, 0, 0.0315647647, 0)
	CombatTab.Size = UDim2.new(0, 143, 0, 26)
	CombatTab.Font = Enum.Font.SourceSans
	CombatTab.Text = "Combat"
	CombatTab.TextColor3 = Color3.new(1, 1, 1)
	CombatTab.TextSize = 18
	CombatTab.MouseButton1Click:connect(function()
		CombatTab.TextColor3 = Color3.new(1, 1, 1)
		MovementTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AutoFarmTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CashModeTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AmmoTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TeleportsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CreditsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		SettingsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TargetTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AnimationTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CombatScrollFrame.Visible = true
		MovementScrollFrame.Visible = false
		AutoFarmScrollFrame.Visible = false
		CashModeScrollFrame.Visible = false
		AmmoScrollFrame.Visible = false
		TeleportsScrollFrame.Visible = false
		CreditsScrollFrame.Visible = false
		TargetScrollFrame.Visible = false
		AnimationScrollFrame.Visible = false
		SettingsScrollFrame.Visible = false
		TimesBuy.Visible = false
		TargetTextbox.Visible = false
	end)

	MovementTab.Name = "MovementTab"
	MovementTab.Parent = TabScrollFrame
	MovementTab.BackgroundColor3 = Color3.new(0, 0, 0)
	MovementTab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	MovementTab.Position = UDim2.new(0.0340909101, 0, 0.0827011243, 0)
	MovementTab.Size = UDim2.new(0, 143, 0, 26)
	MovementTab.Font = Enum.Font.SourceSans
	MovementTab.Text = "MoveMent"
	MovementTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
	MovementTab.TextSize = 18
	MovementTab.MouseButton1Click:connect(function()
		CombatTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		MovementTab.TextColor3 = Color3.new(1 , 1 ,1)
		AutoFarmTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CashModeTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AmmoTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TeleportsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CreditsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		SettingsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TargetTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AnimationTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CombatScrollFrame.Visible = false
		MovementScrollFrame.Visible = true
		AutoFarmScrollFrame.Visible = false
		CashModeScrollFrame.Visible = false
		AmmoScrollFrame.Visible = false
		TeleportsScrollFrame.Visible = false
		CreditsScrollFrame.Visible = false
		TargetScrollFrame.Visible = false
		AnimationScrollFrame.Visible = false
		SettingsScrollFrame.Visible = false
		TargetTextbox.Visible = false
		TimesBuy.Visible = false

	end)

	AutoFarmTab.Name = "AutoFarmTab"
	AutoFarmTab.Parent = TabScrollFrame
	AutoFarmTab.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoFarmTab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoFarmTab.Position = UDim2.new(0.0340909101, 0, 0.130996585, 0)
	AutoFarmTab.Size = UDim2.new(0, 143, 0, 26)
	AutoFarmTab.Font = Enum.Font.SourceSans
	AutoFarmTab.Text = "AutoFarm"
	AutoFarmTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
	AutoFarmTab.TextSize = 18
	AutoFarmTab.MouseButton1Click:connect(function()
		CombatTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		MovementTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AutoFarmTab.TextColor3 = Color3.new(1 , 1 ,1)
		CashModeTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AmmoTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TeleportsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CreditsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		SettingsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TargetTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AnimationTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CombatScrollFrame.Visible = false
		MovementScrollFrame.Visible = false
		AutoFarmScrollFrame.Visible = true
		CashModeScrollFrame.Visible = false
		AmmoScrollFrame.Visible = false
		TeleportsScrollFrame.Visible = false
		CreditsScrollFrame.Visible = false
		TargetScrollFrame.Visible = false
		AnimationScrollFrame.Visible = false
		SettingsScrollFrame.Visible = false
		TimesBuy.Visible = false
		TargetTextbox.Visible = false

	end)

	CashModeTab.Name = "CashMode Tab"
	CashModeTab.Parent = TabScrollFrame
	CashModeTab.BackgroundColor3 = Color3.new(0, 0, 0)
	CashModeTab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	CashModeTab.Position = UDim2.new(0.0340909101, 0, 0.180712491, 0)
	CashModeTab.Size = UDim2.new(0, 143, 0, 26)
	CashModeTab.Font = Enum.Font.SourceSans
	CashModeTab.Text = "Cash mode"
	CashModeTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
	CashModeTab.TextSize = 18
	CashModeTab.MouseButton1Click:connect(function()
		CombatTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		MovementTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AutoFarmTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CashModeTab.TextColor3 = Color3.new(1 , 1 ,1)
		AmmoTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TeleportsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CreditsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		SettingsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TargetTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AnimationTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CombatScrollFrame.Visible = false
		MovementScrollFrame.Visible = false
		AutoFarmScrollFrame.Visible = false
		CashModeScrollFrame.Visible = true
		AmmoScrollFrame.Visible = false
		TeleportsScrollFrame.Visible = false
		CreditsScrollFrame.Visible = false
		TargetScrollFrame.Visible = false
		AnimationScrollFrame.Visible = false
		SettingsScrollFrame.Visible = false
		TimesBuy.Visible = false
		TargetTextbox.Visible = false

	end)
	AmmoTab.Name = "AmmoTab"
	AmmoTab.Parent = TabScrollFrame
	AmmoTab.BackgroundColor3 = Color3.new(0, 0, 0)
	AmmoTab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AmmoTab.Position = UDim2.new(0.0340909101, 0, 0.227587491, 0)
	AmmoTab.Size = UDim2.new(0, 143, 0, 26)
	AmmoTab.Font = Enum.Font.SourceSans
	AmmoTab.Text = "Ammo"
	AmmoTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
	AmmoTab.TextSize = 18
	AmmoTab.MouseButton1Click:connect(function()
		CombatTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		MovementTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AutoFarmTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CashModeTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AmmoTab.TextColor3 = Color3.new(1 , 1 ,1)
		TeleportsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CreditsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		SettingsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TargetTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AnimationTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CombatScrollFrame.Visible = false
		MovementScrollFrame.Visible = false
		AutoFarmScrollFrame.Visible = false
		CashModeScrollFrame.Visible = false
		AmmoScrollFrame.Visible = true
		TeleportsScrollFrame.Visible = false
		CreditsScrollFrame.Visible = false
		TargetScrollFrame.Visible = false
		AnimationScrollFrame.Visible = false
		SettingsScrollFrame.Visible = false

		TimesBuy.Visible = true
		TargetTextbox.Visible = false

	end)
	TeleportsTab.Name = "TeleportsTab"
	TeleportsTab.Parent = TabScrollFrame
	TeleportsTab.BackgroundColor3 = Color3.new(0, 0, 0)
	TeleportsTab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	TeleportsTab.Position = UDim2.new(0.0340909101, 0, 0.273042053, 0)
	TeleportsTab.Size = UDim2.new(0, 143, 0, 26)
	TeleportsTab.Font = Enum.Font.SourceSans
	TeleportsTab.Text = "Teleports"
	TeleportsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
	TeleportsTab.TextSize = 18
	TeleportsTab.MouseButton1Click:connect(function()
		CombatTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		MovementTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AutoFarmTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CashModeTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AmmoTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TeleportsTab.TextColor3 = Color3.new(1 , 1 ,1)
		CreditsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		SettingsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TargetTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AnimationTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CombatScrollFrame.Visible = false
		MovementScrollFrame.Visible = false
		AutoFarmScrollFrame.Visible = false
		CashModeScrollFrame.Visible = false
		AmmoScrollFrame.Visible = false
		TeleportsScrollFrame.Visible = true
		CreditsScrollFrame.Visible = false
		TargetScrollFrame.Visible = false
		AnimationScrollFrame.Visible = false

		SettingsScrollFrame.Visible = false
		TimesBuy.Visible = false
		TargetTextbox.Visible = false

	end)
	CreditsTab.Name = "CreditsTab"
	CreditsTab.Parent = TabScrollFrame
	CreditsTab.BackgroundColor3 = Color3.new(0, 0, 0)
	CreditsTab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	CreditsTab.Position = UDim2.new(0.0340909101, 0, 0.420769304, 0)
	CreditsTab.Size = UDim2.new(0, 143, 0, 26)
	CreditsTab.Font = Enum.Font.SourceSans
	CreditsTab.Text = "Credits"
	CreditsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
	CreditsTab.TextSize = 18
	CreditsTab.MouseButton1Click:connect(function()
		CombatTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		MovementTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AutoFarmTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CashModeTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AmmoTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TeleportsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CreditsTab.TextColor3 = Color3.new(1 , 1 ,1)
		SettingsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TargetTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AnimationTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CombatScrollFrame.Visible = false
		MovementScrollFrame.Visible = false
		AutoFarmScrollFrame.Visible = false
		CashModeScrollFrame.Visible = false
		AmmoScrollFrame.Visible = false
		TeleportsScrollFrame.Visible = false
		CreditsScrollFrame.Visible = true
		TargetScrollFrame.Visible = false
		AnimationScrollFrame.Visible = false
		SettingsScrollFrame.Visible = false
		TimesBuy.Visible = false
		TargetTextbox.Visible = false

	end)
	SettingsTab.Name = "SettingsTab"
	SettingsTab.Parent = TabScrollFrame
	SettingsTab.BackgroundColor3 = Color3.new(0, 0, 0)
	SettingsTab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	SettingsTab.Position = UDim2.new(0.0340909101, 0, 0.474746615, 0)
	SettingsTab.Size = UDim2.new(0, 143, 0, 26)
	SettingsTab.Font = Enum.Font.SourceSans
	SettingsTab.Text = "Settings"
	SettingsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
	SettingsTab.TextSize = 18
	SettingsTab.MouseButton1Click:connect(function()
		CombatTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		MovementTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AutoFarmTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CashModeTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AmmoTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TeleportsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CreditsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		SettingsTab.TextColor3 = Color3.new(1 , 1 ,1)
		TargetTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AnimationTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CombatScrollFrame.Visible = false
		MovementScrollFrame.Visible = false
		AutoFarmScrollFrame.Visible = false
		CashModeScrollFrame.Visible = false
		AmmoScrollFrame.Visible = false
		TeleportsScrollFrame.Visible = false
		CreditsScrollFrame.Visible = false
		TargetScrollFrame.Visible = false
		AnimationScrollFrame.Visible = false
		SettingsScrollFrame.Visible = true
		TimesBuy.Visible = false
		TargetTextbox.Visible = false

	end)
	TargetTab.Name = "TargetTab"
	TargetTab.Parent = TabScrollFrame
	TargetTab.BackgroundColor3 = Color3.new(0, 0, 0)
	TargetTab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	TargetTab.Position = UDim2.new(0.0340909064, 0, 0.319917053, 0)
	TargetTab.Size = UDim2.new(0, 143, 0, 26)
	TargetTab.Font = Enum.Font.SourceSans
	TargetTab.Text = "Target"
	TargetTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
	TargetTab.TextSize = 18
	TargetTab.MouseButton1Click:connect(function()
		CombatTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		MovementTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AutoFarmTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CashModeTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AmmoTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TeleportsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CreditsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		SettingsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TargetTab.TextColor3 = Color3.new(1 , 1 ,1)
		AnimationTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CombatScrollFrame.Visible = false
		MovementScrollFrame.Visible = false
		AutoFarmScrollFrame.Visible = false
		CashModeScrollFrame.Visible = false
		AmmoScrollFrame.Visible = false
		TeleportsScrollFrame.Visible = false
		CreditsScrollFrame.Visible = false
		TargetScrollFrame.Visible = true
		AnimationScrollFrame.Visible = false
		SettingsScrollFrame.Visible = false
		TimesBuy.Visible = false
		TargetTextbox.Visible = true

	end)
	AnimationTab.Name = "AnimationTab"
	AnimationTab.Parent = TabScrollFrame
	AnimationTab.BackgroundColor3 = Color3.new(0, 0, 0)
	AnimationTab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AnimationTab.Position = UDim2.new(0.0340909064, 0, 0.368212521, 0)
	AnimationTab.Size = UDim2.new(0, 143, 0, 26)
	AnimationTab.Font = Enum.Font.SourceSans
	AnimationTab.Text = "Animations"
	AnimationTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
	AnimationTab.TextSize = 18
	AnimationTab.MouseButton1Click:connect(function()
		CombatTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		MovementTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AutoFarmTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CashModeTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AmmoTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TeleportsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		CreditsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		SettingsTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		TargetTab.TextColor3 = Color3.new(0.27451, 0.27451, 0.27451)
		AnimationTab.TextColor3 = Color3.new(1 , 1 ,1)
		CombatScrollFrame.Visible = false
		MovementScrollFrame.Visible = false
		AutoFarmScrollFrame.Visible = false
		CashModeScrollFrame.Visible = false
		AmmoScrollFrame.Visible = false
		TeleportsScrollFrame.Visible = false
		CreditsScrollFrame.Visible = false
		TargetScrollFrame.Visible = false
		AnimationScrollFrame.Visible = true
		SettingsScrollFrame.Visible = false
		TimesBuy.Visible = false
		TargetTextbox.Visible = false

	end)
	CombatScrollFrame.Name = "CombatScrollFrame"
	CombatScrollFrame.Parent = MainChild
	CombatScrollFrame.Active = true
	CombatScrollFrame.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	CombatScrollFrame.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	CombatScrollFrame.Position = UDim2.new(0.247117221, 0, 0.0254765432, 0)
	CombatScrollFrame.Size = UDim2.new(0, 605, 0, 333)

	Floatfist.Name = "Floatfist"
	Floatfist.Parent = CombatScrollFrame
	Floatfist.BackgroundColor3 = Color3.new(0, 0, 0)
	Floatfist.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Floatfist.Position = UDim2.new(0.031863749, 0, 0.0312201343, 0)
	Floatfist.Size = UDim2.new(0, 135, 0, 26)
	Floatfist.Font = Enum.Font.SourceSans
	Floatfist.Text = "Floatfist"
	Floatfist.TextColor3 = Color3.new(1, 1, 1)
	Floatfist.TextSize = 18
	Floatfist.MouseButton1Click:connect(function()

		if Onandoff.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff.BackgroundColor3 = Color3.new(0, 1, 0)
			float = true

			local Players = game:GetService("Players")
			local RunService = game:GetService("RunService")

			local LocalPlayer = Players.LocalPlayer
			local Mouse = LocalPlayer:GetMouse()

			local Character = LocalPlayer.Character
			local RightHand = Character.RightHand

			local Character = LocalPlayer.Character
			local LeftHand = Character.LeftHand


			local localPlayer       = game:GetService("Players").LocalPlayer;
			local localCharacter    = localPlayer.Character
			local Mouse             = localPlayer:GetMouse();
			local FistControl       = false
			local LeftFist          = localCharacter.LeftHand;
			local RightFist         = localCharacter.RightHand;

			-- // Services
			local uis = game:GetService("UserInputService");

			-- // Removing Wrists
			pcall(function()
				LeftFist.LeftWrist:Destroy();
				RightFist.RightWrist:Destroy();
			end);

			loopFunction = function()
				LeftFist.CFrame  = CFrame.new(Mouse.Hit.p);
				RightFist.CFrame = CFrame.new(Mouse.Hit.p);
			end;
			local Loop

			local	 Start = function()
				Loop = game:GetService("RunService").Heartbeat:Connect(loopFunction);
			end;
			Pause = function()
				Loop:Disconnect()
			end;
			Start()
		else
			Onandoff.BackgroundColor3 = Color3.new(1, 0, 0)
			Pause()
			local lol = game.Players.LocalPlayer.Character.HumanoidRootPart

			for i = 1, 10 do
				game.Players.LocalPlayer.Character.RightHand.CFrame = lol.CFrame
				game.Players.LocalPlayer.Character.LeftHand.CFrame = lol.CFrame

				wait(0.05)
			end
		end

	end)
	Onandoff.Name = "Onandoff"
	Onandoff.Parent = Floatfist
	Onandoff.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff.Position = UDim2.new(0, 0, 1, 0)
	Onandoff.Size = UDim2.new(0, 135, 0, 15)

	Godbullet.Name = "Godbullet"
	Godbullet.Parent = CombatScrollFrame
	Godbullet.BackgroundColor3 = Color3.new(0, 0, 0)
	Godbullet.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Godbullet.Position = UDim2.new(0.267193943, 0, 0.0309641957, 0)
	Godbullet.Size = UDim2.new(0, 135, 0, 26)
	Godbullet.Font = Enum.Font.SourceSans
	Godbullet.Text = "GodBullet"
	Godbullet.TextColor3 = Color3.new(1, 1, 1)
	Godbullet.TextSize = 18

	Godbullet.MouseButton1Click:connect(function()
		
		game.Players.LocalPlayer.Character.Humanoid.Health = 0
		function Unban()
			repeat wait() until game.Players.LocalPlayer.Character:FindFirstChild("BodyEffects") and game.Players.LocalPlayer.Character.BodyEffects:FindFirstChild("SpecialParts") and not game.Players.LocalPlayer.Character:FindFirstChild("ForceField_TESTING")
			local loaded = Instance.new("Folder")
			loaded.Name = "FULLY_LOADED_CHAR"
			loaded.Parent = game.Players.LocalPlayer.Character
			game.Players.LocalPlayer.Character.BodyEffects.Dead:Destroy()
			game:GetService("Players").LocalPlayer.PlayerGui.MainScreenGui.TimerJail:Destroy()

		end
		 wait(5.3)
			game.Players.LocalPlayer.CharacterAdded:Connect(function()Unban()end)Unban()
wait(3)
		game.Players.LocalPlayer.Character.BodyEffects.Armor:Destroy()
		wait(1)
		ps = game:GetService("Players")
		lp2 = ps.LocalPlayer
		char12 = lp2.Character
		local Clone1 = Instance.new("IntValue")
		Clone1.Name = "Armor"
		Clone1.Parent = char12.BodyEffects
		noti("Godbullet enabled")
			

		
		
	
	end)

	Onandoff_2.Name = "Onandoff"
	Onandoff_2.Parent = Godbullet
	Onandoff_2.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_2.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_2.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_2.Size = UDim2.new(0, 135, 0, 15)

	BagAll.Name = "BagAll"
	BagAll.Parent = CombatScrollFrame
	BagAll.BackgroundColor3 = Color3.new(0, 0, 0)
	BagAll.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	BagAll.Position = UDim2.new(0.503098488, 0, 0.0312201343, 0)
	BagAll.Size = UDim2.new(0, 135, 0, 26)
	BagAll.Font = Enum.Font.SourceSans
	BagAll.Text = "BagAll"
	BagAll.TextColor3 = Color3.new(1, 1, 1)
	BagAll.TextSize = 18
	BagAll.MouseButton1Click:connect(function()
		bag = true
		if Onandoff_3.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_3.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("Bagall enabled")

			bag = true
			repeat

				local cor = coroutine.wrap(function()
					if not game.Players.LocalPlayer.Character:FindFirstChild("[BrownBag]") then
						takingbag = true
						local cor = coroutine.wrap(function()
							game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-314.580566, 51.1788902, -727.484558))
						end)
						cor()			
						wait(1)
						fireclickdetector(workspace.Ignored.Shop["[BrownBag] - $25"].ClickDetector, 4)
						wait(0.5)
						game.Players.LocalPlayer.Backpack["[BrownBag]"].Parent = game.Players.LocalPlayer.Character
						takingbag = false
					end
				end)
				cor()
				if takingbag == false then
					for i, v  in pairs(game.Players:GetPlayers()) do
						if v.Character:FindFirstChild("Christmas_Sock") == nil and v.Character:FindFirstChildOfClass("ForceField") == nil and v.Character ~= game.Players.LocalPlayer.Character then
							local chars = v.Character
							if game.Players.LocalPlayer.Character:FindFirstChild("[BrownBag]") then
								game.Players.LocalPlayer.Character["[BrownBag]"]:Activate()
							end
							game.Players.LocalPlayer.Character:MoveTo(v.Character.UpperTorso.Position)
						end
						wait(0.005)
					end
				end
				wait()
			until bag == false
		else
			Onandoff_3.BackgroundColor3 = Color3.new(1, 0, 0)
			noti("Bagall disabled")
			bag = false

		end
	end)

	Onandoff_3.Name = "Onandoff"
	Onandoff_3.Parent = BagAll
	Onandoff_3.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_3.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_3.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_3.Size = UDim2.new(0, 135, 0, 15)

	UnBan.Name = "UnBan"
	UnBan.Parent = CombatScrollFrame
	UnBan.BackgroundColor3 = Color3.new(0, 0, 0)
	UnBan.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	UnBan.Position = UDim2.new(0.739462137, 0, 0.0312201343, 0)
	UnBan.Size = UDim2.new(0, 135, 0, 26)
	UnBan.Font = Enum.Font.SourceSans
	UnBan.Text = "UnBan"
	UnBan.TextColor3 = Color3.new(1, 1, 1)
	UnBan.TextSize = 18
	UnBan.MouseButton1Click:connect(function()
		game.Players.LocalPlayer.Character.Humanoid.Health = 0
		function Unban()
			repeat wait() until game.Players.LocalPlayer.Character:FindFirstChild("BodyEffects") and game.Players.LocalPlayer.Character.BodyEffects:FindFirstChild("SpecialParts") and not game.Players.LocalPlayer.Character:FindFirstChild("ForceField_TESTING")
			local loaded = Instance.new("Folder")
			loaded.Name = "FULLY_LOADED_CHAR"
			loaded.Parent = game.Players.LocalPlayer.Character
			game.Players.LocalPlayer.Character.BodyEffects.Dead:Destroy()
			game:GetService("Players").LocalPlayer.PlayerGui.MainScreenGui.TimerJail:Destroy()

		end
		wait(5.3)
		game.Players.LocalPlayer.CharacterAdded:Connect(function()Unban()end)Unban()


	end)


	Onandoff_4.Name = "Onandoff"
	Onandoff_4.Parent = UnBan
	Onandoff_4.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_4.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_4.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_4.Size = UDim2.new(0, 135, 0, 15)

	Male.Name = "Male"
	Male.Parent = CombatScrollFrame
	Male.BackgroundColor3 = Color3.new(0, 0, 0)
	Male.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Male.Position = UDim2.new(0.031863749, 0, 0.10366331, 0)
	Male.Size = UDim2.new(0, 135, 0, 26)
	Male.Font = Enum.Font.SourceSans
	Male.Text = "Male"
	Male.TextColor3 = Color3.new(1, 1, 1)
	Male.TextSize = 18
	Male.MouseButton1Click:connect(function()
		local lol3 = game.Workspace.Ignored.Shop["[Bat] - $275"]
		local lol2 = game.Workspace.Ignored.Shop["[StopSign] - $300"]
		local lol = game.Workspace.Ignored.Shop["[Hamburger] - $5"]
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		wait(0.20)
		fireclickdetector(lol.ClickDetector,4)
		wait(1)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.20)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(1)
		game.Players.LocalPlayer.Character:MoveTo(lol2.Head.Position)
		wait(0.20)
		fireclickdetector(lol2.ClickDetector,4)
		wait(1)
		game.Players.LocalPlayer.Character:MoveTo(lol3.Head.Position)
		wait(0.20)
		fireclickdetector(lol3.ClickDetector,4)
		wait(.2)
		for _,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if (v:IsA("Tool")) then
				v.Parent = game.Players.LocalPlayer.Backpack
			end
		end
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(1.5, -2, -1)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(1.5, -1, -1)
		wait(.3)
		if lol and lol2 and lol3 then
			wait(.1)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[StopSign]"].GripPos     = Vector3.new(0, -1.5, 2 )
			game.Players.LocalPlayer.Backpack["[StopSign]"].GripForward     = Vector3.new(-3, -3, -1)
			game.Players.LocalPlayer.Backpack["[StopSign]"].GripRight     = Vector3.new(-0, -5, 1)
			game.Players.LocalPlayer.Backpack["[StopSign]"].GripUp     = Vector3.new(2, 0, 75)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripPos     = Vector3.new(2, -5, -1.5)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripForward     = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripRight     = Vector3.new(1, 0, -3)
			game.Players.LocalPlayer.Backpack["[Bat]"].GripUp     = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
			game.Players.LocalPlayer.Backpack["[StopSign]"].Parent = game.Players.LocalPlayer.Character
			game.Players.LocalPlayer.Backpack["[Bat]"].Parent = game.Players.LocalPlayer.Character
			game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		end
	end)

	Onandoff_5.Name = "Onandoff"
	Onandoff_5.Parent = Male
	Onandoff_5.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_5.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_5.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_5.Size = UDim2.new(0, 135, 0, 15)

	Nuke.Name = "Nuke"
	Nuke.Parent = CombatScrollFrame
	Nuke.BackgroundColor3 = Color3.new(0, 0, 0)
	Nuke.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Nuke.Position = UDim2.new(0.267193943, 0, 0.103407376, 0)
	Nuke.Size = UDim2.new(0, 135, 0, 26)
	Nuke.Font = Enum.Font.SourceSans
	Nuke.Text = "Nuke"
	Nuke.TextColor3 = Color3.new(1, 1, 1)
	Nuke.TextSize = 18
	Nuke.MouseButton1Click:connect(function()
		pcall(function()
			for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
				if v.Name == '[Grenade]' then
					v.Parent = game.Players.LocalPlayer.Character
				end
			end
		end)
		wait(.9)
		local targetpos = CFrame.new(108.995865, -26.7500305, -276.529877)
		local plr = game.Players.LocalPlayer
		local pos = plr.Character.HumanoidRootPart.Position
		if not game.Players.LocalPlayer.Character:FindFirstChild("[Grenade]") then
			plr.Character.HumanoidRootPart.CFrame = targetpos
			local cd = game:GetService("Workspace").Ignored.Shop["[Grenade] - $700"]:FindFirstChild("ClickDetector")
			wait(.9)
			fireclickdetector(cd)
			wait(.4)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
			wait(.9)
			fireclickdetector(cd)
			wait(.4)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
			wait(.9)
			fireclickdetector(cd)
			wait(.4)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
			wait(.9)
			fireclickdetector(cd)
			wait(.4)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
			wait(.9)
			fireclickdetector(cd)
			wait(.4)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
			wait(.9)
			fireclickdetector(cd)
			wait(.4)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
			wait(.9)
			fireclickdetector(cd)
			wait(.4)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
			wait(.9)
			fireclickdetector(cd)
			wait(.4)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = plr.Character
			wait(.9)
			local oh1 = CFrame.new(-411.605194, 21.7499943, -332.942078)
			local oh2 = game:GetService("Players")
			local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


			oh3.CFrame = oh1

			-- end of script
			local oh1 = CFrame.new(-396.677094, 51.750145, -336.327148)
			local oh2 = game:GetService("Players")
			local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


			oh3.CFrame = oh1

			-- end of script
			local oh1 = CFrame.new(-408.277466, 77.8071213, -369.336456)
			local oh2 = game:GetService("Players")
			local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


			oh3.CFrame = oh1

			-- end of script
			local oh1 = CFrame.new(-396.90979, 61.7791367, -381.694397)
			local oh2 = game:GetService("Players")
			local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


			oh3.CFrame = oh1
		end
		wait(0)
		local LocalPlayer = game:GetService("Players").LocalPlayer
		local char = LocalPlayer.Character
		local Ignored = game.workspace.Ignored
		local backpack = LocalPlayer.Backpack
		local x = 0
		local Grenade = "[Grenade]"
		local DroppedGrenade = "Handle"
		for i,v in pairs(backpack:GetChildren()) do
			if v.Name == Grenade then
				v.Parent = char
			end
		end
		for i,v in pairs(char:GetChildren()) do
			if v.Name == Grenade then
				v:Activate()
				v:Activate()
			end
		end
		wait (1)
		for i,v in pairs(Ignored:GetChildren()) do
			if v.Name == DroppedGrenade then
				x = x + 1
				v.Name = DroppedGrenade..x
			end
		end
		wait(1)
		x = 0
		for i, player in pairs(game.Players:GetPlayers()) do
			x = x + 1
			local launch = Ignored:WaitForChild(DroppedGrenade..x)
			if LocalPlayer.Name == player.Name then do
					launch.Position = Vector3.new(0,1000,0)
				end
			else do
					game.Players.LocalPlayer.MaximumSimulationRadius = math.pow(math.huge,math.huge)*math.huge
					game.Players.LocalPlayer.SimulationRadius = math.pow(math.huge,math.huge)*math.huge
					launch.Position = player.Character.HumanoidRootPart.Position
					wait (0.02)
				end

			end
		end
	end)

	Onandoff_6.Name = "Onandoff"
	Onandoff_6.Parent = Nuke
	Onandoff_6.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_6.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_6.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_6.Size = UDim2.new(0, 135, 0, 15)

	Physic.Name = "Physic"
	Physic.Parent = CombatScrollFrame
	Physic.BackgroundColor3 = Color3.new(0, 0, 0)
	Physic.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Physic.Position = UDim2.new(0.503098488, 0, 0.10366331, 0)
	Physic.Size = UDim2.new(0, 135, 0, 26)
	Physic.Font = Enum.Font.SourceSans
	Physic.Text = "Physic"
	Physic.TextColor3 = Color3.new(1, 1, 1)
	Physic.TextSize = 18
	Physic.MouseButton1Click:connect(function()
		loadstring(game:HttpGet(("https://pastebin.com/raw/KU2T3PwE"),true))()

	end)

	Onandoff_7.Name = "Onandoff"
	Onandoff_7.Parent = Physic
	Onandoff_7.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_7.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_7.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_7.Size = UDim2.new(0, 135, 0, 15)

	Cross.Name = "Cross"
	Cross.Parent = CombatScrollFrame
	Cross.BackgroundColor3 = Color3.new(0, 0, 0)
	Cross.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Cross.Position = UDim2.new(0.739462137, 0, 0.10366331, 0)
	Cross.Size = UDim2.new(0, 135, 0, 26)
	Cross.Font = Enum.Font.SourceSans
	Cross.Text = "Cross"
	Cross.TextColor3 = Color3.new(1, 1, 1)
	Cross.TextSize = 18
	Cross.MouseButton1Click:connect(function()
		wait(0) local A_1 = "[Polakya] HolyCross Enabled" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)

		pcall(function()
			for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
				if v.Name == '[SledgeHammer]' then
					v.Parent = game.Players.LocalPlayer.Character
				end
			end
		end)
		wait(.9)
		local targetpos = CFrame.new(-899.925659, 21.75, -297.100342)
		local plr = game.Players.LocalPlayer
		local pos = plr.Character.HumanoidRootPart.Position
		if not game.Players.LocalPlayer.Character:FindFirstChild("[SledgeHammer]") then
			plr.Character.HumanoidRootPart.CFrame = targetpos
			local cd = game:GetService("Workspace").Ignored.Shop["[SledgeHammer] - $350"]:FindFirstChild("ClickDetector")
			wait(.9)
			fireclickdetector(cd)
			wait(.4)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[SledgeHammer]").Parent = plr.Character
			wait(.9)
			fireclickdetector(cd)
			wait(.4)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[SledgeHammer]").Parent = plr.Character
			for i,v in pairs(plr.Character:GetChildren()) do
				if v.Name == '[SledgeHammer]' then
					v:GetChildren()[3]:Destroy()
				end
			end
			local sd = plr.Character:FindFirstChild("[SledgeHammer]")
			sd.Grip = CFrame.new(-2.4000001, -0.699999988, 0, 0, 1, -0, -1, 0, -0, 0, 0, 1)
			sd.GripForward = Vector3.new(0, 0, -1)
			sd.GripPos = Vector3.new(-2.4, -0.7, 0)
			sd.GripUp = Vector3.new(1, 0, 0)
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
		end
		local sd = plr.Character:FindFirstChild("[SledgeHammer]")
		sd.Grip = CFrame.new(-2.4000001, -0.699999988, 0, 0, 1, -0, -1, 0, -0, 0, 0, 1)
		sd.GripForward = Vector3.new(0, 0, -1)
		sd.GripPos = Vector3.new(-2.4, -0.7, 0)
		sd.GripUp = Vector3.new(1, 0, 0)
		plr.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
	end)

	Onandoff_8.Name = "Onandoff"
	Onandoff_8.Parent = Cross
	Onandoff_8.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_8.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_8.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_8.Size = UDim2.new(0, 135, 0, 15)

	SpinKnife.Name = "SpinKnife"
	SpinKnife.Parent = CombatScrollFrame
	SpinKnife.BackgroundColor3 = Color3.new(0, 0, 0)
	SpinKnife.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	SpinKnife.Position = UDim2.new(0.266734838, 0, 0.177526951, 0)
	SpinKnife.Size = UDim2.new(0, 135, 0, 26)
	SpinKnife.Font = Enum.Font.SourceSans
	SpinKnife.Text = "SpinKnife"
	SpinKnife.TextColor3 = Color3.new(1, 1, 1)
	SpinKnife.TextSize = 18
	SpinKnife.MouseButton1Click:connect(function()
		local spin = false
		spin = true
		flying = false
		if Onandoff_9.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_9.BackgroundColor3 = Color3.new(0, 1, 0)

			if not game.Players.LocalPlayer.Backpack:FindFirstChild("[Knife]")  then


				wait(.9)
				local targetpos = CFrame.new(-278.063446, 21.75, -240.871841)
				local plr = game.Players.LocalPlayer
				local pos = plr.Character.HumanoidRootPart.Position
				plr.Character.HumanoidRootPart.CFrame = targetpos
				local cd = game:GetService("Workspace").Ignored.Shop["[Knife] - $150"]:FindFirstChild("ClickDetector")
				wait(.9)
				fireclickdetector(cd)
				wait(.4)
				game.Players.LocalPlayer.Backpack["[Knife]"].GripPos     = Vector3.new(2, -5, -1.5)
				game.Players.LocalPlayer.Backpack["[Knife]"].GripForward     = Vector3.new(0, 0, 0)
				game.Players.LocalPlayer.Backpack["[Knife]"].GripRight     = Vector3.new(1, 0, -3)
				game.Players.LocalPlayer.Backpack["[Knife]"].GripUp     = Vector3.new(0, 0, 0)
				game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character
				wait(.9)
			end
			pcall(function()
				for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.Name == '[Knife]' then
						v.Parent = game.Players.LocalPlayer.Character
					end
				end
			end)
			wait(.6)
			local spinSpeed = 250
			local speaker = game.Players.LocalPlayer
			for i,v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
				if v.Name == "Spinning" then
					v:Destroy()
				end
			end
			local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
			Spin.Name = "Spinning"
			Spin.MaxTorque = Vector3.new(0, math.huge, 0)
			Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)

		else
			Onandoff_9.BackgroundColor3 = Color3.new(1, 0, 0)
			for _,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
				if (v:IsA("Tool")) then
					v.Parent = game.Players.LocalPlayer.Backpack
				end
			end
			local spinSpeed = 0
			local speaker = game.Players.LocalPlayer
			for i,v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
				if v.Name == "Spinning" then
					v:Destroy()
				end
			end
			local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
			Spin.Name = "Spinning"
			Spin.MaxTorque = Vector3.new(0, math.huge, 0)
			Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)
			Spin:Destroy()	
		end

	end)

	Onandoff_9.Name = "Onandoff"
	Onandoff_9.Parent = SpinKnife
	Onandoff_9.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_9.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_9.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_9.Size = UDim2.new(0, 135, 0, 15)

	NinjaStar.Name = "NinjaStar"
	NinjaStar.Parent = CombatScrollFrame
	NinjaStar.BackgroundColor3 = Color3.new(0, 0, 0)
	NinjaStar.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	NinjaStar.Position = UDim2.new(0.031863749, 0, 0.177526951, 0)
	NinjaStar.Size = UDim2.new(0, 135, 0, 26)
	NinjaStar.Font = Enum.Font.SourceSans
	NinjaStar.Text = "NinjaStar"
	NinjaStar.TextColor3 = Color3.new(1, 1, 1)
	NinjaStar.TextSize = 18
	NinjaStar.MouseButton1Click:connect(function()
		flying = false
		local cor = coroutine.wrap(function()
			game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-278.063446, 21.75, -235.871841))
		end)
		cor()			
		wait(1)
		fireclickdetector(workspace.Ignored.Shop["[Knife] - $150"].ClickDetector, 4)
		wait(1)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripPos     = Vector3.new(0, 0, 0 )
		game.Players.LocalPlayer.Backpack["[Knife]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripUp     = Vector3.new(0, 0, 0)
		wait(0.20)
		game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character
		wait(0.3)
		fireclickdetector(workspace.Ignored.Shop["[Knife] - $150"].ClickDetector, 4)
		wait(1)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripPos     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripForward     = Vector3.new(5, 5, 5)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripUp     = Vector3.new(0, 5, 0)
		wait(0.20)
		if game.Players.LocalPlayer.Backpack:FindFirstChild("[Knife]") then
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Knife]").Parent = game.Players.LocalPlayer.Character
		end
	end)

	Onandoff_10.Name = "Onandoff"
	Onandoff_10.Parent = NinjaStar
	Onandoff_10.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_10.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_10.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_10.Size = UDim2.new(0, 135, 0, 15)

	AntiBag.Name = "AntiBag"
	AntiBag.Parent = CombatScrollFrame
	AntiBag.BackgroundColor3 = Color3.new(0, 0, 0)
	AntiBag.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AntiBag.Position = UDim2.new(0.503098488, 0, 0.177526951, 0)
	AntiBag.Size = UDim2.new(0, 135, 0, 26)
	AntiBag.Font = Enum.Font.SourceSans
	AntiBag.Text = "AntiBag"
	AntiBag.TextColor3 = Color3.new(1, 1, 1)
	AntiBag.TextSize = 18
	AntiBag.MouseButton1Click:connect(function()
		if Onandoff_11.BackgroundColor3 == Color3.new(1, 0, 0)then
			Onandoff_11.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("AntiBag Enabled")
			antoy = true
			delay(0, function()

				while antoy == true do			 
					pcall(function()
						game.Players.LocalPlayer.Character["Christmas_Sock"]:Destroy()
					end)
					wait()
				end
			end)
		else
			antoy = false
			Onandoff_11.BackgroundColor3 = Color3.new(1, 0, 0)
			noti("AntiBag Disabled")


		end	

	end)

	Onandoff_11.Name = "Onandoff"
	Onandoff_11.Parent = AntiBag
	Onandoff_11.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_11.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_11.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_11.Size = UDim2.new(0, 135, 0, 15)

	FistWave.Name = "FistWave"
	FistWave.Parent = CombatScrollFrame
	FistWave.BackgroundColor3 = Color3.new(0, 0, 0)
	FistWave.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FistWave.Position = UDim2.new(0.739462137, 0, 0.177526951, 0)
	FistWave.Size = UDim2.new(0, 135, 0, 26)
	FistWave.Font = Enum.Font.SourceSans
	FistWave.Text = "FistWave"
	FistWave.TextColor3 = Color3.new(1, 1, 1)
	FistWave.TextSize = 18
	FistWave.MouseButton1Click:connect(function()
		wave = false
		if Onandoff_12.BackgroundColor3 == Color3.new(1, 0, 0) and wave == false then
			Onandoff_12.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("Fistwave enabled")
			wave = true
			local Part = Instance.new("Part",workspace)
			Part.Name = "GetFucked"
			Part.Anchored = false
			Part.CanCollide = false
			Part.Transparency = 1
			local Part1= Instance.new("Part",workspace)
			Part1.Name = "GetFucked1"
			Part1.Anchored = true
			Part1.CanCollide = false
			Part1.Transparency = 1

			local Weld = Instance.new("Weld", Part1)
			Weld.Part0 = Part1
			Weld.Part1 = Part
			Weld.C0 = CFrame.new(0, 0, 10000)
			local cor = coroutine.wrap(function()
				wait(2)
				Part:Destroy()
				Part1:Destroy()
				Weld:Destroy()
			end)

			local laugh = 0

			laugh = laugh+200
			Part1.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.Angles(0, laugh, math.pi/-2)
			local lol = game.Players.LocalPlayer.Character.HumanoidRootPart
			game.Players.LocalPlayer.Character.RightHand.CFrame = CFrame.new(Part.CFrame.X ,Part.CFrame.Y+2, Part.CFrame.Z)
			game.Players.LocalPlayer.Character.RightHand.Massless = true
			game.Players.LocalPlayer.Character.RightHand.Size = Vector3.new(0, 0, 0)
			game.Players.LocalPlayer.Character.LeftHand.CFrame = CFrame.new(Part.CFrame.X ,Part.CFrame.Y+2, Part.CFrame.Z)
			game.Players.LocalPlayer.Character.LeftHand.Massless = true
			game.Players.LocalPlayer.Character.LeftHand.Size = Vector3.new(0, 0, 0)




			pcall(function()
				if game.Players.LocalPlayer.Character.RightHand:FindFirstChildOfClass("Model") then
					game.Players.LocalPlayer.Character.RightHand.Model.RightWrist:Destroy()
				end
				if game.Players.LocalPlayer.Character.LeftHand:FindFirstChildOfClass("Model") then
					game.Players.LocalPlayer.Character.LeftHand.Model.RightWrist:Destroy()
				end
				game.Players.LocalPlayer.Character.RightHand.RightWrist:Destroy()
				game.Players.LocalPlayer.Character.LeftHand.LeftWrist:Destroy()

			end)
			local laugh = 0
			repeat

				laugh = laugh+200
				Part1.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.Angles(0, laugh, math.pi/-2)
				local lol = game.Players.LocalPlayer.Character.HumanoidRootPart
				game.Players.LocalPlayer.Character.RightHand.CFrame = CFrame.new(Part.CFrame.X ,Part.CFrame.Y+2, Part.CFrame.Z)
				game.Players.LocalPlayer.Character.RightHand.Massless = true
				game.Players.LocalPlayer.Character.LeftHand.CFrame = CFrame.new(Part.CFrame.X ,Part.CFrame.Y+2, Part.CFrame.Z)
				game.Players.LocalPlayer.Character.LeftHand.Massless = true
				wait()
			until wave == false

		else	
			Onandoff_12.BackgroundColor3 = Color3.new(1, 0, 0)
			noti("Fistwave disabled")
			wave = false
			local lol = game.Players.LocalPlayer.Character.HumanoidRootPart
			game.Players.LocalPlayer.Character.RightHand.Size = Vector3.new(0.9, 0.5, 1)
			game.Players.LocalPlayer.Character.LeftHand.Size = Vector3.new(0.9, 0.5, 1)
			for i = 1, 10 do
				game.Players.LocalPlayer.Character.RightHand.CFrame = lol.CFrame
				game.Players.LocalPlayer.Character.LeftHand.CFrame = lol.CFrame

				wait(0.05)
			end
		end
	end)


	Onandoff_12.Name = "Onandoff"
	Onandoff_12.Parent = FistWave
	Onandoff_12.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_12.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_12.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_12.Size = UDim2.new(0, 135, 0, 15)

	AirStrike.Name = "AirStrike"
	AirStrike.Parent = CombatScrollFrame
	AirStrike.BackgroundColor3 = Color3.new(0, 0, 0)
	AirStrike.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AirStrike.Position = UDim2.new(0.0303712487, 0, 0.248549655, 0)
	AirStrike.Size = UDim2.new(0, 135, 0, 26)
	AirStrike.Font = Enum.Font.SourceSans
	AirStrike.Text = "AirStrike"
	AirStrike.TextColor3 = Color3.new(1, 1, 1)
	AirStrike.TextSize = 18
	AirStrike.MouseButton1Click:connect(function()
		if Onandoff_13.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_13.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("Airstrike enabled")
			for _,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
				if (v:IsA("Tool")) then
					v.Parent = game.Players.LocalPlayer.Backpack

				end
			end

			wait(1)

			for i, v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetDescendants()) do

				if v:IsA("Tool") then
					v.GripPos     = Vector3.new(1, -30, 0.3)


				end
			end

		else 
			Onandoff_13.BackgroundColor3 = Color3.new(1, 0, 0)
			for _,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
				if (v:IsA("Tool")) then
					v.Parent = game.Players.LocalPlayer.Backpack

				end
			end
			wait(1)
			for i, v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetDescendants()) do

				if v:IsA("Tool") then
					v.GripPos     = Vector3.new(0, 0, 0)

				end
			end
			noti("Airstrike disabled")

		end

	end)

	Onandoff_13.Name = "Onandoff"
	Onandoff_13.Parent = AirStrike
	Onandoff_13.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_13.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_13.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_13.Size = UDim2.new(0, 135, 0, 15)

	KillAll.Name = "KillAll"
	KillAll.Parent = CombatScrollFrame
	KillAll.BackgroundColor3 = Color3.new(0, 0, 0)
	KillAll.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	KillAll.Position = UDim2.new(0.266734898, 0, 0.248549655, 0)
	KillAll.Size = UDim2.new(0, 135, 0, 26)
	KillAll.Font = Enum.Font.SourceSans
	KillAll.Text = "KillAll"
	KillAll.TextColor3 = Color3.new(1, 1, 1)
	KillAll.TextSize = 18
	KillAll.MouseButton1Click:connect(function()
		Knife = true
		if Onandoff_14.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_14.BackgroundColor3 = Color3.new(0, 1, 0)

			repeat

				local cor = coroutine.wrap(function()
					if not game.Players.LocalPlayer.Character:FindFirstChild("[Knife]") then
						takingbag = true
						local cor = coroutine.wrap(function()

							game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-278.063446, 21.75, -240.871841))
						end)
						cor()
						wait(1)

						fireclickdetector(workspace.Ignored.Shop["[Knife] - $150"].ClickDetector, 4)
						game.Players.LocalPlayer.Backpack["[Knife]"].Handle.Size = Vector3.new(10, 10, 10)
						wait(0.5)
						game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character
						takingbag = false
					end
				end)
				cor()
				if takingbag == false then
					for i, v  in pairs(game.Players:GetPlayers()) do
						if v.Character:FindFirstChild("Knife") == nil and v.Character:FindFirstChildOfClass("ForceField") == nil and v.Character ~= game.Players.LocalPlayer.Character then
							local chars = v.Character
							if game.Players.LocalPlayer.Character:FindFirstChild("[Knife]") then
								game.Players.LocalPlayer.Character["[Knife]"]:Activate()
							end
							game.Players.LocalPlayer.Character:MoveTo(v.Character.UpperTorso.Position)
						end
						wait(0.005)
					end
				end
				wait()
			until Knife == false
		else
			Onandoff_14.BackgroundColor3 = Color3.new(1, 0, 0)
			Knife = false
		end
	end)

	Onandoff_14.Name = "Onandoff"
	Onandoff_14.Parent = KillAll
	Onandoff_14.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_14.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_14.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_14.Size = UDim2.new(0, 135, 0, 15)

	FistReach.Name = "FistReach"
	FistReach.Parent = CombatScrollFrame
	FistReach.BackgroundColor3 = Color3.new(0, 0, 0)
	FistReach.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FistReach.Position = UDim2.new(0.501445651, 0, 0.248549655, 0)
	FistReach.Size = UDim2.new(0, 135, 0, 26)
	FistReach.Font = Enum.Font.SourceSans
	FistReach.Text = "FistReach"
	FistReach.TextColor3 = Color3.new(1, 1, 1)
	FistReach.TextSize = 18
	FistReach.MouseButton1Click:connect(function()
		if Onandoff_15.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_15.BackgroundColor3 = Color3.new(0, 1, 0)
			LP = game.Players.LocalPlayer
			for i,v in ipairs(LP.Character:GetDescendants()) do
				if v:IsA("MeshPart") then v.Massless = true
					v.CanCollide = false
					v.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)

				end
			end

			for i,v in ipairs(game.workspace:GetDescendants()) do
				if v:IsA("Seat") then 
					v.Disabled = true
				end
			end
			x = 20
			y = 20
			z = 20


			penis = Vector3.new(x,y,z)

			LP.Character.RightHand.Size = penis

			LP.Character.RightHand.Transparency = 1
			selectionBox = Instance.new("SelectionBox",LP.Character.RightHand)
			selectionBox.Adornee = LP.Character.RightHand
			selectionBox.Color3 = Color3.new(1, 0.333333, 1)

			LP.Character.LeftHand.Size = penis
			LP.Character.BodyEffects.SpecialParts.LeftHand.Size = penis

			LP.Character.LeftHand.Transparency = 1

		else
			Onandoff_15.BackgroundColor3 = Color3.new(1, 0, 0)

			LP = game.Players.LocalPlayer
			for i,v in ipairs(LP.Character:GetDescendants()) do
				if v:IsA("MeshPart") then v.Massless = true
					v.CanCollide = false
					v.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)

				end
			end

			for i,v in ipairs(game.workspace:GetDescendants()) do
				if v:IsA("Seat") then 
					v.Disabled = true
				end
			end
			x = 1
			y = .5
			z = 1


			penis = Vector3.new(x,y,z)

			LP.Character.RightHand.Size = penis

			LP.Character.RightHand.Transparency = 0
			selectionBox:Destroy()
			selectionBox:Destroy()
			LP.Character.LeftHand.Size = penis
			LP.Character.BodyEffects.SpecialParts.LeftHand.Size = penis

			LP.Character.LeftHand.Transparency = 0

		end
	end)

	Onandoff_15.Name = "Onandoff"
	Onandoff_15.Parent = FistReach
	Onandoff_15.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_15.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_15.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_15.Size = UDim2.new(0, 135, 0, 15)

	Headless.Name = "Headless"
	Headless.Parent = CombatScrollFrame
	Headless.BackgroundColor3 = Color3.new(0, 0, 0)
	Headless.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Headless.Position = UDim2.new(0.739301741, 0, 0.24854967, 0)
	Headless.Size = UDim2.new(0, 135, 0, 26)
	Headless.Font = Enum.Font.SourceSans
	Headless.Text = "Headless"
	Headless.TextColor3 = Color3.new(1, 1, 1)
	Headless.TextSize = 18
	Headless.MouseButton1Click:connect(function()

		game.Players.LocalPlayer.Character.Head.Neck:Destroy()
		game.Players.LocalPlayer.Character.UpperTorso.NeckAttachment:Destroy()
		game.Players.LocalPlayer.Character.Head.Size = Vector3.new(0,0,0)
		game.Players.LocalPlayer.Character.Head.Massless = true
		game.Players.LocalPlayer.Character.Head.CanCollide = false

		heazd = true

		while heazd == true do 
			pcall(function()  
				game.Players.LocalPlayer.Character.Head.NeckRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
				game.Players.LocalPlayer.Character.UpperTorso.NeckRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
				game.Players.LocalPlayer.Character.Head.CFrame = CFrame.new(0, 100000.4736328125, 0)
			end)
			wait()
		end 
	end)

	Onandoff_16.Name = "Onandoff"
	Onandoff_16.Parent = Headless
	Onandoff_16.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_16.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_16.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_16.Size = UDim2.new(0, 135, 0, 15)

	KillAura.Name = "Kill Aura"
	KillAura.Parent = CombatScrollFrame
	KillAura.BackgroundColor3 = Color3.new(0, 0, 0)
	KillAura.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	KillAura.Position = UDim2.new(0.0303712785, 0, 0.320992827, 0)
	KillAura.Size = UDim2.new(0, 135, 0, 26)
	KillAura.Font = Enum.Font.SourceSans
	KillAura.Text = "Kill Aura"
	KillAura.TextColor3 = Color3.new(1, 1, 1)
	KillAura.TextSize = 18
	KillAura.MouseButton1Click:connect(function()
		noti("Hold [U] To Toggle It.")
		maus = game.Players.LocalPlayer:GetMouse()
		maus.KeyDown:Connect(function(key)
			if key == "u" then
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") then
					game.Players.LocalPlayer.Backpack:FindFirstChild("Combat").Parent = game.Players.LocalPlayer.Character
				end
				wait()
				game.Players.LocalPlayer.Character:FindFirstChild("Combat"):Activate()
				local localPlayer     = game:GetService("Players").LocalPlayer;
				local localCharacter  = localPlayer.Character;

				pcall(function()
					localCharacter.LeftHand.LeftWrist:Destroy();
					localCharacter.RightHand.RightWrist:Destroy();
				end);


				if game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") then
					game.Players.LocalPlayer.Backpack:FindFirstChild("Combat").Parent = game.Players.LocalPlayer.Character
				end
				wait()
				game.Players.LocalPlayer.Character:FindFirstChild("Combat"):Activate()
				if game.Players.LocalPlayer.Character then
					if game.Players.LocalPlayer.character:FindFirstChild("HumanoidRootPart") then
						returnpos = game.Players.LocalPlayer.character:FindFirstChild("HumanoidRootPart").CFrame
					end
				end    
				wait(1.1)

				for i,v in pairs(game.Players:GetChildren()) do
					if v.Name ~= game.Players.LocalPlayer.Name and v.Name ~= "Vortextures" and v.Name ~= "Vortexturize" and v.Name ~= "Vortexturable" then
						if v.Character then
							if v.Character:FindFirstChild("HumanoidRootPart") then
								distance = game.Players.LocalPlayer:DistanceFromCharacter(v.Character.HumanoidRootPart.Position)

								if distance < 35 then
									for i = 1,5 do
										if v then
											if v.Character and game.Players.LocalPlayer.Character then
												if v.Character:FindFirstChild("HumanoidRootPart") and game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart") and v.Character.Humanoid.Health > 10 then
													game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").CFrame = v.Character:FindFirstChild("HumanoidRootPart").CFrame * CFrame.new(0,0,0.7)
												end
											end
										end
										game.Workspace.CurrentCamera.CFrame = CFrame.new(game.Workspace.CurrentCamera.CFrame.p, v.Character.HumanoidRootPart.CFrame.p)
										wait(0.05)
									end

								end

							end
						end
					end
				end
			end
		end)
	end)

	Onandoff_17.Name = "Onandoff"
	Onandoff_17.Parent = KillAura
	Onandoff_17.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_17.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_17.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_17.Size = UDim2.new(0, 135, 0, 15)

	SplitGrenade.Name = "Split Grenade"
	SplitGrenade.Parent = CombatScrollFrame
	SplitGrenade.BackgroundColor3 = Color3.new(0, 0, 0)
	SplitGrenade.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	SplitGrenade.Position = UDim2.new(0.266574472, 0, 0.319572389, 0)
	SplitGrenade.Size = UDim2.new(0, 135, 0, 26)
	SplitGrenade.Font = Enum.Font.SourceSans
	SplitGrenade.Text = "Split Grenade"
	SplitGrenade.TextColor3 = Color3.new(1, 1, 1)
	SplitGrenade.TextSize = 18
	SplitGrenade.MouseButton1Click:connect(function()
		if game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]") then
			local LocalPlayer = game:GetService("Players").LocalPlayer
			local char = LocalPlayer.Character
			local Ignored = game.workspace.Ignored
			local backpack = LocalPlayer.Backpack
			local x = 0
			local Grenade = "[Grenade]"
			local DroppedGrenade = "Handle"

			for i,v in pairs(backpack:GetChildren()) do
				if v.Name == Grenade then
					v.Parent = char
				end
			end
			for i,v in pairs(char:GetChildren()) do
				if v.Name == Grenade then
					v:Activate()
					v:Activate()
				end
			end
		else
			noti("Buy Grenade")
		end
	end)

	Onandoff_18.Name = "Onandoff"
	Onandoff_18.Parent = SplitGrenade
	Onandoff_18.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_18.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_18.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_18.Size = UDim2.new(0, 135, 0, 15)

	BlackHole.Name = "BlackHole"
	BlackHole.Parent = CombatScrollFrame
	BlackHole.BackgroundColor3 = Color3.new(0, 0, 0)
	BlackHole.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	BlackHole.Position = UDim2.new(0.501285195, 0, 0.319572389, 0)
	BlackHole.Size = UDim2.new(0, 135, 0, 26)
	BlackHole.Font = Enum.Font.SourceSans
	BlackHole.Text = "BlackHole"
	BlackHole.TextColor3 = Color3.new(1, 1, 1)
	BlackHole.TextSize = 18
	BlackHole.MouseButton1Click:connect(function()
		if Onandoff_19.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_19.BackgroundColor3 = Color3.new(0, 1, 0)
			alsoko = true
			local UserInputService = game:GetService("UserInputService")
			local Mouse = game:GetService("Players").LocalPlayer:GetMouse()
			local Folder = Instance.new("Folder", game:GetService("Workspace"))
			local Part = Instance.new("Part", Folder)
			local Attachment1 = Instance.new("Attachment", Part)
			Part.Anchored = true
			Part.CanCollide = false
			Part.Transparency = 1
			local Updated = Mouse.Hit + Vector3.new(0, 5, 0)
			local NetworkAccess = coroutine.create(function()
				settings().Physics.AllowSleep = false
				repeat
					for _, Players in next, game:GetService("Players"):GetPlayers() do
						if Players ~= game:GetService("Players").LocalPlayer then
							Players.MaximumSimulationRadius = 0 
							sethiddenproperty(Players, "SimulationRadius", 0) 
						end 
					end
					game:GetService("Players").LocalPlayer.MaximumSimulationRadius = math.pow(math.huge, math.huge)
					setsimulationradius(math.huge) 
					wait()
				until alsoko == false
			end) 
			coroutine.resume(NetworkAccess)
			local function ForcePart(v)
				if v:IsA("Part") and v.Anchored == false and v.Parent:FindFirstChild("Humanoid") == nil and v.Parent:FindFirstChild("Head") == nil and v.Name ~= "Handle" then
					Mouse.TargetFilter = v
					for _, x in next, v:GetChildren() do
						if x:IsA("BodyAngularVelocity") or x:IsA("BodyForce") or x:IsA("BodyGyro") or x:IsA("BodyPosition") or x:IsA("BodyThrust") or x:IsA("BodyVelocity") or x:IsA("RocketPropulsion") then
							x:Destroy()
						end
					end
					if v:FindFirstChild("Attachment") then
						v:FindFirstChild("Attachment"):Destroy()
					end
					if v:FindFirstChild("AlignPosition") then
						v:FindFirstChild("AlignPosition"):Destroy()
					end
					if v:FindFirstChild("Torque") then
						v:FindFirstChild("Torque"):Destroy()
					end
					v.CanCollide = false
					local Torque = Instance.new("Torque", v)
					Torque.Torque = Vector3.new(100000, 100000, 100000)
					local AlignPosition = Instance.new("AlignPosition", v)
					local Attachment2 = Instance.new("Attachment", v)
					Torque.Attachment0 = Attachment2
					AlignPosition.MaxForce = 9999999999999999
					AlignPosition.MaxVelocity = math.huge
					AlignPosition.Responsiveness = 200
					AlignPosition.Attachment0 = Attachment2 
					AlignPosition.Attachment1 = Attachment1
				end
			end
			for _, v in next, game:GetService("Workspace"):GetDescendants() do
				ForcePart(v)
			end
			game:GetService("Workspace").DescendantAdded:Connect(function(v)
				ForcePart(v)
			end)
		else
			Onandoff_19.BackgroundColor3 = Color3.new(1, 0, 0)
			alsoko = false
		end

	end)

	Onandoff_19.Name = "Onandoff"
	Onandoff_19.Parent = BlackHole
	Onandoff_19.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_19.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_19.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_19.Size = UDim2.new(0, 135, 0, 15)

	BurgerSword.Name = "BurgerSword"
	BurgerSword.Parent = CombatScrollFrame
	BurgerSword.BackgroundColor3 = Color3.new(0, 0, 0)
	BurgerSword.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	BurgerSword.Position = UDim2.new(0.739301741, 0, 0.320992857, 0)
	BurgerSword.Size = UDim2.new(0, 135, 0, 26)
	BurgerSword.Font = Enum.Font.SourceSans
	BurgerSword.Text = "BurgerSword"
	BurgerSword.TextColor3 = Color3.new(1, 1, 1)
	BurgerSword.TextSize = 18
	BurgerSword.MouseButton1Click:connect(function()
		flying = false
		local lol = game.Workspace.Ignored.Shop["[Hamburger] - $5"]
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		wait(0.15)
		game.StarterGui:SetCore("SendNotification", {
			Title = "Polakya";
			Text = "Please wait";
			Duration = 15;
		})
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.40)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-1, 0, 0.1)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-2, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-4, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-5, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-6, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-7, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-8, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-9, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-10, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-11, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-12, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-13, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character
		wait(0.45)
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.45)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripPos     = Vector3.new(-14, 0, 0.3)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripRight     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].GripUp     = Vector3.new(-1, 0, 0)
		game.Players.LocalPlayer.Backpack["[Hamburger]"].Parent = game.Players.LocalPlayer.Character

	end)

	Onandoff_20.Name = "Onandoff"
	Onandoff_20.Parent = BurgerSword
	Onandoff_20.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_20.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_20.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_20.Size = UDim2.new(0, 135, 0, 15)

	AntiGrab.Name = "AntiGrab"
	AntiGrab.Parent = CombatScrollFrame
	AntiGrab.BackgroundColor3 = Color3.new(0, 0, 0)
	AntiGrab.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AntiGrab.Position = UDim2.new(0.0287183858, 0, 0.393436015, 0)
	AntiGrab.Size = UDim2.new(0, 135, 0, 26)
	AntiGrab.Font = Enum.Font.SourceSans
	AntiGrab.Text = "AntiGrab"
	AntiGrab.TextColor3 = Color3.new(1, 1, 1)
	AntiGrab.TextSize = 18
	AntiGrab.MouseButton1Click:connect(function()
		if Onandoff_21.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_21.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("Grab Removed")
			antiuy = true
			delay(0, function()
				while antiuy == true do 
					pcall(function()
						game.Players.LocalPlayer.Character.GRABBING_CONSTRAINT:Destroy()
					end)
					wait()

				end
			end)
		else
			noti("Grab Back To Normal")
			Onandoff_21.BackgroundColor3 = Color3.new(1, 0, 0)
			antiuy = false
		end
	end)

	Onandoff_21.Name = "Onandoff"
	Onandoff_21.Parent = AntiGrab
	Onandoff_21.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_21.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_21.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_21.Size = UDim2.new(0, 135, 0, 15)

	AutoEat.Name = "AutoEat"
	AutoEat.Parent = CombatScrollFrame
	AutoEat.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoEat.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoEat.Position = UDim2.new(0.266734928, 0, 0.393436015, 0)
	AutoEat.Size = UDim2.new(0, 135, 0, 26)
	AutoEat.Font = Enum.Font.SourceSans
	AutoEat.Text = "AutoEat"
	AutoEat.TextColor3 = Color3.new(1, 1, 1)
	AutoEat.TextSize = 18
	AutoEat.MouseButton1Click:connect(function()
		local flingop = false

		if Onandoff_22.BackgroundColor3 == Color3.new(1, 0, 0) and flingop == false then
			Onandoff_22.BackgroundColor3 = Color3.new(0, 1, 0)
			flingop = true
			gsPlayers = game:GetService("Players")
			gsWorkspace = game:GetService("Workspace")
			gsLighting = game:GetService("Lighting")
			gsReplicatedStorage = game:GetService("ReplicatedStorage")
			gsCoreGui = game:GetService("CoreGui")
			gsTween = game:GetService("TweenService")
			gsHttp = game:GetService("HttpService")

			LP = gsPlayers.LocalPlayer
			Mouse = LP:GetMouse()

			if flingop == true then
				pcall(function()
					if game.Players.LocalPlayer.Character.Humanoid.Health <= 20 and flingop == true then
						SavedPosition = ""
						SavedPosition = LP.Character.HumanoidRootPart.CFrame
						game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-793.978027, -39.6492004, -938.048706)
						wait(.5)

						fireclickdetector(game.Workspace.Ignored.Shop['[Chicken] - $7'].ClickDetector)
						fireclickdetector(game.Workspace.Ignored.Shop['[Chicken] - $7'].ClickDetector)
						wait(.2)

						local Players = game:GetService("Players")
						local Client = Players.LocalPlayer

						local ToolName = "[Chicken]"
						if Client.Backpack:FindFirstChild(ToolName) then
							Client.Backpack[ToolName].Parent = Client.Character
							wait(.2)
							if game.Players.LocalPlayer.Character:FindFirstChild("[Chicken]") then
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait(0.6)
								game.Players.LocalPlayer.Character["[Chicken]"]:Activate()
								wait()
							end
							if SavedPosition ~= "" and flingop == true  then
								LP.Character.HumanoidRootPart.CFrame = SavedPosition
							end;
						end;
					end;
				end);
				wait()
			end;
		else
			Onandoff_22.BackgroundColor3 = Color3.new(1, 0, 0)
			flingop = false
		end
	end)

	Onandoff_22.Name = "Onandoff"
	Onandoff_22.Parent = AutoEat
	Onandoff_22.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_22.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_22.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_22.Size = UDim2.new(0, 135, 0, 15)

	HatFling.Name = "HatFling"
	HatFling.Parent = CombatScrollFrame
	HatFling.BackgroundColor3 = Color3.new(0, 0, 0)
	HatFling.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	HatFling.Position = UDim2.new(0.501445651, 0, 0.393436015, 0)
	HatFling.Size = UDim2.new(0, 135, 0, 26)
	HatFling.Font = Enum.Font.SourceSans
	HatFling.Text = "HatFling"
	HatFling.TextColor3 = Color3.new(1, 1, 1)
	HatFling.TextSize = 18
	HatFling.MouseButton1Click:connect(function()
		if hatfling.TextColor3 == Color3.new(1, 0, 0) then
			hatfling.TextColor3 = Color3.new(0, 1, 0)
			flinnice = true
			spawn(function()
				while flinnice == true do game:GetService("RunService").Heartbeat:wait()
					for i,v in pairs(game.Players:GetPlayers()) do
						if v == game.Players.LocalPlayer == false then
							game.Players.LocalPlayer.MaximumSimulationRadius = math.pow(math.huge,math.huge)*math.huge
							game.Players.LocalPlayer.SimulationRadius = math.pow(math.huge,math.huge)*math.huge
							v.MaximumSimulationRadius = 0
							v.SimulationRadius = 0
							game:GetService("RunService").Stepped:wait()
						end
					end
				end
			end)

			local Player = game:GetService("Players").LocalPlayer
			local Players = game:GetService("Players")
			local HatList = {}
			local i = 0
			for _,l in pairs(Player.Character:GetChildren()) do
				if l:IsA("Accessory") then if i>0 then l.Parent = workspace  end i = i + 1 end;
			end
			wait(.1)



			for _,v in pairs(workspace:GetDescendants()) do
				if v.Name == "Handle" and v:IsA("BasePart") and v.Parent:IsA("Accessory") and v:IsDescendantOf(Player.Character)==false and Players:GetPlayerFromCharacter(v.Parent.Parent)==nil then
					table.insert(HatList,v)
				end
			end

			for _,hat in pairs(HatList) do
				hat.Parent = workspace
				hat.Position = Player.Character.HumanoidRootPart.Position + Player.Character.HumanoidRootPart.CFrame.lookVector * 5
				local BodyPos = Instance.new("BodyPosition",hat)
				local BodyAng = Instance.new("BodyAngularVelocity",hat)
				BodyAng.AngularVelocity = Vector3.new(0,9e12,0)
				BodyAng.P = 9e12
				BodyPos.MaxForce = Vector3.new(9e9,9e9,9e9)
				BodyPos.P = 9e8
				spawn(function()
					while flinnice == true do
						if pcall(function()
								hat.CanCollide = false
								BodyPos.Position = Player.Character.HumanoidRootPart.Position + Vector3.new(math.random(-2,2),math.random(-2,2),math.random(-2,2))
							end) then
						else
							BodyPos:Destroy()
							hat.CanCollide = true
						end
						wait()
					end
				end)

			end
		else
			Onandoff_23.BackgroundColor3 = Color3.new(1, 0, 0)
			flinnice = false
		end
	end)

	Onandoff_23.Name = "Onandoff"
	Onandoff_23.Parent = HatFling
	Onandoff_23.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_23.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_23.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_23.Size = UDim2.new(0, 135, 0, 15)

	Clone.Name = "Clone"
	Clone.Parent = CombatScrollFrame
	Clone.BackgroundColor3 = Color3.new(0, 0, 0)
	Clone.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Clone.Position = UDim2.new(0.739301741, 0, 0.392015576, 0)
	Clone.Size = UDim2.new(0, 135, 0, 26)
	Clone.Font = Enum.Font.SourceSans
	Clone.Text = "Clone"
	Clone.TextColor3 = Color3.new(1, 1, 1)
	Clone.TextSize = 18
	Clone.MouseButton1Click:connect(function()
		local plr = game.Players.LocalPlayer
		local AncientPOS = plr.Character.HumanoidRootPart.Position
		wait()

		local Player = game:GetService("Players").LocalPlayer
		local Players = game:GetService("Players")
		local HatList = {}
		local i = 0
		plr = game.Players.LocalPlayer
		for _,l in pairs(Player.Character:GetChildren()) do
			if l:IsA("BasePart") then if i>0 then l.Parent = workspace  end i = i + 1 end;
		end
		wait(7)
		plr.Character.HumanoidRootPart.CFrame = CFrame.new(AncientPOS)
		plr.Character.HumanoidRootPart.CFrame = CFrame.new(AncientPOS)	
	end)

	Onandoff_24.Name = "Onandoff"
	Onandoff_24.Parent = Clone
	Onandoff_24.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_24.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_24.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_24.Size = UDim2.new(0, 135, 0, 15)

	AutoMuteBox.Name = "AutoMuteBox"
	AutoMuteBox.Parent = CombatScrollFrame
	AutoMuteBox.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoMuteBox.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoMuteBox.Position = UDim2.new(0.0287183821, 0, 0.470140576, 0)
	AutoMuteBox.Size = UDim2.new(0, 135, 0, 26)
	AutoMuteBox.Font = Enum.Font.SourceSans
	AutoMuteBox.Text = "AutoMuteBox"
	AutoMuteBox.TextColor3 = Color3.new(1, 1, 1)
	AutoMuteBox.TextSize = 18
	AutoMuteBox.MouseButton1Click:connect(function()
		if Onandoff_25.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_25.BackgroundColor3 = Color3.new(0, 1, 0)
			mutelol = true
			local l__LocalPlayer__2 = game.Players.LocalPlayer;
			local v3 = require(game.ReplicatedStorage.MainModule);
			l__LocalPlayer__2:WaitForChild("DataFolder");
			local l__Character__4 = l__LocalPlayer__2.Character;

			for v211, v212 in pairs(workspace.Players:GetChildren()) do
				delay(0, function()

					while mutelol == true do
						pcall(function()

							v212.LowerTorso.BOOMBOXSOUND.Volume = 0;

						end)
						wait()
					end

				end)

			end
		else
			Onandoff_25.BackgroundColor3 = Color3.new(1, 0, 0)
			for v211, v212 in pairs(workspace.Players:GetChildren()) do
				mutelol = false
				pcall(function()
					v212.LowerTorso.BOOMBOXSOUND.Volume = 0.5;

				end)

			end



		end
	end)

	Onandoff_25.Name = "Onandoff"
	Onandoff_25.Parent = AutoMuteBox
	Onandoff_25.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_25.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_25.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_25.Size = UDim2.new(0, 135, 0, 15)

	GrenadeMouse.Name = "GrenadeMouse"
	GrenadeMouse.Parent = CombatScrollFrame
	GrenadeMouse.BackgroundColor3 = Color3.new(0, 0, 0)
	GrenadeMouse.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	GrenadeMouse.Position = UDim2.new(0.266734898, 0, 0.470140576, 0)
	GrenadeMouse.Size = UDim2.new(0, 135, 0, 26)
	GrenadeMouse.Font = Enum.Font.SourceSans
	GrenadeMouse.Text = "GrenadeMouse"
	GrenadeMouse.TextColor3 = Color3.new(1, 1, 1)
	GrenadeMouse.TextSize = 18
	GrenadeMouse.MouseButton1Click:connect(function()
		if 	Onandoff_26.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_26.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("Grenademouse enabled")
			grenadetyu = true
			local plr = game.Players.LocalPlayer
			local Mouse = plr:GetMouse()
			local speed = 50
			local debug = true
			local seats = {}


			delay(0, function()
				while grenadetyu == true do
					pcall(function()
						if game.Workspace.Ignored:FindFirstChild("Grenade")  then
							local lol = game.Workspace.Ignored:FindFirstChild("Grenade")

							if lol:FindFirstChildOfClass("BodyVelocity") then
								wait()
								lol.BodyVelocity:Destroy()
							end

							if lol:FindFirstChild("BodyVelocity") == nil then
								lol.CFrame =  CFrame.new(Mouse.Hit.p);
							end

						elseif game.Workspace.Ignored:FindFirstChild("Handle")  then
							local lol = game.Workspace.Ignored:FindFirstChild("Handle")

							if lol:FindFirstChild("Pin") then
								lol.CFrame =  CFrame.new(Mouse.Hit.p);
							end
						end
					end)
					wait()
				end
			end)
		else
			Onandoff_26.BackgroundColor3 = Color3.new(1, 0, 0)
			noti("Grenademouse disabled")

			grenadetyu = false
		end
	end)

	Onandoff_26.Name = "Onandoff"
	Onandoff_26.Parent = GrenadeMouse
	Onandoff_26.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_26.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_26.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_26.Size = UDim2.new(0, 135, 0, 15)

	FlyingHands.Name = "FlyingHands"
	FlyingHands.Parent = CombatScrollFrame
	FlyingHands.BackgroundColor3 = Color3.new(0, 0, 0)
	FlyingHands.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FlyingHands.Position = UDim2.new(0.501445651, 0, 0.470140576, 0)
	FlyingHands.Size = UDim2.new(0, 135, 0, 26)
	FlyingHands.Font = Enum.Font.SourceSans
	FlyingHands.Text = "FlyingHands"
	FlyingHands.TextColor3 = Color3.new(1, 1, 1)
	FlyingHands.TextSize = 18
	FlyingHands.MouseButton1Click:connect(function()
		if 		Onandoff_27.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_27.BackgroundColor3 = Color3.new(0, 1, 0)
			if bal == false then
				game.Players.LocalPlayer.Character.Head:Destroy()
				Onandoff_27.BackgroundColor3 = Color3.new(1, 0, 0)
				noti("Restarting FlyingHands..")
			end
			noti("Try using it with FistReach ;)")
			bal = true

			local Part = Instance.new("Part",workspace)
			Part.Name = "GetFucked"
			Part.Anchored = false
			Part.CanCollide = false
			Part.Transparency = 1
			local Part1= Instance.new("Part",workspace)
			Part1.Name = "GetFucked1"
			Part1.Anchored = true
			Part1.CanCollide = false
			Part1.Transparency = 1

			local Weld = Instance.new("Weld", Part1)
			Weld.Part0 = Part1
			Weld.Part1 = Part
			Weld.C0 = CFrame.new(0, 0, 10000)
			local cor = coroutine.wrap(function()
				wait(2)
				Part:Destroy()
				Part1:Destroy()
				Weld:Destroy()
			end)



			game:GetService('RunService').Stepped:connect(function()
				if noclip then
					game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
				end
			end)		
			noclip = not noclip
			repeat 
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)

				game.Players.LocalPlayer.Character.RightHand.Massless = true

				game.Players.LocalPlayer.Character.RightHand.RightWrist:Destroy()
				game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.RightHand
				game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)


				local RightHand = game.Players.LocalPlayer.Character.RightHand
				local mouse = game.Players.LocalPlayer:GetMouse()

				local groot = nil

				groot = RightHand

				local plr = game.Players.LocalPlayer
				mouse = plr:GetMouse()

				local plr = game.Players.LocalPlayer
				local torso = RightHand
				local flyings = true
				local deb = true
				local ctrl = {f = 0, b = 0, l = 0, r = 0}
				local lastctrl = {f = 0, b = 0, l = 0, r = 0}
				local maxspeed = 30000
				local speed = 50

				if workspace:FindFirstChild("Core") then
					workspace.Core:Destroy()
				end

				function Fly()
					local bg = Instance.new("BodyGyro", RightHand)
					bg.P = 9e4
					bg.maxTorque = Vector3.new(0, 0, 0)
					bg.cframe = RightHand.CFrame
					local bv = Instance.new("BodyVelocity", RightHand)
					bv.velocity = Vector3.new(0,0,0)
					bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
					repeat wait()

						if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
							speed = speed+.2
							if speed > maxspeed then
								speed = maxspeed
							end
						elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
							speed = speed-1
							if speed < 0 then
								speed = 0
							end
						end
						if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
							bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
							lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
						elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
							bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
						else
							bv.velocity = Vector3.new(0,0.1,0)
						end

					until not flyings or bal == false
					ctrl = {f = 0, b = 0, l = 0, r = 0}
					lastctrl = {f = 0, b = 0, l = 0, r = 0}
					speed = 0
					bg:Destroy()
					bv:Destroy()

				end
				mouse.KeyDown:connect(function(key)
					if key:lower() == "c" then
						if flyings then flyings = false
						else
							flyings = true
							Fly()
						end
					elseif key:lower() == "w" then
						ctrl.f = 1
					elseif key:lower() == "s" then
						ctrl.b = -1
					elseif key:lower() == "a" then
						ctrl.l = -1
					elseif key:lower() == "d" then
						ctrl.r = 1
					end
				end)
				mouse.KeyUp:connect(function(key)
					if key:lower() == "w" then
						ctrl.f = 0
					elseif key:lower() == "s" then
						ctrl.b = 0
					elseif key:lower() == "a" then
						ctrl.l = 0
					elseif key:lower() == "d" then
						ctrl.r = 0
					elseif key:lower() == "r" then

					end
				end)
				Fly()
			until bal == false
		else	
			Onandoff_27.BackgroundColor3 = Color3.new(1, 0, 0)
			bal = false

			noclip = false
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			noclip = false
			local localPlayer = game.Players.LocalPlayer
			game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-432.989, 26.717, -284.6)
			local lol = game.Players.LocalPlayer.Character.HumanoidRootPart
			for i = 1, 10 do
				game.Players.LocalPlayer.Character.RightHand.CFrame = lol.CFrame
				game.Players.LocalPlayer.Character.LeftHand.CFrame = lol.CFrame
				wait(0.05)
			end
		end

	end)

	Onandoff_27.Name = "Onandoff"
	Onandoff_27.Parent = FlyingHands
	Onandoff_27.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_27.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_27.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_27.Size = UDim2.new(0, 135, 0, 15)

	RpgControl.Name = "RpgControl"
	RpgControl.Parent = CombatScrollFrame
	RpgControl.BackgroundColor3 = Color3.new(0, 0, 0)
	RpgControl.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	RpgControl.Position = UDim2.new(0.7378093, 0, 0.470140576, 0)
	RpgControl.Size = UDim2.new(0, 135, 0, 26)
	RpgControl.Font = Enum.Font.SourceSans
	RpgControl.Text = "RpgControl"
	RpgControl.TextColor3 = Color3.new(1, 1, 1)
	RpgControl.TextSize = 18
	RpgControl.MouseButton1Click:connect(function()
		if 	Onandoff_28.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_28.BackgroundColor3 = Color3.new(0, 1, 0)
			contralamaky = true

			game.Workspace.Ignored.ChildAdded:connect(function(child)

				if child.Name == "Launcher" and contralamaky == true then
					peniscock = child
					local groot = nil
					if contralamaky == true then
						game.Workspace.Camera.CameraSubject = peniscock
						game.Players.LocalPlayer.Character.HumanoidRootPart.Massless = true

					end


					groot = peniscock

					local plr = game.Players.LocalPlayer
					mouse = plr:GetMouse()

					local plr = game.Players.LocalPlayer
					local torso = peniscock
					local flying = true
					local deb = true
					local ctrl = {f = 0, b = 0, l = 0, r = 0}
					local lastctrl = {f = 0, b = 0, l = 0, r = 0}
					local maxspeed = 30000
					local speed = 50

					if workspace:FindFirstChild("Core") then
						workspace.Core:Destroy()
					end

					function Fly()
						local bg = Instance.new("BodyGyro", peniscock)
						bg.P = 9e4
						bg.maxTorque = Vector3.new(0, 0, 0)
						bg.cframe = peniscock.CFrame
						local bv = Instance.new("BodyVelocity", peniscock)
						bv.velocity = Vector3.new(0,0,0)
						bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
						repeat wait()

							if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
								speed = speed+.2
								if speed > maxspeed then
									speed = maxspeed
								end
							elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
								speed = speed-1
								if speed < 0 then
									speed = 0
								end
							end
							if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
								bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
								lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
							elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
								bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
							else
								bv.velocity = Vector3.new(0,0.1,0)
							end

						until not flying or contralamaky == false

						ctrl = {f = 0, b = 0, l = 0, r = 0}
						lastctrl = {f = 0, b = 0, l = 0, r = 0}
						speed = 0
						bg:Destroy()
						bv:Destroy()

					end
					mouse.KeyDown:connect(function(key)
						if key:lower() == "x" then
							if flying then flying = false
							else
								flying = true
								Fly()
							end
						elseif key:lower() == "w" then
							ctrl.f = 1
						elseif key:lower() == "s" then
							ctrl.b = -1
						elseif key:lower() == "a" then
							ctrl.l = -1
						elseif key:lower() == "d" then
							ctrl.r = 1
						end
					end)
					mouse.KeyUp:connect(function(key)
						if key:lower() == "w" then
							ctrl.f = 0
						elseif key:lower() == "s" then
							ctrl.b = 0
						elseif key:lower() == "a" then
							ctrl.l = 0
						elseif key:lower() == "d" then
							ctrl.r = 0
						elseif key:lower() == "r" then

						end
					end)
					Fly()
				end
			end)


		else
			Onandoff_28.BackgroundColor3 = Color3.new(1, 0, 0)
			contralamaky = false
			game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid;

			game.Players.LocalPlayer.Character.HumanoidRootPart.Massless = false

		end

	end)

	Onandoff_28.Name = "Onandoff"
	Onandoff_28.Parent = RpgControl
	Onandoff_28.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_28.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_28.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_28.Size = UDim2.new(0, 135, 0, 15)

	RpgRide.Name = "RpgRide"
	RpgRide.Parent = CombatScrollFrame
	RpgRide.BackgroundColor3 = Color3.new(0, 0, 0)
	RpgRide.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	RpgRide.Position = UDim2.new(0.0287184119, 0, 0.544004202, 0)
	RpgRide.Size = UDim2.new(0, 135, 0, 26)
	RpgRide.Font = Enum.Font.SourceSans
	RpgRide.Text = "RpgRide"
	RpgRide.TextColor3 = Color3.new(1, 1, 1)
	RpgRide.TextSize = 18
	RpgRide.MouseButton1Click:connect(function()
		if Onandoff_29.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_29.BackgroundColor3 = Color3.new(0, 1, 0)
			ezride = true
			game.Workspace.Ignored.ChildAdded:connect(function(child)

				if child.Name == "Launcher" and ezride == true then

					peniscock = child
					local groot = nil

					groot = peniscock

					local plr = game.Players.LocalPlayer
					mouse = plr:GetMouse()

					game:GetService("RunService").Stepped:connect(function()
						if peniscock and peniscock.Parent ~= nil and ezride == true then
							setsimulationradius(math.huge^math.huge, math.huge)
							plr.Character.HumanoidRootPart.Anchored = true
							plr.Character.HumanoidRootPart.CFrame = CFrame.new(peniscock.Position + Vector3.new(0, 3, 0))*CFrame.Angles(0, -90, 0)
							plr.Character.Humanoid.Sit = true
						else plr.Character.HumanoidRootPart.Anchored = false end
					end)

					local plr = game.Players.LocalPlayer
					local torso = peniscock
					local flying = true
					local deb = true
					local ctrl = {f = 0, b = 0, l = 0, r = 0}
					local lastctrl = {f = 0, b = 0, l = 0, r = 0}
					local maxspeed = 30000
					local speed = 50

					if workspace:FindFirstChild("Core") then
						workspace.Core:Destroy()
					end

					function Fly()
						local bg = Instance.new("BodyGyro", peniscock)
						bg.P = 9e4
						bg.maxTorque = Vector3.new(0, 0, 0)
						bg.cframe = peniscock.CFrame
						local bv = Instance.new("BodyVelocity", peniscock)
						bv.velocity = Vector3.new(0,0,0)
						bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
						repeat wait()

							if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
								speed = speed+.2
								if speed > maxspeed then
									speed = maxspeed
								end
							elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
								speed = speed-1
								if speed < 0 then
									speed = 0
								end
							end
							if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
								bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
								lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
							elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
								bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
							else
								bv.velocity = Vector3.new(0,0.1,0)
							end

						until not flying 

						ctrl = {f = 0, b = 0, l = 0, r = 0}
						lastctrl = {f = 0, b = 0, l = 0, r = 0}
						speed = 0
						bg:Destroy()
						bv:Destroy()

					end
					mouse.KeyDown:connect(function(key)
						if key:lower() == "x" then
							if flying then flying = false
							else
								flying = true
								Fly()
							end
						elseif key:lower() == "w" then
							ctrl.f = 1
						elseif key:lower() == "s" then
							ctrl.b = -1
						elseif key:lower() == "a" then
							ctrl.l = -1
						elseif key:lower() == "d" then
							ctrl.r = 1
						end
					end)
					mouse.KeyUp:connect(function(key)
						if key:lower() == "w" then
							ctrl.f = 0
						elseif key:lower() == "s" then
							ctrl.b = 0
						elseif key:lower() == "a" then
							ctrl.l = 0
						elseif key:lower() == "d" then
							ctrl.r = 0
						elseif key:lower() == "r" then

						end
					end)
					Fly()
				end
			end)


		else
			Onandoff_29.BackgroundColor3 = Color3.new(1, 0, 0)
			ezride = false
		end
	end)

	Onandoff_29.Name = "Onandoff"
	Onandoff_29.Parent = RpgRide
	Onandoff_29.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_29.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_29.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_29.Size = UDim2.new(0, 135, 0, 15)

	AutoReload.Name = "AutoReload"
	AutoReload.Parent = CombatScrollFrame
	AutoReload.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoReload.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoReload.Position = UDim2.new(0.266734958, 0, 0.544004202, 0)
	AutoReload.Size = UDim2.new(0, 135, 0, 26)
	AutoReload.Font = Enum.Font.SourceSans
	AutoReload.Text = "AutoReload"
	AutoReload.TextColor3 = Color3.new(1, 1, 1)
	AutoReload.TextSize = 18
	AutoReload.MouseButton1Click:connect(function()
		if 		Onandoff_30.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_30.BackgroundColor3 = Color3.new(0, 1, 0)
			ralod = true
			while ralod == true and wait(2) do
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[LMG]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[Silencer]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[AUG]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[SMG]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[Shotgun]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[AR]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[AK47]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[Glock]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[P90]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[SilencerAR]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[TacticalShotgun]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[Double-Barrel SG]")

				end)
				pcall(function()
					function reload(name, gun)

						local XD1 = "Reload"
						local XD2 = game:GetService("Workspace").Players[name][gun]
						local Event = game:GetService("ReplicatedStorage").MainEvent
						Event:FireServer(XD1, XD2)
					end	
					reload(game.Players.LocalPlayer.Name, "[RPG]")

				end)
				wait()	
			end







		else		
			Onandoff_30.BackgroundColor3 = Color3.new(1, 0, 0)
			ralod = false

		end
	end)

	Onandoff_30.Name = "Onandoff"
	Onandoff_30.Parent = AutoReload
	Onandoff_30.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_30.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_30.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_30.Size = UDim2.new(0, 135, 0, 15)

	MaskNames.Name = "MaskNames"
	MaskNames.Parent = CombatScrollFrame
	MaskNames.BackgroundColor3 = Color3.new(0, 0, 0)
	MaskNames.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	MaskNames.Position = UDim2.new(0.501285255, 0, 0.542583764, 0)
	MaskNames.Size = UDim2.new(0, 135, 0, 26)
	MaskNames.Font = Enum.Font.SourceSans
	MaskNames.Text = "MaskNames"
	MaskNames.TextColor3 = Color3.new(1, 1, 1)
	MaskNames.TextSize = 18
	MaskNames.MouseButton1Click:connect(function()
		noti("MaskNames Enabled")
		game:GetService("RunService").Heartbeat:Connect(function()
			for i, v in pairs(game.Players:GetPlayers()) do
				if v and v.Character and v.Character:FindFirstChildOfClass("Humanoid") and v.Character:FindFirstChildOfClass("Humanoid").DisplayDistanceType ~= Enum.HumanoidDisplayDistanceType.Viewer then
					v.Character:FindFirstChildOfClass("Humanoid").DisplayDistanceType = Enum.HumanoidDisplayDistanceType.Viewer
				end
			end
		end)
	end)

	Onandoff_31.Name = "Onandoff"
	Onandoff_31.Parent = MaskNames
	Onandoff_31.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_31.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_31.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_31.Size = UDim2.new(0, 135, 0, 15)

	RpgMouse.Name = "RpgMouse"
	RpgMouse.Parent = CombatScrollFrame
	RpgMouse.BackgroundColor3 = Color3.new(0, 0, 0)
	RpgMouse.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	RpgMouse.Position = UDim2.new(0.739462197, 0, 0.542583764, 0)
	RpgMouse.Size = UDim2.new(0, 135, 0, 26)
	RpgMouse.Font = Enum.Font.SourceSans
	RpgMouse.Text = "RpgMouse"
	RpgMouse.TextColor3 = Color3.new(1, 1, 1)
	RpgMouse.TextSize = 18
	RpgMouse.MouseButton1Click:connect(function()
		if 	Onandoff_32.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_32.BackgroundColor3 = Color3.new(0, 1, 0)
			rpgmouseahahha = true
			-- SETTINGS --
			local speed = 20
			local turnSpeed = 3
			--------------

			local plr = game.Players.LocalPlayer
			local Mouse = plr:GetMouse()
			local peniscock
			local movers
			local control = {q=false,e=false,x=false}

			game:GetService("RunService").Stepped:connect(function()
				if peniscock and peniscock.Parent ~= nil  then
					setsimulationradius(math.huge^math.huge, math.huge)
					if plr.Character.Humanoid.Sit ~= true  then
						peniscock = nil
					end
					peniscock.CFrame = CFrame.lookAt(peniscock.CFrame.p, Mouse.Hit.p)*CFrame.Angles(math.rad(90), 0, 0)
					if control.x  then
						firetouchinterest() -- do the rest later lol
					end
				end
				if control.q and speed > 0  then
					speed = speed - 1
				end
				if control.e and speed < 100  then
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
				if child.Name == "Launcher" and rpgmouseahahha == true
				then
					plr.Character.Humanoid.Sit = true
					peniscock = child
					child:WaitForChild("BodyVelocity"):Destroy()
					local e = Instance.new("BodyVelocity", child)
					while peniscock and peniscock.Parent ~= nil do
						game.RunService.Stepped:wait()
						e.Velocity = ((child.CFrame * CFrame.new(0, -speed, 0)).p - child.CFrame.p)
					end
				end
			end)

		else
			Onandoff_32.BackgroundColor3 = Color3.new(1, 0, 0)
			rpgmouseahahha = false
		end
	end)

	Onandoff_32.Name = "Onandoff"
	Onandoff_32.Parent = RpgMouse
	Onandoff_32.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_32.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_32.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_32.Size = UDim2.new(0, 135, 0, 15)

	SuperRpg.Name = "SuperRpg"
	SuperRpg.Parent = CombatScrollFrame
	SuperRpg.BackgroundColor3 = Color3.new(0, 0, 0)
	SuperRpg.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	SuperRpg.Position = UDim2.new(0.0303713083, 0, 0.6235497, 0)
	SuperRpg.Size = UDim2.new(0, 135, 0, 26)
	SuperRpg.Font = Enum.Font.SourceSans
	SuperRpg.Text = "SuperRpg"
	SuperRpg.TextColor3 = Color3.new(1, 1, 1)
	SuperRpg.TextSize = 18
	SuperRpg.MouseButton1Click:connect(function()
		if 	Onandoff_33.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_33.BackgroundColor3 = Color3.new(0, 1, 0)
			superez = true
			-- SETTINGS --
			local 	 speed = 400 -- noob
			--------------

			local plr = game.Players.LocalPlayer

			game.Workspace.Ignored.ChildAdded:connect(function(child)
				wait()
				if child.Name == "Launcher" and superez == true then
					child:WaitForChild("BodyVelocity"):Destroy()
					Instance.new("BodyVelocity", child).Velocity = (child.CFrame * CFrame.new(0, -speed, 0)).p - child.CFrame.p
					while child and superez == true do
						game.RunService.Stepped:wait()
						setsimulationradius(math.huge^math.huge, math.huge)
					end
				end
			end)

		else
			Onandoff_33.BackgroundColor3 = Color3.new(1, 0, 0)
			superez = false
		end
	end)

	Onandoff_33.Name = "Onandoff"
	Onandoff_33.Parent = SuperRpg
	Onandoff_33.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_33.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_33.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_33.Size = UDim2.new(0, 135, 0, 15)

	BurgerStar.Name = "BurgerStar"
	BurgerStar.Parent = CombatScrollFrame
	BurgerStar.BackgroundColor3 = Color3.new(0, 0, 0)
	BurgerStar.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	BurgerStar.Position = UDim2.new(0.266734958, 0, 0.6235497, 0)
	BurgerStar.Size = UDim2.new(0, 135, 0, 26)
	BurgerStar.Font = Enum.Font.SourceSans
	BurgerStar.Text = "BurgerStar"
	BurgerStar.TextColor3 = Color3.new(1, 1, 1)
	BurgerStar.TextSize = 18
	BurgerStar.MouseButton1Click:connect(function()
		if 	Onandoff_34.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_34.BackgroundColor3 = Color3.new(0, 1, 0)
			burgar = true
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
					if v.Name == "[Hamburger]" and burgar == true
					then
						e = 0
						for i, v in pairs(a) do
							e = e + 1
						end
						table.insert(a, v)
						v.Parent = Plr.Character
					end
				end
			until e >= burgercount*9 or burgar == false

			spawn(function()
				while burgar == true
				do
					e = e + 0.01
					if e >= 1 then
						e = -1
					end
					wait()
				end
			end)
			for i, v in pairs(a) do
				spawn(function()
					while wait() do
						p = 2*(e*math.pi-(radian*i))
						if i <=math.floor(1*burgercount) and burgar == true
						then
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
				if burgar == true then
					burger.Parent = Plr.Character
				end
			end
		else
			Onandoff_34.BackgroundColor3 = Color3.new(1, 0, 0)
			burgar = false
			for _,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
				if (v:IsA("Tool")) then
					v.Parent = game.Players.LocalPlayer.Backpack
				end
			end
		end
	end)

	Onandoff_34.Name = "Onandoff"
	Onandoff_34.Parent = BurgerStar
	Onandoff_34.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_34.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_34.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_34.Size = UDim2.new(0, 135, 0, 15)

	DisableRpg.Name = "DisableRpg"
	DisableRpg.Parent = CombatScrollFrame
	DisableRpg.BackgroundColor3 = Color3.new(0, 0, 0)
	DisableRpg.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	DisableRpg.Position = UDim2.new(0.501445711, 0, 0.6235497, 0)
	DisableRpg.Size = UDim2.new(0, 135, 0, 26)
	DisableRpg.Font = Enum.Font.SourceSans
	DisableRpg.Text = "DisableRpg"
	DisableRpg.TextColor3 = Color3.new(1, 1, 1)
	DisableRpg.TextSize = 18
	DisableRpg.MouseButton1Click:connect(function()
		if 	Onandoff_35.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_35.BackgroundColor3 = Color3.new(0, 1, 0)
			disableezz = true
			game:GetService("RunService").Stepped:connect(function()
				setsimulationradius(9e9,9e9)
				for _, child in next, game.Workspace.Ignored:GetChildren() do
					if child.Name == "Launcher" and disableezz == true then
						child.Name = "reflected"
						local bv = child:FindFirstChild("BodyVelocity")
						local oldveloc = bv.Velocity
						local oldp  = bv.P
						bv:Destroy()
						local e = Instance.new("BodyVelocity", child)
						e.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
						e.P = oldp
						e.Velocity = -oldveloc
					end
				end
			end)

		else
			Onandoff_35.BackgroundColor3 = Color3.new(1, 0, 0)
			disableezz = false

		end


	end)

	Onandoff_35.Name = "Onandoff"
	Onandoff_35.Parent = DisableRpg
	Onandoff_35.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_35.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_35.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_35.Size = UDim2.new(0, 135, 0, 15)

	FlashBangMouse.Name = "FlashBangMouse"
	FlashBangMouse.Parent = CombatScrollFrame
	FlashBangMouse.BackgroundColor3 = Color3.new(0, 0, 0)
	FlashBangMouse.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FlashBangMouse.Position = UDim2.new(0.739462256, 0, 0.6235497, 0)
	FlashBangMouse.Size = UDim2.new(0, 135, 0, 26)
	FlashBangMouse.Font = Enum.Font.SourceSans
	FlashBangMouse.Text = "FlashBangMouse"
	FlashBangMouse.TextColor3 = Color3.new(1, 1, 1)
	FlashBangMouse.TextSize = 18
	FlashBangMouse.MouseButton1Click:connect(function()
		if 	Onandoff_36.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_36.BackgroundColor3 = Color3.new(0, 1, 0)

			flashbango = true
			local plr = game.Players.LocalPlayer
			local Mouse = plr:GetMouse()
			local speed = 50
			local debug = true
			local seats = {}


			delay(0, function()
				while flashbango == true do
					pcall(function()
						if game.Workspace.Ignored:FindFirstChild("Grenade")  then
							local lol = game.Workspace.Ignored:FindFirstChild("Grenade")

							if lol:FindFirstChildOfClass("BodyVelocity") then
								wait()
								lol.BodyVelocity:Destroy()
							end

							if lol:FindFirstChild("BodyVelocity") == nil then
								lol.CFrame =  CFrame.new(Mouse.Hit.p);
							end

						elseif game.Workspace.Ignored:FindFirstChild("Handle")  then
							local lol = game.Workspace.Ignored:FindFirstChild("Handle")

							if lol:FindFirstChild("Pin") then
								lol.CFrame =  CFrame.new(Mouse.Hit.p);
							end
						end
					end)
					wait()
				end
			end)
		else
			Onandoff_36.BackgroundColor3 = Color3.new(1, 0, 0)
			flashbango = false

		end
	end)

	Onandoff_36.Name = "Onandoff"
	Onandoff_36.Parent = FlashBangMouse
	Onandoff_36.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_36.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_36.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_36.Size = UDim2.new(0, 135, 0, 15)

	Toolreach.Name = "Toolreach"
	Toolreach.Parent = CombatScrollFrame
	Toolreach.BackgroundColor3 = Color3.new(0, 0, 0)
	Toolreach.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Toolreach.Position = UDim2.new(0.0287184715, 0, 0.697413325, 0)
	Toolreach.Size = UDim2.new(0, 135, 0, 26)
	Toolreach.Font = Enum.Font.SourceSans
	Toolreach.Text = "ToolReach"
	Toolreach.TextColor3 = Color3.new(1, 1, 1)
	Toolreach.TextSize = 18
	Toolreach.MouseButton1Click:connect(function()

		if 	ToolreachSize.Text:match("%d+") then

			local id = ToolreachSize.Text:match("%d+")
			for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren()) do
				if v:isA("Tool") then
					local a = Instance.new("SelectionBox",v.Handle)
					v.Handle.Massless = true
					v.Handle.Transparency = 1
					a.Adornee = v.Handle
					v.Handle.Size = Vector3.new(id, id, id)
					local selectionBox = Instance.new("SelectionBox",v.Handle)
					selectionBox.Adornee = v.Handle

				end
			end
		else

			noti("Please Put A Size In The TextBox")
		end
	end)

	ToolreachSize.Name = "Toolreach Size"
	ToolreachSize.Parent = Toolreach
	ToolreachSize.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	ToolreachSize.BorderColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	ToolreachSize.Position = UDim2.new(0.00740740728, 0, 1, 0)
	ToolreachSize.Size = UDim2.new(0, 133, 0, 15)
	ToolreachSize.Font = Enum.Font.SourceSans
	ToolreachSize.PlaceholderColor3 = Color3.new(1, 1, 1)
	ToolreachSize.PlaceholderText = "Size Here"
	ToolreachSize.Text = ""
	ToolreachSize.TextColor3 = Color3.new(1, 1, 1)
	ToolreachSize.TextSize = 16

	SuperFlash.Name = "SuperFlash"
	SuperFlash.Parent = CombatScrollFrame
	SuperFlash.BackgroundColor3 = Color3.new(0, 0, 0)
	SuperFlash.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	SuperFlash.Position = UDim2.new(0.266734958, 0, 0.695992887, 0)
	SuperFlash.Size = UDim2.new(0, 135, 0, 26)
	SuperFlash.Font = Enum.Font.SourceSans
	SuperFlash.Text = "SuperFlash"
	SuperFlash.TextColor3 = Color3.new(1, 1, 1)
	SuperFlash.TextSize = 18
	SuperFlash.MouseButton1Click:connect(function()
		if 	Onandoff_37.BackgroundColor3 == Color3.new(1, 0, 0) then

			Onandoff_37.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("Please Wait 10 Moments")
			ezflashsueper = true
			local plr = game.Players.LocalPlayer
			local Mouse = plr:GetMouse()
			local tool = Instance.new("Tool")
			local handle = Instance.new("Part", tool)
			tool.Name = "FLASH"
			handle.Name = "Handle"
			handle.Transparency = 1
			for i=1,2 do wait()
				plr.Character.Humanoid:EquipTool(tool)
			end



			local Plr = game.Players.LocalPlayer
			local e = 0
			local p = 0
			local burgercount = 4
			local a = {}
			local radian = math.pi/burgercount
			repeat
				Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["[Flashlight] - $10"].Head.CFrame
				wait(0.5)
				fireclickdetector(game:GetService("Workspace").Ignored.Shop["[Flashlight] - $10"].ClickDetector)
				for i, v in pairs(Plr.Backpack:GetChildren()) do
					if v.Name == "[Flashlight]" 
					then
						e = 0
						for i, v in pairs(a) do
							e = e + 1
						end
						table.insert(a, v)
						v.Parent = Plr.Character
						wait(.30)
						v:Activate();
					end
				end
			until e >= burgercount*8 or ezflashsueper == false
		else
			Onandoff_37.BackgroundColor3 = Color3.new(1, 0, 0)
			ezflashsueper = false
			for _,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
				if (v:IsA("Tool")) then
					v:Destroy()
				end
			end
		end

	end)

	Onandoff_37.Name = "Onandoff"
	Onandoff_37.Parent = SuperFlash
	Onandoff_37.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_37.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_37.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_37.Size = UDim2.new(0, 135, 0, 15)

	MovementScrollFrame.Name = "MovementScrollFrame"
	MovementScrollFrame.Parent = MainChild
	MovementScrollFrame.Active = true
	MovementScrollFrame.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	MovementScrollFrame.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	MovementScrollFrame.Position = UDim2.new(0.247117221, 0, 0.0254765432, 0)
	MovementScrollFrame.Size = UDim2.new(0, 605, 0, 333)
	MovementScrollFrame.Visible = false

	AntiDisplay.Name = "AntiDisplay"
	AntiDisplay.Parent = MovementScrollFrame
	AntiDisplay.BorderColor3 = Color3.new(0, 0, 0)
	AntiDisplay.BackgroundColor3 = Color3.new(0, 0, 0)
	AntiDisplay.Position = UDim2.new(0.266000003, 0, 0.7016747, 0)
	AntiDisplay.Size = UDim2.new(0, 135, 0, 26)
	AntiDisplay.Font = Enum.Font.SourceSans
	AntiDisplay.TextColor3 = Color3.new(1, 1, 1)
	AntiDisplay.TextSize = 18
	AntiDisplay.Text = "AntiDisplayName"
	AntiDisplay.MouseButton1Click:connect(function()
		local j = require(game.Chat:WaitForChild("ClientChatModules").ChatSettings) -----Made by w44rm  / skyhigh#9441
		j.PlayerDisplayNamesEnabled = false -----Made by w44rm  / skyhigh#9441
		for i,v in pairs(game:GetService("Players"):GetPlayers()) do -----Made by w44rm  / skyhigh#9441
			if v:IsA("Player") then -----Made by w44rm  / skyhigh#9441
				local username = v.Name -----Made by w44rm  / skyhigh#9441
				v.DisplayName = username -----Made by w44rm  / skyhigh#9441
				v.Character:FindFirstChildWhichIsA("Humanoid").DisplayName = username -----Made by w44rm  / skyhigh#9441
				v.CharacterAdded:Connect(function(character) -----Made by w44rm  / skyhigh#9441
					while wait(1) do -----Made by w44rm  / skyhigh#9441
						if character == false then -----Made by w44rm  / skyhigh#9441
							break -----Made by w44rm  / skyhigh#9441
						end -----Made by w44rm  / skyhigh#9441
						character:FindFirstChildWhichIsA("Humanoid").DisplayName = v.Name -----Made by w44rm  / skyhigh#9441
					end -----Made by w44rm  / skyhigh#9441
				end) -----Made by w44rm  / skyhigh#9441
			end -----Made by w44rm  / skyhigh#9441
		end -----Made by w44rm  / skyhigh#9441
		game:GetService("Players").PlayerAdded:Connect(function(player) -----Made by w44rm  / skyhigh#9441
			player.DisplayName = player.Name -----Made by w44rm  / skyhigh#9441
			player.CharacterAdded:Connect(function(character) -----Made by w44rm  / skyhigh#9441
				while wait(1) do -----Made by w44rm  / skyhigh#9441
					if character == false then -----Made by w44rm  / skyhigh#9441
						break -----Made by w44rm  / skyhigh#9441
					end -----Made by w44rm  / skyhigh#9441
					character:FindFirstChildWhichIsA("Humanoid").DisplayName = player.Name -----Made by w44rm  / skyhigh#9441
				end -----Made by w44rm  / skyhigh#9441
			end) -----Made by w44rm  / skyhigh#9441
		end) -----Made by w44rm  / skyhigh#9441
	end)

	Onandoff_164.Name = "Onandoff"
	Onandoff_164.Parent = AntiDisplay
	Onandoff_164.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_164.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_164.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_164.Size = UDim2.new(0, 135, 0, 15)


	NoSlowDown.Name = "NoSlowDown"
	NoSlowDown.Parent = MovementScrollFrame
	NoSlowDown.BackgroundColor3 = Color3.new(0, 0, 0)
	NoSlowDown.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	NoSlowDown.Position = UDim2.new(0.031863749, 0, 0.0312201343, 0)
	NoSlowDown.Size = UDim2.new(0, 135, 0, 26)
	NoSlowDown.Font = Enum.Font.SourceSans
	NoSlowDown.Text = "NoSlowDown"
	NoSlowDown.TextColor3 = Color3.new(1, 1, 1)
	NoSlowDown.TextSize = 18
	NoSlowDown.MouseButton1Click:connect(function()
		if Onandoff_38.BackgroundColor3 == Color3.new(1, 0, 0)  then
			Onandoff_38.BackgroundColor3 = Color3.new(0, 1, 0)
			noslowdown = true

			game:GetService("RunService").Heartbeat:Connect(function()
				if noslowdown == true then
					for i, v in pairs(game.Players.LocalPlayer.Character.BodyEffects.Movement:GetChildren()) do
						if v.Name == ("NoJumping") or v.Name == ("ReduceWalk") or v.Name == ("NoWalkSpeed") then
							v:Destroy()
						end
					end
					if game:GetService("Players").LocalPlayer.Character.BodyEffects.Reload.Value == true then
						game:GetService("Players").LocalPlayer.Character.BodyEffects.Reload.Value = false
					end
				end
			end)
		else
			Onandoff_38.BackgroundColor3 = Color3.new(1, 0, 0)
			noslowdown = false


		end

	end)

	Onandoff_38.Name = "Onandoff"
	Onandoff_38.Parent = NoSlowDown
	Onandoff_38.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_38.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_38.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_38.Size = UDim2.new(0, 135, 0, 15)

	NoJumpCoolDown.Name = "NoJumpCoolDown"
	NoJumpCoolDown.Parent = MovementScrollFrame
	NoJumpCoolDown.BackgroundColor3 = Color3.new(0, 0, 0)
	NoJumpCoolDown.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	NoJumpCoolDown.Position = UDim2.new(0.267193943, 0, 0.0309641957, 0)
	NoJumpCoolDown.Size = UDim2.new(0, 135, 0, 26)
	NoJumpCoolDown.Font = Enum.Font.SourceSans
	NoJumpCoolDown.Text = "NoJumpCoolDown"
	NoJumpCoolDown.TextColor3 = Color3.new(1, 1, 1)
	NoJumpCoolDown.TextSize = 18
	NoJumpCoolDown.MouseButton1Click:connect(function()
		if Onandoff_39.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_39.BackgroundColor3 = Color3.new(0, 1, 0)

			game.Players.LocalPlayer.Character.Humanoid.Name = "Humz"
			game.Players.LocalPlayer.Character.Humz.WalkSpeed = 17
		else
			Onandoff_39.BackgroundColor3 = Color3.new(1, 0, 0)
			game.Players.LocalPlayer.Character.Humz.WalkSpeed = 16
			demspeed = 50
			game.Players.LocalPlayer.Character.Humz.Name = "Humanoid"
		end
	end)

	Onandoff_39.Name = "Onandoff"
	Onandoff_39.Parent = NoJumpCoolDown
	Onandoff_39.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_39.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_39.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_39.Size = UDim2.new(0, 135, 0, 15)

	Fly.Name = "Fly"
	Fly.Parent = MovementScrollFrame
	Fly.BackgroundColor3 = Color3.new(0, 0, 0)
	Fly.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Fly.Position = UDim2.new(0.503098488, 0, 0.0312201343, 0)
	Fly.Size = UDim2.new(0, 135, 0, 26)
	Fly.Font = Enum.Font.SourceSans
	Fly.Text = "Fly"
	Fly.TextColor3 = Color3.new(1, 1, 1)
	Fly.TextSize = 18
	Fly.MouseButton1Click:connect(function()
		maus = game.Players.LocalPlayer:GetMouse()
		maus.KeyDown:Connect(function(key)

			if key == "x" then
				if flying == false  then
					flying = true


					local plr = game.Players.LocalPlayer
					local mouse = plr:GetMouse()

					localplayer = plr

					if workspace:FindFirstChild("Core") then
						workspace.Core:Destroy()
					end

					local Core = Instance.new("Part")
					Core.Name = "Core"
					Core.Size = Vector3.new(0.05, 0.05, 0.05)
					local hum = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
					spawn(function()
						Core.Parent = workspace
						local Weld = Instance.new("Weld", Core)
						Weld.Part0 = Core
						Weld.Part1 = localplayer.Character.LowerTorso
						Weld.C0 = CFrame.new(0, 0, 0)
					end)

					workspace:WaitForChild("Core")

					local torso = workspace.Core

					local speed=100
					local keys={a=false,d=false,w=false,s=false}
					local e1
					local e2
					local function start()
						local pos = Instance.new("BodyPosition",torso)
						local gyro = Instance.new("BodyGyro",torso)
						pos.Name="EPIXPOS"
						pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)
						pos.position = torso.Position
						gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
						gyro.cframe = torso.CFrame
						repeat
							wait()
							hum.PlatformStand=true
							local new=gyro.cframe - gyro.cframe.p + pos.position
							if not keys.w and not keys.s and not keys.a and not keys.d then
								speed=10
							end
							if keys.w then
								new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed
								speed=speed+0
							end
							if keys.s then
								new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed
								speed=speed+0
							end
							if keys.d then
								new = new * CFrame.new(speed,0,0)
								speed=speed+0
							end
							if keys.a then
								new = new * CFrame.new(-speed,0,0)
								speed=speed+0
							end
							if speed>100 then
								speed=100
							end
							pos.position=new.p
							if keys.w then
								gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(speed*0),0,0)
							elseif keys.s then
								gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*0),0,0)
							else
								gyro.cframe = workspace.CurrentCamera.CoordinateFrame
							end
						until flying == false
						if gyro then gyro:Destroy() end
						if pos then pos:Destroy() end
						flying=false
						hum.PlatformStand=false
						speed=100
					end
					e1=mouse.KeyDown:connect(function(key)
						if not torso or not torso.Parent then flying=false e1:disconnect() e2:disconnect() return end
						if key=="w" then
							keys.w=true
						elseif key=="s" then
							keys.s=true
						elseif key=="a" then
							keys.a=true
						elseif key=="d" then
							keys.d=true

						end
					end)
					e2=mouse.KeyUp:connect(function(key)
						if key=="w" then
							keys.w=false
						elseif key=="s" then
							keys.s=false
						elseif key=="a" then
							keys.a=false
						elseif key=="d" then
							keys.d=false
						end
					end)

					start()

				else
					if workspace:FindFirstChild("Core") then
						workspace.Core:Destroy()
					end
					flying = false

				end

			end



		end)
	end)

	Onandoff_40.Name = "Onandoff"
	Onandoff_40.Parent = Fly
	Onandoff_40.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_40.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_40.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_40.Size = UDim2.new(0, 135, 0, 15)
	
	Godblock.Name = "Godblock"
	Godblock.Parent = MovementScrollFrame
	Godblock.BackgroundColor3 = Color3.new(0, 0, 0)
	Godblock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Godblock.Position = UDim2.new(0.739462137, 0, 0.0312201343, 0)
	Godblock.Size = UDim2.new(0, 135, 0, 26)
	Godblock.Font = Enum.Font.SourceSans
	Godblock.Text = "GodBlock"
	Godblock.TextColor3 = Color3.new(1, 1, 1)
	Godblock.TextSize = 18
	Godblock.MouseButton1Click:connect(function()
		game.Players.LocalPlayer.Character.Humanoid.Health = 0
		function Unban()
			repeat wait() until game.Players.LocalPlayer.Character:FindFirstChild("BodyEffects")

			 loaded = Instance.new("Folder")
			loaded.Name = "FULLY_LOADED_CHAR"
			loaded.Parent = game.Players.LocalPlayer.Character
			game.Players.LocalPlayer.Character.BodyEffects.Dead:Destroy()
			game:GetService("Players").LocalPlayer.PlayerGui.MainScreenGui.TimerJail:Destroy()
wait(2)
			gsPlayers = game:GetService("Players")
			gsWorkspace = game:GetService("Workspace")
			gsLighting = game:GetService("Lighting")
			gsReplicatedStorage = game:GetService("ReplicatedStorage")
			gsCoreGui = game:GetService("CoreGui")
			gsTween = game:GetService("TweenService")
			gsHttp = game:GetService("HttpService")
			LP = gsPlayers.LocalPlayer
			Mouse = LP:GetMouse()
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

		end
		wait(5.3)
		game.Players.LocalPlayer.CharacterAdded:Connect(function()Unban()end)Unban()

	end)

	Onandoff_41.Name = "Onandoff"
	Onandoff_41.Parent = Godblock
	Onandoff_41.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_41.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_41.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_41.Size = UDim2.new(0, 135, 0, 15)

	Tools.Name = "Tools"
	Tools.Parent = MovementScrollFrame
	Tools.BackgroundColor3 = Color3.new(0, 0, 0)
	Tools.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Tools.Position = UDim2.new(0.031863749, 0, 0.10366331, 0)
	Tools.Size = UDim2.new(0, 135, 0, 26)
	Tools.Font = Enum.Font.SourceSans
	Tools.Text = "Tools"
	Tools.TextColor3 = Color3.new(1, 1, 1)
	Tools.TextSize = 18
	Tools.MouseButton1Click:connect(function()
		flying = false
		char = game:GetService('Players').LocalPlayer.Character
		-------------------------------------
		function GetKnife()
			wait(.1)
			char.HumanoidRootPart.CFrame = CFrame.new(-680.2, 19.75, -254.97)
			char.HumanoidRootPart.CFrame = CFrame.new(-680.2, 19.75, -254.97)
			wait()
			char.HumanoidRootPart.CFrame = CFrame.new(-115.495, 19.756, -453.45)
			char.HumanoidRootPart.CFrame = CFrame.new(-115.495, 19.756, -453.45)
			wait()
			char.HumanoidRootPart.CFrame = CFrame.new(-418.208, 19.25, -748.694)
			char.HumanoidRootPart.CFrame = CFrame.new(-418.208, 19.25, -748.694)
			wait()
			char.HumanoidRootPart.CFrame = CFrame.new(-418.208, 19.25, -748.694)
			char.HumanoidRootPart.CFrame = CFrame.new(-418.208, 19.25, -748.694)
			wait()
			char.HumanoidRootPart.CFrame = CFrame.new(33, 19.75, -184.6)
			char.HumanoidRootPart.CFrame = CFrame.new(33, 19.75, -184.6)
			wait()
			char.HumanoidRootPart.CFrame = CFrame.new(243.495, 62, -450.5)
			char.HumanoidRootPart.CFrame = CFrame.new(243.495, 62, -450.5)
			wait()
			char.HumanoidRootPart.CFrame = CFrame.new(-103.53, 19.75, -220.21)
			char.HumanoidRootPart.CFrame = CFrame.new(-103.53, 19.75, -220.21)
			wait()
			char.HumanoidRootPart.CFrame = CFrame.new(-581.775, 19.7549, -485.23)
			char.HumanoidRootPart.CFrame = CFrame.new(-581.775, 19.7549, -485.23)
			wait()
			char.HumanoidRootPart.CFrame = CFrame.new(-399.655, 19.7552, -461.55)
			char.HumanoidRootPart.CFrame = CFrame.new(-399.655, 19.7552, -461.55)
			wait()
		end

		wait()
		local X = char.HumanoidRootPart.CFrame.X
		local Y = char.HumanoidRootPart.CFrame.Y
		local Z = char.HumanoidRootPart.CFrame.Z
		GetKnife()
		repeat GetKnife() until plr.Backpack:FindFirstChild('[Knife]') and plr.Backpack:FindFirstChild('[LockPicker]')
		char.HumanoidRootPart.CFrame = CFrame.new(X,Y+5,Z)
	end)

	Onandoff_42.Name = "Onandoff"
	Onandoff_42.Parent = Tools
	Onandoff_42.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_42.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_42.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_42.Size = UDim2.new(0, 135, 0, 15)

	Stick.Name = "Stick"
	Stick.Parent = MovementScrollFrame
	Stick.BackgroundColor3 = Color3.new(0, 0, 0)
	Stick.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Stick.Position = UDim2.new(0.267193943, 0, 0.103407376, 0)
	Stick.Size = UDim2.new(0, 135, 0, 26)
	Stick.Font = Enum.Font.SourceSans
	Stick.Text = "Stick"
	Stick.TextColor3 = Color3.new(1, 1, 1)
	Stick.TextSize = 18
	Stick.MouseButton1Click:connect(function()
		if Onandoff_43.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_43.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("Stick Enabled")
			local spinSpeed = 0
			local speaker = game.Players.LocalPlayer
			for i,v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
				if v.Name == "Spinning" then
					v:Destroy()
				end
			end
			local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
			Spin.Name = "Spinning"
			Spin.MaxTorque = Vector3.new(0, math.huge, 0)
			Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)
			spinknife.TextColor3 = Color3.new(1, 1, 1)


		else
			noti("Stick Disabled")
			Onandoff_43.BackgroundColor3 = Color3.new(1, 0, 0)
			local spinSpeed = 0
			local speaker = game.Players.LocalPlayer
			for i,v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
				if v.Name == "Spinning" then
					v:Destroy()
				end
			end
			local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
			Spin.Name = "Spinning"
			Spin.MaxTorque = Vector3.new(0, math.huge, 0)
			Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)
			Spin:Destroy()
		end
	end)

	Onandoff_43.Name = "Onandoff"
	Onandoff_43.Parent = Stick
	Onandoff_43.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_43.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_43.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_43.Size = UDim2.new(0, 135, 0, 15)

	AutoStomp.Name = "AutoStomp"
	AutoStomp.Parent = MovementScrollFrame
	AutoStomp.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoStomp.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoStomp.Position = UDim2.new(0.503098488, 0, 0.10366331, 0)
	AutoStomp.Size = UDim2.new(0, 135, 0, 26)
	AutoStomp.Font = Enum.Font.SourceSans
	AutoStomp.Text = "AutoStomp"
	AutoStomp.TextColor3 = Color3.new(1, 1, 1)
	AutoStomp.TextSize = 18
	AutoStomp.MouseButton1Click:connect(function()
		if Onandoff_44.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_44.BackgroundColor3 = Color3.new(0, 1, 0)

			stompyz = true
			noti("AutoStomp Enabled")
			repeat
				game.ReplicatedStorage.MainEvent:FireServer("Stomp")
				wait()
			until stompyz == false
		else
			Onandoff_44.BackgroundColor3 = Color3.new(1, 0, 0)
			noti("AutoStomp Disabled")
			stompyz = false
		end
	end)

	Onandoff_44.Name = "Onandoff"
	Onandoff_44.Parent = AutoStomp
	Onandoff_44.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_44.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_44.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_44.Size = UDim2.new(0, 135, 0, 15)

	Reset.Name = "Reset"
	Reset.Parent = MovementScrollFrame
	Reset.BackgroundColor3 = Color3.new(0, 0, 0)
	Reset.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Reset.Position = UDim2.new(0.739462137, 0, 0.10366331, 0)
	Reset.Size = UDim2.new(0, 135, 0, 26)
	Reset.Font = Enum.Font.SourceSans
	Reset.Text = "Reset"
	Reset.TextColor3 = Color3.new(1, 1, 1)
	Reset.TextSize = 18
	Reset.MouseButton1Click:connect(function()
		game.Players.LocalPlayer.Character.Head:Destroy()
	end)


	Onandoff_45.Name = "Onandoff"
	Onandoff_45.Parent = Reset
	Onandoff_45.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_45.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_45.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_45.Size = UDim2.new(0, 135, 0, 15)

	DropAccessory.Name = "DropAccessory"
	DropAccessory.Parent = MovementScrollFrame
	DropAccessory.BackgroundColor3 = Color3.new(0, 0, 0)
	DropAccessory.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	DropAccessory.Position = UDim2.new(0.266734838, 0, 0.177526951, 0)
	DropAccessory.Size = UDim2.new(0, 135, 0, 26)
	DropAccessory.Font = Enum.Font.SourceSans
	DropAccessory.Text = "DropAccessory"
	DropAccessory.TextColor3 = Color3.new(1, 1, 1)
	DropAccessory.TextSize = 18
	DropAccessory.MouseButton1Click:connect(function()
		local Player = game:GetService("Players").LocalPlayer
		local Players = game:GetService("Players")
		local HatList = {}
		local i = 0
		plr = game.Players.LocalPlayer
		for _,l in pairs(Player.Character:GetChildren()) do
			if l:IsA("Accessory") then if i>0 then l.Parent = workspace  end i = i + 1 end;
		end
		wait(.1)

		wait(3)
		local AncientPOS = plr.Character.HumanoidRootPart.Position
		wait()
		game.Players.LocalPlayer.Character.Humanoid.Health = 0
		wait(7)
		plr.Character.HumanoidRootPart.CFrame = CFrame.new(AncientPOS)
		plr.Character.HumanoidRootPart.CFrame = CFrame.new(AncientPOS)	
	end)

	Onandoff_46.Name = "Onandoff"
	Onandoff_46.Parent = DropAccessory
	Onandoff_46.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_46.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_46.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_46.Size = UDim2.new(0, 135, 0, 15)

	BackFlip.Name = "BackFlip"
	BackFlip.Parent = MovementScrollFrame
	BackFlip.BackgroundColor3 = Color3.new(0, 0, 0)
	BackFlip.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	BackFlip.Position = UDim2.new(0.031863749, 0, 0.177526951, 0)
	BackFlip.Size = UDim2.new(0, 135, 0, 26)
	BackFlip.Font = Enum.Font.SourceSans
	BackFlip.Text = "BackFlip"
	BackFlip.TextColor3 = Color3.new(1, 1, 1)
	BackFlip.TextSize = 18
	BackFlip.MouseButton1Click:connect(function()


		local ca = game:GetService("ContextActionService")
		local zeezy = game:GetService("Players").LocalPlayer
		local h = 0.0174533
		local antigrav


		--[[ Functions ]]--


		zeezy.Character.Humanoid:ChangeState("Jumping")
		wait()
		zeezy.Character.Humanoid.Sit = true
		for i = 1,360 do 
			delay(i/720,function()
				zeezy.Character.Humanoid.Sit = true
				zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(-h,0,0)
			end)
		end
		wait(0.55)
		zeezy.Character.Humanoid.Sit = false

	end)



	Onandoff_47.Name = "Onandoff"
	Onandoff_47.Parent = BackFlip
	Onandoff_47.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_47.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_47.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_47.Size = UDim2.new(0, 135, 0, 15)

	DropHead.Name = "DropHead"
	DropHead.Parent = MovementScrollFrame
	DropHead.BackgroundColor3 = Color3.new(0, 0, 0)
	DropHead.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	DropHead.Position = UDim2.new(0.503098488, 0, 0.177526951, 0)
	DropHead.Size = UDim2.new(0, 135, 0, 26)
	DropHead.Font = Enum.Font.SourceSans
	DropHead.Text = "DropHead"
	DropHead.TextColor3 = Color3.new(1, 1, 1)
	DropHead.TextSize = 18
	DropHead.MouseButton1Click:connect(function()
		if Onandoff_48.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_48.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("Click Again!")
			game.Players.LocalPlayer.Character.Head.Neck:Destroy()
			game.Players.LocalPlayer.Character.UpperTorso.NeckAttachment:Destroy()
			game.Players.LocalPlayer.Character.Head.Size = Vector3.new(0,0,0)
			game.Players.LocalPlayer.Character.Head.Massless = true
			game.Players.LocalPlayer.Character.Head.CanCollide = true

			heazd1 = true

			repeat
				pcall(function()  
					game.Players.LocalPlayer.Character.Head.NeckRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
					game.Players.LocalPlayer.Character.UpperTorso.NeckRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
					game.Players.LocalPlayer.Character.Head.CFrame = CFrame.new(0, 100000.4736328125, 0)
				end)
				wait()
			until heazd1 == false


		else

			noti("Successfuly HeadDropped")
			Onandoff_48.BackgroundColor3 = Color3.new(1, 0, 0)
			heazd1 = false
			local lol = game.Players.LocalPlayer.Character.HumanoidRootPart
			for i = 1, 10 do
				game.Players.LocalPlayer.Character.Head.CFrame = lol.CFrame
				wait(0.05)

			end

		end
	end)

	Onandoff_48.Name = "Onandoff"
	Onandoff_48.Parent = DropHead
	Onandoff_48.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_48.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_48.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_48.Size = UDim2.new(0, 135, 0, 15)

	NoClip.Name = "NoClip"
	NoClip.Parent = MovementScrollFrame
	NoClip.BackgroundColor3 = Color3.new(0, 0, 0)
	NoClip.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	NoClip.Position = UDim2.new(0.739462137, 0, 0.177526951, 0)
	NoClip.Size = UDim2.new(0, 135, 0, 26)
	NoClip.Font = Enum.Font.SourceSans
	NoClip.Text = "NoClip"
	NoClip.TextColor3 = Color3.new(1, 1, 1)
	NoClip.TextSize = 18
	NoClip.MouseButton1Click:connect(function()
		game:GetService('RunService').Stepped:connect(function()
			if noclip then
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			end
		end)		
		if Onandoff_49.BackgroundColor3 == Color3.new(1, 0, 0) 	then
			Onandoff_49.BackgroundColor3 = Color3.new(0, 1, 0)
			noclip = not noclip
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		else
			Onandoff_49.BackgroundColor3 = Color3.new(1, 0, 0)
			noclip = false
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)

		end
	end)

	Onandoff_49.Name = "Onandoff"
	Onandoff_49.Parent = NoClip
	Onandoff_49.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_49.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_49.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_49.Size = UDim2.new(0, 135, 0, 15)

	Anonymous.Name = "Anonymous"
	Anonymous.Parent = MovementScrollFrame
	Anonymous.BackgroundColor3 = Color3.new(0, 0, 0)
	Anonymous.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Anonymous.Position = UDim2.new(0.0303712487, 0, 0.248549655, 0)
	Anonymous.Size = UDim2.new(0, 135, 0, 26)
	Anonymous.Font = Enum.Font.SourceSans
	Anonymous.Text = "Anonymous"
	Anonymous.TextColor3 = Color3.new(1, 1, 1)
	Anonymous.TextSize = 18
	Anonymous.MouseButton1Click:connect(function()

		pcall(function()
			game.Players.LocalPlayer.Character.Shirt:Destroy()
			game.Players.LocalPlayer.Character.RightUpperLeg:Destroy()
			game.Players.LocalPlayer.Character.Humanoid.HealthDisplayDistance = math.huge
			game.Players.LocalPlayer.Character.Humanoid.NameDisplayDistance = math.huge
			game.Players.LocalPlayer.Character.RightUpperLeg.Size = Vector3.new(0,0,0)
			game.Players.LocalPlayer.Character.RightUpperLeg.Massless = true
			game.Players.LocalPlayer.Character.RightUpperLeg.CanCollide = false

			heazd = true

			while heazd == true do 
				pcall(function()  
					game.Players.LocalPlayer.Character.RightUpperLeg.RightHipRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
					game.Players.LocalPlayer.Character.RightUpperLeg.CFrame = CFrame.new(0, 100000.4736328125, 0)
				end)
				wait()
			end
		end)
		wait(0.10)
		pcall(function()
			game.Players.LocalPlayer.Character.LeftUpperLeg:Destroy()
			game.Players.LocalPlayer.Character.Pants:Destroy()
			game.Players.LocalPlayer.Character.Humanoid.HealthDisplayDistance = math.huge
			game.Players.LocalPlayer.Character.Humanoid.NameDisplayDistance = math.huge
			game.Players.LocalPlayer.Character.LeftUpperLeg.Size = Vector3.new(0,0,0)
			game.Players.LocalPlayer.Character.LeftUpperLeg.Massless = true
			game.Players.LocalPlayer.Character.LeftUpperLeg.CanCollide = false

			heazd = true

			while heazd == true do 
				pcall(function()  
					game.Players.LocalPlayer.Character.LeftUpperLeg.LeftHipRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
					game.Players.LocalPlayer.Character.LeftUpperLeg.CFrame = CFrame.new(0, 100000.4736328125, 0)
				end)
				wait()
			end
		end)
		wait(0.10)
		pcall(function()
			game.Players.LocalPlayer.Character.Head.Neck:Destroy()
			game.Players.LocalPlayer.Character.UpperTorso.NeckAttachment:Destroy()
			game.Players.LocalPlayer.Character.Humanoid.HealthDisplayDistance = math.huge
			game.Players.LocalPlayer.Character.Humanoid.NameDisplayDistance = math.huge
			game.Players.LocalPlayer.Character.Head.Size = Vector3.new(0,0,0)
			game.Players.LocalPlayer.Character.Head.Massless = true
			game.Players.LocalPlayer.Character.Head.CanCollide = false

			heazd = true

			while heazd == true do 
				pcall(function()  
					game.Players.LocalPlayer.Character.Head.NeckRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
					game.Players.LocalPlayer.Character.UpperTorso.NeckRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
					game.Players.LocalPlayer.Character.Head.CFrame = CFrame.new(0, 100000.4736328125, 0)
				end)
				wait()
			end
		end)
	end)

	Onandoff_50.Name = "Onandoff"
	Onandoff_50.Parent = Anonymous
	Onandoff_50.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_50.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_50.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_50.Size = UDim2.new(0, 135, 0, 15)

	Sing.Name = "Sing"
	Sing.Parent = MovementScrollFrame
	Sing.BackgroundColor3 = Color3.new(0, 0, 0)
	Sing.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Sing.Position = UDim2.new(0.266734898, 0, 0.248549655, 0)
	Sing.Size = UDim2.new(0, 135, 0, 26)
	Sing.Font = Enum.Font.SourceSans
	Sing.Text = "Sing"
	Sing.TextColor3 = Color3.new(1, 1, 1)
	Sing.TextSize = 18
	Sing.MouseButton1Click:connect(function()
		local notifSound = Instance.new("Sound",workspace)
		notifSound.PlaybackSpeed = 1
		notifSound.Volume = 1
		notifSound.SoundId = "rbxassetid://185529776"
		notifSound.PlayOnRemove = true
		wait(1)
		local A_1 = "It's raining tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(3)
		local A_1 = "From out of the sky" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(3.20)
		local A_1 = "Tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(3)
		local A_1 = "No need to ask why" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(3)
		local A_1 = "Just open your mouth and close your eyes" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(3)
		local A_1 = "It's raining tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(5)
		local A_1 = "Out in the street" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "All you can eat" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Lettuce and shells" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Cheese and meat" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "It's raining tacos!!!!!!!!!!!!!!!!!!!!!!!" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Yum, yum, yum, yum, yumidy yum" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(3)
		local A_1 = "It's Like A dream" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(3.20)
		local A_1 = "Yum, yum, yum, yum, yumidy yum" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(3)
		local A_1 = "Bring your sour cream" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(11)
		local A_1 = "Shell" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Meat" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Lettuce" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Cheese" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Shell" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Meat" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Lettuce" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Cheese" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Shell" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(1)
		local A_1 = "Meat" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Cheese, cheese, cheese, cheese, cheese" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "It's raining tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "OOOOOO" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Raining tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "OOOOOO" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Raining tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "It's raining tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "OOOOOO" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "It's raining tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "OOOOOOO" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Raining tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "OOOOOOO" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "Raining tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "OOOOOOO" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "It's raining tacos" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "OOOOOOO" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
		wait(2)
		local A_1 = "It's raining tacos......" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	end)

	Onandoff_51.Name = "Onandoff"
	Onandoff_51.Parent = Sing
	Onandoff_51.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_51.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_51.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_51.Size = UDim2.new(0, 135, 0, 15)

	SilentAim.Name = "SilentAim"
	SilentAim.Parent = MovementScrollFrame
	SilentAim.BackgroundColor3 = Color3.new(0, 0, 0)
	SilentAim.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	SilentAim.Position = UDim2.new(0.501445651, 0, 0.248549655, 0)
	SilentAim.Size = UDim2.new(0, 135, 0, 26)
	SilentAim.Font = Enum.Font.SourceSans
	SilentAim.Text = "SilentAim"
	SilentAim.TextColor3 = Color3.new(1, 1, 1)
	SilentAim.TextSize = 18
	SilentAim.MouseButton1Click:connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/kPUXW9uy"))()

	end)

	Onandoff_52.Name = "Onandoff"
	Onandoff_52.Parent = SilentAim
	Onandoff_52.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
	Onandoff_52.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_52.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_52.Size = UDim2.new(0, 135, 0, 15)

	FullGodmode.Name = "FullGodmode"
	FullGodmode.Parent = MovementScrollFrame
	FullGodmode.BackgroundColor3 = Color3.new(0, 0, 0)
	FullGodmode.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FullGodmode.Position = UDim2.new(0.739301741, 0, 0.24854967, 0)
	FullGodmode.Size = UDim2.new(0, 135, 0, 26)
	FullGodmode.Font = Enum.Font.SourceSans
	FullGodmode.Text = "FullGodmode"
	FullGodmode.TextColor3 = Color3.new(1, 1, 1)
	FullGodmode.TextSize = 18
	FullGodmode.MouseButton1Click:connect(function()

		if Onandoff_53.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_53.BackgroundColor3 = Color3.new(0, 1, 0)
			sfull = true

			game.Players.LocalPlayer.Character.Humanoid.Health = 0
			function Unban()
				repeat wait() until game.Players.LocalPlayer.Character:FindFirstChild("BodyEffects") and game.Players.LocalPlayer.Character.BodyEffects:FindFirstChild("SpecialParts") and not game.Players.LocalPlayer.Character:FindFirstChild("ForceField_TESTING")
				local loaded = Instance.new("Folder")
				loaded.Name = "FULLY_LOADED_CHAR"
				loaded.Parent = game.Players.LocalPlayer.Character
				game.Players.LocalPlayer.Character.BodyEffects.Dead:Destroy()
				game:GetService("Players").LocalPlayer.PlayerGui.MainScreenGui.TimerJail:Destroy()
				
				wait()

				local loaded = Instance.new("Folder")
				loaded.Name = "FULLY_LOADED_CHAR"
				loaded.Parent = game.Players.LocalPlayer.Character
				game.Players.LocalPlayer.Character.BodyEffects.BreakingParts:Destroy()

			end
			wait(5.3)
			game.Players.LocalPlayer.CharacterAdded:Connect(function()Unban()end)Unban()





		else
			Onandoff_53.BackgroundColor3 = Color3.new(1, 0, 0)
			sfull = false
			local plr = game.Players.LocalPlayer
			ded =	game.Players.LocalPlayer.Character.Head
			ded:Destroy()
			wait(5.3)
			game.Players.LocalPlayer.Character.BodyEffects.Dead.Parent = game.Players.LocalPlayer
			game.Players.LocalPlayer.Character.BodyEffects.BreakingParts.Parent = game.Players.LocalPlayer
			wait(7)

			plr.Character.HumanoidRootPart.CFrame = CFrame.new(AncientPOS)
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(AncientPOS)	
		end
	end)

	Onandoff_53.Name = "Onandoff"
	Onandoff_53.Parent = FullGodmode
	Onandoff_53.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_53.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_53.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_53.Size = UDim2.new(0, 135, 0, 15)

	Zoom.Name = "Zoom"
	Zoom.Parent = MovementScrollFrame
	Zoom.BackgroundColor3 = Color3.new(0, 0, 0)
	Zoom.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Zoom.Position = UDim2.new(0.0303712785, 0, 0.320992827, 0)
	Zoom.Size = UDim2.new(0, 135, 0, 26)
	Zoom.Font = Enum.Font.SourceSans
	Zoom.Text = "Zoom"
	Zoom.TextColor3 = Color3.new(1, 1, 1)
	Zoom.TextSize = 18
	Zoom.MouseButton1Click:connect(function()
		if Onandoff_54.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_54.BackgroundColor3 = Color3.new(0, 1, 0)

			game.Players.LocalPlayer.CameraMaxZoomDistance = (1000)
		else
			Onandoff_54.BackgroundColor3 = Color3.new(1, 0, 0)

			game.Players.LocalPlayer.CameraMaxZoomDistance = (21)

		end
	end)

	Onandoff_54.Name = "Onandoff"
	Onandoff_54.Parent = Zoom
	Onandoff_54.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_54.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_54.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_54.Size = UDim2.new(0, 135, 0, 15)

	Crash.Name = "Crash"
	Crash.Parent = MovementScrollFrame
	Crash.BackgroundColor3 = Color3.new(0, 0, 0)
	Crash.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Crash.Position = UDim2.new(0.266574472, 0, 0.319572389, 0)
	Crash.Size = UDim2.new(0, 135, 0, 26)
	Crash.Font = Enum.Font.SourceSans
	Crash.Text = "Crash"
	Crash.TextColor3 = Color3.new(1, 1, 1)
	Crash.TextSize = 18
	Crash.MouseButton1Click:connect(function()

	end)

	Onandoff_55.Name = "Onandoff"
	Onandoff_55.Parent = Crash
	Onandoff_55.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_55.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_55.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_55.Size = UDim2.new(0, 135, 0, 15)

	FirstPerson.Name = "FirstPerson"
	FirstPerson.Parent = MovementScrollFrame
	FirstPerson.BackgroundColor3 = Color3.new(0, 0, 0)
	FirstPerson.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FirstPerson.Position = UDim2.new(0.501285195, 0, 0.319572389, 0)
	FirstPerson.Size = UDim2.new(0, 135, 0, 26)
	FirstPerson.Font = Enum.Font.SourceSans
	FirstPerson.Text = "FirstPerson"
	FirstPerson.TextColor3 = Color3.new(1, 1, 1)
	FirstPerson.TextSize = 18
	FirstPerson.MouseButton1Click:connect(function()
		noti("Press [N]")
		-- Decompiled with the Synapse X Luau decompiler.

		local l__ContextActionService__1 = game:GetService("ContextActionService");
		local l__LocalPlayer__2 = game:GetService("Players").LocalPlayer;
		local l__CurrentCamera__3 = game:GetService("Workspace").CurrentCamera;
		local v4 = l__LocalPlayer__2.Character or l__LocalPlayer__2.CharacterAdded:Wait();
		local l__Humanoid__5 = v4:WaitForChild("Humanoid");
		local l__RunService__1 = game:GetService("RunService");
		local function v6(p1)
			if p1 then
				local v7, v8 = pcall(function()
					l__RunService__1:UnbindFromRenderStep(p1);
				end);
			end;
		end;
		v6("FirstPersonCamera");
		l__CurrentCamera__3.CameraType = Enum.CameraType.Custom;
		l__CurrentCamera__3.CameraSubject = l__Humanoid__5;
		l__CurrentCamera__3.FieldOfView = 70;
		local u2 = false;
		local u3 = nil;
		local u4 = {};
		local function u5(p2)
			if not p2 then
				return nil;
			end;
			local v9, v10, v11 = p2:ToEulerAnglesXYZ();
			return CFrame.Angles(v9, v10, v11);
		end;
		l__ContextActionService__1:BindAction("FirstPersonToggle", function(p3, p4, p5)
			if p4 == Enum.UserInputState.Begin then
				if u2 then
					v6("FirstPersonCamera");
					l__CurrentCamera__3.CFrame = u3;
					l__CurrentCamera__3.CameraType = Enum.CameraType.Custom;
					l__CurrentCamera__3.CameraSubject = l__Humanoid__5;
					l__CurrentCamera__3.FieldOfView = 70;
					local l__Head__12 = v4:FindFirstChild("Head");
					if l__Head__12 then
						l__Head__12.Transparency = u4[l__Head__12.Name] and 0;
					end;
					for v13, v14 in pairs(v4:GetChildren()) do
						if v14:IsA("Accoutrement") then
							local l__Handle__15 = v14:FindFirstChild("Handle");
							if l__Handle__15 then
								l__Handle__15.Transparency = u4[v14.Name] and 0;
							end;
						end;
					end;
				else
					local l__Head__16 = v4:FindFirstChild("Head");
					if l__Head__16 then
						u3 = u5(l__CurrentCamera__3.CFrame);
						l__CurrentCamera__3.CameraType = Enum.CameraType.Scriptable;
						l__CurrentCamera__3.CameraSubject = l__Head__16;
						l__CurrentCamera__3.FieldOfView = 90;
						u4[l__Head__16.Name] = l__Head__16.Transparency;
						l__Head__16.Transparency = 1;
						for v17, v18 in pairs(v4:GetChildren()) do
							if v18:IsA("Accoutrement") then
								local l__Handle__19 = v18:FindFirstChild("Handle");
								if l__Handle__19 then
									u4[v18.Name] = l__Handle__19.Transparency;
									l__Handle__19.Transparency = 1;
								end;
							end;
						end;
						l__RunService__1:BindToRenderStep("FirstPersonCamera", Enum.RenderPriority.Camera.Value - 1, function()
							if not v4:FindFirstChild("Head") then
								v6("FirstPersonCamera");
								return;
							end;
							local v20 = l__Head__16.CFrame * CFrame.new(0, 0.25, -(l__Head__16.Size.Z / 2 - 0.15));
							l__CurrentCamera__3.CFrame = v20;
							print(v20.X, v20.Y, v20.Z);
						end);
					else
						warn("head does not exist");
					end;
				end;
				u2 = not u2;
			end;
		end, true, Enum.KeyCode.N, Enum.KeyCode.ButtonL3);
		l__ContextActionService__1:SetTitle("FirstPersonToggle", "FP");

	end)

	Onandoff_56.Name = "Onandoff"
	Onandoff_56.Parent = FirstPerson
	Onandoff_56.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_56.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_56.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_56.Size = UDim2.new(0, 135, 0, 15)

	Freecam.Name = "Freecam"
	Freecam.Parent = MovementScrollFrame
	Freecam.BackgroundColor3 = Color3.new(0, 0, 0)
	Freecam.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Freecam.Position = UDim2.new(0.739301741, 0, 0.320992857, 0)
	Freecam.Size = UDim2.new(0, 135, 0, 26)
	Freecam.Font = Enum.Font.SourceSans
	Freecam.Text = "FreeCam"
	Freecam.TextColor3 = Color3.new(1, 1, 1)
	Freecam.TextSize = 18
	Freecam.MouseButton1Click:connect(function()

		noti("Press [T]")
		local allowspeedmove = true
		wait(1)

		local c = workspace.CurrentCamera
		local player = game.Players.LocalPlayer
		local userInput = game:GetService("UserInputService")
		local rs = game:GetService("RunService")
		local starterPlayer = game:GetService("StarterPlayer")
		--local util = LoadLibrary("RbxUtility")
		--local camSync = util.CreateSignal()

		local selected = false
		local speed = 60
		local lastUpdate = 0

		local camera = Instance.new('Part', workspace)
		camera.CanCollide = false
		camera.Anchored = true
		camera.Transparency = 1
		camera.Name = 'FreeCam'
		camera.Position = player.Character.HumanoidRootPart.Position + Vector3.new(0,5,0)
		--rs:BindToRenderStep("CamSync",190,function ()
		--	camSync:fire()
		--end)

		c.Changed:connect(function (property)
			if property == "CoordinateFrame" then
				--		camSync:fire()
			end
		end)

		function getNextMovement(deltaTime)
			local nextMove = Vector3.new()
			-- Left/Right
			if userInput:IsKeyDown("A") or userInput:IsKeyDown("Left") then
				nextMove = nextMove + Vector3.new(-1,0,0)
			end
			if userInput:IsKeyDown("D") or userInput:IsKeyDown("Right") then
				nextMove = nextMove + Vector3.new(1,0,0)
			end
			-- Forward/Back
			if userInput:IsKeyDown("W") or userInput:IsKeyDown("Up") then
				nextMove = nextMove + Vector3.new(0,0,-1)
			end
			if userInput:IsKeyDown("S") or userInput:IsKeyDown("Down") then
				nextMove = nextMove + Vector3.new(0,0,1)
			end
			-- Up/Down
			if userInput:IsKeyDown("Space") or userInput:IsKeyDown("Q") then
				nextMove = nextMove + Vector3.new(0,1,0)
			end
			if userInput:IsKeyDown("LeftControl") or userInput:IsKeyDown("E") then
				nextMove = nextMove + Vector3.new(0,-1,0)
			end
			return CFrame.new( nextMove * (speed * deltaTime) )
		end

		function onSelected()
			local char = player.Character
			if char then
				local root = camera
				currentPos = root.Position
				selected = true
				lastUpdate = tick()
				c.CameraSubject = root
				player.Character.HumanoidRootPart.Anchored = true
				while selected do
					local delta = tick()-lastUpdate
					local look = (c.Focus.p-c.CoordinateFrame.p).unit
					local move = getNextMovement(delta)
					local pos = root.Position
					root.CFrame = CFrame.new(pos,pos+look) * move
					lastUpdate = tick()
					wait(0.01)
					--	camSync:wait()
				end
				player.Character.HumanoidRootPart.Anchored = false
				c.CameraSubject = player.Character.Humanoid
				root.Velocity = Vector3.new()
			end
		end

		function onDeselected()
			selected = false
		end

		local isOn = true
		spawn(onSelected)

		function onKeyPressed(_,state)
			if state == Enum.UserInputState.Begin then
				isOn = not isOn
				if isOn then
					onSelected()
				else
					onDeselected()
				end
			end
		end

		local mouse = player:GetMouse()
		mouse.Button1Down:Connect(function()
			if allowspeedmove then speed = 120 end
		end)
		mouse.Button1Up:Connect(function()
			speed = 60
		end)

		function ResetCamera()
			camera.Position = player.Character.HumanoidRootPart.Position + Vector3.new(0,5,0)
		end

		game:GetService("ContextActionService"):BindAction("Noclip Toggle",onKeyPressed,false,"t")
	end)

	Onandoff_57.Name = "Onandoff"
	Onandoff_57.Parent = Freecam
	Onandoff_57.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_57.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_57.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_57.Size = UDim2.new(0, 135, 0, 15)

	FastLegs.Name = "FastLegs"
	FastLegs.Parent = MovementScrollFrame
	FastLegs.BackgroundColor3 = Color3.new(0, 0, 0)
	FastLegs.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FastLegs.Position = UDim2.new(0.0287183858, 0, 0.393436015, 0)
	FastLegs.Size = UDim2.new(0, 135, 0, 26)
	FastLegs.Font = Enum.Font.SourceSans
	FastLegs.Text = "FastLegs"
	FastLegs.TextColor3 = Color3.new(1, 1, 1)
	FastLegs.TextSize = 18
	FastLegs.MouseButton1Click:connect(function()
		flying = false
		local lol = game.Workspace.Ignored.Shop["[SoloBike] - $25"]
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		noti("Please buy it then ride it and execute this again! dont be stupid pls.")
		local l__Character__4 = game.Players.LocalPlayer.Character
		local l__RunService__7 = game:GetService("RunService");
		local u25 = l__Character__4.Humanoid:LoadAnimation(game.ReplicatedStorage.ClientAnimations.Bicycling);

		local l__SeatPart__81 = l__Character__4.Humanoid.SeatPart;
		if l__SeatPart__81 and l__SeatPart__81:IsA("VehicleSeat") and l__SeatPart__81.Parent:FindFirstChild("BikeModel") then
			l__SeatPart__81:Destroy()
			u25:Play(0.100000001, 1, 0);
			while l__Character__4.Humanoid.SeatPart == l__SeatPart__81 do
				if l__SeatPart__81.Throttle == 1000 then
					u25:AdjustSpeed(1000):Destroy()
				elseif l__SeatPart__81.Throttle == -1000 then
					u25:AdjustSpeed(-1000):Destroy()
				else
					u25:AdjustSpeed(1000):Destroy()
				end;
				l__RunService__7.Heartbeat:wait();			
			end;
			u25:Stop();
			return;
		end;
	end)

	Onandoff_58.Name = "Onandoff"
	Onandoff_58.Parent = FastLegs
	Onandoff_58.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_58.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_58.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_58.Size = UDim2.new(0, 135, 0, 15)

	Maskspam.Name = "Maskspam"
	Maskspam.Parent = MovementScrollFrame
	Maskspam.BackgroundColor3 = Color3.new(0, 0, 0)
	Maskspam.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Maskspam.Position = UDim2.new(0.266734928, 0, 0.393436015, 0)
	Maskspam.Size = UDim2.new(0, 135, 0, 26)
	Maskspam.Font = Enum.Font.SourceSans
	Maskspam.Text = "MaskSpam"
	Maskspam.TextColor3 = Color3.new(1, 1, 1)
	Maskspam.TextSize = 18
	Maskspam.MouseButton1Click:connect(function()
		local notifSound = Instance.new("Sound",workspace)
		notifSound.PlaybackSpeed = 1.5
		notifSound.Volume = 0.15
		notifSound.SoundId = "rbxassetid://170765130"
		notifSound.PlayOnRemove = true
		notifSound:Destroy()
		game.StarterGui:SetCore("SendNotification", {Title = "Polakya", Text = "Mask Spam Remove it and put it", Icon = "rbxassetid://505845268", Duration = 5, Button1 = "Okay"})
		gsPlayers = game:GetService("Players")
		gsWorkspace = game:GetService("Workspace")
		gsLighting = game:GetService("Lighting")
		gsReplicatedStorage = game:GetService("ReplicatedStorage")
		gsCoreGui = game:GetService("CoreGui")
		gsTween = game:GetService("TweenService")
		gsHttp = game:GetService("HttpService")

		LP = gsPlayers.LocalPlayer
		Mouse = LP:GetMouse()

		LP.Character.ChildAdded:Connect(function(b)
			wait(0)
			if b:IsA("Accessory") then b.Handle.Mesh:Destroy()
				b.Parent = gsWorkspace
			end
		end)
	end)

	Onandoff_59.Name = "Onandoff"
	Onandoff_59.Parent = Maskspam
	Onandoff_59.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_59.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_59.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_59.Size = UDim2.new(0, 135, 0, 15)

	Naked.Name = "Naked"
	Naked.Parent = MovementScrollFrame
	Naked.BackgroundColor3 = Color3.new(0, 0, 0)
	Naked.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Naked.Position = UDim2.new(0.501445651, 0, 0.393436015, 0)
	Naked.Size = UDim2.new(0, 135, 0, 26)
	Naked.Font = Enum.Font.SourceSans
	Naked.Text = "Naked"
	Naked.TextColor3 = Color3.new(1, 1, 1)
	Naked.TextSize = 18
	Naked.MouseButton1Click:connect(function()


		local wosfeffadw = game.Players.LocalPlayer.Character.Shirt
		local wosfeffadw1 = game.Players.LocalPlayer.Character.Pants
		wosfeffadw:Destroy()
		wosfeffadw1:Destroy()
	end)

	Onandoff_60.Name = "Onandoff"
	Onandoff_60.Parent = Naked
	Onandoff_60.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_60.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_60.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_60.Size = UDim2.new(0, 135, 0, 15)

	Boneless.Name = "Boneless"
	Boneless.Parent = MovementScrollFrame
	Boneless.BackgroundColor3 = Color3.new(0, 0, 0)
	Boneless.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Boneless.Position = UDim2.new(0.739301741, 0, 0.392015576, 0)
	Boneless.Size = UDim2.new(0, 135, 0, 26)
	Boneless.Font = Enum.Font.SourceSans
	Boneless.Text = "BoneLess"
	Boneless.TextColor3 = Color3.new(1, 1, 1)
	Boneless.TextSize = 18
	Boneless.MouseButton1Click:connect(function()
		local Stuff = {"RightHand", "LeftHand","RightUpperArm","RightLowerArm","LeftUpperArm","LeftLowerArm","Head","UpperTorso"}

		pcall(function()
			for i, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
				for z, AdminName in ipairs(Stuff) do
					if v.Name == AdminName then
						if v:FindFirstChildOfClass("Motor6D") then
							local Weld = v:FindFirstChildOfClass("Motor6D")
							Weld:Destroy()
						end
					end
				end
			end
		end)
	end)

	Onandoff_61.Name = "Onandoff"
	Onandoff_61.Parent = Boneless
	Onandoff_61.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_61.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_61.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_61.Size = UDim2.new(0, 135, 0, 15)

	Mask.Name = "Mask"
	Mask.Parent = MovementScrollFrame
	Mask.BackgroundColor3 = Color3.new(0, 0, 0)
	Mask.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Mask.Position = UDim2.new(0.0287183821, 0, 0.470140576, 0)
	Mask.Size = UDim2.new(0, 135, 0, 26)
	Mask.Font = Enum.Font.SourceSans
	Mask.Text = "Mask"
	Mask.TextColor3 = Color3.new(1, 1, 1)
	Mask.TextSize = 18
	Mask.MouseButton1Click:connect(function()
		local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
		local lol = game.Workspace.Ignored.Shop["[Surgeon Mask] - $25"]
		game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
		wait(0.25)
		fireclickdetector(lol.ClickDetector,4)
		wait(0.40)
		if game.Players.LocalPlayer.Backpack:FindFirstChild("Mask") then
			game.Players.LocalPlayer.Backpack:FindFirstChild("Mask").Parent = game.Players.LocalPlayer.Character
		end
		wait()
		game.Players.LocalPlayer.Character:FindFirstChild("Mask"):Activate()
		wait(0.25)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
	end)

	Onandoff_62.Name = "Onandoff"
	Onandoff_62.Parent = Mask
	Onandoff_62.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_62.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_62.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_62.Size = UDim2.new(0, 135, 0, 15)

	AutoUnjail.Name = "AutoUnjail"
	AutoUnjail.Parent = MovementScrollFrame
	AutoUnjail.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoUnjail.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoUnjail.Position = UDim2.new(0.266734898, 0, 0.470140576, 0)
	AutoUnjail.Size = UDim2.new(0, 135, 0, 26)
	AutoUnjail.Font = Enum.Font.SourceSans
	AutoUnjail.Text = "AutoUnjail"
	AutoUnjail.TextColor3 = Color3.new(1, 1, 1)
	AutoUnjail.TextSize = 18
	AutoUnjail.MouseButton1Click:connect(function()
		if Onandoff_63.BackgroundColor3 == Color3.new(1, 0, 0)  then
			Onandoff_63.BackgroundColor3 = Color3.new(0, 1, 0)

			noti("AutoUnjail Enabled")
			autounjail = true
			flying = false
			repeat
				if game:GetService("Players").LocalPlayer.PlayerGui.MainScreenGui.TimerJail.Visible == true then
					local lol = game.Workspace.Ignored.Shop["[Key] - $125"]
					game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
					wait(0.25)
					fireclickdetector(lol.ClickDetector,4)
					wait(0.40)
					if game.Players.LocalPlayer.Backpack:FindFirstChild("[Key]") then
						game.Players.LocalPlayer.Backpack:FindFirstChild("[Key]").Parent = game.Players.LocalPlayer.Character
					end
					wait()
					game.Players.LocalPlayer.Character:FindFirstChild("[Key]"):Activate()
				end
				wait()
			until autounjail == false
		else
			Onandoff_63.BackgroundColor3 = Color3.new(1, 0, 0)
			noti("AutoUnjail Disabled")
			autounjail = false
		end
	end)

	Onandoff_63.Name = "Onandoff"
	Onandoff_63.Parent = AutoUnjail
	Onandoff_63.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_63.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_63.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_63.Size = UDim2.new(0, 135, 0, 15)

	BigOthers.Name = "BigOthers"
	BigOthers.Parent = MovementScrollFrame
	BigOthers.BackgroundColor3 = Color3.new(0, 0, 0)
	BigOthers.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	BigOthers.Position = UDim2.new(0.501445651, 0, 0.470140576, 0)
	BigOthers.Size = UDim2.new(0, 135, 0, 26)
	BigOthers.Font = Enum.Font.SourceSans
	BigOthers.Text = "BigOthers"
	BigOthers.TextColor3 = Color3.new(1, 1, 1)
	BigOthers.TextSize = 18
	BigOthers.MouseButton1Click:connect(function()
		if 	Onandoff_64.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_64.BackgroundColor3 = Color3.new(0, 1, 0)
			bigoatahar = true
			print("niggers")
			function getplrsname()
				for i,v in pairs(game:GetChildren()) do
					if v.ClassName == "Players" then
						return v.Name
					end
				end
			end
			local players = getplrsname()
			local plr = game[players].LocalPlayer
			coroutine.resume(coroutine.create(function()
				while  bigoatahar == true do
					coroutine.resume(coroutine.create(function()
						for _,v in pairs(game[players]:GetPlayers()) do
							if v.Name ~= plr.Name and v.Character then
								v.Character.LowerTorso.CanCollide = false
								v.Character.LowerTorso.Material = "Neon"
								v.Character.RightHand.Size = Vector3.new(5,5,5)
								v.Character.LeftHand.Size = Vector3.new(5,5,5)
								v.Character.HumanoidRootPart.Size = Vector3.new(15,15,15)
							end
						end
					end))
					wait(1)
				end
			end))
		else
			Onandoff_64.BackgroundColor3 = Color3.new(1, 0, 0)
			bigoatahar = false
			print("niggers")
			function getplrsname()
				for i,v in pairs(game:GetChildren()) do
					if v.ClassName == "Players" then
						return v.Name
					end
				end
			end
			local players = getplrsname()
			local plr = game[players].LocalPlayer
			coroutine.resume(coroutine.create(function()
				while  bigoatahar == false do
					coroutine.resume(coroutine.create(function()
						for _,v in pairs(game[players]:GetPlayers()) do
							if v.Name ~= plr.Name and v.Character then
								v.Character.LowerTorso.CanCollide = false
								v.Character.LowerTorso.Material = "Neon"
								v.Character.RightHand.Size = Vector3.new(0.5,0.5,0.5)
								v.Character.LeftHand.Size = Vector3.new(0.5,0.5,0.5)
								v.Character.HumanoidRootPart.Size = Vector3.new(0,0,0)
							end
						end
					end))
					wait(1)
				end
			end))
		end
	end)

	Onandoff_64.Name = "Onandoff"
	Onandoff_64.Parent = BigOthers
	Onandoff_64.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_64.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_64.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_64.Size = UDim2.new(0, 135, 0, 15)

	SpongeBob.Name = "SpongeBob"
	SpongeBob.Parent = MovementScrollFrame
	SpongeBob.BackgroundColor3 = Color3.new(0, 0, 0)
	SpongeBob.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	SpongeBob.Position = UDim2.new(0.7378093, 0, 0.470140576, 0)
	SpongeBob.Size = UDim2.new(0, 135, 0, 26)
	SpongeBob.Font = Enum.Font.SourceSans
	SpongeBob.Text = "SpongeBob"
	SpongeBob.TextColor3 = Color3.new(1, 1, 1)
	SpongeBob.TextSize = 18
	SpongeBob.MouseButton1Click:connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/EjRcJTb9", true))()

	end)

	Onandoff_65.Name = "Onandoff"
	Onandoff_65.Parent = SpongeBob
	Onandoff_65.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_65.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_65.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_65.Size = UDim2.new(0, 135, 0, 15)

	AutoBlock.Name = "AutoBlock"
	AutoBlock.Parent = MovementScrollFrame
	AutoBlock.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoBlock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoBlock.Position = UDim2.new(0.0287184119, 0, 0.544004202, 0)
	AutoBlock.Size = UDim2.new(0, 135, 0, 26)
	AutoBlock.Font = Enum.Font.SourceSans
	AutoBlock.Text = "AutoBlock"
	AutoBlock.TextColor3 = Color3.new(1, 1, 1)
	AutoBlock.TextSize = 18
	AutoBlock.MouseButton1Click:connect(function()
		autoblocking = false
		if Onandoff_66.BackgroundColor3== Color3.new(1, 0, 0) and autoblocking == false then
			Onandoff_66.BackgroundColor3 = Color3.new(0, 1, 0)
			autoblocking = true
			local bruh = game.Players.LocalPlayer.Character.Humanoid
			while autoblocking == true do
				if bruh.Health <= 10 or bruh.Health <= 20 or bruh.Health <= 30 then
					local A_1 = "Block"
					local A_2 = true
					local Event = game:GetService("ReplicatedStorage").MainEvent
					Event:FireServer(A_1, A_2)
				end
				wait()
			end

		else
			Onandoff_66.BackgroundColor3= Color3.new(1, 0, 0)
			autoblocking = false
		end
	end)

	Onandoff_66.Name = "Onandoff"
	Onandoff_66.Parent = AutoBlock
	Onandoff_66.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_66.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_66.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_66.Size = UDim2.new(0, 135, 0, 15)

	AntiStomp.Name = "AntiStomp"
	AntiStomp.Parent = MovementScrollFrame
	AntiStomp.BackgroundColor3 = Color3.new(0, 0, 0)
	AntiStomp.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AntiStomp.Position = UDim2.new(0.266734958, 0, 0.544004202, 0)
	AntiStomp.Size = UDim2.new(0, 135, 0, 26)
	AntiStomp.Font = Enum.Font.SourceSans
	AntiStomp.Text = "AntiStomp"
	AntiStomp.TextColor3 = Color3.new(1, 1, 1)
	AntiStomp.TextSize = 18
	AntiStomp.MouseButton1Click:connect(function()
		if 	Onandoff_67.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_67.BackgroundColor3 = Color3.new(0, 1, 0)

			ssantistomp = true
			pcall(function() 
				local corepackages = game:GetService"CorePackages" 
				local localplayer = game:GetService"Players".LocalPlayer 
				local run = game:GetService"RunService" run:BindToRenderStep("rrrrrrrrrrr",2000,function() 
					pcall(function() 
						if localplayer.Character.BodyEffects["K.O"].Value and ssantistomp == true then 
							localplayer.Character.Humanoid:UnequipTools() 
							localplayer.Character.Humanoid:Destroy() workspace.CurrentCamera.CameraSubject = localplayer.Character 
							wait() 
							local prt = Instance.new("Model", corepackages); Instance.new("Part", prt).Name="Torso"; Instance.new("Part", prt).Name="Head"; Instance.new("Humanoid", prt).Name="Humanoid"; localplayer.Character=prt
						end 
					end)
				end)
			end)

		else
			Onandoff_67.BackgroundColor3 = Color3.new(1, 0, 0)
			ssantistomp = false


		end

	end)

	Onandoff_67.Name = "Onandoff"
	Onandoff_67.Parent = AntiStomp
	Onandoff_67.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_67.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_67.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_67.Size = UDim2.new(0, 135, 0, 15)

	AnimationGamepass.Name = "AnimationGamepass"
	AnimationGamepass.Parent = MovementScrollFrame
	AnimationGamepass.BackgroundColor3 = Color3.new(0, 0, 0)
	AnimationGamepass.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AnimationGamepass.Position = UDim2.new(0.501285255, 0, 0.542583764, 0)
	AnimationGamepass.Size = UDim2.new(0, 135, 0, 26)
	AnimationGamepass.Font = Enum.Font.SourceSans
	AnimationGamepass.Text = "Animationgamepass"
	AnimationGamepass.TextColor3 = Color3.new(1, 1, 1)
	AnimationGamepass.TextSize = 18
	AnimationGamepass.MouseButton1Click:connect(function()
		-- // Services
		local Players = game:GetService("Players")
		local MarketPlaceService = game:GetService("MarketplaceService")

		-- // Vars
		local LocalPlayer = Players.LocalPlayer

		-- // Gamepass Check
		if (MarketPlaceService:UserOwnsGamePassAsync(LocalPlayer.UserId, 6412475)) then
			return
		end

		-- // Vars
		local PlayerGui = LocalPlayer.PlayerGui

		-- // Animation GUI
		local MainScreenGui = PlayerGui.MainScreenGui
		local AnimationPack = MainScreenGui.AnimationPack
		local AnimationPackScrolling = AnimationPack.ScrollingFrame

		-- // Animation IDs
		local Animations = {
			Lean = 3152375249,
			Lay = 3152378852,
			Dance1 = 3189773368,
			Dance2 = 3189776546,
			Greet = 3189777795,
			["Chest Pump"] = 3189779152,
			Praying = 3487719500
		}

		-- // Run Animation
		function runAnimation(animationId)
			local AnimationTrack = Instance.new("Animation")
			AnimationTrack.AnimationId = "rbxassetid://" .. animationId

			local Humanoid = LocalPlayer.Character:WaitForChild("Humanoid")

			-- // Stop current running animation
			local AnimationTracks = Humanoid:GetPlayingAnimationTracks()
			for i = 1, #AnimationTracks do
				AnimationTracks[i]:Stop()
			end

			-- // Run animation
			local Animation = Humanoid:LoadAnimation(AnimationTrack)
			Animation:Play()


		end

		function Stopanimation(animationId)
			local AnimationTrack = Instance.new("Animation")
			AnimationTrack.AnimationId = "rbxassetid://" .. animationId

			local Humanoid = LocalPlayer.Character:WaitForChild("Humanoid")

			-- // Stop current running animation
			local AnimationTracks = Humanoid:GetPlayingAnimationTracks()
			for i = 1, #AnimationTracks do
				AnimationTracks[i]:Stop()
			end

			-- // Run animation
			local Animation = Humanoid:LoadAnimation(AnimationTrack)
			Animation:Stop()


		end


		-- // Loop through all Animations
		do
			local AnimationButtons = AnimationPackScrolling:GetChildren()
			for i = 1, #AnimationButtons do
				local v = AnimationButtons[i]

				if (v:IsA("TextButton")) then
					v.MouseButton1Click:Connect(function()
						runAnimation(Animations[v.Text])
					end)

				end
			end
		end

		-- // Add Functionality to GUI
		AnimationPack.Visible = true
		AnimationPack.MouseButton1Click:Connect(function()
			AnimationPack.CloseButton.Visible = AnimationPack.Visible
			AnimationPackScrolling.Visible = AnimationPack.Visible
		end)
		AnimationPack.CloseButton.MouseButton1Click:Connect(function()
			AnimationPack.CloseButton.Visible = not AnimationPack.CloseButton.Visible
			AnimationPackScrolling.Visible = AnimationPack.CloseButton.Visible
			AnimationPack.Visible = not AnimationPack.CloseButton.Visible
		end)
	end)

	Onandoff_68.Name = "Onandoff"
	Onandoff_68.Parent = AnimationGamepass
	Onandoff_68.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_68.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_68.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_68.Size = UDim2.new(0, 135, 0, 15)

	Godaura.Name = "Godaura"
	Godaura.Parent = MovementScrollFrame
	Godaura.BackgroundColor3 = Color3.new(0, 0, 0)
	Godaura.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Godaura.Position = UDim2.new(0.739462197, 0, 0.542583764, 0)
	Godaura.Size = UDim2.new(0, 135, 0, 26)
	Godaura.Font = Enum.Font.SourceSans
	Godaura.Text = "GodAura"
	Godaura.TextColor3 = Color3.new(1, 1, 1)
	Godaura.TextSize = 18
	Godaura.MouseButton1Click:connect(function()
		if Onandoff_69.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_69.BackgroundColor3 = Color3.new(0, 1, 0)
			aurapro = true

			if workspace:FindFirstChild("Core") then
				workspace.Core:Destroy()
			end
			local Core = Instance.new("Part")
			Core.Name = "Core"
			Core.Size = Vector3.new(0.05, 0.05, 0.05)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CanCollide = false
			local savepos = game.Players.LocalPlayer.Character.UpperTorso.Position
			local lol = game.Workspace.Ignored.Shop["[Hockey Mask] - $60"]
			game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
			wait(0.25)
			fireclickdetector(lol.ClickDetector,4)
			wait(0.25)
			if game.Players.LocalPlayer.Backpack:FindFirstChild("Mask") then
				game.Players.LocalPlayer.Backpack:FindFirstChild("Mask").Parent = game.Players.LocalPlayer.Character
			end
			wait(.2)
			local notifSound = Instance.new("Sound",workspace)
			notifSound.PlaybackSpeed = 1.5
			notifSound.Volume = 0.15
			notifSound.SoundId = "rbxassetid://170765130"
			notifSound.PlayOnRemove = true
			notifSound:Destroy()
			game.StarterGui:SetCore("SendNotification", {Title = "Polakya", Text = "Please wait a few secs", Icon = "rbxassetid://505845268", Duration = 15, Button1 = "Okay"})
			gsPlayers = game:GetService("Players")
			gsWorkspace = game:GetService("Workspace")
			gsLighting = game:GetService("Lighting")
			gsReplicatedStorage = game:GetService("ReplicatedStorage")
			gsCoreGui = game:GetService("CoreGui")
			gsTween = game:GetService("TweenService")
			gsHttp = game:GetService("HttpService")

			LP = gsPlayers.LocalPlayer
			Mouse = LP:GetMouse()

			LP.Character.ChildAdded:Connect(function(b)
				wait(0)
				if b:IsA("Accessory") then b.Handle.Mesh:Destroy()
					b.Parent = gsWorkspace
				end
			end)
			wait()
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-295.006, 90.151, -700.9000)
			wait(1)
			if game.Players.LocalPlayer.Backpack:FindFirstChild("Mask") then
				game.Players.LocalPlayer.Backpack:FindFirstChild("Mask").Parent = game.Players.LocalPlayer.Character
			end
			wait(.1)
			game.Players.LocalPlayer.Character.HumanoidRootPart.Massless = true

			game:GetService('RunService').Stepped:connect(function()
				if noclip then
					game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
				end
			end)			
			noclip = not noclip
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(1)
			game.Players.LocalPlayer.Character.Mask:Activate()
			wait(.1)

			spawn(function()
				while aurapro == true do game:GetService("RunService").Heartbeat:wait()
					for i,v in pairs(game.Players:GetPlayers()) do
						if v == game.Players.LocalPlayer == false then
							game.Players.LocalPlayer.MaximumSimulationRadius = math.pow(math.huge,math.huge)*math.huge
							game.Players.LocalPlayer.SimulationRadius = math.pow(math.huge,math.huge)*math.huge
							v.MaximumSimulationRadius = 0
							v.SimulationRadius = 0
							game:GetService("RunService").Stepped:wait()
						end
					end
				end
			end)

			local Player = game:GetService("Players").LocalPlayer
			local Players = game:GetService("Players")
			local HatList = {}
			local i = 0
			for _,l in pairs(Player.Character:GetChildren()) do
				if l:IsA("Accessory") then if i>0 then l.Parent = workspace  end i = i + 1 end;
			end
			wait(.1)



			for _,v in pairs(workspace:GetDescendants()) do
				if v.Name == "Handle" and v:IsA("BasePart") and v.Parent:IsA("Accessory") and v:IsDescendantOf(Player.Character)==false and Players:GetPlayerFromCharacter(v.Parent.Parent)==nil then
					table.insert(HatList,v)
					v.CanCollide = false
				end
			end

			for _,hat in pairs(HatList) do
				hat.Parent = workspace
				hat.Position = Player.Character.HumanoidRootPart.Position + Player.Character.HumanoidRootPart.CFrame.lookVector * 5
				local BodyPos = Instance.new("BodyPosition",hat)
				local BodyAng = Instance.new("BodyAngularVelocity",hat)
				BodyAng.AngularVelocity = Vector3.new(0,9e12,0)
				BodyAng.P = 9e12
				BodyPos.MaxForce = Vector3.new(9e9,9e9,9e9)
				BodyPos.P = 9e8
				spawn(function()
					while wait() and aurapro == true do
						if pcall(function()
								hat.CanCollide = false

								BodyPos.Position = Player.Character.HumanoidRootPart.Position + Vector3.new(math.random(-2,2),math.random(-2,2),math.random(-2,2))
							end) then
						else
							BodyPos:Destroy()
							hat.CanCollide = false
						end
					end
				end)

			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.Massless = false

			noclip = false
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		else 
			Onandoff_69.BackgroundColor3 = Color3.new(1, 0, 0)
			game.Players.LocalPlayer.Character.HumanoidRootPart.Massless = false

			aurapro = false
			noclip = false
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		end
	end)

	Onandoff_69.Name = "Onandoff"
	Onandoff_69.Parent = Godaura
	Onandoff_69.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_69.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_69.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_69.Size = UDim2.new(0, 135, 0, 15)

	Fakegodblock.Name = "Fakegodblock"
	Fakegodblock.Parent = MovementScrollFrame
	Fakegodblock.BackgroundColor3 = Color3.new(0, 0, 0)
	Fakegodblock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Fakegodblock.Position = UDim2.new(0.0303713083, 0, 0.6235497, 0)
	Fakegodblock.Size = UDim2.new(0, 135, 0, 26)
	Fakegodblock.Font = Enum.Font.SourceSans
	Fakegodblock.Text = "FakeGodBlock"
	Fakegodblock.TextColor3 = Color3.new(1, 1, 1)
	Fakegodblock.TextSize = 18
	Fakegodblock.MouseButton1Click:connect(function()
		if 		Onandoff_70.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_70.BackgroundColor3 = Color3.new(0, 1, 0)
			bakahi = true
			--made by Nighter
			--godblock/godbullet
			noti("Press [F]")
			gsPlayers = game:GetService("Players")
			gsWorkspace = game:GetService("Workspace")
			gsLighting = game:GetService("Lighting")
			gsReplicatedStorage = game:GetService("ReplicatedStorage")
			gsCoreGui = game:GetService("CoreGui")
			gsTween = game:GetService("TweenService")
			gsHttp = game:GetService("HttpService")
			LP = gsPlayers.LocalPlayer
			Mouse = LP:GetMouse()
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
			--ea
			while bakahi == true do
				pcall(function()
					for i, v in pairs(game.Players:GetPlayers()) do
						if (v.Character.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 10 and v.Name ~= game.Players.LocalPlayer.Name then 
							game.ReplicatedStorage.MainEvent:FireServer("Block", true)
							wait()
							game.ReplicatedStorage.MainEvent:FireServer("Block", false)
						end
						wait()
					end
				end)
				wait()
				for _, v in next, game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid"):GetPlayingAnimationTracks() do
					if (v.Animation.AnimationId:match("rbxassetid://2788354405")) then
						v:Stop();
					end;
				end;
			end
		else
			Onandoff_70.BackgroundColor3 = Color3.new(1, 0, 0)
			bakahi = false 
		end
	end)

	Onandoff_70.Name = "Onandoff"
	Onandoff_70.Parent = Fakegodblock
	Onandoff_70.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_70.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_70.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_70.Size = UDim2.new(0, 135, 0, 15)

	AntiKnock.Name = "AntiKnock"
	AntiKnock.Parent = MovementScrollFrame
	AntiKnock.BackgroundColor3 = Color3.new(0, 0, 0)
	AntiKnock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AntiKnock.Position = UDim2.new(0.266734958, 0, 0.6235497, 0)
	AntiKnock.Size = UDim2.new(0, 135, 0, 26)
	AntiKnock.Font = Enum.Font.SourceSans
	AntiKnock.Text = "AntiKnock"
	AntiKnock.TextColor3 = Color3.new(1, 1, 1)
	AntiKnock.TextSize = 18
	AntiKnock.MouseButton1Click:connect(function()
		if 		Onandoff_71.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_71.BackgroundColor3 = Color3.new(0, 1, 0)

			nokncok = true
			delay(0, function()

				while nokncok == true do			 
					pcall(function()
						game.Players.LocalPlayer.Character.BodyEffects["K.O"]:Destroy()
					end)
					wait()
				end
			end)
		else
			nokncok = false
			Onandoff_71.BackgroundColor3 = Color3.new(1, 0, 0)
			ps = game:GetService("Players")
			lp2 = ps.LocalPlayer
			char12 = lp2.Character
			local Clone1 = Instance.new("IntValue")
			Clone1.Name = "K.O"
			Clone1.Parent = char12.BodyEffects
		end
	end)

	Onandoff_71.Name = "Onandoff"
	Onandoff_71.Parent = AntiKnock
	Onandoff_71.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_71.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_71.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_71.Size = UDim2.new(0, 135, 0, 15)

	BikeFly.Name = "BikeFly"
	BikeFly.Parent = MovementScrollFrame
	BikeFly.BackgroundColor3 = Color3.new(0, 0, 0)
	BikeFly.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	BikeFly.Position = UDim2.new(0.501445711, 0, 0.6235497, 0)
	BikeFly.Size = UDim2.new(0, 135, 0, 26)
	BikeFly.Font = Enum.Font.SourceSans
	BikeFly.Text = "BikeFly"
	BikeFly.TextColor3 = Color3.new(1, 1, 1)
	BikeFly.TextSize = 18
	BikeFly.MouseButton1Click:connect(function()
		if 	Bikeflytext.Text:match("%d+") then

			local idspeed = Bikeflytext.Text:match("%d+")

			local speed = Bikeflytext.Text
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
				if control.e and speed<idspeed then
					speed = speed + 1
				end
				if control.q and speed > 0 then
					speed = speed - 1
				end
			end
		else
			noti("Put Speed On The TextBox")
		end
	end)

	Bikeflytext.Name = "Bikefly text"
	Bikeflytext.Parent = BikeFly
	Bikeflytext.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	Bikeflytext.BorderColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	Bikeflytext.Position = UDim2.new(0.00740740728, 0, 1, 0)
	Bikeflytext.Size = UDim2.new(0, 133, 0, 15)
	Bikeflytext.Font = Enum.Font.SourceSans
	Bikeflytext.PlaceholderColor3 = Color3.new(1, 1, 1)
	Bikeflytext.PlaceholderText = "Speed Here"
	Bikeflytext.Text = ""
	Bikeflytext.TextColor3 = Color3.new(1, 1, 1)
	Bikeflytext.TextSize = 16

	InstantBlock.Name = "InstantBlock"
	InstantBlock.Parent = MovementScrollFrame
	InstantBlock.BackgroundColor3 = Color3.new(0, 0, 0)
	InstantBlock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	InstantBlock.Position = UDim2.new(0.0303713232, 0, 0.7016747, 0)
	InstantBlock.Size = UDim2.new(0, 135, 0, 26)
	InstantBlock.Font = Enum.Font.SourceSans
	InstantBlock.Text = "InstantBlock"
	InstantBlock.TextColor3 = Color3.new(1, 1, 1)
	InstantBlock.TextSize = 18
	InstantBlock.MouseButton1Click:connect(function()
		if 	Onandoff_72.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_72.BackgroundColor3 = Color3.new(0, 1, 0)
			ezinstantblock = true
			while ezinstantblock == true do
				local A_1 = "Block"
				local A_2 = true
				local Event = game:GetService("ReplicatedStorage").MainEvent
				Event:FireServer(A_1, A_2)

				wait()
			end
		else
			Onandoff_72.BackgroundColor3 = Color3.new(1, 0, 0)
			ezinstantblock = false
			game.ReplicatedStorage.MainEvent:FireServer("Block", false)

		end
	end)

	Onandoff_72.Name = "Onandoff"
	Onandoff_72.Parent = InstantBlock
	Onandoff_72.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_72.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_72.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_72.Size = UDim2.new(0, 135, 0, 15)

	Mousetp.Name = "Mouse tp"
	Mousetp.Parent = MovementScrollFrame
	Mousetp.BackgroundColor3 = Color3.new(0, 0, 0)
	Mousetp.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Mousetp.Position = UDim2.new(0.73780936, 0, 0.6235497, 0)
	Mousetp.Size = UDim2.new(0, 135, 0, 26)
	Mousetp.Font = Enum.Font.SourceSans
	Mousetp.Text = "Mouse Tp"
	Mousetp.TextColor3 = Color3.new(1, 1, 1)
	Mousetp.TextSize = 18
	Mousetp.MouseButton1Click:connect(function()
		if 	Mousetp.TextColor3 == Color3.new(1, 1, 1) then
			Mousetp.TextColor3 = Color3.new(0, 1, 0)

			mouseyes = true

			local Lplr = game.Players.LocalPlayer
			local mouse = Lplr:GetMouse()

			mouse.KeyDown:connect(function(key)
				if	key == MousetpHere.Text and mouseyes == true then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(mouse.Hit.p)		
				end
			end)

		else
			Mousetp.TextColor3 = Color3.new(1, 1, 1)
			mouseyes = false
			MousetpHere.Text = ""

		end
	end)

	MousetpHere.Name = "Mousetp Here"
	MousetpHere.Parent = Mousetp
	MousetpHere.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	MousetpHere.BorderColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	MousetpHere.Position = UDim2.new(0.00740740728, 0, 1, 0)
	MousetpHere.Size = UDim2.new(0, 133, 0, 15)
	MousetpHere.Font = Enum.Font.SourceSans
	MousetpHere.PlaceholderColor3 = Color3.new(1, 1, 1)
	MousetpHere.PlaceholderText = "KeyBind Here"
	MousetpHere.Text = ""
	MousetpHere.TextColor3 = Color3.new(1, 1, 1)
	MousetpHere.TextSize = 16

	Onandoff_73.Name = "Onandoff"
	Onandoff_73.Parent = MovementScrollFrame
	Onandoff_73.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_73.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_73.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_73.Size = UDim2.new(0, 135, 0, 15)

	AutoFarmScrollFrame.Name = "AutoFarmScrollFrame"
	AutoFarmScrollFrame.Parent = MainChild
	AutoFarmScrollFrame.Active = true
	AutoFarmScrollFrame.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	AutoFarmScrollFrame.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	AutoFarmScrollFrame.Position = UDim2.new(0.247117221, 0, 0.0254765432, 0)
	AutoFarmScrollFrame.Size = UDim2.new(0, 605, 0, 333)
	AutoFarmScrollFrame.Visible = false

	AutoFarm.Name = "AutoFarm"
	AutoFarm.Parent = AutoFarmScrollFrame
	AutoFarm.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoFarm.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoFarm.Position = UDim2.new(0.031863749, 0, 0.0312201343, 0)
	AutoFarm.Size = UDim2.new(0, 135, 0, 26)
	AutoFarm.Font = Enum.Font.SourceSans
	AutoFarm.Text = "AutoFarm"
	AutoFarm.TextColor3 = Color3.new(1, 1, 1)
	AutoFarm.TextSize = 18
	AutoFarm.MouseButton1Click:connect(function()
		if Onandoff_74.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_74.BackgroundColor3 = Color3.new(0, 1, 0)

			robyes = true
			noti("Setup Autofarm....")
			wait(.2)
			game.Players.LocalPlayer.Backpack:FindFirstChild("Combat").Parent = game.Players.LocalPlayer.Character
			wait(.1)

			repeat
			
				
				function GetATM()
					for i, v in pairs(workspace.Cashiers:GetChildren()) do
						if v:WaitForChild("Humanoid").Health > 0 then
							local cf = v.Open.CFrame
							local lv = cf.lookVector
							game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame = cf + (lv * Vector3.new(0, 0, -2))
							return v
						end
					end
				end

			

				function bypass()
					local oh1 = CFrame.new(-346.434296, 52.5954704, 446.756989)
					local oh2 = game:GetService("Players")
					local oh3 = oh2.LocalPlayer.Character.HumanoidRootPart


					oh3.CFrame = oh1
					wait(1.5)
				end
				function money()
					for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
						if v.Name == "MoneyDrop" and (workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.Position - v.Position).Magnitude < 25
						then
							dineros = true
							fireclickdetector(v.ClickDetector)
							wait(0.7)
							dineros = false
						end
					end
				end
local ATM
				ATM = GetATM()
				money()
				

				if ATM.Humanoid.Health > 0 then
					game.Players.LocalPlayer.Character:FindFirstChild("Combat"):Activate()
					
					wait(4)
					local cf = ATM.Open.CFrame
					local lv = cf.lookVector
					game.workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame =
						cf + (lv * Vector3.new(0, 0, -2))
					wait()
				end


				wait()
			until robyes == false
			
			
			
		
		else
			Onandoff_74.BackgroundColor3 = Color3.new(1, 0, 0)
			robyes = false
			collact = false


		end

	end)


	Onandoff_74.Name = "Onandoff"
	Onandoff_74.Parent = AutoFarm
	Onandoff_74.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_74.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_74.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_74.Size = UDim2.new(0, 135, 0, 15)

	Lettuce.Name = "Lettuce"
	Lettuce.Parent = AutoFarmScrollFrame
	Lettuce.BackgroundColor3 = Color3.new(0, 0, 0)
	Lettuce.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Lettuce.Position = UDim2.new(0.267193943, 0, 0.0309641957, 0)
	Lettuce.Size = UDim2.new(0, 135, 0, 26)
	Lettuce.Font = Enum.Font.SourceSans
	Lettuce.Text = "Lettuce"
	Lettuce.TextColor3 = Color3.new(1, 1, 1)
	Lettuce.TextSize = 18
	Lettuce.MouseButton1Click:connect(function()
		
		if Onandoff_75.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_75.BackgroundColor3= Color3.new(0, 1, 0)
			farmlettuce = true
			flying = false
			repeat
				local lol = game.Workspace.Ignored.Shop["[Lettuce] - $5"]
				game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
				wait(0.25)
				fireclickdetector(lol.ClickDetector,4)
				wait(0.50)
				if game.Players.LocalPlayer.Backpack:FindFirstChild("[Lettuce]") then
					game.Players.LocalPlayer.Backpack:FindFirstChild("[Lettuce]").Parent = game.Players.LocalPlayer.Character
				end
				wait(.40)
				game.Players.LocalPlayer.Character:FindFirstChild("[Lettuce]"):Activate()

			until farmlettuce == false
		else
			Onandoff_75.BackgroundColor3 = Color3.new(1, 0, 0)
			farmlettuce = false
		end
	end)

	Onandoff_75.Name = "Onandoff"
	Onandoff_75.Parent = Lettuce
	Onandoff_75.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_75.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_75.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_75.Size = UDim2.new(0, 135, 0, 15)

	Weight.Name = "Weight"
	Weight.Parent = AutoFarmScrollFrame
	Weight.BackgroundColor3 = Color3.new(0, 0, 0)
	Weight.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Weight.Position = UDim2.new(0.503098488, 0, 0.0312201343, 0)
	Weight.Size = UDim2.new(0, 135, 0, 26)
	Weight.Font = Enum.Font.SourceSans
	Weight.Text = "Weight"
	Weight.TextColor3 = Color3.new(1, 1, 1)
	Weight.TextSize = 18
	Weight.MouseButton1Click:connect(function()
		local plr = game.Players.LocalPlayer
		local AncientPOS = plr.Character.HumanoidRootPart.Position
		if Onandoff_76.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_76.BackgroundColor3 = Color3.new(0, 1, 0)
			farmwight = true
			flying = false
			local lol = game.Workspace.Ignored.Shop["[HeavyWeights] - $250"]
			game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
			wait(0.25)
			fireclickdetector(lol.ClickDetector,4)
			wait(.40)
			repeat
				if game.Players.LocalPlayer.Backpack:FindFirstChild("[HeavyWeights]") then
					game.Players.LocalPlayer.Backpack:FindFirstChild("[HeavyWeights]").Parent = game.Players.LocalPlayer.Character
				end
				game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
				game.Players.LocalPlayer.Character:FindFirstChild("[HeavyWeights]"):Activate()
				wait()
			until farmwight == false
		else
			local lol = game.Workspace.Ignored.Shop["[HeavyWeights] - $250"]
			game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
			Onandoff_76.BackgroundColor3 = Color3.new(1, 0, 0)
			farmwight = false



		end
	end)

	Onandoff_76.Name = "Onandoff"
	Onandoff_76.Parent = Weight
	Onandoff_76.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_76.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_76.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_76.Size = UDim2.new(0, 135, 0, 15)

	Hospital.Name = "Hospital"
	Hospital.Parent = AutoFarmScrollFrame
	Hospital.BackgroundColor3 = Color3.new(0, 0, 0)
	Hospital.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Hospital.Position = UDim2.new(0.739462137, 0, 0.0312201343, 0)
	Hospital.Size = UDim2.new(0, 135, 0, 26)
	Hospital.Font = Enum.Font.SourceSans
	Hospital.Text = "Hospital"
	Hospital.TextColor3 = Color3.new(1, 1, 1)
	Hospital.TextSize = 18
	Hospital.MouseButton1Click:connect(function()
		if Onandoff_77.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_77.BackgroundColor3 = Color3.new(0, 1, 0)
			hostifarm = true
			flying = false
			repeat
				wait()
				local d = Vector3.new(116.81, 22.8002, -478.199)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
				local X;
				for Y, Z in pairs(game.Workspace.Ignored.HospitalJob:GetChildren()) do
					wait()
					if Z then
						if Z:IsA("Model") then
							if Z.Name == "Can I get the Green bottle" then
								X = "Green"
							end;
							if Z.Name == "Can I get the Red bottle" then
								X = "Red"
							end;
							if Z.Name == "Can I get the Blue bottle" then
								X = "Blue"
							end;
							print(X)
							print(Z)
							fireclickdetector(game.Workspace.Ignored.HospitalJob:FindFirstChild(X):FindFirstChild("ClickDetector"), 4)
							fireclickdetector(Z:FindFirstChild("ClickDetector"), 4)
							wait(3)
						end
					end
				end
			until hostifarm == false
		else
			Onandoff_77.BackgroundColor3 = Color3.new(1, 0, 0)
			hostifarm = false
		end
	end)

	Onandoff_77.Name = "Onandoff"
	Onandoff_77.Parent = Hospital
	Onandoff_77.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_77.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_77.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_77.Size = UDim2.new(0, 135, 0, 15)

	Box.Name = "Box"
	Box.Parent = AutoFarmScrollFrame
	Box.BackgroundColor3 = Color3.new(0, 0, 0)
	Box.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Box.Position = UDim2.new(0.739462137, 0, 0.10366331, 0)
	Box.Size = UDim2.new(0, 135, 0, 26)
	Box.Font = Enum.Font.SourceSans
	Box.Text = "Box"
	Box.TextColor3 = Color3.new(1, 1, 1)
	Box.TextSize = 18
	Box.MouseButton1Click:connect(function()
		if Onandoff_78.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_78.BackgroundColor3 = Color3.new(0, 1, 0)
			flying = false

			boxingomg = true
			repeat
				local reachthing = "Combat"
				if game.Players.LocalPlayer.Backpack:FindFirstChild(reachthing) then
					game.Players.LocalPlayer.Backpack:FindFirstChild(reachthing).Parent = game.Players.LocalPlayer.Character
				end
				wait()
				game:GetService("VirtualUser"):ClickButton1(Vector2.new(2,222,2))
				game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-261.006, 23.151, -1137.531)

			until boxingomg == false
		else
			Onandoff_78.BackgroundColor3 = Color3.new(1, 0, 0)
			boxingomg = false
			game.Players.LocalPlayer.Character.Humanoid:UnequipTools()

		end
	end)

	Onandoff_78.Name = "Onandoff"
	Onandoff_78.Parent = Box
	Onandoff_78.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_78.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_78.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_78.Size = UDim2.new(0, 135, 0, 15)

	Shoes.Name = "Shoes"
	Shoes.Parent = AutoFarmScrollFrame
	Shoes.BackgroundColor3 = Color3.new(0, 0, 0)
	Shoes.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Shoes.Position = UDim2.new(0.031863749, 0, 0.10366331, 0)
	Shoes.Size = UDim2.new(0, 135, 0, 26)
	Shoes.Font = Enum.Font.SourceSans
	Shoes.Text = "Shoes"
	Shoes.TextColor3 = Color3.new(1, 1, 1)
	Shoes.TextSize = 18
	Shoes.MouseButton1Click:connect(function()
		if Onandoff_79.BackgroundColor3 ==  Color3.new(1, 0, 0) then
			Onandoff_79.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("If it didn't work click again until button green enabled")
			shoesfarm = true
			flying = false
			function ToShoes(d, C, D)
				local E = game:service"TweenService"
				local F = TweenInfo.new((C - d).Magnitude / 50, Enum.EasingStyle.Quad)
				local G = tick()
				local H, I = pcall(function()
					local H = E:Create(game.Players.LocalPlayer.Character["HumanoidRootPart"], F, {
						CFrame = D
					})
					H:Play()
				end)
				if not H then
					return I
				end
			end;
			local function J(K, L)
				local M = (K.Position - L.Position).magnitude;
				if M <= 50 then
					fireclickdetector(L:FindFirstChild("ClickDetector"), 4)
					return M
				end
			end;
			repeat
				for u, v in pairs(game.Workspace:GetDescendants()) do
					if v:IsA("Seat") then
						v:Destroy()
					end
				end;
				for N, O in pairs(game.Workspace.Ignored.Drop:GetChildren()) do
					if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - O.Position).Magnitude <= 50 then
						local P = O
						J(game.Players.LocalPlayer.Character.HumanoidRootPart, O)
						wait()
					end
				end;
				wait()
				for S, T in pairs(game.Workspace.Ignored.Drop:GetChildren()) do
					wait()
					if T:IsA("MeshPart") then
						if T:FindFirstChild("ClickDetector") then
							if game.Players.LocalPlayer.Character.BodyEffects.ShoesCollect.Value < 4 then
								T.Orientation = Vector3.new(0, 0, 0)
								wait()
								posM = T.Position - Vector3.new(0, 0, 0)
								poscM = T.CFrame - Vector3.new(0, -10, 0)
								ToShoes(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position, posM, poscM)
								repeat
									wait()
									wait()
								until (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position - posM).Magnitude < 50 or not b.flags.Shoe
							else
								wait()
								local U = game.Workspace.Ignored["Clean the shoes on the floor and come to me for cash"].Head;
								posMV = U.Position - Vector3.new(0, 0, 0)
								poscMV = U.CFrame - Vector3.new(0, -2, 0)
								ToShoes(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position, posMV, poscMV)
								wait(.3)
								if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - U.Position).Magnitude <= 25 then
									fireclickdetector(U.Parent.ClickDetector)
									wait()
								end
							end
						end
					end
				end
			until shoesfarm == false
		else
			Onandoff_79.BackgroundColor3 = Color3.new(1, 0, 0)
			shoesfarm = false
		end
	end)

	Onandoff_79.Name = "Onandoff"
	Onandoff_79.Parent = Shoes
	Onandoff_79.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_79.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_79.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_79.Size = UDim2.new(0, 135, 0, 15)

	WalkSpeed.Name = "WalkSpeed"
	WalkSpeed.Parent = AutoFarmScrollFrame
	WalkSpeed.BackgroundColor3 = Color3.new(0, 0, 0)
	WalkSpeed.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	WalkSpeed.Position = UDim2.new(0.267193943, 0, 0.103407376, 0)
	WalkSpeed.Size = UDim2.new(0, 135, 0, 26)
	WalkSpeed.Font = Enum.Font.SourceSans
	WalkSpeed.Text = "WalkSpeed"
	WalkSpeed.TextColor3 = Color3.new(1, 1, 1)
	WalkSpeed.TextSize = 18
	WalkSpeed.MouseButton1Click:connect(function()

		if Onandoff_80.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_80.BackgroundColor3 = Color3.new(0, 1, 0)
			sped = true
			game.Players.LocalPlayer.Character.Humanoid.Name = "TRASH"
			game.Players.LocalPlayer.Character.TRASH.WalkSpeed = 100
			demspeed = 200
			noti("This Will Destroy Your Aim Will Be Fixed Soon")
		else
			Onandoff_80.BackgroundColor3 = Color3.new(1, 0, 0)
			sped = false
			game.Players.LocalPlayer.Character.TRASH.WalkSpeed = 16
			demspeed = 50
			game.Players.LocalPlayer.Character.TRASH.Name = "Humanoid"

		end


	end)

	Onandoff_80.Name = "Onandoff"
	Onandoff_80.Parent = WalkSpeed
	Onandoff_80.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_80.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_80.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_80.Size = UDim2.new(0, 135, 0, 15)

	JumpPower.Name = "JumpPower"
	JumpPower.Parent = AutoFarmScrollFrame
	JumpPower.BackgroundColor3 = Color3.new(0, 0, 0)
	JumpPower.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	JumpPower.Position = UDim2.new(0.503098488, 0, 0.10366331, 0)
	JumpPower.Size = UDim2.new(0, 135, 0, 26)
	JumpPower.Font = Enum.Font.SourceSans
	JumpPower.Text = "JumpPower"
	JumpPower.TextColor3 = Color3.new(1, 1, 1)
	JumpPower.TextSize = 18
	JumpPower.MouseButton1Click:connect(function()
		if Onandoff_81.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_81.BackgroundColor3 = Color3.new(0, 1, 0)
			sped = true
			game.Players.LocalPlayer.Character.Humanoid.Name = "Humz"
			game.Players.LocalPlayer.Character.Humz.JumpPower = 200
			demspeed = 200
			noti("This Will Destroy Your Aim Will Be Fixed Soon")

		else
			Onandoff_81.BackgroundColor3 = Color3.new(1, 0, 0)

			sped = false
			game.Players.LocalPlayer.Character.Humz.JumpPower = 50
			demspeed = 50
			game.Players.LocalPlayer.Character.Humz.Name = "Humanoid"

		end
	end)

	Onandoff_81.Name = "Onandoff"
	Onandoff_81.Parent = JumpPower
	Onandoff_81.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_81.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_81.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_81.Size = UDim2.new(0, 135, 0, 15)

	CashModeScrollFrame.Name = "CashModeScrollFrame"
	CashModeScrollFrame.Parent = MainChild
	CashModeScrollFrame.Active = true
	CashModeScrollFrame.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	CashModeScrollFrame.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	CashModeScrollFrame.Position = UDim2.new(0.247117221, 0, 0.0254765432, 0)
	CashModeScrollFrame.Size = UDim2.new(0, 605, 0, 333)
	CashModeScrollFrame.Visible = false

	Cashfloat.Name = "Cashfloat"
	Cashfloat.Parent = CashModeScrollFrame
	Cashfloat.BackgroundColor3 = Color3.new(0, 0, 0)
	Cashfloat.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Cashfloat.Position = UDim2.new(0.031863749, 0, 0.0312201343, 0)
	Cashfloat.Size = UDim2.new(0, 135, 0, 26)
	Cashfloat.Font = Enum.Font.SourceSans
	Cashfloat.Text = "CashFloat"
	Cashfloat.TextColor3 = Color3.new(1, 1, 1)
	Cashfloat.TextSize = 18
	Cashfloat.MouseButton1Click:connect(function()

		if 	Onandoff_82.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_82.BackgroundColor3 = Color3.new(0, 1, 0)
			setsimulationradius(9e9,9e9) 
			local function zeroGrav(part)
				if part:FindFirstChild("BodyForce") then return end
				local temp = Instance.new("BodyForce")
				temp.Force = part:GetMass() * Vector3.new(0,workspace.Gravity,0)
				temp.Parent = part
			end

			for i,v in ipairs(workspace:GetDescendants()) do
				if v:IsA("Part") and v.Anchored == false then
					if not (v:IsDescendantOf(game.Players.LocalPlayer.Character)) then
						zeroGrav(v)
					end
				end
			end

			workspace.DescendantAdded:Connect(function(part)
				if part:IsA("Part") and part.Anchored == false then
					if not (part:IsDescendantOf(game.Players.LocalPlayer.Character)) then
						zeroGrav(part)
					end
				end
			end)
		else
			Onandoff_82.BackgroundColor3 = Color3.new(1, 0, 0)
			setsimulationradius(0,0) 
			local function zeroGrav(part)
				if part:FindFirstChild("BodyForce") then return end
				local temp = Instance.new("BodyForce")
				temp.Force = part:GetMass() * Vector3.new(0,workspace.Gravity,100)
				temp.Parent = part
			end

			for i,v in ipairs(workspace:GetDescendants()) do
				if v:IsA("Part") and v.Anchored == true then
					if not (v:IsDescendantOf(game.Players.LocalPlayer.Character)) then
						zeroGrav(v)
					end
				end
			end

			workspace.DescendantAdded:Connect(function(part)
				if part:IsA("Part") and part.Anchored == true then
					if not (part:IsDescendantOf(game.Players.LocalPlayer.Character)) then
						zeroGrav(part)
					end
				end
			end)
		end
	end)
	Onandoff_82.Name = "Onandoff"
	Onandoff_82.Parent = Cashfloat
	Onandoff_82.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_82.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_82.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_82.Size = UDim2.new(0, 135, 0, 15)

	Destroycash.Name = "Destroycash"
	Destroycash.Parent = CashModeScrollFrame
	Destroycash.BackgroundColor3 = Color3.new(0, 0, 0)
	Destroycash.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Destroycash.Position = UDim2.new(0.267193943, 0, 0.0309641957, 0)
	Destroycash.Size = UDim2.new(0, 135, 0, 26)
	Destroycash.Font = Enum.Font.SourceSans
	Destroycash.Text = "DestroyCash"
	Destroycash.TextColor3 = Color3.new(1, 1, 1)
	Destroycash.TextSize = 18
	Destroycash.MouseButton1Click:connect(function()
		if 		Onandoff_83.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_83.BackgroundColor3 = Color3.new(0, 1, 0)

			destroycashez = true
			while destroycashez == true do
				for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
					if v.Name == "MoneyDrop" then

						v:Destroy()
					end
				end		
				wait()
			end
		else
			Onandoff_83.BackgroundColor3 = Color3.new(1, 0, 0)
			destroycashez = false

		end
	end)

	Onandoff_83.Name = "Onandoff"
	Onandoff_83.Parent = Destroycash
	Onandoff_83.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_83.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_83.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_83.Size = UDim2.new(0, 135, 0, 15)

	CashAura.Name = "Cash Aura"
	CashAura.Parent = CashModeScrollFrame
	CashAura.BackgroundColor3 = Color3.new(0, 0, 0)
	CashAura.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	CashAura.Position = UDim2.new(0.503098488, 0, 0.0312201343, 0)
	CashAura.Size = UDim2.new(0, 135, 0, 26)
	CashAura.Font = Enum.Font.SourceSans
	CashAura.Text = "Cash Aura"
	CashAura.TextColor3 = Color3.new(1, 1, 1)
	CashAura.TextSize = 18
	CashAura.MouseButton1Click:connect(function()
		if 		Onandoff_84.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_84.BackgroundColor3 = Color3.new(0, 1, 0)
			aya = true
			Player = game.Players.LocalPlayer
			while aya == true do

				for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
					if v.Name == "MoneyDrop" then
						v.Position = Player.Character.HumanoidRootPart.Position + Vector3.new(math.random(2,4),math.random(2,5),math.random(2,7))

					end

				end

				wait()	
			end
		else
			Onandoff_84.BackgroundColor3 = Color3.new(1, 0, 0)
			aya = false

		end
	end)

	Onandoff_84.Name = "Onandoff"
	Onandoff_84.Parent = CashAura
	Onandoff_84.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_84.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_84.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_84.Size = UDim2.new(0, 135, 0, 15)

	CashHead.Name = "CashHead"
	CashHead.Parent = CashModeScrollFrame
	CashHead.BackgroundColor3 = Color3.new(0, 0, 0)
	CashHead.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	CashHead.Position = UDim2.new(0.739462137, 0, 0.0312201343, 0)
	CashHead.Size = UDim2.new(0, 135, 0, 26)
	CashHead.Font = Enum.Font.SourceSans
	CashHead.Text = "CashHead"
	CashHead.TextColor3 = Color3.new(1, 1, 1)
	CashHead.TextSize = 18
	CashHead.MouseButton1Click:connect(function()
		if 	Onandoff_85.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_85.BackgroundColor3 = Color3.new(0, 1, 0)
			cashohead = true
			while cashohead == true do
				for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
					if v.Name == "MoneyDrop" then

						v.CFrame = game.Players.LocalPlayer.Character.Head.CFrame
					end
				end		
				wait()
			end
		else
			Onandoff_85.BackgroundColor3 = Color3.new(1, 1, 1)
			cashohead = false
		end
	end)

	Onandoff_85.Name = "Onandoff"
	Onandoff_85.Parent = CashHead
	Onandoff_85.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_85.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_85.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_85.Size = UDim2.new(0, 135, 0, 15)

	CashEsp.Name = "CashEsp"
	CashEsp.Parent = CashModeScrollFrame
	CashEsp.BackgroundColor3 = Color3.new(0, 0, 0)
	CashEsp.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	CashEsp.Position = UDim2.new(0.739462137, 0, 0.10366331, 0)
	CashEsp.Size = UDim2.new(0, 135, 0, 26)
	CashEsp.Font = Enum.Font.SourceSans
	CashEsp.Text = "CashEsp"
	CashEsp.TextColor3 = Color3.new(1, 1, 1)
	CashEsp.TextSize = 18
	CashEsp.MouseButton1Click:connect(function()
		if		Onandoff_86.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_86.BackgroundColor3 = Color3.new(0, 1, 0)
			ezesp = true
			ESPholder = Instance.new("Folder", game.CoreGui)
			function cham(object)
				if object.Name == "MoneyDrop" then
					a = Instance.new("BoxHandleAdornment", ESPholder)
					a.Adornee = object
					a.AlwaysOnTop = true
					a.ZIndex = 10
					a.Size = object.Size
					a.Transparency = 0.3
					a.Color = object.BrickColor
					bill = object:WaitForChild("BillboardGui")
					bill.AlwaysOnTop = true
					bill.Size = UDim2.new(2, 10, 1, 5)
					spawn(function()
						while ezesp == true do
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
		else
			Onandoff_86.BackgroundColor3 = Color3.new(1, 0, 0)
			ESPholder:Destroy()
			a.AlwaysOnTop = false
			a.ZIndex = 0
			a.Transparency = 0
			bill.AlwaysOnTop = false
			bill.Size = UDim2.new(0, 0, 0, 0)
			ezesp = false
		end
	end)

	Onandoff_86.Name = "Onandoff"
	Onandoff_86.Parent = CashEsp
	Onandoff_86.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_86.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_86.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_86.Size = UDim2.new(0, 135, 0, 15)

	CashMouse.Name = "CashMouse"
	CashMouse.Parent = CashModeScrollFrame
	CashMouse.BackgroundColor3 = Color3.new(0, 0, 0)
	CashMouse.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	CashMouse.Position = UDim2.new(0.031863749, 0, 0.10366331, 0)
	CashMouse.Size = UDim2.new(0, 135, 0, 26)
	CashMouse.Font = Enum.Font.SourceSans
	CashMouse.Text = "CashMouse"
	CashMouse.TextColor3 = Color3.new(1, 1, 1)
	CashMouse.TextSize = 18
	CashMouse.MouseButton1Click:connect(function()
		if 	Onandoff_87.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_87.BackgroundColor3 = Color3.new(0, 1, 0)
			cashamousa = true
			local plr = game.Players.LocalPlayer
			local pro = plr:GetMouse()
			while cashamousa == true do
				for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
					if v.Name == "MoneyDrop" then
						v.CFrame = CFrame.new(pro.Hit.p)
					end
				end		
				wait()
			end
		else
			Onandoff_87.BackgroundColor3 = Color3.new(1, 0, 0)
			cashamousa = false

		end

	end)

	Onandoff_87.Name = "Onandoff"
	Onandoff_87.Parent = CashMouse
	Onandoff_87.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_87.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_87.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_87.Size = UDim2.new(0, 135, 0, 15)

	Cashfun.Name = "Cashfun"
	Cashfun.Parent = CashModeScrollFrame
	Cashfun.BackgroundColor3 = Color3.new(0, 0, 0)
	Cashfun.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Cashfun.Position = UDim2.new(0.267193943, 0, 0.103407376, 0)
	Cashfun.Size = UDim2.new(0, 135, 0, 26)
	Cashfun.Font = Enum.Font.SourceSans
	Cashfun.Text = "CashFun"
	Cashfun.TextColor3 = Color3.new(1, 1, 1)
	Cashfun.TextSize = 18
	Cashfun.MouseButton1Click:connect(function()
		if Cashfuntext.Text == "" then
			noti("Put Value On The Text Bellow")
		else
			local id = Cashfuntext.Text:match("%d+")
			game:GetService("Players").LocalPlayer.DataFolder.Currency.Value = id

		end
	end)

	Cashfuntext.Name = "Cashfun text"
	Cashfuntext.Parent = Cashfun
	Cashfuntext.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	Cashfuntext.BorderColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	Cashfuntext.Position = UDim2.new(0.00740740728, 0, 1, 0)
	Cashfuntext.Size = UDim2.new(0, 133, 0, 15)
	Cashfuntext.Font = Enum.Font.SourceSans
	Cashfuntext.PlaceholderColor3 = Color3.new(1, 1, 1)
	Cashfuntext.PlaceholderText = "Size Here"
	Cashfuntext.Text = ""
	Cashfuntext.TextColor3 = Color3.new(1, 1, 1)
	Cashfuntext.TextSize = 16

	CashControl.Name = "CashControl"
	CashControl.Parent = CashModeScrollFrame
	CashControl.BackgroundColor3 = Color3.new(0, 0, 0)
	CashControl.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	CashControl.Position = UDim2.new(0.503098488, 0, 0.10366331, 0)
	CashControl.Size = UDim2.new(0, 135, 0, 26)
	CashControl.Font = Enum.Font.SourceSans
	CashControl.Text = "CashControl"
	CashControl.TextColor3 = Color3.new(1, 1, 1)
	CashControl.TextSize = 18
	CashControl.MouseButton1Click:connect(function()
		if Onandoff_88.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_88.BackgroundColor3 = Color3.new(0, 1, 0)
			cahsassas = true
			for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do


				if v.Name == "MoneyDrop" then
					peniscock = v
					local groot = nil
					if cahsassas == true then
						game.Workspace.Camera.CameraSubject = peniscock

					end


					groot = peniscock

					local plr = game.Players.LocalPlayer
					mouse = plr:GetMouse()

					local plr = game.Players.LocalPlayer
					local torso = peniscock
					local flying = true
					local deb = true
					local ctrl = {f = 0, b = 0, l = 0, r = 0}
					local lastctrl = {f = 0, b = 0, l = 0, r = 0}
					local maxspeed = 30000
					local speed = 50

					if workspace:FindFirstChild("Core") then
						workspace.Core:Destroy()
					end

					function Fly()
						local bg = Instance.new("BodyGyro", peniscock)
						bg.P = 9e4
						bg.maxTorque = Vector3.new(0, 0, 0)
						bg.CFrame = peniscock.CFrame
						local bv = Instance.new("BodyVelocity", peniscock)
						bv.velocity = Vector3.new(0,0,0)
						bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
						repeat wait()

							if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
								speed = speed+.2
								if speed > maxspeed then
									speed = maxspeed
								end
							elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
								speed = speed-1
								if speed < 0 then
									speed = 0
								end
							end
							if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
								bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
								lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
							elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
								bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
							else
								bv.velocity = Vector3.new(0,0.1,0)
							end

						until not flying or cahsassas == false

						ctrl = {f = 0, b = 0, l = 0, r = 0}
						lastctrl = {f = 0, b = 0, l = 0, r = 0}
						speed = 0
						bg:Destroy()
						bv:Destroy()

					end
					mouse.KeyDown:connect(function(key)
						if key:lower() == "x" then
							if flying then flying = false
							else
								flying = true
								Fly()
							end
						elseif key:lower() == "w" then
							ctrl.f = 1
						elseif key:lower() == "s" then
							ctrl.b = -1
						elseif key:lower() == "a" then
							ctrl.l = -1
						elseif key:lower() == "d" then
							ctrl.r = 1
						end
					end)
					mouse.KeyUp:connect(function(key)
						if key:lower() == "w" then
							ctrl.f = 0
						elseif key:lower() == "s" then
							ctrl.b = 0
						elseif key:lower() == "a" then
							ctrl.l = 0
						elseif key:lower() == "d" then
							ctrl.r = 0
						elseif key:lower() == "r" then

						end
					end)
					Fly()
				end
			end

		else
			Onandoff_88.BackgroundColor3 = Color3.new(1, 0, 0)
			cahsassas = false
			game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid;

		end
	end)

	Onandoff_88.Name = "Onandoff"
	Onandoff_88.Parent = CashControl
	Onandoff_88.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_88.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_88.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_88.Size = UDim2.new(0, 135, 0, 15)

	Bypasscashcooldown.Name = "Bypasscashcooldown"
	Bypasscashcooldown.Parent = CashModeScrollFrame
	Bypasscashcooldown.BackgroundColor3 = Color3.new(0, 0, 0)
	Bypasscashcooldown.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Bypasscashcooldown.Position = UDim2.new(0.0303712487, 0, 0.178947404, 0)
	Bypasscashcooldown.Size = UDim2.new(0, 135, 0, 26)
	Bypasscashcooldown.Font = Enum.Font.SourceSans
	Bypasscashcooldown.Text = "BypassCashCooldown"
	Bypasscashcooldown.TextColor3 = Color3.new(1, 1, 1)
	Bypasscashcooldown.TextSize = 18
	Bypasscashcooldown.MouseButton1Click:connect(function()
		local fakecash = Instance.new("Part")
		local shit = require(game.ReplicatedStorage.MainModule).AddComma
		local Plr = game.Players.LocalPlayer
		do
			fakecash.Name = "MoneyDrop"
			fakecash.Size = Vector3.new(2, 0.4, 1.2)
			fakecash.BrickColor = BrickColor.new("Bright green")
			local stank = Instance.new("BillboardGui", fakecash)
			stank.Size = UDim2.new(2, 0, 1, 0)
			stank.ExtentsOffset = Vector3.new(0,3,0)
			stank.LightInfluence = 1
			local lab = Instance.new("TextLabel", stank)
			lab.Size = UDim2.new(1, 0, 1, 0)
			lab.TextColor3 = Color3.fromRGB(53, 173, 44)
			lab.TextSize = 50
			lab.Text = "$0"
			lab.Font = Enum.Font.Highway
			lab.BackgroundTransparency = 1
			lab.TextStrokeTransparency = 0
			lab.TextStrokeColor3 = Color3.fromRGB(66, 49, 35)
			lab.BorderSizePixel = 1
			lab.TextWrapped = true
			lab.TextScaled = true

			local faces = {Enum.NormalId.Top, Enum.NormalId.Bottom}
			for i= 1, 2 do
				local g = Instance.new("Decal", fakecash)
				g.Texture = "http://www.roblox.com/asset/?id=47682803"
				g.Face = faces[i]
			end
		end
		local cur = Plr.DataFolder.Currency
		cur.Changed:connect(function()
			(Plr.Character:FindFirstChild("Wallet") or Plr.Backpack:FindFirstChild("Wallet")).Handle.BillboardGui.TextLabel.Text = shit(cur.Value)
		end)

		local mt = getrawmetatable(game)
		setreadonly(mt, false)
		local old = mt.__namecall
		mt.__namecall = function(remote, call, amount, ...)
			if remote == game.ReplicatedStorage.MainEvent and call == "DropMoney" then
				cur.Value = cur.Value - tonumber(amount)
				local c = fakecash:Clone()
				c.Parent = game.Workspace.Ignored.Drop
				c.BillboardGui.Adornee = c
				c.BillboardGui.TextLabel.Text = "$"..shit(math.floor(tonumber(amount)*0.7))
				c.Position = Plr.Character.Head.CFrame.p + Vector3.new(0, 1, 0)
				spawn(function()
					Instance.new("ClickDetector", c).MouseClick:wait()
					c:Destroy()
					cur.Value = cur.Value + math.floor(tonumber(amount)*0.7)
				end)
				return print("dropped")
			end
			return old(remote, call, amount, ...)
		end
		setreadonly(mt, true)
	end)

	Onandoff_89.Name = "Onandoff"
	Onandoff_89.Parent = Bypasscashcooldown
	Onandoff_89.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_89.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_89.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_89.Size = UDim2.new(0, 135, 0, 15)

	AutoCollectCash.Name = "AutoCollectCash"
	AutoCollectCash.Parent = CashModeScrollFrame
	AutoCollectCash.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoCollectCash.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoCollectCash.Position = UDim2.new(0.739462137, 0, 0.177526951, 0)
	AutoCollectCash.Size = UDim2.new(0, 135, 0, 26)
	AutoCollectCash.Font = Enum.Font.SourceSans
	AutoCollectCash.Text = "AutoCollectCash"
	AutoCollectCash.TextColor3 = Color3.new(1, 1, 1)
	AutoCollectCash.TextSize = 18
	AutoCollectCash.MouseButton1Click:connect(function()
		if OnandoffAutoCollectCash.BackgroundColor3 == Color3.new(1, 0, 0) then
			OnandoffAutoCollectCash.BackgroundColor3 = Color3.new(0, 1, 0)
			collact = true
			noti("AutoCollect Enabled")
			while collact == true do
				for i, v in pairs(workspace.Ignored.Drop:GetChildren()) do
					if v.Name == "MoneyDrop" and (workspace.Players[game.Players.LocalPlayer.Name].HumanoidRootPart.Position - v.Position).Magnitude < 25
					then
						dineros = true
						fireclickdetector(v.ClickDetector)
						wait(0.7)
						dineros = false
					end
				end
				wait()
			end
		else
			OnandoffAutoCollectCash.BackgroundColor3 = Color3.new(1, 0, 0)
			collact = false
			noti("AutoCollect Disabled")

		end

	end)

	OnandoffAutoCollectCash.Name = "Onandoff"
	OnandoffAutoCollectCash.Parent = AutoCollectCash
	OnandoffAutoCollectCash.BackgroundColor3 = Color3.new(1, 0, 0)
	OnandoffAutoCollectCash.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	OnandoffAutoCollectCash.Position = UDim2.new(0, 0, 1, 0)
	OnandoffAutoCollectCash.Size = UDim2.new(0, 135, 0, 15)

	AutoDropCash.Name = "AutoDrop Cash"
	AutoDropCash.Parent = CashModeScrollFrame
	AutoDropCash.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoDropCash.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoDropCash.Position = UDim2.new(0.501904666, 0, 0.178691477, 0)
	AutoDropCash.Size = UDim2.new(0, 135, 0, 26)
	AutoDropCash.Font = Enum.Font.SourceSans
	AutoDropCash.Text = "AutoDrop Cash"
	AutoDropCash.TextColor3 = Color3.new(1, 1, 1)
	AutoDropCash.TextSize = 18
	AutoDropCash.MouseButton1Click:connect(function()

		cashdrop1 = false
		if AutoDropCash.TextColor3 == Color3.new(1, 1, 1) and cashdrop1 == false then
			AutoDropCash.TextColor3 = Color3.new(0, 1, 0)
			noti("AutoDrop Enabled")
			cashdrop1 = true
			repeat
				local id = autodropamout.Text:match("%d+")
				local A_1 = "DropMoney"
				local A_2 = id
				local Event = game:GetService("ReplicatedStorage").MainEvent
				Event:FireServer(A_1, A_2)
				wait()
			until cashdrop1 == false
		else
			AutoDropCash.TextColor3 = Color3.new(1, 1, 1)
			cashdrop1 = false
			noti("AutoDrop Disabled")

		end
	end)

	autodropamout.Name = "autodropamout"
	autodropamout.Parent = AutoDropCash
	autodropamout.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	autodropamout.BorderColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	autodropamout.Position = UDim2.new(0.00740740728, 0, 1, 0)
	autodropamout.Size = UDim2.new(0, 133, 0, 15)
	autodropamout.Font = Enum.Font.SourceSans
	autodropamout.PlaceholderColor3 = Color3.new(1, 1, 1)
	autodropamout.PlaceholderText = "Amout"
	autodropamout.Text = ""
	autodropamout.TextColor3 = Color3.new(1, 1, 1)
	autodropamout.TextSize = 16

	DropCash.Name = "Drop Cash"
	DropCash.Parent = CashModeScrollFrame
	DropCash.BackgroundColor3 = Color3.new(0, 0, 0)
	DropCash.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	DropCash.Position = UDim2.new(0.267193943, 0, 0.178691477, 0)
	DropCash.Size = UDim2.new(0, 135, 0, 26)
	DropCash.Font = Enum.Font.SourceSans
	DropCash.Text = "Drop Cash"
	DropCash.TextColor3 = Color3.new(1, 1, 1)
	DropCash.TextSize = 18
	DropCash.MouseButton1Click:connect(function()
		cashdrop = true
		local id = TargetTextbox.Text:match("%d+")
		local A_1 = "DropMoney"
		local A_2 = id
		local Event = game:GetService("ReplicatedStorage").MainEvent
		Event:FireServer(A_1, A_2)
		game.StarterGui:SetCore("SendNotification", {
			Title = "Kara";
			Text = " Dropping $"..id.." cash";
			Duration = 4;
		})
		local cor = coroutine.wrap(function()
			wait(10)
			cashdrop = false
		end)
		cor()
	end)

	dropcashamout.Name = "dropcash amout"
	dropcashamout.Parent = DropCash
	dropcashamout.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	dropcashamout.BorderColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	dropcashamout.Position = UDim2.new(0.00740740728, 0, 1, 0)
	dropcashamout.Size = UDim2.new(0, 133, 0, 15)
	dropcashamout.Font = Enum.Font.SourceSans
	dropcashamout.PlaceholderColor3 = Color3.new(1, 1, 1)
	dropcashamout.PlaceholderText = "Amout"
	dropcashamout.Text = ""
	dropcashamout.TextColor3 = Color3.new(1, 1, 1)
	dropcashamout.TextSize = 16



	AmmoScrollFrame.Name = "AmmoScrollFrame"
	AmmoScrollFrame.Parent = MainChild
	AmmoScrollFrame.Active = true
	AmmoScrollFrame.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	AmmoScrollFrame.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	AmmoScrollFrame.Position = UDim2.new(0.247117266, 0, 0.131311327, 0)
	AmmoScrollFrame.Size = UDim2.new(0, 605, 0, 295)
	AmmoScrollFrame.Visible = false
	AmmoScrollFrame.CanvasSize = UDim2.new(0, 0, 3, 0)
	local Plr = game.Players.LocalPlayer

	_20ShotGunAmmo60.Name = "20 [ShotGun Ammo] - $60"
	_20ShotGunAmmo60.Parent = AmmoScrollFrame
	_20ShotGunAmmo60.BackgroundColor3 = Color3.new(0, 0, 0)
	_20ShotGunAmmo60.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_20ShotGunAmmo60.Position = UDim2.new(0.0467397645, 0, 0.0319120102, 0)
	_20ShotGunAmmo60.Size = UDim2.new(0, 531, 0, 26)
	_20ShotGunAmmo60.Font = Enum.Font.SourceSans
	_20ShotGunAmmo60.Text = "20 [ShotGun Ammo] - $60"
	_20ShotGunAmmo60.TextColor3 = Color3.new(1, 1, 1)
	_20ShotGunAmmo60.TextSize = 18
	_20ShotGunAmmo60.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")
			if 	Onandoff_90.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_90.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzz1 = true


				for  i =  0, ezzzmanybuys do
					if ezzzz1 == true  then
						local lol = game.Workspace.Ignored.Shop["20 [Shotgun Ammo] - $60"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["20 [Shotgun Ammo] - $60"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end

				wait()
				Onandoff_90.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzz1 = false
			else	
				Onandoff_90.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzz1 = false



			end
		else
			Onandoff_90.BackgroundColor3  = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["20 [Shotgun Ammo] - $60"]
			game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)


		end
	end)

	Onandoff_90.Name = "Onandoff"
	Onandoff_90.Parent = _20ShotGunAmmo60
	Onandoff_90.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_90.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_90.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_90.Size = UDim2.new(0, 531, 0, 15)

	_80SMGAmmo60.Name = "80 [SMG Ammo] - $60"
	_80SMGAmmo60.Parent = AmmoScrollFrame
	_80SMGAmmo60.BackgroundColor3 = Color3.new(0, 0, 0)
	_80SMGAmmo60.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_80SMGAmmo60.Position = UDim2.new(0.0467397645, 0, 0.0934650376, 0)
	_80SMGAmmo60.Size = UDim2.new(0, 531, 0, 26)
	_80SMGAmmo60.Font = Enum.Font.SourceSans
	_80SMGAmmo60.Text = "80 [SMG Ammo] - $60"
	_80SMGAmmo60.TextColor3 = Color3.new(1, 1, 1)
	_80SMGAmmo60.TextSize = 18
	_80SMGAmmo60.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_91.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_91.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzz = true


				for  i =  0, ezzzmanybuys do
					if ezzzz == true  then
						local lol = game.Workspace.Ignored.Shop["80 [SMG Ammo] - $60"]

						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["80 [SMG Ammo] - $60"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end
				wait()
				Onandoff_91.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzz = false


			else	
				Onandoff_91.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzz = false



			end
		else
			Onandoff_91.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["80 [SMG Ammo] - $60"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["80 [SMG Ammo] - $60"].Head.CFrame
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_91.Name = "Onandoff"
	Onandoff_91.Parent = _80SMGAmmo60
	Onandoff_91.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_91.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_91.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_91.Size = UDim2.new(0, 531, 0, 15)

	_90AK47Ammo80.Name = "90 [AK47 Ammo] - $80"
	_90AK47Ammo80.Parent = AmmoScrollFrame
	_90AK47Ammo80.BackgroundColor3 = Color3.new(0, 0, 0)
	_90AK47Ammo80.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_90AK47Ammo80.Position = UDim2.new(0.0467397645, 0, 0.211836249, 0)
	_90AK47Ammo80.Size = UDim2.new(0, 531, 0, 26)
	_90AK47Ammo80.Font = Enum.Font.SourceSans
	_90AK47Ammo80.Text = "90 [AK47 Ammo] - $80"
	_90AK47Ammo80.TextColor3 = Color3.new(1, 1, 1)
	_90AK47Ammo80.TextSize = 18
	_90AK47Ammo80.MouseButton1Click:connect(function()

		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_92.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_92.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzz133 = true


				for  i =  0, ezzzmanybuys do
					if ezzzz133 == true  then
						local lol = game.Workspace.Ignored.Shop["90 [AK47 Ammo] - $80"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["90 [AK47 Ammo] - $80"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end

				wait()
				Onandoff_92.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzz133 = false
			else	
				Onandoff_92.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzz133 = false



			end

		else
			Onandoff_92.BackgroundColor3 = Color3.new(1, 0, 0)


			local lol = game.Workspace.Ignored.Shop["90 [AK47 Ammo] - $80"]
			game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_92.Name = "Onandoff"
	Onandoff_92.Parent = _90AK47Ammo80
	Onandoff_92.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_92.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_92.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_92.Size = UDim2.new(0, 531, 0, 15)

	_25SilencerAmmo50.Name = "25 [Silencer Ammo] - $50"
	_25SilencerAmmo50.Parent = AmmoScrollFrame
	_25SilencerAmmo50.BackgroundColor3 = Color3.new(0, 0, 0)
	_25SilencerAmmo50.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_25SilencerAmmo50.Position = UDim2.new(0.0467397645, 0, 0.155018076, 0)
	_25SilencerAmmo50.Size = UDim2.new(0, 531, 0, 26)
	_25SilencerAmmo50.Font = Enum.Font.SourceSans
	_25SilencerAmmo50.Text = "25 [Silencer Ammo] - $50"
	_25SilencerAmmo50.TextColor3 = Color3.new(1, 1, 1)
	_25SilencerAmmo50.TextSize = 18
	_25SilencerAmmo50.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_93.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_93.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzz12 = true


				for  i =  0, ezzzmanybuys do
					if ezzzz12 == true  then
						local lol = game.Workspace.Ignored.Shop["25 [Silencer Ammo] - $50"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["25 [Silencer Ammo] - $50"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end

				wait()
				Onandoff_93.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzz2 = false

			else	
				Onandoff_93.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzz2 = false



			end
		else
			Onandoff_93.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["25 [Silencer Ammo] - $50"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["25 [Silencer Ammo] - $50"].Head.CFrame
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_93.Name = "Onandoff"
	Onandoff_93.Parent = _25SilencerAmmo50
	Onandoff_93.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_93.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_93.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_93.Size = UDim2.new(0, 531, 0, 15)

	_25GlockAmmo60.Name = "25 [Glock Ammo] - $60"
	_25GlockAmmo60.Parent = AmmoScrollFrame
	_25GlockAmmo60.BackgroundColor3 = Color3.new(0, 0, 0)
	_25GlockAmmo60.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_25GlockAmmo60.Position = UDim2.new(0.0467397645, 0, 0.441002935, 0)
	_25GlockAmmo60.Size = UDim2.new(0, 531, 0, 26)
	_25GlockAmmo60.Font = Enum.Font.SourceSans
	_25GlockAmmo60.Text = "25 [Glock Ammo] - $60"
	_25GlockAmmo60.TextColor3 = Color3.new(1, 1, 1)
	_25GlockAmmo60.TextSize = 18
	_25GlockAmmo60.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_94.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_94.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee222 = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee222 == true  then
						local lol = game.Workspace.Ignored.Shop["25 [Glock Ammo] - $60"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["25 [Glock Ammo] - $60"].Head.CFrame

						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end

				wait()
				Onandoff_94.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee222 = false
			else	
				Onandoff_94.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee222 = false



			end
		else
			Onandoff_94.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["25 [Glock Ammo] - $60"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["25 [Glock Ammo] - $60"].Head.CFrame
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_94.Name = "Onandoff"
	Onandoff_94.Parent = _25GlockAmmo60
	Onandoff_94.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_94.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_94.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_94.Size = UDim2.new(0, 531, 0, 15)

	_20TacticalShotgunAmmo60.Name = "20 [TacticalShotgun Ammo] - $60"
	_20TacticalShotgunAmmo60.Parent = AmmoScrollFrame
	_20TacticalShotgunAmmo60.BackgroundColor3 = Color3.new(0, 0, 0)
	_20TacticalShotgunAmmo60.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_20TacticalShotgunAmmo60.Position = UDim2.new(0.0467397645, 0, 0.382290751, 0)
	_20TacticalShotgunAmmo60.Size = UDim2.new(0, 531, 0, 26)
	_20TacticalShotgunAmmo60.Font = Enum.Font.SourceSans
	_20TacticalShotgunAmmo60.Text = "20 [TacticalShotgun Ammo] - $60"
	_20TacticalShotgunAmmo60.TextColor3 = Color3.new(1, 1, 1)
	_20TacticalShotgunAmmo60.TextSize = 18
	_20TacticalShotgunAmmo60.MouseButton1Click:connect(function()

		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_95.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_95.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee2232 = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee2232 == true  then
						local lol = game.Workspace.Ignored.Shop["20 [TacticalShotgun Ammo] - $60"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["20 [TacticalShotgun Ammo] - $60"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end

				wait()
				Onandoff_95.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee2232 = false
			else	
				Onandoff_95.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee2232 = false



			end
		else
			Onandoff_95.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["20 [TacticalShotgun Ammo] - $60"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["20 [TacticalShotgun Ammo] - $60"].Head.CFrame
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_95.Name = "Onandoff"
	Onandoff_95.Parent = _20TacticalShotgunAmmo60
	Onandoff_95.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_95.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_95.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_95.Size = UDim2.new(0, 531, 0, 15)

	_120P90Ammo60.Name = "120 [P90 Ammo] - $60"
	_120P90Ammo60.Parent = AmmoScrollFrame
	_120P90Ammo60.BackgroundColor3 = Color3.new(0, 0, 0)
	_120P90Ammo60.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_120P90Ammo60.Position = UDim2.new(0.0467397645, 0, 0.324999064, 0)
	_120P90Ammo60.Size = UDim2.new(0, 531, 0, 26)
	_120P90Ammo60.Font = Enum.Font.SourceSans
	_120P90Ammo60.Text = "120 [P90 Ammo] - $60"
	_120P90Ammo60.TextColor3 = Color3.new(1, 1, 1)
	_120P90Ammo60.TextSize = 18
	_120P90Ammo60.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_96.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_96.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee22322 = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee22322 == true  then
						local lol = game.Workspace.Ignored.Shop["120 [P90 Ammo] - $60"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["120 [P90 Ammo] - $60"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end

				wait()
				Onandoff_96.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee22322 = false

			else	
				Onandoff_96.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee22322 = false



			end
		else
			Onandoff_96.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["120 [P90 Ammo] - $60"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["120 [P90 Ammo] - $60"].Head.CFrame
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_96.Name = "Onandoff"
	Onandoff_96.Parent = _120P90Ammo60
	Onandoff_96.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_96.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_96.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_96.Size = UDim2.new(0, 531, 0, 15)

	_100ARAmmo75.Name = "100 [AR Ammo] - $75"
	_100ARAmmo75.Parent = AmmoScrollFrame
	_100ARAmmo75.BackgroundColor3 = Color3.new(0, 0, 0)
	_100ARAmmo75.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_100ARAmmo75.Position = UDim2.new(0.0467397645, 0, 0.270548314, 0)
	_100ARAmmo75.Size = UDim2.new(0, 531, 0, 26)
	_100ARAmmo75.Font = Enum.Font.SourceSans
	_100ARAmmo75.Text = "100 [AR Ammo] - $75"
	_100ARAmmo75.TextColor3 = Color3.new(1, 1, 1)
	_100ARAmmo75.TextSize = 18
	_100ARAmmo75.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_97.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_97.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee222322 = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee222322 == true  then
						local lol = game.Workspace.Ignored.Shop["100 [AR Ammo] - $75"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["100 [AR Ammo] - $75"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end

				wait()
				Onandoff_97.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee222322 = false

			else	
				Onandoff_97.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee222322 = false



			end
		else
			Onandoff_97.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["100 [AR Ammo] - $75"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["100 [AR Ammo] - $75"].Head.CFrame
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_97.Name = "Onandoff"
	Onandoff_97.Parent = _100ARAmmo75
	Onandoff_97.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_97.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_97.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_97.Size = UDim2.new(0, 531, 0, 15)

	_120SilencerARAmmo75.Name = "120 [SilencerAR Ammo] - $75"
	_120SilencerARAmmo75.Parent = AmmoScrollFrame
	_120SilencerARAmmo75.BackgroundColor3 = Color3.new(0, 0, 0)
	_120SilencerARAmmo75.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_120SilencerARAmmo75.Position = UDim2.new(0.0467397645, 0, 0.496874183, 0)
	_120SilencerARAmmo75.Size = UDim2.new(0, 531, 0, 26)
	_120SilencerARAmmo75.Font = Enum.Font.SourceSans
	_120SilencerARAmmo75.Text = "120 [SilencerAR Ammo] - $75"
	_120SilencerARAmmo75.TextColor3 = Color3.new(1, 1, 1)
	_120SilencerARAmmo75.TextSize = 18
	_120SilencerARAmmo75.MouseButton1Click:connect(function()

		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_98.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_98.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzz12 = true


				for  i =  0, ezzzmanybuys do
					if ezzzz12 == true  then
						local lol = game.Workspace.Ignored.Shop["25 [Silencer Ammo] - $50"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["25 [Silencer Ammo] - $50"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end

				wait()
				Onandoff_98.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzz2 = false

			else	
				Onandoff_98.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzz2 = false



			end
		else
			Onandoff_98.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["25 [Silencer Ammo] - $50"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["25 [Silencer Ammo] - $50"].Head.CFrame
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_98.Name = "Onandoff"
	Onandoff_98.Parent = _120SilencerARAmmo75
	Onandoff_98.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_98.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_98.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_98.Size = UDim2.new(0, 531, 0, 15)

	_100DrumGunAmmo200.Name = "100 [DrumGun Ammo] - $200"
	_100DrumGunAmmo200.Parent = AmmoScrollFrame
	_100DrumGunAmmo200.BackgroundColor3 = Color3.new(0, 0, 0)
	_100DrumGunAmmo200.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_100DrumGunAmmo200.Position = UDim2.new(0.0467397645, 0, 0.549904466, 0)
	_100DrumGunAmmo200.Size = UDim2.new(0, 531, 0, 26)
	_100DrumGunAmmo200.Font = Enum.Font.SourceSans
	_100DrumGunAmmo200.Text = "100 [DrumGun Ammo] - $200"
	_100DrumGunAmmo200.TextColor3 = Color3.new(1, 1, 1)
	_100DrumGunAmmo200.TextSize = 18
	_100DrumGunAmmo200.MouseButton1Click:connect(function()

		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_99.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_99.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee == true  then
						local lol = game.Workspace.Ignored.Shop["100 [DrumGun Ammo] - $200"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["100 [DrumGun Ammo] - $200"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end
				wait()
				Onandoff_99.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee = false

			else	
				Onandoff_99.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee = false



			end
		else
			Onandoff_99.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["100 [DrumGun Ammo] - $200"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["100 [DrumGun Ammo] - $200"].Head.CFrame
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_99.Name = "Onandoff"
	Onandoff_99.Parent = _100DrumGunAmmo200
	Onandoff_99.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_99.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_99.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_99.Size = UDim2.new(0, 531, 0, 15)

	_140FlamethrowerAmmo1550.Name = "140 [Flamethrower Ammo] - $1550"
	_140FlamethrowerAmmo1550.Parent = AmmoScrollFrame
	_140FlamethrowerAmmo1550.BackgroundColor3 = Color3.new(0, 0, 0)
	_140FlamethrowerAmmo1550.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_140FlamethrowerAmmo1550.Position = UDim2.new(0.0467397645, 0, 0.603881776, 0)
	_140FlamethrowerAmmo1550.Size = UDim2.new(0, 531, 0, 26)
	_140FlamethrowerAmmo1550.Font = Enum.Font.SourceSans
	_140FlamethrowerAmmo1550.Text = "140 [Flamethrower Ammo] - $1550"
	_140FlamethrowerAmmo1550.TextColor3 = Color3.new(1, 1, 1)
	_140FlamethrowerAmmo1550.TextSize = 18
	_140FlamethrowerAmmo1550.MouseButton1Click:connect(function()

		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_100.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_100.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee22222222322 = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee22222222322 == true  then
						local lol = game.Workspace.Ignored.Shop["140 [Flamethrower Ammo] - $1550"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["140 [Flamethrower Ammo] - $1550"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end
				wait()
				Onandoff_100.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee22222222322 = false


			else	
				Onandoff_100.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee22222222322 = false



			end
		else
			Onandoff_100.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["140 [Flamethrower Ammo] - $1550"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["140 [Flamethrower Ammo] - $1550"].Head.CFrame

			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_100.Name = "Onandoff"
	Onandoff_100.Parent = _140FlamethrowerAmmo1550
	Onandoff_100.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_100.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_100.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_100.Size = UDim2.new(0, 531, 0, 15)

	_5RPGAmmo1000.Name = "5 [RPG Ammo] - $1000"
	_5RPGAmmo1000.Parent = AmmoScrollFrame
	_5RPGAmmo1000.BackgroundColor3 = Color3.new(0, 0, 0)
	_5RPGAmmo1000.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_5RPGAmmo1000.Position = UDim2.new(0.0467397645, 0, 0.661646962, 0)
	_5RPGAmmo1000.Size = UDim2.new(0, 531, 0, 26)
	_5RPGAmmo1000.Font = Enum.Font.SourceSans
	_5RPGAmmo1000.Text = "5 [RPG Ammo] - $1000"
	_5RPGAmmo1000.TextColor3 = Color3.new(1, 1, 1)
	_5RPGAmmo1000.TextSize = 18
	_5RPGAmmo1000.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_101.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_101.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee2222322 = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee2222322 == true  then
						local lol = game.Workspace.Ignored.Shop["5 [RPG Ammo] - $1000"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["5 [RPG Ammo] - $1000"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end
				wait()
				Onandoff_101.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee2222322 = false

			else	
				Onandoff_101.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee2222322 = false



			end
		else
			Onandoff_101.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["5 [RPG Ammo] - $1000"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["5 [RPG Ammo] - $1000"].Head.CFrame
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_101.Name = "Onandoff"
	Onandoff_101.Parent = _5RPGAmmo1000
	Onandoff_101.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_101.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_101.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_101.Size = UDim2.new(0, 531, 0, 15)


	_12RevolverAmmo75.Name = "12 [Revolver Ammo] - $75"
	_12RevolverAmmo75.Parent = AmmoScrollFrame
	_12RevolverAmmo75.BackgroundColor3 = Color3.new(0, 0, 0)
	_12RevolverAmmo75.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_12RevolverAmmo75.Position = UDim2.new(0.0467397645, 0, 0.82736665, 0)
	_12RevolverAmmo75.Size = UDim2.new(0, 531, 0, 26)
	_12RevolverAmmo75.Font = Enum.Font.SourceSans
	_12RevolverAmmo75.Text = "12 [Revolver Ammo] - $75"
	_12RevolverAmmo75.TextColor3 = Color3.new(1, 1, 1)
	_12RevolverAmmo75.TextSize = 18
	_12RevolverAmmo75.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_103.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_103.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee222222223222 = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee222222223222 == true  then
						local lol = game.Workspace.Ignored.Shop["12 [Revolver Ammo] - $75"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["12 [Revolver Ammo] - $75"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end
				wait()
				Onandoff_103.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee222222223222 = false
			else	
				Onandoff_103.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee222222223222 = false



			end
		else
			Onandoff_103.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["12 [Revolver Ammo] - $75"]
			Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["12 [Revolver Ammo] - $75"].Head.CFrame

			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_103.Name = "Onandoff"
	Onandoff_103.Parent = _12RevolverAmmo75
	Onandoff_103.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_103.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_103.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_103.Size = UDim2.new(0, 531, 0, 15)

	_1Flashbang750.Name = "1 [Flashbang]  - $750"
	_1Flashbang750.Parent = AmmoScrollFrame
	_1Flashbang750.BackgroundColor3 = Color3.new(0, 0, 0)
	_1Flashbang750.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_1Flashbang750.Position = UDim2.new(0.0467397645, 0, 0.769601464, 0)
	_1Flashbang750.Size = UDim2.new(0, 531, 0, 26)
	_1Flashbang750.Font = Enum.Font.SourceSans
	_1Flashbang750.Text = "1 [Flashbang]  - $750"
	_1Flashbang750.TextColor3 = Color3.new(1, 1, 1)
	_1Flashbang750.TextSize = 18
	_1Flashbang750.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_104.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_104.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee2222322223222 = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee2222322223222 == true  then
						local lol = game.Workspace.Ignored.Shop["[Flashbang] - $550"]
						game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
						wait(0.50)

						fireclickdetector(lol.ClickDetector,4)
						wait(0.50)
						game.Players.LocalPlayer.Backpack["[Flashbang]"].Parent = game.Players.LocalPlayer.Character


					end


				end


			else	
				Onandoff_104.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee2222322223222 = false



			end
			wait(.3)
			Onandoff_104.BackgroundColor3 = Color3.new(1, 0, 0)
			ezzzzee2222322223222 = false
		else
			Onandoff_104.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["[Flashbang] - $550"]
			game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_104.Name = "Onandoff"
	Onandoff_104.Parent = _1Flashbang750
	Onandoff_104.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_104.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_104.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_104.Size = UDim2.new(0, 531, 0, 15)

	_1Grenade700.Name = "1 [Grenade] - $700"
	_1Grenade700.Parent = AmmoScrollFrame
	_1Grenade700.BackgroundColor3 = Color3.new(0, 0, 0)
	_1Grenade700.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_1Grenade700.Position = UDim2.new(0.0467397645, 0, 0.715624154, 0)
	_1Grenade700.Size = UDim2.new(0, 531, 0, 26)
	_1Grenade700.Font = Enum.Font.SourceSans
	_1Grenade700.Text = "1 [Grenade] - $700"
	_1Grenade700.TextColor3 = Color3.new(1, 1, 1)
	_1Grenade700.TextSize = 18
	_1Grenade700.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_105.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_105.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee22222322 = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee22222322 == true  then
						local lol = game.Workspace.Ignored.Shop["[Grenade] - $700"]
						game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end
				wait()
				Onandoff_105.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee22222322 = false

			else	
				Onandoff_105.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee22222322 = false



			end
		else
			Onandoff_105.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["[Grenade] - $700"]
			game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_105.Name = "Onandoff"
	Onandoff_105.Parent = _1Grenade700
	Onandoff_105.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_105.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_105.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_105.Size = UDim2.new(0, 531, 0, 15)

	_200LMGAmmo300.Name = "200 [LMG Ammo] - $300"
	_200LMGAmmo300.Parent = AmmoScrollFrame
	_200LMGAmmo300.BackgroundColor3 = Color3.new(0, 0, 0)
	_200LMGAmmo300.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	_200LMGAmmo300.Position = UDim2.new(0.0467397645, 0, 0.887025714, 0)
	_200LMGAmmo300.Size = UDim2.new(0, 531, 0, 26)
	_200LMGAmmo300.Font = Enum.Font.SourceSans
	_200LMGAmmo300.Text = "200 [LMG Ammo] - $300"
	_200LMGAmmo300.TextColor3 = Color3.new(1, 1, 1)
	_200LMGAmmo300.TextSize = 18
	_200LMGAmmo300.MouseButton1Click:connect(function()
		if 	TimesBuy.Text:match("%d+") then
			local ezzzmanybuys = TimesBuy.Text:match("%d+")

			if 	Onandoff_106.BackgroundColor3 == Color3.new(1, 0, 0) then
				Onandoff_106.BackgroundColor3 = Color3.new(0, 1, 0)
				ezzzzee2222222322 = true


				for  i =  0, ezzzmanybuys do
					if ezzzzee2222222322 == true  then
						local lol = game.Workspace.Ignored.Shop["200 [LMG Ammo] - $300"]
						Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["200 [LMG Ammo] - $300"].Head.CFrame
						wait(0.50)
						fireclickdetector(lol.ClickDetector,4)

					end


				end

				wait()
				Onandoff_106.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee2222222322 = false

			else	
				Onandoff_106.BackgroundColor3 = Color3.new(1, 0, 0)
				ezzzzee2222222322 = false



			end
		else
			Onandoff_106.BackgroundColor3 = Color3.new(1, 0, 0)

			local lol = game.Workspace.Ignored.Shop["200 [LMG Ammo] - $300"]
			game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
			wait(0.40)
			fireclickdetector(lol.ClickDetector,4)

		end
	end)

	Onandoff_106.Name = "Onandoff"
	Onandoff_106.Parent = _200LMGAmmo300
	Onandoff_106.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_106.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_106.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_106.Size = UDim2.new(0, 531, 0, 15)

	TeleportsScrollFrame.Name = "TeleportsScrollFrame"
	TeleportsScrollFrame.Parent = MainChild
	TeleportsScrollFrame.Active = true
	TeleportsScrollFrame.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	TeleportsScrollFrame.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	TeleportsScrollFrame.Position = UDim2.new(0.247117221, 0, 0.0254765432, 0)
	TeleportsScrollFrame.Size = UDim2.new(0, 605, 0, 333)
	TeleportsScrollFrame.Visible = false

	Teleport.Name = "Teleport"
	Teleport.Parent = TeleportsScrollFrame
	Teleport.BackgroundColor3 = Color3.new(0, 0, 0)
	Teleport.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Teleport.Position = UDim2.new(0.0120290387, 0, 0.0212769527, 0)
	Teleport.Size = UDim2.new(0, 135, 0, 26)
	Teleport.Font = Enum.Font.SourceSans
	Teleport.Text = "Teleport"
	Teleport.TextColor3 = Color3.new(1, 1, 1)
	Teleport.TextSize = 18
	Teleport.MouseButton1Click:connect(function()
		if TextBox.Text == "sewer" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(112.622, -26.212, -277.321)

		elseif TextBox.Text == "Sewer" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(112.622, -26.212, -277.321)

		elseif TextBox.Text == "SEWER" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(112.622, -26.212, -277.321)
		elseif TextBox.Text == "bank" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-470.668, 20.620, -285.169)

		elseif TextBox.Text == "Bank" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-470.668, 20.620, -285.169)

		elseif TextBox.Text == "BANK" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-470.668, 20.620, -285.169)

		elseif TextBox.Text == "prison" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-294.162, 22.644, -111.716)

		elseif TextBox.Text == "Prison" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-294.162, 22.644, -111.716)

		elseif TextBox.Text == "PRISON" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-294.162, 22.644, -111.716)
		elseif TextBox.Text == "ufo" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.565, 142.926, -690.33)

		elseif TextBox.Text == "Ufo" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.565, 142.926, -690.33)

		elseif TextBox.Text == "UFO" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.565, 142.926, -690.33)
		elseif TextBox.Text == "boxing" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)

		elseif TextBox.Text == "Boxing" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)

		elseif TextBox.Text == "BOXING" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)

		elseif TextBox.Text == "box" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)

		elseif TextBox.Text == "Box" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)

		elseif TextBox.Text == "BOX" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)
		elseif TextBox.Text == "gun" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-582, 7.172, -739.015)

		elseif TextBox.Text == "GUN" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-582, 7.172, -739.015)

		elseif TextBox.Text == "Gun" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-582, 7.172, -739.015)
		elseif TextBox.Text == "admin" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
		elseif TextBox.Text == "Admin" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)

		elseif TextBox.Text == "ADMIN" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)
		elseif TextBox.Text == "fitness" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-75.795, 23.701, -633.72)

		elseif TextBox.Text == "Fitness" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-75.795, 23.701, -633.72)

		elseif TextBox.Text == "FITNESS" then
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-75.795, 23.701, -633.72)

		end
	end)

	TextBox.Parent = Teleport
	TextBox.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	TextBox.BorderColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	TextBox.Position = UDim2.new(0.00740740728, 0, 1, 0)
	TextBox.Size = UDim2.new(0, 133, 0, 15)
	TextBox.Font = Enum.Font.SourceSans
	TextBox.PlaceholderColor3 = Color3.new(1, 1, 1)
	TextBox.PlaceholderText = "Map Here"
	TextBox.Text = ""
	TextBox.TextColor3 = Color3.new(1, 1, 1)
	TextBox.TextSize = 16

	Sewer.Name = "Sewer"
	Sewer.Parent = TeleportsScrollFrame
	Sewer.BackgroundColor3 = Color3.new(0, 0, 0)
	Sewer.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Sewer.Position = UDim2.new(0.261615813, 0, 0.0212769527, 0)
	Sewer.Size = UDim2.new(0, 135, 0, 26)
	Sewer.Font = Enum.Font.SourceSans
	Sewer.Text = "Sewer"
	Sewer.TextColor3 = Color3.new(1, 1, 1)
	Sewer.TextSize = 18
	Sewer.MouseButton1Click:connect(function()
		game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(112.622, -26.212, -277.321)

	end)

	Onandoff_107.Name = "Onandoff"
	Onandoff_107.Parent = Sewer
	Onandoff_107.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_107.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_107.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_107.Size = UDim2.new(0, 135, 0, 15)

	Bank.Name = "Bank"
	Bank.Parent = TeleportsScrollFrame
	Bank.BackgroundColor3 = Color3.new(0, 0, 0)
	Bank.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Bank.Position = UDim2.new(0.506243885, 0, 0.0212769527, 0)
	Bank.Size = UDim2.new(0, 135, 0, 26)
	Bank.Font = Enum.Font.SourceSans
	Bank.Text = "Bank"
	Bank.TextColor3 = Color3.new(1, 1, 1)
	Bank.TextSize = 18
	Bank.MouseButton1Click:connect(function()
		game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-470.668, 20.620, -285.169)

	end)

	Fitness.Name = "Fitness"
	Fitness.Parent = TeleportsScrollFrame
	Fitness.BackgroundColor3 = Color3.new(0, 0, 0)
	Fitness.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Fitness.Position = UDim2.new(0.750872016, 0, 0.0212769527, 0)
	Fitness.Size = UDim2.new(0, 135, 0, 26)
	Fitness.Font = Enum.Font.SourceSans
	Fitness.Text = "FitNess"
	Fitness.TextColor3 = Color3.new(1, 1, 1)
	Fitness.TextSize = 18
	Fitness.MouseButton1Click:connect(function()
		game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-75.795, 23.701, -633.72)

	end)

	Onandoff_108.Name = "Onandoff"
	Onandoff_108.Parent = Fitness
	Onandoff_108.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_108.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_108.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_108.Size = UDim2.new(0, 135, 0, 15)

	Boxing.Name = "Boxing"
	Boxing.Parent = TeleportsScrollFrame
	Boxing.BackgroundColor3 = Color3.new(0, 0, 0)
	Boxing.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Boxing.Position = UDim2.new(0.00872325897, 0, 0.103663318, 0)
	Boxing.Size = UDim2.new(0, 135, 0, 26)
	Boxing.Font = Enum.Font.SourceSans
	Boxing.Text = "Boxing"
	Boxing.TextColor3 = Color3.new(1, 1, 1)
	Boxing.TextSize = 18
	Boxing.MouseButton1Click:connect(function()
		game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-236.006, 23.151, -1120.531)

	end)

	Onandoff_109.Name = "Onandoff"
	Onandoff_109.Parent = Boxing
	Onandoff_109.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_109.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_109.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_109.Size = UDim2.new(0, 135, 0, 15)

	Ufo.Name = "Ufo"
	Ufo.Parent = TeleportsScrollFrame
	Ufo.BackgroundColor3 = Color3.new(0, 0, 0)
	Ufo.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Ufo.Position = UDim2.new(0.261615813, 0, 0.103663318, 0)
	Ufo.Size = UDim2.new(0, 135, 0, 26)
	Ufo.Font = Enum.Font.SourceSans
	Ufo.Text = "Ufo"
	Ufo.TextColor3 = Color3.new(1, 1, 1)
	Ufo.TextSize = 18
	Ufo.MouseButton1Click:connect(function()
		game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.565, 142.926, -690.33)

	end)

	Onandoff_110.Name = "Onandoff"
	Onandoff_110.Parent = Ufo
	Onandoff_110.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_110.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_110.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_110.Size = UDim2.new(0, 135, 0, 15)

	Prison.Name = "Prison"
	Prison.Parent = TeleportsScrollFrame
	Prison.BackgroundColor3 = Color3.new(0, 0, 0)
	Prison.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Prison.Position = UDim2.new(0.506243944, 0, 0.103663318, 0)
	Prison.Size = UDim2.new(0, 135, 0, 26)
	Prison.Font = Enum.Font.SourceSans
	Prison.Text = "Prison"
	Prison.TextColor3 = Color3.new(1, 1, 1)
	Prison.TextSize = 18
	Prison.MouseButton1Click:connect(function()
		game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-294.162, 22.644, -111.716)

	end)

	Onandoff_111.Name = "Onandoff"
	Onandoff_111.Parent = Prison
	Onandoff_111.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_111.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_111.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_111.Size = UDim2.new(0, 135, 0, 15)

	Gun.Name = "Gun"
	Gun.Parent = TeleportsScrollFrame
	Gun.BackgroundColor3 = Color3.new(0, 0, 0)
	Gun.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Gun.Position = UDim2.new(0.750872016, 0, 0.103663318, 0)
	Gun.Size = UDim2.new(0, 135, 0, 26)
	Gun.Font = Enum.Font.SourceSans
	Gun.Text = "Gun"
	Gun.TextColor3 = Color3.new(1, 1, 1)
	Gun.TextSize = 18
	Gun.MouseButton1Click:connect(function()
		game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-582, 7.172, -739.015)

	end)

	Onandoff_112.Name = "Onandoff"
	Onandoff_112.Parent = Gun
	Onandoff_112.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_112.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_112.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_112.Size = UDim2.new(0, 135, 0, 15)

	Admin.Name = "Admin"
	Admin.Parent = TeleportsScrollFrame
	Admin.BackgroundColor3 = Color3.new(0, 0, 0)
	Admin.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Admin.Position = UDim2.new(0.00872325897, 0, 0.188890591, 0)
	Admin.Size = UDim2.new(0, 135, 0, 26)
	Admin.Font = Enum.Font.SourceSans
	Admin.Text = "Admin"
	Admin.TextColor3 = Color3.new(1, 1, 1)
	Admin.TextSize = 18
	Admin.MouseButton1Click:connect(function()
		game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.895, -37.642, -885.8)

	end)

	Onandoff_113.Name = "Onandoff"
	Onandoff_113.Parent = Admin
	Onandoff_113.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_113.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_113.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_113.Size = UDim2.new(0, 135, 0, 15)

	printpos.Name = "print pos"
	printpos.Parent = TeleportsScrollFrame
	printpos.BackgroundColor3 = Color3.new(0, 0, 0)
	printpos.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	printpos.Position = UDim2.new(0.261615783, 0, 0.187688515, 0)
	printpos.Size = UDim2.new(0, 135, 0, 26)
	printpos.Font = Enum.Font.SourceSans
	printpos.Text = "Print Pos"
	printpos.TextColor3 = Color3.new(1, 1, 1)
	printpos.TextSize = 18
	printpos.MouseButton1Click:connect(function()
		print(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)
		local hums = game.Players.LocalPlayer.Character.HumanoidRootPart
		noti("."..hums.Position)
	end)

	Onandoff_114.Name = "Onandoff"
	Onandoff_114.Parent = printpos
	Onandoff_114.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_114.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_114.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_114.Size = UDim2.new(0, 135, 0, 15)

	BombMap.Visible = false
	BombMap.Name = "BombMap"
	BombMap.Parent = TeleportsScrollFrame
	BombMap.BackgroundColor3 = Color3.new(0, 0, 0)
	BombMap.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	BombMap.Position = UDim2.new(0.506243885, 0, 0.188890591, 0)
	BombMap.Size = UDim2.new(0, 135, 0, 26)
	BombMap.Font = Enum.Font.SourceSans
	BombMap.Text = "Bomb Map"
	BombMap.TextColor3 = Color3.new(1, 1, 1)
	BombMap.TextSize = 18
	BombMap.MouseButton1Click:connect(function()


		function activebomb()

			local LocalPlayer = game:GetService("Players").LocalPlayer
			local char = LocalPlayer.Character
			local Ignored = game.workspace.Ignored
			local backpack = LocalPlayer.Backpack
			local x = 0
			local Grenade = "[Grenade]"
			local DroppedGrenade = "Handle"

			for i,v in pairs(char:GetChildren()) do
				if v.Name == Grenade then
					v:Activate()
					v:Activate()
					v:Activate()
					v:Activate()

				end
			end
		end
		function bomb(place,active)
			for i = 0,3 do
				local lol = game.Workspace.Ignored.Shop["[Grenade] - $700"]
				Plr.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop["[Grenade] - $700"].Head.CFrame
				wait(0.25)
				fireclickdetector(lol.ClickDetector,4)
			end

		end
		if string.find(BombMapText.Text, "bank") then
			bomb()
			wait(1)
			game:GetService('Players').LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-470.668, 20.620, -285.169)
			wait(.30)
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = game.Players.LocalPlayer.Character
			wait(.1)
			activebomb()
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = game.Players.LocalPlayer.Character
			wait(.1)
			activebomb()
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = game.Players.LocalPlayer.Character
			wait(.1)
			activebomb()
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = game.Players.LocalPlayer.Character
			wait(.1)
			activebomb()
			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = game.Players.LocalPlayer.Character


		end

	end)

	BombMapText.Name = "BombMapText"
	BombMapText.Parent = BombMap
	BombMapText.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	BombMapText.BorderColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	BombMapText.Position = UDim2.new(0.00740740728, 0, 1, 0)
	BombMapText.Size = UDim2.new(0, 133, 0, 15)
	BombMapText.Font = Enum.Font.SourceSans
	BombMapText.PlaceholderColor3 = Color3.new(1, 1, 1)
	BombMapText.PlaceholderText = "Place Name"
	BombMapText.Text = ""
	BombMapText.TextColor3 = Color3.new(1, 1, 1)
	BombMapText.TextSize = 16


	TargetScrollFrame.Name = "TargetScrollFrame"
	TargetScrollFrame.Parent = MainChild
	TargetScrollFrame.Active = true
	TargetScrollFrame.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	TargetScrollFrame.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	TargetScrollFrame.Position = UDim2.new(0.247117266, 0, 0.131311327, 0)
	TargetScrollFrame.Size = UDim2.new(0, 605, 0, 295)
	TargetScrollFrame.Visible = false
	TargetScrollFrame.CanvasSize = UDim2.new(0, 0, 3, 0)

	function GetShortenedPlrFromName(name) -- uses string.sub to see if the typed in name fits and matches somewhere in the player's name, uncase sensitive. returns a table where the player is inside because of the all and others support
		name = string.lower(tostring(name))

		if not game:GetService("Players"):FindFirstChild("all") and name == "all" or game:GetService("Players"):FindFirstChild("all") and game:GetService("Players"):FindFirstChild("all").ClassName ~= "Player" and name == "all" then
			return game:GetService("Players"):GetPlayers()
		end
		if not game:GetService("Players"):FindFirstChild("others") and name == "others" or game:GetService("Players"):FindFirstChild("others") and game:GetService("Players"):FindFirstChild("others").ClassName ~= "Player" and name == "others" then
			name = game:GetService("Players"):GetPlayers()
			for i, v in pairs(name) do
				if v == LocalPlayer then
					table.remove(name, i)
				end
			end
			return name
		end

		for i, v in pairs(game.Players:GetPlayers()) do
			if string.lower(string.sub(v.Name, 1, #name)) == name then
				return {v}
			end
		end

		return nil
	end
	local LocalPlayer = game:GetService("Players").LocalPlayer
	local Character = LocalPlayer.Character
	local Workspace = game:GetService("Workspace")
	local CoreGui = game:GetService("CoreGui")

	FistLock.Name = "FistLock"
	FistLock.Parent = TargetScrollFrame
	FistLock.BackgroundColor3 = Color3.new(0, 0, 0)
	FistLock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FistLock.Position = UDim2.new(0.0105364919, 0, 0.00896634161, 0)
	FistLock.Size = UDim2.new(0, 135, 0, 26)
	FistLock.Font = Enum.Font.SourceSans
	FistLock.Text = "FistLock"
	FistLock.TextColor3 = Color3.new(1, 1, 1)
	FistLock.TextSize = 18
	FistLock.MouseButton1Click:connect(function()
		local TargetPlr = findPlayer(TargetTextbox.Text);
		local localPlayer     = game:GetService("Players").LocalPlayer;
		local localCharacter  = localPlayer.Character;
		ezpro = false
		if Onandoff_115.BackgroundColor3 == Color3.new(1, 0, 0) and ezpro == false then
			Onandoff_115.BackgroundColor3 = Color3.new(0, 1, 0)

			LockedPlayer = nil
			if GetShortenedPlrFromName(TargetTextbox.Text) ~= nil then
				for i, v in pairs(GetShortenedPlrFromName(TargetTextbox.Text)) do
					LockedPlayer = v
					break
				end
			end
		else
			Onandoff_115.BackgroundColor3 = Color3.new(1, 0, 0)
			ezpro = false
			LockedPlayer = nil

			local lol = game.Players.LocalPlayer.Character.HumanoidRootPart
			for i = 1, 10 do
				game.Players.LocalPlayer.Character.RightHand.CFrame = lol.CFrame
				game.Players.LocalPlayer.Character.LeftHand.CFrame = lol.CFrame
				wait(0.05)
			end
			game.StarterGui:SetCore("SendNotification", {
				Title = "Polakya";
				Text = TargetPlr.Name .. " Successfully Unlocked";
				Duration = 15;
			})

		end

	end)
	game:GetService("RunService").Heartbeat:Connect(function()
		if LockedPlayer ~= nil and LockedPlayer.Character and LockedPlayer.Character:FindFirstChildOfClass("Humanoid") and LockedPlayer.Character:FindFirstChildOfClass("Humanoid").Health > 0 then
			for i, v in pairs(LocalPlayer.Character:GetDescendants()) do
				if v.ClassName == "Motor6D" and (v.Name == "RightWrist" or v.Name == "LeftWrist") then
					v:Destroy()
				end
			end
			if LocalPlayer ~= nil and LocalPlayer.Character and LocalPlayer.Character:FindFirstChild("RightHand") and LocalPlayer.Character:FindFirstChild("LeftHand") and LocalPlayer.Character:FindFirstChildOfClass("Humanoid") and LocalPlayer.Character:FindFirstChildOfClass("Humanoid").Health > 0 then

				if LockedPlayer.Character.PrimaryPart and not LockedPlayer.Character:FindFirstChild("HumanoidRootPart") then
					LocalPlayer.Character.RightHand.CFrame = LockedPlayer.Character.PrimaryPart.CFrame
					LocalPlayer.Character.LeftHand.CFrame = LockedPlayer.Character.PrimaryPart.CFrame
				elseif LockedPlayer.Character:FindFirstChild("HumanoidRootPart") then
					LocalPlayer.Character.RightHand.CFrame = LockedPlayer.Character.HumanoidRootPart.CFrame
					LocalPlayer.Character.LeftHand.CFrame = LockedPlayer.Character.HumanoidRootPart.CFrame
				end

			end
		end
	end)

	Onandoff_115.Name = "Onandoff"
	Onandoff_115.Parent = FistLock
	Onandoff_115.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_115.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_115.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_115.Size = UDim2.new(0, 135, 0, 15)

	ForceKill.Name = "ForceKill"
	ForceKill.Parent = TargetScrollFrame
	ForceKill.BackgroundColor3 = Color3.new(0, 0, 0)
	ForceKill.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	ForceKill.Position = UDim2.new(0.258470356, 0, 0.00896634161, 0)
	ForceKill.Size = UDim2.new(0, 135, 0, 26)
	ForceKill.Font = Enum.Font.SourceSans
	ForceKill.Text = "ForceKill"
	ForceKill.TextColor3 = Color3.new(1, 1, 1)
	ForceKill.TextSize = 18
	ForceKill.MouseButton1Click:Connect(function()
		local Target = findPlayer(TargetTextbox.Text);
		punchreachrr = Target.Name
		local reachthing = "Combat"
		if game.Players.LocalPlayer.Backpack:FindFirstChild(reachthing) then
			game.Players.LocalPlayer.Backpack:FindFirstChild(reachthing).Parent = game.Players.LocalPlayer.Character
		end
		wait()
		game.Players.LocalPlayer.Character:FindFirstChild(reachthing):Activate()
		punchreach = true
		local cor = coroutine.wrap(function()
			wait(3)
			punchreach = false
			local lol = game.Players.LocalPlayer.Character.HumanoidRootPart
			game.Players.LocalPlayer.Character.RightHand.Size = Vector3.new(0.5,0.5, 0.5)
			game.Players.LocalPlayer.Character.LeftHand.Size = Vector3.new(0.5,0.5, 0.5)

			for i = 1, 10 do
				game.Players.LocalPlayer.Character.RightHand.CFrame = lol.CFrame
				game.Players.LocalPlayer.Character.LeftHand.CFrame = lol.CFrame
				wait(0.05)
			end

		end)
		cor()
		game:service'RunService'.Heartbeat:Connect(function(step)
			if punchreach == true then
				pcall(function()
					if game.Players.LocalPlayer.Character.RightHand:FindFirstChildOfClass("Model") then
						game.Players.LocalPlayer.Character.RightHand.Model.RightWrist:Destroy()
					end

					game.Players.LocalPlayer.Character.RightHand.RightWrist:Destroy()

				end)
				pcall(function()
					if game.Players.LocalPlayer.Character.LeftHand:FindFirstChildOfClass("Model") then
						game.Players.LocalPlayer.Character.LeftHand.Model.LeftWrist:Destroy()
					end
					game.Players.LocalPlayer.Character.LeftHand.LeftWrist:Destroy()
				end)
				local Part = workspace.Players[punchreachrr].LowerTorso

				game.Players.LocalPlayer.Character.RightHand.CFrame = CFrame.new(Part.CFrame.X ,Part.CFrame.Y+2, Part.CFrame.Z)
				game.Players.LocalPlayer.Character.RightHand.Massless = true
				game.Players.LocalPlayer.Character.RightHand.Size = Vector3.new(5, 5, 5)
				game.Players.LocalPlayer.Character.LeftHand.CFrame = CFrame.new(Part.CFrame.X ,Part.CFrame.Y+2, Part.CFrame.Z)
				game.Players.LocalPlayer.Character.LeftHand.Massless = true
				game.Players.LocalPlayer.Character.LeftHand.Size = Vector3.new(5, 5, 5)
			end
		end)
	end)


	Onandoff_116.Name = "Onandoff"
	Onandoff_116.Parent = ForceKill
	Onandoff_116.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_116.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_116.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_116.Size = UDim2.new(0, 135, 0, 15)

	Spectate.Name = "Spectate"
	Spectate.Parent = TargetScrollFrame
	Spectate.BackgroundColor3 = Color3.new(0, 0, 0)
	Spectate.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Spectate.Position = UDim2.new(0.508057117, 0, 0.00896634161, 0)
	Spectate.Size = UDim2.new(0, 135, 0, 26)
	Spectate.Font = Enum.Font.SourceSans
	Spectate.Text = "Spectate"
	Spectate.TextColor3 = Color3.new(1, 1, 1)
	Spectate.TextSize = 18
	Spectate.MouseButton1Click:connect(function()
		local spech = findPlayer(TargetTextbox.Text);
		spech = spech.Name
		if Onandoff_117.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_117.BackgroundColor3 = Color3.new(0, 1, 0)
			game.Workspace.Camera.CameraSubject = game.Players[spech].Character.Humanoid;

		else
			Onandoff_117.BackgroundColor3 = Color3.new(1, 0, 0)
			game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid;

		end
	end)

	Onandoff_117.Name = "Onandoff"
	Onandoff_117.Parent = Spectate
	Onandoff_117.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_117.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_117.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_117.Size = UDim2.new(0, 135, 0, 15)

	RpgLock.Name = "RpgLock"
	RpgLock.Parent = TargetScrollFrame
	RpgLock.BackgroundColor3 = Color3.new(0, 0, 0)
	RpgLock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	RpgLock.Position = UDim2.new(0.751032352, 0, 0.00896634161, 0)
	RpgLock.Size = UDim2.new(0, 135, 0, 26)
	RpgLock.Font = Enum.Font.SourceSans
	RpgLock.Text = "RpgLock"
	RpgLock.TextColor3 = Color3.new(1, 1, 1)
	RpgLock.TextSize = 18
	RpgLock.MouseButton1Click:connect(function()
		if Onandoff_118.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_118.BackgroundColor3 = Color3.new(0, 1, 0)

			nuking = true
			local nukar = findPlayer(TargetTextbox.Text);
			nukerowner = nukar.Name
			if nuking == true then
				noti("RpgLock Successfully Locked Manually")
				delay(0, function()
					while wait() do
						pcall(function()
							if game.Workspace.Ignored:FindFirstChild("Launcher") and nuking == true and workspace.Players:FindFirstChild(nukerowner) then
								local lol = game.Workspace.Ignored:FindFirstChild("Launcher")

								if lol:FindFirstChildOfClass("BodyVelocity") then
									wait()
									lol.BodyVelocity:Destroy()
								end

								if lol:FindFirstChild("BodyVelocity") == nil and nuking == true then
									lol.CFrame = CFrame.new(workspace.Players[nukerowner].LowerTorso.CFrame.X,workspace.Players[nukerowner].LowerTorso.CFrame.Y+6.5,workspace.Players[nukerowner].LowerTorso.CFrame.Z)
								end

							elseif game.Workspace.Ignored:FindFirstChild("Handle") and nuking == true then
								local lol = game.Workspace.Ignored:FindFirstChild("Handle")

								if lol:FindFirstChild("Pin") and nuking == true then
									lol.CFrame = CFrame.new(workspace.Players[nukerowner].LowerTorso.CFrame.X,workspace.Players[nukerowner].LowerTorso.CFrame.Y+8,workspace.Players[nukerowner].LowerTorso.CFrame.Z)
								end
							end
						end)
					end
				end)
				if game.Players.LocalPlayer.Character.BodyEffects['K.O'].Value == true then
					noti("Sorry try again while you fly?")
				end
			end
		else
			Onandoff_118.BackgroundColor3 = Color3.new(1, 0, 0)
			nuking = false
		end
	end)

	Onandoff_118.Name = "Onandoff"
	Onandoff_118.Parent = RpgLock
	Onandoff_118.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_118.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_118.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_118.Size = UDim2.new(0, 135, 0, 15)

	RpgArrest.Name = "RpgArrest"
	RpgArrest.Parent = TargetScrollFrame
	RpgArrest.BackgroundColor3 = Color3.new(0, 0, 0)
	RpgArrest.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	RpgArrest.Position = UDim2.new(0.0105364649, 0, 0.0648375601, 0)
	RpgArrest.Size = UDim2.new(0, 135, 0, 26)
	RpgArrest.Font = Enum.Font.SourceSans
	RpgArrest.Text = "RpgArrest"
	RpgArrest.TextColor3 = Color3.new(1, 1, 1)
	RpgArrest.TextSize = 18
	RpgArrest.MouseButton1Click:connect(function()
		if Onandoff_119.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_119.BackgroundColor3 = Color3.new(0, 1, 0)
			nuking = true
			if game.Players.LocalPlayer.Backpack:FindFirstChild("Cuff") and nuking == true then
				local Target          = findPlayer(TargetTextbox.Text);
				for i,v in pairs(game.Players:GetPlayers()) do 
					if game.Players.LocalPlayer.Backpack:FindFirstChild("[RPG]") and nuking == true then

						game.Players.LocalPlayer.Backpack:FindFirstChild("[RPG]").Parent = game.Players.LocalPlayer.Character
					end
					nukerowner = Target.Name
					game.Players.LocalPlayer.Character:FindFirstChild("[RPG]"):Activate()
					repeat
						if workspace.Players:FindFirstChild(Target.Name) and nuking == true then
							if workspace.Players[Target.Name].BodyEffects["K.O"].Value == true and nuking == true then
								if game.Players.LocalPlayer.Backpack:FindFirstChild("Cuff") and nuking == true then
									game.StarterGui:SetCore("SendNotification", {
										Title = "Polakya";
										Text = "Arresting "..nukerowner ;
										Duration = 15;
									})
									game.Players.LocalPlayer.Backpack:FindFirstChild("Cuff").Parent = game.Players.LocalPlayer.Character
								end
								game.Players.LocalPlayer.Character:FindFirstChild("Cuff"):Activate()
								game.Players.LocalPlayer.Character:MoveTo(workspace.Players[Target.Name].Head.Position)
								if workspace:FindFirstChild("Core") then
									workspace.Core:Destroy()
								end
								flying = false
							end
						end
						wait()
					until workspace.Players[nukerowner].BodyEffects["Cuff"].Value == true

					break
				end
			else
				noti("Must Be A Cop")
			end
		else
			nuking = false
			Onandoff_119.BackgroundColor3 = Color3.new(1, 0, 0)

		end
	end)

	Onandoff_119.Name = "Onandoff"
	Onandoff_119.Parent = RpgArrest
	Onandoff_119.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_119.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_119.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_119.Size = UDim2.new(0, 135, 0, 15)

	CallPlr.Name = "Call Plr"
	CallPlr.Parent = TargetScrollFrame
	CallPlr.BackgroundColor3 = Color3.new(0, 0, 0)
	CallPlr.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	CallPlr.Position = UDim2.new(0.258470356, 0, 0.0657845289, 0)
	CallPlr.Size = UDim2.new(0, 135, 0, 26)
	CallPlr.Font = Enum.Font.SourceSans
	CallPlr.Text = "Call Plr"
	CallPlr.TextColor3 = Color3.new(1, 1, 1)
	CallPlr.TextSize = 18
	CallPlr.MouseButton1Click:connect(function()
		local Target = findPlayer(TargetTextbox.Text);
		for i,v in pairs(game.Players:GetPlayers()) do 
			local plr = v
			if plr.Character:FindFirstChild("Humanoid") then
				local A_1 = "PhoneCall"
				local A_2 = Target.Name
				local Event = game:GetService("ReplicatedStorage").MainEvent
				Event:FireServer(A_1, A_2)
				break
			end
		end
	end)

	Onandoff_120.Name = "Onandoff"
	Onandoff_120.Parent = CallPlr
	Onandoff_120.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_120.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_120.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_120.Size = UDim2.new(0, 135, 0, 15)

	AutoCall.Name = "AutoCall"
	AutoCall.Parent = TargetScrollFrame
	AutoCall.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoCall.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoCall.Position = UDim2.new(0.506404221, 0, 0.0638905913, 0)
	AutoCall.Size = UDim2.new(0, 135, 0, 26)
	AutoCall.Font = Enum.Font.SourceSans
	AutoCall.Text = "AutoCall"
	AutoCall.TextColor3 = Color3.new(1, 1, 1)
	AutoCall.TextSize = 18
	AutoCall.MouseButton1Click:connect(function()
		callallomg = false
		local Target = findPlayer(TargetTextbox.Text);
		if Onandoff_121.BackgroundColor3 == Color3.new(1, 0, 0) and callallomg == false then
			Onandoff_121.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("AutoCall Enabled")

			callallomg = true
			repeat
				local	Target = findPlayer(TargetTextbox.Text);

				if game.Players.LocalPlayer.Backpack:FindFirstChild("[Phone]") then
					game.Players.LocalPlayer.Backpack:FindFirstChild("[Phone]").Parent = game.Players.LocalPlayer.Character
				end
				for i, v in pairs(game.Players:GetPlayers()) do
					local A_1 = "PhoneCall"
					local A_2 = Target.Name
					local Event = game:GetService("ReplicatedStorage").MainEvent
					Event:FireServer(A_1, A_2)

				end
				wait(1)
			until callallomg == false
		else
			Onandoff_121.BackgroundColor3 = Color3.new(1, 0, 0)
			callallomg = false
			noti("AutoCall Disabled")
		end
	end)

	Onandoff_121.Name = "Onandoff"
	Onandoff_121.Parent = AutoCall
	Onandoff_121.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_121.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_121.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_121.Size = UDim2.new(0, 135, 0, 15)

	TaserLock.Name = "TaserLock"
	TaserLock.Parent = TargetScrollFrame
	TaserLock.BackgroundColor3 = Color3.new(0, 0, 0)
	TaserLock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	TaserLock.Position = UDim2.new(0.751032352, 0, 0.0657845289, 0)
	TaserLock.Size = UDim2.new(0, 135, 0, 26)
	TaserLock.Font = Enum.Font.SourceSans
	TaserLock.Text = "TaserLock"
	TaserLock.TextColor3 = Color3.new(1, 1, 1)
	TaserLock.TextSize = 18
	TaserLock.MouseButton1Click:connect(function()
		local Target = findPlayer(TargetTextbox.Text);
		nukerowner = Target.Name
		game.Players.LocalPlayer.Backpack["[Taser]"].Parent = game.Players.LocalPlayer.Character
		game.Players.LocalPlayer.Character["[Taser]"]:Activate()
		pcall (function()
			game.Players.LocalPlayer.Character["[Taser]"].Handle.ChildAdded:Connect(function(obj)
				if obj.Name == "Part" then
					repeat
						obj.CFrame = game.Players[nukerowner].Character.HumanoidRootPart.CFrame
						wait()
					until not obj:IsDescendantOf(game) -- destroyed
				end
			end)
		end)
	end)

	Onandoff_122.Name = "Onandoff"
	Onandoff_122.Parent = TaserLock
	Onandoff_122.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_122.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_122.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_122.Size = UDim2.new(0, 135, 0, 15)

	Aimlock.Name = "Aimlock"
	Aimlock.Parent = TargetScrollFrame
	Aimlock.BackgroundColor3 = Color3.new(0, 0, 0)
	Aimlock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Aimlock.Position = UDim2.new(0.0105364621, 0, 0.121655747, 0)
	Aimlock.Size = UDim2.new(0, 135, 0, 26)
	Aimlock.Font = Enum.Font.SourceSans
	Aimlock.Text = "Aimlock"
	Aimlock.TextColor3 = Color3.new(1, 1, 1)
	Aimlock.TextSize = 18
	Aimlock.MouseButton1Click:connect(function()
		aimlocked = false
		if Onandoff_123.BackgroundColor3 == Color3.new(1, 0, 0) and aimlocked == false then
			Onandoff_123.BackgroundColor3 = Color3.new(0, 1, 0)

			aimlocked = true
			local protarget = findPlayer(TargetTextbox.Text);
			game.Players.LocalPlayer.Character.BodyEffects.Armor:Destroy()
			while true do
				local c = "UpdateMousePos"
				local v = protarget.Character.Head.Position
				local e = game:GetService("ReplicatedStorage").MainEvent
				e:FireServer(c, v)
				wait()
			end
		else
			Onandoff_123.BackgroundColor3= Color3.new(1, 0, 0)
			aimlocked = false
			ps = game:GetService("Players")
			lp2 = ps.LocalPlayer
			char12 = lp2.Character
			local Clone1 = Instance.new("IntValue")
			Clone1.Name = "Armor"
			Clone1.Parent = char12.BodyEffects
		end
	end)

	Onandoff_123.Name = "Onandoff"
	Onandoff_123.Parent = Aimlock
	Onandoff_123.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_123.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_123.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_123.Size = UDim2.new(0, 135, 0, 15)

	FlingPlr.Name = "Fling Plr"
	FlingPlr.Parent = TargetScrollFrame
	FlingPlr.BackgroundColor3 = Color3.new(0, 0, 0)
	FlingPlr.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FlingPlr.Position = UDim2.new(0.258470356, 0, 0.121655747, 0)
	FlingPlr.Size = UDim2.new(0, 135, 0, 26)
	FlingPlr.Font = Enum.Font.SourceSans
	FlingPlr.Text = "Fling Plr"
	FlingPlr.TextColor3 = Color3.new(1, 1, 1)
	FlingPlr.TextSize = 18
	FlingPlr.MouseButton1Click:connect(function()
		if Onandoff_124.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_124.BackgroundColor3 = Color3.new(0, 1, 0)
			noti("Fling Plr")

			for i,v in pairs(game.Players:GetPlayers()) do 
				local Party = Instance.new("Part",workspace)
				Party.Name = "Shit"
				Party.CanCollide = false
				Party.Anchored = false
				Party.Size = Vector3.new(0, 0, 0)
				Party.Massless = true
				local Weld = Instance.new("Weld",Party)
				Weld.Part0 = Party
				Weld.Part1 = game.Players.LocalPlayer.Character.HumanoidRootPart
				HasDied = false
				local bodyp    = Instance.new("BodyPosition",Party)
				bodyp.D        = 0
				bodyp.MaxForce = Vector3.new(math.huge,math.huge,math.huge)
				bodyp.P = 25000
				local ERTY = findPlayer(TargetTextbox.Text);
				local Target = workspace.Players[ERTY.Name]

				repeat
					game:GetService("RunService").RenderStepped:Wait()
					pcall(function()
						flying = false
						if Target.BodyEffects["K.O"].Value == true then
							HasDied = true
						end
						if Target.BodyEffects:FindFirstChild("K.O") == nil then
							HasDied = true

						end
						if HasDied == false then
							bodyp.Position = Target.PrimaryPart.Position
						end
					end)
				until HasDied == true

				Party:Destroy()
				for i = 1, 10 do
					game.Players.LocalPlayer.Character:MoveTo(Target.LowerTorso.Position)
					wait(0.1)
				end
				break
			end
		else
			Onandoff_124.BackgroundColor3 = Color3.new(1, 0, 0)
			noti("Fling Stopped")
			HasDied = true


		end
	end)

	Onandoff_124.Name = "Onandoff"
	Onandoff_124.Parent = FlingPlr
	Onandoff_124.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_124.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_124.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_124.Size = UDim2.new(0, 135, 0, 15)

	InfoPlr.Name = "InfoPlr"
	InfoPlr.Parent = TargetScrollFrame
	InfoPlr.BackgroundColor3 = Color3.new(0, 0, 0)
	InfoPlr.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	InfoPlr.Position = UDim2.new(0.506404281, 0, 0.12165574, 0)
	InfoPlr.Size = UDim2.new(0, 135, 0, 26)
	InfoPlr.Font = Enum.Font.SourceSans
	InfoPlr.Text = "Info Plr"
	InfoPlr.TextColor3 = Color3.new(1, 1, 1)
	InfoPlr.TextSize = 18
	InfoPlr.MouseButton1Click:connect(function()
		local infoplr = findPlayer(TargetTextbox.Text)
		local	targetop = 	infoplr.Name
		local ScreenGui = Instance.new("ScreenGui")
		local Infoframe = Instance.new("Frame")
		local Money = Instance.new("TextLabel")
		local Name = Instance.new("TextLabel")
		local Bounty = Instance.new("TextLabel")
		local Crew = Instance.new("TextLabel")
		local Age = Instance.new("TextLabel")
		local UserId = Instance.new("TextLabel")
		local ImageLabel = Instance.new("ImageLabel")
		local TextButton = Instance.new("TextButton")

		ScreenGui.Parent = game.CoreGui
		ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

		Infoframe.Name = "Infoframe"
		Infoframe.Parent = ScreenGui
		Infoframe.BorderColor3 = Color3.new(0, 0, 0)
		Infoframe.BackgroundColor3 = Color3.new(0, 0, 0)
		Infoframe.Position = UDim2.new(0.0891393423, 0, 0.0947176665, 0)
		Infoframe.Size = UDim2.new(0, 684, 0, 404)
		Infoframe.Active = true
		Infoframe.Draggable = true

		Money.Name = "Money"
		Money.Parent = Infoframe
		Money.BackgroundColor3 = Color3.new(1, 1, 1)
		Money.BackgroundTransparency = 1
		Money.Position = UDim2.new(0.136065573, 0, 0.0421836227, 0)
		Money.Size = UDim2.new(0, 73, 0, 41)
		Money.Font = Enum.Font.SourceSans
		Money.Text = "Money: $"..game:GetService("Players")[targetop].DataFolder.Currency.Value..""
		Money.TextColor3 = Color3.new(1, 0, 0)
		Money.TextSize = 20

		Name.Name = "Name"
		Name.Parent = Infoframe
		Name.BackgroundColor3 = Color3.new(1, 1, 1)
		Name.BackgroundTransparency = 1
		Name.Position = UDim2.new(0.136065573, 0, 0.230769232, 0)
		Name.Size = UDim2.new(0, 73, 0, 41)
		Name.Font = Enum.Font.SourceSans
		Name.Text = "Name: "..game:GetService("Players")[targetop].Name.."."
		Name.TextColor3 = Color3.new(1, 0, 0)
		Name.TextSize = 20

		Bounty.Name = "Bounty"
		Bounty.Parent = Infoframe
		Bounty.BackgroundColor3 = Color3.new(1, 1, 1)
		Bounty.BackgroundTransparency = 1
		Bounty.Position = UDim2.new(0.136065573, 0, 0.431761801, 0)
		Bounty.Size = UDim2.new(0, 73, 0, 41)
		Bounty.Font = Enum.Font.SourceSans
		Bounty.Text = "Bounty: "..game:GetService("Players")[targetop].DataFolder.Information.Wanted.Value.."."
		Bounty.TextColor3 = Color3.new(1, 0, 0)
		Bounty.TextSize = 20

		Age.Name = "Age"
		Age.Parent = Infoframe
		Age.BackgroundColor3 = Color3.new(1, 1, 1)
		Age.BackgroundTransparency = 1
		Age.Position = UDim2.new(0.136065573, 0, 0.898262978, 0)
		Age.Size = UDim2.new(0, 73, 0, 41)
		Age.Font = Enum.Font.SourceSans
		Age.Text = "Age: "..game:GetService("Players")[targetop].AccountAge.."."
		Age.TextColor3 = Color3.new(1, 0, 0)
		Age.TextSize = 20

		UserId.Name = "UserId"
		UserId.Parent = Infoframe
		UserId.BackgroundColor3 = Color3.new(1, 1, 1)
		UserId.BackgroundTransparency = 1
		UserId.Position = UDim2.new(0.507755756, 0, 0.0421836227, 0)
		UserId.Size = UDim2.new(0, 73, 0, 41)
		UserId.Font = Enum.Font.SourceSans
		UserId.Text = "UserId: "..game:GetService("Players")[targetop].UserId.."."
		UserId.TextColor3 = Color3.new(1, 0, 0)
		UserId.TextSize = 20

		ImageLabel.Parent = Infoframe
		ImageLabel.BackgroundColor3 = Color3.new(1, 1, 1)
		ImageLabel.BackgroundTransparency = 1
		ImageLabel.Position = UDim2.new(0.69590646, 0, 0.279702961, 0)
		ImageLabel.Size = UDim2.new(0, 189, 0, 249)
		ImageLabel.Image = "https://assetgame.roblox.com/Thumbs/Avatar.ashx?x=250&y=250&Format=Png&username="..game:GetService("Players")[targetop].Name

		TextButton.Parent = Infoframe
		TextButton.BackgroundColor3 = Color3.new(1, 1, 1)
		TextButton.BackgroundTransparency = 1
		TextButton.Position = UDim2.new(0.760233939, 0, 0.0198019799, 0)
		TextButton.Size = UDim2.new(0, 152, 0, 50)
		TextButton.Font = Enum.Font.SourceSans
		TextButton.Text = "Close"
		TextButton.TextColor3 = Color3.new(1, 0, 0)
		TextButton.TextSize = 30
		TextButton.MouseButton1Click:connect(function()
			Infoframe.Visible = false
			Money.Text = "Money: "

		end)
		Crew.Name = "Crew"
		Crew.Parent = Infoframe
		Crew.BackgroundColor3 = Color3.new(1, 1, 1)
		Crew.BackgroundTransparency = 1
		Crew.Position = UDim2.new(0.136065573, 0, 0.657568216, 0)
		Crew.Size = UDim2.new(0, 73, 0, 41)
		Crew.Font = Enum.Font.SourceSans
		Crew.Text = "Crew: "..game:GetService("Players")[targetop].DataFolder.Information.Crew.Value.."."
		Crew.TextColor3 = Color3.new(1, 0, 0)
		Crew.TextSize = 20
	end)

	Onandoff_125.Name = "Onandoff"
	Onandoff_125.Parent = InfoPlr
	Onandoff_125.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_125.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_125.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_125.Size = UDim2.new(0, 135, 0, 15)

	GrenadeLock.Name = "GrenadeLock"
	GrenadeLock.Parent = TargetScrollFrame
	GrenadeLock.BackgroundColor3 = Color3.new(0, 0, 0)
	GrenadeLock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	GrenadeLock.Position = UDim2.new(0.751032352, 0, 0.120708779, 0)
	GrenadeLock.Size = UDim2.new(0, 135, 0, 26)
	GrenadeLock.Font = Enum.Font.SourceSans
	GrenadeLock.Text = "Grenade Lock"
	GrenadeLock.TextColor3 = Color3.new(1, 1, 1)
	GrenadeLock.TextSize = 18
	GrenadeLock.MouseButton1Click:connect(function()
		local Target = findPlayer(TargetTextbox.Text);
		if game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]") then

			game.Players.LocalPlayer.Backpack:FindFirstChild("[Grenade]").Parent = game.Players.LocalPlayer.Character
			nuking = true
			nukerowner = Target.Name
			game.Players.LocalPlayer.Character:FindFirstChild("[Grenade]"):Activate()
			game.Players.LocalPlayer.Character:FindFirstChild("[Grenade]"):Activate()
		end
		delay(0, function()
			while wait() do
				pcall(function()
					if game.Workspace.Ignored:FindFirstChild("Grenade") and nuking == true and workspace.Players:FindFirstChild(nukerowner) then
						local lol = game.Workspace.Ignored:FindFirstChild("Grenade")

						if lol:FindFirstChildOfClass("BodyVelocity") then
							wait()
							lol.BodyVelocity:Destroy()
						end

						if lol:FindFirstChild("BodyVelocity") == nil then
							lol.CFrame = CFrame.new(workspace.Players[nukerowner].Head.CFrame.X,workspace.Players[nukerowner].Head.CFrame.Y+6.5,workspace.Players[nukerowner].Head.CFrame.Z)
						end

					elseif game.Workspace.Ignored:FindFirstChild("Handle") and nuking == true then
						local lol = game.Workspace.Ignored:FindFirstChild("Handle")

						if lol:FindFirstChild("Pin") then
							lol.CFrame = CFrame.new(workspace.Players[nukerowner].Head.CFrame.X,workspace.Players[nukerowner].Head.CFrame.Y+8,workspace.Players[nukerowner].Head.CFrame.Z)
						end
						wait(5)
						if game.Players[nukerowner].Character.BodyEffects['K.O'].Value == true then
							noti("Target Got Boomeed")
						else
							noti("Target Still Alive")
						end

					end
				end)
			end
		end)
	end)

	Onandoff_126.Name = "Onandoff"
	Onandoff_126.Parent = GrenadeLock
	Onandoff_126.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_126.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_126.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_126.Size = UDim2.new(0, 135, 0, 15)

	FlashBangLock.Name = "FlashBang Lock"
	FlashBangLock.Parent = TargetScrollFrame
	FlashBangLock.BackgroundColor3 = Color3.new(0, 0, 0)
	FlashBangLock.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FlashBangLock.Position = UDim2.new(0.0105364919, 0, 0.179420903, 0)
	FlashBangLock.Size = UDim2.new(0, 135, 0, 26)
	FlashBangLock.Font = Enum.Font.SourceSans
	FlashBangLock.Text = "FlashBang Lock"
	FlashBangLock.TextColor3 = Color3.new(1, 1, 1)
	FlashBangLock.TextSize = 18
	FlashBangLock.MouseButton1Click:connect(function()
		local Target = findPlayer(TargetTextbox.Text);
		if game.Players.LocalPlayer.Backpack:FindFirstChild("[Flashbang]") then

			game.Players.LocalPlayer.Backpack:FindFirstChild("[Flashbang]").Parent = game.Players.LocalPlayer.Character
			nuking = true
			nukerowner = Target.Name
			game.Players.LocalPlayer.Character:FindFirstChild("[Flashbang]"):Activate()
			game.Players.LocalPlayer.Character:FindFirstChild("[Flashbang]"):Activate()
		end
		delay(0, function()
			while wait() do
				pcall(function()
					if game.Workspace.Ignored:FindFirstChild("Flashbang") and nuking == true and workspace.Players:FindFirstChild(nukerowner) then
						local lol = game.Workspace.Ignored:FindFirstChild("Flashbang")

						if lol:FindFirstChildOfClass("BodyVelocity") then
							wait()
							lol.BodyVelocity:Destroy()
						end

						if lol:FindFirstChild("BodyVelocity") == nil then
							lol.CFrame = CFrame.new(workspace.Players[nukerowner].Head.CFrame.X,workspace.Players[nukerowner].Head.CFrame.Y+6.5,workspace.Players[nukerowner].Head.CFrame.Z)
						end

					elseif game.Workspace.Ignored:FindFirstChild("Handle") and nuking == true then
						local lol = game.Workspace.Ignored:FindFirstChild("Handle")

						if lol:FindFirstChild("Pin") then
							lol.CFrame = CFrame.new(workspace.Players[nukerowner].Head.CFrame.X,workspace.Players[nukerowner].Head.CFrame.Y+8,workspace.Players[nukerowner].Head.CFrame.Z)
						end
						wait(5)
						if game.Players[nukerowner].Character.BodyEffects['K.O'].Value == true then
							noti("Target Got Boomeed")
						else
							noti("Target Still Alive")
						end

					end
				end)
			end
		end)
	end)

	Onandoff_127.Name = "Onandoff"
	Onandoff_127.Parent = FlashBangLock
	Onandoff_127.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_127.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_127.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_127.Size = UDim2.new(0, 135, 0, 15)

	BagPlr.Name = "Bag Plr"
	BagPlr.Parent = TargetScrollFrame
	BagPlr.BackgroundColor3 = Color3.new(0, 0, 0)
	BagPlr.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	BagPlr.Position = UDim2.new(0.258470356, 0, 0.179420903, 0)
	BagPlr.Size = UDim2.new(0, 135, 0, 26)
	BagPlr.Font = Enum.Font.SourceSans
	BagPlr.Text = "Bag Plr"
	BagPlr.TextColor3 = Color3.new(1, 1, 1)
	BagPlr.TextSize = 18
	BagPlr.MouseButton1Click:connect(function()
		if Onandoff_128.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_128.BackgroundColor3 = Color3.new(0, 1, 0)
			flying = false
			omgbag = true
			plr = game:GetService('Players').LocalPlayer
			X1 = plr.Character:FindFirstChild('HumanoidRootPart').CFrame.X
			Y1 = plr.Character:FindFirstChild('HumanoidRootPart').CFrame.Y
			Z1 = plr.Character:FindFirstChild('HumanoidRootPart').CFrame.Z
			local TargetPlr = TargetTextbox.Text
			function getRoot(char)
				local rootPart = char:FindFirstChild('HumanoidRootPart') or char:FindFirstChild('Torso') or char:FindFirstChild('UpperTorso')
				return rootPart
			end

			if TargetPlr and game.Players[TargetPlr].Character.BodyEffects['K.O'].Value == false then
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Ignored.Shop['[BrownBag] - $25'].Head.CFrame
				wait(.30)
				fireclickdetector(game.Workspace.Ignored.Shop['[BrownBag] - $25'].ClickDetector)
				game.Players.LocalPlayer.Backpack:WaitForChild("[BrownBag]").Parent = game.Players.LocalPlayer.Character

				local A_1 = "[Polakya] Bagging the Player" .. TargetPlr .. "." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
				wait(.5)
				repeat
					pcall(function()
						wait()
						getRoot(game.Players[TargetPlr].Character).CFrame = getRoot(game.Players.LocalPlayer.Character).CFrame + Vector3.new(1,3,0)
						game.Players.LocalPlayer.Character["[BrownBag]"]:Activate()

					end)

				until game.Players[TargetPlr].Character:FindFirstChild("Christmas_Sock") or omgbag == false
				plr.Character.HumanoidRootPart.CFrame = CFrame.new(X1,Y1+5,Z1)
				local A_1 = "[Polakya] Successfully Bagged " .. TargetPlr .. "." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
			elseif game.Players[TargetPlr].Character.BodyEffects['K.O'].Value == false then
				local A_1 = "[Polakya] " .. TargetPlr .. " Is Already Bagged." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
			end
		else
			Onandoff_128.BackgroundColor3 = Color3.new(1, 0, 0)
			omgbag = false
		end
	end)


	Onandoff_128.Name = "Onandoff"
	Onandoff_128.Parent = BagPlr
	Onandoff_128.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_128.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_128.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_128.Size = UDim2.new(0, 135, 0, 15)

	Goto.Name = "Goto"
	Goto.Parent = TargetScrollFrame
	Goto.BackgroundColor3 = Color3.new(0, 0, 0)
	Goto.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Goto.Position = UDim2.new(0.506404281, 0, 0.179420888, 0)
	Goto.Size = UDim2.new(0, 135, 0, 26)
	Goto.Font = Enum.Font.SourceSans
	Goto.Text = "Goto"
	Goto.TextColor3 = Color3.new(1, 1, 1)
	Goto.TextSize = 18
	Goto.MouseButton1Click:connect(function()
		local TargetPlr = TargetTextbox.Text;
		flying = false
		wait(.30)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[TargetPlr].Character.HumanoidRootPart.CFrame
	end)

	Onandoff_129.Name = "Onandoff"
	Onandoff_129.Parent = Goto
	Onandoff_129.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_129.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_129.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_129.Size = UDim2.new(0, 135, 0, 15)

	AudioId.Name = "Audio Id"
	AudioId.Parent = TargetScrollFrame
	AudioId.BackgroundColor3 = Color3.new(0, 0, 0)
	AudioId.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AudioId.Position = UDim2.new(0.749379516, 0, 0.179420888, 0)
	AudioId.Size = UDim2.new(0, 135, 0, 26)
	AudioId.Font = Enum.Font.SourceSans
	AudioId.Text = "Audio ID"
	AudioId.TextColor3 = Color3.new(1, 1, 1)
	AudioId.TextSize = 18
	AudioId.MouseButton1Click:connect(function()
		noti("If ID Didn't Show Up, Means He Doesn't Have Audio On!")
		local Target = findPlayer(TargetTextbox.Text);
		local plr = Target
		local SoundIdZ = workspace.Players[plr.Name].LowerTorso.BOOMBOXSOUND
		local id = SoundIdZ.SoundId:match("%d+")
		local Asset = game:GetService("MarketplaceService"):GetProductInfo(id)
		if plr.Character:FindFirstChild("Humanoid") then
			print(Asset.Name.." - "..id)
			game.StarterGui:SetCore("SendNotification", {
				Title = "Polakya"; -- the title (ofc)
				Text = Asset.Name.." - "..id; -- what the text says (ofc)
				Duration = 30; -- how long the notification should in secounds
			})
			setclipboard(id)
			noti("Coped ID!")
		end
	end)

	Onandoff_130.Name = "Onandoff"
	Onandoff_130.Parent = AudioId
	Onandoff_130.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_130.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_130.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_130.Size = UDim2.new(0, 135, 0, 15)

	AutoStompPlr.Name = "AutoStomp Plr"
	AutoStompPlr.Parent = TargetScrollFrame
	AutoStompPlr.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoStompPlr.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoStompPlr.Position = UDim2.new(0.010536477, 0, 0.240973935, 0)
	AutoStompPlr.Size = UDim2.new(0, 135, 0, 26)
	AutoStompPlr.Font = Enum.Font.SourceSans
	AutoStompPlr.Text = "AutoStomp Plr"
	AutoStompPlr.TextColor3 = Color3.new(1, 1, 1)
	AutoStompPlr.TextSize = 18
	AutoStompPlr.MouseButton1Click:connect(function()
		if Onandoff_131.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_131.BackgroundColor3 = Color3.new(0, 1, 0)
			local target = findPlayer(TargetTextbox.Text)
			if game.Players[target.Name].Character.BodyEffects['K.O'].Value == false then
				game.StarterGui:SetCore("SendNotification", {
					Title = "Polakya";
					Text = ""..target.Name.." Still not knocked";
					Duration = 7
				})
			end 
			stompa = true
			while  stompa == true do
				pcall(function()
					if game.Players[target.Name].Character.BodyEffects['K.O'].Value == true then
						flying = false
						game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[target.Name].Character.Head.CFrame
						game.ReplicatedStorage.MainEvent:FireServer("Stomp")

					end
				end)
				wait()
			end

		else
			Onandoff_131.BackgroundColor3 = Color3.new(1, 0, 0)
			stompa = false
		end
	end)

	Onandoff_131.Name = "Onandoff"
	Onandoff_131.Parent = AutoStompPlr
	Onandoff_131.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_131.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_131.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_131.Size = UDim2.new(0, 135, 0, 15)

	AutoArrestPlr.Name = "AutoArrest Plr"
	AutoArrestPlr.Parent = TargetScrollFrame
	AutoArrestPlr.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoArrestPlr.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoArrestPlr.Position = UDim2.new(0.258470356, 0, 0.240973935, 0)
	AutoArrestPlr.Size = UDim2.new(0, 135, 0, 26)
	AutoArrestPlr.Font = Enum.Font.SourceSans
	AutoArrestPlr.Text = "AutoArrest Plr"
	AutoArrestPlr.TextColor3 = Color3.new(1, 1, 1)
	AutoArrestPlr.TextSize = 18
	AutoArrestPlr.MouseButton1Click:connect(function()
		local target = findPlayer(TargetTextbox.Text)
		if Onandoff_132.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_132.BackgroundColor3 = Color3.new(0, 1, 0)
			arrasta = true
			repeat
				if workspace.Players:FindFirstChild(target.Name) then
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Cuff") then
						if workspace.Players[target.Name].BodyEffects["K.O"].Value == true then

							game.StarterGui:SetCore("SendNotification", {
								Title = "Polakya";
								Text = "Arresting "..nukerowner ;
								Duration = 15;
							})
							game.Players.LocalPlayer.Backpack:FindFirstChild("Cuff").Parent = game.Players.LocalPlayer.Character
						else
							noti("Still Not Knocked")
						end
						game.Players.LocalPlayer.Character:FindFirstChild("Cuff"):Activate()
						game.Players.LocalPlayer.Character:MoveTo(workspace.Players[target.Name].Head.Position)
						if workspace:FindFirstChild("Core") then
							workspace.Core:Destroy()
						end
						flying = false
					else
						game.StarterGui:SetCore("SendNotification", {
							Title = "Polakya";
							Text = "Must be a cop";
							Duration = 7
						})
						wait(.20)
						Onandoff_132.BackgroundColor3 = Color3.new(1, 0, 0)
						arrasta = true

					end
				end
				wait()
			until workspace.Players[nukerowner].BodyEffects["Cuff"].Value == true or arrasta == false
		else
			Onandoff_132.BackgroundColor3 = Color3.new(1, 0, 0)
			arrasta = true

		end
	end)

	Onandoff_132.Name = "Onandoff"
	Onandoff_132.Parent = AutoArrestPlr
	Onandoff_132.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_132.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_132.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_132.Size = UDim2.new(0, 135, 0, 15)

	InstantFlingPlr.Name = "InstantFling Plr"
	InstantFlingPlr.Parent = TargetScrollFrame
	InstantFlingPlr.BackgroundColor3 = Color3.new(0, 0, 0)
	InstantFlingPlr.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	InstantFlingPlr.Position = UDim2.new(0.749379456, 0, 0.240973935, 0)
	InstantFlingPlr.Size = UDim2.new(0, 135, 0, 26)
	InstantFlingPlr.Font = Enum.Font.SourceSans
	InstantFlingPlr.Text = "InstantFling Plr"
	InstantFlingPlr.TextColor3 = Color3.new(1, 1, 1)
	InstantFlingPlr.TextSize = 18
	InstantFlingPlr.MouseButton1Click:connect(function()


		if 	Onandoff_133.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_133.BackgroundColor3 = Color3.new(0, 1, 0)
			local instantflingtarget = findPlayer(TargetTextbox.Text)
			targetez = instantflingtarget.Name
			instantflingez = false
			game:GetService('RunService').Stepped:connect(function()
				if noclip then
					game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
				end
			end)		
			noclip = not noclip
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			if 			instantflingez == false then

				noti("It will not work because you used your hair/hat please reset")

			end
			instantflingez = true
			noti("You must wear a hat and hair to work!")
			spawn(function()
				while instantflingez ==  true do game:GetService("RunService").Heartbeat:wait()
					for i,v in pairs(game.Players:GetPlayers()) do
						if v == game.Players.LocalPlayer == false then
							game.Players.LocalPlayer.MaximumSimulationRadius = math.pow(math.huge,math.huge)*math.huge
							game.Players.LocalPlayer.SimulationRadius = math.pow(math.huge,math.huge)*math.huge
							v.MaximumSimulationRadius = 0
							v.SimulationRadius = 0
							game:GetService("RunService").Stepped:wait()
						end
					end
				end
			end)


			local Player = game:GetService("Players").LocalPlayer
			local mouse = Player:GetMouse()
			local Players = game:GetService("Players")
			local HatList = {}
			local i = 0
			for _,l in pairs(Player.Character:GetChildren()) do
				if l:IsA("Accessory") then if i>0 then l.Parent = workspace  end i = i + 1 end;
			end
			wait(.1)



			for _,v in pairs(workspace:GetDescendants()) do
				if v.Name == "Handle" and v:IsA("BasePart") and v.Parent:IsA("Accessory") and v:IsDescendantOf(Player.Character)==false and Players:GetPlayerFromCharacter(v.Parent.Parent)==nil then
					table.insert(HatList,v)
				end
			end

			for _,hat in pairs(HatList) do
				hat.Parent = workspace
				hat.Position = game.Players[targetez].Character.HumanoidRootPart.Position
				local BodyPos = Instance.new("BodyPosition",hat)
				local BodyAng = Instance.new("BodyAngularVelocity",hat)
				BodyAng.AngularVelocity = Vector3.new(0,9e12,0)
				BodyAng.P = 9e12
				BodyPos.MaxForce = Vector3.new(9e9,9e9,9e9)
				BodyPos.P = 9e8

				spawn(function()
					while instantflingez ==  true do

						if pcall(function()
								hat.CanCollide = false
								BodyPos.Position = game.Players[targetez].Character.HumanoidRootPart.Position + Vector3.new(math.random(-2,2),math.random(-2,2),math.random(-2,2))
							end) then
						else
							BodyPos:Destroy()
							hat.CanCollide = true
						end
						wait()
					end
				end)

			end


		else
			Onandoff_133.BackgroundColor3 = Color3.new(1, 0, 0)
			instantflingez =  false
			noclip = false
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		end

	end)

	Onandoff_133.Name = "Onandoff"
	Onandoff_133.Parent = InstantFlingPlr
	Onandoff_133.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_133.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_133.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_133.Size = UDim2.new(0, 135, 0, 15)

	AutoFlashPlr.Name = "AutoFlash Plr"
	AutoFlashPlr.Parent = TargetScrollFrame
	AutoFlashPlr.BackgroundColor3 = Color3.new(0, 0, 0)
	AutoFlashPlr.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	AutoFlashPlr.Position = UDim2.new(0.501445591, 0, 0.240973935, 0)
	AutoFlashPlr.Size = UDim2.new(0, 135, 0, 26)
	AutoFlashPlr.Font = Enum.Font.SourceSans
	AutoFlashPlr.Text = "AutoFlash Plr"
	AutoFlashPlr.TextColor3 = Color3.new(1, 1, 1)
	AutoFlashPlr.TextSize = 18
	AutoFlashPlr.MouseButton1Click:connect(function()
		if 	Onandoff_134.BackgroundColor3 == Color3.new(1, 0, 0)  then
			Onandoff_134.BackgroundColor3 = Color3.new(0, 1, 0)
			flying = false
			local TargetPlrs = TargetTextbox.Text
			local NIGGA = game:GetService("Players").LocalPlayer.PlayerGui.MainScreenGui

			ewrwewewewdsd=true
			repeat

				if NIGGA:FindFirstChild("whiteScreen") then
					NIGGA.whiteScreen:Destroy()
				end
				wait(0.2)

				local lol = game.Workspace.Ignored.Shop["[Flashbang] - $550"]
				game.Players.LocalPlayer.Character:MoveTo(lol.Head.Position)
				wait(0.25)
				fireclickdetector(lol.ClickDetector,4)
				wait(0.50)
				if game.Players.LocalPlayer.Backpack:FindFirstChild("[Flashbang]") then
					game.Players.LocalPlayer.Backpack:FindFirstChild("[Flashbang]").Parent = game.Players.LocalPlayer.Character
				end
				wait(.30)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[TargetPlrs].Character.HumanoidRootPart.CFrame
				wait(.2)
				game.Players.LocalPlayer.Character:FindFirstChild("[Flashbang]"):Activate()
				game.Players.LocalPlayer.Character:FindFirstChild("[Flashbang]"):Activate()
				wait(1)
			until ewrwewewewdsd==false




		else
			Onandoff_134.BackgroundColor3 = Color3.new(1, 0, 0)
			ewrwewewewdsd=false

		end

	end)

	Onandoff_134.Name = "Onandoff"
	Onandoff_134.Parent = AutoFlashPlr
	Onandoff_134.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_134.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_134.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_134.Size = UDim2.new(0, 135, 0, 15)

	AnimationScrollFrame.Name = "AnimationScrollFrame"
	AnimationScrollFrame.Parent = MainChild
	AnimationScrollFrame.Active = true
	AnimationScrollFrame.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	AnimationScrollFrame.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	AnimationScrollFrame.Position = UDim2.new(0.247117266, 0, 0.131311327, 0)
	AnimationScrollFrame.Size = UDim2.new(0, 605, 0, 295)
	AnimationScrollFrame.Visible = false
	AnimationScrollFrame.CanvasSize = UDim2.new(0, 0, 3, 0)
	Animate = game.Players.LocalPlayer.Character.Animate

	Ninja.Name = "Ninja"
	Ninja.Parent = AnimationScrollFrame
	Ninja.BackgroundColor3 = Color3.new(0, 0, 0)
	Ninja.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Ninja.Position = UDim2.new(0.0154951401, 0, 0.00896635652, 0)
	Ninja.Size = UDim2.new(0, 135, 0, 26)
	Ninja.Font = Enum.Font.SourceSans
	Ninja.Text = "Ninja"
	Ninja.TextColor3 = Color3.new(1, 1, 1)
	Ninja.TextSize = 18
	Ninja.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true	
	end)

	Onandoff_135.Name = "Onandoff"
	Onandoff_135.Parent = Ninja
	Onandoff_135.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_135.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_135.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_135.Size = UDim2.new(0, 135, 0, 15)

	Levitation.Name = "Levitation "
	Levitation.Parent = AnimationScrollFrame
	Levitation.BackgroundColor3 = Color3.new(0, 0, 0)
	Levitation.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Levitation.Position = UDim2.new(0.253511667, 0, 0.00896635652, 0)
	Levitation.Size = UDim2.new(0, 135, 0, 26)
	Levitation.Font = Enum.Font.SourceSans
	Levitation.Text = "Levitation"
	Levitation.TextColor3 = Color3.new(1, 1, 1)
	Levitation.TextSize = 18
	Levitation.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_136.Name = "Onandoff"
	Onandoff_136.Parent = Levitation
	Onandoff_136.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_136.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_136.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_136.Size = UDim2.new(0, 135, 0, 15)

	Stylish.Name = "Stylish"
	Stylish.Parent = AnimationScrollFrame
	Stylish.BackgroundColor3 = Color3.new(0, 0, 0)
	Stylish.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Stylish.Position = UDim2.new(0.729544759, 0, 0.00936925504, 0)
	Stylish.Size = UDim2.new(0, 135, 0, 26)
	Stylish.Font = Enum.Font.SourceSans
	Stylish.Text = "Stylish"
	Stylish.TextColor3 = Color3.new(1, 1, 1)
	Stylish.TextSize = 18
	Stylish.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_137.Name = "Onandoff"
	Onandoff_137.Parent = Stylish
	Onandoff_137.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_137.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_137.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_137.Size = UDim2.new(0, 135, 0, 15)

	Werewolf.Name = "Werewolf"
	Werewolf.Parent = AnimationScrollFrame
	Werewolf.BackgroundColor3 = Color3.new(0, 0, 0)
	Werewolf.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Werewolf.Position = UDim2.new(0.489875317, 0, 0.00936925504, 0)
	Werewolf.Size = UDim2.new(0, 135, 0, 26)
	Werewolf.Font = Enum.Font.SourceSans
	Werewolf.Text = "WereWolf"
	Werewolf.TextColor3 = Color3.new(1, 1, 1)
	Werewolf.TextSize = 18
	Werewolf.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_138.Name = "Onandoff"
	Onandoff_138.Parent = Werewolf
	Onandoff_138.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_138.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_138.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_138.Size = UDim2.new(0, 135, 0, 15)

	Robot.Name = "Robot"
	Robot.Parent = AnimationScrollFrame
	Robot.BackgroundColor3 = Color3.new(0, 0, 0)
	Robot.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Robot.Position = UDim2.new(0.0154951811, 0, 0.0661874413, 0)
	Robot.Size = UDim2.new(0, 135, 0, 26)
	Robot.Font = Enum.Font.SourceSans
	Robot.Text = "Robot"
	Robot.TextColor3 = Color3.new(1, 1, 1)
	Robot.TextSize = 18
	Robot.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_139.Name = "Onandoff"
	Onandoff_139.Parent = Robot
	Onandoff_139.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_139.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_139.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_139.Size = UDim2.new(0, 135, 0, 15)

	Bubbly.Name = "Bubbly"
	Bubbly.Parent = AnimationScrollFrame
	Bubbly.BackgroundColor3 = Color3.new(0, 0, 0)
	Bubbly.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Bubbly.Position = UDim2.new(0.253511667, 0, 0.0657845438, 0)
	Bubbly.Size = UDim2.new(0, 135, 0, 26)
	Bubbly.Font = Enum.Font.SourceSans
	Bubbly.Text = "Bubbly"
	Bubbly.TextColor3 = Color3.new(1, 1, 1)
	Bubbly.TextSize = 18
	Bubbly.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"
		Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"
		Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_140.Name = "Onandoff"
	Onandoff_140.Parent = Bubbly
	Onandoff_140.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_140.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_140.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_140.Size = UDim2.new(0, 135, 0, 15)

	Cartoony.Name = "Cartoony"
	Cartoony.Parent = AnimationScrollFrame
	Cartoony.BackgroundColor3 = Color3.new(0, 0, 0)
	Cartoony.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Cartoony.Position = UDim2.new(0.489875317, 0, 0.0661874413, 0)
	Cartoony.Size = UDim2.new(0, 135, 0, 26)
	Cartoony.Font = Enum.Font.SourceSans
	Cartoony.Text = "Cartoony"
	Cartoony.TextColor3 = Color3.new(1, 1, 1)
	Cartoony.TextSize = 18
	Cartoony.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_141.Name = "Onandoff"
	Onandoff_141.Parent = Cartoony
	Onandoff_141.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_141.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_141.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_141.Size = UDim2.new(0, 135, 0, 15)

	SuperHero.Name = "SuperHero"
	SuperHero.Parent = AnimationScrollFrame
	SuperHero.BackgroundColor3 = Color3.new(0, 0, 0)
	SuperHero.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	SuperHero.Position = UDim2.new(0.729544759, 0, 0.0661874413, 0)
	SuperHero.Size = UDim2.new(0, 135, 0, 26)
	SuperHero.Font = Enum.Font.SourceSans
	SuperHero.Text = "SuperHero"
	SuperHero.TextColor3 = Color3.new(1, 1, 1)
	SuperHero.TextSize = 18
	SuperHero.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_142.Name = "Onandoff"
	Onandoff_142.Parent = SuperHero
	Onandoff_142.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_142.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_142.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_142.Size = UDim2.new(0, 135, 0, 15)

	Zombie.Name = "Zombie"
	Zombie.Parent = AnimationScrollFrame
	Zombie.BackgroundColor3 = Color3.new(0, 0, 0)
	Zombie.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Zombie.Position = UDim2.new(0.253511667, 0, 0.1235497, 0)
	Zombie.Size = UDim2.new(0, 135, 0, 26)
	Zombie.Font = Enum.Font.SourceSans
	Zombie.Text = "Zombie"
	Zombie.TextColor3 = Color3.new(1, 1, 1)
	Zombie.TextSize = 18
	Zombie.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_143.Name = "Onandoff"
	Onandoff_143.Parent = Zombie
	Onandoff_143.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_143.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_143.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_143.Size = UDim2.new(0, 135, 0, 15)

	Knight.Name = "Knight"
	Knight.Parent = AnimationScrollFrame
	Knight.BackgroundColor3 = Color3.new(0, 0, 0)
	Knight.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Knight.Position = UDim2.new(0.0154951811, 0, 0.123952597, 0)
	Knight.Size = UDim2.new(0, 135, 0, 26)
	Knight.Font = Enum.Font.SourceSans
	Knight.Text = "Knight"
	Knight.TextColor3 = Color3.new(1, 1, 1)
	Knight.TextSize = 18
	Knight.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=657595757"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=657568135"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=657552124"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=657564596"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=658409194"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=658360781"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=657600338"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_144.Name = "Onandoff"
	Onandoff_144.Parent = Knight
	Onandoff_144.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_144.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_144.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_144.Size = UDim2.new(0, 135, 0, 15)

	Mage.Name = "Mage"
	Mage.Parent = AnimationScrollFrame
	Mage.BackgroundColor3 = Color3.new(0, 0, 0)
	Mage.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Mage.Position = UDim2.new(0.729544759, 0, 0.123952597, 0)
	Mage.Size = UDim2.new(0, 135, 0, 26)
	Mage.Font = Enum.Font.SourceSans
	Mage.Text = "Mage"
	Mage.TextColor3 = Color3.new(1, 1, 1)
	Mage.TextSize = 18
	Mage.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_145.Name = "Onandoff"
	Onandoff_145.Parent = Mage
	Onandoff_145.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_145.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_145.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_145.Size = UDim2.new(0, 135, 0, 15)

	Elder.Name = "Elder"
	Elder.Parent = AnimationScrollFrame
	Elder.BackgroundColor3 = Color3.new(0, 0, 0)
	Elder.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Elder.Position = UDim2.new(0.489875317, 0, 0.123952597, 0)
	Elder.Size = UDim2.new(0, 135, 0, 26)
	Elder.Font = Enum.Font.SourceSans
	Elder.Text = "Elder"
	Elder.TextColor3 = Color3.new(1, 1, 1)
	Elder.TextSize = 18
	Elder.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=845397899"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_146.Name = "Onandoff"
	Onandoff_146.Parent = Elder
	Onandoff_146.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_146.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_146.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_146.Size = UDim2.new(0, 135, 0, 15)

	Toy.Name = "Toy"
	Toy.Parent = AnimationScrollFrame
	Toy.BackgroundColor3 = Color3.new(0, 0, 0)
	Toy.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Toy.Position = UDim2.new(0.0154951811, 0, 0.185505629, 0)
	Toy.Size = UDim2.new(0, 135, 0, 26)
	Toy.Font = Enum.Font.SourceSans
	Toy.Text = "Toy"
	Toy.TextColor3 = Color3.new(1, 1, 1)
	Toy.TextSize = 18
	Toy.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_147.Name = "Onandoff"
	Onandoff_147.Parent = Toy
	Onandoff_147.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_147.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_147.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_147.Size = UDim2.new(0, 135, 0, 15)

	Astronaut.Name = "Astronaut"
	Astronaut.Parent = AnimationScrollFrame
	Astronaut.BackgroundColor3 = Color3.new(0, 0, 0)
	Astronaut.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Astronaut.Position = UDim2.new(0.253511667, 0, 0.185102731, 0)
	Astronaut.Size = UDim2.new(0, 135, 0, 26)
	Astronaut.Font = Enum.Font.SourceSans
	Astronaut.Text = "Astronaut"
	Astronaut.TextColor3 = Color3.new(1, 1, 1)
	Astronaut.TextSize = 18
	Astronaut.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_148.Name = "Onandoff"
	Onandoff_148.Parent = Astronaut
	Onandoff_148.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_148.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_148.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_148.Size = UDim2.new(0, 135, 0, 15)

	Pirate.Name = "Pirate"
	Pirate.Parent = AnimationScrollFrame
	Pirate.BackgroundColor3 = Color3.new(0, 0, 0)
	Pirate.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Pirate.Position = UDim2.new(0.489875317, 0, 0.185505629, 0)
	Pirate.Size = UDim2.new(0, 135, 0, 26)
	Pirate.Font = Enum.Font.SourceSans
	Pirate.Text = "Pirate"
	Pirate.TextColor3 = Color3.new(1, 1, 1)
	Pirate.TextSize = 18
	Pirate.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_149.Name = "Onandoff"
	Onandoff_149.Parent = Pirate
	Onandoff_149.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_149.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_149.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_149.Size = UDim2.new(0, 135, 0, 15)

	Vampire.Name = "Vampire"
	Vampire.Parent = AnimationScrollFrame
	Vampire.BackgroundColor3 = Color3.new(0, 0, 0)
	Vampire.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Vampire.Position = UDim2.new(0.729544759, 0, 0.185505629, 0)
	Vampire.Size = UDim2.new(0, 135, 0, 26)
	Vampire.Font = Enum.Font.SourceSans
	Vampire.Text = "Vampire"
	Vampire.TextColor3 = Color3.new(1, 1, 1)
	Vampire.TextSize = 18
	Vampire.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_150.Name = "Onandoff"
	Onandoff_150.Parent = Vampire
	Onandoff_150.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_150.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_150.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_150.Size = UDim2.new(0, 135, 0, 15)

	Popstar.Name = "Popstar"
	Popstar.Parent = AnimationScrollFrame
	Popstar.BackgroundColor3 = Color3.new(0, 0, 0)
	Popstar.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Popstar.Position = UDim2.new(0.0154951811, 0, 0.248005629, 0)
	Popstar.Size = UDim2.new(0, 135, 0, 26)
	Popstar.Font = Enum.Font.SourceSans
	Popstar.Text = "Popstar"
	Popstar.TextColor3 = Color3.new(1, 1, 1)
	Popstar.TextSize = 18
	Popstar.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1212900985"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980338"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980348"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1212954642"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1213044953"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1212900995"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_151.Name = "Onandoff"
	Onandoff_151.Parent = Popstar
	Onandoff_151.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_151.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_151.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_151.Size = UDim2.new(0, 135, 0, 15)

	Patrol.Name = "Patrol"
	Patrol.Parent = AnimationScrollFrame
	Patrol.BackgroundColor3 = Color3.new(0, 0, 0)
	Patrol.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Patrol.Position = UDim2.new(0.253511667, 0, 0.247602731, 0)
	Patrol.Size = UDim2.new(0, 135, 0, 26)
	Patrol.Font = Enum.Font.SourceSans
	Patrol.Text = "Patrol"
	Patrol.TextColor3 = Color3.new(1, 1, 1)
	Patrol.TextSize = 18
	Patrol.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1149612882"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1151231493"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1150967949"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1148863382"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_152.Name = "Onandoff"
	Onandoff_152.Parent = Patrol
	Onandoff_152.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_152.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_152.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_152.Size = UDim2.new(0, 135, 0, 15)

	Confident.Name = "Confident"
	Confident.Parent = AnimationScrollFrame
	Confident.BackgroundColor3 = Color3.new(0, 0, 0)
	Confident.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Confident.Position = UDim2.new(0.489875317, 0, 0.248005629, 0)
	Confident.Size = UDim2.new(0, 135, 0, 26)
	Confident.Font = Enum.Font.SourceSans
	Confident.Text = "Confident"
	Confident.TextColor3 = Color3.new(1, 1, 1)
	Confident.TextSize = 18
	Confident.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1069977950"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1069987858"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1070017263"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1070001516"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1069984524"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1069946257"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1069973677"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_153.Name = "Onandoff"
	Onandoff_153.Parent = Confident
	Onandoff_153.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_153.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_153.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_153.Size = UDim2.new(0, 135, 0, 15)

	Sneaky.Name = "Sneaky"
	Sneaky.Parent = AnimationScrollFrame
	Sneaky.BackgroundColor3 = Color3.new(0, 0, 0)
	Sneaky.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Sneaky.Position = UDim2.new(0.729544759, 0, 0.248005629, 0)
	Sneaky.Size = UDim2.new(0, 135, 0, 26)
	Sneaky.Font = Enum.Font.SourceSans
	Sneaky.Text = "Sneaky"
	Sneaky.TextColor3 = Color3.new(1, 1, 1)
	Sneaky.TextSize = 18
	Sneaky.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1132473842"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1132477671"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1132510133"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1132494274"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1132489853"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1132461372"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1132469004"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_154.Name = "Onandoff"
	Onandoff_154.Parent = Sneaky
	Onandoff_154.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_154.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_154.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_154.Size = UDim2.new(0, 135, 0, 15)

	None.Name = "None"
	None.Parent = AnimationScrollFrame
	None.BackgroundColor3 = Color3.new(0, 0, 0)
	None.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	None.Position = UDim2.new(0.729544759, 0, 0.30955866, 0)
	None.Size = UDim2.new(0, 135, 0, 26)
	None.Font = Enum.Font.SourceSans
	None.Text = "None"
	None.TextColor3 = Color3.new(1, 1, 1)
	None.TextSize = 18
	None.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=0"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)
	Onandoff_155.Name = "Onandoff"
	Onandoff_155.Parent = None
	Onandoff_155.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_155.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_155.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_155.Size = UDim2.new(0, 135, 0, 15)

	Ghost.Name = "Ghost"
	Ghost.Parent = AnimationScrollFrame
	Ghost.BackgroundColor3 = Color3.new(0, 0, 0)
	Ghost.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Ghost.Position = UDim2.new(0.489875317, 0, 0.30955866, 0)
	Ghost.Size = UDim2.new(0, 135, 0, 26)
	Ghost.Font = Enum.Font.SourceSans
	Ghost.Text = "Ghost"
	Ghost.TextColor3 = Color3.new(1, 1, 1)
	Ghost.TextSize = 18
	Ghost.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
		Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=616012453"
		Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=616011509"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_156.Name = "Onandoff"
	Onandoff_156.Parent = Ghost
	Onandoff_156.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_156.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_156.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_156.Size = UDim2.new(0, 135, 0, 15)

	Cowboy.Name = "Cowboy"
	Cowboy.Parent = AnimationScrollFrame
	Cowboy.BackgroundColor3 = Color3.new(0, 0, 0)
	Cowboy.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Cowboy.Position = UDim2.new(0.253511667, 0, 0.309155762, 0)
	Cowboy.Size = UDim2.new(0, 135, 0, 26)
	Cowboy.Font = Enum.Font.SourceSans
	Cowboy.Text = "Cowboy"
	Cowboy.TextColor3 = Color3.new(1, 1, 1)
	Cowboy.TextSize = 18
	Cowboy.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1014390418"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1014398616"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1014421541"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1014401683"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1014394726"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1014380606"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1014384571"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_157.Name = "Onandoff"
	Onandoff_157.Parent = Cowboy
	Onandoff_157.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_157.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_157.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_157.Size = UDim2.new(0, 135, 0, 15)

	Princess.Name = "Princess"
	Princess.Parent = AnimationScrollFrame
	Princess.BackgroundColor3 = Color3.new(0, 0, 0)
	Princess.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Princess.Position = UDim2.new(0.0154951811, 0, 0.30955866, 0)
	Princess.Size = UDim2.new(0, 135, 0, 26)
	Princess.Font = Enum.Font.SourceSans
	Princess.Text = "Princess"
	Princess.TextColor3 = Color3.new(1, 1, 1)
	Princess.TextSize = 18
	Princess.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=941003647"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=941013098"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=941028902"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=941015281"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=941008832"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=940996062"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=941000007"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Onandoff_158.Name = "Onandoff"
	Onandoff_158.Parent = Princess
	Onandoff_158.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_158.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_158.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_158.Size = UDim2.new(0, 135, 0, 15)

	Anthro.Name = "Anthro"
	Anthro.Parent = AnimationScrollFrame
	Anthro.BackgroundColor3 = Color3.new(0, 0, 0)
	Anthro.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	Anthro.Position = UDim2.new(0.0154951811, 0, 0.366376847, 0)
	Anthro.Size = UDim2.new(0, 135, 0, 26)
	Anthro.Font = Enum.Font.SourceSans
	Anthro.Text = "Anthro"
	Anthro.TextColor3 = Color3.new(1, 1, 1)
	Anthro.TextSize = 18
	Anthro.MouseButton1Click:connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=2510196951"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=2510197257"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=2510202577"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=2510198475"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=2510197830"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=2510192778"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=2510195892"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true	end)

	Onandoff_159.Name = "Onandoff"
	Onandoff_159.Parent = Anthro
	Onandoff_159.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
	Onandoff_159.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_159.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_159.Size = UDim2.new(0, 135, 0, 15)

	CreditsScrollFrame.Name = "CreditsScrollFrame"
	CreditsScrollFrame.Parent = MainChild
	CreditsScrollFrame.Active = true
	CreditsScrollFrame.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	CreditsScrollFrame.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	CreditsScrollFrame.Position = UDim2.new(0.247117221, 0, 0.0254765432, 0)
	CreditsScrollFrame.Size = UDim2.new(0, 605, 0, 333)
	CreditsScrollFrame.Visible = false

	TextLabel.Parent = CreditsScrollFrame
	TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
	TextLabel.BackgroundTransparency = 1
	TextLabel.Position = UDim2.new(0.0545454547, 0, 0.0184659064, 0)
	TextLabel.Size = UDim2.new(0, 200, 0, 50)
	TextLabel.Font = Enum.Font.SourceSans
	TextLabel.Text = "Owner: RushKara#3999"
	TextLabel.TextColor3 = Color3.new(1, 1, 1)
	TextLabel.TextSize = 30

	TextLabel_2.Parent = CreditsScrollFrame
	TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)
	TextLabel_2.BackgroundTransparency = 1
	TextLabel_2.Position = UDim2.new(0.0776859522, 0, 0.200284094, 0)
	TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
	TextLabel_2.Font = Enum.Font.SourceSans
	TextLabel_2.Text = "Designer: RushKara#3999"
	TextLabel_2.TextColor3 = Color3.new(1, 1, 1)
	TextLabel_2.TextSize = 30

	TextLabel_3.Parent = CreditsScrollFrame
	TextLabel_3.BackgroundColor3 = Color3.new(1, 1, 1)
	TextLabel_3.BackgroundTransparency = 1
	TextLabel_3.Position = UDim2.new(0.267768592, 0, 0.370738626, 0)
	TextLabel_3.Size = UDim2.new(0, 200, 0, 50)
	TextLabel_3.Font = Enum.Font.SourceSans
	TextLabel_3.Text = "New Design Of Polakya Time of work 4/28 - 5/15"
	TextLabel_3.TextColor3 = Color3.new(0.333333, 1, 0)
	TextLabel_3.TextSize = 30

	SettingsScrollFrame.Name = "SettingsScrollFrame"
	SettingsScrollFrame.Parent = MainChild
	SettingsScrollFrame.Active = true
	SettingsScrollFrame.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	SettingsScrollFrame.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	SettingsScrollFrame.Position = UDim2.new(0.244629666, 0, 0.0254765432, 0)
	SettingsScrollFrame.Size = UDim2.new(0, 605, 0, 333)
	SettingsScrollFrame.Visible = false

	ButtonDraggable.Name = "Button Draggable"
	ButtonDraggable.Parent = SettingsScrollFrame
	ButtonDraggable.BackgroundColor3 = Color3.new(0, 0, 0)
	ButtonDraggable.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	ButtonDraggable.Position = UDim2.new(0.0121894302, 0, 0.021276921, 0)
	ButtonDraggable.Size = UDim2.new(0, 135, 0, 26)
	ButtonDraggable.Font = Enum.Font.SourceSans
	ButtonDraggable.Text = "Button Draggable"
	ButtonDraggable.TextColor3 = Color3.new(1, 1, 1)
	ButtonDraggable.TextSize = 18
	ButtonDraggable.MouseButton1Click:connect(function()
		local draggebutton = false

		if Onandoff_160.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_160.BackgroundColor3 = Color3.new(0, 1, 0)
			draggebutton = true

		else
			Onandoff_160.BackgroundColor3 = Color3.new(1, 0, 0)
			draggebutton = false


		end




		local function opalo() -- MainFrame.LocalScript 
			local script = Instance.new('LocalScript', MovementScrollFrame)

			local scroll = MainChild

			-- if it has text
			local buttons = scroll:GetDescendants() -- all of the buttons

			for _, button in pairs(buttons) do -- loops through the buttons
				if button:IsA("TextButton") then
					if 	draggebutton == true then
						button.Active = true
						button.Draggable = true

					else
						button.Active = false
						button.Draggable = false
					end
				end
			end


		end
		coroutine.wrap(opalo)()

	end)

	Onandoff_160.Name = "Onandoff"
	Onandoff_160.Parent = ButtonDraggable
	Onandoff_160.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_160.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_160.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_160.Size = UDim2.new(0, 135, 0, 15)

	FrameDraggable.Name = "Frame Draggable"
	FrameDraggable.Parent = SettingsScrollFrame
	FrameDraggable.BackgroundColor3 = Color3.new(0, 0, 0)
	FrameDraggable.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	FrameDraggable.Position = UDim2.new(0.248553082, 0, 0.021276921, 0)
	FrameDraggable.Size = UDim2.new(0, 135, 0, 26)
	FrameDraggable.Font = Enum.Font.SourceSans
	FrameDraggable.Text = "Frame Draggable"
	FrameDraggable.TextColor3 = Color3.new(1, 1, 1)
	FrameDraggable.TextSize = 18
	FrameDraggable.MouseButton1Click:connect(function()
		local draggebutton2 = false

		if Onandoff_161.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_161.BackgroundColor3 = Color3.new(0, 1, 0)
			draggebutton2 = true

		else
			Onandoff_161.BackgroundColor3 = Color3.new(1, 0, 0)
			draggebutton2 = false


		end




		local function opalo() -- MainFrame.LocalScript 
			local script = Instance.new('LocalScript', MovementScrollFrame)

			local scroll = Ezpolakyascreengui

			-- if it has text
			local buttons = scroll:GetDescendants() -- all of the buttons

			for _, button in pairs(buttons) do -- loops through the buttons
				if button:IsA("Frame") then
					if 	draggebutton2 == true then
						button.Active = true
						button.Draggable = true

					else
						button.Active = false
						button.Draggable = false
					end
				end
			end


		end
		coroutine.wrap(opalo)()

	end)

	Onandoff_161.Name = "Onandoff"
	Onandoff_161.Parent = FrameDraggable
	Onandoff_161.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_161.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_161.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_161.Size = UDim2.new(0, 135, 0, 15)

	NameScript.Name = "Name Script"
	NameScript.Parent = SettingsScrollFrame
	NameScript.BackgroundColor3 = Color3.new(0, 0, 0)
	NameScript.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	NameScript.Position = UDim2.new(0.48822251, 0, 0.021276921, 0)
	NameScript.Size = UDim2.new(0, 135, 0, 26)
	NameScript.Font = Enum.Font.SourceSans
	NameScript.Text = "soon"
	NameScript.TextColor3 = Color3.new(1, 1, 1)
	NameScript.TextSize = 18
	NameScript.MouseButton1Click:connect(function()

	end)

	TextBox_2.Parent = NameScript
	TextBox_2.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	TextBox_2.BorderColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	TextBox_2.Position = UDim2.new(0, 0, 1, 0)
	TextBox_2.Size = UDim2.new(0, 135, 0, 15)
	TextBox_2.Font = Enum.Font.SourceSans
	TextBox_2.PlaceholderColor3 = Color3.new(1, 1, 1)
	TextBox_2.PlaceholderText = ""
	TextBox_2.Text = ""
	TextBox_2.TextColor3 = Color3.new(1, 1, 1)
	TextBox_2.TextSize = 16

	RemoveGlows.Name = "Remove Glows"
	RemoveGlows.Parent = SettingsScrollFrame
	RemoveGlows.BackgroundColor3 = Color3.new(0, 0, 0)
	RemoveGlows.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	RemoveGlows.Position = UDim2.new(0.726239026, 0, 0.021276921, 0)
	RemoveGlows.Size = UDim2.new(0, 135, 0, 26)
	RemoveGlows.Font = Enum.Font.SourceSans
	RemoveGlows.Text = "Remove Glow"
	RemoveGlows.TextColor3 = Color3.new(1, 1, 1)
	RemoveGlows.TextSize = 18

	Onandoff_162.Name = "Onandoff"
	Onandoff_162.Parent = RemoveGlows
	Onandoff_162.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_162.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_162.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_162.Size = UDim2.new(0, 135, 0, 15)

	RainbowName.Name = "Rainbow Name"
	RainbowName.Parent = SettingsScrollFrame
	RainbowName.BackgroundColor3 = Color3.new(0, 0, 0)
	RainbowName.BorderColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
	RainbowName.Position = UDim2.new(0.0105365515, 0, 0.106504194, 0)
	RainbowName.Size = UDim2.new(0, 135, 0, 26)
	RainbowName.Font = Enum.Font.SourceSans
	RainbowName.Text = "Rainbow Name"
	RainbowName.TextColor3 = Color3.new(1, 1, 1)
	RainbowName.TextSize = 18
	RainbowName.MouseButton1Click:connect(function()
		if Onandoff_163.BackgroundColor3 == Color3.new(1, 0, 0) then
			Onandoff_163.BackgroundColor3 = Color3.new(0, 1, 0)
			ezraindbow = true
			function zigzag(X) return math.acos(math.cos(X*math.pi))/math.pi end

			counter = 0

			while wait(0.1)do
				if ezraindbow == true
				then
					TextLabel_4.TextColor3 = Color3.fromHSV(zigzag(counter),1,1)
					TextLabel_5.TextColor3 = Color3.fromHSV(zigzag(counter),1,1)
					Frame.BorderColor3 = Color3.fromHSV(zigzag(counter),1,1)

					counter = counter + 0.01
				end
			end
		else
			Onandoff_163.BackgroundColor3 = Color3.new(1, 0, 0)
			ezraindbow = false
			TextLabel_4.TextColor3 = Color3.new(0, 0, 0)
			TextLabel_5.TextColor3 = Color3.new(0, 0, 0)
			Frame.BorderColor3 = Color3.new(0, 0, 0)

		end
	end)

	Onandoff_163.Name = "Onandoff"
	Onandoff_163.Parent = RainbowName
	Onandoff_163.BackgroundColor3 = Color3.new(1, 0, 0)
	Onandoff_163.BorderColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Onandoff_163.Position = UDim2.new(0, 0, 1, 0)
	Onandoff_163.Size = UDim2.new(0, 135, 0, 15)

	TextLabel_4.Parent = Main
	TextLabel_4.BackgroundColor3 = Color3.new(1, 1, 1)
	TextLabel_4.BackgroundTransparency = 1
	TextLabel_4.Position = UDim2.new(0.0233644843, 0, 0, 0)
	TextLabel_4.Size = UDim2.new(0, 70, 0, 32)
	TextLabel_4.Font = Enum.Font.SourceSans
	TextLabel_4.Text = "Polakya"
	TextLabel_4.TextColor3 = Color3.new(0, 0, 0)
	TextLabel_4.TextSize = 30

	Frame.Parent = Main
	Frame.BackgroundColor3 = Color3.new(1, 1, 1)
	Frame.Position = UDim2.new(0.0093457941, 0, 0.744186044, 0)
	Frame.Size = UDim2.new(0, 89, 0, 0)

	TextLabel_5.Parent = Main
	TextLabel_5.BackgroundColor3 = Color3.new(1, 1, 1)
	TextLabel_5.BackgroundTransparency = 1
	TextLabel_5.Position = UDim2.new(0.119368121, 0, 0.372093022, 0)
	TextLabel_5.Size = UDim2.new(0, 37, 0, 27)
	TextLabel_5.Font = Enum.Font.SourceSans
	TextLabel_5.Text = "4.0A"
	TextLabel_5.TextColor3 = Color3.new(0, 0, 0)
	TextLabel_5.TextSize = 14

	Close.Name = "Close"
	Close.Parent = Main
	Close.BackgroundColor3 = Color3.new(0, 0, 0)
	Close.BackgroundTransparency = 1
	Close.Position = UDim2.new(0.951713383, 0, 0.186046511, 0)
	Close.Size = UDim2.new(0, 23, 0, 24)
	Close.Font = Enum.Font.SourceSans
	Close.Text = "X"
	Close.TextColor3 = Color3.new(0, 0, 0)
	Close.TextSize = 22
	Close.MouseButton1Click:connect(function()

		Main:TweenPosition(UDim2.new(0,0,-17,0),"In","Quart",1)
		wait(1)
		Main:Destroy()
	end)

	Close.MouseEnter:connect(function()
		Close.BackgroundTransparency = 0
		Close.TextColor3 = Color3.new(1, 1, 1)


	end)

	Close.MouseLeave:connect(function()
		Close.BackgroundTransparency = 1
		Close.TextColor3 = Color3.new(0, 0, 0)

	end)




	FullMinimize.Name = "Full Minimize"
	FullMinimize.Parent = Main
	FullMinimize.BackgroundColor3 = Color3.new(1, 1, 1)
	FullMinimize.BackgroundTransparency = 1
	FullMinimize.Position = UDim2.new(0.922083497, 0, 0.186046511, 0)
	FullMinimize.Size = UDim2.new(0, 22, 0, 24)
	FullMinimize.Font = Enum.Font.SourceSans
	FullMinimize.Text = "-"
	FullMinimize.TextColor3 = Color3.new(0, 0, 0)
	FullMinimize.TextSize = 24
	FullMinimize.MouseButton1Click:connect(function()
		ezoldpos = Main.Position
		Main:TweenPosition(UDim2.new(977,0,0,0),"In","Quart",1)
		wait(.3)

		MINIMIZEBUTTON.Visible = true

	end)

	minimizebuttonuicorner = Instance.new("UICorner")
	minimizebuttonuicorner.Parent = MINIMIZEBUTTON
	minimizebuttonuicorner.CornerRadius = UDim.new(10, 8)
	MINIMIZEBUTTON.Visible = false
	MINIMIZEBUTTON.Name = "MINIMIZEBUTTON"
	MINIMIZEBUTTON.Parent = Ezpolakyascreengui
	MINIMIZEBUTTON.BackgroundColor3 = Color3.new(0, 0, 0)
	MINIMIZEBUTTON.BorderColor3 = Color3.new(0, 0, 0)
	MINIMIZEBUTTON.Position = UDim2.new(0.95575738, 0, 0.0291438978, 0)
	MINIMIZEBUTTON.Size = UDim2.new(0, 81, 0, 50)
	MINIMIZEBUTTON.Font = Enum.Font.SourceSans
	MINIMIZEBUTTON.Text = "   <"
	MINIMIZEBUTTON.TextColor3 = Color3.new(1, 1, 1)
	MINIMIZEBUTTON.TextSize = 40
	MINIMIZEBUTTON.TextXAlignment = Enum.TextXAlignment.Left
	MINIMIZEBUTTON.MouseButton1Click:connect(function()
		wait(.2)
		MINIMIZEBUTTON.Visible = false
		Main:TweenPosition(UDim2.new(ezoldpos),"In","Quart",1)


	end)



	TargetTextbox.Name = "TargetTextbox"
	TargetTextbox.Parent = Main
	TargetTextbox.BackgroundColor3 = Color3.new(0, 0, 0)
	TargetTextbox.BorderColor3 = Color3.new(0, 0, 0)
	TargetTextbox.Position = UDim2.new(0.247117266, 0, 1.19195008, 0)
	TargetTextbox.Size = UDim2.new(0, 559, 0, 25)
	TargetTextbox.Visible = false
	TargetTextbox.Font = Enum.Font.SourceSans
	TargetTextbox.PlaceholderColor3 = Color3.new(1, 1, 1)
	TargetTextbox.PlaceholderText = "Player Name"
	TargetTextbox.Text = ""
	TargetTextbox.TextColor3 = Color3.new(1, 1, 1)
	TargetTextbox.TextSize = 20
	local function ShrinkName()
		TargetTextbox.FocusLost:connect(function()
			for i,v in pairs(game.Players:GetChildren()) do
				if (string.sub(string.lower(v.Name),1,string.len(TargetTextbox.Text))) == string.lower(TargetTextbox.Text) then
					TargetTextbox.Text = v.Name
				end

			end
		end)
	end
	ShrinkName()
	TimesBuy.Name = "TimesBuy"
	TimesBuy.Parent = Main
	TimesBuy.BackgroundColor3 = Color3.new(0, 0, 0)
	TimesBuy.BorderColor3 = Color3.new(0, 0, 0)
	TimesBuy.Position = UDim2.new(0.247117266, 0, 1.19195008, 0)
	TimesBuy.Size = UDim2.new(0, 559, 0, 25)
	TimesBuy.Visible = false
	TimesBuy.Font = Enum.Font.SourceSans
	TimesBuy.PlaceholderColor3 = Color3.new(1, 1, 1)
	TimesBuy.PlaceholderText = "Put How Many Times You Want to Buy Here"
	TimesBuy.Text = ""
	TimesBuy.TextColor3 = Color3.new(1, 1, 1)
	TimesBuy.TextSize = 20


	glow.Name = "glow"
	glow.Parent = MainChild
	glow.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	glow.BackgroundTransparency = 1
	glow.BorderSizePixel = 0
	glow.Position = UDim2.new(0, -15, 0, -15)
	glow.Size = UDim2.new(1, 30, 1, 30)
	glow.Image = "rbxassetid://5028857084"
	glow.ImageColor3 = Color3.fromRGB(0, 0, 0)
	glow.ScaleType = Enum.ScaleType.Slice
	glow.ZIndex = 33
	glow.SliceCenter = Rect.new(24, 24, 276, 276)



elseif game.PlaceId == 142823291 then
	ScreenGui = Instance.new("ScreenGui")
	Mian = Instance.new("Frame")
	Stick = Instance.new("Frame")
	Close = Instance.new("TextButton")
	Logo = Instance.new("TextLabel")
	Page1 = Instance.new("TextButton")
	Stick_2 = Instance.new("Frame")
	Page1Frame = Instance.new("Frame")
	Page1Scrollinframe = Instance.new("ScrollingFrame")
	Flyx = Instance.new("TextButton")
	OffoOn = Instance.new("Frame")
	GunGrabber = Instance.new("TextButton")
	OffoOn_2 = Instance.new("Frame")
	CoinFarm = Instance.new("TextButton")
	OffoOn_3 = Instance.new("Frame")
	Noclip = Instance.new("TextButton")
	OffoOn_4 = Instance.new("Frame")
	MurderEsp = Instance.new("TextButton")
	OffoOn_5 = Instance.new("Frame")
	Tptolobby = Instance.new("TextButton")
	OffoOn_6 = Instance.new("Frame")
	SherrifEsp = Instance.new("TextButton")
	OffoOn_7 = Instance.new("Frame")
	KillAll = Instance.new("TextButton")
	OffoOn_8 = Instance.new("Frame")
	TpTOMAP = Instance.new("TextButton")
	OffoOn_9 = Instance.new("Frame")
	TpTosherrif = Instance.new("TextButton")
	OffoOn_10 = Instance.new("Frame")
	Tptomurder = Instance.new("TextButton")
	OffoOn_11 = Instance.new("Frame")
	Walkspeed = Instance.new("TextButton")
	TextBoxforwalkspeed = Instance.new("TextBox")
	Jumppower = Instance.new("TextButton")
	TextBoxforjumpower = Instance.new("TextBox")
	TpTo = Instance.new("TextButton")
	Targetplayer = Instance.new("TextBox")
	Spectate = Instance.new("TextButton")
	SpectatePlr = Instance.new("TextBox")
	Mousetp = Instance.new("TextButton")
	OffoOn_12 = Instance.new("Frame")
	Stick_3 = Instance.new("TextButton")
	OffoOn_13 = Instance.new("Frame")
	Godmode = Instance.new("TextButton")
	OffoOn_14 = Instance.new("Frame")
	Home = Instance.new("TextButton")
	HOMEFrame = Instance.new("Frame")
	Welcome = Instance.new("TextLabel")
	Playerimage = Instance.new("ImageLabel")
	Update = Instance.new("TextLabel")
	Noupdates = Instance.new("TextLabel")
	Xray = Instance.new("TextButton")
	OffoOn_15 = Instance.new("Frame")

	function findPlayer(name)
		name = name:lower()
		if name == 'me' then
			return game:GetService'Players'.LocalPlayer
		end
		for i,v in pairs(game:GetService'Players':GetPlayers()) do
			if v.Name:lower():find(name) == 1 then
				return v
			end
		end
	end

	ScreenGui.Parent = game.CoreGui
	ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

	Mian.Name = "Mian"
	Mian.Parent = ScreenGui
	Mian.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
	Mian.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
	Mian.Position = UDim2.new(0.137724549, 0, 0.233151183, 0)
	Mian.Size = UDim2.new(0, 579, 0, 362)
	Mian.Active = true
	Mian.Draggable = true

	Stick.Name = "Stick"
	Stick.Parent = Mian
	Stick.BackgroundColor3 = Color3.new(1, 1, 1)
	Stick.BorderColor3 = Color3.new(1, 1, 1)
	Stick.Position = UDim2.new(0, 0, 0.0994475111, 0)
	Stick.Size = UDim2.new(0, 579, 0, 0)

	Close.Name = "Close"
	Close.Parent = Mian
	Close.BackgroundColor3 = Color3.new(1, 0, 0)
	Close.BackgroundTransparency = 1
	Close.Position = UDim2.new(0.936096668, 0, 0.0193370171, 0)
	Close.Size = UDim2.new(0, 29, 0, 23)
	Close.Font = Enum.Font.SourceSans
	Close.Text = "X"
	Close.TextColor3 = Color3.new(1, 1, 1)
	Close.TextSize = 20
	Close.MouseButton1Click:connect(function()
		Mian:TweenPosition(UDim2.new(0,0,-17,0),"In","Quart",1)
		wait(1)
		Mian:Destroy()

	end)

	Close.MouseEnter:connect(function()
		Close.BackgroundTransparency = 0

	end)
	Close.MouseLeave:connect(function()
		Close.BackgroundTransparency = 1

	end)

	Logo.Name = "Logo"
	Logo.Parent = Mian
	Logo.BackgroundColor3 = Color3.new(1, 1, 1)
	Logo.BackgroundTransparency = 1
	Logo.Position = UDim2.new(0.010362694, 0, 0.0193370171, 0)
	Logo.Size = UDim2.new(0, 32, 0, 23)
	Logo.Font = Enum.Font.SourceSans
	Logo.Text = "P"
	Logo.TextColor3 = Color3.new(1, 1, 1)
	Logo.TextSize = 50
	local function IFTKRE_fake_script() -- ImageLabel.LocalScript 
		local script = Instance.new('LocalScript', Logo)

		while true do
			wait()
			script.Parent.Rotation = script.Parent.Rotation + 5
		end
	end
	coroutine.wrap(IFTKRE_fake_script)()

	Page1.Name = "Page1"
	Page1.Parent = Mian
	Page1.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Page1.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Page1.Position = UDim2.new(0.208981007, 0, 0.132596686, 0)
	Page1.Size = UDim2.new(0, 89, 0, 24)
	Page1.Font = Enum.Font.SourceSans
	Page1.Text = "Page1"
	Page1.TextColor3 = Color3.new(1, 1, 1)
	Page1.TextSize = 20
	Page1.MouseButton1Click:connect(function()
		Page1.TextColor3 = Color3.new(0, 1, 0)
		Home.TextColor3 = Color3.new(1, 1, 1)

		Page1Frame.Visible = true
		HOMEFrame.Visible = false
	end)

	Stick_2.Name = "Stick"
	Stick_2.Parent = Mian
	Stick_2.BackgroundColor3 = Color3.new(1, 1, 1)
	Stick_2.BorderColor3 = Color3.new(1, 1, 1)
	Stick_2.Position = UDim2.new(0, 0, 0.226519346, 0)
	Stick_2.Size = UDim2.new(0, 579, 0, 0)

	Page1Frame.Name = "Page1Frame"
	Page1Frame.Parent = Mian
	Page1Frame.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
	Page1Frame.BorderColor3 = Color3.new(1, 1, 1)
	Page1Frame.Position = UDim2.new(0, 0, 0.254143655, 0)
	Page1Frame.Size = UDim2.new(0, 579, 0, 270)
	Page1Frame.Visible = false

	Page1Scrollinframe.Name = "Page1Scrollinframe"
	Page1Scrollinframe.Parent = Page1Frame
	Page1Scrollinframe.Active = true
	Page1Scrollinframe.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
	Page1Scrollinframe.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
	Page1Scrollinframe.Size = UDim2.new(0, 579, 0, 270)
	Page1Scrollinframe.ScrollBarThickness = 5

	Flyx.Name = "Fly x"
	Flyx.Parent = Page1Scrollinframe
	Flyx.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Flyx.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Flyx.Position = UDim2.new(0.0310881138, 0, 0.141855925, 0)
	Flyx.Size = UDim2.new(0, 89, 0, 24)
	Flyx.Font = Enum.Font.SourceSans
	Flyx.Text = "Fly [X]"
	Flyx.TextColor3 = Color3.new(1, 1, 1)
	Flyx.TextScaled = true
	Flyx.TextSize = 20
	Flyx.TextWrapped = true
	Flyx.MouseButton1Click:connect(function()

		repeat wait() 
		until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Head") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid") 
		local mouse = game.Players.LocalPlayer:GetMouse() 
		repeat wait() until mouse
		local plr = game.Players.LocalPlayer 
		local torso = plr.Character.Head 
		local flying = false
		local deb = true 
		local ctrl = {f = 0, b = 0, l = 0, r = 0} 
		local lastctrl = {f = 0, b = 0, l = 0, r = 0} 
		local maxspeed = 5000
		local speed = 5000 

		function Fly() 
			local bg = Instance.new("BodyGyro", torso) 
			bg.P = 9e4 
			bg.maxTorque = Vector3.new(9e9, 9e9, 9e9) 
			bg.cframe = torso.CFrame 
			local bv = Instance.new("BodyVelocity", torso) 
			bv.velocity = Vector3.new(0,0.1,0) 
			bv.maxForce = Vector3.new(9e9, 9e9, 9e9) 
			repeat wait() 
				plr.Character.Humanoid.PlatformStand = true 
				if ctrl.l + ctrl.r ~= 100000 or ctrl.f + ctrl.b ~= 10000 then 
					speed = speed+.0+(speed/maxspeed) 
					if speed > maxspeed then 
						speed = maxspeed 
					end 
				elseif not (ctrl.l + ctrl.r ~= 5 or ctrl.f + ctrl.b ~= 5) and speed ~= 5 then 
					speed = speed-5
					if speed > 5 then 
						speed = -2 
					end 
				end 
				if (ctrl.l + ctrl.r) ~= 5 or (ctrl.f + ctrl.b) ~= 5 then 
					bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed 
					lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r} 
				elseif (ctrl.l + ctrl.r) == 5 and (ctrl.f + ctrl.b) == 5 and speed ~= 5 then 
					bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed 
				else 
					bv.velocity = Vector3.new(0,0.1,0) 
				end 
				bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0) 
			until not flying 
			ctrl = {f = 0, b = 0, l = 0, r = 0} 
			lastctrl = {f = 0, b = 0, l = 0, r = 0} 
			speed = 5 
			bg:Destroy() 
			bv:Destroy() 
			plr.Character.Humanoid.PlatformStand = false 
		end 
		mouse.KeyDown:connect(function(key) 
			if key:lower() == "x" then 
				if flying then flying = false 
					OffoOn.BackgroundColor3 = Color3.new(1, 0, 0)
					OffoOn.BorderColor3 = Color3.new(1, 0, 0)

				else 
					flying = true 
					OffoOn.BackgroundColor3 = Color3.new(0, 1, 0)
					OffoOn.BorderColor3 = Color3.new(0, 1, 0)
					Fly() 
				end 
			elseif key:lower() == "w" then 
				ctrl.f = 45
			elseif key:lower() == "s" then 
				ctrl.b = -45 
			elseif key:lower() == "a" then 
				ctrl.l = -45 
			elseif key:lower() == "d" then 
				ctrl.r = 45
			end 
		end) 
		mouse.KeyUp:connect(function(key) 
			if key:lower() == "w" then 
				ctrl.f = 0
			elseif key:lower() == "s" then 
				ctrl.b = 0
			elseif key:lower() == "a" then 
				ctrl.l = 0
			elseif key:lower() == "d" then 
				ctrl.r = 0
			end 
		end)
		Fly()
	end)

	OffoOn.Name = "Off/oOn"
	OffoOn.Parent = Flyx
	OffoOn.BackgroundColor3 = Color3.new(1, 0, 0)
	OffoOn.BorderColor3 = Color3.new(1, 0, 0)
	OffoOn.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn.Size = UDim2.new(0, 89, 0, 10)

	GunGrabber.Name = "Gun Grabber"
	GunGrabber.Parent = Page1Scrollinframe
	GunGrabber.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	GunGrabber.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	GunGrabber.Position = UDim2.new(0.74784112, 0, 0.0437077843, 0)
	GunGrabber.Size = UDim2.new(0, 89, 0, 24)
	GunGrabber.Font = Enum.Font.SourceSans
	GunGrabber.Text = "Gun Grabber"
	GunGrabber.TextColor3 = Color3.new(1, 1, 1)
	GunGrabber.TextScaled = true
	GunGrabber.TextSize = 20
	GunGrabber.TextWrapped = true
	GunGrabber.MouseButton1Click:connect(function()
		local currentX = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.X
		local currentY = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Y
		local currentZ = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Z	

		if workspace:FindFirstChild("GunDrop") ~= nil then

			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = workspace:FindFirstChild("GunDrop").CFrame	
			wait(.25)	
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentX, currentY, currentZ)

		else

			GunGrabber.Text = "No Gun Is Dropped"
			wait(1)

			GunGrabber.Text = "Gun Grabber"

		end
	end)

	OffoOn_2.Name = "Off/oOn"
	OffoOn_2.Parent = GunGrabber
	OffoOn_2.BackgroundColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_2.BorderColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_2.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_2.Size = UDim2.new(0, 89, 0, 10)

	CoinFarm.Name = "Coin Farm"
	CoinFarm.Parent = Page1Scrollinframe
	CoinFarm.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	CoinFarm.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	CoinFarm.Position = UDim2.new(0.569948196, 0, 0.0437077843, 0)
	CoinFarm.Size = UDim2.new(0, 89, 0, 24)
	CoinFarm.Font = Enum.Font.SourceSans
	CoinFarm.Text = "Coin Farm"
	CoinFarm.TextColor3 = Color3.new(1, 1, 1)
	CoinFarm.TextScaled = true
	CoinFarm.TextSize = 20
	CoinFarm.TextWrapped = true
	CoinFarm.MouseButton1Click:connect(function()
		if OffoOn_3.BackgroundColor3 == Color3.new(1, 0, 0) then
			OffoOn_3.BackgroundColor3 = Color3.new(0, 1, 0)
			OffoOn_3.BorderColor3 = Color3.new(0, 1, 0)
			local plr = game.Players.LocalPlayer
			toggle = true
			local AncientPOS = plr.Character.HumanoidRootPart.Position


			while toggle == true and wait(2) do wait(.25)
				local place = workspace:GetChildren()	

				for i,v in pairs(place) do	    
					local vChildren = v:GetChildren()
					for i,child in pairs(vChildren) do
						if child.Name == "CoinContainer" then

							if child.Coin_Server:FindFirstChild("Coin") ~= nil then
								game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = child.Coin_Server.Coin.CFrame
							else
								plr.Character.HumanoidRootPart.CFrame = CFrame.new(AncientPOS)
								plr.Character.HumanoidRootPart.CFrame = CFrame.new(AncientPOS)	
								CoinFarm.Text = "No Coins"

								OffoOn_3.BackgroundColor3 = Color3.new(0, 1, 0)
								OffoOn_3.BorderColor3 = Color3.new(0, 1, 0)
								toggle = false
							end

						end
					end	
				end
			end
		else
			toggle = false
			OffoOn_3.BackgroundColor3 = Color3.new(1, 0, 0)
			OffoOn_3.BorderColor3 = Color3.new(1, 0, 0)
		end
	end)

	OffoOn_3.Name = "Off/oOn"
	OffoOn_3.Parent = CoinFarm
	OffoOn_3.BackgroundColor3 = Color3.new(1, 0, 0)
	OffoOn_3.BorderColor3 = Color3.new(1, 0, 0)
	OffoOn_3.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_3.Size = UDim2.new(0, 89, 0, 10)

	Noclip.Name = "Noclip"
	Noclip.Parent = Page1Scrollinframe
	Noclip.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Noclip.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Noclip.Position = UDim2.new(0.208981037, 0, 0.141855925, 0)
	Noclip.Size = UDim2.new(0, 89, 0, 24)
	Noclip.Font = Enum.Font.SourceSans
	Noclip.Text = "NoClip"
	Noclip.TextColor3 = Color3.new(1, 1, 1)
	Noclip.TextScaled = true
	Noclip.TextSize = 20
	Noclip.TextWrapped = true
	Noclip.MouseButton1Click:connect(function()
		game:GetService('RunService').Stepped:connect(function()
			if noclip then
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			end
		end)		
		if OffoOn_4.BackgroundColor3 == Color3.new(1, 0, 0) 	then
			OffoOn_4.BackgroundColor3 = Color3.new(0, 1, 0)
			OffoOn_4.BorderColor3 = Color3.new(0, 1, 0)
			noclip = not noclip
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		else
			OffoOn_4.BackgroundColor3 = Color3.new(1, 0, 0)
			OffoOn_4.BorderColor3 = Color3.new(1, 0, 0)
			noclip = false
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)

		end
	end)

	OffoOn_4.Name = "Off/oOn"
	OffoOn_4.Parent = Noclip
	OffoOn_4.BackgroundColor3 = Color3.new(1, 0, 0)
	OffoOn_4.BorderColor3 = Color3.new(1, 0, 0)
	OffoOn_4.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_4.Size = UDim2.new(0, 89, 0, 10)

	MurderEsp.Name = "MurderEsp"
	MurderEsp.Parent = Page1Scrollinframe
	MurderEsp.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	MurderEsp.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	MurderEsp.Position = UDim2.new(0.0310880803, 0, 0.0437077954, 0)
	MurderEsp.Size = UDim2.new(0, 89, 0, 24)
	MurderEsp.Font = Enum.Font.SourceSans
	MurderEsp.Text = "Murder Esp"
	MurderEsp.TextColor3 = Color3.new(1, 1, 1)
	MurderEsp.TextScaled = true
	MurderEsp.TextSize = 20
	MurderEsp.TextWrapped = true
	MurderEsp.MouseButton1Click:connect(function()


		if OffoOn_5.BackgroundColor3 == Color3.new(1, 0, 0) then
			OffoOn_5.BackgroundColor3 = Color3.new(0, 1, 0)
			OffoOn_5.BorderColor3 = Color3.new(0, 1, 0)
			toggle = true
			while toggle do wait(.1)		
				local Players = game:GetService("Players")

				for i, Plr in pairs(Players:GetPlayers()) do
					for i, Bp in pairs(Plr:GetChildren()) do
						if Bp.Name == "Backpack" then
							if Bp:FindFirstChild("Knife") ~= nil then
								if Bp.Parent.Character.UpperTorso:FindFirstChild("BoxHandleAdornment") == nil then
									local box = Instance.new("BoxHandleAdornment", Bp.Parent.Character.UpperTorso)
									box.Size = Bp.Parent.Character.UpperTorso.Size
									box.Adornee = Bp.Parent.Character.UpperTorso
									box.ZIndex = 5
									box.AlwaysOnTop = true
									box.Color3 = Color3.fromRGB(255, 0, 25)

									local at0 = Instance.new("Attachment", game.Players.LocalPlayer.Character.UpperTorso)
									local at1 = Instance.new("Attachment", Bp.Parent.Character.UpperTorso)
									local beam = Instance.new("Beam", game.Players.LocalPlayer.Character)
									beam.Color = ColorSequence.new(Color3.fromRGB(255, 0, 25), Color3.fromRGB(255, 0, 25))
									beam.FaceCamera = true
									beam.Width0 = 0.2
									beam.Width1 = 0.2
									beam.Attachment0 = at0
									beam.Attachment1 = at1
								end
							end
						end
					end
				end
			end


			while toggle == false do wait()		
				local Players = game:GetService("Players")

				for i, Plr in pairs(Players:GetPlayers()) do
					for i, Bp in pairs(Plr:GetChildren()) do
						if Bp.Name == "Backpack" then
							if Bp:FindFirstChild("Knife") ~= nil then
								if Bp.Parent.Character.UpperTorso:FindFirstChild("BoxHandleAdornment") ~= nil then
									Bp.Parent.Character.UpperTorso:FindFirstChild("BoxHandleAdornment"):Destroy()

								elseif game.Players.LocalPlayer.Character:FindFirstChild("Beam") ~= nil then
									game.Players.LocalPlayer.Character:FindFirstChild("Beam"):Destroy()
								end
							end
						end
					end
				end	
			end
		else
			OffoOn_5.BackgroundColor3 = Color3.new(1, 0, 0)
			OffoOn_5.BorderColor3 = Color3.new(1, 0, 0)
			toggle = false
		end
	end)

	OffoOn_5.Name = "Off/oOn"
	OffoOn_5.Parent = MurderEsp
	OffoOn_5.BackgroundColor3 = Color3.new(1, 0, 0)
	OffoOn_5.BorderColor3 = Color3.new(1, 0, 0)
	OffoOn_5.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_5.Size = UDim2.new(0, 89, 0, 10)

	Tptolobby.Name = "Tp to lobby"
	Tptolobby.Parent = Page1Scrollinframe
	Tptolobby.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Tptolobby.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Tptolobby.Position = UDim2.new(0.390328169, 0, 0.141855925, 0)
	Tptolobby.Size = UDim2.new(0, 89, 0, 24)
	Tptolobby.Font = Enum.Font.SourceSans
	Tptolobby.Text = "Tp To Lobby"
	Tptolobby.TextColor3 = Color3.new(1, 1, 1)
	Tptolobby.TextScaled = true
	Tptolobby.TextSize = 20
	Tptolobby.TextWrapped = true
	Tptolobby.MouseButton1Click:connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-108.5, 145, 0.6)

	end)

	OffoOn_6.Name = "Off/oOn"
	OffoOn_6.Parent = Tptolobby
	OffoOn_6.BackgroundColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_6.BorderColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_6.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_6.Size = UDim2.new(0, 89, 0, 10)

	SherrifEsp.Name = "Sherrif Esp"
	SherrifEsp.Parent = Page1Scrollinframe
	SherrifEsp.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	SherrifEsp.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	SherrifEsp.Position = UDim2.new(0.208981007, 0, 0.0437077954, 0)
	SherrifEsp.Size = UDim2.new(0, 89, 0, 24)
	SherrifEsp.Font = Enum.Font.SourceSans
	SherrifEsp.Text = "Sherrif Esp"
	SherrifEsp.TextColor3 = Color3.new(1, 1, 1)
	SherrifEsp.TextScaled = true
	SherrifEsp.TextSize = 20
	SherrifEsp.TextWrapped = true
	SherrifEsp.MouseButton1Click:connect(function()
		if OffoOn_7.BackgroundColor3 == Color3.new(1, 0, 0) then
			proez = true
			OffoOn_7.BackgroundColor3 = Color3.new(0, 1, 0)
			OffoOn_7.BorderColor3 = Color3.new(0, 1, 0)

			while proez == true do wait(.1)		
				local Players = game:GetService("Players")

				for i, Plr in pairs(Players:GetPlayers()) do
					for i, Bp in pairs(Plr:GetChildren()) do
						if Bp.Name == "Backpack" then
							if Bp:FindFirstChild("Gun") ~= nil then
								if Bp.Parent.Character.UpperTorso:FindFirstChild("BoxHandleAdornment") == nil then
									local box = Instance.new("BoxHandleAdornment", Bp.Parent.Character.UpperTorso)
									box.Size = Bp.Parent.Character.UpperTorso.Size
									box.Adornee = Bp.Parent.Character.UpperTorso
									box.ZIndex = 5
									box.AlwaysOnTop = true
									box.Color3 = Color3.fromRGB(0, 50, 255)

									local at0 = Instance.new("Attachment", game.Players.LocalPlayer.Character.UpperTorso)
									local at1 = Instance.new("Attachment", Bp.Parent.Character.UpperTorso)
									local beam = Instance.new("Beam", game.Players.LocalPlayer.Character)
									beam.Color = ColorSequence.new(Color3.fromRGB(0, 50, 255), Color3.fromRGB(0, 50, 255))
									beam.FaceCamera = true
									beam.Width0 = 0.2
									beam.Width1 = 0.2
									beam.Attachment0 = at0
									beam.Attachment1 = at1
								end
							end
						end
					end
				end
			end


			while proez == false do wait()		
				local Players = game:GetService("Players")

				for i, Plr in pairs(Players:GetPlayers()) do
					for i, Bp in pairs(Plr:GetChildren()) do
						if Bp.Name == "Backpack" then
							if Bp:FindFirstChild("Gun") ~= nil then
								if Bp.Parent.Character.UpperTorso:FindFirstChild("BoxHandleAdornment") ~= nil then
									Bp.Parent.Character.UpperTorso:FindFirstChild("BoxHandleAdornment"):Destroy()

								elseif game.Players.LocalPlayer.Character:FindFirstChild("Beam") ~= nil then
									game.Players.LocalPlayer.Character:FindFirstChild("Beam"):Destroy()
								end
							end
						end
					end
				end	
			end
		else
			OffoOn_7.BackgroundColor3 = Color3.new(1, 0, 0)
			OffoOn_7.BorderColor3 = Color3.new(1, 0, 0)
			proez = false
		end
	end)

	OffoOn_7.Name = "Off/oOn"
	OffoOn_7.Parent = SherrifEsp
	OffoOn_7.BackgroundColor3 = Color3.new(1, 0, 0)
	OffoOn_7.BorderColor3 = Color3.new(1, 0, 0)
	OffoOn_7.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_7.Size = UDim2.new(0, 89, 0, 10)

	KillAll.Name = "Kill All"
	KillAll.Parent = Page1Scrollinframe
	KillAll.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	KillAll.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	KillAll.Position = UDim2.new(0.392055273, 0, 0.0437077954, 0)
	KillAll.Size = UDim2.new(0, 89, 0, 24)
	KillAll.Font = Enum.Font.SourceSans
	KillAll.Text = "Kill All"
	KillAll.TextColor3 = Color3.new(1, 1, 1)
	KillAll.TextScaled = true
	KillAll.TextSize = 20
	KillAll.TextWrapped = true
	KillAll.MouseButton1Click:connect(function()
		if OffoOn_8.BackgroundColor3 == Color3.new(1, 0, 0) then
			OffoOn_8.BackgroundColor3 = Color3.new(0, 1, 0)
			OffoOn_8.BorderColor3 = Color3.new(0, 1, 0)
			killallllllll = true
			if game.Players.LocalPlayer.Backpack:FindFirstChild("Knife") ~= nil then -- Only works if you're the murderer

				local Players = game:GetService("Players")	
				for i, Victim in pairs(Players:GetPlayers()) do
					if Victim.Name ~= game.Players.LocalPlayer.Name then

						repeat wait()
							game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Victim.Character.HumanoidRootPart.CFrame * CFrame.new(0, 0, 1)
						until	Victim.Character.Humanoid.Health == 0 or killallllllll == false

					end
				end

			else
				KillAll.Text = "You Are Not Murder"

				killallllllll = false
				OffoOn_8.BackgroundColor3 = Color3.new(1, 0, 0)
				OffoOn_8.BorderColor3 = Color3.new(1, 0, 0)
				wait(1

				)
				KillAll.Text = "Kill All"

			end
		else
			killallllllll = false
			OffoOn_8.BackgroundColor3 = Color3.new(1, 0, 0)
			OffoOn_8.BorderColor3 = Color3.new(1, 0, 0)
		end

	end)

	OffoOn_8.Name = "Off/oOn"
	OffoOn_8.Parent = KillAll
	OffoOn_8.BackgroundColor3 = Color3.new(1, 0, 0)
	OffoOn_8.BorderColor3 = Color3.new(1, 0, 0)
	OffoOn_8.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_8.Size = UDim2.new(0, 89, 0, 10)

	TpTOMAP.Name = "Tp TO MAP"
	TpTOMAP.Parent = Page1Scrollinframe
	TpTOMAP.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	TpTOMAP.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	TpTOMAP.Position = UDim2.new(0.569948196, 0, 0.141855925, 0)
	TpTOMAP.Size = UDim2.new(0, 89, 0, 24)
	TpTOMAP.Font = Enum.Font.SourceSans
	TpTOMAP.Text = "Tp To Map"
	TpTOMAP.TextColor3 = Color3.new(1, 1, 1)
	TpTOMAP.TextScaled = true
	TpTOMAP.TextSize = 20
	TpTOMAP.TextWrapped = true
	TpTOMAP.MouseButton1Click:connect(function()
		local Workplace = workspace:GetChildren()

		for i, Thing in pairs(Workplace) do

			local ThingChildren = Thing:GetChildren()
			for i, Child in pairs(ThingChildren) do
				if Child.Name == "Spawns" then

					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Child.Spawn.CFrame

				end
			end
		end
	end)

	OffoOn_9.Name = "Off/oOn"
	OffoOn_9.Parent = TpTOMAP
	OffoOn_9.BackgroundColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_9.BorderColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_9.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_9.Size = UDim2.new(0, 89, 0, 10)

	TpTosherrif.Name = "Tp To sherrif"
	TpTosherrif.Parent = Page1Scrollinframe
	TpTosherrif.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	TpTosherrif.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	TpTosherrif.Position = UDim2.new(0.74784112, 0, 0.141855925, 0)
	TpTosherrif.Size = UDim2.new(0, 89, 0, 24)
	TpTosherrif.Font = Enum.Font.SourceSans
	TpTosherrif.Text = "Tp To Sherrif"
	TpTosherrif.TextColor3 = Color3.new(1, 1, 1)
	TpTosherrif.TextScaled = true
	TpTosherrif.TextSize = 20
	TpTosherrif.TextWrapped = true
	TpTosherrif.MouseButton1Click:connect(function()
		local Players = game:GetService("Players")			
		for i, player in pairs(Players:GetPlayers()) do

			local bp = player.Backpack:GetChildren()
			for i, tool in pairs(bp) do
				if tool.Name == "Gun" then

					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[tool.Parent.Parent.Name].Character.HumanoidRootPart.CFrame

				end
			end

		end
	end)

	OffoOn_10.Name = "Off/oOn"
	OffoOn_10.Parent = TpTosherrif
	OffoOn_10.BackgroundColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_10.BorderColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_10.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_10.Size = UDim2.new(0, 89, 0, 10)

	Tptomurder.Name = "Tp to murder"
	Tptomurder.Parent = Page1Scrollinframe
	Tptomurder.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Tptomurder.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Tptomurder.Position = UDim2.new(0.0293609984, 0, 0.241855919, 0)
	Tptomurder.Size = UDim2.new(0, 89, 0, 24)
	Tptomurder.Font = Enum.Font.SourceSans
	Tptomurder.Text = "Tp To Murder"
	Tptomurder.TextColor3 = Color3.new(1, 1, 1)
	Tptomurder.TextScaled = true
	Tptomurder.TextSize = 20
	Tptomurder.TextWrapped = true
	Tptomurder.MouseButton1Click:connect(function()
		local Players = game:GetService("Players")			
		for i, player in pairs(Players:GetPlayers()) do

			local bp = player.Backpack:GetChildren()
			for i, tool in pairs(bp) do
				if tool.Name == "Knife" then

					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[tool.Parent.Parent.Name].Character.HumanoidRootPart.CFrame

				end
			end

		end
	end)

	OffoOn_11.Name = "Off/oOn"
	OffoOn_11.Parent = Tptomurder
	OffoOn_11.BackgroundColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_11.BorderColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_11.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_11.Size = UDim2.new(0, 89, 0, 10)

	Walkspeed.Name = "Walkspeed"
	Walkspeed.Parent = Page1Scrollinframe
	Walkspeed.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Walkspeed.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Walkspeed.Position = UDim2.new(0.208981022, 0, 0.240004063, 0)
	Walkspeed.Size = UDim2.new(0, 89, 0, 24)
	Walkspeed.Font = Enum.Font.SourceSans
	Walkspeed.Text = "WalkSpeed"
	Walkspeed.TextColor3 = Color3.new(1, 0, 0)
	Walkspeed.TextScaled = true
	Walkspeed.TextSize = 20
	Walkspeed.TextWrapped = true
	Walkspeed.MouseButton1Click:connect(function()
		if Walkspeed.TextColor3 == Color3.new(1, 0, 0) then
			Walkspeed.TextColor3 = Color3.new(0, 1, 0)
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = TextBoxforwalkspeed.Text
			if 	TextBoxforwalkspeed.Text == "" then
				Walkspeed.Text = "Put Value"
				Walkspeed.TextColor3 = Color3.new(1, 0, 0)

				wait(1)
				Walkspeed.Text = "WalkSpeed"


			end

		else
			Walkspeed.TextColor3 = Color3.new(1, 0, 0)

			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
			TextBoxforwalkspeed.Text = ""
		end

	end)

	TextBoxforwalkspeed.Name = "TextBox for walkspeed"
	TextBoxforwalkspeed.Parent = Walkspeed
	TextBoxforwalkspeed.BackgroundColor3 = Color3.new(0.235294, 0.235294, 0.235294)
	TextBoxforwalkspeed.BorderColor3 = Color3.new(0.235294, 0.235294, 0.235294)
	TextBoxforwalkspeed.Position = UDim2.new(0, 0, 1.04166663, 0)
	TextBoxforwalkspeed.Size = UDim2.new(0, 89, 0, 17)
	TextBoxforwalkspeed.Font = Enum.Font.SourceSans
	TextBoxforwalkspeed.PlaceholderText = "Put Value"
	TextBoxforwalkspeed.Text = ""
	TextBoxforwalkspeed.TextColor3 = Color3.new(0, 0, 0)
	TextBoxforwalkspeed.TextSize = 14

	Jumppower.Name = "Jumppower"
	Jumppower.Parent = Page1Scrollinframe
	Jumppower.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Jumppower.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Jumppower.Position = UDim2.new(0.390328169, 0, 0.240004063, 0)
	Jumppower.Size = UDim2.new(0, 89, 0, 24)
	Jumppower.Font = Enum.Font.SourceSans
	Jumppower.Text = "JumpPower"
	Jumppower.TextColor3 = Color3.new(1, 0, 0)
	Jumppower.TextScaled = true
	Jumppower.TextSize = 20
	Jumppower.TextWrapped = true
	Jumppower.MouseButton1Click:connect(function()
		if Jumppower.TextColor3 == Color3.new(1, 0, 0) then
			Jumppower.TextColor3 = Color3.new(0, 1, 0)
			game.Players.LocalPlayer.Character.Humanoid.JumpPower = TextBoxforjumpower.Text
			if 	TextBoxforjumpower.Text == "" then
				Jumppower.Text = "Put Value"
				Jumppower.TextColor3 = Color3.new(1, 0, 0)

				wait(1)
				Jumppower.Text = "JumpPower"


			end

		else
			Jumppower.TextColor3 = Color3.new(1, 0, 0)

			game.Players.LocalPlayer.Character.Humanoid.JumpPower = 48
			TextBoxforjumpower.Text = ""
		end

	end)

	TextBoxforjumpower.Name = "TextBox for jumpower"
	TextBoxforjumpower.Parent = Jumppower
	TextBoxforjumpower.BackgroundColor3 = Color3.new(0.235294, 0.235294, 0.235294)
	TextBoxforjumpower.BorderColor3 = Color3.new(0.235294, 0.235294, 0.235294)
	TextBoxforjumpower.Position = UDim2.new(0, 0, 1.04166663, 0)
	TextBoxforjumpower.Size = UDim2.new(0, 89, 0, 17)
	TextBoxforjumpower.Font = Enum.Font.SourceSans
	TextBoxforjumpower.PlaceholderText = "Put Value"
	TextBoxforjumpower.Text = ""
	TextBoxforjumpower.TextColor3 = Color3.new(0, 0, 0)
	TextBoxforjumpower.TextSize = 14

	TpTo.Name = "Tp To"
	TpTo.Parent = Page1Scrollinframe
	TpTo.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	TpTo.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	TpTo.Position = UDim2.new(0.569948196, 0, 0.240004063, 0)
	TpTo.Size = UDim2.new(0, 89, 0, 24)
	TpTo.Font = Enum.Font.SourceSans
	TpTo.Text = "Tp To"
	TpTo.TextColor3 = Color3.new(1, 0, 0)
	TpTo.TextScaled = true
	TpTo.TextSize = 20
	TpTo.TextWrapped = true
	TpTo.MouseButton1Click:connect(function()
		local spech = findPlayer(Targetplayer.Text);
		spech = spech.Name
		local plr = game.Players.LocalPlayer

		if TpTo.TextColor3 == Color3.new(1, 0, 0) then
			TpTo.TextColor3 = Color3.new(0, 1, 0)
			flying = false
			AncientPOS = plr.Character.HumanoidRootPart.Position
			wait(.30)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[spech].Character.HumanoidRootPart.CFrame
		else
			TpTo.TextColor3 = Color3.new(1, 0, 0)
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(AncientPOS)
			plr.Character.HumanoidRootPart.CFrame = CFrame.new(AncientPOS)	
		end
	end)

	Targetplayer.Name = "Targetplayer"
	Targetplayer.Parent = TpTo
	Targetplayer.BackgroundColor3 = Color3.new(0.235294, 0.235294, 0.235294)
	Targetplayer.BorderColor3 = Color3.new(0.235294, 0.235294, 0.235294)
	Targetplayer.Position = UDim2.new(0, 0, 1.04166663, 0)
	Targetplayer.Size = UDim2.new(0, 89, 0, 17)
	Targetplayer.Font = Enum.Font.SourceSans
	Targetplayer.PlaceholderText = "PlayerName"
	Targetplayer.Text = ""
	Targetplayer.TextColor3 = Color3.new(0, 0, 0)
	Targetplayer.TextSize = 14
	local function ShrinkName()
		Targetplayer.FocusLost:connect(function()
			for i,v in pairs(game.Players:GetChildren()) do
				if (string.sub(string.lower(v.Name),1,string.len(Targetplayer.Text))) == string.lower(Targetplayer.Text) then
					Targetplayer.Text = v.Name
				end

			end
		end)
	end
	ShrinkName()

	Spectate.Name = "Spectate"
	Spectate.Parent = Page1Scrollinframe
	Spectate.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Spectate.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Spectate.Position = UDim2.new(0.74784112, 0, 0.240004063, 0)
	Spectate.Size = UDim2.new(0, 89, 0, 24)
	Spectate.Font = Enum.Font.SourceSans
	Spectate.Text = "Spectate"
	Spectate.TextColor3 = Color3.new(1, 0, 0)
	Spectate.TextScaled = true
	Spectate.TextSize = 20
	Spectate.TextWrapped = true
	Spectate.MouseButton1Click:connect(function()
		local spech = findPlayer(SpectatePlr.Text);
		spech = spech.Name
		if Spectate.TextColor3 == Color3.new(1, 0, 0) then
			Spectate.TextColor3 = Color3.new(0, 1, 0)
			game.Workspace.Camera.CameraSubject = game.Players[spech].Character.Humanoid;

		else
			Spectate.TextColor3 = Color3.new(1, 0, 0)
			game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid;

		end
	end)

	SpectatePlr.Name = "Spectate Plr"
	SpectatePlr.Parent = Spectate
	SpectatePlr.BackgroundColor3 = Color3.new(0.235294, 0.235294, 0.235294)
	SpectatePlr.BorderColor3 = Color3.new(0.235294, 0.235294, 0.235294)
	SpectatePlr.Position = UDim2.new(0, 0, 1.04166663, 0)
	SpectatePlr.Size = UDim2.new(0, 89, 0, 17)
	SpectatePlr.Font = Enum.Font.SourceSans
	SpectatePlr.PlaceholderText = "PlayerName"
	SpectatePlr.Text = ""
	SpectatePlr.TextColor3 = Color3.new(0, 0, 0)
	SpectatePlr.TextSize = 14
	local function ShrinkName()
		SpectatePlr.FocusLost:connect(function()
			for i,v in pairs(game.Players:GetChildren()) do
				if (string.sub(string.lower(v.Name),1,string.len(SpectatePlr.Text))) == string.lower(SpectatePlr.Text) then
					SpectatePlr.Text = v.Name
				end

			end
		end)
	end
	ShrinkName()

	Mousetp.Name = "Mouse tp"
	Mousetp.Parent = Page1Scrollinframe
	Mousetp.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Mousetp.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Mousetp.Position = UDim2.new(0.0276338905, 0, 0.345559627, 0)
	Mousetp.Size = UDim2.new(0, 89, 0, 24)
	Mousetp.Font = Enum.Font.SourceSans
	Mousetp.Text = "Tp [E]"
	Mousetp.TextColor3 = Color3.new(1, 1, 1)
	Mousetp.TextScaled = true
	Mousetp.TextSize = 20
	Mousetp.TextWrapped = true
	Mousetp.MouseButton1Click:connect(function()
		if 	OffoOn_12.BackgroundColor3 == Color3.new(1, 0, 0) then
			OffoOn_12.BackgroundColor3 = Color3.new(0, 1, 0)
			OffoOn_12.BorderColor3 = Color3.new(0, 1, 0)

			mousepro  = true
			plr = game.Players.LocalPlayer

			hum = plr.Character.HumanoidRootPart

			mouse = plr:GetMouse()



			mouse.KeyDown:connect(function(key)

				if key == "e" and mousepro == true then

					if mouse.Target then

						hum.CFrame = CFrame.new(mouse.Hit.x, mouse.Hit.y + 5, mouse.Hit.z)

					end

				end
			end)	

		else
			OffoOn_12.BackgroundColor3 = Color3.new(1, 0, 0)
			OffoOn_12.BorderColor3 = Color3.new(1, 0, 0)
			mousepro  = false

		end

	end)

	OffoOn_12.Name = "Off/oOn"
	OffoOn_12.Parent = Mousetp
	OffoOn_12.BackgroundColor3 = Color3.new(1, 0, 0)
	OffoOn_12.BorderColor3 = Color3.new(1, 0, 0)
	OffoOn_12.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_12.Size = UDim2.new(0, 89, 0, 10)

	Stick_3.Name = "Stick"
	Stick_3.Parent = Page1Scrollinframe
	Stick_3.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Stick_3.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Stick_3.Position = UDim2.new(0.208981037, 0, 0.345559627, 0)
	Stick_3.Size = UDim2.new(0, 89, 0, 24)
	Stick_3.Font = Enum.Font.SourceSans
	Stick_3.Text = "Stick"
	Stick_3.TextColor3 = Color3.new(1, 1, 1)
	Stick_3.TextScaled = true
	Stick_3.TextSize = 20
	Stick_3.TextWrapped = true
	Stick_3.MouseButton1Click:connect(function()
		if OffoOn_13.BackgroundColor3 == Color3.new(1, 0, 0) then
			OffoOn_13.BackgroundColor3 = Color3.new(0, 1, 0)
			OffoOn_13.BorderColor3 = Color3.new(0, 1, 0)
			local spinSpeed = 0
			local speaker = game.Players.LocalPlayer
			for i,v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
				if v.Name == "Spinning" then
					v:Destroy()
				end
			end
			local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
			Spin.Name = "Spinning"
			Spin.MaxTorque = Vector3.new(0, math.huge, 0)
			Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)

		else
			OffoOn_13.BackgroundColor3 = Color3.new(1, 0, 0)
			OffoOn_13.BorderColor3 = Color3.new(1, 0, 0)
			local spinSpeed = 0
			local speaker = game.Players.LocalPlayer
			for i,v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
				if v.Name == "Spinning" then
					v:Destroy()
				end
			end
			local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
			Spin.Name = "Spinning"
			Spin.MaxTorque = Vector3.new(0, math.huge, 0)
			Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)
			Spin:Destroy()
		end

	end)

	OffoOn_13.Name = "Off/oOn"
	OffoOn_13.Parent = Stick_3
	OffoOn_13.BackgroundColor3 = Color3.new(1, 0, 0)
	OffoOn_13.BorderColor3 = Color3.new(1, 0, 0)
	OffoOn_13.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_13.Size = UDim2.new(0, 89, 0, 10)

	Godmode.Name = "Godmode"
	Godmode.Parent = Page1Scrollinframe
	Godmode.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Godmode.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Godmode.Position = UDim2.new(0.392055273, 0, 0.345559627, 0)
	Godmode.Size = UDim2.new(0, 89, 0, 24)
	Godmode.Font = Enum.Font.SourceSans
	Godmode.Text = "Godmode"
	Godmode.TextColor3 = Color3.new(1, 1, 1)
	Godmode.TextScaled = true
	Godmode.TextSize = 20
	Godmode.TextWrapped = true
	Godmode.MouseButton1Click:connect(function()
		local player = game.Players.LocalPlayer
		if player.Character then
			if player.Character:FindFirstChild("Humanoid") then
				player.Character.Humanoid.Name = "1"
			end
			local l = player.Character["1"]:Clone()
			l.Parent = player.Character
			l.Name = "Humanoid"; wait(0.1)
			player.Character["1"]:Destroy()
			workspace.CurrentCamera.CameraSubject = player.Character.Humanoid
			player.Character.Animate.Disabled = true; wait(0.1)
			player.Character.Animate.Disabled = false
		end
	end)

	OffoOn_14.Name = "Off/oOn"
	OffoOn_14.Parent = Godmode
	OffoOn_14.BackgroundColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_14.BorderColor3 = Color3.new(0, 0.666667, 1)
	OffoOn_14.Position = UDim2.new(0, 0, 0.999999344, 0)
	OffoOn_14.Size = UDim2.new(0, 89, 0, 10)


	Home.Name = "Home"
	Home.Parent = Mian
	Home.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
	Home.BorderColor3 = Color3.new(0.2, 0.2, 0.2)
	Home.Position = UDim2.new(0.0293609649, 0, 0.132596686, 0)
	Home.Size = UDim2.new(0, 89, 0, 24)
	Home.Font = Enum.Font.SourceSans
	Home.Text = "Home"
	Home.TextColor3 = Color3.new(0, 1, 0)
	Home.TextSize = 20
	Home.MouseButton1Click:connect(function()
		Home.TextColor3 = Color3.new(0, 1, 0)
		Page1.TextColor3 = Color3.new(1, 1, 1)

		Page1Frame.Visible = false
		HOMEFrame.Visible = true
	end)

	HOMEFrame.Name = "HOMEFrame"
	HOMEFrame.Parent = Home
	HOMEFrame.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
	HOMEFrame.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
	HOMEFrame.Position = UDim2.new(-0.191011235, 0, 1.79581022, 0)
	HOMEFrame.Size = UDim2.new(0, 579, 0, 270)

	Welcome.Name = "Welcome,"
	Welcome.Parent = HOMEFrame
	Welcome.BackgroundColor3 = Color3.new(1, 1, 1)
	Welcome.BackgroundTransparency = 1
	Welcome.Position = UDim2.new(0.405872196, 0, 0.0296296328, 0)
	Welcome.Size = UDim2.new(0, 89, 0, 41)
	Welcome.Font = Enum.Font.SourceSans
	Welcome.Text = "Welcome, "..game.Players.LocalPlayer.Name
	Welcome.TextColor3 = Color3.new(1, 1, 1)
	Welcome.TextSize = 30

	Playerimage.Name = "Playerimage"
	Playerimage.Parent = HOMEFrame
	Playerimage.BackgroundTransparency = 1
	Playerimage.BackgroundColor3 = Color3.new(1, 1, 1)
	Playerimage.Position = UDim2.new(0.34887737, 0, 0.240740746, 0)
	Playerimage.Size = UDim2.new(0, 155, 0, 182)
	Playerimage.Image = "https://assetgame.roblox.com/Thumbs/Avatar.ashx?x=250&y=250&Format=Png&username="..game:GetService("Players").LocalPlayer.Name

	Update.Name = "Update"
	Update.Parent = HOMEFrame
	Update.BackgroundColor3 = Color3.new(1, 1, 1)
	Update.BackgroundTransparency = 1
	Update.Position = UDim2.new(0.0949913561, 0, 0.2696296328, 0)
	Update.Size = UDim2.new(0, 89, 0, 41)
	Update.Font = Enum.Font.SourceSans
	Update.Text = "Updates:"
	Update.TextColor3 = Color3.new(1, 1, 1)
	Update.TextSize = 30

	Noupdates.Name = "No updates"
	Noupdates.Parent = HOMEFrame
	Noupdates.BackgroundColor3 = Color3.new(1, 1, 1)
	Noupdates.BackgroundTransparency = 1
	Noupdates.Position = UDim2.new(0.0949913561, 0, 0.481481481, 0)
	Noupdates.Size = UDim2.new(0, 89, 0, 41)
	Noupdates.Font = Enum.Font.SourceSans
	Noupdates.Text = "Not Yet"
	Noupdates.TextColor3 = Color3.new(1, 1, 1)
	Noupdates.TextSize = 20

else
	local ScreenGui = Instance.new("ScreenGui")
	local Universal = Instance.new("Frame")
	local OK = Instance.new("Frame")
	local FLYx = Instance.new("TextButton")
	local Noclip = Instance.new("TextButton")
	local Stick = Instance.new("TextButton")
	local InfJump = Instance.new("TextButton")
	local Walkspeed = Instance.new("TextButton")
	local JumpPower = Instance.new("TextButton")
	local Goto = Instance.new("TextButton")
	local TextBox = Instance.new("TextBox")
	local Spectate = Instance.new("TextButton")
	local TextBox_2 = Instance.new("TextBox")
	local Kara = Instance.new("TextLabel")
	local Close = Instance.new("TextButton")

	ScreenGui.Parent = game.CoreGui
	ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

	Universal.Name = "Universal "
	Universal.Parent = ScreenGui
	Universal.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
	Universal.BorderColor3 = Color3.new(0.156863, 0.156863, 0.156863)
	Universal.Position = UDim2.new(0.194610775, 0, 0.238615662, 0)
	Universal.Size = UDim2.new(0, 592, 0, 306)
	Universal.Active = true
	Universal.Draggable = true

	OK.Name = "OK"
	OK.Parent = Universal
	OK.BackgroundColor3 = Color3.new(1, 1, 1)
	OK.Position = UDim2.new(0, 0, 0.124183007, 0)
	OK.Size = UDim2.new(0, 592, 0, 6)

	FLYx.Name = "FLY x"
	FLYx.Parent = Universal
	FLYx.BackgroundColor3 = Color3.new(0, 0, 0)
	FLYx.BorderColor3 = Color3.new(0, 0, 0)
	FLYx.Position = UDim2.new(0.015202703, 0, 0.248366013, 0)
	FLYx.Size = UDim2.new(0, 96, 0, 27)
	FLYx.Font = Enum.Font.SourceSans
	FLYx.Text = "Fly X"
	FLYx.TextColor3 = Color3.new(1, 1, 1)
	FLYx.TextSize = 14
	FLYx.MouseButton1Click:connect(function()
		FLYx.TextColor3 = Color3.new(1, 0, 0)

		repeat wait() 
		until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Head") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid") 
		local mouse = game.Players.LocalPlayer:GetMouse() 
		repeat wait() until mouse
		local plr = game.Players.LocalPlayer 
		local torso = plr.Character.Head 
		local flying = false
		local deb = true 
		local ctrl = {f = 0, b = 0, l = 0, r = 0} 
		local lastctrl = {f = 0, b = 0, l = 0, r = 0} 
		local maxspeed = 5000
		local speed = 5000 

		function Fly() 
			local bg = Instance.new("BodyGyro", torso) 
			bg.P = 9e4 
			bg.maxTorque = Vector3.new(9e9, 9e9, 9e9) 
			bg.cframe = torso.CFrame 
			local bv = Instance.new("BodyVelocity", torso) 
			bv.velocity = Vector3.new(0,0.1,0) 
			bv.maxForce = Vector3.new(9e9, 9e9, 9e9) 
			repeat wait() 
				plr.Character.Humanoid.PlatformStand = true 
				if ctrl.l + ctrl.r ~= 100000 or ctrl.f + ctrl.b ~= 10000 then 
					speed = speed+.0+(speed/maxspeed) 
					if speed > maxspeed then 
						speed = maxspeed 
					end 
				elseif not (ctrl.l + ctrl.r ~= 5 or ctrl.f + ctrl.b ~= 5) and speed ~= 5 then 
					speed = speed-5
					if speed > 5 then 
						speed = -2 
					end 
				end 
				if (ctrl.l + ctrl.r) ~= 5 or (ctrl.f + ctrl.b) ~= 5 then 
					bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed 
					lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r} 
				elseif (ctrl.l + ctrl.r) == 5 and (ctrl.f + ctrl.b) == 5 and speed ~= 5 then 
					bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed 
				else 
					bv.velocity = Vector3.new(0,0.1,0) 
				end 
				bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0) 
			until not flying 
			ctrl = {f = 0, b = 0, l = 0, r = 0} 
			lastctrl = {f = 0, b = 0, l = 0, r = 0} 
			speed = 5 
			bg:Destroy() 
			bv:Destroy() 
			plr.Character.Humanoid.PlatformStand = false 
		end 
		mouse.KeyDown:connect(function(key) 
			if key:lower() == "x" then 
				if flying then flying = false 
					FLYx.TextColor3 = Color3.new(1, 0, 0)

				else 
					FLYx.TextColor3 = Color3.new(0, 1, 0)

					flying = true 
					Fly() 
				end 
			elseif key:lower() == "w" then 
				ctrl.f = 45
			elseif key:lower() == "s" then 
				ctrl.b = -45 
			elseif key:lower() == "a" then 
				ctrl.l = -45 
			elseif key:lower() == "d" then 
				ctrl.r = 45
			end 
		end) 
		mouse.KeyUp:connect(function(key) 
			if key:lower() == "w" then 
				ctrl.f = 0
			elseif key:lower() == "s" then 
				ctrl.b = 0
			elseif key:lower() == "a" then 
				ctrl.l = 0
			elseif key:lower() == "d" then 
				ctrl.r = 0
			end 
		end)
		Fly()
	end)

	Noclip.Name = "Noclip"
	Noclip.Parent = Universal
	Noclip.BackgroundColor3 = Color3.new(0, 0, 0)
	Noclip.BorderColor3 = Color3.new(0, 0, 0)
	Noclip.Position = UDim2.new(0.194256753, 0, 0.248366013, 0)
	Noclip.Size = UDim2.new(0, 96, 0, 27)
	Noclip.Font = Enum.Font.SourceSans
	Noclip.Text = "NoClip"
	Noclip.TextColor3 = Color3.new(1, 0, 0)
	Noclip.TextSize = 14
	Noclip.MouseButton1Click:connect(function()
		game:GetService('RunService').Stepped:connect(function()
			if noclip then
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			end
		end)			if Noclip.TextColor3 == Color3.new(1, 0, 0) then
			Noclip.TextColor3 = Color3.new(0, 1, 0)
			noclip = not noclip
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		else
			Noclip.TextColor3 = Color3.new(1, 0, 0)
			noclip = false
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)

		end
	end)

	Stick.Name = "Stick"
	Stick.Parent = Universal
	Stick.BackgroundColor3 = Color3.new(0, 0, 0)
	Stick.BorderColor3 = Color3.new(0, 0, 0)
	Stick.Position = UDim2.new(0.37499997, 0, 0.248366013, 0)
	Stick.Size = UDim2.new(0, 96, 0, 27)
	Stick.Font = Enum.Font.SourceSans
	Stick.Text = "Stick"
	Stick.TextColor3 = Color3.new(1, 0, 0)
	Stick.TextSize = 14
	Stick.MouseButton1Click:connect(function()
		if 	Stick.TextColor3 == Color3.new(1, 0, 0) then
			Stick.TextColor3 = Color3.new(0, 1, 0)

			local spinSpeed = 0
			local speaker = game.Players.LocalPlayer
			for i,v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
				if v.Name == "Spinning" then
					v:Destroy()
				end
			end
			local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
			Spin.Name = "Spinning"
			Spin.MaxTorque = Vector3.new(0, math.huge, 0)
			Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)

		else
			Stick.TextColor3 = Color3.new(1, 0, 0)
			local spinSpeed = 0
			local speaker = game.Players.LocalPlayer
			for i,v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
				if v.Name == "Spinning" then
					v:Destroy()
				end
			end
			local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
			Spin.Name = "Spinning"
			Spin.MaxTorque = Vector3.new(0, math.huge, 0)
			Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)
			Spin:Destroy()	

		end

	end)

	InfJump.Name = "Inf Jump"
	InfJump.Parent = Universal
	InfJump.BackgroundColor3 = Color3.new(0, 0, 0)
	InfJump.BorderColor3 = Color3.new(0, 0, 0)
	InfJump.Position = UDim2.new(0.552364826, 0, 0.248366013, 0)
	InfJump.Size = UDim2.new(0, 96, 0, 27)
	InfJump.Font = Enum.Font.SourceSans
	InfJump.Text = "Inf Jump"
	InfJump.TextColor3 = Color3.new(1, 1, 1)
	InfJump.TextSize = 14
	InfJump.MouseButton1Click:connect(function()
		Player = game:GetService'Players'.LocalPlayer;
		UIS = game:GetService'UserInputService';

		_G.JumpHeight = 50;

		function Action(Object, Function) if Object ~= nil then Function(Object); end end

		UIS.InputBegan:connect(function(UserInput)
			if UserInput.UserInputType == Enum.UserInputType.Keyboard and UserInput.KeyCode == Enum.KeyCode.Space then
				Action(Player.Character.Humanoid, function(self)
					if self:GetState() == Enum.HumanoidStateType.Jumping or self:GetState() == Enum.HumanoidStateType.Freefall then
						Action(self.Parent.HumanoidRootPart, function(self)
							self.Velocity = Vector3.new(0, _G.JumpHeight, 0);
						end)
					end
				end)
			end
		end)
	end)

	Walkspeed.Name = "Walkspeed"
	Walkspeed.Parent = Universal
	Walkspeed.BackgroundColor3 = Color3.new(0, 0, 0)
	Walkspeed.BorderColor3 = Color3.new(0, 0, 0)
	Walkspeed.Position = UDim2.new(0.734797239, 0, 0.248366013, 0)
	Walkspeed.Size = UDim2.new(0, 96, 0, 27)
	Walkspeed.Font = Enum.Font.SourceSans
	Walkspeed.Text = "WalkSpeed"
	Walkspeed.TextColor3 = Color3.new(1, 0, 0)
	Walkspeed.TextSize = 14
	Walkspeed.MouseButton1Click:connect(function()
		if Walkspeed.TextColor3 == Color3.new(1, 0, 0) then
			Walkspeed.TextColor3 = Color3.new(0, 1, 0)
			sped = true
			game.Players.LocalPlayer.Character.Humanoid.Name = "Humz"
			game.Players.LocalPlayer.Character.Humz.WalkSpeed = 100
			demspeed = 200
		else
			Walkspeed.TextColor3 = Color3.new(1, 0, 0)
			sped = false
			game.Players.LocalPlayer.Character.Humz.WalkSpeed = 16
			demspeed = 50
			game.Players.LocalPlayer.Character.Humz.Name = "Humanoid"

		end
	end)

	JumpPower.Name = "JumpPower"
	JumpPower.Parent = Universal
	JumpPower.BackgroundColor3 = Color3.new(0, 0, 0)
	JumpPower.BorderColor3 = Color3.new(0, 0, 0)
	JumpPower.Position = UDim2.new(0.0152026415, 0, 0.375817001, 0)
	JumpPower.Size = UDim2.new(0, 96, 0, 27)
	JumpPower.Font = Enum.Font.SourceSans
	JumpPower.Text = "JumpPower"
	JumpPower.TextColor3 = Color3.new(1, 0, 0)
	JumpPower.TextSize = 14
	JumpPower.MouseButton1Click:connect(function()
		if JumpPower.TextColor3 == Color3.new(1, 0, 0) then
			JumpPower.TextColor3 = Color3.new(0, 1, 0)
			sped = true
			game.Players.LocalPlayer.Character.Humanoid.Name = "Humz"
			game.Players.LocalPlayer.Character.Humz.JumpPower = 200
			demspeed = 200
		else
			JumpPower.TextColor3 = Color3.new(1, 0, 0)

			sped = false
			game.Players.LocalPlayer.Character.Humz.JumpPower = 50
			demspeed = 50
			game.Players.LocalPlayer.Character.Humz.Name = "Humanoid"

		end
	end)
	function findPlayer(name)
		name = name:lower()
		if name == 'me' then
			return game:GetService'Players'.LocalPlayer
		end
		for i,v in pairs(game:GetService'Players':GetPlayers()) do
			if v.Name:lower():find(name) == 1 then
				return v
			end
		end
	end
	Goto.Name = "Goto"
	Goto.Parent = Universal
	Goto.BackgroundColor3 = Color3.new(0, 0, 0)
	Goto.BorderColor3 = Color3.new(0, 0, 0)
	Goto.Position = UDim2.new(0.194256693, 0, 0.375817001, 0)
	Goto.Size = UDim2.new(0, 96, 0, 27)
	Goto.Font = Enum.Font.SourceSans
	Goto.Text = "Goto"
	Goto.TextColor3 = Color3.new(1, 1, 1)
	Goto.TextSize = 14
	Goto.MouseButton1Click:connect(function()
		local TargetPlr = TextBox.Text
		flying = false
		wait(.30)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[TargetPlr].Character.HumanoidRootPart.CFrame
	end)

	TextBox.Parent = Goto
	TextBox.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	TextBox.BorderColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	TextBox.Position = UDim2.new(0, 0, 1, 0)
	TextBox.Size = UDim2.new(0, 96, 0, 13)
	TextBox.Font = Enum.Font.SourceSans
	TextBox.PlaceholderColor3 = Color3.new(1, 1, 1)
	TextBox.PlaceholderText = "Player Name"
	TextBox.Text = "Player Name"
	TextBox.TextColor3 = Color3.new(1, 1, 1)
	TextBox.TextSize = 14

	local function ShrinkName()
		TextBox.FocusLost:connect(function()
			for i,v in pairs(game.Players:GetChildren()) do
				if (string.sub(string.lower(v.Name),1,string.len(TextBox.Text))) == string.lower(TextBox.Text) then
					TextBox.Text = v.Name
				end

			end
		end)
	end
	ShrinkName()
	Spectate.Name = "Spectate"
	Spectate.Parent = Universal
	Spectate.BackgroundColor3 = Color3.new(0, 0, 0)
	Spectate.BorderColor3 = Color3.new(0, 0, 0)
	Spectate.Position = UDim2.new(0.37499994, 0, 0.375817001, 0)
	Spectate.Size = UDim2.new(0, 96, 0, 27)
	Spectate.Font = Enum.Font.SourceSans
	Spectate.Text = "Spectate"
	Spectate.TextColor3 = Color3.new(1, 0, 0)
	Spectate.TextSize = 14
	Spectate.MouseButton1Click:connect(function()
		local spech = findPlayer(TextBox_2.Text);
		spech = spech.Name
		if Spectate.TextColor3 == Color3.new(1, 0, 0) then
			Spectate.TextColor3 = Color3.new(0, 1, 0)
			game.Workspace.Camera.CameraSubject = game.Players[spech].Character.Humanoid;

		else
			Spectate.TextColor3 = Color3.new(1, 0, 0)
			game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid;

		end
	end)

	TextBox_2.Parent = Spectate
	TextBox_2.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	TextBox_2.BorderColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	TextBox_2.Position = UDim2.new(0, 0, 1, 0)
	TextBox_2.Size = UDim2.new(0, 96, 0, 13)
	TextBox_2.Font = Enum.Font.SourceSans
	TextBox_2.PlaceholderColor3 = Color3.new(1, 1, 1)
	TextBox_2.PlaceholderText = "Player Name"
	TextBox_2.Text = ""
	TextBox_2.TextColor3 = Color3.new(1, 1, 1)
	TextBox_2.TextSize = 14

	local function ShrinkName()
		TextBox_2.FocusLost:connect(function()
			for i,v in pairs(game.Players:GetChildren()) do
				if (string.sub(string.lower(v.Name),1,string.len(TextBox_2.Text))) == string.lower(TextBox_2.Text) then
					TextBox_2.Text = v.Name
				end

			end
		end)
	end
	ShrinkName()
	Kara.Name = "Kara"
	Kara.Parent = Universal
	Kara.BackgroundColor3 = Color3.new(1, 1, 1)
	Kara.BackgroundTransparency = 1
	Kara.Position = UDim2.new(0.0422297344, 0, 0.0196078438, 0)
	Kara.Size = UDim2.new(0, 90, 0, 23)
	Kara.Font = Enum.Font.SourceSans
	Kara.Text = "Polakya Universal"
	Kara.TextColor3 = Color3.new(1, 1, 1)
	Kara.TextSize = 25

	Close.Name = "Close"
	Close.Parent = Universal
	Close.BackgroundColor3 = Color3.new(0, 0, 0)
	Close.BorderColor3 = Color3.new(0, 0, 0)
	Close.Position = UDim2.new(0.929054081, 0, 0.0196078438, 0)
	Close.Size = UDim2.new(0, 28, 0, 27)
	Close.Font = Enum.Font.SourceSans
	Close.Text = "X"
	Close.TextColor3 = Color3.new(1, 1, 1)
	Close.TextSize = 14
	Close.MouseButton1Click:connect(function()
		Universal:TweenPosition(UDim2.new(0,0,-17,0),"In","Quart",1)
		wait(1)
		Universal:Destroy()
	end)

end

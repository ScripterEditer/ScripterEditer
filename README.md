-- Fortnite Hub Hub


local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("Fortnite Hub V3☠", "DarkTheme")
local HomeTab = Window:NewTab("Home")
local HubTab = Window:NewTab("Hub")
local GuiTab = Window:NewTab("Gui")
local OthersTab = Window:NewTab("Others")
local CreditTab = Window:NewTab("Credit")
local Section = HomeTab:NewSection("Home")
Section:NewLabel("Update Logs-")
Section:NewLabel("Add More Stuff")
Section:NewLabel("Add Home Tab")
Section:NewLabel("Change Theme (DarkTheme)")
Section:NewLabel("Removed GameHub")
Section:NewLabel("Name : Dark Dex - Fortnite")
Section:NewLabel("Seperated Gui And Hub")
Section:NewLabel("Removed Player And Visual")
Section:NewLabel("Credits Name created")
Section:NewLabel("Version 3.0")
Section:NewLabel("All Bugs Fixed")
local Section = HubTab:NewSection("Hub")
Section:NewButton("Free Pass V2", "Nothing", function()
  loadstring(game:HttpGet("https://gist.githubusercontent.com/dark-modz/6982de484735e730494b2d5a10fd6a2a/raw/a92563b0cd6a63683341a09f54baccea5349ed69/feGamepassV2"))()
end)
Section:NewButton("Acrylix V2.0", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/HubbyScripts/FE-Trolling-Hub/main/source"))()
end)
Section:NewButton("Moon Ui Hub V13", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/IlikeyocutgHAH/MoonUI-v13-102-SCRIPTS/main/MoonUI%20v13!"))()
end)
Section:NewButton("Ice Hub", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))() 
end)
Section:NewButton("X GHOST HUB X", "Nothing", function()
  loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
end)
Section:NewButton("Vhub[Key]", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/V31nc/2642/Created/VHub"))()
end)
Section:NewButton("Scripter Hub V1", "Nothing", function()
  loadstring(game:HttpGet(('https://pastebin.com/raw/cHfXLMNP'),true))()
end)
Section:NewButton("Multi Scripter Hub X [Beta]", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/0n1kidd/Multi-Script-Hub-X/main/Protected.lua_1.txt"))()
end)
Section:NewButton("MegaHub", "Nothing", function()
  loadstring(game:HttpGet(('https://raw.githubusercontent.com/WholeF00ds/Mega/main/Obfuscated%20Loader'),true))()
end)
Section:NewButton("Shakars Hub", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/shakar60/USH.P/main/rotected",true))()
end)
Section:NewButton("Haker_666 [Key]", "Nothing", function()
  loadstring(game:HttpGet('https://paste.website/p/f4c0bdd2-0340-4009-bf57-5d23d362aa94.txt'))()
end)
Section:NewButton("GigaChad Hub", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/OWJBWKQLAISH/GigaChad-Hub/main/Protected_3038811338432694.lua.txt"))()
end)
Section:NewButton("NullWare Hub(Patched Version)", "Nothing", function()
  loadstring(game:HttpGet("https://gist.githubusercontent.com/M6HqVBcddw2qaN4s/37eef2120d509b37b31fa73944ab2361/raw/kT2fVEFnzDfCRXAP"))()
end)
Section:NewLabel("Next Version Update Coming Soon...♻️😊👍")
local Section = GuiTab:NewSection("Gui")
Section:NewButton("Fe UTG V3", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/Blukez/Scripts/main/UTG%20V3%20RAW"))()
end)
Section:NewButton("UTG V3 Command At Info", "Say /open UTG", function()
  local Player = game.Players.LocalPlayer

Player.Chatted:connect(function(cht)
	if cht:match("/open UTG") then
		loadstring(game:HttpGet("https://pastebin.com/raw/NhRrqGgy", true))() -- make sure you add in the script too
	elseif cht:match(";admin") then -- add what you want to say for the script to execute so i put "admin" because i want it to load an admin script
		loadstring(game:HttpGet("https://pastebin.com/raw/iM2Hhq68", true))()
	end
end)
end)
Section:NewButton("Ray x Da hood", "Nothing", function()
  loadstring(game:HttpGet('https://raw.githubusercontent.com/SpaceYes/Lua/Main/DaHood.Lua'))()
end)
Section:NewButton("Swag Da Hood", "Nothing", function()
  loadstring(game:HttpGet('https://raw.githubusercontent.com/lerkermer/lua-projects/master/SwagModeV002'))()
end)
Section:NewButton("Faded Listed", "Nothing", function()
    _G.Toggles = "V"
loadstring(game:HttpGet("https://raw.githubusercontent.com/NighterEpic/Faded/main/YesEpic", true))()
end)
Section:NewButton("Faded Grid", "Nothing", function()
  _G.Toggles = "V"
loadstring(game:HttpGet("https://raw.githubusercontent.com/NighterEpic/Faded-Grid/main/YesEpic", true))()
end)
Section:NewButton("AGENT Da Hood", "Nothing", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/mrhackerman35297/AgentCC/main/Launch.lua"))()
end)
Section:NewButton("Rtx Gui", "Nothing", function()
  loadstring(game:HttpGet(('https://pastefy.ga/xXkUxA0P/raw'),true))()
end)
Section:NewLabel("Next Version Update Coming Soon...😊👍♻️")
local Section = OthersTab:NewSection("Others")
Section:NewButton("Shiftlock", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/MiniNoobie/ShiftLockx/main/Shiftlock-MiniNoobie",true))()
end)
Section:NewButton("Reduse Lag", "Nothing", function()
  _G.Settings = {
    Players = {
        ["Ignore Me"] = true, -- Ignore your Character
        ["Ignore Others"] = true -- Ignore other Characters
    },
    Meshes = {
        Destroy = false, -- Destroy Meshes
        LowDetail = true -- Low detail meshes (NOT SURE IT DOES ANYTHING)
    },
    Images = {
        Invisible = true, -- Invisible Images
        LowDetail = false, -- Low detail images (NOT SURE IT DOES ANYTHING)
        Destroy = false, -- Destroy Images
    },
    Other = {
        ["No Particles"] = true, -- Disables all ParticleEmitter, Trail, Smoke, Fire and Sparkles
        ["No Camera Effects"] = true, -- Disables all PostEffect's (Camera/Lighting Effects)
        ["No Explosions"] = true, -- Makes Explosion's invisible
        ["No Clothes"] = true, -- Removes Clothing from the game
        ["Low Water Graphics"] = true, -- Removes Water Quality
        ["No Shadows"] = true, -- Remove Shadows
        ["Low Rendering"] = true, -- Lower Rendering
        ["Low Quality Parts"] = true -- Lower quality parts
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/FPSBooster.lua"))()
end)
Section:NewButton("Anti Fling", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/GGH52lan/GGH52lan/main/anti-fling.txt"))()
end)
Section:NewButton("Netless V7", "Nothing", function()
      -- when you reset make sure to re-execute this or just make this execute in a loop
for i,v in next, game:GetService("Players").LocalPlayer.Character:GetDescendants() do
    if v:IsA("BasePart") and v.Name ~="HumanoidRootPart" then 
    game:GetService("RunService").Heartbeat:connect(function()
    v.Velocity = Vector3.new(-30,0,0)
    end)
    end
    end
    
    game:GetService("StarterGui"):SetCore("SendNotification", { 
        Title = "Notification";
        Text = "Netless Ran";
        Icon = "rbxthumb://type=Asset&id=5107182114&w=150&h=150"})
    Duration = 16;
end)
Section:NewButton("Rtx Enchancer", "Nothing", function()
  local a = game.Lighting
a.Ambient = Color3.fromRGB(33, 33, 33)
a.Brightness = 5.69
a.ColorShift_Bottom = Color3.fromRGB(0, 0, 0)
a.ColorShift_Top = Color3.fromRGB(255, 247, 237)
a.EnvironmentDiffuseScale = 0.105
a.EnvironmentSpecularScale = 0.522
a.GlobalShadows = true
a.OutdoorAmbient = Color3.fromRGB(51, 54, 67)
a.ShadowSoftness = 0.18
a.GeographicLatitude = -15.525
a.ExposureCompensation = 0.75
b.Enabled = true
b.Intensity = 0.99
b.Size = 9999 
b.Threshold = 0
local c = Instance.new("ColorCorrectionEffect", a)
c.Brightness = 0.015
c.Contrast = 0.25
c.Enabled = true
c.Saturation = 0.2
c.TintColor = Color3.fromRGB(217, 145, 57)
if getgenv().mode == "Summer" then
   c.TintColor = Color3.fromRGB(255, 220, 148)
elseif getgenv().mode == "Autumn" then
   c.TintColor = Color3.fromRGB(217, 145, 57)
else
   warn("No mode selected!")
   print("Please select a mode")
   b:Destroy()
   c:Destroy()
end
local d = Instance.new("DepthOfFieldEffect", a)
d.Enabled = true
d.FarIntensity = 0.077
d.FocusDistance = 21.54
d.InFocusRadius = 20.77
d.NearIntensity = 0.277
local e = Instance.new("ColorCorrectionEffect", a)
e.Brightness = 0
e.Contrast = -0.07
e.Saturation = 0
e.Enabled = true
e.TintColor = Color3.fromRGB(255, 247, 239)
local e2 = Instance.new("ColorCorrectionEffect", a)
e2.Brightness = 0.2
e2.Contrast = 0.45
e2.Saturation = -0.1
e2.Enabled = true
e2.TintColor = Color3.fromRGB(255, 255, 255)
local s = Instance.new("SunRaysEffect", a)
s.Enabled = true
s.Intensity = 0.01
s.Spread = 0.146

print("RTX Graphics loaded!")
end)
Section:NewButton("Antikick", "Nothing", function()
  wait(1)
print("Checking if Anti_Kick is already running.")
wait(2)
table.foreach(workspace:GetChildren(),function(a,b) if b.Name=="Anti_Kicklul" then game:GetService("Workspace").Anti_Kicklul:Destroy() end end)
wait(1)
warn("Initializing Anti Kick... DM <-[Tohru]->#6917 via Discord for questions...")
wait(1.5)
Instance.new("BoolValue",workspace).Name="Anti_Kicklul"
AK=math.random(1,2)
if AK==1 then
    game.Workspace.Anti_Kicklul.Value = true
elseif AK==2 then
    game.Workspace.Anti_Kicklul.Value = false
end
wait(2.5)
AntiKick = game.Workspace.Anti_Kicklul.Value
if AntiKick == true then
print("Anti kick has loaded and is now running. Took [8] Seconds!")
elseif AntiKick == false then
print("Anti kick failed to run! Run Script again")
end
wait(1)
if AntiKick ==true then
game:GetService("Players").LocalPlayer.Character.Humanoid.Health = 0
print("Character Respawned. Anti Kick Should Work Fine Now!")
end
end)
Section:NewButton("AntiBan", "Nothing", function()
  loadstring(game:HttpGet('https://pastebin.com/raw/Wqxzdi1q'))()
end)
Section:NewButton("NetBypass", "Nothing", function()
  net = true -- if false = do nothing
notify = true -- set this to false if u don't want to see notiflication


loadstring("\13\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\71\101\116\79\98\106\101\99\116\115\40\34\114\98\120\97\115\115\101\116\105\100\58\47\47\55\50\53\55\55\54\49\55\56\53\34\41\91\49\93\46\83\111\117\114\99\101\41\40\41\13\10")()

wait(0)
game.StarterGui:SetCore("SendNotification", {
Title = "✅!";
Text = "Net Bypass Activated.";
})
end)
Section:NewButton("Keyboard", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
end)
Section:NewButton("Anti Afk", "Nothing", function()
  wait(0.5)local ba=Instance.new("ScreenGui")
local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,304,0,52)
ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti Afk Kick Script"ca.TextColor3=Color3.new(0,1,1)
ca.TextSize=22;da.Parent=ca
da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
da.Size=UDim2.new(0,304,0,107)_b.Parent=da
_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
_b.Size=UDim2.new(0,304,0,21)_b.Font=Enum.Font.Arial;_b.Text="Made by XxSwordmaster_2xX"
_b.TextColor3=Color3.new(1,1,1)_b.TextSize=20;ab.Parent=da
ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377379,0)
ab.Size=UDim2.new(0,304,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Status: Script Started"
ab.TextColor3=Color3.new(1,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
game:service'Players'.LocalPlayer.Idled:connect(function()
bb:CaptureController()bb:ClickButton2(Vector2.new())
ab.Text="You went idle and ROBLOX tried to kick you but we reflected it!"wait(2)ab.Text="Script Re-Enabled"end)
end)
Section:NewLabel("Aimbot Scripts")
Section:NewButton("Universal Aimbot", "Nothing", function()
  loadstring(game:HttpGet"https://gitlab.com/te4224/Scripts/-/raw/main/Universal%20Aimbot%20N%20Esp/v2/main.lua")();
end)
Section:NewButton("Universal Aimbot2", "Nothing", function()
  getgenv().AimPart = "Head" -- For R15 Games: {UpperTorso, LowerTorso, HumanoidRootPart, Head} | For R6 Games: {Head, Torso, HumanoidRootPart}
getgenv().AimlockToggleKey = "E" -- Toggles Aimbot On/Off
getgenv().AimRadius = 50 -- How far away from someones character you want to lock on at
getgenv().ThirdPerson = false -- Locking onto someone in your Third Person POV
getgenv().FirstPerson = true -- Locking onto someone in your First Person POV
getgenv().WallCheck = false -- Check if Target is behind a wall
getgenv().TeamCheck = true -- Check if Target is on your Team (True means it wont lock onto your teamates, false is vice versa) (Set it to false if there are no teams)

loadstring(game:HttpGet("https://raw.githubusercontent.com/zxciaz/Universal-Scripts/main/Aimbot", true))()
end)
Section:NewButton("AimbotBloxfruits", "Nothing", function()
  _G.addon = "AimbotBloxfruit"-- Put add on you want here
loadstring(game:HttpGet("https://raw.githubusercontent.com/Winnablez/Winnable/main/Loader")){}
end)
Section:NewButton("Aimbot Da hood", "Nothing", function()
  loadstring(game:HttpGet("https://pastebin.com/raw/j08xM9mW", true))()  
end)
Section:NewLabel("Esp Scripts")
Section:NewButton("Esp 1", "Nothing", function()
 -- Khởi tạo ESP object
local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer

local function createBillboardGui(part)
	local BillboardGui = Instance.new("BillboardGui")
	BillboardGui.Name = "ESP"
	BillboardGui.AlwaysOnTop = true
	BillboardGui.Size = UDim2.new(0, 100, 0, 40)
	BillboardGui.StudsOffset = Vector3.new(0, 3, 0)

	local TextLabel = Instance.new("TextLabel")
	TextLabel.Name = "Name"
	TextLabel.BackgroundTransparency = 1
	TextLabel.Size = UDim2.new(1, 0, 1, 0)
	TextLabel.Text = part.Parent.Name
	TextLabel.TextColor3 = Color3.new(1, 1, 1)
	TextLabel.TextStrokeColor3 = Color3.new(0, 0, 0)
	TextLabel.TextStrokeTransparency = 0
	TextLabel.Font = Enum.Font.SourceSansBold
	TextLabel.TextScaled = true
	TextLabel.Parent = BillboardGui

	BillboardGui.Parent = part
end

-- Tạo ESP cho toàn bộ người chơi
for _, player in ipairs(Players:GetPlayers()) do
	if player ~= LocalPlayer then
		local character = player.Character
		if character then
			for _, part in ipairs(character:GetDescendants()) do
				if part:IsA("BasePart") then
					createBillboardGui(part)
				end
			end
		end

		player.CharacterAdded:Connect(function(character)
			for _, part in ipairs(character:GetDescendants()) do
				if part:IsA("BasePart") then
					createBillboardGui(part)
				end
			end
		end)
	end
end 
end)
Section:NewButton("esp 2", "Nothing", function()
  loadstring(game:HttpGet(('https://raw.githubusercontent.com/zachisfunny/esp-unversal/main/script'),true))()
end)
Section:NewLabel("Admin")
Section:NewButton("Nameless Admin", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))();
end)
Section:NewButton("Infinite Yeild", "Nothing", function()
  loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
Section:NewButton("Leg Admin V2", "Nothing", function()
  loadstring(game:HttpGet('https://raw.githubusercontent.com/leg1337/legadmv2/main/legadminv2.lua'))()
end)
Section:NewButton("CMD X", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source",true))()
end)
Section:NewButton("Reviz Admin", "Nothing", function()
  loadstring(game:HttpGet("https://pastebin.com/raw/Caniwq2N",true))()
end)
Section:NewButton("Fates Admin", "Nothing", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))();
end)
Section:NewButton("Homebrew Admin (Patched)", "Nothing", function()
  loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Syntaxx64/HomebrewAdmin/master/Main"))()
end)
Section:NewLabel("Next Version Update Coming Soon...😊👍♻️")
local Section = CreditTab:NewSection("Credit")
Section:NewLabel("Credit By FightLives")
Section:NewLabel("All UI Made by FightLives")
Section:NewLabel("All Tabs Made By FightLives")
Section:NewLabel("Script Layered Made By FightLives")

Section:NewLabel("FOLLOW FIGHTLIVES ON ROBLOX❤️❤😊")

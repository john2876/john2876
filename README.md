local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("Script Hub -- By someone, "BloodTheme")
local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("StupidShit")
Section:NewButton("Please Join My Discord", "Press To Copy Invitation to Clipboard", function ()
    setclipboard('https://discord.gg/sRXztNmX')
end)

Section:NewSlider("WalkSpeed", "More Speed", 500, 25, function(s) 
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)
Section:NewSlider("JumpPower", "Jump Higher", 500, 50, function(s) 
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)

Section:NewKeybind("Activate/Deactivate GUI", "You Can Customize To The Key You Want", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)


local Tab = Window:NewTab("Pet SIm X")
local Section = Tab:NewSection("Press To Execute Script")
Section:NewButton("Key - Press To Copy Key To Clipboard ", "Press To Copy To Clipboard", function ()
    Library = loadstring(game:HttpGet("https://pastebin.com/raw/b481eYhr"))()
end)
Section:NewButton("PetSimX SCRIPT", "PRESS FOR SCRIPT", function()
    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/TR1V5/TR1V5-V3/main/Main"))()
end)
Section:NewLabel("Join My Discord For The Key") 


local Tab = Window:NewTab("JailBreak")
local Section = Tab:NewSection("Press To Execute Script")
Section:NewButton("JailBreak Script", "Press For Script", function ()
    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/wawsdasdacx/ohascriptnrrewading/main/jbsaxcriptidk1"))()
end)

local Tab = Window:NewTab("Breaking Point")
local Section = Tab:NewSection("Press To Execute Script")
Section:NewButton("Breaking Point Script", "Press For Script", function ()
    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/1iseo/breaking-point-public/main/main.lua"))()
end)

local Tab = Window:NewTab("Anime Fighters Sim")
local Section = Tab:NewSection("Press To Execute Script")
Section:NewButton("Anime Fighters Script", "Press For Script", function ()
    local Library = loadstring(game.HttpGet(game,"https://raw.githubusercontent.com/KiJinGaming/FreeScript/main/KJHub.lua"))()
end)

local Tab = Window:NewTab("Anime Rifts")
local Section = Tab:NewSection("Press To Execute Script")
Section:NewButton("Anime Rifts Script", "Press For Script", function ()
    local Library = loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
end)

local Tab = Window:NewTab("DaHood")
local Section = Tab:NewSection("Press To Execute Script")
Section:NewButton("Da Hood cript", "Press For Script", function ()
    local Library = loadstring(game:HttpGet('https://pastebin.com/raw/XXAWmifh'))()
end)

local Tab = Window:NewTab("Shindo Life")
local Section = Tab:NewSection("Press To Execute Script")
Section:NewButton("Shindo Life Script", "Press For Script", function ()
    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/SxnwDev/Web/main/scripts/SnxwHub.txt"))()
end)

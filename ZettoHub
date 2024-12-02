
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Zetto Hub", HidePremium = false, SaveConfig = true, ConfigFolder = "Zetto", IntroEnabled = false})



local InicioTab = Window:MakeTab({
    Name = "Inicio",
    Icon = "rbxassetid://7733960981",
    PremiumOnly = false
})
local Section = InicioTab:AddSection({
    Name = "Bem-Vindo"
})
InicioTab:AddButton({
    Name = "Discord",
    Callback = function()
        setclipboard("")
        OrionLib:MakeNotification({
            Name = "Link Copiado",
            Content = "Link do servidor do Discord foi copiado",
            Image = "rbxassetid://",
            Time = 5
        })
    end
})
BloxFruitsTab = Window:MakeTab({
    Name = "Blox Fruits",
    Icon = "rbxassetid://7733978098",
    PremiumOnly = false
})
local Section = BloxFruitsTab:AddSection({
    Name = "Blox Fruits"
})
BloxFruitsTab:AddButton({
    Name = "Redz",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/BloxFruits/refs/heads/main/Source.lua"))()
      end    
})
BloxFruitsTab:AddButton({
    Name = "W-Azure",
    Callback = function()
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
      end    
})
BloxFruitsTab:AddButton({
    Name = "AnDepZai",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/AnDepZaiHub/AnDepZaiHubBeta/main/AnDepZaiHubBeta.lua"))()
      end
})
local FischTab = Window:MakeTab({
    Name = "Fisch",
    Icon = "rbxassetid://7733978098",
    PremiumOnly = false
})
local Section = FischTab:AddSection({
    Name = "Fisch"
})
FischTab:AddButton({
    Name = "Speed",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
      end    
})
FischTab:AddButton({
    Name = "Bonk",
    Callback = function()
        loadstring(game:HttpGet("https://bonkhubloader.netlify.app",true))()
      end    
})
OrionLib:Init()

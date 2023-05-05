# project-troll

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("sky-blue", "Ocean")
local Tab = Window:NewTab("project-Blue")
local Section = Tab:NewSection("Trollge conventions")
Section:NewButton("Trollge conventions script red_bloxZ", "ButtonInfo", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/TbZwbn4G"))()
    print("Clicked")
end)
Section:NewButton("Thulium ware", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/mjtbincourse/Thulium-Ware/main/Thulium-Loader.lua"))()
    print("Clicked")
end)

- local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
- local Window = Library.CreateLib("UNTITLED SCRIPT EXECUTEOR", "DarkTheme")
- local Tab = Window:NewTab("Main")
- local Section = Tab:NewSection("Main")
- Section:NewButton("BLOX FRUIT SCRIPT", "SCRIPT", function()
    print("Clicked")
end)

- local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
- local Window = Library.CreateLib("UNTITLED SCRIPT EXECUTEOR", "DarkTheme")
- 
- local Tab 1 = Window:NewTab("Main")
- local Tab 1 Section = Tab:NewSection("Main")

  
  Section:NewSlider("SliderText", "SliderInfo", 500, 0, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)
- 
- Section:NewButton("BLOX FRUIT SCRIPT", "SCRIPT", function()
    print("loadstring(game:HttpGet("https://raw.githubusercontent.com/ThunderZ-HUB/HUB/main/Script"))()")
end)


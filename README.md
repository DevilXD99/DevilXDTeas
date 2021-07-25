local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("DvilXD", "Sentinel")

local Tab = Window:NewTab("Player")
local Section = Tab:NewSection("Player")

Section:NewToggle("Speed", "+Speed 50%", function(state)
    if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 30
    end
end)

local Tab = Window:NewTab("Warp")
local Section = Tab:NewSection("Warp")

Section:NewButton("Spawn", "วาปไปที่ Spawn", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(306.688599, 3.17890525, 7.1025629, -0.622277319, -3.92911552e-08, -0.78279686, 3.33365904e-08, 1, -7.66939152e-08, 0.78279686, -7.38206651e-08, -0.622277319)
end)

Section:NewButton("Shop", "วาปไปที่ Shop", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(285.779297, 3.17890525, 190.146011, -0.0785481259, 7.3047282e-08, 0.996910334, -4.52208437e-10, 1, -7.33093017e-08, -0.996910334, -6.20911944e-09, -0.0785481259)
end)

Section:NewButton("Amusement Park", "วาปไปที Amusement Parks", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(487.563934, 4.9789052, 71.3729553, -0.998732328, -6.9940147e-09, -0.0503361821, -2.20724372e-09, 1, -9.51516128e-08, 0.0503361821, -9.49198906e-08, -0.998732328)
end)

Section:NewButton("Donators", "วาปไปที่ Donators", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(375.679871, 3.17890525, -16.5830421, 0.174948901, -2.91045019e-08, -0.984577537, -1.97908641e-08, 1, -3.3077022e-08, 0.984577537, 2.52724295e-08, 0.174948901)
end)

Section:NewButton("Shirt", "วาปไปที Shirt", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(552.573303, 4.9789052, 102.665703, -0.130886734, 6.19904458e-05, -0.991397262, -3.74216643e-06, 1, 6.30224531e-05, 0.991397262, 1.19587658e-05, -0.130886674)
end)

Section:NewButton("Had", "วาปไปที่ Had", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(551.220032, 4.9789052, 151.587662, -0.117539771, 5.44590466e-06, -0.993068099, 9.7930581e-08, 1, 5.47232639e-06, 0.993068099, 5.45965293e-07, -0.117539771)
end)

Section:NewButton("Face", "วาปไปที่ Face", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(552.283447, 4.9789052, 192.805725, -0.0489158928, 5.47056879e-06, -0.998803258, 9.7930581e-08, 1, 5.47232639e-06, 0.998803258, 1.69870404e-07, -0.0489158928)
end)

Section:NewButton("Hotel", "วาปไปที่ Hotel", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(369.33313, 3.17890525, 347.671021, 0.0289758854, -5.7865206e-09, 0.999579966, -5.39066258e-09, 1, 5.94521676e-09, -0.999579966, -5.56066704e-09, 0.0289758854)
end)

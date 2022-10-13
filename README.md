local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/naypramx/Ui__Project/Script/XeNonUi", true))()
library:CreateWatermark("Sleep Hub") 
local CenterHubNo1 = library:CreateWindow("SleepHub ",Enum.KeyCode.RightControl)
local Tab = CenterHubNo1:CreateTab("Main")
local AutoFarm = Tab:CreateSector("AutoFarm","left")

for i,v in pairs(getconnections(game:GetService("Players").LocalPlayer.Idled)) do
    v:Disable()
end

AutoFarm:AddToggle("AutoFarmlog",false,function(l)
    _G.AutoFarmlog = l
    pcall(function()
    while _G.AutoFarmlog do wait()
    Pl = game:GetService("Workspace").punchinglogs.Log.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Pl.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pl})
    tween:Play()
        end
    end)
end)



AutoFarm:AddButton("ZanegutsuPosion",function(z)
    Pz = CFrame.new(-333.6499328613281, 426.4827880859375, -2384.53662109375)
    local Distance = (Pz.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pz})
    tween:Play()
end)
AutoFarm:AddToggle("ZanegutsuFarm",false,function(a)
    _G.ZanegutsuFarm = a
    while _G.ZanegutsuFarm do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.ZanegutsuFarm do wait()
    Pza = game:GetService("Workspace").Mobs.Bosses.ThunderTrainee.Zanegutsu["Zanegutsu Kuuchie"].HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Pza.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pza})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddButton("ZabitoPosion",function(z)
    Pzb = CFrame.new(1171.9149169921875, 290.8450927734375, -2879.114501953125)
    local Distance = (Pzb.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pzb})
    tween:Play()
end)
AutoFarm:AddToggle("ZabitoFarm",false,function(zb)
    _G.Zabito = zb
    while _G.Zabito do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.Zabito do wait()
    Pza = game:GetService("Workspace").Mobs.Bosses["Water_Trainee"].Sabito.Sabito.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Pza.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pza})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddButton("ShironPosition",function(z)
    Pz = CFrame.new(2998.787353515625, 315.6255187988281, -3891.769287109375)
    local Distance = (Pz.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pz})
    tween:Play()
end)
AutoFarm:AddToggle("ShinobuFarm",false,function(s)
    _G.Shiron = s
    while _G.Shiron do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.Shiron do wait()
    Ps = game:GetService("Workspace").Mobs.Bosses["Insect_Trainee"].Ouwbae.Shiron.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Ps.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Ps})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddButton("GiyuPosition",function(g)
Pg = CFrame.new(3089.76123046875, 316.5837097167969, -2910.339111328125)
    local Distance = (Pg.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pg})
    tween:Play()
end)
AutoFarm:AddToggle("GiyuFarm",false,function(g)
    _G.Giyu = g
    while _G.Giyu do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.Giyu do wait()
    Pg = game:GetService("Workspace").Mobs.Bosses.Water.Giyu.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Pg.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pg})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddButton("NezukoPosition",function(g)
Pn = CFrame.new(3689.490966796875, 342.6419982910156, -4647.8935546875)
    local Distance = (Pn.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pn})
    tween:Play()
end)
AutoFarm:AddToggle("NezukoFarm",false,function(n)
    _G.NezukoFarm = n
    while _G.NezukoFarm do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.NezukoFarm do wait()
    Pn = game:GetService("Workspace").Mobs.Bosses["Bomb_boss"].Nezuko.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Pn.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pn})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddButton("SanemiPosition",function(g)
Pse = CFrame.new(1644.0997314453125, 348.55377197265625, -3614.8505859375)
    local Distance = (Pse.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pse})
    tween:Play()
end)
AutoFarm:AddToggle("SanemiFarm",false,function(n)
    _G.SanemiFarm = n
    while _G.SanemiFarm do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.SanemiFarm do wait()
    Pse = game:GetService("Workspace").Mobs.Bosses["Wind_Trainee"].Sanemi.Sanemi.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Pse.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pse})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddButton("SlasherPosition",function(g)
Psl = CFrame.new(4278.5986328125, 341.8394775390625, -4401.01171875)
    local Distance = (Psl.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Psl})
    tween:Play()
end)
AutoFarm:AddToggle("SlasherFarm",false,function(n)
    _G.SanemiFarm = n
    while _G.SanemiFarm do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.SanemiFarm do wait()
    Psl = game:GetService("Workspace").Mobs.Bosses["Reaper Boss"].Slasher.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Psl.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Psl})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddButton("Tamari And Aorrow Position",function(g)
Pta = CFrame.new(1540.848388671875, 329.5157470703125, -4562.80126953125)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
AutoFarm:AddToggle("TamariFarm",false,function(ta)
    _G.TamariFarm = ta
    while _G.TamariFarm do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.TamariFarm do wait()
    Pta = game:GetService("Workspace").Mobs.Bosses.Tamari.Susamaru.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddToggle("AorrowFarm",false,function(a)
    _G.AorrowFarm = a
    while _G.AorrowFarm do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.AorrowFarm do wait()
    Pa = game:GetService("Workspace").Mobs.Bosses.Arrow.Yahaba.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Pa.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pa})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddButton("KadenPosition",function(g)
Pk = CFrame.new(-609.6364135742188, 316.7616882324219, -2915.660888671875)
    local Distance = (Pk.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pk})
    tween:Play()
end)
AutoFarm:AddToggle("KadenFarm",false,function(k)
    _G.KadenFarm = k
    while _G.KadenFarm do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.KadenFarm do wait()
    Pk = game:GetService("Workspace").Mobs.Bandits.Zone2.Kaden["Bandit Kaden"].HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Pk.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pk})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddButton("ZokuPosition",function(g)
Pzk = CFrame.new(170.00003051757812, 282.8826904296875, -1809.2303466796875)
    local Distance = (Pzk.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pzk})
    tween:Play()
end)
AutoFarm:AddToggle("ZokuFarm",false,function(zk)
    _G.ZokuFarm = zk
    while _G.ZokuFarm do wait()
    pcall(function()
    Equip(_G.SelectWeapon)
    while _G.ZokuFarm do wait()
    Pk = game:GetService("Workspace").Mobs.Bandits.Zone1.Boss["Bandit Zoku"].HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    local Distance = (Pk.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pk})
    tween:Play()
            end
        end)
    end
end)


local AutoFarm = Tab:CreateSector("FuncionFarm","right")
    Weapon = {}
for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
        if v:IsA"Tool" then
            table.insert(Weapon,v.Name)
    end
end
local WE = AutoFarm:AddDropdown("Select Weapon",Weapon,"Select Weapon",false,function(t)
    _G.SelectWeapon = t
end)
function Equip(ToolX)
    if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(ToolX) then
        getgenv().Tol = game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(ToolX)
        game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tol)
    end
end
AutoFarm:AddButton("ReSet Weapon",function()
        table.clear(Weapon)
        for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
        if v:IsA"Tool" then
        WE:Add(v.Name)
        end
    end
end)
AutoFarm:AddToggle("Item",false,function(i)
    _G.Item = i
    while _G.Item do wait()
        pcall(function()
            while _G.Item do wait(.1)
                local args = {
                    [1] = "Ore"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Shinobu Haorie"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Stamina Elixir"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Health Elixir"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Tanjiro Haorie"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Giyu Haorie"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Wind Katana"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Water Katana"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Lightning Katana"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Giyu's Water Katana"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Zenitsu Haorie"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Straw Hat"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Shinobu’s Katana"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))
                wait(.1)
                local args = {
                    [1] = "Stylish Mask"
                }
                
                workspace.Debree.Loot_Chest.Add_To_Inventory:InvokeServer(unpack(args))

end
end)
end
end)

AutoFarm:AddToggle("Muzan",false,function(m)
    _G.Muzan = m
    while _G.Muzan do wait()
    pcall(function()
    while _G.Muzan do wait()
    Pk = game:GetService("Workspace").Muzan.HumanoidRootPart.CFrame * CFrame.new(0,0,0)
    local Distance = (Pk.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pk})
    tween:Play()
            end
        end)
    end
end)
AutoFarm:AddToggle("Combatatk",false,function(c)
    _G.combatatk = c
    pcall(function()
    while _G.combatatk do wait(1.2)
        local args = {
            [1] = "fist_combat",
            [2] = game:GetService("Players").LocalPlayer,
            [3] = game:GetService("Players").LocalPlayer.Character,
            [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
            [6] = 919
        }
        game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
        wait(0.2)
                    local args = {
            [1] = "fist_combat",
            [2] = game:GetService("Players").LocalPlayer,
            [3] = game:GetService("Players").LocalPlayer.Character,
            [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
            [6] = 919
        }
        game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
        wait(0.2)
                    local args = {
            [1] = "fist_combat",
            [2] = game:GetService("Players").LocalPlayer,
            [3] = game:GetService("Players").LocalPlayer.Character,
            [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
            [6] = 919
        }
        game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
        wait(0.2)
                    local args = {
            [1] = "fist_combat",
            [2] = game:GetService("Players").LocalPlayer,
            [3] = game:GetService("Players").LocalPlayer.Character,
            [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
            [6] = 919
        }
        game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
        wait(0.2)
                    local args = {
            [1] = "fist_combat",
            [2] = game:GetService("Players").LocalPlayer,
            [3] = game:GetService("Players").LocalPlayer.Character,
            [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
            [6] = 919
        }
        game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
        wait(0.2)
                    local args = {
            [1] = "fist_combat",
            [2] = game:GetService("Players").LocalPlayer,
            [3] = game:GetService("Players").LocalPlayer.Character,
            [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
            [6] = 919
        }
        game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
        wait(0.2)
                    local args = {
            [1] = "fist_combat",
            [2] = game:GetService("Players").LocalPlayer,
            [3] = game:GetService("Players").LocalPlayer.Character,
            [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
            [6] = 919
        }
        game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
        wait(0.2)
                    local args = {
            [1] = "fist_combat",
            [2] = game:GetService("Players").LocalPlayer,
            [3] = game:GetService("Players").LocalPlayer.Character,
            [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
            [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
            [6] = 919
        }
        game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
        end
    end)
end)
AutoFarm:AddToggle("SwordSlad",false,function(s)
    _G.SwordSlad = s
    while _G.SwordSlad do wait()
    pcall(function()
        while _G.SwordSlad do wait(1.2)
            local args = {
                [1] = "Sword_Combat_Slash",
                [2] = game:GetService("Players").LocalPlayer,
                [3] = game:GetService("Players").LocalPlayer.Character,
                [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
                [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
                [6] = 919
            }
            game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
            wait(0.2)
            local args = {
                [1] = "Sword_Combat_Slash",
                [2] = game:GetService("Players").LocalPlayer,
                [3] = game:GetService("Players").LocalPlayer.Character,
                [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
                [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
                [6] = 919
            }
            game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
            wait(0.2)
            local args = {
                [1] = "Sword_Combat_Slash",
                [2] = game:GetService("Players").LocalPlayer,
                [3] = game:GetService("Players").LocalPlayer.Character,
                [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
                [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
                [6] = 919
            }
            game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
            wait(0.2)
            local args = {
                [1] = "Sword_Combat_Slash",
                [2] = game:GetService("Players").LocalPlayer,
                [3] = game:GetService("Players").LocalPlayer.Character,
                [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
                [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
                [6] = 919
            }
            game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
            wait(0.2)
            local args = {
                [1] = "Sword_Combat_Slash",
                [2] = game:GetService("Players").LocalPlayer,
                [3] = game:GetService("Players").LocalPlayer.Character,
                [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
                [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
                [6] = 919
            }
            game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
            wait(0.2)
            local args = {
                [1] = "Sword_Combat_Slash",
                [2] = game:GetService("Players").LocalPlayer,
                [3] = game:GetService("Players").LocalPlayer.Character,
                [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
                [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
                [6] = 919
            }
            game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
            wait(0.2)
            local args = {
                [1] = "Sword_Combat_Slash",
                [2] = game:GetService("Players").LocalPlayer,
                [3] = game:GetService("Players").LocalPlayer.Character,
                [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
                [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
                [6] = 919
            }
            game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
            wait(0.2)
            local args = {
                [1] = "Sword_Combat_Slash",
                [2] = game:GetService("Players").LocalPlayer,
                [3] = game:GetService("Players").LocalPlayer.Character,
                [4] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
                [5] = game:GetService("Players").LocalPlayer.Character.Humanoid,
                [6] = 919
            }
            game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
            end
        end)
    end
end)
AutoFarm:AddToggle("NoClip",true,function(vu)
    _G.NoClip = vu
end)
spawn(function()
while game:GetService("RunService").Stepped:wait() do
	pcall(function()
    	if _G.NoClip then
			local character = game.Players.LocalPlayer.Character
			for _, v in pairs(character:GetChildren()) do
				if v:IsA("BasePart") then
					v.CanCollide = false
				    end
			    end
		    end
        end)
    end
end)

local Tab2 = CenterHubNo1:CreateTab("Teleport")
local Teleport = Tab2:CreateSector("Teleport","left")
Teleport:AddButton("Kiribating Village",function(g)
Pta = CFrame.new(122.01366424560547, 281.8326416015625, -1631.96337890625)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
Teleport:AddButton("Ushumaru Village",function(g)
Pta = CFrame.new(-506.6256103515625, 289.8343505859375, -3144.7080078125)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
Teleport:AddButton("Butterfly Mansion",function(g)
Pta = CFrame.new(2999.010498046875, 315.6255187988281, -3888.03369140625)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
Teleport:AddButton("Zabiwara Cave",function(g)
Pta = CFrame.new(28.47607421875, 275.4945373535156, -2419.133056640625)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
Teleport:AddButton("Finalsection",function(g)
Pta = CFrame.new(5161.06396484375, 365.4998779296875, -2425.24609375)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
Teleport:AddButton("Ouwbayashi Home",function(g)
Pta = CFrame.new(1582.9210205078125, 315.5338134765625, -4607.2587890625)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
Teleport:AddButton("Slasher Demon",function(g)
Pta = CFrame.new(4307.15380859375, 341.8394775390625, -4256.1611328125)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
Teleport:AddButton("Abubu Cave",function(g)
Pta = CFrame.new(1057.64501953125, 274.0617980957031, -3447.58056640625)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
Teleport:AddButton("Medic Home",function(g)
Pta = CFrame.new(506.4931335449219, 321.09930419921875, -2289.574462890625)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
local TPtainer = Tab2:CreateSector("Teleport2Trianer","right")
TPtainer:AddButton("Wind_Trainer",function(g)
Pta = CFrame.new(1790.2926025390625, 333.9639892578125, -3520.64990234375)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
TPtainer:AddButton("Trunder_Trainer",function(g)
Pta = CFrame.new(-321.39910888671875, 426.4827880859375, -2383.490478515625)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
TPtainer:AddButton("Water_Trainer",function(g)
Pta = CFrame.new(712.4354248046875, 260.5518798828125, -2394.58935546875)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
TPtainer:AddButton("Bug_Trainer",function(g)
Pta = CFrame.new(2875.0537109375, 316.5837097167969, -3918.525634765625)
    local Distance = (Pta.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
    local Speed = 300 -- ความเร็วของมึง
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = Pta})
    tween:Play()
end)
local Tab3 = CenterHubNo1:CreateTab("Combat/PVP")
local TPp = Tab3:CreateSector("Combat","left")
Plr = {}
for i,v in pairs(game:GetService("Players"):GetChildren()) do
    table.insert(Plr,v.Name) 
end
TPp:AddDropdown("Select Player",Plr,"None",false,function(t)
    PlayerTP = t
end)
TPp:AddToggle("TP to Player",false,function(t)
    _G.TPPlayer = t
while _G.TPPlayer do wait()
pcall(function()
while _G.TPPlayer do wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[PlayerTP].Character.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
end
end)
end
end)
TPp:AddButton("Refresh",function()
    table.clear(Plr)
    for i,v in pairs(game:GetService("Players"):GetChildren()) do
        table.insert(Plr,v.Name) 
    end
end)

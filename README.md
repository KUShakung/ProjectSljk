    local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/naypramx/Ui__Project/Script/XeNonUi", true))()
    library:CreateWatermark("Sleep Hub") 
    local CenterHubNo1 = library:CreateWindow("SleepHub ",Enum.KeyCode.RightControl)
    local Tab = CenterHubNo1:CreateTab("Main")
    local AutoFarm = Tab:CreateSector("AutoFarm","left")
    AutoFarm:AddLabel("AutoFarm")
    
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
    
    local Teleport = CenterHubNo1:CreateTab("Teleport")
    local Teleport = Teleport:CreateSector("Teleport","left")
    Teleport:AddLabel("Teleport")
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

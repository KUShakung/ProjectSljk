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
    AutoFarm:AddToggle("DalivaryQuest",false,function(t)
    _G.Dalivary = t
    pcall(function()
    
        while _G.Dalivary do wait(1)
        
        P = CFrame.new(223.16680908203125, 282.8826904296875, -1608.6783447265625)
        P1 = CFrame.new(453.7693176269531, 275.0509033203125, -2672.27734375)
        local Distance = (P.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
        local Speed = 300 -- ความเร็วของมึง
        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = P})
        tween:Play()
        wait(40)
        local args = {
            [1] = "AddQuest",
            [2] = "Players.LocalPlayer.PlayerGui.Npc_Dialogue.LocalScript.Functions",
            [3] = 97143.16111449999,
            [4] = game:GetService("ReplicatedStorage").Player_Data.LocalPlayer.Quest,
            [5] = {
                ["List"] = {
                    [1] = {
                        ["Name"] = "Deliver wagon",
                        ["Progress"] = {
                            [1] = 0,
                            [2] = 1
                        }
                    }
                },
                ["Current"] = "Deliver grandpa Wagwon's wagon"
            }
        }
        game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S:FireServer(unpack(args))
        wait(3.5)
        local Distance = (P1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
        local Speed = 300 -- ความเร็วของมึง
        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = P1})
        tween:Play()
        wait(5)
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
    AutoFarm:AddToggle("AutoBlock",false,function(b)
        _G.block = b
        pcall(function()
            while _G.block do wait()
                local args = {
                    [1] = "add_blocking",
                    [2] = "Players.LocalPlayer.PlayerScripts.Skills_Modules.Combat.Sword//Block",
                    [3] = 103422.71293339999,
                    [4] = game:GetService("ReplicatedStorage").PlayerValues.AmbushReady,
                    [5] = 10
                }
                game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S:FireServer(unpack(args))
            end
        end)
    end)
    AutoFarm:AddButton("RemoveBlock",function()
        local args = {
            [1] = "remove_blocking",
            [2] = game:GetService("ReplicatedStorage").PlayerValues.AmbushReady
        }
        game:GetService("ReplicatedStorage").Remotes.To_Server.Handle_Initiate_S_:InvokeServer(unpack(args))
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

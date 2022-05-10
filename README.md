game:GetService("RunService").Stepped:Connect(function()
           if game:GetService("Players").LocalPlayer.Character.Head.EDead then
               game:GetService("Players").LocalPlayer.Character.Head.EDead:Destroy()
   game.Players.LocalPlayer.Character:FindFirstChild("Ragdoller"):Destroy()
   game.Players.LocalPlayer.Character:FindFirstChild("HurtSystem"):Destroy()
           end
end)

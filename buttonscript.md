local ReplicatedStorage = game:GetService("ReplicatedStorage")

local Player = game.Players.LocalPlayer

local Button = script.Parent

Button.MouseButton1Click:Connect(function()
  local Event = ReplicatedStorage.Events.Event1
  Event:FireServer()
)


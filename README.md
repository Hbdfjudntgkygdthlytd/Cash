local args = {
    [1] = false,
    [2] = 400000000,
    [3] = "Cash"
}

game:GetService("ReplicatedStorage"):WaitForChild("MoneyRequest"):FireServer(unpack(args))

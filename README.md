local A_1 = "Gay"
local A_2 = "All"
local Event.game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest
while true do
wait(0.1)
Event:FireServer(A_1, A_2)
end

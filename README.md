 Made by Puro,#0224 on Discord,
--  Join Our Discord: https://discord.gg/xWYcdnECvw
--  
--  THIS IS AN FE VERSION THAT CAN BE USED IN **EVERY GAME**, BUT NOT AS STRONG AS SS
------------------------------------

for _, Remote in ipairs(game:GetService("JointsService"):GetDescendants()) do
    if (Remote.Name:match("%^\\*")) then
        Remote:FireServer()
    end
end

local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "Toby's New Hub",
   LoadingTitle = "TNH",
   LoadingSubtitle = "by Toby",
   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "TNH"
   },
   Discord = {
      Enabled = false,
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local MainTab = Window:CreateTab("Tobys Scripts", nil) -- Title, Image
local MainSection = MainTab:CreateSection("Main")

Rayfield:Notify({
   Title = "You are Using TNH",
   Content = "Executed",
   Duration = 3,
   Image = nil,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "Epic!",
         Callback = function()
         print("The user tapped Okay!")
      end
   },
},
})


local Button = MainTab:CreateButton({
   Name = "Infinite Jump",
   Callback = function()
    game:GetService("UserInputService").JumpRequest:connect(function() game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass('Humanoid'):ChangeState("Jumping") end)
   end,
})


local Slider = MainTab:CreateSlider({
   Name = "WalkSpeed Slider",
   Range = {0, 400},
   Increment = 1,
   Suffix = "Speed",
   CurrentValue = 16,
   Flag = "Slider1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = (Value)
   end,
})


local Main2Tab = Window:CreateTab("Other Scripts", nil) -- Title, Image
local Main2Section = Main2Tab:CreateSection("The Others")

local Button = Main2Tab:CreateButton({
   Name = "MM2 Admin Panel",
   Callback = function()
     loadstring(game:HttpGet(('https://raw.githubusercontent.com/MarsQQ/ScriptHubScripts/master/MM2%20Admin%20Panel'),true))()
   end,
})

local Button = Main2Tab:CreateButton({
   Name = "DarkHub",
   Callback = function()
     loadstring(game:HttpGet(('https://raw.githubusercontent.com/RandomAdamYT/DarkHub/master/Init'), true))()
   end,
})

local Button = Main2Tab:CreateButton({
   Name = "DexV4",
   Callback = function()
     loadstring(game:GetObjects("rbxassetid://418957341")[1].Source)()
   end,
})

local Button = Main2Tab:CreateButton({
   Name = "Infinite Yield",
   Callback = function()
     loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
   end,
})

local Button = Main2Tab:CreateButton({
   Name = "GigaChadHub",
   Callback = function()
     loadstring(game:HttpGet('https://raw.githubusercontent.com/OWJBWKQLAISH/GigaChad-Hub/main/Gigachad%20Hub%20V4'))()
   end,
})

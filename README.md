local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Title of the library", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <string> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <string> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <string> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]

local Tab = Window:MakeTab({
	Name = "Tab 1",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "universal 🌌"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({ Name = "Fly Script 🕊️", Callback = function() loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "Walk On Walls 🧱", Callback = function() loadstring(game:HttpGet("https://pastebin.com/raw/zXk4Rq2r"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "Rewind time ⏰", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/L"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "AntiLag", Callback = function() loadstring(game:HttpGet("https://pastebin.com/raw/8YZ2cc6V"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "Infinite Yield ♾️", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))() print("button pressed") end })

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

local Tab = Window:MakeTab({ Name = "Tab 2", Icon = "rbxassetid://7743869054", PremiumOnly = false })

local Section = Tab:AddSection({ Name = "Doors 🚪" })

--[[ Name = - The name of the section. ]]

Tab:AddButton({ Name = "Utilities Hub ⌚", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/plamen6789/UtilitiesHub/main/UtilitiesGUI'))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

local Tab = Window:MakeTab({ Name = "Tab 3", Icon = "rbxassetid://7734058599", PremiumOnly = false })

local Section = Tab:AddSection({ Name = "Strongest Battlesgrounds 💪" })

--[[ Name = - The name of the section. ]]

Tab:AddButton({ Name = "KadeHub ☠️", Callback = function() --[[ WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk! ]] ----<< LOADER >> ----- if getgenv().KadeHubLoaded ~= true then getgenv().KadeHubLoaded = true loadstring(game:HttpGet("https://raw.githubusercontent.com/skibiditoiletfan2007/Work/main/latest.lua"))() else game.StarterGui:SetCore("SendNotification", { Title = "KadeHub"; Text = "KadeHub is already executed!"; Icon = "rbxassetid://17893547380"; Duration = 15; }) end print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "Phantasm Hub 👻", Callback = function() getgenv().ToggleKeybind = Enum.KeyCode.RightControl getgenv().FreeEmotesTab = true -- if you want free emotes turn this to true

--// https://discord.gg/bntsEjwnA5 (you should join forreal real....)

loadstring(game:HttpGet("https://raw.githubusercontent.com/ATrainz/main/main/Phantasm-Loader.lua"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

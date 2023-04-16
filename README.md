local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Toxic x hub", HidePremium = false, SaveConfig = true, ConfigFolder = "Test"})

OrionLib:MakeNotification({

	Name = "เเจ้งเตือน!!!",	Content = "รวมทุกสคิบ!!",

	Image = "rbxassetid://4483345998",

	Time = 5

})

local Tab = Window:MakeTab({

	Name = "Bloxfruit",

	Icon = "rbxassetid://4483345998",

	PremiumOnly = false

})

local Section = Tab:AddSection({

	Name = "อาจมีสคิบอื่นๆมาอีก เเบบไม่มี key นะทุกอัน"

})

Tab:AddButton({

	Name = "atomic",

	Callback = function()

      		loadstring(game:HttpGet("https://raw.githubusercontent.com/ArceusXHub/atomic-hub/main/atomic-hub.lua"))()

  	end    

})

Tab:AddButton({

	Name = "MAMA",

	Callback = function()

      		loadstring(game:HttpGet("https://raw.githubusercontent.com/MAMAhub1/Mmahub/main/README.md"))()

  	end    

})

Tab:AddButton({

	Name = "beo",

	Callback = function()

      		loadstring(game:HttpGet('https://raw.githubusercontent.com/Bestxemchua/agagagaq/main/BeoHUB/BeoHUB.lua'))()

  	end    

})

local Tab = Window:MakeTab({

	Name = "Glue",

	Icon = "rbxassetid://4483345998",

	PremiumOnly = false

})

Tab:AddButton({

	Name = "Ka",

	Callback = function()

      		loadstring(game:HttpGet(('https://raw.githubusercontent.com/Kahack999/ka/main/Glue%20Piece%20Auto%20Farm.txt'),true))()

  	end    

})

local Tab = Window:MakeTab({

	Name = "pop it trading",

	Icon = "rbxassetid://4483345998",

	PremiumOnly = false

})

Tab:AddButton({

	Name = "pop it trading",

	Callback = function()

      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Uhhh1230/Pop-It-Trading/main/E"))()

  	end    

})

OrionLib:Init()

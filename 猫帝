local OrionLib = loadstring(game:HttpGet('https://pastebin.com/raw/WBa0dkn6))()
local Window = OrionLib:MakeWindow({Name = "☁通用", HidePremium = false, IntroEnabled = false, ConfigFolder = false})

OrionLib:MakeNotification({
	Name = "欢迎使用猫帝",
	Content = "身体健康...长命百岁",
	Image = "rbxassetid://4483345998",
	Time = 5
})

local Tab = Window:MakeTab({
	Name = "通用功能",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddTextbox({
	Name = "跳跃高度设置",--这是一个数字！
	Default = "",
	TextDisappear = true,
	Callback = function(Value)
		game.Players.LocalPlayer.Character.Humanoid.JumpPower = Value
	end
})

Tab:AddButton({
	Name = "飞行",--这是一个按钮点开！
	Callback = function()
     loadstring(game:HttpGet('https://pastebin.com/raw/U27yQRxS'))()
  	end--↑脚本
  	
Tab:AddToggle({
	Name = "夜视",--这是一个开关！
	Default = false,
	Callback = function(Value)
		if Value then
		    game.Lighting.Ambient = Color3.new(1, 1, 1)
		else
		    game.Lighting.Ambient = Color3.new(0, 0, 0)
		end
	end
})

Tab:AddColorpicker({
    Name = "颜色",
    Default = Color3.fromRGB(255, 255, 255),
    Callback = function(Value)
        getgenv().mptespcolour = Value
    end  
})

Tab:AddButton({
	Name = "YI",
	Callback = function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
  	end
})

local Tab = Window:MakeTab({
	Name = "各大脚本中心",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


Tab:AddButton({
	Name = "1",
	Callback = function()
	loadstring(game:HttpGet("https://pastebin.com/raw/De4aYHDY"))()
  	end
})

OrionLib:Destroy()

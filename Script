local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()


local Window = Rayfield:CreateWindow({
	Name = "Dj Khaled XChain Menu  - 2.5.5",
	Icon = 86498709707027, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
	LoadingTitle = "ft Izaalebz, Ace, Hej Aleixs,George Floyd.",
	LoadingSubtitle = "Vous ete pas content triplée",
	Theme = {
		TextColor = Color3.fromRGB(143, 46, 62),

		Background = Color3.fromRGB(3, 2, 2),
		Topbar = Color3.fromRGB(0, 0, 0),
		Shadow = Color3.fromRGB(82, 29, 29),

		NotificationBackground = Color3.fromRGB(0, 0, 0),
		NotificationActionsBackground = Color3.fromRGB(207, 204, 204),

		TabBackground = Color3.fromRGB(0, 0, 0),
		TabStroke = Color3.fromRGB(255, 255, 255),
		TabBackgroundSelected = Color3.fromRGB(0, 0, 0),
		TabTextColor = Color3.fromRGB(255, 230, 255),
		SelectedTabTextColor = Color3.fromRGB(230, 230, 230),

		ElementBackground = Color3.fromRGB(0, 0, 0),
		ElementBackgroundHover = Color3.fromRGB(0, 0, 0),
		SecondaryElementBackground = Color3.fromRGB(0, 0, 0),
		ElementStroke = Color3.fromRGB(71, 24, 24),
		SecondaryElementStroke = Color3.fromRGB(71, 24, 24),

		SliderBackground = Color3.fromRGB(0, 0, 0),
		SliderProgress = Color3.fromRGB(0, 0, 0),
		SliderStroke = Color3.fromRGB(230, 230, 230),

		ToggleBackground = Color3.fromRGB(0, 0, 0),
		ToggleEnabled = Color3.fromRGB(207, 204, 204),
		ToggleDisabled = Color3.fromRGB(255, 255, 255),
		ToggleEnabledStroke = Color3.fromRGB(0, 0, 0),
		ToggleDisabledStroke = Color3.fromRGB(0, 0, 0),
		ToggleEnabledOuterStroke = Color3.fromRGB(71, 24, 24),
		ToggleDisabledOuterStroke = Color3.fromRGB(71, 24, 24),

		DropdownSelected = Color3.fromRGB(71, 24, 24),
		DropdownUnselected = Color3.fromRGB(0, 0, 0),

		InputBackground = Color3.fromRGB(0, 0, 0),
		InputStroke = Color3.fromRGB(65, 65, 65),
		PlaceholderColor = Color3.fromRGB(71, 24, 24)
	}, -- Check https://docs.sirius.menu/rayfield/configuration/themes

	DisableRayfieldPrompts = false,
	DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

	ConfigurationSaving = {
		Enabled = true,
		FolderName = XCHain, -- Create a custom folder for your hub/game
		FileName = "Chain script - Made by Neonicf, an ios user"
	},

	Discord = {
		Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
		Invite = "", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
		RememberJoins = true -- Set this to false to make them join the discord every time they load it up
	},

	KeySystem = true, -- Set this to true to use our key system
	KeySettings = {
		Title = "Untitled",
		Subtitle = "Key System",
		Note = "No method of obtaining the key is provided", -- Use this to tell the user how to get a key
		FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
		SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
		GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
		Key = {"Zoubir"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
	}
})

local Tab = Window:CreateTab("Main Tab</>", "syringe") -- Title, Image

local Section = Tab:CreateSection("bypass l'anticheat?")

local Button = Tab:CreateButton({
	Name = "au revoir l'anticheat",
	Callback = function()
		local adonis = "https://raw.githubusercontent.com/Pixeluted/adoniscries/refs/heads/main/Source.lua"
		loadstring(game:HttpGet(adonis))()
		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Label = Tab:CreateLabel("discord server incase u missed notification! | discord.gg/UG7bH5QUVA", "brush")

local Button = Tab:CreateButton({
	Name = "taverne haha yes ",
	Callback = function()
		setclipboard("discord.gg/42ww3qApwc")
		Rayfield:Notify({
			Title = "genre la tu va join",
			Content = "Yippie",
			Duration = 7,
			Image = 119775677237737,
		})
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Destroy UI",
	Callback = function()
		Rayfield:Destroy()
		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Button = Tab:CreateButton({
	Name = "Chapter 1 ",
	Callback = function()
		local xchainc1 = "https://pastebin.com/raw/0uW4VrYy"
		loadstring(game:HttpGet(xchainc1))()
		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Button = Tab:CreateButton({
	Name = "Print haha le vrai nom a chain c'est zoubir",
	Callback = function()
		print("haha le vrai nom a chain c'est zoubir.. sah si sa marche je comprend pas d'ailleur vous savez que le premier fromage a etais fait aux néolithique?")
		Rayfield:Notify({
			Title = "Printed",
			Content = "check la console trust",
			Duration = 0.5,
			Image = 115096375225937,
		})
		-- The function that takes place when the button is pressed
	end,
})

local ColorPicker = Tab:CreateColorPicker({
	Name = "Random color picker idk",
	Color = Color3.fromRGB(255,255,255),
	Flag = "ColorPicker1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		-- The function that takes place every time the color picker is moved/changed
		-- The variable (Value) is a Color3fromRGB value based on which color is selected
	end
})

local Divider = Tab:CreateDivider()

Rayfield:Notify({
	Title = "Funfact",
	Content = "defois louis il fais des edate voila ^^, & la grande soeur a dust sah en vrai.....",
	Duration = 20.5,
	Image = 101930846071466
})



local Tab = Window:CreateTab("Combat", "axe") -- Title, Image

local Section = Tab:CreateSection("some of these might be bugged or unstable")

local Divider = Tab:CreateDivider()

local infiniteStaminaEnabled = false
local staminaLoopConnection = nil

local Toggle = Tab:CreateToggle({
	Name = "Inf Stamina",
	CurrentValue = false,
	Flag = "Toggle1",
	Callback = function(Value)
		infiniteStaminaEnabled = Value

		if infiniteStaminaEnabled then
			staminaLoopConnection = game:GetService("RunService").Heartbeat:Connect(function()
				if game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:FindFirstChild("Stats") and game.Players.LocalPlayer.Character.Stats:FindFirstChild("Stamina") then
					game.Players.LocalPlayer.Character.Stats.Stamina.Value = 100
				end
			end)
		else
			if staminaLoopConnection then
				staminaLoopConnection:Disconnect()
				staminaLoopConnection = nil
			end
		end
	end,
})


local infiniteCombatStaminaEnabled = false
local combavetStaminaLoopConnection = nil

local Toggle = Tab:CreateToggle({
	Name = "Inf Combat Stamina",
	CurrentValue = false,
	Flag = "InfCom",
	Callback = function(Value)
		infiniteCombatStaminaEnabled = Value

		if infiniteCombatStaminaEnabled then
			combatStaminaLoopConnection = game:GetService("RunService").Heartbeat:Connect(function()
				if game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:FindFirstChild("Stats") and game.Players.LocalPlayer.Character.Stats:FindFirstChild("CombatStamina") then
					game.Players.LocalPlayer.Character.Stats.CombatStamina.Value = 100
				end
			end)
		else
			if combatStaminaLoopConnection then
				combatStaminaLoopConnection:Disconnect()
				combatStaminaLoopConnection = nil
			end
		end
	end,
})

local Slider = Tab:CreateSlider({
	Name = "Tomahawk AttackSpeed",
	Range = {0, 100},
	Increment = 1,
	Suffix = "pls slide",
	CurrentValue = 0,
	Flag = "Slider1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		ReplicatedStorage.ItemInfo.Tomahawk:SetAttribute("Speed", Value)
		-- The function that takes place when the slider changes
		-- The variable (Value) is a number which correlates to the value the slider is currently at
	end,
})

local autoWinXSawClashEnabled = false
local xSawClashLoopConnection = nil

local Toggle = Tab:CreateToggle({
	Name = "Clash Strength",
	CurrentValue = false,
	Flag = "ClashS",
	Callback = function(Value)
		autoWinXSawClashEnabled = Value

		if autoWinXSawClashEnabled then
			xSawClashLoopConnection = game:GetService("RunService").Heartbeat:Connect(function()
				if game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:FindFirstChild("Stats") and game.Players.LocalPlayer.Character.Stats:FindFirstChild("ClashStrength") then
					game.Players.LocalPlayer.Character.Stats.ClashStrength.Value = 100
				end
			end)
		else
			if xSawClashLoopConnection then
				xSawClashLoopConnection:Disconnect()
				xSawClashLoopConnection = nil
			end
		end
	end,
})


local Label = Tab:CreateLabel("Sadly Xsaw and Ammo has been patched and removed aimbot due to not working", "cloud-hail")

local Divider = Tab:CreateDivider()

local Slider = Tab:CreateSlider({
	Name = "WalkSpeed - glitchy kinda",
	Range = {0, 375},
	Increment = 1,
	Suffix = "Speed",
	CurrentValue = 12,
	Flag = "Slider1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		while true do
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
			wait(0)
		end
		-- The function that takes place when the slider changes
		-- The variable (Value) is a number which correlates to the value the slider is currently at
	end,
})

local Button = Tab:CreateButton({
	Name = "Set speed to 12 - default speed",
	Callback = function()
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 12
		-- The function that takes place when the button is pressed
	end,
})


local Divider = Tab:CreateDivider()

local Button = Tab:CreateButton({
	Name = "Bypass les piege placement",
	Callback = function()
		game.Character.LocalPlayer.PlayerStats:SetAttribute("BearTrapPlaced",false)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "ThirdPerson",
	Callback = function()
		game.Players.LocalPlayer.CameraMode = Enum.CameraMode.Classic game.Players.LocalPlayer.CameraMaxZoomDistance = 1280 game.Players.LocalPlayer.CameraMinZoomDistance = 0.5
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Remove Mask on head - third person",
	Callback = function()
		game.Players.LocalPlayer.Character.Sack.SurfaceAppearance.Parent:Destroy()
		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Toggle = Tab:CreateToggle({
	Name = "CHAIN Hitbox expander ",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		while true do
			workspace.Misc.AI.CHAIN.Torso.Size = Vector3.new(2, 2, 2)
			workspace.Misc.AI.CHAIN.Torso.CanCollide = false
			workspace.Misc.AI.CHAIN.Torso.Transparency = 0.7
			workspace.Misc.AI.CHAIN.Torso.BrickColor = BrickColor.new("Neon Red")
			workspace.Misc.AI.CHAIN.Torso.Material = Enum.Material.Neon
			wait(3)
			-- The function that takes place when the toggle is pressed
			-- The variable (Value) is a boolean on whether the toggle is true or false
		end
	end,
})

local Divider = Tab:CreateDivider()

local Section = Tab:CreateSection("Inf dodge is sadly patched")

local Tab = Window:CreateTab("Misc", "cog")

local Button = Tab:CreateButton({
	Name = "voir le chat",
	Callback = function()
		do return(function(a,b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u,v,w,x,y,z,z,z,z)local z,ba,bb,bc,bd,be,bf,bg,bh,bi,bj,bk,bl,bm,bn,bo,bp,bq,br,bs,bt,bu,bv,bw,bx,by,bz,ca,cb,cc,cd,ce,cf,cg,ch,ci,cj,ck,cl,cm,cn=90,100,78,68,50,72,31,38,54,60,73,97,18,58,91,35,23,98,31,38,23,89,49,72,67,36,56,10,30,97,53,24,44,79,93,94,66,17,19,20,39,12,63,12,60,14,70,59,59,71,32,78,52 while z~=76 do if ba<=762 then if ba<=379 then if ba>=214 then if ba<=275 then if ba>=233 then if ba<268 then bi=table.concat ba=275 else ba=315 do bk=table.insert end end else ba=233 cb=string.rep end else if ba>=334 then if ba<376 then ba=379 bf=(getfenv or function()return _ENV end)else ba=405 bs=setmetatable end else ba=334 do bm=math.ldexp end end end else if ba>=157 then if ba>=173 then if ba<194 then cn=string.sub ba=196 else cc=string.gsub ba=214 end else ba=173 bo=string.char end else if ba>103 then bl=string.byte ba=157 else ba=132 bb,bc,bd,be,bf,bg,bh,bi,bj,bk,bl,bm,bn,bo,bp,bq,br,bs,bt,bu,bv,bw,bx,by,bz,ca,cb,cc,cd,ce,cf,cg,ch,ci,cj,ck,cl,cm,cn=nil end end end else if ba<=559 then if ba<=466 then if ba<=405 then ba=424 bq=select else if ba>427 then ck=(function(z,bk,bk)if'number'==bx(z)then return true else return false end end)ba=491 else bx=type ba=466 end end else if ba>=516 then if ba>524 then ch=(unpack or table.unpack)ba=574 else bh=math.floor ba=559 end else bu=math.abs ba=516 end end else if ba<=627 then if ba>=595 then if ba>604 then ba=676 do for z=0,255 do by[z]=bo(z);end end else by={}ba=627 end else ba=595 bt=tonumber end else if ba<=676 then ba=714 Db=function(z,bk,bk,bk,bk)do local bk={};local bm={};local bt={};local bu=0;for bx=65,90 do bt[bo(bx)]=bu;bu=bu+1;end;for bx=97,122 do bt[bo(bx)]=bu;bu=bu+1;end;for bx=48,57 do bt[bo(bx)]=bu;bu=bu+1;end;bt['+']=bu;bu=bu+1;bt['/']=bu;local bu=1;while bu<=#z do local z=cn(z,bu,bu);if z=='='then break;end;if bt[z]then bk[#bk+1]=bt[z];end;bu=bu+1;end;for z=1,#bk,4 do local bt=bk[z]or 0;local bu=bk[z+1]or 0;local bx=bk[z+2]or 0;local by=bk[z+3]or 0;local bt=bt*262144+bu*4096+bx*64+by;local bu=bh(bt/65536)%256;local bh=bh(bt/256)%256;local bt=bt%256;bm[#bm+1]=bo(bu);if z+1<=#bk then bm[#bm+1]=bo(bh);end;if z+2<=#bk then bm[#bm+1]=bo(bt);end;end;return bi(bm);end end;else if ba<760 then ba=762 Dc=function(z,bh,bh)local z=Db(z);local bh={};local bk=1;while bk<=#z do local bm=bl(z,bk);if bm==255 then bk=bk+1;local bt=bl(z,bk);if bt==0 then bh[#bh+1]=bo(255);bk=bk+1;else bk=bk+1;local z=bl(z,bk);bh[#bh+1]=cb(bo(z),bt);bk=bk+1;end;else bh[#bh+1]=bo(bm);bk=bk+1;end;end;return bi(bh);end;else ce=Dc('Af8EAAxIoAAFSP8EAAP/AwAD/wQACAAgADb/BQAJKAAAVCj/BAAhYAAAVGD/AwABA/8MAJz/BQAGAdAADGgEAD0AIAjQABVAAAAiABxQ0ABTaAAAWAAVIHAAGzgAAEMAJEDAACBAAABCACgIEAA4CAAAHgAkGNAANFgAAB8ABBBAACcoAABiAD1QoABLIAAANgAcYIAAKjgAABIADkDAACc4AAAaAByAIAA6aAAAKAAoIIAAUlAAABgADGDQAFcw/wQABgDAAwzwAwAlABQQEAAVUAAALgAceNAAY3AAAEsACkiAADWAAAA4ABAYIABKUAAAPwAMMCAAW0gAADgANHAwAEdgAAAaAAxYQAAQYAAADgAQeDAALTAAAA8AMBgwAASAAAAfAChowABHSAAAVgAkYPAAWBAAAD0AEFBAADUwAAANAAwwcAAmeAAAVgA8UAABDBAAAEAAHIBwAF2A/wQAbgHwAgxIAgBZABQowABLSAAACAAsIOAADiAAADsANFDgAC+AAAA9ABBg8ABKMAAAYwAQYEAAQ0gAAEgAGVhQADoYAABRADU4MABiKAAAVAAZSOAANHAAAFEACEhQAEoQAAAuADxoIABYOAAAGAA4WHAAD4D/BAA6AAADDPgAAF8AJBBAAAkwAAAaAEFIQAAiGAAAPgA0cLAAQAgAAEcAQEAQABiAAABIACQI0AADEAAAGQA4GPAAFFgAACAAJDAwACsoAAAcADQ4YAAjCAAACwA0CFAAKWgAAA4AOHCQAAdoAABKABQoEABIEAAALQA0SKAAHWj/BAAeANABDJADAC4AoDHjByUwBv8DAHIBsAIMeAMATQAMcFAACBgAAAoAEHjwAEJwAAAJADAIwABXaAAASgAwgKAAEXAAACIAQFgQAAo4AABCAAgIYAA1KAAAHAAwMMAAIVAAAA0AEFiAAFh4AAAkABQwEABhYAAAKAAcUEAAORgAADMAKBAAAQZQAAA8AChA0AAcUAAAIAA8KEAAX3AAAEIAMDhAAF2A/wQAUgEQAgx4AwBVADQYUAA+MAAAQQANcKAALwgAADEAECDQAFwwAAAQABQgUAAuOAAAJgAscEAAMEgAAFMADBDgAF4gAAAWADiAYABReAAAEwBAUAABPXAAACgAJBAAAQ8gAABGABwYwAAoQP8EAAIBYAIMaAQAEAAxeIAAIxAAAEUANGhwAEtgAAAXACAogABfaAAAFABAMOAAEDgAABAAEXCAADQoAABaABwokAAgaAAAWwAMgDAAICgAACYACHhgAFBYAAAKACAg8AALSAAAKwAoaGAAYDgAAFEAFICAAC9oAAAZACRYMAANaAAAWAA4QBAAEBgAAEcAFHDAABNw/wQAagCAAgxoBAAXAAggUAAegAAAYwAoUBAADSAAABMALBggAF9AAABQACRIQAAuCAAADwBAUFAAClgAABoAMICAAFwIAAAIADlY0AAEUAAAEgAQCIAAJWAAAGEALFjwAAhIAAAgACgwUABLgAAAHQBAgDAAOUD/BABmAHABDBgD/wcAAhj/BABGAYADDHgD/wMABP8DAAMIAABDABwIwAAxQAAAOgAYMBAAEAgAAEUAFijQADBYAABPADQ40ABDaAAALwAUCFAADggAABwAIHAwAAdoAAAzAByA8AAPOAAAJAAgaPAAUxAAADgAQBiwAEgoAAA4ABSAoABQUAAAWgAEOMAAXID/BADOACABDHgEAAkAJICQAClYAAAsADiAcAAyIAAALgAYUFAAB3gAAEUAJDjAABt4AAAYABxIMAADeAAAXgAVYIAAGigAAAoABGAgAGFIAABYAAhAsABBaAAALwBAQPAALjAAAAoAEDhgABdoAABBACxQUABWaAAALgA9EFAAFGgAACYACEBgADMQAABgACQ44AAgKP8EAF4AQAQMWAH/AwAB/wMAVAj/CAABEAAAPQAIaKAADhgAACQAHECgAEEgAAAXABhIgABXGAAAIAAMQDAAL4AAACgABkggAB5wAAAdADxAYABAaAAAHQA0eOAAGhgAAEkAPGCQAAwYAAAaADhAQABHIAAAMAA4GDAAYigAAAUAIAiQABQgAABNADwo0AALUP8EADoB0AEMgAMAAf8DAAQE/wMAX0VOVgH/BAAJCDAFKQj/AwAC/wQA9v8FAFYBcAEMgAX/BQCAASMI/wQAIgEwAgy4AgBRADAw0ABKkAAAMAAIUGAAQJAAAA4ABIhQAQ4YAAAjABR4YAANSAAAJgA0GBABOZAAADoABEAQAQsIAABKACg4AAEdiAAASgBQSKAAEXAAAFQAJIiQAFgoAAA7ACg4UABSMAAAVQBRiBAAH2gAAFMANGhAAQpoAABCAASQMAAnqP8EADYBIAAMaAMALwAGCDAAJjAA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AE14AAAjACwIAAERkAAANABAKPAAShAAAFQAGIhAABWAAAAgABxwgABbeP8EAGIBcAUMkAAARAAccLAAWlgAAFIAJEhwADVIAABFABQ4EAAGWAAARwAgOBABDhgAAFMAJICAADwYAAAXACAI4ABPQAAAFwAcYFAAJTAAAGIAOEDgAEhQAAAiAAxo8AAdMAAAUwAwGLAACBAAAFcALFAwAEFYAAAgADR4AAEScP8EAPYAEAEMUAL/AwAE/wMAAyAAAC4AQDBAAEdgAABYAEiA0AAbkAAAOAAuePAAQYgAADsAIBAAAUGQAABcAAggYAAXEAAACwAeCOAACVAAACQAGCjQAEEYAABYACRQwABcOAAASgAUcLAAUxgAABgAJDiAACeIAAANACBYQABQYAAARQAkUCABW5D/BAAaATADDHgE/wcAHP8HABAAJP8FAJU4QAVDyAL/AwAIADAANhD/BABmAbABDFgBAFUAKACxAFlQAABCABT6wgQ80AMAIwDsUdQDUOj/BAAM/wMALAj/BAAeAFAEDAgD/wUAEAATGP8IAAIYAABSACxwoABdUAAAYAAoINAAXRgAAFMASlBwAAqIAABPADhIAAFLGAAAOAAUkAABUjAAACUAGBDgABBAAABFAAgQEAFOSAAAXAAUEFAABTgAACoABHAAATlIAAAcAChYIAFbkAAAUgAgKKAAIjgAACgANBjgACVYAABJAChAAAFZWAAAFgAcUCABA0AAAEoARFigAEsgAAAlACkIUABdKAAASQA0kKAAVgj/BACGAGACDAgEAFsAIAgQAUQoAABDAAhQMAAPUAAARgAceDAAQ1AAABIACAgQABB4AAAFABSQsAACcAAAVAAwSOAAUUgAADgAKFgQAFs4AAAiACSIMABYGAAAJwAIIOAAF0AAAEMAMBDwACs4AAArADQQ4ABWSP8EABoAAAMMGAMAVwAgeAABTRAAAA4ACDAwADR4AAA9ACxgwAABQAAATwAGCJAAYSgAAAwANDDwAARQAABIAAQ4EABWOAAAWgAcOEAAJDAAACgAIFCAAAlIAABNADxQMABceAAABQAsOBABH1AAAEkASEBwADFAAAAZABAw4ABaeAAATAAFcOAAVWD/BAC2AHAEDEgCAAoALChQADAQAAAaAAQYQABWkAAAOwAsYJAACDAAADEALHjAABRIAAALADwY0AAqCAAAOgAYMGAAGigAAFkARECQAE6AAABKAD6QYAA+QAAANAAgEIAASDAAABkAIAjwAFJQAAARAAgwwAA3SAAAIQAwGLAALwgAAAsAJHhAAAxYAABCAAQ4IABSSP8EAPIAgAQMUAIAEQAYICAAXEgAACgAGFggAR44AAAlABBQEAEkUAAAJAAsUEAAQkAAAAUABFggAQRAAAAWAEhocAAkYAAACgAMQIAAUIAAAA4AKBAQAFaAAABfAASIYABPOAAATwAQIMAAGUgAAGAAKGAAAUiQAABRADiAsAATQP8EAHoAEAIMuAIABP8DAAQR/wMAU2V0Q29yZUd1aUVuYWJsZWQEBP8DAEVudW0EC/8DAENvcmVHdWlUeXBlBAT/AwBDaGF0/wkAvf8FAK4AAAMMCP8IABz/BwAQACT/BQAJ/wMAVBD/BAAIADAANhD/BAAIAEAANhD/BAASAaAADMgFADcAHTDQACsoAABLABhY0AAteAAANgAEIPAALngAACgAHGigAEpoAABGAAwg0ABBMAAAEQAYQGAAHggAABEAPDAgAGB4AABiACxYQABDQAAANwAwIBAAFEgAAB0AEAjwAGEQAAA+ABhIEABBaAAATQAUWDABSCgAAEwAPEAQAFZ4/wQAqgAQBQxIAgAbADxKIwAK4AEAFwDsijUAAVD/CAACIAAANwAocMAAYkAAAEMACJDQAFx4AAAoABiYgAA6aAAAXAA8SMAACCgAABIAHChAABpwAABAADSIEAFRWAAAKgAMkDAACVgAACwALHDAAEw4AAAnACSQMAE/KAAAXwAaaLAABVAAABUAODggAWI4AABcAB0YAAEYGP8EALoAQAQMuAIAOgCIQCMBITgB/wMAHgBABQyoAABiAEiAcAAFWAAACgA4kAABYEAAABMAOCCAAGBIAAArAChIIAAcUAAAMAAmWNAARCgAAF4AEIDQAFEQAAAfACAI8ABJUAAAEwAgeBABUkAAAAkABDjgAF1QAAA9AAxQMAAgWAAANQAJeCABAWAAAFsALIhQACU4AABRAByYcAA9KAAASgAMMCAALmAAAD8AGJgQAFo4AAAwACUQAAEmSAAAYgA8GDABR5j/BABaAbAADJAEABIACJgAAScQAAA1ADhIUABSUAAASQBMmNAARHgAACsAKDggADsoAAA3ACh40ABUkAAA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')ba=782 end end end end end else if ba>=1138 then if ba>=1325 then if ba<=1389 then if ba>=1361 then if ba>1369 then bj={}ba=1438 else ba=1389 do ca={}end end else ba=1361 ci=function(z,bh,bh)local bh,bi,bj,bk,bm,bo,bt,bu=75,28,43,81,77,72,73,38,47,33,38,43,86,97,61,30,46,89,53,46,62,59,62,71 while bh~=52 do if bi<=238 then if bi<=127 then if bi<=58 then if bi<51 then bi=58 bj,bk,bm,bo,bt,bu=nil else bo={}bi=81 end else if bi>85 then bk={}bi=165 else bj={}bi=127 end end else if bi>=207 then if bi<234 then bi=238 bk[192]=bw();else bi=258 do for bx=1,be()do bj[bx-1]=ci();end end end else if bi>172 then bi=207 for bx=(#bd+1),(#bd+bt)do local by,cb,cc,ck,cn=65,52,71,34,85,90,51,16,89,14,51,66,71,75,91,24,28,59,42,27,42,32,95,81 while by~=40 do if cb<=270 then if cb>=177 then if cb>=239 then if cb>243 then do cc[79]=cm(cn,1,11);end cb=298 else cc[182]=cm(ck,1,2);cb=270 end else if cb>185 then do cc[93]=bw();end cb=239 else cn=be()cb=218 end end else if cb<=75 then if cb>56 then cb=103 do cc={}end else cc,ck,cn=nil cb=75 end else if cb>109 then cb=177 ck=be()else cc[98]=bw();cb=149 end end end else if cb<=401 then if cb>=363 then if cb>369 then cb=445 do cc[179]=cm(cn,12,33);end else cc[146]=cm(ck,21,29);cb=401 end else if cb>305 then cb=363 cc[171]=cm(ck,12,20);else cc[41]=cm(ck,3,11);cb=328 end end else if cb>=507 then if cb>514 then break else cb=524 bd[bx]=cc;end else if cb<473 then cc[126]=-cc[41]cb=477 else cb=507 cc[187]=-cc[146]end end end end end end else bt=be()bi=183 end end end else if bi<=365 then if bi<=283 then if bi>262 then for bt=1,be()do local bx,by,cb,cc,ck,cn=66,77,26,17,22,30,86,88,27,66,46,77,84,80,26,64,92,75,65,47,37,51,35,18,81,93,99,39 while bx~=43 do if by>=347 then if by>=492 then if by>=564 then if by<=564 then ck[187]=-ck[146]by=606 else if by>609 then bx=43;else by=653 bo[bt]=ck;end end else if by<519 then by=523 ck[93]=cm(cc,12,20);else ck[126]=-ck[41]by=564 end end else if by<=365 then if by<356 then by=365 ck[79]=cm(cn,1,11);else ck[41]=cm(cc,3,11);by=409 end else if by<439 then ck[179]=cm(cn,12,33);by=448 else ck[146]=cm(cc,21,29);by=492 end end end else if by<=186 then if by<=125 then if by<120 then by=125 cb,cc,ck,cn=nil else ck={{},nil}by=150 end else if by<177 then ck[98]=bw();by=186 else by=210 ck[119]={};end end else if by>=252 then if by>=270 then if by>274 then by=347 ck[182]=cb else by=298 do cb=cm(cc,1,2)end end else cn=be()by=270 end else if by<223 then by=230 while(bw()==1)do for bt=1,bw()do ck[119][bt]={bw()==0,be()}end break end else cc=be()by=252 end end end end end end bi=321 else bi=283 bk[87]=bj;end else if bi<359 then bi=365 bk[12]=bo;else bi=402 do bu=be()end end end else if bi>=437 then if bi>=455 then if bi<478 then bi=481 do return bk;end else bh=52;end else bi=455 bk[130]=bm end else if bi>405 then bi=437 do for bh=1,bu do local bj,bk,bo,bt=84,38,75,90,40,68,98,21,98,54,59,97,49 while bj~=37 do if bk>=154 then if bk>=198 then if bk<217 then bk=226 do bm[bh]=bo;end else bj=37;end else bk=198 if(2==bt)then bo=(not(bw()==0));elseif(1==bt)then bo=bc();elseif(h==bt)then bo=bv();elseif(0==bt)then bo=z[bv()];end;end else if bk<=38 then bk=87 bo,bt=nil else if bk<134 then bk=136 bt=bw()else bk=154 bo=nil end end end end end end else bm={}bi=418 end end end end end end end else if ba<=1438 then cg=function(h,z,bh,bi)local bi,bj,bk,bm,bo do bk=h[12]end bo=h[192]bj=h[87]bi=h[130]bm=ca return function(...)local h,bm,bt,bu,bx,by,cb,cc,ck h=1 cb=-1 do cc=-1 end do bx={}end bm={...}ck=(bq('#',...)-1)bu={}bt={}do for cc=0,ck do if(not(cc<bo))then do bx[(cc-bo)]=bm[(cc+1)];end else bt[cc]=bm[(cc+1)];end;end;end by=(ck-bo+1)while true do local by,cc,cn,co,cp,cq,cr,cs,ct,cu cu=bk[h]do cr=cu[79]end cc=cu[98]cn=cu[s]ct=cu[171]cp=cu[146]do co=cu[93]end cs=cu[126]cq=cu[179]by=cu[187]if not(cr>44)then if not(cr>21)then do if not(cr<11)then if not(cr>15)then if not(cr<13)then if not(cr>13)then local s,cc,cv cv=cn s=bt[cv]cc=bt[(cv+j)]if((cc>0))then if((s>bt[cv+1]))then h=cq;else bt[(cv+3)]=s;end elseif((s<bt[cv+1]))then h=cq;else do bt[(cv+3)]=s;end end else do if(cr<15)then local j j=bt[cs][co]bt[cu[126]][co]=(j..bt[cp]);else local j,s,cc,cv s=cu[41]cv,j=cd(bt[s](ch(bt,(s+1),cq)))cb=(j+s-d)cc=0 for d=s,cb do cc=(cc+1);bt[d]=cv[cc];end;end end end else if(cr>11)then h=cu[179];else if(bt[cu[146]]==bt[cn])then do h=cq;end end;end end else if not(cr<19)then if not(cr<20)then do if(cr>20)then do bt[cu[41]]=(not(cq==0));end h=(h+e);else bt[cn]=bt[cq]end end else local d d=cn bt[d](ch(bt,(d+1),cq))end else if not(cr>16)then local d,e e=cq d=bt[e]for j=(e+1),cp do d=(d..bt[j]);end;bt[cu[41]]=d;else if(cr<18)then local d d=cn bt[d]=bt[d](ch(bt,d+1,cq));else if((bi[cn]<bt[cp]))then do h=cu[179];end end;end end end end else if not(cr<5)then if not(cr>7)then if not(cr>5)then bt[cn][bi[cq]]=bi[cp];else do if not(cr~=6)then for d=cn,cu[179]do bt[d]=nil;end;else bt[cn]=ca[ct]end end end else if not(cr>8)then bt[cu[41]]=(bt[cq]*bi[cp]);else if(cr<10)then else do while not bt[cp]do bt[cn]=bt[cp];h=cu[179];break end end end end end else if not(cr<2)then if not(cr>2)then local d d={}if(#bu>0)then for e=1,#bu do local j j=bu[e]for e=0,#j do local s,cc,cv do s=j[e]end cv=s[1]cc=s[2]if(cv==bt and cc>=0)then d[cc]=cv[cc]s[c]=d end end end end do return true;end else do if 3==cr then local c,d c=cn d={}if(#bu>0)then for e=1,#bu do local j do j=bu[e]end for e=r,#j do local r,s,cc s=j[e]cc=s[1]r=s[2]if(cc==bt and r>=0)then d[r]=cc[r]s[1]=d end end end end return ch(bt,c,cb);else ca[cn]=ca[ct]end end end else if(cr>0)then do return bt[cn]end else local c,d c=cn d=cq do for e=c,d do bt[e]=bx[(e-c)];end;end end end end end end else if not(cr>32)then if not(cr>26)then if not(cr>23)then if 22==cu[79]then bi=ca[cn](bi)else bk[h]=bd[co];h=cq;end else if not(cr<25)then if not(cu[79]~=25)then bt[cn]=#bt[cq];else if cn then do cn=false;end cp=cq;h=(h-1);else do h=(h+cq+cp);end end end else local c,d,e,j c=cn j=((cp-1)*50)e=bt[c]d=cu[179]for r=1,d do e[(j+r)]=bt[(c+r)]end;end end else if not(cr<30)then if not(cr<31)then if(cr>31)then do ca=bt end else local c,d,e d=bj[cq]e=nil c={}e=bs({},{__index=function(j,j)local j=c[j];return j[1][j[2]];end,__newindex=function(j,j,r)local j=c[j]j[1][j[2]]=r;end;});do for j=1,cp do local r r=cu[119][j]if r[1]then c[(j-1)]={bt,r[2],nil,nil};else do c[(j-1)]={z,r[2],nil,nil,nil};end end;bu[(#bu+1)]=c;end;end bt[cn]=cg(d,e,bh);end else if(bi[cp]~=bt[cn])then h=cq;end;end else do if not(cu[79]>27)then bt={};do for c=0,ck do if(c<bo)then bt[c]=bm[(c+1)];else break end;end;end else if 28==cr then bt[cn]=z[cq];else local c,d,e e=cu[41]c={bt[e](ch(bt,e+1,cq))}d=0 for j=e,cp do do d=(d+1);end bt[j]=c[d];end end end end end end else if not(cu[79]<39)then if not(cr>41)then do if not(cr>39)then bt[cu[cn]]=bt else do if not(cr~=40)then h=((bi[cn]<bt[cu[146]])and cq or h)else do bt[cn]=bi[cq]end end end end end else do if not(cr<43)then if(cr<44)then else bt[cn]=(not(cq==0));end else bt[cn]={};end end end else if not(cr>35)then do if not(cr<34)then if(cr>34)then bt[cn]=bt[cq];else local c do c=cn end do return bt[c](ch(bt,(c+1),cq))end;end else local c,d,e d=cn c={bt[d](bt[d+1])}do e=0 end do for j=d,cp do e=(e+1);bt[j]=c[e];end end end end else if not(cu[79]>36)then local c,d do d=cn end c=bt[cu[179]]bt[(d+1)]=c;do bt[d]=c[bi[cp]];end else if(cr>37)then bt[cn]=(bt[cq]*bt[cp]);else bt[cn]=(bt[cq]-bt[cp]);end end end end end end else if not(cr<68)then if not(cu[79]>78)then if not(cr>72)then if not(cr<70)then if not(cu[79]>70)then if bt[cn]then h=cq;end;else if(cr>71)then bt[cn]=(bt[cq]/bi[cu[146]]);else do cb=cu[cu[41]];end end end else if not(cr~=68)then local c c=cn do return ch(bt,c,(c+cq))end;else end end else do if not(cr>75)then if not(cr>73)then do bt[cn]=cg(bj[cq],nil,bh);end else do if(cr>74)then do if(bt[cp]~=bt[cn])then h=cu[179];end;end else do do return bt[cs][co]end end end end end else if not(cr<77)then do if(cr>77)then local c,d d=cn c={}for e=1,#bu do local j do j=bu[e]end for e=0,#j do local r,s,bm s=j[e]do r=s[1]end bm=s[2]do if(r==bt and bm>=d)then c[bm]=r[bm];do s[1]=c;end end;end end;end;else bt[cn]=(bt[cq]%bi[cp]);end end else local c c=cu[41]bt[c](bt[(c+1)])end end end end else if not(cr>84)then if not(cr>81)then do if not(cr>79)then bt[cu[41]]=(bt[cu[179]]/bt[cu[146]]);else if(cr>80)then bt[cn]=ca[cu[171]]else bt[by]=(function()bt[cn]=cg(bj[ct],nil,bh);end)end end end else if not(cu[79]>82)then ca[cn]()else do if(cr<84)then z[cu[o]]=bt[cn];else bt[cn]=bh[bi[cq]];end end end end else if not(cr<88)then if not(cr>88)then local c do c=cu[41]end bt[c]=bt[c](ch(bt,c+1,cb));else if 89==cr then while(bt[cn]>bt[cp])do h=cq;break end else bt[cn]=nil;end end else if not(cr<86)then if(cr>86)then local c,d d=cn do c=bt[cq]end bt[(d+1)]=c;do bt[d]=c[bt[cp]];end else bt[cn][bt[cq]]=bt[cp];end elseif not bt[cn]then h=cq;end end end end else if not(cr<56)then if not(cr<62)then if not(cr>64)then if not(cu[79]<63)then if(cr<64)then ca[cu[41]]={}else bt[cn]=bh[bi[cq]][bi[cu[146]]];end else local c,d,e c=cn e=bt[(c+2)]d=(bt[c]+e)bt[c]=d;do if((e>0))then do if(not(d>bt[c+1]))then h=cq;bt[(c+3)]=d;end end elseif(not(d<bt[c+1]))then h=cq;bt[(c+3)]=d;end end end else if not(cr<66)then if(cr>66)then do bk[h]=bd[co];end do h=cq;end else bt[cu[f]]=(not bt[cq]);end else do bt[cn]=(bt[cq]%bt[cp]);end end end else if not(cr>58)then if not(cr>56)then bh=bt[cu[cn]]else if(cr<58)then do bt[cn]=(bt[cq]+bi[cp]);end else ca[cn]=bt[ct]end end else if not(cr<60)then if(cr>60)then local c,d,e do e=cu[41]end c=bt[e]d=cu[179]do for f=1,d do do c[f]=bt[(e+f)]end end;end else bt[cn]=-bt[cq];end else local c,d d,c=cd(...)for c=1,cn do bt[(c-1)]=d[c]end end end end else if not(cr<50)then if not(cr<53)then if not(cr>53)then local c,d,e,f,j c=cu[41]d=cp j=(c+2)e={bt[c](bt[c+1],bt[j])}for o=1,d do bt[(j+o)]=e[o]end f=bt[(c+3)]if f then bt[j]=f else h=cu[179];end;else if(cr<55)then bt[cu[p]]=bt[cq][bi[cp]];else while((bt[cn]<bt[cp]))do h=cu[179];break end end end else if not(cr>50)then bh[bi[cq]]=bt[cn];else if 51==cu[79]then bt[by]();else local c c=cn bt[c]=bt[c](bt[c+1]);end end end else if not(cr<47)then if not(cr<48)then if(cu[79]<49)then bt[cn]=(bt[cq]^bt[cp]);else do if(not(bt[cn]<bt[cu[146]]))then h=cu[179];end;end end else do h=((bt[cn]~=bt[cu[146]])and cq or h)end end else if(cr<46)then do bt[cn]=bt[cq][bt[cp]];end else do bt[cn]=(bt[cq]+bt[cp]);end end end end end end end h=(h+1);end;end;end ba=1484 else if ba<1521 then ba=1523 return cg(ci(bf()),{},bf())();else break end end end else if ba>=1230 then if ba>=1262 then if ba>1271 then ba=1325 do bd={}end else cd=function(...)return{...},bq('#',...)end ba=1306 end else bv=function(c,c,c,c)local c,d,e,f=79,37,69,81,79,61,57,95,23,27,45,95,79 while c~=37 do if d>=142 then if d<=142 then d=185 bz=(bz+f);else if d<200 then d=205 return e;else c=37;end end else if d<=37 then e,f=nil d=76 else if d<101 then d=110 do f=be()end else e=ce:sub(bz,(bz+f-1))d=142 end end end end end ba=1262 end else if ba<=1138 then bw=function()local c c=bl(ce,bz,bz)bz=(bz+1);return c;end ba=1171 else if ba>1175 then ba=1230 do bc=function()local c,d,e,f,h,j,o,p=90,64,11,55,89,60,11,92,43,29,82,74,25,26,96,14,95,22,97,55 while c~=43 do if d>=187 then if d>=277 then if d>=324 then if d>329 then c=43;else d=346 return(f*(2^(j-1023))*(o/bn+e))end else d=324 if not(j~=0)then if 0~=o then j=1 e=0 else return(f*0)end elseif not(j==2047)then else if 0==o then do return(f*(0/0))end else return(f*(1/0))end end end else if d>=220 then if d>229 then do e=1 end d=277 else d=262 do o=(bp(a,h,20)*4294967296+p)end end else j=bp(20,h,11)d=220 end end else if d<=91 then if d<86 then d=91 e,f,h,j,o,p=nil else p=be()d=110 end else if d<=110 then do h=be()end d=152 else if d>160 then d=187 f=((-1)^bp(31,h,1))else d=167 if((p==x and h==0))then return t end end end end end end end end else ba=1213 bg=function()local a,c do c,a=bl(ce,bz,(bz+u))end bz=(bz+2);return((a*l)+c);end end end end end else if ba<=888 then if ba<=798 then if ba<790 then cj={{0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,},{1,0,3,2,5,4,7,6,9,8,11,10,13,12,15,14,},{2,3,0,1,6,7,q,5,10,11,8,9,14,15,12,13,},{3,2,1,0,7,6,5,4,11,10,9,8,15,14,13,12,},{4,5,6,7,0,1,2,3,12,13,14,15,8,9,10,11,},{5,4,7,6,1,0,3,2,13,12,15,14,9,8,11,10,},{6,7,4,5,2,3,0,y,n,15,12,13,10,11,8,9,},{7,v,5,4,3,2,1,0,15,14,13,12,11,10,9,8,},{8,9,10,11,12,13,14,15,0,1,2,3,4,5,6,7,},{9,8,11,10,13,12,15,14,1,0,3,2,5,4,7,6,},{10,11,8,9,14,15,12,13,2,3,0,1,6,7,4,5,},{11,10,9,8,15,14,13,12,3,2,1,0,7,6,5,4,},{12,13,14,15,8,9,10,11,g,5,w,7,0,1,2,3,},{13,12,15,14,9,8,11,10,5,4,7,6,1,0,3,2,},{14,15,12,13,10,11,8,9,6,7,4,5,2,3,0,1,},{15,14,13,12,11,10,9,b,i,6,5,4,3,2,1,0,},nil}ba=798 else cf=''ba=839 end else if ba>=854 then if ba<883 then cl={[0]=1}ba=888 else br=2 ba=926 end else ba=854 do bn=(2^52)end end end else if ba<=1001 then if ba>=954 then if ba<996 then ba=1001 do bp=function(a,b,c,d,d,d)local d,e,f=56,69,54,23,64,39,93,74,31,36,38,95,46,43 while d~=38 do if e>=174 then if e<=174 then f=(f-f%1)e=219 else if e<246 then e=251 return f else d=38;end end else if e<=69 then f=nil e=108 else if e>115 then do f=((b/cl[a])%cl[c])end e=174 else e=151 do f=nil end end end end end end end else do bb=(bit_lib and bit_lib.bxor or function(a,b)a=a%(2^k)b=b%(2^32)local c,d=0,1 while a>0 and b>0 do local e,f=a%16,b%16 c=c+cj[e+1][f+m]*d a=(a-e)/16 b=(b-f)/16 d=d*16 end c=c+a*d+b*d return c end)end ba=1018 end else for a=1,31 do cl[a]=br do br=(br*2)end end ba=954 end else if ba<=1018 then ba=1048 do cm=function(a,b,c,d,d)local d d=((a/2^(b-1))%2^((c-1)-(b-1)+1))do return(d-d%1);end end end else if ba<1088 then ba=1092 bz=1 else ba=1138 be=function()local a,b,c,d c,a,d,b=bl(ce,bz,(bz+3))bz=(bz+4);return((b*16777216)+(d*65536)+(a*256)+c);end end end end end end end end end)(0,8,1,1,1,41,4,4,7,2,32,256,1,14,179,41,4,0,41,0,2,6,6,0,1)end
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Shiftlock thing by bloxy idk",
	Callback = function()
		return(function(a,b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u,v,w,x,y,z,ba,bb,bc,bd,be)local be,bf,bg,bh,bi,bj,bk,bl,bm,bn,bo,bp,bq,br,bs,bt,bu,bv,bw,bx,by,bz,ca,cb,cc,cd,ce,cf,cg,ch,ci,cj,ck,cl,cm,cn,co,cp,cq,cr,cs=125,88,56,53,23,89,71,71,24,91,34,66,39,25,27,33,13,38,33,81,46,32,86,63,83,32,44,59,58,51,46,65,88,37,59,15,17,59,84,82,55,28,52,95,97,76,59,27,25,66,45,40 while be~=77 do if bf<=659 then if bf>=401 then if bf<=482 then if bf>=434 then if bf>=462 then if bf<474 then bf=482 do ck=math.abs end else cn=math.floor bf=520 end else cr=(function(ct,cu,cu,cu,cu)if not(cf(ct)~='number')then return true else return false end end)bf=462 end else if bf<412 then bf=419 bt=select else cf=type bf=434 end end else if bf<=572 then if bf>=545 then if bf<567 then bf=572 bv=tonumber else bf=598 do cj={}end end else bf=545 cq=(unpack or table.unpack)end else if bf>=619 then if bf>621 then bf=679 do bw={{e,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,},{1,0,3,2,5,4,7,6,9,o,11,10,13,12,15,14,},{2,3,0,1,6,7,4,5,10,11,f,9,14,15,12,13,},{3,2,1,0,7,6,5,4,11,10,9,8,15,14,13,12,},{4,5,6,7,0,1,2,3,12,13,14,15,8,9,10,s,},{5,4,7,6,1,0,3,2,13,12,15,14,9,8,11,10,},{6,7,4,5,2,3,0,1,14,15,12,13,10,11,8,9,},{7,6,5,4,3,2,1,0,15,14,13,12,11,10,9,8,},{8,9,10,11,12,13,14,15,0,1,2,3,4,5,6,7,},{9,8,11,r,13,12,15,14,b,g,3,2,5,4,7,6,},{10,11,8,9,14,15,12,13,2,3,0,1,6,7,4,5,},{11,10,9,8,15,14,13,12,3,2,1,0,7,6,5,4,},{12,13,14,15,8,9,10,11,4,5,6,7,0,1,2,3,},{13,12,15,14,9,8,11,10,5,4,7,6,1,0,3,2,},{14,15,12,13,10,11,8,9,6,7,4,5,2,3,0,1,},{15,14,13,k,11,10,9,8,7,6,5,4,3,2,1,0,},nil,nil}end else ca=bz('0A00000000142870003228000000002028C000062800000000289030010D90000000003C9020003690000000004158D1040E5801000000496081020E600100000049B091040EB0010000003C78200306780000000045C880040EC800000000440000004100000000005A0100000000F600D00314400A000000450060030EC800000000213110084610000000004D00C0000EC8000000003C0020003698000000005601400014E0090000000C0020020DB8010000003C0080030610000000003C00900332780000000109000E000000000600000000080000000002000000000A0000000003000000000B000000000C000000000D000000470090005E08000000003C0010001688000000002E01E00314B0000000003500000008B8000000005400100029A000000000390060030ED0000000003D0050050EC800000000760080031408090000003C0020003698000000000C00F0005B78010000003D0000000850010000003C002000067800000000C200300414B8010000010100020000003F0010005E10000000004000A003323800000000490030050ED8010000000201000514300A000000240070003248000000002D0010000E6800000000240020003658000000004601900414400900590094A01002242001005A000418700041B80000180040B070005E9000001B0018C06000251801001C00719860013A2801000B0064A810015A0800005C0004A870011B0801000E008C788001012000002C008008D000212801002E002C18A0015D1800001F0074D070011EF0000062007278A0000C98000000005201C003144005000000280050010DA0000000002D0070010EB0000000003100000008B80000000030002000066000000000350050050EC0000000001200A00214B803000000410070030E3001000000F148F009469001000000490010040EC8000000003C0020003690000000000C00F0005B18010000009200C0021430000000004100B0040E6001000000450090010EC8000000004900E0020E60010000004D0080010EC8000000003C002000369800000000260160051440020000004100E0040EB001000000450000020EC8000000000139000846F8010000004D0030060EC800000000DA00C003148800000000450030000E60010000003C0020003688000000000C00F0005B68010000003D00000008F800000000BC4030034630020000007600C0021498020000000C00F0005B48010000003D0000000870010000003C0020000678000000004100C0040E60010000001A0130021410020000003C0020003688000000000800F0005B68010000003D0000000850010000003C002000067800000000410050050E80010000004201E00414E0070000003C0030030678000000000C00F0005B90010000003C00B00037B0000000003D0000000820010000003C00500206780000000056011004148801001F008C38400016B0000014006468C0010440000053004038D0001DB8000013002C0860003588000005001008F0005E3800001E00981800010208000038008C0071012020010009005648100151D000000E00383890000658000037004410D10137F8000015008000C1012DD8000000000600200614E0090010001CE870003D500000200064B8F000633001004B0098E820013E6000005E008C2850001640000057001C6090000AB000002B0014686000443000003C000C3000010B5000004E004C0011000F500000310080C010002F5800005F008C305000083800004500902061010F48000039004C3841014E3800002E00542850010D60000000001A01900414C80800000019000000083000000000180070003230000000002100A0050E50000000004601300314A806000000390080010EC8000000003D0010000EC80000000030002000367800000000520190001460000000003C0020010650000000000C00F0005BA0010000003D0000000850010000003C002000067800000000A600100514E80100000009000000080800000000080020000610000000000D00E0030E2000000000080020004C10000000000D0000000808000000001E01E0001488060000003D00000008F8000000003C00E0010678000000003C0000020678000000000400F0005BF000000000040020020D0801000000080010005BE8000000006E00900314D8050018009922100425C805004400888184002F6002005B000EBA920351A0010000000E0180031480060044006048E00035F8000017009028A1001D7000005A004D402000638800004100746010005288000059002C68C0005740000056003538C1011B50000047008020B1013F88000005008C3050025E1001004800643820010FA000001C005C10700012680000400074F0600221B800000000720140021430040000000000000035180000000044001000600000000000F850900B46F804000000470010003360070000004A01300314100A000000550040040E5801000000590070030EC8000000005D00C0000E60010000006100D0000EC8000000005000000040C0000000000600400514F004000000080080020D38010000003D0000000850010000003C002000067800000000D529B0084658050000002601600514080000420020D050005CF8000026003C5830010238010023007110C000046000003B005CA01001074800005A009C28B10019D000004500803061005B4800004A005C302100343800003B0054B8100061B000003E000C38E0001E100000610018B8E00155F00000340095C8300105D00000330050B8900059C800000E0070F040015348000000007200900014E8040000003D0000000820010000003C0050020678000000004100B0010E30010000003E00700414E0080000000800F0005B78010000003D00000008F8000000003C0020030678000000003C0030030678000000001200800214A00A0024002CB850010CB000000D00747820024C9000004D005480F001121800001D008C8860004258000010008DC8D00004C0000060008CB8D00037100100210014B0B0015F50000048009060F00133E8000030002C784002376000001C0024A040015B20010008006C40A0010B7000000000BE00A0031408000000007201200114980A0000000C0020000618000000001100D0050E28000000000C0020004C10000000009600E00414E806000000180020003640000000001D000000083000000000500020014300000000001A00C00014700A000000500000000900000000005500F0010E80000000004000200036A8000000000A01A00514080800000011000000083000000000100070003220000000001900E0010E40000000007600B000143008002D009848C00027A000000D0064500001064800005200741060021AA800003E004C68900008200100210065C020013D90000026004028110256D800004F009C38810111C0000041001048D00108E80000590010C0A000179800004C00481050001418010000002201E00214400A000000440020005880000000006200200214980A002C0094B0D0005710010048007C2800023EB00000140044C060001F5000004300281840011178000061002C9040025B28010049003C38000128380000340088D0200136E80000330074D8B0004110010056008080900156600000150040F850011AD00000170040A85001175800004400788860013F700000090084A0600123B00000000036004003143000000000450010000EC800000000490020060E88010000004D0020010EC8000000003C0020003698000000001600200614F8050000004400C0033238000000004D0000020ED801000000510000000850010000005000200006A0000000008A0180001410050000001000200036300000000015000000083000000000DC08F0014640080000001D0000030E4800000000140020003638000000007601C0031498030010008EC0C00155A0000012004C60000131F000000800800800011AF800001800083861012538000061003028510001B8000050000C50100050A000001F00585000021AD800000C00701011002F280100050050E8500103E80000090051186000569000003D0034A0D0013160000010006C8820023DA000000000EA007005146802000600B428A10A281005002500846281031860000000005E00900014300A000000450020040E3001000000490060020E30010000000423E00646F0080000000800F0005B180100000072001004144005000000410050000EC800000000340020003680000000003800F0016298010000000400C0010DD800000000040040005BE8000000003A01500414300400000004000000512000000000280040004100000000002800F0000D7000000000280010010D80000000006818B0064658090000001A013001145801003F0094680001471800000900744820021E9800003600083880005CD0000011000C20610229700000610024F87001029000004F007450400155E000002E0034E8700239000100120034C0900023280000210060A030015EE8000037009040A0000420000025004CF0D000489800002E002E40400156C000001E0034C8C0016308000047005488000211B800000000D20060051408070000000800F0005B48010000003D0000000870010000003C0020000678000000004100B0030EC8000000004500B0050E6001000000CA00600514680200000042011005148006000D00252AC6044F78000026005809B10B449001004200A0BA920A45A8000000004C00F0025878000000008600B00514C8060000000100000020000000000005000000080800000000040020000608000000000900C0030E1800000000040020004C10000000006200F003140004000000250010040E58000000001C002000364800000000E810200546800A000000250000000830000000001201A00214D000000000440000000110000000000800F0005B90010000003C00E0000650000000000800F0005BA0010000000C0050030DD8000000000C0010005BE800000000B200100314D80300030000000500000000192000000820000000002D8000000880000000004D9850040E98000000003CA0600156A0000000006198A0000E9800000001E600000000007200C003141804002500388850004D8000000F00543870000B40010043009D80D000183001005E00B8285102495800003200646840011BB0000041007CD0C0005C4800003400A13060014148010005006C6801025178010007006CC880025D680000100078B010022368000012003070C1011A68000034000C50E101591000000D008C68210050D00000350084A030023B00010000006601800114C0030000003C000000410000000000410070030E9000000000450060010E9800000000480000004A00000000000A00300314D000000000090000000818000000000C007000580000000000080020004C10000000000B0040000588040000002200E0041420020000000D6B400546D000000000EA0050051418030029005018300210E0000061005008D1010ED000004500581090026268000018006820F101359800004B009080D00231380000170018C8400126A8000049005C104101360801004B00A8085102554000001E004830F1024D18000012003CF0000214D800000800586070013EE0000014007C10E100138000000000AE00F0031480000000005A00F0FF03B8040000001201B0051488060000006C0020003800000000005400B00104D0000000004E005001144801000000215AD0034670010000001800A0000630000000001D0000000820000000001C00B0000638000000002100000008600000000042002004144806000000250000002000000000006A00D00114580400430020C870001C28010025006878400241900000460076E8D002217800005B00B420D001199800002600B8F89001387801000F000828F00032E000003900847080002EC0000028006C30C1001748010014002848C0025A800000220010B060012AF8000048005830C1012560010000007600D0031408000000004600F0FF039002000000AA0020011420060000005A00F0001498030028004C60610242500100290070A0E0021400010016002C2060000BD00000410030284000491800000B00BC08000256C8000039004C18A100414800003C0010F800025660010026005C1811025B88000013008C4811015E1801005D001438F100254000005F00A07050004F6001003000A820A10234100000000092003002146806000000550080010EA000000000590000000818000000005C004001530000000000580020004C10000000005B00500005300600000012004005147804000000590050050E98000000005C0040015300000000005C0000004AB8000000008D7AB00A46D8020000007601100614A0050000007400D000581000000000780040015300000000007C00700358C8000000004A01D001147805004A00E008810722E801005100219212042560050000004600F0FF2E1002000000CA0000011490020000007E006005145804001A0090F020023690000023002430D100087801004C00BCA0C000397001003900AC58E102283800001E009C58100040100100260060D0C0010BE000005B003E98A0004128000041005CD050014F1801000F0034B8C00041600000350090C8F000405800005500683090012690000033006D78C1003120000000007600A00214E80200000009000000082800000000080060000610000000000D0000000828000000000C007000061800000000BE00300114D804005F0090B0E001355000005500B000610151D8000037006040900249100100110088384102577801001E001430B0004C0800003D000AE8E0010C3800005B00BC4841002860010018000C78E1021F900000410090A0A001310001002D0071E8A0025390000000001A0070031438040000000500B0000E0800000000080020000600000000000B0010003370050000001601F003142807001B0028E0E403520805000000350000002010000000003900B0010E88000000004E005002148000000000290000000878000000005561500C466004000000310000002008000000009A00C0011498040000005200600214C002005E0088A0A50259480500000008000001626801000000080000000110000000000A0000021440040000006A01400114880400000000000000350800000000040000005108000000006800A00458A8000000006C00E00358180000000070005004586000000000B200D00214E80200000011000000082800000000100080000620000000001500000008280000000014009000062800000000E200D0031470010034003430C10236C800003700108870011620010048002040F0022530010023008C28B1021120000016009C9090020F1800004D002CA0F0012968010031005910110019F000002B00BCA81001453800000E009078A001462000002500B8607102447000000B00AC1031014B3001006200985851014988000016006040D00008A00000000082008003145804000000000000000110000000008000400058C80000000074002000360001000000780090055870000000007000000040F0000000007E0110031458010000005A00F0FF2E48010000007601A00414B804004A00603000020D40000036009C0821000A48010053000450610207E000005C004C70F1010D0001002900A0F8100062B0000058008460C10229E800001200686890004B68010026009C78610133680000360042F880014040010049005830B10152D80000060078C0800214A80000610014E0F0000D20000052006C5031026358000000003E0140031480040000003C0050010D10000000003C000000011000000000580040015300000000005470000C4638060000008A0080051410020000002000D000064000000000250000000870000000002700000048A00100000042005002142803003F00CC22A0040E6800002A003490220A1AF001002D00C4422005078801000000620120011470050000003C00500156A00000000082012006141002002C008460F0016058000019009018910158D000005D006960F10057D0000048005038A1023D500100300078B8E0022AA000006200343881001B10010009005570B00062D000003E006078E0002668000054003C7881012D9800002300A02020013F700000530040C8400216D0000057001C680102091800000E00786890013FD000003800704030022C0801003A002C50F001523801003B00346051021038000000002E00600314B0040000003201C0021470050000003200600114A800000300000000000000009300000000007600000614380300000004000000510800001E003C78A0000A1800001B00405010000C68000026003028A0001C70000039001468E000556800000C000850D0000450000031002840A0000F58000038003C78300045600000490024781000277800004D000458F000412800003C0014409000432000005E0010805000196000005A004028B0002D3000003100041090005C5000000000DE00200414E00100560024304000303000003E003C3850005E2000003C003C581000096800003700186830001D4800004E000470D0004A5000002100242010003740000045003018E000504800001800046870003F380000230028801000565000001A00406020004A80000055001C38C0004B0800004D00381050004E2800003A00347830001E2800001B001538B0002A78000000004200A0031470010015003C20D0002018000022004230C000201000002C0008587000504800001400202800010C0800003F0030581000071800000A002408A000462800001D001458B000494800000A0014388000550800002A002440A0000F50000032001C4800013558000008003C3030003070000009002460A0000928000036000478A000074800001F00101000015A28000000001601200114E001004A003440E0000F680000160026302000603800000600262810001D4800002A001408B0002B58000021002038E000577800001600282810002948000011001010A00042580000290040605000071800003A000C0850001958000063003C20D0004710000058000848E0004B4000004C003C203000392000001A0024087000078000000000C200A00314F8000056001C7870004510000044002868D0000A1800000F0015808000284000004C000C3890000448000050001E4050003670000054004078C00017480000240028201000355800004E0008808000541000001C00382020004778000056003C38D0003C8000000F003008B0005020000025002468C000285000005D000C7000015D28000000003E01E0021470010013003060E0004948000039000880F000216800003E003020C0005F58000050002840E000161000004A0009100001293800003700092830003C180000340014606000276800005F002040F0005F1800006300325060004F10000040003470B0005648000014001C48D000463000000000DE00100014E001003C0040682000190800004D002070C00013380000120008288000391800003200083020005C4000002E0008405000020800001E0024502000602800001A000C288000382000003D001A602000287800001B003040B000633800005200180860001C400000600004382000525000001B0028308000026800003E00386850005218000044003C4870000970000005000C6840006048000000000A010004141804000000000000003520000000000100000008080000000000000000011000004200346810004E080000420014301000271000004F000C387000291000003B000838E0002A68000015002C5080003E200000060030205000475800004E004078D0001A20000018001048C000425800006000403020002658000018003810A0005F5800005B0024082000466000005D000C5000014B58000031000408D000331800000000DA009005141000000A00242090004870000053001060700018680000300010303000511800004000184800016020000017003868F000178000003B00405890001D7000003C00403810004850000016003848A0001E38000010003818D00060680000080038780001474000002C003D18B0004780000000001E01A0021418040047001C2020003C8000003100340810001D70000057000810D000338000001D003020D0004D78000012000C5820000350000057001C68200042680000610034389000183000000F00086830000630000020002C185000282800005D000C600001451800001700042030002468000061003558B0000C10000035000C7820003B38000020000C20C0003E0800005200258070003F28000000006E00E00414F80000000000000100000002040000005F454E560300000000140830003108000000000C1820003B1800000000081030004B1000000002A10000000000D20030031440030023003C19340A26D800000000130050002540020000009600700314500200510010309000487800005400408830010730000048003C4040001D1800003A002C4810003B68000026002C90B000394800004E00083030002B88000050000828100109500000570010A04000489000005F0054A0100051A8000053004248E0000420000000009200F004140802003B0004801001382000001B003CA080003F90000028003030E0005E9800003B00507050001A5800004700249830011BA800001B00341820001A4000001E003C6030012098000040002010B0004A48000018000C6830014A980000460019284000045000002200082070001A5800002A003C7810010F2000004400186010001768000000005600E0021488040000001201A0031410020000000300100015C802000000CE00200214E8000000007200300014E8010000000B0000000BF0010000009200D00214F003005E000983F40B1438000000000601900314E801002B00D08AA00A363001001900FCC9E10B6190030019009479C3000FF0030000006E0110041418010005001C68200019A80000320040801000486000002600282040000E9800005C001C707000069800003D00145810003810000046003840200123700000230034A840010E7000002F00049030000DA00000600054A870002D6000001000485820011A280000490054282001222000005D002490900051A00000340020885001158800004000243820000D48000000002A007003140001000000100030003100000000000481400246C8010000000E01D0051410000000000600500314F0000000007200E0021410020000000C0000000110000000000B0010000BC0010000005201C00514D80100000000000000351000005400482960001018010000000B0000000B6003000000A200F00514580300000018004000020000000000000030005C3000000000180050000208000000001201600314E0040000007888C0024640020000007A005000142002000000B600C002142002003E003C183001305800005A0054382001312800003A003430F0003A500000330034681000496000000500287840000F3000004500366010014B40000034001CA870004E2800002A00107830003228000029003830F000468800003A003C581000593800006300387810011F800000440014304000383000006200386000015040000000001E00100214C0010000000000B0015808000000006201B00214100200060034903001035800002E00087830010318000007003460500132480000520008209000206800002400316840001A580000230005A0D000349800002C0024580001602800004600241820010F9000004B004C88D0003F28000009003018B0003C2800000F003C680001496000006300281000010710000000001E015002140800000000100060005F30000000000D0020010E10000000003E011001140801000000EE00F00314E801000000100030003100000000000B0040000B18040000004601B00214280400000096009001140005001E003C4070002530000046003470B0004460000028001420D000552000003F0054102000376000002B00404020006208000018002C5030013458000035002810E0004990000016004010B0004F080000580044A820014830000029001CA0C0004A78000050004820300056A80000480048502001392000005400144840000860000000003E00F000140801000000F600700214F00000000014004000020000000000000030005C2800000000080030004B10000000009600600214E0010000000C0020003B18000000007600800214F8030000000E00500414F8030010002460A000619000001F0048080001533800003400541810003170000038004D1050000E580000150054A090002C8800003E0030283001198000000B001C108000498800003C004068E0004660000041002C901001342000000600381010016018000000007201F00114C001002900344030004828000031001848F0003B400000330004384001546000003B001C70D000132800005D00487060004A4800000A005120D0004B58000016003C90E0000F100000090004605001275800004E00087890001B4000005F000C10C0001920000000002E00300414E801000000040030005C3000000000BC92400A46E804000000EA00300314080100360080C252052BC8040000000400000051080000000000000300000001000000000000F03F01000000000000000001000000000000004000000000028000000000001601F001145801000E0018781001436000001D003468600018680000460016108000350800001800181010000B2800004F0034305000556800000E001C38F0005F300000190034783000321000004200248010003A600000160028708000510800005000100890003960000011000820F000058000001800087010014628000000003A00A00314280200230018180001452000004F0034589000593800004700382060004D80000063000C6050000E1000005C002C608000333000005B0020308000116800001A00146030001B6000000A00346080005D3800001C0044608000336800001500343040005780000000007E00E002140800004F008431630539A004003900D6B162054BC8020000000601600514F0010010003578D0003E700000510030182000420800003500100820002030000040003C786000295800003600266080000410000021002838E000146800005A002C6840000C4800003A003940A0005348000018000438100145880000240014185000596800001A001428E00025100000110038380001065800001D001C2020001980000033002C20D000605000000000D200100514C800000000080000004A0000000000080010004F1000000000000010005610000000007A01E0041400020026001421440C5AC0000000006A01B004148803003700248820000678000021004028E0000348000007000418F0002E7000004A0020886000628000005A003C1850003E60000031002458E0003B4800001F00445860004F70000022003C20600008780000280010081001457000001300200880004F7000003D003C7070000F5000000E002480E0004C7000003900124050000D0800002E009C40F20A2D2006001B0020F8F00538380300000000000000350800001B007C0A300601D8000009001050850A2DF0010043006878710333A8050000007E00B0021478010053003030D0002D6800002D000828700028600000150039686000481800002E001418800057700000420018302000367000004A0026807000335800001500404020000E5000005E00405000013B6800002D00108030000A7000001400240830001260000034003E48D00025680000000016015003148803005400250860000A70000047001C10A0000658000012000C10800027700000150008806000301800004600460810010420000005002168E0005928000051001030F0000B1000005B001C482000394800003D00244050004C7800003900201080004D5000002E0028602000526000003B00444860003E4800000F00248810012F780000410019202000051000002C00306860006120000000005A01E0041408000000000E00D0011488030044006079C30522B8040043000C93D4051360050028002CA2D5004C2003000000AE005001140002003200080800011B5000003B0004083000575800000F00342810013F40000035001C3070005C5800005C0015381001577800002300380860004E2800005D0004681001607000003D0028700001202000000C001C50A0005D4000001C00305810011B8800000000E600A00414E000000000040000005110000052003C806000518000004A00140860004A3000001E000418F0004B7000000B001C089000443000002D000C5880003068000017002C4020004A7000006300047890000B18000015003050D0000258000034001860700016600000510044305000438800000E003008A0002780000036004430B000056800000A00083050004620000000002200200414700000000000000100000001000000000000F03F1500000002180000004A46535F505249564154455F584F525F46554E4354494F4E01000000000000F0BF02040000007479706502050000007461626C650206000000737472696E6702040000006279746502040000006368617202030000007375620204000000677375620206000000636F6E6361740206000000696E7365727402040000006D61746802050000006C64657870020700000067657466656E76020C0000007365746D6574617461626C65020600000073656C656374010000000000002E4001000000000000000001000000000000F03F02000000000301010000000000102000361000000000F500000000004A01B00214A004000F002888F000502000000C002D38D0005740000020000C18C000457000004A000C8000012F7800003D003C80E0002E2800003100088070005C68000048002488B000380800002100104040001C8000005100412010015E6800005000047890005D68000038002C6010001628000012003648B0003D8800000000BA004000145803000000040000005108000000000000200036100000000000000000300000000000C600E00114C00000000001000000087800000001010100000000070010005E0800000000000010002D10000000009A00100614C000005700729824000EA000000000B200D005149004000000000000003520000000007A00E00414A8020062002C7030001D7000004600382800013F5000002F0044606000362800002700087070001C6000000B0028206000168000001600142860005608000037001920D0001B4800000500385830003E1800004C00308890002770000009001C60F000043800003D001C38F0003468000000007601A001141807004900088020003130000060003A8800013478000034002C3860002C1000000F000450B00004200000180018889000484800005800123840004F3800003E00092060001F2000000D00254880005D60000010001E682000604000005B002C20F0004F40000028003A20F000351000003B001420E0005E88000006002C2860005078000048001870A0003110000000001A0070031428030000000000B000060000000000050000000850000000000400B0000608000000000400C0000608000000001601F00114B806002000096860002F700000530038409000246000000600386060002E4000001E00282060004B6800003400145840003E7000001700442820003D28000047002028E0005368000039003860B0003F20000014001C40B000224000001A0008405000240800005B0018789000107800006300042850004180000000005A00F00014C8030043008878D20248C8020000008A01600014C803000000000000002108000000000000100006000000000000002000320000000001060102000000010300000001040000000105000000010600000001070000000B0060005E000000000026005002147800003A0064222600522801005D00B462310B07F000005A00180B13034840040000003E01500314B000003A0028A0040A4B8800000000C6009000142806002B0098D8B1033A38060000000300100033E0030000005A01E000141806002500043800015B2000003A000838C0005A70000011002C38D0004B10000006003488C000274800002B00188810012548000019004040B0002C7000005C00103070003A2800002F0010608000241800005D000858900058180000590018300001286800004D002438C0004838000044004480C0002B40000000007E00A001141807000000AE003006142803000000000000002118000000000400000021200000000004009000060800000000000010005B4000000000010000000850000000001A01200214A8010060000C6820000860000031002228B0005C6800002E002C1080004F7800004700242800014010000034002888B0004D2800001E00282890005F1000001300408070000F3800000500188830003A88000052001C6840004E580000420020203000435800004900305070001C4000002F0030606000577000004900142830003B48000000007A01D00114B00000000000000000211000000000000030000600000000005200900114A8020000000000000021100000000000003000060000000000000040003200000000000900B0040E2800000000E099C00B4600040000003E00D00114A80600200040605000245000001B002E18900062180000350028680001103000004A001C801001047800001700082000014478000030002038C0001788000021002430B000443800003A0046880001573800003600105830005808000037004468F0001D1800005D0014384000478000000B002030E0002A3000002E00243880002218000051002878F0005F3000005A00188890004F30000000006A01E00114A0040000000300100033F0060000007201C00014200300000000000000210000000000030000004848020000007A01D002142006002900F4F8D001539800000E00B8C8D40946300400110048A814041C90020045000C181001141000003D003888B0004C8000000B003410C0003A5000005C00084810002070000039003C40B000423800003A00407880001C6800003900385890000258000010002420A0006320000063003C5840001348000060000480100025200000100041601000304000001200342870005950000000003A01300114E0030052003820300020800000370018605000533000004E003C6070000C1800004B000468F0006338000015002440F0004A1800005C001C88F00055680000120005609000078800002D001478B000411800000B001C102000543800002800084010004F3000002C00188010004C680000530008609000345800002E002E0870002B20000011002018F0001510000015004088A0000660000028003010B000496800001C002450B0003F6800004900086810012D7000003F0018304000056000004B0020386000466800001A000C68D000392000001600443840000840000062000C28E000316800002E0010281000127800002900082800013438000000005A00C00214A004001F00A40262063A3801005D00B45235015A18010000008200F0051428030000009200C00214C8030031004C3906041D980000250018CA240B294002001A00A000A1070FA802000000CE00300114C8000042003850F0006180000050003020B0000A1800003F00110880004C0800000E002D404000117800004F00205060004F70000030001440A000416800005300088040004928000033000A2800011758000022002E109000530800001C00100840000B1800004E000C30B0006270000000005A00200314B8020000007600B005149004004500388931035F30060000000800000021400000000004002000450800000000000010005B6000000000000000002128000000000000E0000D6800000000820030021490000000006200200114C803000000000000002110000000000000300006000000000000005000060000000000000070000D30000000002601200414280300330018703000433800004700082860004C58000021004048D0005B7000005F0004787000198000001E0038600001345800000A00306810015C8000005E003C60F0001718000051000620A0005880000036001C40C000052000002500287090000A5000004B002838B000230800005700344060005A08000030003170A000314000005F0028506000481800001E00442080004B7800002D002850E0005A68000053003C50E0002E30000000000E01200614E80600020000000D0000000000001000060000000000000030000600000000000D70000008700000000010205000452000000000142810000628000000001428D0000628000000000C300000403000000000017800000878000000000000000106000000000009780000087800000000081050010610000000001020800106200000000004202000362000000000FA00000000005E0190051418020000000C00C00006180000000011000000087800000000100000010620000000008600F00414D00600160050582001198800005C004478D0002A88000013004480D0000D48000029000C2800010F8000001500501060001E08000056001420500016600000520021A040012C68000024004420400159A800000D0038B0C00031A80000290040A0500005780000130039A8B0004220000000008600100514C805004B0020DAE5082FF0010000002E00700014100200610010A8C0003C70000042002C580001180800001F0054B0A000568800004D00543870005A980000130038900001454800002000468060012CA8000058001088500139800000340048A8B000400800002A002C88000146800000290024A0A0004CA800000000C200500314C8060055000CB95009174002003C00C8D1900524F8020000000600100514A001000000000010000600000000000000400006000000000005000000085800000000FA00100014D80400140054204001535000001E003C5810012808000014004018600061A8000023003CA0A00019A0000039004C706000142800000B001C703001510800001B00405030003E48000027001C6000015A280000170054A0000105280000500040608000417800002C005848100058080000260038A820001D40000043002C2850002D18000034001898C000593000000000DE00B00514A80200540018308407153805005D0040D8D2052198000000001A00000114D005000000D0C1200A46B801000000140040000628000000009CC9500746C80100000014003001062800000000190000000878000000001800000106300000000086004005148007000000000000002118000000000000A0000D4800000000000000002100000000009A0010001408010000000000000035200000000000000000210000000000000010000600000000000300100033B0020000001200E00514C8050000007E00000414B002000000100000010620000000001000B00006200000000020F8500A4650020000005802510C46580200000008000000212800000000040020004508000000007200800114400500000004002000450800000000000010005B58000000000100000008780000000000000001060000000000050000000858000000008200300514A807000000040000005120000000000000000021000000000000001000060000000000000020003200000000000900F0020E1800000000000020003610000000000300100033D0050000003E01500014C80600000000002000361000000000030010003310050000002E00F00214A0070000000400000021100000000018001000191800000000000010005B38000000007601700514F0010027003D90D00254580100200010A3630C2D2806004B005CB085020F1800002900BDF252003948030000001C000000212000000000CE0000061450030000001800700045300000000038D2200146580300000004002000380000000000000010005B580000000035D83000467003000000E8E2400A46780300000082019002145807005C005A9880001A5000002C0048A85000439800001300545060003D6000005D004168500027180000550058700001042800004D004868F000566000001A004020400038280000190020808000582800000B004C2050001638000017002050E00011A800005A0014A8B0005A68000044002878E0000DA800000800580850000380000000006600700514F8060000000800D0000610000000000D0000000878000000000C0000010618000000000C00B0000618000000000C0070010618000000001100000008780000000056010001144002002C008D3A06094718040013001CCB400619C8010000001400000021200000000068B8000446480400000014000000210000000000CE00500214B8010026002C408000582000002C00187070000A1800001100385000013528000005004D389000194800003E0038886001045800005200102820002070000056005428700018880000370018686000445800002A004C90A000201800006200587860014328000015001C9010002D10000000002E00900514880300430020F85309182806004700E088F2030B00050000007E00500114B0020000000400C0000608000000000800000021000000000008001000061000000000080040000610000000000800D00006100000000089B260034600050000001601300114080000000000000000210000000000C4A05005461805000000C0AAE007462005000000000060000D28000000000000000021080000000066009005140003000000000010005BA8000000001E005005141002003C001C90A0003718000016000C8860003F800000190032A83001385000002700347890004918000041002C203001544800004C000498D0005968000020005868200059A0000035005460C00050A00000230050B040000850000062004C204001613800001D001C804000620800002100544020000B3000000900122830012A5800004B004C2020003F6000000000220030011460040000009200A0021490000000000000000021000000000000001000060000000000000020003200000000000900F0050E2000000000D200100414E802004D0040786000591000000B0004909000511800002C00141040001448000028004C7820003A8800002400501060013D3800002500308880002BB000002B0038305000291000002300507000011698000030005090300033A8000055001490E0005CB0000000000A017004143802003200248050010D4800004E001C5040012388000022004E384001421000001700441040002D88000026002C881001276800004E0034A050014298000061002C782000107000000C0034A850015F9000005A0008581000139000002C000C2850003EB000000C003920B000436800002D0050A8B0002A3000003F00389870003718000014000C7040014D8000000000860140021408000000008A0030061410020000001000B00006200000000010001001062000000000100020010620000000007200B0041440040000006E01700414D0050040002C986000443000001E003CA8900054580000210024885001072000000F001C403001372000002B00349850011638000025003C6860004F6000005500046820012BB00000110040788000277800003A002070600013B000005F002448700060A0000038001148B0005160000000005600F00414F00100000005000000087800000000040000010608000000000400B000060800000000080000002128000000009A0060041478020000001800B00006300000000018001001063000000000180040010630000000007600F00314400300000062000003141002000000040060010608000000008DE8D00346B0070000000800000106100000000058F1E00A46C0070000007E00300514F8030000000000180000000209000000436861726163746572020E00000046696E6446697273744368696C64020800000048756D616E6F6964021000000048756D616E6F6964526F6F7450617274020A0000004175746F526F7461746503000205000000496D61676502020000004F6E020700000056697369626C6503010206000000434672616D6502030000006E65770208000000506F736974696F6E0207000000566563746F72330209000000776F726B7370616365020D00000043757272656E7443616D657261020A0000004C6F6F6B566563746F7202010000005802010000005902010000005A0205000000466F637573020A00000066726F6D4D6174726978020B0000005269676874566563746F7202080000005570566563746F7200000000007E0000000000D200600314480100210038688000576000000C002450B0000A30000049002068100038180000590020489000580800001B002C10300053680000390030188000391800005F00383080003E3000003400142860002D48000037002C70B0000C8000003100243860000A280000120012508000427000005A00345840001660000000006A007005140800005100106870004B3800002F002868F0000D4800002F001D4880002510000014002C10D0000B5800005F003820D0000618000039000C2840001768000050001C6840000A7000003400202060002180000007002C18D0005530000058003C70B000403800000E001C1090003C08000047001C4060002240000000000A00B0041470010058001880A0000838000026000418B0001C8000005A001028F000155000005A0018189000387000000D001480C000061000002C003870C0001C700000630015804000294000002C003C08400033800000560038709000447000001A003C4890005D7800002000406810000A5800003E002C4000013B08000018001410E0005B08000000009A00F0051470000000000000000021000000000000001000320000000000000010002D10000000000000C0056290020000001601000614E001003F00201830000D800000470029205000164800004C0040189000515000003F00381040000C500000190035081000347800003400183850000470000043003C6850000670000033003C80B0003A4800004B002480F0005C700000550020189000114000003D003678A000393000001A00364060000D700000280008385000614000000000FA0070051408000000000000000030000000000000000000351000002E0010809000077000006200141040004D80000017002E4840005608000058002478D0003A3000003A003018700031200000600040288000633000004C00202080003228000032000408F000226000002B002C60D0000620000023000C58F000337000002F001070A0006168000061002448A000503800004F000C28F000583000005F000C30F0005B40000000004E0040031470000045002550D0004B4800004F001410F000357000005A00343090002330000050001118E00042380000390010780001257000003A002C7880001148000054001040D0001C4800004F002040D000584000000D000868F0003F3000001F002150B0000860000000007601600414F0010012001030F000476800004A001428B000516000000D000C4840003780000021003070D0005A780000190014402000426800004100047830002928000022001060F000341000004B00340890004618000040002C2870002150000007003058A0001038000033003018B00014800000320010603000450800000000C6004004140800005200287050004560000035000C282000022000005F00046030003C48000031004050100036180000390030601000421800001B0038387000303000003D002C1820003710000035003040B000216000005E002C500001527000003E0020109000535800004400146050004738000000007A011000148803000000040000005108000045000A101000025800002300183830005D20000046003878E0000950000052001870D000260800005D00186010000868000056001C38C0000C5000004200405090004F40000007000C60F000236800005A004070D000532000006200107890004F4000000F0018100001227800000000B200A000140800000000000001000000020A000000446973636F6E6E6563740F000000020D00000052656E646572537465707065640207000000436F6E6E6563740209000000436861726163746572020E00000046696E6446697273744368696C64020800000048756D616E6F6964020A0000004175746F526F7461746503010205000000496D61676502030000004F66660209000000776F726B7370616365020D00000043757272656E7443616D6572610206000000434672616D65020700000056697369626C65030002050000007063616C6C00000000009A0000000000A600B00414A00400090038207000580800000A0020683000222800006300286870003D2000004600397870001F58000053003C50F0002748000033002560D0002C30000026003560B0002D60000049002460C0002F7000002C002C78A0003D8000003A0024206000240800004C001838C0002F400000310024408000061800005A002C308000493000005B002410B0001118000000000600000314A004004600E469930B097800000D00E448B204056004000000AA00B00314A8030030000C808000057000005A003C68600042180000120004709000573000004D00046880004180000015004210A000127000003F00303800014E30000008000410D0004C70000013001810C0003A4000002200144050002838000050000830F000543000005A000C6080001F3800006000145060005E30000007000818C0003E30000000002200D001144004005F000C0830005E7800004E002C20D000391800002D002C18C0001A48000020001428C000566000003B000470A0005C7000005300244010000B280000350018584000011000000A003C68C000206800000700347850000168000047003140E0001E08000047002680F000585800003F001018F0002F500000560020208000533000000E003C6020000D100000140018602000578000000000F200800314C8030037004C50C00B42180300000000000000351000000900252AB002238801002E0050B9A5000D80040000005E00700014380400000000001000320000000000000010002D10000000006E01C000149001000000040000005108000061003C50F0000648000051000C2030002F1800004C00200810003D5800005F000880D0003A80000010000430F000431000005400181050005018000034000A10D000221000002B00106840002E800000160014405000536800004A003830C000571800000D00247810005430000020000428C0002D30000000001200200114A8030018002C4830003B8000004E000820D000024800001A003C5080002A7000003E002C3000013430000009004018D000282000000B001870500058780000340010401000316800004C003C084000130800004B002068F000583000005B00283080003A6000003800188080004F8000000E00408010005618000026001870B000275000002200102050004C2000000000AA00700214C801002D0008C8D3080C9802001700B8B1B40530F804002700E062B3032FA00100000016004000148801005C000440D0004C5000000D00207830001D3800001A003A50C0000E0800004700040880002C700000200040403000441000003F0020109000526000002F00383860004960000026000C180001387000005900302040001740000020000568A0001B200000370010483000465800000000620170011440040017000440B0005C80000062003C504000082800004D003070E0003C4800005F0005187000636000002900108090001358000034003080C0000C48000045000838C0002D2000003B00304070001C70000022001870D0005A4000005B00140800012C78000005004068A0004468000057001008B0003828000011003808B000260800005500207020000658000000003A00400414D0020000001200B00314C00400240048E161022BC804005600EC9170083D88050000006E01900414C0040060003C4810002E7800003C003E3870002458000040003038E000158000002C002468F0000F600000500010805000332000001C002010D000441800003D003038F0005610000037004050A0004240000036003C30C0004170000054000860C0002648000040004068A000192000004B00081020003F1000000500082810002268000000002E00D0011488010000008E00200114C004004400284080003010000014004080E0006250000057001A106000282000005500086020001738000007001C10B00061480000250018509000616000005F003C7090000F50000037002C3030002F68000055001C4850004A3000001100341870004A800000490040289000524800000000C600C0021408010000002600800114C004005D00086AB20B2178040040001C424007044001006300B8F290001D7802000000000000002100000000002200E00414B00100000000000100000002110000004D6F757365427574746F6E31436C69636B3C0000000208000000496E7374616E636502030000006E6577020900000053637265656E477569020B000000496D616765427574746F6E020A000000496D6167654C6162656C020400000067616D65020A000000476574536572766963650207000000436F72654775690207000000506C6179657273020A00000052756E536572766963650214000000436F6E74657874416374696F6E53657276696365020B0000004C6F63616C506C61796572021000000055736572496E7075745365727669636502030000004F6666022B00000072627861737365743A2F2F74657874757265732F75692F6D6F7573654C6F636B5F6F66664032782E706E6702020000004F6E022A00000072627861737365743A2F2F74657874757265732F75692F6D6F7573654C6F636B5F6F6E4032782E706E6702040000004C6F636B022900000072627861737365743A2F2F74657874757265732F4D6F7573654C6F636B6564437572736F722E706E6702050000004C6F636B32021E00000072627861737365743A2F2F53797374656D437572736F72732F43726F7373010000000040772B410206000000434672616D6501333333333333FB3F01000000000000000001333333333333FBBF02040000004E616D65021300000053686966746C6F636B2028436F7265477569290206000000506172656E74020E0000005A496E6465784265686176696F720204000000456E756D02070000005369626C696E67020C00000052657365744F6E537061776E030002100000004261636B67726F756E64436F6C6F72330206000000436F6C6F7233020700000066726F6D524742010000000000E06F4002160000004261636B67726F756E645472616E73706172656E637901000000000000F03F0208000000506F736974696F6E02050000005544696D32019A9999999999A93F01000000000000E03F020B000000416E63686F72506F696E740207000000566563746F7232020400000053697A65011B0326C00D49B03F018E94EDBFEEEDB03F020E00000053697A65436F6E73747261696E74020A00000052656C617469766558580205000000496D616765021000000053686966746C6F636B20437572736F7201B81E85EB51B89E3F020700000056697369626C6502110000004D6F757365427574746F6E31436C69636B0207000000436F6E6E656374020A00000042696E64416374696F6E020A0000005368696674204C6F636B020B000000536574506F736974696F6E','..',function(b,e,e)return cj[bv(b,16)]end)bf=659 end else do for b=0,255 do cj[b]=co(b);end end bf=619 end end end else if bf<=176 then if bf>=137 then if bf>=159 then if bf<170 then bf=176 do bj=string.sub end else bf=206 bz=string.gsub end else bf=159 co=string.char end else if bf<108 then bg,bh,bi,bj,bk,bl,bm,bn,bo,bp,bq,br,bs,bt,bu,bv,bw,bx,by,bz,ca,cb,cc,cd,ce,cf,cg,ch,ci,cj,ck,cl,cm,cn,co,cp,cq,cr,cs=nil bf=110 else bf=137 bq=string.byte end end else if bf<=243 then if bf<=206 then br=string.rep bf=225 else if bf>230 then bf=290 cs=table.insert else bf=243 cl=table.concat end end else if bf<=290 then bf=330 bk=math.ldexp else if bf>335 then bf=401 ch=setmetatable else bf=366 do cb=(getfenv or function()return _ENV end)end end end end end end else if bf>=992 then if bf<=1106 then if bf>=1041 then if bf<=1041 then do cm=function(b,b,b,b,b)local b,e,f,g=54,61,18,47,91,44,40,77,56,14,98,68,19,32 while b~=40 do if e<=134 then if e>=105 then if e>112 then f=ca:sub(ci,(ci+g-1))e=181 else g=bn()e=134 end else e=105 f,g=nil end else if e>=217 then if e<252 then e=261 return f;else b=40;end else do ci=(ci+g);end e=217 end end end end end bf=1071 else if bf<1097 then bf=1106 cd=function(...)do return{...},bt('#',...)end end else bi={}bf=1125 end end else if bf<1011 then bf=1017 bh=function()local b,e b,e=bq(ca,ci,(ci+2))ci=(ci+2);return((e*256)+b);end else ce=function()local b,e,f,g,k,o,r,s=91,43,36,46,91,35,28,31,58,50,99,32,79,21,90,85,29,71 while b~=42 do if e>=219 then if e>=346 then if e<=346 then e=370 if not(k~=0)then do if 0~=g then do k=1 end o=0 else return(s*l)end end elseif not(k==2047)then else if not(g~=0)then do return(s*(0/0))end else do return(s*(1/0))end end end else if e<381 then e=390 return(s*(2^(k-1023))*(g/cc+o))else break end end else if e<=219 then k=bs(20,f,11)e=255 else if e<292 then do g=(bs(0,f,20)*4294967296+r)end e=299 else e=346 do o=1 end end end end else if e<=69 then if e>45 then r=bn()e=106 else f,g,k,o,r,s=nil e=69 end else if e>=141 then if e<168 then e=171 if((r==0 and f==0))then return 0 end else s=((-t)^bs(31,f,1))e=219 end else e=141 f=bn()end end end end end bf=1041 end end else if bf<=1214 then if bf>=1165 then if bf>1168 then bf=1257 by={}else bf=1214 do bl={}end end else bx=function(b,e,e)local e,f,g,k,l,o,r,s=69,72,62,88,92,21,20,41,89,76,58,16,44,81,68,41,23,90,28,28,96,80,44,47,28 while e~=54 do if f<=314 then if f>=206 then if f<=250 then if f>213 then for t=(#bi+1),(#bi+g)do local bh,bj,bk,br,bv=74,67,59,72,97,37,23,82,38,69,84,31,77,27,40,34,54,30,17,21,52,18,21,53 while bh~=45 do if bj<=275 then if bj<=138 then if bj>=115 then if bj>119 then bj=160 br=bn()else do bv[77]=bg();end bj=138 end else if bj>72 then bv={}bj=115 else bj=86 bk,br,bv=nil end end else if bj>=235 then if bj<272 then bv[164]=bm(br,1,2);bj=275 else do bv[39]=bm(bk,1,11);end bj=324 end else if bj>169 then bj=235 bv[68]=bg();else bj=199 bk=bn()end end end else if bj<=443 then if bj>=410 then if bj>413 then bv[139]=bm(bk,12,bd);bj=466 else bv[145]=bm(br,21,29);bj=443 end else if bj<355 then bv[178]=bm(br,3,11);bj=364 else bj=410 do bv[v]=bm(br,12,20);end end end else if bj>=535 then if bj>540 then bh=45;else bj=570 do bi[t]=bv;end end else if bj>475 then bv[26]=-bv[145]bj=535 else bv[43]=-bv[178]bj=512 end end end end end end f=294 else f=250 g=bn()end else if f<309 then f=314 s[73]=bg();else for t=1,bn()do local v,bd,bh,bj,bk,br=96,48,39,82,28,20,56,96,62,71,21,48,95,43,12,84,50,41,10,22,66,93,34,35,11,36,13 while v~=48 do if bd<=272 then if bd>=177 then if bd>=233 then if bd>=249 then if bd<265 then bd=272 bk=bm(br,1,2)else bd=293 bh[164]=bk end else bd=249 bj=bn()end else if bd<206 then bd=215 while(bg()==1)do for v=1,bg()do bh[181][v]={bg()==0,bn()}end break end else do br=bn()end bd=233 end end else if bd<=89 then if bd>52 then bh={{},nil,nil}bd=111 else bd=89 bh,bj,bk,br=nil end else if bd>113 then bd=177 do bh[181]={};end else bd=138 bh[77]=bg();end end end else if bd>=409 then if bd<=441 then if bd>418 then bh[43]=-bh[178]bd=472 else bh[68]=bm(br,12,20);bd=441 end else if bd<=472 then bd=509 bh[26]=-bh[145]else if bd>516 then break else bd=545 o[t]=bh;end end end else if bd>=364 then if bd<384 then bd=391 bh[139]=bm(bj,12,33);else bd=409 bh[145]=bm(br,21,29);end else if bd<317 then bh[39]=bm(bj,1,11);bd=326 else bh[178]=bm(br,3,11);bd=364 end end end end end end f=330 end end else if f<=111 then if f<107 then g,k,l,o,r,s=nil f=111 else o={}f=133 end else if f>138 then s={}f=206 else f=158 r={}end end end else if f>=452 then if f<=476 then if f<472 then do k={}end f=476 else f=525 do for g=1,l do local t,v,bd,bh=64,68,95,84,29,73,40,31,31,51,84,88,99,30 while t~=44 do if v<=122 then if v>=89 then if v>92 then v=163 bd=nil else bh=bg()v=122 end else bd,bh=nil v=89 end else if v>=187 then if v<211 then v=214 k[g]=bd;else t=44;end else v=187 if(3==bh)then bd=(not(bg()==0));elseif(not(bh~=x))then bd=ce();elseif(not(bh~=2))then bd=cm();elseif(not(bh~=4))then do bd=b[cm()];end end;end end end end end end else if f<=525 then s[179]=k f=570 else if f>575 then e=54;else f=599 return s;end end end else if f<=374 then if f<369 then s[49]=o;f=374 else for b=1,bn()do r[b-1]=bx();end f=403 end else if f<425 then s[183]=r;f=432 else f=452 do l=bn()end end end end end end end bf=1165 end else if bf<=1257 then bf=1306 bo=function(b,e,f,g,g,g)local g,k,l,o,r k=b[49]r=b[179]do l=b[73]end o=b[183]g=bl do return function(...)local b,g,s,t,v,x,bd,bh,bj b=1 do x=-1 end v=-1 bh={}s={...}bd=(bt('#',...)-1)do t={}end bj={}for v=0,bd do if(not(v<l))then do bh[(v-l)]=s[(v+1)];end else do bj[v]=s[(v+1)];end end;end;g=(bd-l+1)while true do local g,v,bk,br,bt,bv,by,bz,ce,cf g=k[b]bv=g[39]cf=g[77]ce=g[178]do v=g[93]end bz=g[n]bk=g[68]do bt=g[43]end br=g[139]by=g[26]if not(bv<49)then if not(bv>73)then if not(bv<61)then if not(bv>66)then if not(bv>63)then if not(bv<62)then if not(bv~=62)then do bj[by]=(function()bj[ce]=bo(o[v],w,f);end)end else local n,w,cf,cj n=ce cf=((bz-1)*50)w=bj[n]cj=br for ck=ba,cj do w[(cf+ck)]=bj[(n+ck)]end;end else bl=bj end else if not(bv<65)then if(bv<66)then bj[g[178]]={};else local n,w,ba,cf cf=ce do ba={bj[cf]()}end do w=g[145]end n=0 for cj=cf,w do n=(n+1);bj[cj]=ba[n];end end else local n,w,ba,cf do w=ce end n,cf=cd(bj[w](cq(bj,(w+1),br)))do x=(cf+w-1)end ba=0 for cf=w,x do ba=(ba+1);bj[cf]=n[ba];end;end end else if not(bv>69)then if not(bv<68)then do if 68==bv then bj[g[178]]=(bj[br]^bj[bz]);else bj[ce]=(bj[br]*bj[bz]);end end else k[b]={[39]=bv-17,[139]=7,[68]=0,[178]=7,[145]=7};b=(b-h);end else if not(bv>71)then if(bv<71)then k[b]=bi[bk];b=br;else bj[g[178]]=-bj[br];end else if(bv<73)then if not bj[ce]then b=g[139];end;else f=bj[g[ce]]end end end end else do if not(bv>54)then if not(bv>51)then if not(bv<50)then if(bv>50)then if bj[ce]then b=br;end;else local h,n n=ce do h=bj[br]end do bj[(n+1)]=h;end bj[n]=h[r[bz]];end else bj[ce]=(bj[br]%r[bz]);end else if not(bv<53)then if not(g[39]~=53)then local h h={}if(#t>0)then for n=1,#t do local w w=t[n]for n=0,#w do local ba,cf,cj ba=w[n]do cj=ba[1]end cf=ba[2]if(cj==bj and cf>=0)then h[cf]=cj[cf]ba[1]=h end end end end return g[ce];else local h h=ce bj[h]=bj[h](cq(bj,h+1,br));end elseif((bj[g[178]]>bj[g[145]]))then b=br;end end else if not(bv<58)then if not(g[39]>58)then for h=ce,br do bj[h]=nil;end;else if bb==g[39]then do bj[ce]=(bj[br]+bj[bz]);end else local h,n n=ce h=bj[br]bj[(n+1)]=h;do bj[n]=h[bj[bz]];end end end else if not(bv<56)then if(bv>56)then bj[ce]=(bj[br]%bj[bz]);else local h h=ce bj[h]=bj[h](cq(bj,h+1,x));end else k[b]={[145]=40,[68]=0,[139]=39,[39]=bv-42,[178]=3};b=(b-1);end end end end end else do if not(bv<86)then if not(g[39]<92)then if not(bv<95)then if not(bv<97)then if(bv<98)then while((bj[ce]>=bj[bz]))do b=br;break end else bj[ce]=nil;end else if not(bv~=95)then k[b]={[68]=0,[145]=36,[39]=g[39]-81,[u]=2,[139]=1};b=(b-bc);else local h h=ce bj[h](cq(bj,(h+1),x))end end else if not(bv>92)then bj[ce]=(bj[br]/r[bz]);else if not(bv~=93)then bj[ce]=f[r[br]][r[bz]];else local h,n,u u=o[br]h=nil n={}do h=ch({},{__index=function(w,w)local w=n[w];return w[1][w[2]];end,__newindex=function(w,w,ba)local w=n[w]w[1][w[2]]=ba;end;});end for w=1,bz do local ba ba=g[181][w]if ba[1]then n[(w-1)]={bj,ba[2],nil,nil};else n[(w-1)]={e,ba[2],nil,nil};end;do t[(#t+1)]=n;end end;bj[ce]=bo(u,h,f);end end end else if not(bv<89)then if not(bv<90)then do if(bv<91)then local h,n n=ce do h=br end do for u=n,h do do bj[u]=bh[(u-n)];end end;end else bj[ce][r[br]]=bj[bz];end end else local h,n do n=g[178]end h={}while(#t>0)do for u=1,#t do local u=t[u]for w=0,#u do local u=u[w]local w=u[1]local ba=u[2]if w==bj and ba>=0 then h[ba]=w[ba]u[1]=h end end end break end return bj[n],bj[(n+1)]end else if not(g[39]<87)then if(bv<88)then b=((bj[ce]~=bj[g[145]])and br or b)else bj[g[178]]=bj[br];end else bj[g[178]][bj[br]]=bj[bz];end end end else do if not(g[39]<80)then if not(bv<83)then if not(bv<84)then if(bv>84)then do bj[g[26]]();end else f[r[br]]=bj[ce];end else bj[ce]=bj[br][bj[bz]];end else do if not(bv>d)then local d d=ce do return cq(bj,d,(d+br))end;else if 81==bv then local d,h do d=g[178]end h={}do if(#t>0)then for n=1,#t do local u u=t[n]for n=0,#u do local w,ba,bb w=u[n]ba=w[1]bb=w[2]do if(ba==bj and bb>=0)then do h[bb]=ba[bb]end w[1]=h end end end end end end return cq(bj,d,x);else do bj[ce]=(bj[br]/bj[bz]);end end end end end else do if not(bv<77)then if not(bv>77)then bj[g[ce]]=bj else if(bv<79)then local d,h,n do n=ce end h={bj[n](cq(bj,n+1,br))}d=0 do for u=n,bz do d=(d+1);bj[u]=h[d];end end else bj[ce]=(bj[br]+r[bz]);end end else if not(bv<75)then if(bv>75)then local d d=ce bj[d]=bj[d](bj[d+a]);else bj[ce]=(bj[br]*r[bz]);end else do bj[ce]=#bj[g[139]];end end end end end end end end end else if not(bv<p)then if not(bv>35)then if not(bv>29)then do if not(bv>26)then if not(bv<25)then if(bv<26)then k[b]={[139]=1,[178]=1,[39]=bv-19,[145]=8,[68]=0};b=(b-1);elseif not bj[bz]then do bj[ce]=bj[bz];end do b=g[139];end end else bj[ce]=bl[v]end else if not(g[39]<q)then if(bv>28)then local a,d,h,n,p do d=ce end n=bz h=(d+2)p={bj[d](bj[d+y],bj[h])}for q=1,n do bj[(h+q)]=p[q]end a=bj[(d+3)]if a then do bj[h]=a end else do b=g[139];end end;else do k[b]=bi[bk];end b=br;end else bl[ce]=bl[g[93]]end end end else if not(bv<z)then if not(g[39]>33)then do bj[ce]=e[br];end else if(bv<35)then local a a=bj[bt][bk]bj[bt][bk]=(a..bj[bz]);else do do return bj[bt][bk]end end end end else if not(g[39]<31)then if(bv<32)then bj[by]=(function()bj[ce]=bo(o[v],nil,f);end)else bj[ce]=bo(o[br],nil,f);end else bj[g[178]]=(not(br==0));b=(b+1);end end end else do if not(bv>41)then if not(bv>38)then if not(bv>36)then r=bl[ce](r)else if not(bv~=37)then if(not(bj[ce]==bj[bz]))then do b=br;end end;else end end else do if not(bv<40)then if not(bv~=40)then do b=((r[ce]<bj[bz])and br or b)end else k[b]={[39]=bv-35,[68]=0,[145]=2,[178]=13,[139]=13};do b=(b-1);end end else do if ce then ce=false;do bz=br;end do b=(b-1);end else b=(b+br+bz);end end end end end else do if not(bv>44)then if not(bv>42)then x=g[ce];else if not(bv~=43)then bj={};do for a=c,bd do do if(a<l)then bj[a]=s[(a+1)];else do break end end;end end;end else bl[ce]=bj[v]end end else if not(bv<47)then do if not(bv~=47)then bl[ce]()else e[br]=bj[ce];end end else if(bv>45)then local a,c,d a=ce c=bj[a]d=bj[(a+2)]if((d>0))then do if((c>bj[a+1]))then b=br;else bj[(a+3)]=c;end end elseif((c<bj[a+1]))then b=br;else bj[(a+3)]=c;end else local a a=ce bj[a](bj[(a+j)])end end end end end end end else if not(bv<12)then if not(bv>17)then if not(bv>14)then if not(bv<13)then if not(bv~=13)then do bj[ce][r[g[139]]]=r[bz];end else do bj[ce]=r[br]end end else bj[ce]=(not bj[br]);end else if not(bv>15)then do bj[ce]=bj[br]end else if(bv<17)then local a,c c=ce a={}for d=1,#t do local e e=t[d]for d=0,#e do local h,j,k h=e[d]j=h[1]k=h[2]do if(j==bj and k>=c)then a[k]=j[k];h[1]=a;end;end end;end;else end end end else do if not(bv<21)then if not(bv>21)then if((bj[ce]<bj[bz]))then b=br;end;else if(bv>22)then local a,c c,a=cd(...)for a=1,ce do bj[(a-1)]=c[a]end else local a a=ce bj[a](cq(bj,(a+1),g[m]))end end else do if not(bv<19)then if not(g[39]~=19)then do return bj[ce]();end;else b=br;end else bj[ce]=bl[v]end end end end end else if not(bv>5)then if not(bv>2)then do if not(bv<1)then if(bv<2)then do return bj[ce]end else do bj[g[178]]=(bj[br]-bj[bz]);end end else local a a=ce do do return bj[a](cq(bj,(a+1),br))end;end end end else do if not(bv<4)then if(bv>4)then if(not(bj[ce]==r[g[145]]))then b=br;end;else local a,c a=br do c=bj[a]end do for d=(a+1),bz do c=(c..bj[d]);end;end bj[g[178]]=c;end else local a,c,d d=g[178]do c=bj[(d+2)]end a=(bj[d]+c)do bj[d]=a;end if((c>0))then if(not(a>bj[d+1]))then b=g[139];bj[(d+3)]=a;end elseif(not(a<bj[d+1]))then do b=br;end bj[(d+3)]=a;end end end end else do if not(g[39]<9)then if not(bv>9)then bj[ce]=(0~=br);else if(bv<11)then else if((r[ce]<bj[bz]))then b=br;end;end end else if not(bv>6)then bj[g[178]]=bj[br][r[g[145]]];else if not(g[39]~=7)then bl[ce]={}else bj[ce]=f[r[g[139]]];end end end end end end end end b=(b+1);end;end;end end else if bf>1313 then be=77;else bf=1329 return bo(bx(cb()),{},cb())();end end end end else if bf>=845 then if bf<=893 then if bf<=845 then bs=function(a,b,c,d,d)local d,e,f=73,62,73,60,53,31,90,15,32,22,77,90,22,84,70,62 while d~=27 do if e>=163 then if e>=188 then if e<218 then e=226 return f else d=27;end else e=188 f=(f-f%1)end else if e<=62 then f=nil e=105 else if e<123 then f=nil e=129 else e=163 do f=((b/cp[a])%cp[c])end end end end end end bf=862 else if bf<890 then bf=893 bu=(bit_lib and bit_lib.bxor or function(a,b)a=a%(2^32)b=b%(2^32)local c,d=0,1 while a>0 and b>0 do local e,f=a%16,b%16 c=c+bw[e+1][f+1]*d a=(a-e)/16 b=(b-f)/16 d=d*16 end c=c+a*d+b*d return c end)else bm=function(a,b,c,d,d,d)local d d=((a/2^(b-1))%2^((c-1)-(b-1)+1))return(d-d%1);end bf=911 end end else if bf>=932 then if bf<951 then bn=function()local a,b,c,d a,d,b,c=bq(ca,ci,(ci+3))ci=(ci+4);return((c*16777216)+(b*65536)+(d*256)+a);end bf=959 else bf=992 bg=function()local a a=bq(ca,ci,ci)ci=(ci+1);return a;end end else bf=932 do ci=1 end end end else if bf>=747 then if bf<=747 then cp={[0]=1}bf=780 else if bf<810 then bf=812 bp=2 else for a=i,31 do cp[a]=bp bp=(bp*2)end bf=845 end end else if bf>684 then bf=747 do cc=(2^52)end else cg=''bf=703 end end end end end end end)(1,1,0,80,0,8,0,1,1,1,12,0,139,145,8,24,28,10,11,1,178,93,nil,1,1,33,1,59,1,33)
		-- The function that takes place when the button is pressed
	end,
})

local Label = Tab:CreateLabel("These are mostly people who will ban/report you so be careful!", "box")

local Toggle = Tab:CreateToggle({
	Name = "Detect Special Thanks people",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		local Players = game:GetService("Players")
		local targetUsers = {"Mylezeezz", "Sir_Mason13", "jasper_creations", "ItzRoboMaggot", "CyroTr00per"}
		local targetSet = {}

		-- Populate the set for faster checking
		for _, userName in ipairs(targetUsers) do
			targetSet[userName] = true
		end

		local function notify(playerName, joined)
			Rayfield:Notify({
				Title = "Special Thanks person Detected",
				Content = "Detected " .. playerName .. (joined and " joined." or " is already here."),
				Duration = 17.5,
				Image = 91599976542183,
			})
		end

		local function onPlayerAdded(player)
			if targetSet[player.Name] then
				notify(player.Name, true)
			end
		end

		Players.PlayerAdded:Connect(onPlayerAdded)

		for _, player in Players:GetPlayers() do
			if targetSet[player.Name] then
				notify(player.Name, false)
			end
		end
	end, -- Closing brace for the Toggle's Callback function
})

local Toggle = Tab:CreateToggle({
	Name = "Detect Contributers",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value) 
		local Players = game:GetService("Players")
		local targetUsers = {"JankCorp", "JakeDravioli", "1Boomah"}
		local targetSet = {}

		for _, userName in ipairs(targetUsers) do
			targetSet[userName] = true
		end

		local function notify(playerName, joined)
			Rayfield:Notify({
				Title = "Contributer Detected",
				Content = "Detected " .. playerName .. (joined and " joined." or " is already here."),
				Duration = 17.5,
				Image = 91599976542183,
			})
		end

		local function onPlayerAdded(player)
			if targetSet[player.Name] then
				notify(player.Name, true)
			end
		end

		Players.PlayerAdded:Connect(onPlayerAdded)

		for _, player in Players:GetPlayers() do
			if targetSet[player.Name] then
				notify(player.Name, false)
			end
		end
	end,
})

local Toggle = Tab:CreateToggle({
	Name = "Detect Testers",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		local Players = game:GetService("Players")
		local targetUsers = {"MikoSfx", "Lgl_frijol", "xF_alse", "FluxedThoughts", "Blackcoolia", "Crinsikle", "HolyBlanks", "mightyasher", "ROV3RRO", "Oce1rosTheConsum3d", "Tsunantt", "Shark_bossx007", "AgentCatto", "ashinvy", "roblox_user_841257226"}
		local targetSet = {}

		for _, userName in ipairs(targetUsers) do
			targetSet[userName] = true
		end

		local function notify(playerName, joined)
			Rayfield:Notify({
				Title = "Tester Detected",
				Content = "Detected " .. playerName .. (joined and " joined." or " is already here."),
				Duration = 12.5,
				Image = "wrench",
			})
		end

		local function onPlayerAdded(player)
			if targetSet[player.Name] then
				notify(player.Name, true)
			end
		end

		Players.PlayerAdded:Connect(onPlayerAdded)

		for _, player in Players:GetPlayers() do
			if targetSet[player.Name] then
				notify(player.Name, false)
			end
		end
	end,
})

local Toggle = Tab:CreateToggle({
	Name = "Detect Mods/Admins (include server mods)",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		local Players = game:GetService("Players")
		local targetUsers = {"As3tra1", "GetRightDawg", "N0XMANIAC", "Benthesoccerone", "Megamind184", "OrekLus1", "maravilye2312", "euphoria4830", "XHttpkeVin", "ddelus1", "Chromixx_WasTaken"}
		local targetSet = {}

		for _, userName in ipairs(targetUsers) do
			targetSet[userName] = true
		end

		local function notify(playerName, joined)
			Rayfield:Notify({
				Title = "Mod/Admin Detected",
				Content = "Detected " .. playerName .. (joined and " joined" or " is already here."),
				Duration = 15.5,
				Image = 91599976542183,
			})
		end

		local function onPlayerAdded(player)
			if targetSet[player.Name] then
				notify(player.Name, true)
			end
		end

		Players.PlayerAdded:Connect(onPlayerAdded)

		for _, player in Players:GetPlayers() do
			if targetSet[player.Name] then
				notify(player.Name, false)
			end
		end
	end,
})

local Toggle = Tab:CreateToggle({
	Name = "Detect Managers",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		local Players = game:GetService("Players")
		local targetUsers = {"fraudTheSecond", "IAmUnderAMask"}
		local targetSet = {}

		for _, userName in ipairs(targetUsers) do
			targetSet[userName] = true
		end

		local function notify(playerName, joined)
			Rayfield:Notify({
				Title = "Manager Detected",
				Content = "Detected " .. playerName .. (joined and " joined." or " is already here."),
				Duration = 17.5,
				Image = 91599976542183,
			})
		end

		local function onPlayerAdded(player)
			if targetSet[player.Name] then
				notify(player.Name, true)
			end
		end

		Players.PlayerAdded:Connect(onPlayerAdded)

		for _, player in Players:GetPlayers() do
			if targetSet[player.Name] then
				notify(player.Name, false)
			end
		end
	end,
})

local Toggle = Tab:CreateToggle({
	Name = "Detect Devs",
	CurrentValue = false,
	Flag = "Toggle1",
	Callback = function(Value)
		local Players = game:GetService("Players")
		local targetUsers = {"Yurixzaaa", "SSpreezzy"}
		local targetSet = {}

		for _, userName in ipairs(targetUsers) do
			targetSet[userName] = true
		end

		local function notify(playerName, joined)
			Rayfield:Notify({
				Title = "Dev Detected",
				Content = "Detected " .. playerName .. (joined and " joined." or " is already here."),
				Duration = 17.5,
				Image = 91599976542183,
			})
		end

		local function onPlayerAdded(player)
			if targetSet[player.Name] then
				notify(player.Name, true)
			end
		end

		Players.PlayerAdded:Connect(onPlayerAdded)

		for _, player in Players:GetPlayers() do
			if targetSet[player.Name] then
				notify(player.Name, false)
			end
		end
	end,
})

local Divider = Tab:CreateDivider()

local bloodmoonDetectEnabled = false
local heartbeatConnection = nil

local Toggle = Tab:CreateToggle({
	Name = "Detect Bloodmoon",
	CurrentValue = false,
	Flag = "DetectBloodmoonToggle",
	Callback = function(Value)
		bloodmoonDetectEnabled = Value

		if bloodmoonDetectEnabled then
			heartbeatConnection = game:GetService("RunService").Heartbeat:Connect(function()
				local angerObject = workspace:FindFirstChild("Misc") and
					workspace.Misc:FindFirstChild("AI") and
					workspace.Misc.AI:FindFirstChild("CHAIN") and
					workspace.Misc.AI.CHAIN:FindFirstChild("Anger")

				if angerObject and angerObject.Value >= 105 then
					Rayfield:Notify({
						Title = "Chain is entering bloodmoon soon",
						Content = "Detected Chain's Anger at " .. angerObject.Value,
						Duration = 8,
						Image = "moon",
					})
				end
			end)
		else
			if heartbeatConnection then
				heartbeatConnection:Disconnect()
				heartbeatConnection = nil
			end
		end
	end,
})

local detectChokeEnabled = false
local chokeHeartbeatConnection = nil

local LocalToggle = Tab:CreateToggle({
	Name = "Detect Chain's Choke",
	CurrentValue = false,
	Flag = "DetectChokeToggle",
	Callback = function(Value)
		detectChokeEnabled = Value

		if detectChokeEnabled then
			chokeHeartbeatConnection = game:GetService("RunService").Heartbeat:Connect(function()
				local chokeMeterObject = workspace:FindFirstChild("Misc") and
					workspace.Misc:FindFirstChild("AI") and
					workspace.Misc.AI:FindFirstChild("CHAIN") and
					workspace.Misc.AI.CHAIN:FindFirstChild("ChokeMeter")

				if chokeMeterObject and chokeMeterObject.Value >= 85 then
					Rayfield:Notify({
						Title = "Detected Chain's Choke",
						Content = "Chain is about to use choke, his choke meter is around 85",
						Duration = 8,
						Image = "bone",
					})
				end
			end)
		else
			if chokeHeartbeatConnection then
				chokeHeartbeatConnection:Disconnect()
				chokeHeartbeatConnection = nil
			end
		end
	end,
})

local detectGroundslamEnabled = false
local groundslamHeartbeatConnection = nil

local Toggle = Tab:CreateToggle({
	Name = "Detect Chain's Groundslam",
	CurrentValue = false,
	Flag = "DetectGroundslamToggle",
	Callback = function(Value)
		detectGroundslamEnabled = Value

		if detectGroundslamEnabled then
			groundslamHeartbeatConnection = game:GetService("RunService").Heartbeat:Connect(function()
				local burstObject = workspace:FindFirstChild("Misc") and
					workspace.Misc:FindFirstChild("AI") and
					workspace.Misc.AI:FindFirstChild("CHAIN") and
					workspace.Misc.AI.CHAIN:FindFirstChild("Burst")

				if burstObject and burstObject.Value >= 85 then -- fish then fishssssssszz - Neonicf
					Rayfield:Notify({
						Title = "Detected Chain's Groundslam",
						Content = "Chain is about to use groundslam, his groundslam is around 85",
						Duration = 8,
						Image = "hammer",
					})
				end
			end)
		else
			if groundslamHeartbeatConnection then
				groundslamHeartbeatConnection:Disconnect()
				groundslamHeartbeatConnection = nil
			end
		end
	end,
})



local Divider = Tab:CreateDivider()

local Label = Tab:CreateLabel("These only unlock blueprints btw", "printer")

local Button = Tab:CreateButton({
	Name = "Unlock all Blueprints",
	Callback = function()
		local player = game.Players.LocalPlayer
		local playerStats = player:WaitForChild("PlayerStats")
		local blueprints = playerStats:WaitForChild("Blueprints")

		for _, name in ipairs(blueprints:GetAttributeNames()) do
			blueprints:SetAttribute(name, true)
		end
	end,
})

local Button = Tab:CreateButton({
	Name = "Unlock CombatKnife",
	Callback = function()
		local player = game.Players.LocalPlayer
		local blueprints = player:WaitForChild("PlayerStats"):WaitForChild("Blueprints")

		local attributeName = "CombatKnife"

		if blueprints:GetAttribute(attributeName) ~= nil then
			blueprints:SetAttribute(attributeName, true)
			print("Attribute '" .. attributeName .. "' set to true.")
		else
			print("Attribute '" .. attributeName .. "' not found in Blueprints.")
		end
	end,
})

local Button = Tab:CreateButton({
	Name = "Unlock Deagle",
	Callback = function()
		local player = game.Players.LocalPlayer
		local blueprints = player:WaitForChild("PlayerStats"):WaitForChild("Blueprints")

		local attributeName = "Deagle"

		if blueprints:GetAttribute(attributeName) ~= nil then
			blueprints:SetAttribute(attributeName, true)
			print("Attribute '" .. attributeName .. "' set to true.")
		else
			print("Attribute '" .. attributeName .. "' not found in Blueprints.")
		end
	end,
})

local Button = Tab:CreateButton({
	Name = "Unlock DoubleBarrel",
	Callback = function()
		local player = game.Players.LocalPlayer
		local blueprints = player:WaitForChild("PlayerStats"):WaitForChild("Blueprints")

		local attributeName = "DoubleBarrel"

		if blueprints:GetAttribute(attributeName) ~= nil then
			blueprints:SetAttribute(attributeName, true)
			print("Attribute '" .. attributeName .. "' set to true.")
		else
			print("Attribute '" .. attributeName .. "' not found in Blueprints.")
		end
	end,
})

local Button = Tab:CreateButton({
	Name = "Unlock M1911",
	Callback = function()
		local player = game.Players.LocalPlayer
		local blueprints = player:WaitForChild("PlayerStats"):WaitForChild("Blueprints")

		local attributeName = "M1911"

		if blueprints:GetAttribute(attributeName) ~= nil then
			blueprints:SetAttribute(attributeName, true)
			print("Attribute '" .. attributeName .. "' set to true.")
		else
			print("Attribute '" .. attributeName .. "' not found in Blueprints.")
		end
	end,
})

local Button = Tab:CreateButton({
	Name = "Unlock Machete",
	Callback = function()
		local player = game.Players.LocalPlayer
		local blueprints = player:WaitForChild("PlayerStats"):WaitForChild("Blueprints")

		local attributeName = "Machete"

		if blueprints:GetAttribute(attributeName) ~= nil then
			blueprints:SetAttribute(attributeName, true)
			print("Attribute '" .. attributeName .. "' set to true.")
		else
			print("Attribute '" .. attributeName .. "' not found in Blueprints.")
		end
	end,
})

local Button = Tab:CreateButton({
	Name = "Unlock SpellBook (may be glitched)",
	Callback = function()
		local player = game.Players.LocalPlayer
		local blueprints = player:WaitForChild("PlayerStats"):WaitForChild("Blueprints")

		local attributeName = "SpellBook"

		if blueprints:GetAttribute(attributeName) ~= nil then
			blueprints:SetAttribute(attributeName, true)
			print("Attribute '" .. attributeName .. "' set to true.")
		else
			print("Attribute '" .. attributeName .. "' not found in Blueprints.")
		end
	end,
})

local Divider = Tab:CreateDivider()

local Button = Tab:CreateButton({
	Name = "Unlock Artifact Quest (might fix spellbook blueprint)",
	Callback = function()
		local playerStats = game.Players.LocalPlayer:WaitForChild("PlayerStats")
		local quests = playerStats:WaitForChild("Quests")

		-- Set the "ArtifactQuest" attribute to true
		quests:SetAttribute("ArtifactQuest", true)
	end,
})

local Tab = Window:CreateTab("GUI interface", "square-terminal")

local Button = Tab:CreateButton({
	Name = "Watch and Power Gui",
	Callback = function()
		loadstring(game:HttpGet('https://pastebin.com/raw/9gdApaSy'))()
		-- The function that takes place when the button is pressed
	end,
})

local Toggle = Tab:CreateToggle({
	Name = "Radio Gui",
	CurrentValue = false,
	Flag = "Toggle1",
	Callback = function(Value)
		local player = game.Players.LocalPlayer
		local ingameGui = player:WaitForChild("PlayerGui"):WaitForChild("Ingame")
		local radioFrame = ingameGui:WaitForChild("Radio")
		local titleLabel = radioFrame:WaitForChild("Title"):WaitForChild("TextLabel")

		local isVisible = radioFrame.Visible

		if not isVisible then
			radioFrame.Visible = true
			titleLabel.Text = "Spoofed Radio gui by Nëonicf"
			titleLabel.TextStrokeColor3 = Color3.fromRGB(110, 77, 47)
			radioFrame.BackgroundColor3 = Color3.fromRGB(20, 0, 70)
		else
			radioFrame.Visible = false
		end

		-- The function that takes place when the button is pressed
	end,
})

local Toggle = Tab:CreateToggle({
	Name = "Shop Gui - Only works during day",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		local player = game.Players.LocalPlayer
		local ingameGui = player:WaitForChild("PlayerGui"):WaitForChild("Ingame")
		local Shop = ingameGui:WaitForChild("Shop")

		local isVisible = Shop.Visible

		if not isVisible then
			Shop.Visible = true
		else
			Shop.Visible = false
		end
		-- The function that takes place when the toggle is pressed
		-- The variable (Value) is a boolean on whether the toggle is true or false
	end,
})

local Divider = Tab:CreateDivider()

local Label = Tab:CreateLabel("These are somewhat useless Guis, deconstructor and workbench may not work cuz u have to be near it", "rewind")

local Toggle = Tab:CreateToggle({
	Name = "Deconstructor Gui",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		local player = game.Players.LocalPlayer
		local ingameGui = player:WaitForChild("PlayerGui"):WaitForChild("Ingame")
		local De = ingameGui:WaitForChild("Deconstructor")

		local isVisible = De.Visible

		if not isVisible then
			De.Visible = true
		else
			De.Visible = false
		end
		-- The function that takes place when the toggle is pressed
		-- The variable (Value) is a boolean on whether the toggle is true or false
	end,
})

local Toggle = Tab:CreateToggle({
	Name = "Workbench Gui",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		local player = game.Players.LocalPlayer
		local ingameGui = player:WaitForChild("PlayerGui"):WaitForChild("Ingame")
		local Work = ingameGui:WaitForChild("Workbench")

		local isVisible = Work.Visible

		if not isVisible then
			Work.Visible = true
		else
			Work.Visible = false
		end
		-- The function that takes place when the toggle is pressed
		-- The variable (Value) is a boolean on whether the toggle is true or false
	end,
})

local Tab = Window:CreateTab("Render", "fire-extinguisher") -- Title, Image

local Section = Tab:CreateSection("Lightening - recommended to use both")

local Divider = Tab:CreateDivider()

local Button = Tab:CreateButton({
	Name = "nofog",
	Callback = function()
		-- Services
		local Lighting = game:GetService("Lighting")

		-- FogEnd
		Lighting.FogEnd = 100000

		Lighting:GetPropertyChangedSignal("FogEnd"):Connect(function()
			Lighting.FogEnd = 100000
		end)

		-- Atmosphere
		for _,v in ipairs(Lighting:GetDescendants()) do
			if v:IsA("Atmosphere") then
				v.Density = 0

				v:GetPropertyChangedSignal("Density"):Connect(function()
					v.Density = 0
				end)
			end
		end

		Lighting.DescendantAdded:Connect(function(v)
			if v:IsA("Atmosphere") then
				v.Density = 0

				v:GetPropertyChangedSignal("Density"):Connect(function()
					v.Density = 0
				end)
			end
		end)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "fullbright",
	Callback = function()
		if not _G.FullBrightExecuted then

			_G.FullBrightEnabled = false

			_G.NormalLightingSettings = {
				Brightness = game:GetService("Lighting").Brightness,
				ClockTime = game:GetService("Lighting").ClockTime,
				FogEnd = game:GetService("Lighting").FogEnd,
				GlobalShadows = game:GetService("Lighting").GlobalShadows,
				Ambient = game:GetService("Lighting").Ambient
			}

			game:GetService("Lighting"):GetPropertyChangedSignal("Brightness"):Connect(function()
				if game:GetService("Lighting").Brightness ~= 1 and game:GetService("Lighting").Brightness ~= _G.NormalLightingSettings.Brightness then
					_G.NormalLightingSettings.Brightness = game:GetService("Lighting").Brightness
					if not _G.FullBrightEnabled then
						repeat
							wait()
						until _G.FullBrightEnabled
					end
					game:GetService("Lighting").Brightness = 1
				end
			end)

			game:GetService("Lighting"):GetPropertyChangedSignal("ClockTime"):Connect(function()
				if game:GetService("Lighting").ClockTime ~= 12 and game:GetService("Lighting").ClockTime ~= _G.NormalLightingSettings.ClockTime then
					_G.NormalLightingSettings.ClockTime = game:GetService("Lighting").ClockTime
					if not _G.FullBrightEnabled then
						repeat
							wait()
						until _G.FullBrightEnabled
					end
					game:GetService("Lighting").ClockTime = 12
				end
			end)

			game:GetService("Lighting"):GetPropertyChangedSignal("FogEnd"):Connect(function()
				if game:GetService("Lighting").FogEnd ~= 786543 and game:GetService("Lighting").FogEnd ~= _G.NormalLightingSettings.FogEnd then
					_G.NormalLightingSettings.FogEnd = game:GetService("Lighting").FogEnd
					if not _G.FullBrightEnabled then
						repeat
							wait()
						until _G.FullBrightEnabled
					end
					game:GetService("Lighting").FogEnd = 786543
				end
			end)

			game:GetService("Lighting"):GetPropertyChangedSignal("GlobalShadows"):Connect(function()
				if game:GetService("Lighting").GlobalShadows ~= false and game:GetService("Lighting").GlobalShadows ~= _G.NormalLightingSettings.GlobalShadows then
					_G.NormalLightingSettings.GlobalShadows = game:GetService("Lighting").GlobalShadows
					if not _G.FullBrightEnabled then
						repeat
							wait()
						until _G.FullBrightEnabled
					end
					game:GetService("Lighting").GlobalShadows = false
				end
			end)

			game:GetService("Lighting"):GetPropertyChangedSignal("Ambient"):Connect(function()
				if game:GetService("Lighting").Ambient ~= Color3.fromRGB(178, 178, 178) and game:GetService("Lighting").Ambient ~= _G.NormalLightingSettings.Ambient then
					_G.NormalLightingSettings.Ambient = game:GetService("Lighting").Ambient
					if not _G.FullBrightEnabled then
						repeat
							wait()
						until _G.FullBrightEnabled
					end
					game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)
				end
			end)

			game:GetService("Lighting").Brightness = 1
			game:GetService("Lighting").ClockTime = 12
			game:GetService("Lighting").FogEnd = 786543
			game:GetService("Lighting").GlobalShadows = false
			game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)

			local LatestValue = true
			spawn(function()
				repeat
					wait()
				until _G.FullBrightEnabled
				while wait() do
					if _G.FullBrightEnabled ~= LatestValue then
						if not _G.FullBrightEnabled then
							game:GetService("Lighting").Brightness = _G.NormalLightingSettings.Brightness
							game:GetService("Lighting").ClockTime = _G.NormalLightingSettings.ClockTime
							game:GetService("Lighting").FogEnd = _G.NormalLightingSettings.FogEnd
							game:GetService("Lighting").GlobalShadows = _G.NormalLightingSettings.GlobalShadows
							game:GetService("Lighting").Ambient = _G.NormalLightingSettings.Ambient
						else
							game:GetService("Lighting").Brightness = 1
							game:GetService("Lighting").ClockTime = 12
							game:GetService("Lighting").FogEnd = 786543
							game:GetService("Lighting").GlobalShadows = false
							game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)
						end
						LatestValue = not LatestValue
					end
				end
			end)
		end

		_G.FullBrightExecuted = true
		_G.FullBrightEnabled = not _G.FullBrightEnabled
		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Button = Tab:CreateButton({
	Name = "Shaders - PShade",
	Callback = function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/randomstring0/pshade-ultimate/refs/heads/main/src/cd.lua'))()
		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Button = Tab:CreateButton({
	Name = "chain info esp",
	Callback = function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/BongCloudMaster/CHAIN/main/chain%20esp.lua"))()
		-- The function that takes place when the button is pressed
	end,
})

local Toggle = Tab:CreateToggle({
	Name = "Chain ESP - red",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		-- Simple Highlight Script
		-- Made by alan.nguyen.12 (fixed by Neon 🗣️ 🔥{ok but actually i did all the work -Neon})
		--chain esp for chain

		local partToHighlight = workspace.Misc.AI.CHAIN

		local highlight = Instance.new("Highlight")
		highlight.Parent = partToHighlight
		highlight.FillColor = Color3.fromRGB(255, 21, 21) -- Red
		highlight.OutlineColor = Color3.fromRGB(255, 255, 255) -- Black
		highlight.FillTransparency = 0.60
		highlight.OutlineTransparency = 0
		-- The function that takes place when the toggle is pressed
		-- The variable (Value) is a boolean on whether the toggle is true or false
	end,
})

local Button = Tab:CreateButton({
	Name = "Scrap ESP - not mine",
	Callback = function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/BongCloudMaster/CHAIN/main/scrap%20esp.lua"))()
		-- The function that takes place when the button is pressed
	end,
})

local Toggle = Tab:CreateToggle({
	Name = "Artifact ESP - not mine",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		local Players = game:GetService("Players")
		local RunService = game:GetService("RunService")

		local plr = Players.LocalPlayer
		local chr = plr.Character or plr.CharacterAdded:Wait()
		local hrp = chr:WaitForChild("HumanoidRootPart")
		local artifactsFolder = workspace.Misc.Zones.LootingItems.Artifacts

		local function createDistanceGui(part)
			local billboard = Instance.new("BillboardGui")
			billboard.Name = "DistanceGui"
			billboard.Adornee = part
			billboard.Size = UDim2.new(0, 100, 0, 40)
			billboard.StudsOffset = Vector3.new(0, 2, 0)
			billboard.AlwaysOnTop = true

			local textLabel = Instance.new("TextLabel")
			textLabel.BackgroundTransparency = 1
			textLabel.Size = UDim2.new(1, 0, 1, 0)
			textLabel.TextColor3 = Color3.new(1, 0, 0)
			textLabel.TextStrokeTransparency = 0.5
			textLabel.TextScaled = true
			textLabel.Font = Enum.Font.SourceSansBold
			textLabel.Parent = billboard

			billboard.Parent = part
			return textLabel
		end

		for _, model in ipairs(artifactsFolder:GetChildren()) do
			if model:IsA("Model") then
				for _, part in ipairs(model:GetChildren()) do
					if part:IsA("MeshPart") then
						local highlight = Instance.new("Highlight")
						highlight.Adornee = part
						highlight.FillColor = Color3.new(1, 0, 0)
						highlight.OutlineColor = Color3.new(1, 0, 0)
						highlight.Parent = part

						local distanceLabel = createDistanceGui(part)

						RunService.Heartbeat:Connect(function()
							if hrp and hrp.Parent then
								local dist = (hrp.Position - part.Position).Magnitude
								distanceLabel.Text = string.format("%.1f studs", dist)
							end
						end)
					end
				end
			end
		end
		-- The function that takes place when the toggle is pressed
		-- The variable (Value) is a boolean on whether the toggle is true or false
	end,
})

local Tab = Window:CreateTab("AutoFarm", "feather") -- Title, Image

local Toggle = Tab:CreateToggle({
	Name = "Auto collect Scrap",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		loadstring(game:HttpGet("https://raw.githubusercontent.com/BongCloudMaster/CHAIN/main/scrapcollector.lua"))()
		-- The function that takes place when the toggle is pressed
		-- The variable (Value) is a boolean on whether the toggle is true or false
	end,
})

local Toggle = Tab:CreateToggle({
	Name = "Auto collect Artifact",
	CurrentValue = false,
	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		local plr = game.Players.LocalPlayer
		local chr = plr.Character or plr.CharacterAdded:Wait()
		local hrp = chr:WaitForChild("HumanoidRootPart")
		local artifactsFolder = workspace.Misc.Zones.LootingItems.Artifacts
		local artifactModels = artifactsFolder:GetChildren()

		for _, model in ipairs(artifactModels) do
			if model:IsA("Model") then
				for _, part in ipairs(model:GetChildren()) do
					if part:IsA("MeshPart") and part.Transparency == 0 then
						hrp.CFrame = part.CFrame + Vector3.new(0, 2, 0)
						task.wait(0.3)

						local prompt = part:FindFirstChildOfClass("ProximityPrompt")
						if prompt and prompt.Enabled then
							fireproximityprompt(prompt)
						end

						task.wait(0.5)
					end
				end
			end
		end
		-- The function that takes place when the toggle is pressed
		-- The variable (Value) is a boolean on whether the toggle is true or false
	end,
})

local Tab = Window:CreateTab("Teleport - Locations", "drafting-compass") -- Title, Image

local Section = Tab:CreateSection("I assume this will be patched soon - due to map update soon")

local Divider = Tab:CreateDivider()

local Button = Tab:CreateButton({
	Name = "SafeHouse",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(162.680023, -94.2610092, 230.036407, 0.999293089, -1.40679939e-08, 0.0375940055, 1.348163e-08, 1, 1.58507891e-08, -0.0375940055, -1.53327555e-08, 0.999293089)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "WorkShop Outside",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(130.923874, -106.07193, -2.17581439, 0.507446766, -0.859753072, -0.0576408654, 0.767467797, 0.481365085, -0.42341572, 0.391779244, 0.170623437, 0.904099941)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "WorkShop Inside",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(169.560654, -103.651337, -30.0143433, 0.262320459, 1.83968858e-08, -0.964980841, 9.02348959e-11, 1, 1.90890379e-08, 0.964980841, -5.09452036e-09, 0.262320459)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Cabin inside",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-324.801575, -88.6199799, 290.675598, 0.451050401, 1.02070366e-07, -0.892498493, -2.45230627e-08, 1, 1.01971303e-07, 0.892498493, -2.41073987e-08, 0.451050401)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Shop",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-111.376678, -87.2069778, 203.522934, -0.851789057, -5.88233995e-08, 0.523884892, -1.06661249e-08, 1, 9.49409156e-08, -0.523884892, 7.5281811e-08, -0.851789057)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "PowerStation",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-208.299744, -110.604126, -120.227615, 0.994857252, -4.01115097e-09, 0.101287208, 1.21101742e-08, 1, -7.9346087e-08, -0.101287208, 8.01646323e-08, 0.994857252)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "WareHouse",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(314.623566, -113.515549, -258.481567, 0.99898839, 1.88050908e-08, -0.0449683107, -1.91088674e-08, 1, -6.32548991e-09, 0.0449683107, 7.17838455e-09, 0.99898839)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Ritual",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-18.6015053, -107.779076, -229.89505, 0.924807549, -7.74951925e-09, -0.380435318, -1.76391968e-09, 1, -2.46580836e-08, 0.380435318, 2.34750388e-08, 0.924807549)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "LeaderBoard",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(45.6568947, -97.9687805, 352.514221, -0.99593854, -2.09143503e-09, -0.0900359452, 1.3530822e-09, 1, -3.81960987e-08, 0.0900359452, -3.8162792e-08, -0.99593854)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Radio Tower",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-402.222595, -112.368164, 44.1699409, 0.0451246351, -1.07376825e-14, -0.998981357, -6.33584847e-08, 1, -2.86195445e-09, 0.998981357, 6.34230872e-08, 0.0451246351)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Teleport Outside Map - safe",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(39.0608749, -99.1718979, 574.259521, 0.907835662, 7.08418568e-08, -0.419326216, -3.53907694e-08, 1, 9.23215708e-08, 0.419326216, -6.89725326e-08, 0.907835662)
		-- The function that takes place when the button is pressed
	end,
})

local Tab = Window:CreateTab("Animation Logger", "folder-archive") -- Title, Image

local Label = Tab:CreateLabel("Try some of these animations that feature 2 players with a friend! to do it, stand directly ontop of eachother (basically the same exact spot) then play it", "contact")

local Label = Tab:CreateLabel("Fun Fact: If you hold Xsaw in ur hand and use a xsaw animation it will also use xsaw in the animation, same with combat knife", "axe")



local Section = Tab:CreateSection("XSaw Interaction Animations")

-- scripting a animation makes me bored

local Button = Tab:CreateButton({
	Name = "ChainStart",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local chainStartAnimation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("XSawInteraction"):WaitForChild("ChainStart")

		playAnimation(chainStartAnimation)

		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "PlayerStart",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("XSawInteraction"):WaitForChild("PlayerStart")

		playAnimation(Animation)

		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "ChainPlayerWin",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("XSawInteraction"):WaitForChild("ChainPlayerWin")

		playAnimation(Animation)

		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "ChainPlayerLose",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("XSawInteraction"):WaitForChild("ChainPlayerLose")

		playAnimation(Animation)

		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "PlayerLose",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("XSawInteraction"):WaitForChild("PlayerLose")

		playAnimation(Animation)

		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "PlayerWin",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("XSawInteraction"):WaitForChild("PlayerWin")

		playAnimation(Animation)

		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Section = Tab:CreateSection("XSawSave Animation")

local Button = Tab:CreateButton({
	Name = "Chain",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("XSawSave"):WaitForChild("Chain")

		playAnimation(Animation)

		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Player",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("XSawSave"):WaitForChild("Player")

		playAnimation(Animation)

		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Section = Tab:CreateSection("Combat Knife Animations")

local Button = Tab:CreateButton({
	Name = "KnifeExecutionPlayer - Bloodmoon thing",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("KnifeExecutionPlayer")

		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "CounterExecutionChain - Chain tryna kill u when u do combatknife",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("CounterExecutionChain")

		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "CounterExecutionPlayer",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
		end

		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("CounterExecutionPlayer")

		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Section = Tab:CreateSection("Bloodmoon animations")

local Button = Tab:CreateButton({
	Name = "BloodmoonExecutionChain",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("HallowChain"):WaitForChild("BloodmoonExecutionChain")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "BloodmoonExecutionVictim",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("HallowChain"):WaitForChild("BloodmoonExecutionVictim")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "BloodmoonTransformChain",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("HallowChain"):WaitForChild("BloodmoonTransformChain")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "BloodmoonTransformChainBM",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("HallowChain"):WaitForChild("BloodmoonTransformChainBM")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Section = Tab:CreateSection("Choke Animations")

local Button = Tab:CreateButton({
	Name = "ChainChokeLose",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("Choke"):WaitForChild("ChainChokeLose")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "ChainChokeStart",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("Choke"):WaitForChild("ChainChokeStart")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "ChainChokeSwing",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("Choke"):WaitForChild("ChainChokeSwing")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "ChainChokeWin",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("Choke"):WaitForChild("ChainChokeWin")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "PlayerChokeLose",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("Choke"):WaitForChild("PlayerChokeLose")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "PlayerChokeStart",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("Choke"):WaitForChild("PlayerChokeStart")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "PlayerChokeWin",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainEssentials"):WaitForChild("Choke"):WaitForChild("PlayerChokeWin")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Section = Tab:CreateSection("Intro Animations (at the start)")

local Button = Tab:CreateButton({
	Name = "Player",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("Intro"):WaitForChild("Player")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Puncher",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("Intro"):WaitForChild("Puncher")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Dragger",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("Intro"):WaitForChild("Dragger")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Passenger",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("Intro"):WaitForChild("Passenger")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Driver",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("Intro"):WaitForChild("Driver")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Divider = Tab:CreateDivider()

local Section = Tab:CreateSection("Some Chain anims")

local Button = Tab:CreateButton({
	Name = "ChainSpawn",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("ChainSpawn")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "DespawnChain",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("DespawnChain")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "DespawnRitual",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("DespawnRitual")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Charge",
	Callback = function()
		local Players = game:GetService("Players")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local localPlayer = Players.LocalPlayer

		local function playAnimation(animationObject)
			local character = localPlayer.Character or localPlayer.CharacterAdded:Wait()
			local humanoid = character:WaitForChild("Humanoid")
			local animator = humanoid:WaitForChild("Animator")
			local animationTrack = animator:LoadAnimation(animationObject)
			animationTrack:Play()
			-- You might want to add a way to stop the animation later
		end

		-- Find the animation object in ReplicatedStorage using the correct path
		local Animation = ReplicatedStorage:WaitForChild("GameStuff"):WaitForChild("Animations"):WaitForChild("Charge")

		-- Play the animation
		playAnimation(Animation)
		-- The function that takes place when the button is pressed
	end,
})



local Tab = Window:CreateTab("Themes", "cloud-fog")

local Section = Tab:CreateSection("Themes if you dont like the one I made / re exec if u want original theme back and also destroy ui")

local Divider = Tab:CreateDivider()

local Button = Tab:CreateButton({
	Name = "Default",
	Callback = function()
		Window.ModifyTheme('Default')
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Amber Glow",
	Callback = function()
		Window.ModifyTheme('AmberGlow')
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Amethyst",
	Callback = function()
		Window.ModifyTheme('Amethyst')
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Bloom",
	Callback = function()
		Window.ModifyTheme('Bloom')
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Dark Blue",
	Callback = function()
		Window.ModifyTheme('DarkBlue')
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Green",
	Callback = function()
		Window.ModifyTheme('Green')
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Light",
	Callback = function()
		Window.ModifyTheme('Light')
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Ocean",
	Callback = function()
		Window.ModifyTheme('Ocean')
		-- The function that takes place when the button is pressed
	end,
})

local Button = Tab:CreateButton({
	Name = "Serenity",
	Callback = function()
		Window.ModifyTheme('Serenity')
		-- The function that takes place when the button is pressed
	end,
})

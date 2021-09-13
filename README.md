# qb-storerobbery
Store Robberies For QB-Core
Edited by Nathan#8860

# Reworked qb-storerobbery
Hit the cash registers to get quick cash (10-20 secs [advanced lockpick], 20-40 secs [lockpick])
10% chance to get a Safe Cracker from hitting the cash registers
You can use the Safe Cracker to trigger the memory game on a 5x5 grid or use the standard 6x6 (I considered this too difficult for a simple store)
3 Minute timer for the safe to open - Configurable in Config.SafeWait
Target options added to the safe for opening and grabbing loot
Uses a circle based lock for the cash registers

# Dependancies
- qb-lock - https://github.com/ArcadiaRoleplay/qb-lock
- memorygame_2 - https://github.com/ArcadiaRoleplay/memorygame_2
- qb-target - https://github.com/BerkieBb/qb-target

# Shared.lua item
	["safecracker"] 			 	 = {["name"] = "safecracker", 			 		["label"] = "Safe Cracker", 			["weight"] = 1000, 		["type"] = "item", 		["image"] = "advancedlockpick.png", 			["unique"] = true, 		["useable"] = true, 	["shouldClose"] = true,	   ["combinable"] = nil,   ["description"] = "Useful for opening strong locks."},

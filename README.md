local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Attrixx/FreeScripts/main/YTUILib1.lua"))():init("incomware.cc | Public")
-- This function takes 1 arguement, the hub name which is meant to be an string
local Tab = Library:Tab("Main")
local Section = Tab:Section("Esp")
Section:Keybind("Chams", "F", function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/VapingCat/Open-Source-Chasms-Script/main/script.lua",true))();
    print("Chams!")
end)
local Section = Tab:Section("Player (UNFINISHED)")
Section:Slider("Walkspeed", 0, 50, 100, function(value)
    print(value)
end)
-- This function takes 5 arguements, the slider name which is meant to be an string,
-- the minimum value which is meant to be an number, the default value which is meant
-- to be an number, the max value which is meant to be an number, and the callback
-- which is meant to be an function, shown in the code above it returns an value
-- which is the current slider value (the script above prints the slider value)
-- This function takes 3 arguements, the keybind name which is supposed to be an string,
-- the default value which is supposed to be an string (key) and the callback which is
-- supposed to be an function, the function has no returns
-- This function takes 3 arguements, the toggle name which is meant to be an string,
-- the default value, true or false / a boolean, the callback which is meant to be
-- an function, the function will have an value (shown in the function above, its printing the value)
	Section:Slider("JumpPower", 0, 50, 100, function(value)
    print(value)
end)
-- This function takes 5 arguements, the slider name which is meant to be an string,
-- the minimum value which is meant to be an number, the default value which is meant
-- to be an number, the max value which is meant to be an number, and the callback
-- which is meant to be an function, shown in the code above it returns an value
-- which is the current slider value (the script above prints the slider value)

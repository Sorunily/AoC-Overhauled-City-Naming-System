# AoC-Overhauled-City-Naming-System
This mod revamps the city naming system!

# Features
- Cities take solely from the last names section of the names JSON. No more "Empire of [X]" or "Republic of [X]" as the name of a city. 
- Razed and rebuilt cities no longer name themselves "New [X]"
- New nations arising from rebellions are no longer always named after their capital. 

# Limitations
- Unfortunately the way this mod works means cities can still be named things like France or Germany if those are in your last names section. Be mindful of this! I'll try to remedy this with a future mod!

## Requirements
- BepInEx 5 x64 (Mono). Download from the official BepInEx releases. https://github.com/bepinex/bepinex/releases

## Install
1. Extract the BepInEx zip into the game folder (next to the exe). Run the game once.
2. Extract **this mod’s zip** into the plugins location so that:
   - BepInEx\plugins\Overhauled City Naming System.dll exists
3. Run the game. Check `BepInEx/LogOutput.log` for "Overhauled City Naming System loaded".

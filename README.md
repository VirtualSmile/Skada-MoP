# Skada for MoP (5.4.8)
My fork of Skada with the parts I liked from "Details!".  
Probably the most accurate combat meter addon for 5.4.8.  
Currently only working on enUS / enGB clients due to lack of translations.  

Please let me know if there are any issues!

# Extras
1. Seperate bar and bar background textures.
2. Seperate class colour toggles for name and data texts.
3. Adjustable update rate between 0.05 and 1. **Note: This does impact cpu-usage.**
4. Smooth texture / bar updates.

# To-Do
1. Identify unit specialisation. This will be hard without third-party libraries (LibInspect) or heavy caching.  
2. Class specialisation icons.
3. Absorb tracking on refreshed auras & damage taken rather than aura removed.

# Help
1. Try disabling ElvUI_AddOnSkins for Skada.  
**ElvUI > Plugins > AddOnSkins > Un-tick Skada**  

2. Try clearing all Skada config files from your WTF folders.  
**WTF > Account > Username > SavedVariables > Skada.lua & Skada.lua.bak**  
**WTF > Account > Username > Realm > Character Name > SavedVariables > Skada.lua & Skada.lua.bak**

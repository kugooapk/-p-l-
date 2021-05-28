"Radar Zoom" for GTA V by LizNet [ver. 2.1] (http://www.gta5-mods.com/scripts/radar-zoom-net/)

This mod is originally designed to be a hotfix for "Satellite View in Radar" by Designerappz (http://www.gta5-mods.com/misc/satelite-view-in-radar)

Toggle key in game is "Z".

This mod works also without the "RadarZoom.ini" file! You can use it if you want to modify zoom settings (see below).

You can contact me by mail: feedback@liznet.tk


----------[ HOW TO INSTALL ]----------

Make sure you have the following mods installed:

- ScriptHook V (http://www.gta5-mods.com/tools/script-hook-v)
- ScriptHook V .NET (http://www.gta5-mods.com/tools/scripthookv-net)

1. Extract "RadarZoom.dll" into the scripts folder in the main directory of your GTA V.
2. You're done. 


----------[ HOW TO MODIFY ]----------

Extract "RadarZoom.ini" into the scripts folder in the main directory of your GTA V if.

In file "RadarZoom.ini" you can find a few settings called:

	1. Enabled (Enables the mod) [Default: true]
	2. toggleButton (Sets button to toggle Radar Zoom) [Default: Z]
	3. onFoot (Sets radar zoom level when walking) [Default: 840]
	4. inBuilding (Sets radar zoom level when inside building) [Default: 1200]
	5. onVehicle (Sets radar zoom level when driving) [Default: 0]
	6. vehSpeed (Sets vehicle speed value when to start zooming out) [Default: 15]
	
You can change those values as you like.


----------[ CHANGELOG ]----------
2.1: Updated toggle button; it's now changeable through the ".ini" file.

2.0: Fully rewritten in C#.
	 Fixed radar to not zooming in while inside building.
	 Added toggle button.
	 
1.0: Release build. 
# Poodmund's Outer Planets Mod - Visual Overhaul

### 1 - About

Pood's OPM-VO is a graphical overhaul modification for Kerbal Space Program's additional planet/moon mod, Outer Planets Mod, that is developed by CaptRobau & Eudae55. Pood's OPM-VO builds upon the OPM mod by adding additional atmospheric and cloud effects using original artwork through the following mods: Environmental Visual Enhancements by rbray89, Scatterer by Blackrack, Module Manager by Sarbian and Kopernicus by Thomas P.

### 2 - Features

- New Gas Giant colour maps
- Cloud layers on Atmosphere bodies
- Scatterer configs for Atmospheric bodies
- Auroras where relevant (to be updated)
- Volumetric cloud layers
- Surface fog/dust
- Heavy, dark Hydrocarbon Seas on Tekto
- Storms on Tekto (planned)
- Sigma OPM-Tilt support for Urlum
- Suggest more!

### 3 - Known Issues

- Scatterer effects when transitioning from orbit to landed do not appear well and will be worked on.
- EVE cloud integration with Scatterer is not functioning correctly and is disabled automatically. This is a known issue with Scatterer when using cloud layers in EVE that are not RGBA 255,255,255,255 and when enabled all EVE cloud layers will render as solid, opaque white.

### 4 - How to Install

Extract the GameData folder found in the downloadable .zip directly into your Kerbal Space Program install directory. If located correctly, the PoodsOPMVO directory should be found at:

Drive:\*\Kerbal Space Program\GameData\PoodsOPMVO

### 5 - Dependencies

The following KSP mods must be installed prior to using PoodsOPMVO for it to function correctly (KSP Forum links attached):

- Module Manager by Sarbian - http://forum.kerbalspaceprogram.com/index.php?/topic/50533-105-m
- Kopernicus by Thomas P - http://forum.kerbalspaceprogram.com/index.php?/topic/103277-105-k
- Outer Planets Mod by CaptRobau & Eudae55 - http://forum.kerbalspaceprogram.com/index.php?/topic/93999-105-o
- Environment Visual Enhancements by rbray89 - http://forum.kerbalspaceprogram.com/index.php?/topic/51142-1
- Scatterer by Blackrack - http://forum.kerbalspaceprogram.com/index.php?/topic/103963-w

### 6 - Optional Mods

- OPM Tilt by Sigma88 - http://forum.kerbalspaceprogram.com/index.php?/topic/122314-1
- Distant Object Enhancement by MOARdv - http://forum.kerbalspaceprogram.com/index.php?/topic/89214-1
- Planetshine by Valerian - http://forum.kerbalspaceprogram.com/index.php?/topic/87012-1

### 7 - Warnings

PoodsOPMVO utilises many very hi-res textures and therefore can increase system RAM usage to the point where it may cause KSP to crash unexpectedly when run through a 32bit launcher (pre KSP v1.1). If running KSP through a 64bit launcher, this should not be an issue if your system has a large amount of system RAM.

### 8 - Changelog

- v0.3.4 - 08th Apr. 17 - Edited Tekto's & Urlums EVE cloud layers slightly, amended SVE integration due to SVE's new file structure and added in Kopernicus' new Ring Shader effects for all bodies (if Jool rings are present, they are maintained). Kopernicus' Ring Shader update is not incorporated in the latest Kopernicus release yet, however, the patch can be downloaded here to be installed into your Kopernicus directory: http://bit.ly/2oQyyt6
- v0.3.3 - 02nd Apr. 17 - Added Sigma OPM-Tilt support. As the base colour-map is effectively a cloud layer, it doesn't render quite right with scatterer though; good enough for now.
- v0.3.2 - 01st Apr. 17 - Forgot to render Tekto's oceans... doh!
- v0.3.1 - 01st Apr. 17 - Fixed scatterer's configs so they play well with other mods and don't repeatedly add OPM body configs to other body's ones.
- v0.3.0 - 30th Mar. 17 - KSP 1.2.2 Compatibility update.
- v0.2.0 - 8th May. 16 - Rebuilt from ground up for KSP 1.1.2; Thatmo work has not been included.
- v0.1.3 - 26th Jan. 16 - Scatterer for Gas Giants supported. Removed KSPRC fix file. Updated cloud configs. 
- v0.1.2 - 11th Jan. 16 - Included support for OPM Tilt and Kopernicus Expansion. Compatibility with KSPRC has been fixed by included updated pqs.cfg file for KSPRC (bundled in distribution).
- v0.1.1 - 8th Jan. 16 - Forgot to include Scatterer files within .zip (Doh!)
- v0.1.0 - 6th Jan. 16 - Initial Release - First GitHub commit & beta release

### 9 - Mini-AVC

This mod includes version checking using MiniAVC. If you opt-in, it will use the internet to check whether there is a new version available. Data is only read from the internet and no personal information is sent. For a more comprehensive version checking experience, please download the KSP-AVC Plugin - http://forum.kerbalspaceprogram.com/index.php?/topic/72169-1.

### 10 - License

Poodmund's Outer Planets Mod - Visual Overhaul is licensed under the All Rights Reserved license, however, any/all other work contained within this distribution is licensed under it's respective owner's license where applicable.

Volumetric cloud particle textures have been included from Environmental Visual Enhancements with express permission from Ryan Bray to be packaged within OPM-VO's own directory structure. Environmental Visual Enhancements is licensed under the MIT License and these textures are subject as such; these textures can be located under the GameData/PoodsOPMVO/Textures/particles path.

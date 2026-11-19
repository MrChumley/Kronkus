# Kronkus
Kronkus planet pack (v1.6.0) for Kerbal Space Program 1.12.x  
REQUIRES Kopernicus and ModuleManager!

This update targets Kerbal Space Program 1.12.x with current Kopernicus
(https://github.com/Kopernicus/Kopernicus, maintained by R-T-B)
and Module Manager (https://github.com/sarbian/ModuleManager).

## Branches
The `master` branch (commit `cb1ef37`) is the preserved legacy edition
of this pack. It is left unchanged. The `ksp-1.12` branch is the
modernized edition for KSP 1.12.x, with current Kopernicus and optional
visual-mod support.

INCLUDES:  
1 Gas Giant  
*Kronkus  

4 Moons  
*Scool
*Meelo
*Eahpeh
*Kersex
  
  https://github.com/MrChumley/Kronkus
  _____________________________________________  
  
Installation:  
To add the Kronkus planet pack to Kerbal Space Program, copy the Kronkus folder into your (KSP directory)/GameData folder.  
  
Requires Kopernicus and Module Manager to work!  
Kopernicus: https://github.com/Kopernicus/Kopernicus  
Module Manager: https://github.com/sarbian/ModuleManager  

Optional (not bundled):
- Environmental Visual Enhancements / EVE-Redux (Blackrack) and the
  Stock Volumetric Clouds V5 pack — Kersex clouds and the Eahpeh
  cryovolcano plume use these if they are installed, and are skipped
  otherwise. Configs only reference V5 textures by path; this pack
  does not bundle any V5 files.
- Scatterer
- Distant Object Enhancement (DOE) — planet colors in celesbod.cfg
- ResearchBodies

KSP forum thread for Kronkus: https://forum.kerbalspaceprogram.com/topic/119202-15x-kronkus-a-kopernicus-planet-pack/
    
  
_____________________________________________  
  
Changelog:

(v1.6.0)
(11-17-2026)
KSP 1.12.x update: removed stale Kopernicus cache files, added a KSP-AVC .version file, and updated documentation links.
Guarded the optional EVE, Distant Object Enhancement, and ResearchBodies configs with :NEEDS so they only load when those mods are installed.
Physics, orbits, atmosphere, biomes, rings, and compatibility patches are unchanged.

(11-18-2026)
Gave Kronkus a Jool template so its scaled-space lighting and terminator are correct.
Added mipmaps to the scaled-space normal maps on Eahpeh, Kersex, Meelo, and Scool to stop map-view shimmer.
Converted the Kersex EVE cloud deck to Blackrack V5 volumetrics (layerRaymarchedVolumeV5) with a 2D orbit fallback. Configs only reference StockVolumetricClouds textures by path; no V5 files are bundled. The layer is skipped if EVE or the V5 stock pack is not installed. Kronkshadows.cfg is unchanged.
Updated Eahpeh's in-game description: the original poster-salesman discovery story is unchanged, and a new paragraph ties its cryovolcano and blue rift to the building of Kronkus's rings.
Added a localized Blackrack V5 cryovolcano plume and rift vapor on Eahpeh. Coverage is painted from the blue features in Eahpeh's own color map and lined up with the Seeping Blue biome. The frost is locked to the surface (speed and detailSpeed are zero, with a 180° longitude offset so EVE matches the Kopernicus color map), tinted an icy lavender to match Kronkus's purple bands, and kept see-through. The main plume is a bit denser than the wispy rift vapor. The layers are skipped if EVE or the V5 stock pack is not installed.

(v1.5)
KSP 1.5.x release.
  
  
supports (not included):  
Distant Object Enhancement https://forum.kerbalspaceprogram.com/topic/205063-ksp-131-distant-object-enhancement-doe-l-under-new-management-21116-2024-0428/  
Galactic Neighborhood http://forum.kerbalspaceprogram.com/threads/128856  
Contract Configurator https://forum.kerbalspaceprogram.com/topic/91625-1101-contract-configurator-v1305-2020-10-05
Environmental Visual Enhancements https://forum.kerbalspaceprogram.com/topic/149733
Scatterer https://forum.kerbalspaceprogram.com/topic/160747

©2015

License: 
12-12-2015  
CC0- Full text @ https://creativecommons.org/publicdomain/zero/1.0/  
To the extent possible under law, MrChumley (KSP forum thread: https://forum.kerbalspaceprogram.com/topic/119202-15x-kronkus-a-kopernicus-planet-pack/) has waived all copyright and related or neighboring rights to "The Kronkus Planet Pack" including Kronkus.cfg, Meelo.cfg, Kersex.cfg, Scool.cfg, Eahpeh.cfg, and associated images. This work is published from: United States.  

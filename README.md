# Grannus-Expansion-Pack

This mod is licensed by Creative Commons Attribution-NonCommercial-NoDerivs
CC BY-NC-ND

## Changelog
## v1.0.0.0

* Made GEP a standalone mod, independent of GPP.
* Added GEP_Primary, including all related configs and revisions.
* Added GEP_CommNet, including all related configs and revisions.
* Added textures for Communotron 7-1000 antenna.
* Added delta-v tables.
* Enabled PlanetShine and EVE eclipses for GEP_Primary.
* Revised Nodens' PQSmods and textures, added islands for PQSCity.
* Revised Belisama's meanAnomalyAtEpoch to improve solar eclipses.
* Revised some in-game descriptions.

## Installation Instructions (with Stock, no GPP)

1. Begin with an installation of KSP version 1.4.3, running in 64-bit.

2. If reusing an existing install, empty the GameData folder of all contents but for the folder [KSP]\GameData\Squad\. If starting with an entirely new install, is it recommended that you run once with no mods installed before proceeding.

3. Download the third party mod [Kopernicus](https://github.com/Kopernicus/Kopernicus/releases/). The Kopernicus version number must match the KSP version number, i.e. 1.4.3-x.

4. Install by copying from [Kopernicus Download]\GameData\ to [KSP]\GameData\ the following folders and files:  
   * Kopernicus
   * ModularFlightIntergrator
   * ModuleManager.3.0.7.dll

5. Download Grannus Expansion Pack v1.0.0.0.

6. Copy from [GEP Download]\GameData\ to [KSP]\GameData\ the folder GEP and all its contents.

## Installation Instructions (with GPP):

1.  Download and install [Galileo's Planet Pack](https://github.com/Galileo88/Galileos-Planet-Pack/releases), version 1.6.3.0 or later. Be sure to carefully follow all the GPP installation instructions. Any dependencies or optional mods required or used by GEP will be installed when you install GPP. It is recommended that you confirm the correct operation of GPP before installing GEP.

2. If you have an existing [KSP]\GameData\GEP folder from a previous installation, delete it. 

3. Download Grannus Expansion Pack v1.0.0.0.

4. Copy from [GEP Download]\GameData\ to [KSP]\GameData\ the folder GEP and all its contents.

## GEP_Primary

1. GEP_Primary is an optional add-on that turns GEP into a primary star system, with Grannus as the central star and Nodens the home world.

2. To use GEP_Primary, first install GEP per the instructions above (with Stock, no GPP).

3. Copy [GEP Download]\Optional Mods\GEP_Primary\GameData\GEP_Primary to [KSP]\GameData\ .

4. If GEP + GEP_Primary is installed in combination with GPP + GPP_Secondary, then GPP is added as a secondary star system orbiting Grannus.

5. GEP_Primary is not recommended for beginner players.

## GEP_CommNet

1. GEP_CommNet is an optional add-on that increases communications range by adding a level 4 Tracking Station and a powerful additional antenna. With both upgrades, a line of communication can reach between Grannus and the Sun/Ciro.

2. To install, copy [GEP Download]\Optional Mods\GEP_CommNet\GameData\GEP\GEP_CommNet to [KSP]\GameData\GEP\ .

## Other Optional Mods

1. Install the optional mods of your choice by copying or merging [GEP Download]\Optional Mods\GEP_[mod name]\GameData\[mod name] to [KSP]\GameData\ .

2. [Final Frontier](https://spacedock.info/mod/580/Final%20Frontier) must be downloaded and installed separately.

## Recommended mods with support for or by GEP

  * Environmental Visual Enhancements
  * Scatterer
  * Distant Object Enhancement
  * Flare Replacer
  * ResearchBodies
  * Final Frontier
  * PlanetShine (GEP_Primary only)
  * Kronometer (GEP_Primary only)

## Known Issues

  * PlanetShine works with GEP_Primary only, otherwise disabled.
  * EVE eclipses work with GEP_Primary only, otherwise disabled.
  * SCANsat day-night terminator works with GEP_Primary only, otherwise it is drawn incorrectly.
  * JX2 Antenna conflicts with GEP_CommNet when OPM is also installed; JX2 is not recommended.
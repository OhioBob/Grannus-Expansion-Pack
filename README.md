﻿![GEP](https://i.imgur.com/FYW1iTU.jpg)
# Grannus Expansion Pack

Grannus Expansion Pack (GEP) is an planet pack that turns a single star system into a binary system by adding the red dwarf star Grannus, along with its family of five major planets, two dwarf planets, and seven moons.

GEP is designed to provide several installation options. It can be added to the stock solar system, Galileo's Planet Pack (GPP), or JNSQ. It also works in combination with Outer Planets Mod (OPM).  And with the optional add-on GEP_Primary, GEP takes center stage as the primary star system, with the planet Nodens as the home world.

## Requirements

  * [Kopernicus](https://github.com/Kopernicus/Kopernicus/releases)
  * ModularFlightIntegrator
  * Module Manager
  
## Installation Instructions

1. Begin with an installation of KSP version 1.12.1 or later, running in 64-bit.

2. If reusing an existing install, empty the GameData folder of all contents but for the folders "Squad" and (if you own DLCs) "SquadExpansion". If starting with an entirely new install, it is recommended that you run KSP once with no mods installed before proceeding.

3. Download the third party mod [Kopernicus](https://github.com/Kopernicus/Kopernicus/releases). The Kopernicus version number must match the KSP version number, e.g. 1.12.1-x.

4. Install by copying/merging the GameData folder from the Kopernicus download to your KSP install.

5. If installing with [Galileo's Planet Pack](https://github.com/Galileo88/Galileos-Planet-Pack/releases) or [JNSQ](https://github.com/Galileo88/JNSQ/releases), it is recommended that you download and install those mods first, and confirm their correct operation before installing GEP. Be sure to carefully follow all the GPP or JNSQ installation instructions.

6. Download Grannus Expansion Pack v1.2.6.

7. Install by copying/merging the GameData folder from the GEP download to your KSP install.

## GEP_Primary

GEP_Primary is an optional add-on that turns GEP into a primary star system, with Grannus as the central star and Nodens the home world. If GEP + GEP_Primary is installed in combination with GPP + GPP_Secondary, then GPP is added as a secondary star system orbiting Grannus. GEP_Primary is not recommended for beginner players.

To install GEP_Primary:

1. Download and install Grannus Expansion Pack per the installation instructions.

2. Drill down to [GEP Download]\Optional Mods\GEP_Primary\ .

3. Copy/merge the GameData folder into your KSP install.

4. For implementation of anomalies, download and install [Kerbal Konstructs](https://github.com/GER-Space/Kerbal-Konstructs/releases).

## GEP_CommNet

GEP_CommNet is an optional add-on that increases communications range by adding a level 4 Tracking Station and a powerful additional antenna. With both upgrades, a line of communication can reach between Grannus and the Sun/Ciro.

To install GEP_CommNet:

1. Download and install the third party mod [Custom Barn Kit](https://ksp.sarbian.com/jenkins/job/CustomBarnKit/).

2. Drill down to [GEP Download]\Optional Mods\GEP_CommNet\ .

3. Copy/merge the GameData folder into your KSP install.

## GEP_Rescale

GEP_Rescale is an optional add-on that rescales the GEP solar system to either 2.5x or 10x its normal size. Rescaling is accomplished without the use of Sigma Dimensions (these mods should never be used in combination with Sigma Dimensions). GEP also works with GPP and/or JNSQ using the appropriate GEP, GPP and JNSQ rescale mods to provide size compatibility.

To install GEP_Rescale:

1. Download and install Grannus Expansion Pack per the installation instructions.

2. Drill down to [GEP Download]\Optional Mods\GEP_Rescale\ and select either Rescale_2.5X or Rescale_10X.

3. Copy/merge the selected GameData folder into your KSP install.

4. If applicable, download and install GPP and/or JNSQ and the appropriate rescale mods per their instructions.

5. Delete the Kopernicus cache, i.e. the *.bin files located within each planet pack's Cache folder.

6. It is recommended that for GEP_Primary at 10x scale the DSN modifier in game difficulty be set to 4.

## Other Optional Mods

Install the optional mods of your choice by drilling down to [GEP Download]\Optional Mods\GEP_[mod name]\ and then copying/merging the GameData folder into your KSP install.

If using [Final Frontier](https://spacedock.info/mod/580/Final%20Frontier), it must be downloaded and installed separately.

## Bundled Mods

Sigma TweakChutes - Changes parachute behavior so that parachutes won't fully deploy unless the minimum pressure for semi-deployment has first been met. Also corrects a bug that allows the deployment pressure to be set below the intended minimum while in flight mode.

Sigma HeatShifter - Required to correctly align minimum and maximum global temperatures to the sun's directional axis for tidally locked atmospheric planets (Toutatis).

## Planet Pack Compatibility

GEP works with the stock solar system, [Galileo's Planet Pack](https://github.com/Galileo88/Galileos-Planet-Pack/releases), [Outer Planets Mod](https://github.com/Poodmund/Outer-Planets-Mod/releases), and [Minor Planets Expansion](https://spacedock.info/mod/2383/Minor%20Planets%20Expansion?ga=%3CGame+3102+%27Kerbal+Space+Program%27%3E) in a variety of configurations, both primary and secondary. Orbits are modified as necessary to assure seamless integration.

GEP also works with [JNSQ](https://github.com/Galileo88/JNSQ/releases) using the optional add-on GEP_Rescale (2.5x version) to match the scale of JNSQ.

## Recommended mods with support for or by GEP

  * [Environmental Visual Enhancements](https://github.com/WazWaz/EnvironmentalVisualEnhancements/releases)
  * [Scatterer, v0.0772](https://spacedock.info/mod/141/scatterer)
  * [Distant Object Enhancement](https://github.com/MOARdV/DistantObject/releases)
  * [ResearchBodies](https://github.com/JPLRepo/ResearchBodies/releases)
  * [Final Frontier](https://spacedock.info/mod/580/Final%20Frontier)
  * [Kerbal Health](https://github.com/GarwelGarwel/KerbalHealth/releases)
  * [Flare Replacer](https://github.com/Galileo88/FlareReplacer/releases)
  * [PlanetShine](https://github.com/prestja/ksp-planetshine/releases) (GEP_Primary only)
  * [Kerbalism](https://github.com/Kerbalism/Kerbalism/releases) (GEP_Primary only)
  * [Kronometer](https://github.com/StollD/Kronometer/releases) (GEP_Primary only)
  * [Kerbal Konstructs](https://github.com/GER-Space/Kerbal-Konstructs/releases) (GEP_Primary only)

## Known Issues

  * PlanetShine works with GEP_Primary only, otherwise disabled.
  * EVE eclipses work with GEP_Primary only, otherwise disabled.
  * SCANsat day-night terminator works with GEP_Primary only, otherwise it is drawn incorrectly.
  * This planet pack is not compatible with Scatterer v0.0825b, use v0.0772.

## License

This mod is licensed by Creative Commons Attribution-NonCommercial-NoDerivs (CC BY-NC-ND)
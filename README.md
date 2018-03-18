  
# PoGoMaps

![Python 2.7](https://img.shields.io/badge/python-2.7-blue.svg) ![License](https://img.shields.io/github/license/RocketMap/RocketMap.svg) [![Build Status](https://travis-ci.org/RocketMap/RocketMap.svg?branch=develop)](https://travis-ci.org/RocketMap/RocketMap)

Live visualization of all the Pokémon (with option to show gyms, raids and PokéStops) in your area. This is a proof of concept that we can load all the Pokémon visible nearby given a location. Currently runs on a Flask server displaying Google Maps with markers on it.

![Map](https://github.com/KetchumMaps/KetchumMaps/blob/master/static/KetchumMaps.png)

## Features:

* Shows Pokémon, PokéStops, raids and gyms with a clean GUI.
* Notifications
* Lure information
* Multithreaded mode
* Filters
* Independent worker threads (many can be used simultaneously to quickly generate a livemap of a huge geographical area)
* Localization (en, fr, pt_br, de, ru, ko, ja, zh_tw, zh_cn, zh_hk)
* DB storage (mysql) of all found Pokémon
* Incredibly fast, efficient searching algorithm (compared to everything else available)

## Information
* [Discord](https://discord.gg/XjUjzmD) for support
* [Documentation](https://rocketmap.readthedocs.io/) for installation and usage docs
* [Github Issues](https://github.com/KetchumMaps/KetchumMaps/issues) for reporting bugs (not for support!)

## Installation

For instructions on how to setup and run the tool, please refer to the project [documentation](https://rocketmap.readthedocs.io).

## Contributions

Please submit all pull requests to [PoGoMaps](https://github.com/KetchumMaps/PoGoMaps/pulls).

Building off [RocketMap](https://github.com/RocketMap/RocketMap).

Discord and front-end use [Iconset](http://www.flaticon.com/packs/packs/pokemon-go/) by [Roundicons Freebies](http://www.flaticon.com/authors/roundicons-freebies/) and [icon](http://www.flaticon.com/free-icon/rocket_178158) by [Flat Icons](http://flat-icons.com/) from [www.flaticon.com](http://www.flaticon.com/). Filters by [Tomballer](https://github.com/tomballgithub/RocketMap) License: CC 3.0 BY can be found [here](http://creativecommons.org/licenses/by/3.0/).


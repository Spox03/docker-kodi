# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2019-02-04

### Changed

* Upgrade to [Kodi 18.0 "Leia"](https://kodi.tv/article/kodi-180)

### Added

* New PVR add-ons
  * [FilmOn](https://kodi.wiki/view/PVR/Backend/FilmOn)
  * [Stalker](https://kodi.wiki/view/Add-on:Stalker_Client)
  * [Teleboy](https://kodi.wiki/view/Add-on:Teleboy_PVR_Client)
  * [WMC](https://kodi.wiki/view/Add-on:PVR_WMC_Client)
  * [Zattoo Box](https://kodi.wiki/view/Add-on:Zattoo_Box)
  

## [1.2.0] - 2018-09-06

### Added

* MediaPortal TV-Server PVR support

### Fixed

* Wrong timezone / timezone can not be set ([#5](https://github.com/ehough/docker-kodi/issues/5))

## [1.1.0] - 2018-05-24

### Added

* PVR support (#4)
* New selection of image tags: `latest`, `pulseaudio`, `alsa`, or `pvr`

### Changed

* Base image is now `ubuntu:bionic` (was `ubuntu:xenial`)
* Ditched `ca-certificates` as it was not needed

## [1.0.0] - 2018-05-15
Initial release.
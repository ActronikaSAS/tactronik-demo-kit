# Changelog

## [0.18.0] - 2019-04-25
### Changed
- Fusion of button import and merge (choose option in modal)

## [0.16.0] - 2019-04-24
### Fixed
- Add delay to get version because hardware need delay

## [0.14.0] - 2018-10-02
### Added
- Automatic management of mode (mode proxy or effect) (depend of avr code)

### Changed
- Change effect to use input instead of sensor raw values

## [0.12.0] - 2018-07-02
### Added
- Link sliders between us (link min/max value of one slider to value of
an other slider)

## [0.10.0] - 2018-04-09
### Added
- Add ability to *import*/*export* effects database
- Add ability to reset database
- Display version of database
- Load first preset available when click on an effect
### Changed
- Create branch `prod` without internal effect

## [0.8.0] - 2018-02-15
### Added
- Activate internal sensor of tactronik when connect
- Update configuration of repository adding `editorconfig` file
### Changed
- Refactor effect library to use enum

## [0.6.0] - 2018-01-16
### Changed
- Update effect library
### Added
- Update unit test to check effect
- Use libsmp and libtup (new API of tactronik)
- Add `/tmp/ttyUSB` as serial port (to snif serial port)
- Display successive frames with two colors
### Fixed
- log if effect is not an effect (bad structure)

## [0.4.3] - 2017-07-10
### Changed
- Update effect library

## [0.4.2] - 2017-06-30
### Changed
- Update effect library
- change url to API documentation
### Added
- Add link to dev.actronika.com in menu
### Removed
- Don't display value of button in button title

## [0.4.1] - 2017-06-28
### Changed
- Update description of effect

## [0.4.0] - 2017-06-26
### Changed
- Update effect library

## [0.4.0-rc] - 2017-06-21
### Added
- Update effects
- Add description of effects
- Add effects
- Add comments on buttons
- Add a debounce on serial
- Ignore case on name search

## [0.3.0] - 2017-06-16
### Added
- Add some effects in internal database
- First version of application

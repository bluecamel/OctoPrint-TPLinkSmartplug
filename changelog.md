# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.5.0] - 2017-09-22
### Changed
- Modified encrypt function to work with hardware version 2 SmartPlugs.

## [0.4.0] - 2017-09-16
### Added
- Added system command options on power on and off.

### Changed
- Modified settings dialog for above additions.
- Converted settings dialog to tabbed interface.
- Updated screenshots.
- Updated readme to add additional settings screenshots.

## [0.3.1] - 2017-09-13
### Added
- Added missing import reference to flask.make_response.

## [0.3.0] - 2017-09-12
### Added
- Incorporated hostname support.  You can now use ip address or hostname.
- Additional debugging logged to separate log file.
- Added processing of M80 and M81 gcode commands.
- Added changelog.md.

### Changed
- Settings dialog updated for additional hostname support and M80/M81 gcode processing.
- Settings screenshot updated for above additions and changes.
- error notification reference on connection error to include hostname in description.
- Increment version in setup.py.

### Removed
- Took out unused css references created by cookiecutter.

## [0.2.0] - 2017-09-06
### Added
- Added error notification popup on unknown status, typically meaning a communication error due to bad ip address.

### Changed
- Updated readme.md and screenshots.
- Increment version in setup.py.

## [0.1.0] - 2017-09-03
### Added
- Initial release.

[0.5.0]: https://github.com/jneilliii/OctoPrint-TPLinkSmartplug/tree/0.5.0
[0.4.0]: https://github.com/jneilliii/OctoPrint-TPLinkSmartplug/tree/0.4.0
[0.3.1]: https://github.com/jneilliii/OctoPrint-TPLinkSmartplug/tree/0.3.1
[0.3.0]: https://github.com/jneilliii/OctoPrint-TPLinkSmartplug/tree/0.3.0
[0.2.0]: https://github.com/jneilliii/OctoPrint-TPLinkSmartplug/tree/0.2.0
[0.1.0]: https://github.com/jneilliii/OctoPrint-TPLinkSmartplug/tree/0.1.0

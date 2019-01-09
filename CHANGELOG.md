# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

-----------------------------------------------------------------------
## [1.2.5] - 2019-01-09

### Changed

- Styling changes to the dashboard template.
- Made the dashboard template the default one for the reporter
- Alternative template added to the `./templates` dir

-----------------------------------------------------------------------

## [1.2.4] - 2019-01-08

### Fixed

- The dashboard template request headers were not turning red if a test failed.

-----------------------------------------------------------------------

## [1.2.3] - 2019-01-08

### Changed

- The templates now display the request body, if the request has one.

-----------------------------------------------------------------------

## [1.2.2] - 2019-01-04

### Added

- Added images of the new dashboard style report to the `README.md` file

-----------------------------------------------------------------------

## [1.2.1] - 2019-01-03

### Added

- Added a new dashboard style report template

-----------------------------------------------------------------------

## [1.2.0] - 2019-01-03

### Added

- Added the ability to display the folder level descriptions on the report

### Changed

- Updated the default template to show the folder level descriptions
- Markdown is now rendered on the HTML page

-----------------------------------------------------------------------

## [1.1.3] - 2018-12-21

### Added

- Travis CI badge to the `README` file

### Changed

- Node v6 build removed from Travis file - No `npm ci` support for that version

-----------------------------------------------------------------------

## [1.1.2] - 2018-12-21

### Added

- Created a `.travis.yml` file and committed the `package-lock.json` file to the repo

-----------------------------------------------------------------------

## [1.1.1] - 2018-12-17

### Added

- Added integration tests for the CLI runner

-----------------------------------------------------------------------

## [1.1.0] - 2018-12-17

### Added

- All the Skipped Tests during the collection run are now part of the individual requests (This has a dependency on Newman Version 4.2.3 or higher)
- Added some integration and repository level tests

### Changed

- Updated the default template to show the skipped tests in the single request summary

-----------------------------------------------------------------------

## [1.0.5] - 2018-12-14

### Fixed

- Updated the default template to fix a pass percentage calculation error

-----------------------------------------------------------------------

## [1.0.4] - 2018-12-13

### Added

- Exposed the skipped tests - Currently, this are still showing as `passed` in the main aggregations though :(

### Changed

- Updated the default template

-----------------------------------------------------------------------

## [1.0.3] - 2018-12-09

### Added

- Included the `moment-helpers` module to give more flexibly about what date format you can choose

### Changed

- Updated the default template

-----------------------------------------------------------------------

## [1.0.2] - 2018-12-07

### Fixed

- Missed a single comma in the `./lib/index.js` file which caused the package to fail :(

-----------------------------------------------------------------------

## [1.0.1] - 2018-12-07

### Added

- Updated the `package.json` file to include more details

-----------------------------------------------------------------------

## [1.0.0] - 2018-12-07

### Added

- Initial Release

-----------------------------------------------------------------------

# Change log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

### Added
### Changed
### Removed

## [0.3.2] - 2020-05-29

### Added
### Changed

- Fix select issues
- Fix the map resize
- Fix campaign and character deletion

### Removed

## [0.3.1] - 2020-05-17

### Added

- Duplicate maps
- In line mode all objects become not selectable
- Using shift in polygon mode will generate lines and stop the polygon mode

### Changed

- Refactor toolbar to display active drawing mode
- Enabling a drawing mode should disable the others
- Save original opacity, visible and selectable

## [0.3.0] - 2020-05-15

### Added

- Line of Sight
- FOW
- Add contextual menu placeholder
- Side bar for the editor

### Changed

- Refactored the Zoom
- Refactored the Map model introducing breaking changes
  - Reseting the existing maps that would break with the new model

## [0.2.1] - 2020-04-28

### Added

- Added better error handling

### Changed

- Fix skills proficiency values & custom bonuses
- Fix dungeon save
- Fix save when using zoom
- Fix issue with skills proficiency

## [0.2.0] - 2020-04-25

### Added

- Send the activation link again
- Create maps in the editor
- Auto save and restore maps when editing them 

## [0.1.1] - 2020-04-23

### Added

- Experimental dungeon builder
- Links to github

### Changed

- Fix a bug where removing a character was not removing it from campaigns

## [0.1.0] - 2020-04-19

### Added

- Authentication
  - Register / Login / Logout
  - Email confirmation on registration
- Campaign management
  - Create a campaign
  - Edit a campaign
  - Delete a campaign
  - Assign characters to a campaign
- Character management
  - Import from DnDBeyond
  - Refresh from DnDBeyond
  - Delete a character
- DM Screen
  - Display a campaign
  - Refresh per character
- Virtual tabletop
  - Multi layers
  - Add images from URL

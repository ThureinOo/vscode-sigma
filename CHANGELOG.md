# Change Log

All notable changes to the "sigma" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.
## [1.5.1]
### Added
- Sigconverter.io codelens
- Some more Snippets (Thanks to @nasbench https://github.com/humpalum/vscode-sigma/pull/16)

### Fixed
- Snippet having to many whitespaces (Thanks to @ThureinOo https://github.com/humpalum/vscode-sigma/pull/14)

## [1.4.1]
### Added
- Readme update
### Fixed
- Results were not properly sorted

## [1.4.0]
### Added
- Sigma Search Engine Integration (Thanks to @ph-T https://github.com/humpalum/vscode-sigma/pull/8)

### Changed
- Updated Attack Map
  
## [1.3.2]
### Fixed
- Duplicate diagnostics now checks case insensitive
- Changed how the sigmac config works (Thanks to @ZikyHD https://github.com/humpalum/vscode-sigma/pull/6)
## [1.3.1]
### Added
- Added more diagnostics
  - YAML parser: Errors will be shown in the editor as diagnostics
  - Started implementing the Tests from the official sigma repo

### Fixed
- Fixed cursor positioning in the auto list completion
## [1.3.0]
### Added
- Compile Rule Codelens
  - Install sigmac (pip install sigmatools)
  - Configure your sigmac compile configs in settings: sigma.compileConfig
  - Click on the codelens in the first line (Compile: kibana)
  - Compiled sigma rule will be in your clipboard

### Changed
- Small bugfixes
## [1.2.1]
### Changed
Readme Cleanup

## [1.2.0]
### Added
- Automatic List Continuation
- 'all' modifier with only one entry - diagnostic

### Changed
- Cleaner adding of Attack Tags
- Added Tabstop in "Detection"-snippet

## [1.1.0]
### Added
- Attack Tag Hover
- Attack Tag Command - Add Attack Tag (sigma.AddTag)
- Attack Tag Codelens

## [1.0.0]
Version 1.0.0!
### Added
- Webextension Support (Quite untested)
## [0.0.4]
### Changed
- Kind of Fixed the Language Problem. Could still be better, See: https://github.com/microsoft/vscode/issues/145659

## [0.0.3]
### Added
- New Icon.
- Provide Diagnostics only for sigma files.
- Some fixes for diagnostics.

## [0.0.2]
### Added
- First Diagnostics!
### Changed
- Fixed some Snippets

## [0.0.1]
Initial commit
### Added
Snippets!
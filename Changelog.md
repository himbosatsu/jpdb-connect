# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- auto_forget option: automatically mark added card as unknown
- open a card in browser by clicking "View added note (alt-v)" after adding it in yomichan
### Fixed
- improve error message when duplicate detection is on


## [0.4.1] - 2022-08-21
### Fixed
- boolean config options are now optional

## [0.4.0] - 2022-08-21
### Added
- auto forq
- auto unlock
### Fixed
- improved login check

## [0.3.0] - 2022-08-14
### Added
- validation of configuration (it will tell you if it can't log in)
- logging with log levels, configurable in config file (for debugging purposes)

### Fixed
- error messages will pop up in yomi chan now 

## [0.2.0] - 2022-07-31
### Added
- rate limit for requests
- configuration file
- added option to automatically add cards to a deck

## [0.1.0] - 2022-07-11
### Added
- open jpdb on the appropriate card in the browser

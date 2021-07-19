# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [unreleased]
### Fixed
- Unhandled $_REQUEST non existed offset
- COU delete with no parent COU or tree structure fails to provision

## [v1.1.2] - 2021-05-27
### Changed
- Manually fire provision

### Fixed
- Handle Whitelisted COUs with children

## [v1.1.1] - 2021-05-21
### Fixed
- Do not sanitize the password

## [v1.1.0] - 2021-05-21
### Added
- Added configuration in order to explicitly make VO Whitelist groups eligible for deletion

## [v1.0.4] - 2020-11-14
### Fixed
- Check if Identifier Model exists

## [v1.0.3] - 2020-11-13
### Fixed
- Activate provisioner when adding admin to a COU through api

## [v1.0.2] - 2020-11-12
### Fixed
- Fix lang texts

## [v1.0.1] - 2020-11-10
### Fixed
- Fix queries for updating MitreId when removing/renaming cous to COmanage

## [v1.0.0] - 2020-10-29
### Added

- Create Entitlements for Users
- Push Entitlements to MitreId when provisioner is activated
- API for getting entitlements

# Changelog

## [Upcoming changes][Unreleased]

## [1.1.0]

### Added
* Improvement to inline authentication documentation

### Changed

* Geocoder results are now inspected for errors and passed to callbacks appropriately even when the status code of the response is 200
* geocoding requests now utilize HTTPS

## 1.0.0

#### Breaking Changes

* FeatureService calls now automatically detect JSON being passed in and no longer require coersion to `String`

[Unreleased]: https://github.com/Esri/geoservices-js/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/Esri/geoservices-js/compare/v1.0.0...v1.1.0

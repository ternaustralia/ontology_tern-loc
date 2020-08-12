# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [0.0.7] - 2020-08-12
### Added
- tern-loc:datum


## [0.0.6] - 2020-06-16
### Added
- tern-loc:depth


## [0.0.5] - 2020-06-02
### Changed
- tern-loc:Point values are now of type data:QuantitativeMeasure. This class allows us to capture the error provided by digital instruments as well as the value. 


## [0.0.4] - 2020-05-19
### Changed
- tern-loc:Point restriction type for tern-loc:altitude, tern-loc:elevation, tern-loc:latitude and tern-loc:longitude from xsd:decimal to xsd:double


## [0.0.3] - 2020-05-13
### Added
- tern-loc:Location rdfs:subClassOf geosparql:Feature


## [0.0.2] - 2020-05-07
### Added
- Added tern-loc:wktLiteral
- Added tern-loc:LineString
### Changed
- OWL restrictions on tern-loc:Point and tern-loc:Polygon - geosparql:asWKT only tern-loc:wktLiteral instead of geosparql:wktLiteral


## [0.0.1] - 2020-05-05
### Added
- Initial release.
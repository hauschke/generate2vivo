# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased] - 2021-05-25
### Added
- Playground for transformations from JSON to RDF.

## [Renamed Project] - 2021-05-25
As new datsources were integrated and the name datacitecommons2vivo was not reflecting
these additions, the repository was renamed generate2vivo and moved to https://github.com/vivo-community/generate2vivo. 
Development will continue there.

## [1.0.0] - 2021-05-25
### Added
- Queries for Datacite Commons (orga2person & person2publication).
- Queries for ROR (organization & organizationPlusChildren).
- Sparql-Generate Pipeline based on config & resources.
- Health Check via spring-boot-starter-actuator.
- Dockerfiles (one relying on local Java setup and one without any dependencies).
- Swagger-UI for all queries available.
- Optional export to VIVO.
- Optional output to JSON-LD.
- Error Handling.
- Log file.
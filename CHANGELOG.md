# Changelog
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]: https://github.com/dkdeploy/dkdeploy-php/compare/master...develop

### Added

- `:ssl_verify_mode` for server properties, which takes SSL verify_mode constants (`OpenSSL::SSL::VERIFY_NONE`)

### Changed

- `Dkdeploy::Php::Helpers::Http::http_get_with_redirect` gets arguments as options hash now

### Fixed

- remove SSL certificate bypassing in http helper #5


## [7.0.0] - 2016-07-01
### Summary

- first public release


[7.0.0]: https://github.com/dkdeploy/dkdeploy-php/releases/tag/v7.0.0

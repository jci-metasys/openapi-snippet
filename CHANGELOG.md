# Changelog

All notable changes to this project that were made by Johnson Controls
will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.14.0-jci3] - 2024-12-13

Adds

- Perform variable substitution in urls of server objects found in
  path and operation objects. This makes for nicer code snippets.

## [0.14.0-jci2] - 2024-09-19

Adds

- Allow for precise control over which parameters show up in code snippets
- Allow for the use of custom code snippet generators by exporting `addTargetClient`
  from httpsnippet

## [0.14.0-jci1] - 2024-06-24

Changes since `0.14.0`:

- Add support for server variables when generating base url for code snippets.

[0.14.0-jci3]: https://github.com/jci-metasys/openapi-snippet/compare/v0.14.0-jci2...v0.14.0-jci3
[0.14.0-jci2]: https://github.com/jci-metasys/openapi-snippet/compare/v0.14.0-jci1...v0.14.0-jci2
[0.14.0-jci1]: https://github.com/jci-metasys/openapi-snippet/compare/v0.14.0...v0.14.0-jci1

# Changelog

All notable changes to this project that were made by Johnson Controls
will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.14.0-jci7] - 2025-10-07

This change updated to a forked version of httpsnippet from jci
so that it and this repo could be run in node 24.

## [0.14.0-jci5] - 2025-05-21

This change only updated the dependencies used by this package.
This resulted in behavior related to how URLs of operations
are interpreted. URLs must be valid. They cannot contain
path parameter placeholders (for example `{id}`). To ensure the
URLs are valid any path parameter should

- In 2.0 spec, include a default for any path parameter. This
  value will be used to replace the placeholder.
- In 3.0 spec, include in the schema an example, examples or
  default value.

Also, due to dependency updates, the target client expected when
calling addTargetClient should be an object with info and convert
members.

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

[0.14.0-jci7]:https://github.com/jci-metasys/openapi-snippet/compare/v0.14.0-jci5...v0.14.0-jci7
[0.14.0-jci5]:https://github.com/jci-metasys/openapi-snippet/compare/v0.14.0-jci3...v0.14.0-jci5
[0.14.0-jci3]: https://github.com/jci-metasys/openapi-snippet/compare/v0.14.0-jci2...v0.14.0-jci3
[0.14.0-jci2]: https://github.com/jci-metasys/openapi-snippet/compare/v0.14.0-jci1...v0.14.0-jci2
[0.14.0-jci1]: https://github.com/jci-metasys/openapi-snippet/compare/v0.14.0...v0.14.0-jci1

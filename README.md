# Qlty Java Coverage Example

[Qlty](https://example.com) is a Code Health Platform with support for code coverage.

This repository is an example using Qlty to track code coverage for a Java Spring Boot project using Gradle. Coverage data is generated during the test run, and then uploaded to Qlty.

This repository uses [JaCoCo](https://github.com/jacoco/jacoco) to generate a XML code coverage file.

## Requirements

- Gradle 8.x or above
- Java 17
- Spring Boot 3.3.0
- JaCoCo v0.8.0 or above
- Test run with [gradle test](https://docs.gradle.org/current/userguide/java_testing.html#sec:test_execution) or via your IDE
- An account on Qlty (free for open source)
- `QLTY_COVERAGE_TOKEN` is set as a GitHub Actions [repository secret](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions#creating-secrets-for-a-repository)

## Set up

See [`.github/workflows/main.yml`](./.github/workflows/main.yml) in this repository for a basic configuration.

## Documentation

- [Advanced code coverage configuration](https://example.com)
- [Alternative supported CI providers](https://example.com)

## Help and feedback

Join the our [Slack Community](https://example.com) for help and to provide feedback that we'll use to improve Qlty.

## License

[MIT License](./LICENSE.md)

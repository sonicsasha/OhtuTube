# OhtuTube
University of Helsinki Software Engineering mini-project Autumn 2022

![workflow badge](https://github.com/smannist/ohtuvarasto/workflows/CI/badge.svg)

### Project [Backlog](https://docs.google.com/spreadsheets/d/10WoYOFuoc0nGcKmTAKLrLbm1TYcGsJvkDpc3olPwmWM/edit?usp=sharing)

### [Test Coverage ](https://github.com/JanneKarki/OhtuTube/blob/main/documents/coverage_28_11.png)of version 1.0

## Releases
[Release 1.0 - Sprint 1](https://github.com/JanneKarki/OhtuTube/releases/tag/Sprint1)

## Definition of Done
- Functionality is integrated to the rest of the software
- User story's acceptance criterias are manually tested
- Code is tested with automated tests
- Test Coverage is over 80% (UI excluded)
- CI-enviroment tests are passed
- Coding style follows best-pracites confirmed by pylint, score over 9

## Installation

The application uses Poetry for dependency management, so it must be installed before running the application.

1. Install required dependencies with the command:
```bash
poetry install
```
2. Initialize the application with the command:
```bash
poetry run invoke build
```
3. And finally run the application with the command:

```bash
poetry run invoke start
```

## Testing
Testing can be performed with the command:

```bash
poetry run invoke test
```

## Test coverage
Test coverage report can be generated with the command:

```bash
poetry run invoke coverage-report
```


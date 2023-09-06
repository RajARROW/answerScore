# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

## [v0.1.0](https://github.com/danieldeutsch/qaeval/releases/tag/0.0.9) - 2021-08-02
### Added
- Added an end-to-end implementation of the metric

## [v0.0.9](https://github.com/danieldeutsch/qaeval/releases/tag/0.0.9) - 2021-06-23
### Fixed
- Added `edlib` to `setup.py` and `requirements.txt`.

## [v0.0.8](https://github.com/danieldeutsch/qaeval/releases/tag/0.0.8) - 2021-06-15
### Added
- Added trying to fix the predicted character offsets using an alignment algorithm
- Added an option to return the QA result as a dict

### Changed
- Refactored the `Scorer` code to be cleaner

### Fixed
- Specifying the spacy version to 2.2.4 in `setup.py`

## [v0.0.7](https://github.com/danieldeutsch/qaeval/releases/tag/0.0.7) - 2021-05-07
### Added
- Added returning approximate character offsets in the context for the QA model's prediction

## [v0.0.6](https://github.com/danieldeutsch/qaeval/releases/tag/0.0.6) - 2021-05-06
### Added
- Added "silent" options for the question generation and answering models

## [v0.0.5](https://github.com/danieldeutsch/qaeval/releases/tag/0.0.5) - 2021-01-02
### Added
- Added scoring predictions with [LERC](https://arxiv.org/abs/2010.03636)

### Changed
- Changed the scoring interface with a breaking change 

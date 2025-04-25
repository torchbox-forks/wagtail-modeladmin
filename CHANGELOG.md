# ModelAdmin Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.3.0] - [UNRELEASED]

- Drop support for Wagtail 5.2, 6.0, 6.1 and 6.2

## [2.2.0] - 2025-04-25

- Wagtail 6.3 and 6.4 support
- Provisional support for Wagtail 7.0
- Django 5.2 support
- Fix `RemovedInWagtail70Warning` deprecation warning about `classnames` kwarg usage when initializing `MenuItem`
- Docs: add [`docs/migrating.md](docs/migrating.md) for detailed instructions on how to migrate your modeladmin code to Wagtail's built-in features
- Maintenance: fix nightly testing against upcoming Wagtail versions

## [2.1.0] - 2024-10-23

### Added

- Wagtail 6.1 and 6.2 support
- Provisional support for Wagtail 6.3
- Django 5.1 support
- Python 3.13 support

### Removed

- Drop Python 3.8 from the testing matrix. The package can still be installed on Python 3.8 to account for Wagtail 5.2 support, but expect this to change when support for Wagtail 5.2 ends in February 2025.

## [2.0.0] - 2024-02-05

### Added

- Provisional Wagtail 6.0 support

### Changed

- Update sphinx-wagtail-theme to 6.2.0 for documentation

### Removed

- Django < 4.2 support
- Wagtail < 5.2 support

## [1.0.0] - 2023-07-26

This is the initial release for the [`wagtail-modeladmin`](https://pypi.org/project/wagtail-modeladmin) package.

The package is nearly identical to the `wagtail.contrib.modeladmin` module and is intended for projects that still rely on ModelAdmin. Documentation is available at https://wagtail-modeladmin.readthedocs.io.

<!-- TEMPLATE - keep below to copy for new releases -->
<!--


## [x.y.z] - YYYY-MM-DD

### Added

- ...

### Changed

- ...

### Removed

- ...

-->

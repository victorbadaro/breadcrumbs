# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [3.3.2] - 2020-04-18
### Fixed
- Fix argument type in the `setDivider()` docblock (#24)

## [3.3.1] - 2020-04-18
### Fixed
- The last breadcrumb shouldn't have `href` microdata if not linked (#23)

## [3.3.0] - 2019-06-07
### Added
- Add the ability to enable the last item to be a link (#22)

### Fixed
- Fix microdata bug on last element (#21)

## [3.2.1] - 2018-01-27
### Fixed
- Fix `composer.json` license identifier
- Document how the `setListItemCssClass()` method can be used

## [3.2.0] - 2017-07-20
### Added
- `setListItemCssClass()` method for configuring a custom CSS class that will be applied to each list item element (#20)

## [3.1.0] - 2016-04-24
### Added
- `add()` alias for `addCrumb()` (#18)
- Ability to chain calls to `addCrumb()` and `add()` (#18)
- Ability to chain calls to `setBreadcrumbs()`, `setCssClasses()`, `addCssClasses()`, `removeCssClasses()`, `setDivider()`, `setListElement()`, `removeAll()`

## [3.0.0] - 2016-03-09
### Added
- Automatic microdata markup support (#15)
    - BC break for too specific CSS styling
    - BC break for users who extended the `Creitive\Breadcrumbs\Breadcrumbs` class while overriding the `renderCrumb()` method (because its arguments have changed)
- Tips on Laravel integration
- Started [keeping a changelog](http://keepachangelog.com/)
- PSR-2
- PSR-4

## [2.0.0] - 2015-03-07
### Added
- Major refactor, making the app framework agnostic (BC break for Laravel users)

### Removed
- Laravel support


## [1.0.8] - 2015-03-07
### Added
- Documentation updates, info on upgrading, deprecation notice


## [1.0.7] - 2015-02-02
### Added
- Class alias so that Laravel's IoC Container can automatically inject the class when type-hinted

## [1.0.6] - 2015-02-02
### Added
- Documentation fixes (#7 and #10)
- The ability to configure the list element used, `<li>` vs. `<ol>` (#10)

## [1.0.5] - 2014-02-16
### Added
- Documentation updates

## [1.0.4] - 2014-02-16
### Added
- `isEmpty()` method
- `removeAll()` method
- Fix for `addCrumb()` and `https` URLs

## [1.0.3] - 2014-02-05
### Added
- `count()` method (#5)

## [1.0.2] - 2013-12-09
### Added
- Support all Laravel 4 versions (#3)

## [1.0.1] - 2013-10-14
### Added
- Support for full URLs

## 1.0.0 - 2013-09-13
### Added
- Initial project release

[Unreleased]: https://github.com/creitive/breadcrumbs/compare/v3.3.2...HEAD
[3.3.2]: https://github.com/creitive/breadcrumbs/compare/v3.3.1...v3.3.2
[3.3.1]: https://github.com/creitive/breadcrumbs/compare/v3.3.0...v3.3.1
[3.3.0]: https://github.com/creitive/breadcrumbs/compare/v3.2.1...v3.3.0
[3.2.1]: https://github.com/creitive/breadcrumbs/compare/v3.2.0...v3.2.1
[3.2.0]: https://github.com/creitive/breadcrumbs/compare/v3.1.0...v3.2.0
[3.1.0]: https://github.com/creitive/breadcrumbs/compare/v3.0.0...v3.1.0
[3.0.0]: https://github.com/creitive/breadcrumbs/compare/v2.0.0...v3.0.0
[2.0.0]: https://github.com/creitive/breadcrumbs/compare/v1.0.8...v2.0.0
[1.0.8]: https://github.com/creitive/breadcrumbs/compare/v1.0.7...v1.0.8
[1.0.7]: https://github.com/creitive/breadcrumbs/compare/v1.0.6...v1.0.7
[1.0.6]: https://github.com/creitive/breadcrumbs/compare/v1.0.5...v1.0.6
[1.0.5]: https://github.com/creitive/breadcrumbs/compare/v1.0.4...v1.0.5
[1.0.4]: https://github.com/creitive/breadcrumbs/compare/v1.0.3...v1.0.4
[1.0.3]: https://github.com/creitive/breadcrumbs/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/creitive/breadcrumbs/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/creitive/breadcrumbs/compare/v1.0.0...v1.0.1

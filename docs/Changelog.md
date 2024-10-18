

  # Changelog for avb-is-me/reflex

## [0.6.3] - 2024-10-18

### Changed
- Updated version to 0.6.3 in pyproject.toml

### Fixed
- Modified `IndividualEventType` in `reflex/event.py` to use `Var[Any]` instead of `Var`

## [0.6.3a4] - 2024-10-18

### Changed
- Updated version to 0.6.3a4 in pyproject.toml

### Added
- Added automatic Redis state manager detection in `reflex/state.py`

### Fixed
- Improved type handling in `foreach` method in `reflex/vars/sequence.py`

## [0.6.3a3] - 2024-10-17

### Changed
- Updated version to 0.6.3a3 in pyproject.toml

### Fixed
- Modified `JavascriptInputEvent` deprecation handling in `reflex/event.py`
- Refactored event handling in multiple components to use `empty_event` instead of `lambda: []`
- Updated event trigger types in various component files

### Added
- Introduced `empty_event` function in `reflex/event.py`
- Added overloaded `__get__` methods for `EventCallback` in `reflex/event.py`

### Improved
- Refactored `LiteralEventVar` and `LiteralEventChainVar` classes for better performance and clarity

### Testing
- Added new test cases for event var data in `tests/units/test_event.py`

## [0.6.3a2] - 2024-10-16

### Changed
- Updated version to 0.6.3a2 in pyproject.toml

This changelog summarizes the main changes in the reflex repository, focusing on version updates, bug fixes, and improvements to event handling and state management. The changes span across multiple components and include both feature additions and code refactoring for better performance and type safety.

  
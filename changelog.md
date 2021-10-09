# Changelog

This is the changelog for the Hilbish shell made in Go and Lua.

## [0.3.0] - 2021-4-5

## [0.2.0] - 2021-3-31

### Added

- Hooks (events) are the new and main thing in v0.2, you can now listen for hooks or cast out (emit) custom ones, via the [bait](https://github.com/Hilbis/Hilbish/wiki/Bait) package
- `^^` to refer to the previous command. It's for the lazy hands like me, so I can do something like `ENV=VAR ^^`
- Way more (more like any) comments in the core code.

### Changed

- Prompt has been changed to have printf-like verbs to format. This makes it easier on the user's side to configure, and doesn't require hooks to change it for things like current directory.
- Default prompt's changed and the triangle changes color based on if command failed or not.

## [0.1.2] - 2021-3-24

### Added

- Add Lua input to history

## [0.1.1] - 2021-3-24

### Added

- Go to new line if sh input is incomplete

```bash
> for i in {1..5}
```

This input for example will prompt for more input to complete:

![input](https://camo.githubusercontent.com/b757e474da5880d57be135087f59f45ab214b8f39f182b299d861cac7b6d84ff/68747470733a2f2f6d6f646575732e69732d696e736964652e6d652f30624456547461352e706e67)

## [0.1.0] - 2021-3-24

### Added

- Tab complete files
- Makefile installation
- sh support

## [0.0.12] - 2021-3-21

First "stable" release of Hilbish.

[0.5.1]: https://github.com/Rosettea/Hilbish/compare/v0.5.0...v0.5.1
[0.5.0]: https://github.com/Rosettea/Hilbish/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/Rosettea/Hilbish/compare/v0.3.2...v0.4.0
[0.3.2]: https://github.com/Rosettea/Hilbish/compare/v0.3.1...v0.3.2
[0.3.1]: https://github.com/Rosettea/Hilbish/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/Rosettea/Hilbish/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/Rosettea/Hilbish/compare/v0.1.2...v0.2.0
[0.1.2]: https://github.com/Rosettea/Hilbish/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/Rosettea/Hilbish/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/Rosettea/Hilbish/compare/v0.0.12...v0.1.0 
[0.0.12]: https://github.com/Rosettea/Hilbish/releases/tag/v0.0.12

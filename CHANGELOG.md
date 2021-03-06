# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)

## [1.0.10] - 2018-03-23

### Changed

- Updated `vscode-icons` to 7.22.0, added 13 new icons  [changelog](https://marketplace.visualstudio.com/items/robertohuertasm.vscode-icons/changelog)

## [1.0.9] - 2018-03-18

### Changed

- Updated `vscode-icons` to 7.21.0 [changelog](https://marketplace.visualstudio.com/items/robertohuertasm.vscode-icons/changelog)

## [1.0.8] - 2018-02-18

### Added

- Support for [gitlab.com](https://about.gitlab.com/)
    - Display icons in Repo Tree
- Support for [bitbucket.org](https://bitbucket.org/)
    - Display icons in Repo Tree
- Support for [pastebin.com](https://pastebin.com/)
    - Display icons in user profile
- Support for [sourceforge.com](https://sourceforge.net)
    - Display icons in project files

### Changed

- Updated `vscode-icons` to 7.19.0, added 25 new icons, read more at vscode-icons [changelog](https://marketplace.visualstudio.com/items/robertohuertasm.vscode-icons/changelog)
- Changed structure of project to be more abstract for several web-based GIT hostings (Github, Gitlab, Bitbucket and Gist) and even for Pastebin

### Fixes

- [Github] no icon for submodule
- [Github] temporally fixed bug with `symlink` files
- [Github] not showing file icons

## [1.0.6] - 2017-10-29

- updated `vscode-icons` to 7.17.0, added 24 new icons, read more at vscode-icons [changelog](https://github.com/vscode-icons/vscode-icons/blob/master/CHANGELOG.md#7170-october-28-2017)
- changed orange logo back to blue one, read more about this change at [vscode blogpost](https://code.visualstudio.com/blogs/2017/10/24/theicon)

## [1.0.5] - 2017-10-24

### Changed

- `vscode-icons` updated to `7.16.0`, added 25 new icons, read more at vscode-icons [changelog](https://github.com/vscode-icons/vscode-icons/blob/master/CHANGELOG.md#7160-october-22-2017)

## [1.0.4] - 2017-10-20

### Changed

- Blue logo to orange one, read more about this change at [vscode blogpost](https://code.visualstudio.com/updates/v1_17#_new-visual-studio-code-logo)
- Name of extension from `vscode-github-icons` to `github-vscode-icons` in chrome store
- Project Structure, now is more readable and better self-explanatory
- Better performance (~25%) thanks to optimizing `getIcons` functions

### Added

- Support for filenames with several extensions like `content.js.map`, `index.test.tsx`, etc
- Opera browser extension
- Loading icon when `vscode-icons` is loading
- Test for *getIcons* functions

## [1.0.3] - 2017-10-10

### Fixes

- Showing light version of icons should work correctly

## [1.0.2] - 2017-10-08

### Fixes

- Icons are now showed properly in github repo tree

### Added

- Travis Support

### Changed

- Default theme for icons is `light` now (before it was `dark`)
- [vscode-icons](https://github.com/vscode-icons/vscode-icons) version changed to `7.15.0`, see [CHANGELOG.md](https://github.com/vscode-icons/vscode-icons/blob/master/CHANGELOG.md)

## [1.0.1] - 2017-10-06

### Added

- Showing icons on `gist.github`
- This changelog file
- `CREDITS.md`

### Changed

- Script is running on proper GH pages (so it'll no trying to render file icons on account settings page)

## [1.0.0] - 2017-10-03

- Initial version

# Changelog

## `0.3.1`

0.3.0 was incorrectly released due to an automation failure, this release fixes
that. No changes were included.

## `0.3.0`

 - Add: JupyterLab 2.0 compatibility

Functional changes were planned for this release, but retracted due to
compatibility issues with JupyterLab 2.0 and will instead ship in a later
release. Minor version bumped to prevent older installs from picking this
version up.

## `0.2.0`

 - Add: JupyterLab 1.1 compatibility

This release includes no functional changes. The minor version was bumped to
prevent 1.0 installs from picking this up erroneously.

## `0.1.0`

 - Chore: JupyterLab 1.0 compatibility

This release includes no functional changes. Minor version was bumped to prevent
existing installs from fetching an incompatible version before a JupyterLab
upgrade.

## `0.0.5`

0.0.4 was incorrectly released, causing issues for end users on *nix platforms.
This release corrected that.

## `0.0.4`

 - Add: Sheet Picker

The sheet picker lives below the sheet, and allows you to switch between sheets
in a workbook.
This was intended for `0.1.0`, but adding row heights will require either a fork
of SlickGrid, or a whole new grid. I don't want to release a UX-breaking change
as a minor release, so this got bumped up.

## `0.0.3`

 - Fix: Row Indexing starts at 1 (#4)
 - Fix: Model indexing left off last row and column
 - Add: Cell Merges

The grid now supports cell merges! Merges work horizontally, vertically, or
both.

## `0.0.2`

 - Bugfix release: add keywords to NPM registry

This was released shortly after 0.0.1, and added community-standard keywords
to make this plugin discoverable.

## `0.0.1`

 - Initial release.
# Changelog

Before tagging a release, move the notes from `[Unreleased]` to a heading such as
`## [1.2.0]`. Use that section as the GitHub release body. The publishing
workflow reads the same section from the tagged commit for JetBrains Marketplace.

## [Unreleased]

## [1.2.1]

### Fixed

- Fixed a visible seam in the main toolbar when project colors are enabled in IntelliJ IDEA 2026.3 with Lotus Copper Light or Lotus Iridium Light.

## [1.2.0]

### Added

- Added Lotus Copper and Lotus Iridium in Light, Dark, and Midnight. Each has its own UI palette and syntax colors for keywords, types, declarations, and constants.
- Added Lotus Midnight for a near-black editor. Lotus Dark now uses a lighter charcoal editor and window frame.

### Changed

- Shortened the names in the theme picker, including Lotus Light, Lotus Dark, and Lotus Midnight.
- Applied each palette’s accent to switches, search, progress, and drag-and-drop states. Refined keyboard focus and inactive selections.
- Improved the contrast of comments and syntax on search matches and diff lines. Refined selections and breadcrumbs in Lotus Light.

### Fixed

- Restored consistent outlines on dropdowns and spinners and visible island borders in Copper Light and Iridium Light.

## [1.1.4]

- Improved Light syntax contrast, diagnostics, search highlights, version control colors, and inline hints.
- Refined borders, focus indicators, selections, and disabled controls in both themes.
- Improved tooltip, shortcut, and secondary-label readability.
- Fixed unintended bold styling on instance fields and additional syntax elements in Light.

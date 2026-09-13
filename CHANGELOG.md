# Changelog

## 1.1.1

- Removed the unsupported `description` field from `manifest.json`. Theme manifests do not support it; that field is plugin-only.
- Removed a `:has()` selector from the inactive pane fade, flagged as a performance risk by Obsidian's own theme scanner. Focusing a sidebar now dims every pane instead of only the ones not genuinely focused; see the Limits section in the README.

## 1.1.0

- Added a palette picker. Choose Flexoki, Penumbra, or Tailwind CSS for the heading colors, callout colors, and the active-pane accent.
- Added palette-driven colors for callouts.
- Added an optional accent tint for tags.
- Added an optional background wash for the active pane.

## 1.0.0

Initial release.

- Focal colors headings H1 through H6 with the Flexoki palette. The colors work in light mode and in dark mode.
- Focal adds an accent to the active tab in the focused pane. Choose a bar, a tint, a solid fill, or text only.
- Focal can dim inactive panes. This effect is optional.

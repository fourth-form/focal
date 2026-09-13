# Focal

Focal is a minimal theme for Obsidian. Focal keeps the layout and the colors of the Default theme. Focal adds three visual effects.

## Use

Focal adds these effects:

- **Headings.** Focal colors headings H1 through H6 with the Flexoki palette. The colors work in light mode and in dark mode. By default, the note title stays a plain color, so the title reads as a file name, not as a heading.
- **Active pane.** Focal adds an accent to the tab in your active pane. Choose a bar under the tab, a tinted fill, a solid fill, or text only.
- **Inactive pane fade.** This effect is optional. It dims the content of panes that are not active.

You can change these effects with the Style Settings plugin. Without Style Settings, Focal uses its default colors and choices.

## Install

Obsidian's Community Themes list does not yet include Focal. Until then, install Focal by hand:

1. Go to the [latest release](https://github.com/fourth-form/focal/releases/latest).
2. Download `manifest.json` and `theme.css`.
3. In your vault, create the folder `.obsidian/themes/Focal/`.
4. Copy both files into that folder.
5. Restart Obsidian.
6. Open Settings → Appearance → Themes. Select **Focal**.

## Limits

Focal needs Obsidian 1.4.0 or later. The tinted active-tab fill uses the CSS function `color-mix()`, which needs this version. Focal has been tested on macOS only; Windows and mobile are not yet tested. To change colors and toggles beyond the defaults, install the Style Settings plugin.

## Privacy

Focal does not send data over the network. Focal does not collect usage data. Focal does not read your notes. Focal does not write files in your vault. Focal changes only the visual style of Obsidian.

## Develop

Focal is plain CSS with no build step. To change Focal, edit `theme.css` directly.

## License

Focal uses the MIT license. See [LICENSE](LICENSE).

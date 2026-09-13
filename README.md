# Focal

A minimal Obsidian theme. Leaves the Default theme's layout and colors alone; adds three things.

## Use

- **Headings**: H1 through H6 colored with the Flexoki palette, light and dark aware. The inline note title stays neutral by default, so it reads as a filename, not a heading.
- **Active pane**: the tab in your focused pane gets an accent, as a bar under the tab, a tinted fill, a solid fill, or text only.
- **Inactive pane fade**: optional, dims the content of panes that don't have focus.

All three are configurable through the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin. Without it, the defaults above still apply.

## Install

Manual install until this is listed in Obsidian's Community Themes:

1. Download `manifest.json` and `theme.css` from the [latest release](https://github.com/fourth-form/focal/releases/latest).
2. Create `.obsidian/themes/Focal/` inside your vault and copy both files into it.
3. Restart Obsidian and select **Focal** in Settings → Appearance → Themes.

## Limits

Requires Obsidian 1.4.0 or later (the tinted active-tab fill uses `color-mix()`). Tested on macOS; Windows and mobile are not yet tested. Configuring colors and toggles beyond the shipped defaults requires the Style Settings plugin.

## Privacy

No network requests, telemetry, note-content access, or vault-file writes. Focal changes visual styling only.

## Develop

Plain CSS, no build step. Edit `theme.css` directly.

## License

[MIT](LICENSE)

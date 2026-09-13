# Working on Focal

These instructions apply throughout this repository. Follow the user's explicit task instructions and preserve unrelated work.

## Purpose

A minimal accent theme on top of Obsidian's Default look. Solve this with the smallest understandable CSS. Every rule, variable, and settings entry should serve a concrete visual effect the user asked for.

## Behavioral contract

- Everything not explicitly restyled must render exactly as Obsidian's Default theme.
- Every color and toggle must work from its hardcoded default with the Style Settings plugin disabled.
- Disabling Focal (switching to another theme) must leave the vault and its notes unchanged.
- Do not read note content, write vault files, add telemetry, or make network requests. It is CSS; it has no such access to begin with, keep it that way.
- Keep limits explicit. Do not claim support for platforms or Obsidian versions that have not been checked.

## Implementation

- Read `theme.css` before changing behavior; it is the only stylesheet.
- Group related rules under a comment header naming the feature (Headings, Active pane, ...). Keep each feature's variables, defaults, and rules together.
- Prefer Obsidian's existing CSS variables over new selectors. Add a new class or variable only for a demonstrated need.
- Keep the `@settings` block (Style Settings) in sync with the variables and classes it exposes; every setting must have a working hardcoded default alongside it.

## Verification

- After a change, load the theme in a real vault (Settings → Appearance → Themes → Focal) and check both light and dark mode.
- Check the change with Style Settings both installed and not installed.
- Check panes and tabs in a split, not just a single pane, for anything touching active/inactive state.

## Writing

- Use familiar words, short explanations, and concrete visual descriptions. Document purpose, usage, installation, limits, privacy, then development.
- Keep user instructions separate from implementation details. Update documentation when behavior changes.
- Do not add personal names, machine paths, conversation history, AI attribution, generated-by credits, or promotional author bylines to documentation or release text.
- Retain author metadata, functional repository links, and required license notices. Do not fabricate authorship or remove required third-party attribution.
- Avoid unsolicited co-author trailers. Use the project's configured public identity for commits and never infer it from a machine username.

## Releases

- Keep experiments local or private; publish reviewed release snapshots.
- Version changes and publication must fall within the user's requested task. Existing explicit authorization is sufficient; do not repeatedly ask for approval.
- Before publication, check staged files and commit metadata for private data and unintended history. Never rewrite published history without explicit authorization.
- Keep manifest, changelog, release tag, and release assets consistent.
- Report GitHub publication and Obsidian directory acceptance separately. A submission is not an accepted listing.

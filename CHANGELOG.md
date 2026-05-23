# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2026-05-23

### Added
- Accent palette (`accents`) with six rainbow indicator colors for tabs and indent guides
- Git status colors (`git.added`, `git.modified`, `git.deleted`, `git.untracked`, `git.ignored`, `git.conflicting`, `git.submodule`)
- Diff highlight backgrounds (`diff.inserted.background`, `diff.removed.background`)
- Editor cursor color, editor selection color, and active/modified/deleted/added gutter indicators
- Tab and panel active borders (`tab.active.border_top`, `panel.title.active.border`) and debug status bar color
- Predictive (inline suggestion) color, search match highlight, and hint styling
- Full icon color set (`icon`, `icon.muted`, `icon.disabled`, `icon.placeholder`, `icon.accent`)
- Text variants: `text.link`, `text.link.active`, `text.error`, `text.placeholder`, `text.accent`
- Scrollbar shadow and active thumb background
- Terminal foreground color
- Expanded syntax coverage: function/method variants (`function.method`, `function.macro`, `method`, `macro`, `constructor`), keyword variants (`keyword.control`, `keyword.operator`, `keyword.directive`, `keyword.function`, `keyword.return`), variable variants (`variable.parameter`, `variable.member`, `variable.special`, `variable.builtin`, `parameter`, `property`, `field`), type variants (`type.builtin`, `type.parameter`, `struct`, `variant`, `trait`, `builtin_type`), numeric variants (`float`, `unit`), string variants (`string.escape`, `string.special`, `string.special.symbol`, `string.regex`, `regexp`, `character`), markup tokens (`markup.heading`, `markup.bold`, `markup.italic`, `markup.link`, `markup.raw`, `markup.list`, `text.title`, `text.uri`, `text.reference`), punctuation variants (`punctuation.bracket`, `punctuation.delimiter`, `punctuation.list_marker`, `punctuation.special`, `punctuation.attribute`, `punctuation.macro`), and miscellaneous (`annotation`, `attribute.builtin`, `attribute.macro`, `function.special`, `comment.documentation`, `modifier`, `preproc`, `preprocessor`, `label`, `builtin`, `tag.attribute`, `embedded`, `emphasis`, `control`)

### Changed
- Theme schema upgraded from v0.1.0 to v0.2.0
- Syntax palette retuned to match VSCode Dark+ more closely (keywords `#569CD6`, types `#4EC9B0`, variables `#9CDCFE`, constants `#4FC1FF`, numbers `#B5CEA8`, regex `#D16969`)
- Surface colors aligned to GitHub Dark UI (`elevated_surface`, `surface`, `tab_bar`, `panel`, `drop_target`)
- Status colors updated: `created` `#56d364`, `modified` `#e3b341`, `error` `#f85149`, `warning` `#f0883e`, `success` `#238636`
- Editor selection (`#264F784D`) and foreground (`#D4D4D4`) tuned for readability
- Renamed `scrollbar_thumb.background` to `scrollbar.thumb.background` to match the v0.2.0 schema
- Replaced legacy `extension.json` with `extension.toml`

### Removed
- `extension.json` (superseded by `extension.toml`)

[0.1.0]: https://github.com/napalmpapalam/napalm-theme-zed/compare/0.0.2...0.1.0
[0.0.2]: https://github.com/napalmpapalam/napalm-theme-zed/releases/tag/0.0.2

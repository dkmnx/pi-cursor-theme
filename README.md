# pi-cursor-theme

A Cursor-inspired dark theme for the pi coding agent.

**Inspiration:** Based on the [Cursor theme] from the [opencode] project.

[Cursor theme]: https://github.com/anomalyco/opencode/blob/dev/packages/opencode/src/cli/cmd/tui/context/theme/cursor.json

[opencode]: https://github.com/anomalyco/opencode

## Installation

Install from npm:

```bash
pi install npm:pi-cursor-theme
```

Or install from git:

```bash
pi install git:github.com/dkmnx/pi-cursor-theme
```

## Theme Preview

The `cursor-dark` theme features a carefully balanced color palette inspired by
Cursor's dark mode, optimized for readability in the pi TUI interface.

### Color Palette

| Name       | Color     |
| ---------- | --------- |
| Background | `#181818` |
| Panel      | `#141414` |
| Element    | `#262626` |
| Foreground | `#e4e4e4` |
| Muted      | `#888888` |
| Border     | `#333333` |

### Accent Colors

| Name         | Color     |
| ------------ | --------- |
| Cyan         | `#88c0d0` |
| Blue         | `#81a1c1` |
| Green        | `#3fa266` |
| Green Bright | `#70b489` |
| Red          | `#e34671` |
| Red Bright   | `#fc6b83` |
| Yellow       | `#f1b467` |
| Orange       | `#d2943e` |
| Pink         | `#E394DC` |
| Purple       | `#AAA0FA` |
| Teal         | `#82D2CE` |

## Usage

After installation, use the theme by passing it to pi:

```bash
pi --theme cursor-dark
```

To make it default, use the `/settings` command and select the theme.

Or add it directly to `~/.pi/agent/settings.json`:

```json
{
  "theme": "cursor-dark"
}
```

Or use `pi config` to enable it interactively:

```bash
pi config
```

Then use `space` to toggle the cursor-dark theme.

## License

[MIT](LICENSE)

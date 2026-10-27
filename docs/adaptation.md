# Adaptation notes

This package uses the Xcode Classic (Dark) and Xcode Classic (Light) pair from Mateo Cerquetella's community VS Code port. The project lists both as native variants and uses Xcode's editor and syntax colors. It is an open-source community port, not an Apple-published theme pack; its pinned 5.2.0 package metadata and MIT license identify Mateo Cerquetella as author.

## Sources

- Classic Dark: https://github.com/MateoCerquetella/xcode-theme/blob/6e5fa872e0c60e5a58908c85d02a5ac13c482dd7/themes/Xcode%20Classic%20Dark.json
- Classic Light: https://github.com/MateoCerquetella/xcode-theme/blob/6e5fa872e0c60e5a58908c85d02a5ac13c482dd7/themes/Xcode%20Classic%20Light.json
- Package metadata: https://github.com/MateoCerquetella/xcode-theme/blob/6e5fa872e0c60e5a58908c85d02a5ac13c482dd7/package.json (version 5.2.0)
- License: https://github.com/MateoCerquetella/xcode-theme/blob/6e5fa872e0c60e5a58908c85d02a5ac13c482dd7/LICENSE

## Mapping decisions

- The dark canvas (#1f1f24) follows the installed Codex Xcode Dark reference; foreground (#DFDFE0), link (#6699FF) and key accents are adapted from the upstream Classic Dark theme.
- Classic Light supplies syntax and UI colors; its VS Code definition omits `editor.background`, so the Tine canvas is explicitly mapped to white. Other tiers use its declared #F5F5F5 and #EEF5FE surfaces.
- Selection, inline code, marks and other supported roles map to Tine's 21-color API. Fonts, task markers, Xcode editor chrome and syntax-specific scopes are outside this package.
- No Apple or Codex program code or assets are included.

## Local validation

See the [local check summary](local-check.md) for the exact tested combinations and current manifest digest. User screenshots and full Tine interaction acceptance are pending.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.

Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.

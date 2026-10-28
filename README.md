<div align="center">

# Xcode · Prism

**A blue note rests on graphite; morning opens the same page in clean white. Let the quiet colors make room for thought.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-6699ff?labelColor=292a30)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-6699ff?labelColor=292a30)
[![License: MIT](https://img.shields.io/badge/license-MIT-6699ff?labelColor=292a30)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-xcode-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-xcode-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-xcode-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

Xcode Classic Light and Dark share one Tine theme: clean white for day and soft graphite for night, with the familiar blue links and measured syntax colors of the Xcode palette.

Explore the full [Prism theme gallery](https://github.com/martinkoutecky/tine/discussions/786) to compare all 29 themes in light and dark modes.

### Dark mode

![Xcode · Prism in Tine dark mode](docs/xcode-dark.png)

### Light mode

![Xcode · Prism in Tine light mode](docs/xcode-light.png)

*Actual Windows Tine screenshots supplied after testing. Both palettes are included in this package.*

## Install

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-xcode-prism/releases/latest/download/theme.json).
2. In Tine, open **Settings → Appearance → Theme packages → Select theme.json** and select the downloaded file.
3. Choose **Use colors**, then select **Light**, **Dark** or **System** mode.

Requires Tine Theme API **0.2** support. Existing `logseq/custom.css` and device accent settings may affect the result. This package supplies colors only; typography, layout, task markers and other roles outside the theme API remain host-controlled.

## Palette

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#FFFFFF` | `#1f1f24` |
| Sidebar | `#F5F5F5` | `#282831` |
| Body | `#282828` | `#DFDFE0` |
| Heading | `#282828` | `#FFFFFF` |
| Accent | `#3C93FD` | `#007AFF` |
| Links | `#0066CC` | `#6699FF` |
| Tags | `#4B21B0` | `#FF7AB2` |
| Mark background | `#FFF1B8` | `#454238` |

## Tested in Tine

The manifest passed the official theme checker. A Chromium fixture checked both complete token sets, mode switching and specified contrast pairs. The user supplied the real Windows light/dark screenshots above using Tine's public welcome graph. The visible headings, body, outlines, links, tags, inline code and reference panels are shown; mark highlights, selection behavior, Settings and other platforms are not established by these images. See [screenshot notes](docs/screenshots.md).

## Source and scope

Based on [Xcode Classic (Light / Dark)](https://github.com/MateoCerquetella/xcode-theme) at `6e5fa872e0c60e5a58908c85d02a5ac13c482dd7`, under MIT; see [LICENSE](LICENSE). Both modes are based on the Classic Light and Classic Dark color themes in Mateo Cerquetella's open-source Xcode palette port. They are native paired variants in that community project; this package maps their editor colors to Tine's 21-color API.

Independent community adaptation by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`). No Codex program code, logo or bundled assets are included. No affiliation or endorsement is claimed.

Only the 21 supported literal color roles per mode are packaged. It does not claim pixel-for-pixel reproduction of Codex, or that all Tine-derived and opacity-dimmed text meets a contrast target. Check results and actual application coverage are recorded in [adaptation notes](docs/adaptation.md).

## Feedback

[Open an issue](https://github.com/EllisMorrow/tine-theme-xcode-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content. The download badge counts GitHub Release asset downloads, not installations or unique users.

# Xcode · Prism

**一枚蓝色音符落在石墨上，清晨则把同一页翻成洁白。让安静的颜色，为思绪留出空间。**

[![发行附件下载量](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-xcode-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-xcode-prism/releases)

[English](README.md) · [下载 theme.json](https://github.com/EllisMorrow/tine-theme-xcode-prism/releases/latest/download/theme.json)

Xcode Classic Light 与 Dark 汇入同一套 Tine 主题：白日清爽洁白，夜晚柔和石墨，并延续 Xcode 配色中熟悉的蓝色链接与克制的语法色彩。

### 深色模式

![Xcode · Prism 深色模式实拍](docs/xcode-dark.png)

### 浅色模式

![Xcode · Prism 浅色模式实拍](docs/xcode-light.png)

*用户测试后提供的 Windows 实机截图，两套配色均实际包含在同一个主题包中。*

## 安装

1. 下载 [theme.json](https://github.com/EllisMorrow/tine-theme-xcode-prism/releases/latest/download/theme.json)。
2. 在 Tine 打开 **设置 → 外观 → 主题包 → 选择 theme.json**，选择下载的文件。
3. 点击 **使用颜色**，选择 **浅色、深色或跟随系统**。

需要主题 API **0.2** 支持。原有 `logseq/custom.css` 和设备强调色可能影响效果；主题只负责 API 支持的颜色，不包含额外字体、布局或任务标记样式。

## 配色

| 角色 | 浅色 | 深色 |
| --- | --- | --- |
| 主背景 | `#FFFFFF` | `#1f1f24` |
| 侧栏 | `#F5F5F5` | `#282831` |
| 正文 | `#282828` | `#DFDFE0` |
| 标题 | `#282828` | `#FFFFFF` |
| 强调色 | `#3C93FD` | `#007AFF` |
| 链接 | `#0066CC` | `#6699FF` |
| 标签 | `#4B21B0` | `#FF7AB2` |
| 高亮底色 | `#FFF1B8` | `#454238` |

## 验证情况

通过官方主题格式检查；浏览器样例检查了两套完整变量、模式切换及指定颜色组合。用户提供了上方 Windows 明暗实机截图，展示公开欢迎页面上的标题、正文、层级、链接、标签、行内代码和引用区域。高亮、选中操作、设置状态和其它平台未由这些截图覆盖，不据此宣称全部路径均已验证。

## 来源与边界

基于 [Xcode Classic (Light / Dark)](https://github.com/MateoCerquetella/xcode-theme)，固定版本 `6e5fa872e0c60e5a58908c85d02a5ac13c482dd7`，采用 MIT 许可；详见 [许可说明](LICENSE)。两种模式均基于 Mateo Cerquetella 开源 Xcode 配色移植项目中的 Classic Light 与 Classic Dark。它们是该社区项目的原生明暗配对；本包将编辑器颜色映射到 Tine 的 21 色 API。

独立社区适配由 EllisMorrow 完成，使用 AI 辅助开发。不分发 Codex 程序代码、标志或附带资源，不代表相关项目或 OpenAI 的官方产品，也不承诺与 Codex 像素级一致。具体映射和验证边界见 [适配说明](docs/adaptation.md)。

顶部徽标统计 GitHub Release 附件累计下载量，不代表安装人数。可在本仓库反馈问题，附版本、系统、模式及不包含私人内容的截图。

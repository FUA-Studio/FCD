# FCD · FUA CODE

<p align="center">
  <b>FUA Studio 出品的 AI 编码代理</b><br>
  <sub>读写代码 · 执行命令 · 操控电脑 · MCP 扩展 · 多模型自由切换</sub>
</p>

<p align="center">
  <img src="fcd.ico" alt="FCD" width="96">
</p>

<p align="center">
  <img alt="platform" src="https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-0078D6">
  <img alt="latest" src="https://img.shields.io/badge/latest-0.1.3-success">
  <img alt="license" src="https://img.shields.io/badge/license-Proprietary-lightgrey">
</p>

## 中文

FCD 是一款 AI 编码代理：它能阅读代码、修改文件、运行命令、调试与构建，像一位随叫随到的工程搭档。

### 能力

| 能力 | 说明 |
| --- | --- |
| 读写代码 | 读取、创建、精准编辑项目中的任意文件，自动搜索与定位 |
| 执行命令 | 运行构建、测试、安装等 shell 命令，并解读输出 |
| 真流式回复 | 逐字实时输出，不必等整段生成完 |
| 操控电脑 | 截屏、移动鼠标、点击、键入、管理窗口、操作剪贴板 |
| MCP 扩展 | 通过 Model Context Protocol 接入 Blender、Ghidra、IDA、Wireshark 等 |
| 多模型 | 内置 3 款免费模型开箱即用，也支持任意 OpenAI 兼容服务的 Key |

### 下载

**推荐**从 [Releases](https://github.com/FUA-Studio/FCD/releases/latest) 下载最新版（当前 `0.1.3`）：

| 文件 | 平台 | 说明 |
| --- | --- | --- |
| `FCD-Setup.exe` | Windows | 一键安装，含 CLI 与桌面版 |
| `fcd.exe` | Windows | 命令行版，单文件免安装 |
| `fcd-desktop.exe` | Windows | 原生桌面窗口版，无浏览器依赖 |
| `fcd-desktop-pro.exe` | Windows | Pro 桌面版（仅 0.1.3 Release 提供） |
| `FCD-0.0.1.apk` | Android | 移动端 |
| `fcd.elf` | Linux x86-64 | 纯命令行版，需系统 python3 |
| `fcd.ico` | — | 应用图标 |

仓库根目录也保存了一份 `0.1.3` 的同名文件，便于直接取用；
**长期使用请以 Releases 为准**，根目录副本会在下一个版本发布时同步更新。

### 三步开始

1. 运行 `FCD-Setup.exe`，选择安装目录（建议非系统盘）。
2. 启动后选择一个内置免费模型。
3. 直接输入需求，例如「帮我看下这个项目的结构」。

无需注册、无需配置，首次启动即可用。内置免费 API 有使用时长限制，
长期使用请换成自己的 API Key。

### 界面

CLI：

![CLI](https://github.com/user-attachments/assets/f4835873-47a5-4f1a-90d3-d29c16952854)

桌面版：

![Desktop](https://github.com/user-attachments/assets/c6161dad-e732-4f0f-9444-9b93f59a8253)

### 版本归档

| 位置 | 内容 | 说明 |
| --- | --- | --- |
| [Releases](https://github.com/FUA-Studio/FCD/releases) | 每个版本的完整安装包与单文件 | **正式发布渠道**，按标签区分 stable / pre-release |
| 仓库根目录 `0.0.4PT/` … `0.1.3S/` | 各版本的构建产物留存 | 版本号后缀含义见下方说明 |

各版本目录内的说明（取自当时的版本说明）：

| 目录 | 版本性质 | 备注 |
| --- | --- | --- |
| `0.0.4PT` | 首个公测版 | 内置免费 API 有 6 小时限制 |
| `0.0.6PT` | 公测版 | 修复 12 类已知问题，命令有新增 |
| `0.0.7-P` | 公开版 | 首次支持 Android（仍待测试） |
| `0.0.8S` | 稳定版 | 修复桌面端无法启动；建议优先使用 |
| `0.0.9S` | 稳定版 | UI 大改；该版本曾因功能问题未全部上传 Release |
| `0.1.0S` | 首个大版本 | 明透玻璃 UI 上线 |
| `0.1.1S` | 稳定版 | FUA Workflow（FWF）正式上线；`/adm auto` 改为独立审批 Agent |
| `0.1.2S` | 稳定版 | OpenRouter 归因头对齐 |
| `0.1.3S` | 稳定版 | FWF 同模型可身兼数职；桌面端接入 `/fwf` |

> 目录后缀：`PT` 公测、`S` 稳定、`-P`/`PREVIEW` 预览；最新稳定版以 **Releases** 为准。

### 数据与隐私

配置、会话与用量数据都保存在安装目录的 `data` 文件夹内，便携可迁移；
仅在当前用户注册表写入卸载信息，随时可用卸载器彻底清除。

## English

**FCD (FUA CODE)** is an AI coding agent by FUA Studio. It reads and edits code, runs shell
commands, debugs and builds — a pair programmer that is ready when you are.

- **Code** — read, create and precisely edit any file in the project, with search and navigation.
- **Commands** — run build, test and install commands and interpret the output.
- **Streaming** — token-by-token output instead of waiting for the full answer.
- **Computer control** — screenshot, move the mouse, click, type, manage windows, use the clipboard.
- **MCP** — connect external tools such as Blender, Ghidra, IDA and Wireshark.
- **Models** — three built-in free models, or bring any OpenAI-compatible API key.

### Download

Use the [latest release](https://github.com/FUA-Studio/FCD/releases/latest) (currently `0.1.3`):
`FCD-Setup.exe` (Windows installer), `fcd.exe` (CLI), `fcd-desktop.exe` (native desktop),
`fcd-desktop-pro.exe` (Pro desktop, 0.1.3 only), `FCD-0.0.1.apk` (Android),
`fcd.elf` (Linux CLI, requires python3).

The repository root keeps a copy of the same `0.1.3` binaries for convenience; **Releases are the
source of truth** and the root copies are refreshed with each new version.

### Quick start

Run `FCD-Setup.exe`, pick an install folder (avoid the system drive), choose one of the built-in
free models, and type your request.

### Version archive

Releases carry the installers and single-file builds for every published version. The root
folders `0.0.4PT/` … `0.1.3S/` keep the artifacts of each version; the suffix means `PT` public
test, `S` stable, `-P`/`PREVIEW` preview.

### Data & privacy

Configuration, sessions and usage data live in the `data` folder next to the install directory —
portable and removable, with only the uninstall entry written to the registry.

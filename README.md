# FCD · FUA CODE

<p align="center">
  <b>FUA Studio 出品的 AI 编码代理</b><br>
  <sub>读写代码 · 执行命令 · 操控电脑 · MCP 扩展 · 多模型自由切换</sub>
</p>

<p align="center">
  <img alt="platform" src="https://img.shields.io/badge/platform-Windows%20%7C%20Linux-0078D6">
  <img alt="agent" src="https://img.shields.io/badge/type-AI%20coding%20agent-7C3AED">
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

[最新版本](https://github.com/FUA-Studio/FCD/releases)

| 文件 | 平台 | 说明 |
| --- | --- | --- |
| `FCD-Setup.exe` | Windows | 一键安装，含 CLI 与桌面版 |
| `fcd.exe` | Windows | 命令行版，单文件免安装 |
| `fcd-desktop.exe` | Windows | 原生桌面窗口版，无浏览器依赖 |
| `fcd.elf` | Linux x86-64 | 纯命令行版，需系统 python3 |

### 三步开始

1. 运行 `FCD-Setup.exe`，选择安装目录（建议非系统盘）。
2. 启动后选择一个内置免费模型。
3. 直接输入需求，例如「帮我看下这个项目的结构」。

无需注册、无需配置，首次启动即可用。

### 界面

CLI：

![CLI](https://github.com/user-attachments/assets/f4835873-47a5-4f1a-90d3-d29c16952854)

桌面版：

![Desktop](https://github.com/user-attachments/assets/c6161dad-e732-4f0f-9444-9b93f59a8253)

### 版本归档

历史版本按 `0.0.4PT`、`0.0.6PT` … `0.1.3S` 的目录归档在仓库根目录，每个目录内为该版本的构建产物与说明。

### 数据与隐私

配置、会话与用量数据都保存在安装目录的 `data` 文件夹内，便携可迁移；仅在当前用户注册表写入卸载信息，随时可用卸载器彻底清除。

## English

**FCD (FUA CODE)** is an AI coding agent by FUA Studio. It reads and edits code, runs shell
commands, debugs and builds — a pair programmer that is ready when you are.

- **Code** — read, create and precisely edit any file in the project, with search and navigation.
- **Commands** — run build, test and install commands and interpret the output.
- **Streaming** — token-by-token output instead of waiting for the full answer.
- **Computer control** — screenshot, move the mouse, click, type, manage windows, use the clipboard.
- **MCP** — connect external tools such as Blender, Ghidra, IDA and Wireshark.
- **Models** — three built-in free models, or bring any OpenAI-compatible API key.

Download the latest [release](https://github.com/FUA-Studio/FCD/releases):
`FCD-Setup.exe` (Windows installer), `fcd.exe` (CLI), `fcd-desktop.exe` (native desktop),
`fcd.elf` (Linux CLI, requires python3).

All configuration, sessions and usage data live in the `data` folder next to the install
directory — portable and removable, with only the uninstall entry written to the registry.

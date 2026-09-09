<div align="center">
  <img src="media/ingenic_blue.svg" width="96" alt="Ingenic logo">

  <h1>Ingenic MCU SDK</h1>

  <p><strong>君正 MCU SDK（代号：Sunflower）官方公开预览与发行仓库</strong></p>

  <p>
    <a href="README.md">English</a>
    &nbsp;|&nbsp;
    简体中文
  </p>

  <p>
    <a href="https://img.shields.io/badge/status-public%20preview-0B6BCB"><img src="https://img.shields.io/badge/status-public%20preview-0B6BCB" alt="Status: public preview"></a>
    <a href="https://img.shields.io/badge/license-Apache--2.0-0B6BCB"><img src="https://img.shields.io/badge/license-Apache--2.0-0B6BCB" alt="Apache License 2.0"></a>
    <a href="https://github.com/trevisy/IMDE-Sunflower/releases"><img src="https://img.shields.io/badge/releases-download-0B6BCB" alt="Releases"></a>
  </p>
</div>

---

> 由 Sunflower SDK 团队维护的官方公开预览仓库。

本仓库是君正 MCU SDK（代号：Sunflower）当前面向外部用户的公开入口。仓库提供 SDK 源码、公共头文件、示例、文档以及版本化发行包。

当前项目处于实验性公开预览阶段。正式稳定版发布前，API、目录结构和发行策略都可能发生变化。

所有面向外部用户的版本均通过 [GitHub Releases](https://github.com/trevisy/IMDE-Sunflower/releases) 发布。每个版本对应的 Git Tag 与 Release Notes 是该版本的最终依据。

## 快速开始

### 1. 下载 SDK

打开 [Releases](https://github.com/trevisy/IMDE-Sunflower/releases) 页面，选择最新版本下载 `tar.gz` 或 `zip` 压缩包。

### 2. 获取工具链与环境

- 安装主机工具链（CMake、Ninja、GCC 等）。
- 拉取并配置对应芯片的 BSP 与工具链。
- 使用本仓库提供的示例工程验证环境。

### 3. 构建示例

确保 SDK 环境变量与工具链就绪后，进入示例目录执行构建，具体命令以官方文档中对应芯片说明为准。

## 目录结构

```text
.
|- include/            公共头文件
|- src/                SDK 源码
|- examples/           示例工程
|- tools/              构建与辅助工具
|- docs/               文档
|   |- en/             英文文档
|   `- zh-CN/          中文文档
|- .github/            CI 与协作配置
|- CHANGELOG.md        版本历史
|- LICENSE             许可证
`- README.md           本文件
```

## 文档

官方文档与快速入门请参见 [君正技术论坛 - 官方文档](http://forum.ingenic.com/official-docs/id-56.html)。

英文版本见 [English](README.md)。

## 下载

所有对外发行包均通过 GitHub Releases 下载。每个发行版包含：

```text
SDK 源码包
预编译发行包
SHA256SUMS
英文 Release Notes
中文 Release Notes（如可用）
已知限制
支持的芯片、工具链与平台
```

## 语言

- **中文（简体）**：本文件
- **English**：[README.md](README.md)

API 名称、函数名、命令行参数与错误码一律以英文为准。其他语言的文档为翻译版本，若与英文存在出入，以英文文档为准。

## 发行与版本

- 当前状态：**Public Preview**
- 版本号遵循 SemVer
- 预发布版本使用 `-preview.N` 或 `-rc.N` 后缀
- 已发布的 Tag 不可修改或删除

## 贡献与安全

欢迎通过 GitHub Issues 报告问题或提出功能建议。提交 Pull Request 前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。安全问题请遵循 [SECURITY.md](SECURITY.md) 中的私密报告流程。

## 许可证

本项目以 [Apache License 2.0](LICENSE) 发布。

<p align="right"><a href="#ingenic-mcu-sdk">回到顶部</a></p>

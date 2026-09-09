<div align="center">
  <img src="media/ingenic_blue.svg" width="96" alt="Ingenic logo">

  <h1>Ingenic MCU SDK</h1>

  <p><strong>Official public preview and distribution repository for the Ingenic MCU SDK (codenamed Sunflower)</strong></p>

  <p>
    English
    &nbsp;|&nbsp;
    <a href="README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://img.shields.io/badge/status-public%20preview-0B6BCB"><img src="https://img.shields.io/badge/status-public%20preview-0B6BCB" alt="Status: public preview"></a>
    <a href="https://img.shields.io/badge/license-Apache--2.0-0B6BCB"><img src="https://img.shields.io/badge/license-Apache--2.0-0B6BCB" alt="Apache License 2.0"></a>
    <a href="https://github.com/trevisy/IMDE-Sunflower/releases"><img src="https://img.shields.io/badge/releases-download-0B6BCB" alt="Releases"></a>
  </p>
</div>

---

> Official public preview repository maintained by the Sunflower SDK team.

This repository is the current public entry point for the Ingenic MCU SDK, codenamed Sunflower. It provides SDK source code, public headers, examples, documentation, and versioned release artifacts for external developers.

The project is currently in the experimental preview phase. APIs, package structure, and release policies may change before the first stable release.

All externally distributed versions are published through [GitHub Releases](https://github.com/trevisy/IMDE-Sunflower/releases). The tagged release and its accompanying release notes are the source of truth for that SDK version.

## Quick Start

### 1. Download the SDK

Open the [Releases](https://github.com/trevisy/IMDE-Sunflower/releases) page and download the `tar.gz` or `zip` archive for the latest version.

### 2. Prepare the toolchain and environment

- Install the host toolchain (CMake, Ninja, GCC, etc.).
- Fetch and configure the BSP and toolchain for your target chip.
- Validate the environment using the example projects in this repository.

### 3. Build an example

With the SDK environment and toolchain ready, enter an example directory and build it. See the chip-specific documentation under the official docs for exact commands.

## Repository Layout

```text
.
|- include/            Public headers
|- src/                SDK source
|- examples/           Example projects
|- tools/              Build and helper tools
|- docs/               Documentation
|   |- en/             English docs
|   `- zh-CN/          Chinese docs
|- .github/            CI and collaboration config
|- CHANGELOG.md        Version history
|- LICENSE             License
`- README.md           This file
```

## Documentation

Official documentation and getting started guides are available at the [Ingenic official forum - Documentation](http://forum.ingenic.com/official-docs/id-56.html).

See the [简体中文](README.zh-CN.md) version for Chinese.

## Download

All externally distributed artifacts are downloaded from GitHub Releases. Each release includes:

```text
SDK source archive
Prebuilt release archive
SHA256SUMS
English release notes
Chinese release notes (when available)
Known limitations
Supported chips, toolchains, and platforms
```

## Languages

- **English**: see below
- **简体中文 (Simplified Chinese)**: [README.zh-CN.md](README.zh-CN.md)

API names, function names, command-line arguments, and error codes are always defined in English. Translations are provided for convenience; if there is any discrepancy, the English documentation is authoritative.

## Releases and Versioning

- Status: **Public Preview**
- Versioning follows SemVer
- Pre-release versions use a `-preview.N` or `-rc.N` suffix
- Published tags cannot be modified or deleted

## Contributing and Security

Report issues or suggest features through GitHub Issues. Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request. For security issues, follow the private reporting process in [SECURITY.md](SECURITY.md).

## License

This project is licensed under the [Apache License 2.0](LICENSE).

<p align="right"><a href="#ingenic-mcu-sdk">Back to top</a></p>

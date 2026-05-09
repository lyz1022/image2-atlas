# Releases / 发布说明

Installers are attached to GitHub Releases. Source code is not distributed from this repository.

安装包通过 GitHub Releases 分发。本仓库不公开分发源代码。

## v0.1.0

### Assets / 发布资产

- `Image2.Atlas-0.1.0-arm64.dmg`
  - macOS Apple Silicon
  - Developer ID signed
  - Apple notarized
  - Stapled
- `Image2.Atlas.Setup.0.1.0-x64.exe`
  - Windows x64
  - NSIS installer
  - Unsigned; Microsoft Defender SmartScreen may warn on first install
- `SHA256SUMS.txt`
- `EULA.md`
- `THIRD_PARTY_NOTICES.md`

### SHA256

```text
b6d6f1fd9a5e4048c83f15c53e0a99a2ba9ab7bd2b770312d3c04f36bf9d72e3  Image2.Atlas-0.1.0-arm64.dmg
3cbc50db813e32b4dcab2e4dec8ecb992e0051e278bdde604cffd96205663bbd  Image2.Atlas.Setup.0.1.0-x64.exe
```

### Notes / 说明

- Windows installer is not Authenticode-signed. Download only from this repository's Releases page and verify SHA256 before installing.
- Windows uninstaller preserves user data by default and provides checkbox options for deleting sync cache, generation history/API settings, or all local app data.
- Windows 安装包未配置 Authenticode 代码签名证书。请仅从本仓库 Releases 页面下载，并在安装前校验 SHA256。
- Windows 卸载程序默认保留用户数据，并提供复选框选项，可选择删除同步缓存、生图历史/API 设置，或全部本机数据。

## Important / 重要说明

This repository does not distribute source code.

本仓库不分发源代码。

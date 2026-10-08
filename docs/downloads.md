# Basic 免费版下载 / Free Basic downloads

[中文介绍](../README.md) · [English overview](../README.en.md) · [版本范围 / Editions](editions.md)

状态核对日期 / Status checked: **2026-10-08**

## 当前下载 / Current download

**[下载 Basic 0.1.0 预览版 / Download Basic 0.1.0 preview](https://github.com/qaqdjh/STEDVOR/releases/tag/basic-v0.1.0-preview.1)**

本仓库仅提供 **STEDVOR Basic 免费版**。本次是 **Pre-release 预览版**，适用于 macOS Apple Silicon（arm64）；不提供 Full 完整版安装包。

This repository provides only **free STEDVOR Basic**. This **pre-release preview** supports macOS Apple Silicon (arm64). No Full-edition installer is provided here.

| 文件 / File | 用途 / Purpose |
| --- | --- |
| [STEDVOR-Basic-0.1.0-macos-arm64-clean.zip](https://github.com/qaqdjh/STEDVOR/releases/download/basic-v0.1.0-preview.1/STEDVOR-Basic-0.1.0-macos-arm64-clean.zip) | Basic 应用 ZIP，27,240,635 bytes。 / Basic application ZIP. |
| [SHA256SUMS.txt](https://github.com/qaqdjh/STEDVOR/releases/download/basic-v0.1.0-preview.1/SHA256SUMS.txt) | 安装包校验值。 / Application checksum. |
| [THIRD-PARTY-NOTICES.txt](https://github.com/qaqdjh/STEDVOR/releases/download/basic-v0.1.0-preview.1/THIRD-PARTY-NOTICES.txt) | 请与应用一并保存的第三方许可证和通知。 / Third-party licences and notices to keep with the application. |

安装包 SHA-256 / ZIP SHA-256:

```text
c3fc9d71761f6590fa1ffaeda9d16f95134b8a4b1a0a493bb3b8d008325c981d
```

本次更新为发行清理候选：已清除本机私人路径和打包元数据，第三方许可已内置；保留上游通用构建配置。

This revision removes developer-local paths and packaging metadata, and bundles third-party notices. Generic upstream build metadata is retained.

## 验证状态 / Validation status

**PASS**：候选离线构建、裁剪与包检查，公开下载、文件大小、SHA-256 和 ZIP 完整性核验。

**PASS:** offline candidate build, trimming and package checks; public download, size, SHA-256 and ZIP integrity verification.

**REJECTED**（尚未完成）：干净设备首装、Gatekeeper 首装、Basic 原生界面和真实 Testnet 验收。该包使用本地证书签名，**没有 Apple 公证**。Intel macOS、Windows、Linux 暂无已验证发行包。

**REJECTED (pending):** clean-device/Gatekeeper installation, native Basic UI and real Testnet acceptance. The package uses a local signing certificate and **has not been notarized by Apple**. There is no verified Intel macOS, Windows or Linux package.

解压后得到 **STEDVOR Basic.app**，具有独立名称、Bundle ID `com.quantworkstation.desktop.basic` 和 Basic 数据目录。下载并保留全部三个文件；遇到启动或系统安全提示时，记录原提示并通过本仓库 Issues 反馈。

Extract the ZIP to obtain **STEDVOR Basic.app**, with a separate name, bundle ID and Basic data directory. Download and keep all three files; report the original launch or system-security message through this repository's Issues if you encounter a problem.

## 下载与授权范围 / Download and licensing scope

GitHub 的 **Code → Download ZIP** 和自动生成的 Source code 压缩包只有介绍材料，不是应用安装包。截图展示开发版本，不意味着所有模块均属于免费 Basic。

GitHub's **Code → Download ZIP** and generated Source code archives contain presentation materials, not the application. Development screenshots do not mean every module belongs to free Basic.

Basic 长期免费，账户与交易流程限于受支持的 Testnet 产品；AI 与增强数据提供方的账号、Key、额度和费用另计。应用使用条款将随正式安装包提供；仓库材料的[版权声明](../LICENSE)与软件许可分别处理，第三方许可见伴随通知。

Basic stays free long term; account and trading workflows are limited to supported Testnet products. AI and enhanced-data accounts, keys, quotas and fees are separate. Application use terms will accompany the official installer; the repository [copyright notice](../LICENSE) and software licensing are separate, and third-party licences are provided in the companion notices.

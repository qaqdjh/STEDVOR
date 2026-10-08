# 系统要求与安装状态 / System requirements and installation status

[快速开始](quick-start.md) · [下载](downloads.md) · [发行记录](release-notes.md)

核对日期 / Checked: **2026-10-08**

本页仅对应 `STEDVOR-Basic-0.1.0-macos-arm64-clean.zip`，其 SHA-256 为 `c3fc9d71761f6590fa1ffaeda9d16f95134b8a4b1a0a493bb3b8d008325c981d`。其他版本须查看各自发行说明。

This page applies only to the named Basic ZIP and checksum. Other builds must state their own requirements.

## 当前预览包 / Current preview

| 项目 / Item | 要求或状态 / Requirement or status |
| --- | --- |
| 处理器 / Processor | Apple Silicon，arm64。 / Apple Silicon, arm64. |
| macOS 编译最低要求 / macOS compile minimum | **26.0**。随包 Python 和相关运行库的 arm64 Mach-O 记录了此下限。 / **26.0**, recorded by the bundled Python and related arm64 runtime libraries. |
| 实际系统兼容性 / Runtime compatibility | 干净设备和原生界面验收尚未完成；编译下限不能证明所有 26.x 或后续系统已通过验收。 / Clean-device and native UI acceptance is pending; a compile minimum does not verify every 26.x or later system. |
| Intel macOS / Windows / Linux | 暂无已验证发行包。 / No verified release package. |
| 内存及可用磁盘 / RAM and free disk | 尚未给出经过验证的最低阈值。 / No validated minimum thresholds published. |
| 网络 / Network | 公开行情需要连接相应交易所公开接口；AI 和增强数据按实际提供方连接。 / Public markets need the exchange's public endpoints; optional services use their respective providers. |
| 基础公开行情 Key / Basic public-market key | 无需交易所 API Key 或 AI Key。 / No exchange API key or AI key required. |
| 模拟账户 / Simulated accounts | Basic 账户与交易流程仅限受支持的 Testnet 产品，需另行配置对应环境凭据。 / Basic account/trading flows are limited to supported Testnet products and require matching credentials. |

应用清单中的版本字段、桌面壳的构建目标和随包依赖的编译下限可能不同。本包以实际随包运行时的 **26.0** 编译要求为准，不将清单字段当作旧系统兼容性证明。

Manifest values, shell build targets and bundled-runtime compile requirements can differ. This package uses the actual bundled-runtime **26.0** requirement; a manifest field is not evidence of older-system compatibility.

## 签名与首装 / Signature and first installation

- **PASS**：冻结包离线检查、文件校验与本地签名完整性检查。
- **REJECTED / 尚未完成**：Developer ID 发行签名、Apple 公证、干净设备／Gatekeeper 首装、Basic 原生界面及真实 Testnet 验收。

The package has passed offline checks, file integrity and local-signature integrity checks. Developer ID distribution signing, Apple notarization, clean-device/Gatekeeper installation, native UI and real Testnet acceptance remain pending.

本预览包不是已完成上述验收的稳定发行。发生系统阻止、启动失败或数据刷新错误时，请保留原提示，按照[反馈说明](feedback.md)提交。首次下载应用的系统提示可参考 [Apple 官方说明](https://support.apple.com/en-us/102445)。

This is a preview rather than a stable release with those acceptances completed. Report the original system, launch or refresh message using the [feedback guide](feedback.md). See [Apple's official explanation](https://support.apple.com/en-us/102445) for first-launch prompts.

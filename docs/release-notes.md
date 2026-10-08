# 发行记录 / Release notes

[下载](downloads.md) · [快速开始](quick-start.md) · [系统要求](system-requirements.md)

## Basic 0.1.0 — basic-v0.1.0-preview.1

**状态 / Status：Pre-release** · **平台 / Platform：macOS Apple Silicon / arm64**

### 当前发行内容 / Current files

- 免费 Basic 应用 ZIP：`STEDVOR-Basic-0.1.0-macos-arm64-clean.zip`。
- 配套 `SHA256SUMS.txt` 与 `THIRD-PARTY-NOTICES.txt`。
- Full 安装包及应用源码不在本次发行范围。

The release contains the free Basic application ZIP, checksum and third-party notices. It provides no Full installer or application source.

### 2026-10-08：发行清理 / Publication cleanup

清除开发者本机私人路径及打包附加元数据，内置第三方通知。前端、执行逻辑和原生组件保持冻结身份，通用上游构建配置保留。公开下载已核对大小、SHA-256 和 ZIP 完整性；旧候选资产已撤下。

Developer-local paths and packaging metadata were removed, and third-party notices were bundled. Frozen frontend, executable logic and native component identities were retained along with generic upstream build metadata. Public download size, checksum and ZIP integrity were checked; superseded assets were withdrawn.

### 2026-10-08：入门与许可文档 / Onboarding and licensing documentation

新增快速开始、系统要求、Basic 免费预览使用条款，并补齐许可入口。核对实际随包 Python 运行时后，明确当前包的编译最低要求为 **macOS 26.0**。

本次文档更新不替换安装包、不改变 SHA-256、不新增运行功能，也不将预览版改为稳定发行。使用条款单独发布，未写入冻结 ZIP。

Quick-start, system requirements and free Basic preview-use terms were added. Inspection of the bundled Python runtime established a **macOS 26.0** compile minimum. This documentation update does not replace the ZIP, change its checksum, add runtime features or turn the preview into a stable release. Use terms are separate from the frozen ZIP.

### 已知限制 / Known limitations

- Developer ID 发行签名、Apple 公证、干净设备／Gatekeeper 首装、Basic 原生界面和真实 Testnet 验收尚未完成。
- 仅提供 Apple Silicon 候选；没有已验证的 Intel macOS、Windows 或 Linux 包。
- 账户和交易限于受支持的 Testnet 产品；公开行情不代表 Mainnet 私人账户访问。
- 截图来自开发版本，可能包含 Full 导航和功能；实际 Basic 范围以[版本说明](editions.md)为准。
- Full 月订阅尚未开放，正式商业条款须另行公布。

Developer ID distribution signing, notarization, clean-device/Gatekeeper installation, native UI and real Testnet acceptance remain pending. Only the Apple Silicon candidate is provided. Basic account/trading scope is limited to supported Testnet products. Development screenshots may include Full modules. Full monthly subscriptions are not open.

### 反馈 / Feedback

按照[反馈说明](feedback.md)提供应用版本、系统版本、页面、复现步骤和原提示。不要提交凭据、账户标识、交易数据库或私人报告。

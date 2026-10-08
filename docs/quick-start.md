# Basic 快速开始 / Basic quick start

[中文介绍](../README.md) · [English overview](../README.en.md) · [下载](downloads.md) · [系统要求](system-requirements.md) · [免费预览使用条款](basic-preview-terms.md)

本教程面向 Basic 0.1.0 的 macOS Apple Silicon 预览包，目标是完成一次基础公开行情扫描。操作名称按冻结 Basic 构建核对；干净设备首装、原生界面和真实 Testnet 验收仍待完成。

## 中文

### 1. 检查系统并下载

当前包的随包运行时编译下限为 **macOS 26.0**，架构为 **Apple Silicon / arm64**。这不是已经完成全部兼容性验收的声明。先阅读[系统要求](system-requirements.md)与[免费预览使用条款](basic-preview-terms.md)。

从 [Basic 0.1.0 预览版发行页](https://github.com/qaqdjh/STEDVOR/releases/tag/basic-v0.1.0-preview.1) 下载以下三个文件：

- `STEDVOR-Basic-0.1.0-macos-arm64-clean.zip`
- `SHA256SUMS.txt`
- `THIRD-PARTY-NOTICES.txt`

GitHub 的 Code → Download ZIP 和自动生成的 Source code 压缩包只有展示材料，不是应用安装包。

### 2. 核对文件

在终端切换到下载文件所在目录后运行：

```sh
shasum -a 256 STEDVOR-Basic-0.1.0-macos-arm64-clean.zip
```

预期 SHA-256：

```text
c3fc9d71761f6590fa1ffaeda9d16f95134b8a4b1a0a493bb3b8d008325c981d
```

不一致时重新从固定发行页下载，勿继续使用该副本。校验用于确认文件一致，不替代安全审计或实际运行验收。

### 3. 解压与首次打开

解压后得到 **STEDVOR Basic.app**。将它放入“应用程序”，并保留两个伴随文件。Basic 使用独立应用名称和数据目录。

当前包使用本地证书签名，尚未获得 Apple 公证，Gatekeeper 首装未验收。若系统允许打开，再继续下面步骤；若被系统阻止或出现启动错误，请记录原提示，通过 [Issues](https://github.com/qaqdjh/STEDVOR/issues)反馈。系统提示的含义可参考 [Apple 官方说明](https://support.apple.com/en-us/102445)。

### 4. 首次设置

进入 **设置**，按需选择 **语言 / Language** 与 **外观**。

第一次查看基础公开行情无需交易所 API Key，也无需 AI Key。AI 与增强数据是另行配置的可选服务，其账号、额度和费用由提供方决定。

### 5. 完成一次公开行情扫描

进入 **市场扫描**，从下面配置开始：

| 项目 | 入门设置 |
| --- | --- |
| 行情环境 | Testnet · 公开行情 |
| 交易所 | Binance |
| 市场类型 | 永续合约 |
| 观察周期 | 15m |
| 筛选范围 | 全部品种 |
| 扫描依据 | 成交额 |
| 扫描前 N | 100 |
| 市值与增强分类条件 | 留空 |

点击 **刷新行情**。查看可见品种、最新价、24h 涨跌、成交额、快照时间和刷新状态；搜索框可输入 BTC 或 ETH，再使用 **筛选器**缩小范围。

缺失字段不是零；刷新失败时可能继续显示上次快照，请同时阅读状态提示。若没有数据，检查网络、行情环境与交易所公开接口状态，再记录原提示反馈。

完成这一流程无需配置账户或发送订单。行内 **查看 Testnet** 仅打开对应工作区，不会提交订单。

### 6. Testnet 账户准备（可选）

想继续模拟资金练习时，再进入 **设置 → 交易所 → 交易所连接配置**。Basic 的凭据环境仅为 Testnet；Binance 当前配置名称是 **Binance Demo（现货与合约）**。

仅使用对应模拟资金环境的 Key；点击 **保存**后，按产品分别使用 **测试 U 本位连接**或 **测试现货连接**。保存凭据不代表连接已通过或交易已验收。独立的 Spot Testnet 开发测试不能替代当前工作区的下单环境。

本教程不要求下单或启动机器人。其他交易所的公开行情支持也不能推导为其签名账户或下单适配器已启用。准备真实 Testnet 交易前，应另行核对支持产品、账户环境、参数与验收状态；请勿在 Issues 中上传 Key、账户标识或私人交易记录。

## English

This guide targets the Basic 0.1.0 Apple Silicon preview and a first public-market scan. Steps were checked against the frozen Basic source; clean-device installation, native UI and real Testnet acceptance are still pending.

1. **Check requirements.** Bundled runtimes have a compile minimum of **macOS 26.0**, on **Apple Silicon / arm64**. Read the [system requirements](system-requirements.md) and [free-preview terms](basic-preview-terms.md).
2. **Download all three files.** Get the Basic ZIP, `SHA256SUMS.txt` and `THIRD-PARTY-NOTICES.txt` from the [fixed preview release](https://github.com/qaqdjh/STEDVOR/releases/tag/basic-v0.1.0-preview.1). GitHub-generated source archives contain presentation materials.
3. **Check the ZIP.** Run the checksum command above from the download directory and compare all 64 characters. Matching checksums establish file identity, not security or runtime acceptance.
4. **Extract and open.** Move **STEDVOR Basic.app** to Applications and keep its companion notices. The preview has a local signature and no Apple notarization. If macOS blocks it or it fails to start, report the original message through [Issues](https://github.com/qaqdjh/STEDVOR/issues); see [Apple's explanation](https://support.apple.com/en-us/102445).
5. **Set language and appearance.** In **Settings**, select your preferences. Basic public market data needs neither an exchange API key nor an AI key.
6. **Scan public markets.** Open **Market Scanner**. Choose **Testnet public market data**, **Binance**, **Perpetual Contract**, the 15m interval, all symbols, volume ranking and up to 100 symbols. Leave market-cap/enrichment filters unset, then select **Refresh Market Data**.
7. **Inspect the result.** Check prices, 24-hour change, volume, snapshot time and refresh status. Missing fields are unavailable rather than zero; failed refreshes may retain the previous snapshot. Use search and filters to narrow the list. This workflow places no orders.
8. **Optional Testnet setup.** In **Settings → Exchanges**, use the corresponding **Binance Demo (spot and futures)** credentials and product-specific connection tests. Saving a key does not establish successful connection or trading acceptance. Account setup and trading are separate from public-market scanning.

Development screenshots may show Full navigation or Mainnet labels. Follow the [Basic edition scope](editions.md); screenshots are not evidence that the Basic native build or real Testnet workflow has passed.

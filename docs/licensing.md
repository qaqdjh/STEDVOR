# Licensing and source policy / 许可与源码政策

Policy decision: 8 October 2026. This page describes the product direction and publication boundaries. It is not an application licence or a checkout agreement.

方案确认日期：2026 年 10 月 8 日。本页说明产品方向与公开范围，不是应用使用许可或付款协议。

## Editions / 版本

**Basic stays free long term. Full is planned as a closed-source commercial edition with monthly subscriptions.** Full subscriptions are not open. The official offering must state its price, included features, term, renewal and cancellation rules, device scope, updates and support before payment.

**Basic 长期免费；Full 采用闭源商业许可，计划按月订阅。** Full 尚未开放订阅。正式方案须在付款前说明价格、包含功能、有效期、续费与取消、设备范围、更新和支持安排。

Free pricing and source-code permissions are separate. Basic being free does not grant an open-source licence. The [edition scope](editions.md) and [Basic preview notes](downloads.md) retain their existing limits.

免费定价与源码授权分别处理。Basic 免费不意味着授予开源许可；现有[版本范围](editions.md)及[Basic 预览说明](downloads.md)的限制仍适用。

## Software scope and funds / 软件定位与资金边界

STEDVOR is a market analysis and quantitative trading workstation for self-directed traders, including individuals and small teams. It provides market observation and scanning, unusual-activity monitoring, factor research, strategy backtesting, performance analysis, and user-configured and authorized manual and automated trading, subject to the actual support of each edition and trading product. Current connections cover crypto-asset markets. Stocks and other markets are planned for gradual expansion, with no available version or confirmed launch date.

STEDVOR 是面向自主交易者的行情分析与量化交易工作台，适用于个人与小团队。提供行情观察与市场扫描、异动监控、因子研究、策略回测、收益分析，以及由用户配置并授权的人工与自动交易功能，受版本及交易产品的实际支持范围限制。当前接入加密资产市场；股票等市场计划逐步扩展，尚无可用版本或确定的上线时间。

Fees for paid software editions purchase a licence to use the software. The developer does not receive users' trading capital or provide trading-fund deposits, custody, order matching or settlement services.

付费软件版本的费用对应软件使用许可。开发者不接收用户交易本金，也不提供交易资金充值、托管、撮合或结算服务。

Users manage their own exchange accounts, API permissions and operating decisions. For trading connections actually supported by an edition, the software submits orders through exchange APIs configured and authorized by the user. If a supported live connection is used, orders execute in the user's own exchange account; the developer does not handle trading funds. Basic execution is limited to supported Testnet products. See the [edition notes](editions.md) for Full's features and release status.

用户自行管理交易所账户、API 权限和操作决策。对于版本实际支持的交易连接功能，软件通过用户自行配置并授权的交易所 API 提交订单。如使用获支持的实盘连接，订单在用户自己的交易所账户执行，开发者不经手交易资金。Basic 仅提供受支持的 Testnet 执行；Full 的功能与开放状态以[版本说明](editions.md)为准。

## Public repository and application / 公开仓库与应用

This repository publishes product descriptions, screenshots, feedback materials and free Basic release downloads. It does not publish STEDVOR application source or a Full installer. GitHub-generated source archives contain only this presentation repository.

本仓库公开产品介绍、截图、反馈材料及免费 Basic 发行下载，不发布 STEDVOR 应用源码或 Full 安装包。GitHub 自动生成的源码压缩包仅包含本展示仓库。

The repository's [copyright notice](../LICENSE) covers original presentation materials to the extent owned by the rights holder. The covered Basic preview has separate [free application-use terms](basic-preview-terms.md), which are not included in the frozen ZIP. Full commercial terms remain pending. This policy page does not itself grant an application licence.

仓库[版权声明](../LICENSE)仅覆盖权利人拥有的原创展示材料。所列 Basic 预览版适用单独发布的[免费应用使用条款](basic-preview-terms.md)，该条款尚未内置到冻结 ZIP；Full 正式商业条款仍待公布。本政策页本身不授予应用许可。

Third-party components keep their own licences and applicable rights. STEDVOR's commercial policy does not override those rights. Redistribution and any source-delivery obligations must be checked for the components actually included in each release; keep the companion third-party notices.

第三方组件保留各自的许可证及适用权利，STEDVOR 的商业政策不覆盖这些权利。每次发行须按实际纳入的组件核对再分发与源码提供义务，并保留随包第三方通知。

## Source review and trust / 源码审阅与可信度

Scoped source disclosure or independent auditing may be considered later. Any disclosure must identify the code, version and granted review, build, modification and redistribution rights. It must not expose credentials, private account data or production state.

后续可考虑指定范围的源码公开或独立审计。公开时须明确代码范围、版本及审阅、构建、修改和再分发权限，并保护凭据、私人账户数据和生产状态。

No source publication schedule or completed security audit is announced here. Partial source disclosure does not verify undisclosed code or establish that a distributed binary was built from the reviewed source. Release provenance, installation and trading behaviour require their own evidence.

本页不承诺源码公开时间，也不宣称已经完成安全审计。公开部分源码不能证明其余代码已受审阅，也不能证明发行二进制来自已审阅源码；发行来源、安装及交易行为仍须分别提供证据。

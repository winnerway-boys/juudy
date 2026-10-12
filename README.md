# Juudy

**CME 股指期货桌面工作台 · macOS**　｜　**A desktop workstation for CME equity-index futures · macOS**

[下载最新版 / Download the latest release](https://github.com/winnerway-boys/juudy/releases/latest)

---

## 中文

### Juudy 是什么
Juudy 是一款看 CME 股指期货（MNQ / NQ / MES / ES）的桌面软件，把行情、订单流和交易结构放在一个画面里：

- **实时行情**：K 线（1 秒到 4 小时）与逐笔成交
- **订单流**：Big Prints 大单气泡、足迹（Footprint）、Session CVD、Delta、Cluster Search
- **成交分布**：Volume Profile、价值区（POC / VAH / VAL）、VWAP、关键价位（PDH / PDL / ONH / ONL 等）
- **ICT 结构**：OB / BB / MB / RB、FVG、MSS / BOS / CHoCH、NWOG / NDOG / ORG、DOL
- **今日大势（Daily Bias）**：偏多 / 偏空 / 中性，附 Why 依据和一段总结
- **策略窗格**：趋势、订单流、FVG、SMC 等内置策略同屏扫描，进出场信号均为**模拟（Sim）**
- **AI 策略工坊**：用中文描述一个想法，AI 生成策略并在实时 K 线上模拟
- **经济日历**：重大数据公布时间与实际值

> 软件只看行情、不下单。所有策略信号都是模拟，仅供研究和学习，**不构成投资建议**。期货交易风险很高。

### 系统要求
- macOS 15 及以上，Apple 芯片（M1 及以后）的 Mac
- Windows 版开发中

### 使用前要准备
1. **行情**：TopstepX 账户，并订阅 ProjectX API。行情**只支持 TopstepX 账户**；Lucid、Apex、Tradeify、TakeProfitTrader 等其他公司的账户用不了。
2. **AI**：一个 AI 服务的 API Key，例如 DeepSeek、智谱 GLM、火山方舟、通义千问。

### 下载与安装
1. 在 [Releases](https://github.com/winnerway-boys/juudy/releases) 下载 `Juudy-版本号.dmg`。GitHub 打不开或下载很慢：能直连就直连，连不上用科学上网。
2. 双击 dmg，把 Juudy 拖进「应用程序」。
3. 第一次打开如果提示无法打开：打开「系统设置 → 隐私与安全性」，点「仍要打开」。
4. 按软件里的设置向导填好 AI 和 ProjectX，向导里有看图教程。

### 试用与授权
- 每个版本可以免费试用 **14 天**。
- 到期后，把软件里显示的**申请码**发邮件到 **996032777@qq.com**，收到回信后把**解锁码**粘进软件即可。
- 解锁码只对申请的那台 Mac、那个版本有效。

### 问题反馈
软件里「设置 → 问题反馈」，或发邮件到 **996032777@qq.com**。

### 校验
每个安装包都在 Releases 里附了 SHA256，下载后可以用 `shasum -a 256 Juudy-版本号.dmg` 核对。

---

## English

### What is Juudy
Juudy is a desktop app for CME equity-index futures (MNQ / NQ / MES / ES) that puts price, order flow and market structure on one screen:

- **Live market data**: candles (1 s to 4 h) and every trade print
- **Order flow**: Big Prints bubbles, Footprint, Session CVD, Delta, Cluster Search
- **Volume profile**: POC / VAH / VAL, VWAP, key levels (PDH / PDL / ONH / ONL …)
- **ICT structure**: OB / BB / MB / RB, FVG, MSS / BOS / CHoCH, NWOG / NDOG / ORG, DOL
- **Daily Bias**: bullish / bearish / neutral with the reasons and a short summary
- **Strategy panes**: built-in strategies (Trend, Order Flow, FVG, SMC …) scanning side by side; all entries and exits are **simulated (Sim)**
- **AI Strategy Studio**: describe an idea, AI writes the strategy and simulates it on live candles
- **Economic calendar**: release times and actual values

> Juudy only reads market data and never places orders. All strategy signals are simulated, for research and learning only, and are **not investment advice**. Futures trading carries high risk.

### Requirements
- macOS 15 or later on an Apple-silicon Mac (M1 or newer)
- A Windows version is in development

### What you need
1. **Market data**: a TopstepX account with a ProjectX API subscription. Only **TopstepX accounts** are supported; accounts from Lucid, Apex, Tradeify, TakeProfitTrader and other firms do not work.
2. **AI**: an API key from an AI provider (e.g. DeepSeek, Zhipu GLM, Volcano Ark, Qwen).

### Install
1. Download `Juudy-<version>.dmg` from [Releases](https://github.com/winnerway-boys/juudy/releases).
2. Open the dmg and drag Juudy into Applications.
3. If macOS says it cannot be opened: System Settings → Privacy & Security → **Open Anyway**.
4. Follow the in-app setup wizard (with an illustrated guide) to connect AI and ProjectX.

### Trial and license
- Every version includes a **14-day free trial**.
- After the trial, email the **request code** shown in the app to **996032777@qq.com** and paste the **unlock code** from the reply.
- An unlock code works only on the Mac and the version it was issued for.

### Feedback
In the app: Settings → Feedback, or email **996032777@qq.com**.

### Checksums
Each installer in Releases comes with its SHA256 (`shasum -a 256 Juudy-<version>.dmg`).

---

© 2026 Juudy. 保留所有权利 / All rights reserved. 本仓库只提供安装包与介绍，不含源代码 / This repository contains installers and documentation only — no source code. 详见 / See [LICENSE](LICENSE).

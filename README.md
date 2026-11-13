# GKD_subscription

Mikon 自托管的 GKD 订阅规则（跳过 App 开屏广告等），规则迁移自 [Lin-arm/GKD_subscription](https://github.com/Lin-arm/GKD_subscription)（已停止维护）及 AIsouler 等开源订阅。

## 订阅地址

- **jsDelivr CDN（推荐）**：
  `https://fastly.jsdelivr.net/gh/Mikon233/GKD_subscription@main/dist/gkd.json5`
- **GitHub Raw**：
  `https://raw.githubusercontent.com/Mikon233/GKD_subscription/main/dist/gkd.json5`

在 GKD App → 订阅 → 右上角 ➕ 添加上述任一地址即可。

## 规则规模

- 1003 个应用 / 2508 个规则组（v1，2026-11-13）

## 更新方式

修改 `dist/gkd.json5` 并将 `version` 字段 +1 后提交推送，GKD 会自动检测更新。

# CardBalance 原型

信用卡管理与财务对账相关原型页面。

**Version:** `1.5.0`（见 `VERSION`）

## 模块

- 信用卡管理：Card 日消耗 / 额度 / 返点统计 / 返点明细 / BI统计
- 财务对账：密钥信息配置（静态 / API）

## BI统计标签

- 日消耗额度情况
- 月度消耗情况
- 卡使用情况
- 卡申请统计

## 本地预览

直接打开 `index.html`，或：

```bash
python3 -m http.server 8080
```

访问 http://localhost:8080

## GitHub Pages

推送到 `main` 后，在仓库 Settings → Pages 中选择 Deploy from branch：`main` / `/ (root)`。

线上地址：https://maxmabiz.github.io/cardbalance/

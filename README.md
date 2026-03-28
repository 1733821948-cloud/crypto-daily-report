# 🪙 币圈日报自动生成器

每天自动采集加密货币市场数据、行业新闻、Reddit 社交热点，通过 DeepSeek AI 生成专业日报，发送到 QQ 邮箱。

## 功能

- 📊 市场数据：CoinGecko 实时币价、涨跌幅、市值、恐惧贪婪指数
- 📰 行业新闻：CoinTelegraph / Decrypt / CoinDesk / Bitcoin Magazine RSS 聚合
- 💬 社交热点：Reddit 热门讨论（r/CryptoCurrency、r/Bitcoin 等）
- 🤖 AI 汇总：DeepSeek Reasoner 生成结构化中文日报
- 🎯 今日总评：市场情绪评分 + 最大机会 + 最大风险
- 📧 邮件推送：QQ 邮箱 SMTP 自动发送 HTML 格式邮件

## 快速开始

1. 安装依赖
```bash
pip install requests pyyaml feedparser
```

2. 复制 `Config` 为 `config.yaml`，填入你的 DeepSeek API Key 和 QQ 邮箱授权码

3. 运行
```bash
python crypto_daily.py
```

## 费用

| 服务 | 费用 |
|------|------|
| CoinGecko / RSS / Reddit | 免费 |
| DeepSeek Reasoner | ~¥0.1-0.3/次 |
| QQ 邮箱 SMTP | 免费 |

每天一次，每月不到 ¥10。

## ⚠️ 免责声明

本报告仅供参考，不构成任何投资建议。

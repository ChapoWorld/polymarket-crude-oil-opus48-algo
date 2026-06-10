# 🛢️ Polymarket Crude Oil AI Algorithm (5m / 15m / 1h) — Claude Opus 4.8 Edition

An automated high-frequency trading algorithm designed specifically for Crude Oil prediction markets on [Polymarket](https://polymarket.com/). 

This bot utilizes the deep reasoning capabilities of **Claude Opus 4.8** to instantly parse complex geopolitical shifts, OPEC+ secret briefings, and EIA inventory reports, executing YES/NO share orders across 5-minute, 15-minute, and 1-hour timeframes.

## ⚠️ The Bottleneck: Claude Opus 4.8 Token Costs
Claude Opus 4.8 is the most advanced model on the market, but its advanced thinking process burns through massive amounts of tokens. Running data scans every 5 minutes on standard Anthropic billing will cost you hundreds of dollars an hour. 

## 🚀 The Solution: Anonymous Cached Endpoint
To run this algorithm profitably without blowing your budget, you must route your trading bot through a low-latency, Enterprise-grade endpoint that supports **Active Prompt Caching**. This cuts Opus 4.8 processing costs by up to 90%.

**Get your required No-KYC, Crypto-funded Opus 4.8 API Key:**
👉 **[Purchase Cached Claude API Key here](https://claude.sell.app/product/claude-api-tokens)**

## ⚙️ Configuration (`config.json`)
```json
{
  "market": "crude_oil_wti",
  "timeframes": ["5m", "15m", "1h"],
  "llm_provider": "anthropic_custom_vertex",
  "api_key": "YOUR_PURCHASED_API_KEY",
  "base_url": "YOUR_CUSTOM_BASE_URL",
  "model": "claude-opus-4.8",
  "execution_delay_ms": 120
}

Privacy Note: Protect your alpha. The recommended API provider requires no corporate KYC and takes instant crypto payments.

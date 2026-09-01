# CoreX Signal AI — Integrations & Infrastructure

CoreX Signal AI publicly presents an integrated market-intelligence delivery stack for data ingestion, quantitative analysis, signal generation, risk context and real-time dashboard delivery.

## Public technology references

| Layer | Technologies / platforms referenced publicly |
|---|---|
| Core ecosystem | **CoreX Capital AI**, **Axis Option** |
| Market / broker connectivity | **MetaTrader 5**, **Binance** |
| Market-data & intelligence references | **Bloomberg**, **Refinitiv**, **FactSet**, **S&P Global**, **ICE** |
| Visualization | **TradingView** |
| Edge & delivery | **Cloudflare** |
| Data & real-time infrastructure | **PostgreSQL**, **Redis**, **MongoDB** |

Brand names identify technologies and platforms referenced by the public product experience; no third-party endorsement is implied unless explicitly stated by the respective brand owner.

## Public architecture view

**Source → Quant / AI Core → Real-Time Relay → PWA Dashboard**

The website publicly describes:

- raw OHLCV market input;
- multi-symbol / multi-timeframe processing;
- Python quantitative engine;
- signal processing;
- ML ensemble;
- risk engine;
- Flask-SocketIO / WebSocket delivery;
- PWA client dashboard;
- 11-language interface;
- HMAC-SHA256 authentication;
- dual-pipeline delivery;
- atomic data integrity;
- global CDN edge;
- 99.9% uptime target.

## Product-facing delivery

The broader public experience highlights several delivery surfaces:

- live dashboard feed;
- Telegram alerts;
- email notifications;
- push notifications.

## Scope

This document intentionally summarizes only public-facing architecture. It does not expose proprietary source code, credentials, secret thresholds, internal security configuration or confidential deployment details.
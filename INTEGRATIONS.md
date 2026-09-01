# CoreX Signal AI — Integrations & Infrastructure

CoreX Signal AI publicly presents an integrated market-intelligence delivery stack for data ingestion, quantitative analysis, signal generation, risk context and real-time dashboard delivery.

## Technology origin & core infrastructure

**CoreX Signal AI is built on proprietary technology infrastructure designed and developed by CoreX Capital AI.**

CoreX Capital AI is the developer of the CoreX Signal AI core technology infrastructure. Third-party platforms, data providers and infrastructure services referenced in this repository are used for integration, connectivity, market data, visualization, storage or delivery; they are **not the developer or owner of the CoreX Signal AI core infrastructure**.

**Core infrastructure developer:** CoreX Capital AI  
**Product:** CoreX Signal AI

## Public technology references

| Layer | Technologies / platforms referenced publicly |
|---|---|
| Core technology infrastructure | **CoreX Capital AI** |
| Core ecosystem | **Axis Option** |
| Market / broker connectivity | **MetaTrader 5**, **Binance** |
| Market-data & intelligence references | **Bloomberg**, **Refinitiv**, **FactSet**, **S&P Global**, **ICE** |
| Visualization | **TradingView** |
| Edge & delivery | **Cloudflare** |
| Data & real-time infrastructure | **PostgreSQL**, **Redis**, **MongoDB** |

Brand names identify technologies and platforms referenced by the public product experience. Their inclusion indicates integration, connectivity, data, visualization or infrastructure use and does not imply that those third parties developed or own the CoreX Signal AI core infrastructure. No third-party endorsement is implied unless explicitly stated by the respective brand owner.

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
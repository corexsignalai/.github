# CoreX Signal AI — Feature Catalog

CoreX Signal AI is presented as an **AI-powered quantitative market intelligence and signal analytics workspace**. This document maps the public dashboard capabilities without exposing proprietary source code, private thresholds, credentials or internal deployment details.

## Core dashboard layers

| # | Module | Public purpose |
|---:|---|---|
| 1 | **AI Decision Output** | Primary decision state with BUY / SELL / HOLD / protection context, recommended action, readable rationale, score context, historical Win Rate, Expected R and past-setup context. |
| 2 | **Cross-Timeframe Coherence** | Micro-to-macro alignment matrix across `M1 · M5 · M15 · M30 · H1 · H4 · D1 · W1 · MN1`. |
| 3 | **Master Action Gauge / Strategic Console** | Composite view of AI Confidence, Master Score, Market Risk, Buyer / directional power, alignment and readiness. |
| 4 | **Execution Optimization** | Analytical risk-planning layer for direction, risk class, R:R, lot-size context, SL / Entry / TP geometry, ATR, distance and risk budget. |
| 5 | **Probabilistic Forecast Engine** | Scenario distribution with 95% confidence interval, 1,000 paths, forecast horizon, lower / median / upper bounds and directional spread. |
| 6 | **Institutional Depth Map** | Supply / demand zones, FVG / order-block context, spot-price anchor and zone confidence. |
| 7 | **Strategy Performance Curve** | Historical / simulated signal-history context including return, maximum drawdown, Win Rate, signal count and equity-curve visualization. |
| 8 | **Model Interpretation Layer** | Human-readable multi-timeframe reasoning stream showing which factors support, oppose or neutralize the active decision. |
| 9 | **Factor Intelligence Hub** | Multi-axis factor view, driver attribution, ranked impact drivers and AI-consensus context. |
| 10 | **Market Regime Pulse** | Cross-market alignment / drift, correlation and regime context around the active timeframe. |
| 11 | **Macro Intelligence Feed** | Market headlines, sentiment state, impact context and upcoming session windows. |
| 12 | **Regime & Structural DNA** | Random-Walk / Trending state, Hurst context, structural score and ML confirmation / neutral state. |
| 13 | **Price & Signal Chart** | Multi-timeframe price chart with selectable signal overlays and active-layer comparison. |
| 14 | **Secondary Timeframe Analysis** | Compact non-primary timeframe reads with HOLD / BUY / SELL context, recommended action and expandable reasoning. |
| 15 | **Strategy Selection & Risk Profiles** | Conservative, Balanced, Aggressive and Scalper profiles that change filtering and decision context. |
| 16 | **11-Language & Multi-Market Experience** | One intelligence workflow across multiple markets with an 11-language interface. |

## Top market header

The live dashboard exposes a compact state bar designed for fast scanning:

- **Price**
- **Bias**
- **Composite**
- **Confidence**
- **Alignment**
- **Readiness**
- **Signal Quality**
- **Regime**
- **Risk**
- **Session**
- **Engine version**
- **Last update / live time**

## Decision states & protection

The decision layer is intentionally capable of showing action **and non-action** states.

- **BUY** — bullish actionable context.
- **SELL** — bearish actionable context.
- **HOLD / WAIT** — conditions are not sufficiently aligned for an entry.
- **VETO / Active Protection** — a risk or inhibitor is detected and the system explicitly blocks or delays entry while the market is re-evaluated.
- **Auto re-scanning** — the interface communicates that conditions are being checked again rather than forcing a trade.

The current dashboard also exposes **Trade Style Impact** so one market state can affect different styles differently:

- ⚡ **Scalp:** `M1–M15`
- 📊 **Day Trade:** `M30–H4`
- 🌊 **Swing:** `H4–D1`

A style can be shown as **Caution**, **Blocked** or otherwise affected by the active protection state.

## Risk-planning fields

Execution Optimization may expose:

`Direction · Risk class · R:R · Lot size · Stop Loss · Entry · Take Profit · Risk budget · TP distance · SL distance · ATR % · ATR-14`

This module is analytical planning support and **does not place orders**.

## Explainability factors visible in the product

The public Model Interpretation / Factor Intelligence experience can reference factors such as:

- Trend Strength Factor
- PCA Principal Factor
- Momentum Differential Signal
- Slope Gradient Factor
- Momentum Acceleration
- Hurst Trend Exponent
- Short-Term Flow Imbalance
- Dynamic Time-Warp Match
- Distribution Skew Factor
- volatility / regime effects
- RSI / divergence context
- MACD / divergence context
- directional boost / inhibitor context

## Signal analytics

Depending on the dashboard state, the interface can provide historical / analytical context such as:

- historical **Win Rate**;
- **Expected R / Expected Value**;
- past-setup sample size;
- simulated / historical return;
- maximum drawdown;
- signal count;
- signal-history equity curve.

These are contextual analytics and are not guarantees of future performance.

## Public scope

This repository documents **what the user can see and understand**. It intentionally does not publish proprietary model code, private infrastructure, credentials, internal security configuration or confidential thresholds.
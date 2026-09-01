# CoreX Signal AI — Dashboard Guide

This document explains the **public-facing dashboard experience** of CoreX Signal AI. It intentionally documents product behavior and visible analytical modules only. It does not publish proprietary source code, private infrastructure configuration, credentials, internal thresholds beyond what the product itself displays, or security-sensitive implementation details.

---

## Dashboard at a glance

CoreX Signal AI is an **AI-powered quantitative market intelligence and signal analytics platform**. The dashboard is built around four questions:

1. **What is the current signal state?**
2. **How much agreement exists across timeframes and factors?**
3. **What is the current risk / regime context?**
4. **What historical and probabilistic context supports or challenges the decision?**

The dashboard does not directly execute trades.

---

## Top Market Header

The top status region provides the fastest possible read of the selected market.

Visible fields can include:

| Field | Meaning |
|---|---|
| **Price** | current market price shown by the dashboard |
| **Bias** | directional market bias |
| **Composite** | combined model / factor score context |
| **Confidence** | AI confidence context |
| **Alignment** | degree of signal / timeframe agreement |
| **Readiness** | current readiness for an actionable state |
| **Signal Quality** | qualitative signal-strength indicator |
| **Regime** | statistical market regime such as Random-Walk / Trending |
| **Risk** | current risk-state classification |
| **Session** | active market session context |
| **Engine** | visible product engine version |

The header also contains the **symbol selector, strategy / risk profile selector and language selector**.

---

## Symbol Selection

Dashboard examples currently show fast switching between:

- EURUSD
- GBPUSD
- USDJPY
- USDCAD
- XAUUSD
- Bitcoin
- Ethereum

The broader product experience covers multiple market classes, including major FX, crypto and equity / stock contexts as available in the product and plan.

---

## Strategy Selection & Risk Profiles

The dashboard exposes four profiles:

| Profile | Visible multiplier | Dashboard description |
|---|---:|---|
| **Conservative** | ×0.5 | highest-conviction filtering, fewest signals, strictest vetoes |
| **Balanced** | ×1.0 | balanced signal frequency and protection |
| **Aggressive** | ×1.5 | more opportunities; softer vetoes can become warnings |
| **Scalper** | ×2.0 | maximum frequency for short-term tactical analysis |

The selected profile affects how analytical context is filtered and presented. It is not a promise of performance.

---

## 11-Language Interface

A language selector is integrated into the dashboard. CoreX Signal AI publicly presents **11 supported languages**, allowing the same analytical workflow to serve an international user base.

---

# Intelligence Modules

## AI Decision Output

This is the primary actionable layer.

Typical visible elements:

- market / symbol;
- BUY / SELL / HOLD state;
- decision title;
- recommended action;
- explanatory rationale;
- historical outcome / Win Rate context;
- Expected R;
- sample size / past setups;
- model score;
- profile multiplier;
- timeframe meta-analysis;
- veto or inhibitor context;
- expandable model reasoning.

The module can explicitly recommend waiting when alignment is insufficient.

---

## Cross-Timeframe Coherence

The dashboard compares:

`M1 · M5 · M15 · M30 · H1 · H4 · D1 · W1 · MN1`

Each timeframe can have its own state, price context, strength and micro-chart.

The coherence summary reports the balance between:

**Buy · Sell · Wait / Hold**

and highlights the timeframe associated with the selected strategy profile.

---

## Strategic Console / Master Action Gauge

The strategic layer condenses decision quality into visual gauges.

It can include:

- AI Confidence;
- Master Score;
- Market Risk;
- Buyer Power / directional power;
- overall composite context.

This panel is designed for rapid interpretation before the user opens deeper reasoning.

---

## Execution Optimization

**Important:** this is an analytical planning module. It does not place orders.

Visible fields can include:

- BUY / SELL direction;
- Low / Medium / other risk state;
- R:R;
- analytical lot-size context;
- SL;
- Entry;
- TP;
- risk budget;
- TP distance;
- SL distance;
- ATR %;
- ATR-14.

The objective is to connect signal context to disciplined risk planning.

---

## Probabilistic Forecast Engine

The forecast panel presents scenario ranges instead of a single deterministic prediction.

Visible components can include:

- 95% confidence interval;
- 1,000 simulated paths;
- forecast horizon;
- lower bound;
- median;
- upper bound;
- bullish / bearish spread.

This is a probabilistic context layer, not a guaranteed price forecast.

---

## Institutional Depth Map

The depth panel visualizes price zones around the current spot price.

The interface can show:

- Institutional Supply Zone;
- Institutional Demand Zone;
- Order Block (`OB`);
- Fair Value Gap (`FVG`);
- confidence / strength percentage;
- spot price anchor.

---

## Strategy Performance Curve

The performance panel can present historical or simulated signal-history analytics such as:

- return;
- maximum drawdown;
- Win Rate;
- signal count;
- equity curve.

These figures are contextual historical / simulated analytics and are not guarantees of future results.

---

## Model Interpretation Layer

The interpretation stream provides readable model-factor context across timeframes.

Visible contributors can include:

- Trend Strength Factor;
- PCA Principal Factor 1;
- Momentum Differential Signal;
- Slope Gradient Factor;
- Momentum Acceleration;
- Hurst Trend Exponent;
- Short-Term Flow Imbalance;
- Dynamic Time-Warp Match;
- Distribution Skew Factor;
- volatility-regime effects;
- divergence signals;
- momentum-exhaustion signals;
- BUY / SELL boost context.

The purpose is to expose the logic chain in human-readable form.

---

## Factor Intelligence Hub

The Factor Intelligence Hub combines:

- multi-axis factor radar;
- driver attribution;
- ranked Impact Drivers;
- AI consensus context.

Common visible factors include MACD, ADX, PCA components, volatility components, DTW, RSI / divergence signals and multi-signal factors.

---

## Market Regime Pulse

The regime panel measures broader alignment / correlation context.

It can show:

- market aligned / drifting state;
- positive-to-negative alignment gauge;
- cross-market correlation;
- timeframe / moving-reference context.

This helps separate a signal from the environment in which it appears.

---

## Macro Intelligence Feed

The macro panel can combine:

- market headlines;
- sentiment classification;
- impact context;
- upcoming session windows;
- market-session timing.

The purpose is to keep event / macro context inside the decision workspace rather than in a separate product.

---

## Regime & Structural DNA

This structural module describes the statistical character of the current market.

Visible elements can include:

- Random-Walk or Trending state;
- Hurst value;
- structural score;
- ML confirmation / neutral context.

---

## Price & Signal Chart

The chart shows the active price path with selectable signal overlays.

Users can compare signal layers across the dashboard timeframe family and visually inspect where signal states appeared relative to price.

---

## Secondary Timeframe Analysis

This module provides compact reads for non-primary timeframes.

It can display:

- HOLD / BUY / SELL;
- bullish / bearish context;
- recommended action;
- threshold / score context;
- expandable reasoning.

A key design goal is to communicate **when conditions are unsuitable for trading**, not only when a signal is present.

---

# Historical Setup Analytics

A signal decision can be accompanied by historical context such as:

- historical Win Rate;
- Expected R / expected value;
- sample size / past setups;
- signal-history return;
- max drawdown;
- signal count.

Because market conditions change, these metrics should be interpreted as **context**, not as promises or guaranteed future performance.

---

# Explainable AI Experience

The product publicly presents an explainability layer that can reference:

- PCA;
- ML ensemble consensus;
- Hurst analysis;
- NLP sentiment;
- factor attribution;
- model reasoning by timeframe.

The user-facing decision chain is:

**market data → model / factor context → timeframe agreement → signal decision → risk context → probabilistic scenarios → historical setup analytics**

---

# Product Scope

CoreX Signal AI is a **market intelligence and signal analytics system**.

It is not presented here as:

- an automatic trade execution engine;
- a guarantee of profitable outcomes;
- a replacement for user judgment;
- a source-code repository.

This GitHub organization is a **product, documentation and brand showcase**. Proprietary algorithms, internal infrastructure, security-sensitive configuration and user data remain private.

---

## Official destinations

- Website: https://corexsignalai.com/
- Live Dashboard: https://api.corexsignalai.com/
- Interactive Demo: https://corexsignalai.com/demo.html
- Contact: info@corexsignalai.com
- Parent technology ecosystem: https://corexcapitalai.com/

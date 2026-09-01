# CoreX Signal AI — Complete Dashboard Guide

This document maps the **public-facing CoreX Signal AI dashboard** in detail. It is intentionally focused on product behavior, visible analytics and user experience. It does **not** expose proprietary source code, credentials, private infrastructure, confidential thresholds or security-sensitive implementation details.

---

# 1. Dashboard philosophy

CoreX Signal AI is designed around one core principle:

> **A useful signal should show the decision, the evidence, the risk and the reason to wait when conditions are not good enough.**

The dashboard therefore treats **BUY, SELL, HOLD and VETO / Active Protection** as first-class outcomes.

The workspace is built to answer:

1. What is happening now?
2. Are the timeframes aligned?
3. What does the AI recommend?
4. What risk / regime context surrounds the decision?
5. What historical and probabilistic evidence supports or challenges it?
6. Why is the system acting — or refusing to act?

---

# 2. Top Market Header

The top status bar provides a compact real-time read of the selected market.

Visible fields can include:

| Field | Meaning |
|---|---|
| **Price** | Current price displayed by the dashboard |
| **Bias** | Directional market bias |
| **Composite** | Combined model / factor context |
| **Confidence** | AI confidence context |
| **Alignment** | Degree of signal / timeframe agreement |
| **Readiness** | Current action-readiness state |
| **Signal Quality** | HOLD / Veto / other signal-quality context |
| **Regime** | Statistical market regime such as Trending or Random-Walk |
| **Risk** | Current risk classification |
| **Session** | Active market-session context |
| **Engine** | Visible engine version |
| **Last Update** | Latest dashboard-data refresh time |
| **Live Time** | Current live-time display |

The same header also exposes:

- symbol selection;
- risk-profile selection;
- language selection;
- account / plan context;
- compact multi-market ticker state.

---

# 3. Multi-Market Symbol Selector

The current dashboard shows fast switching between:

`EURUSD · GBPUSD · USDJPY · USDCAD · XAUUSD · Bitcoin · Ethereum`

The selector is designed so the user can move from one market to another without changing the analytical workflow.

The wider public product presentation also shows multi-market intelligence across **Forex, Crypto and equity / stock contexts**.

See [MARKETS.md](MARKETS.md) for the dedicated coverage guide.

---

# 4. Strategy Selection & Risk Profiles

CoreX Signal AI exposes four strategy / risk profiles:

| Profile | Multiplier | Intended dashboard behavior |
|---|---:|---|
| **Conservative** | `×0.50` | Highest-conviction filtering, fewer signals, strictest veto behavior |
| **Balanced** | `×1.00` | Balanced protection and opportunity frequency |
| **Aggressive** | `×1.50` | More opportunities; softer vetoes can become warnings |
| **Scalper** | `×2.00` | Maximum short-term tactical frequency |

The profile can influence:

- signal filtering;
- active timeframe emphasis;
- veto severity;
- opportunity frequency;
- risk-budget context;
- analytical sizing context;
- warning vs blocked behavior.

See [RISK_PROFILES.md](RISK_PROFILES.md).

---

# 5. AI Decision Output

The **AI Decision Output** is the primary decision layer.

It can present:

- market / symbol;
- primary state;
- BUY / SELL / HOLD / VETO context;
- recommended action;
- readable decision title;
- explanatory rationale;
- meta-analysis;
- score / threshold context;
- profile-adjusted score;
- historical Win Rate;
- Expected R / Expected Value;
- past-setup sample size;
- veto / inhibitor context;
- expandable model reasoning.

## Actionable states

### BUY
Bullish conditions have reached an actionable state for the active profile.

### SELL
Bearish conditions have reached an actionable state for the active profile.

### HOLD / WAIT
The system can recognize directional structure while still recommending no entry.

Example public dashboard language can distinguish between:

- **Waiting HOLD**;
- **Neutral HOLD (Bullish)**;
- **Neutral HOLD (Bearish)**;
- trend present but threshold not reached;
- weak / choppy market where entry should be avoided.

### VETO / Active Protection

A risk factor or inhibitor can cause the system to explicitly block entry.

The current live dashboard can display:

- `VETO` badge;
- **Active Protection** title;
- recommended-action explanation;
- meta-analysis / inhibitor detail;
- selected profile and multiplier;
- **Auto re-scanning** state.

This makes the protection system visible rather than silently suppressing a trade.

See [DECISION_STATES.md](DECISION_STATES.md).

---

# 6. Trade Style Impact

When protection or caution is active, the dashboard can translate the state into practical trading horizons:

| Style | Timeframe family | Dashboard impact examples |
|---|---|---|
| ⚡ **Scalp** | `M1–M15` | Caution / short-term protection context |
| 📊 **Day Trade** | `M30–H4` | Caution or Blocked |
| 🌊 **Swing** | `H4–D1` | Caution / higher-timeframe protection context |

This lets one market state be interpreted differently depending on the user's working horizon.

---

# 7. Cross-Timeframe Coherence

The dashboard compares the active market across:

`M1 · M5 · M15 · M30 · H1 · H4 · D1 · W1 · MN1`

Each timeframe can expose:

- BUY / SELL / HOLD state;
- local price context;
- directional percentage / strength;
- mini price path;
- active profile-timeframe highlight;
- contribution to overall coherence.

The coherence summary can display counts such as:

**Buy · Sell · Wait**

This allows the user to see disagreement rather than receiving one flattened directional label.

---

# 8. Strategic Console / Master Action Gauge

The Strategic Console compresses several dimensions into a fast visual read.

Typical gauges include:

- **AI Confidence**;
- **Master Score**;
- **Market Risk**;
- **Buyer Power / directional power**;
- alignment / readiness context.

The purpose is fast interpretation before the user opens deeper factor reasoning.

---

# 9. Execution Optimization

**Execution Optimization is an analytical planning module. It does not place orders.**

Visible fields can include:

- BUY / SELL direction;
- Low / Medium / other risk state;
- Risk:Reward (`R:R`);
- analytical lot-size context;
- Stop Loss (`SL`);
- Entry;
- Take Profit (`TP`);
- risk budget;
- TP distance;
- SL distance;
- ATR percentage;
- `ATR-14`.

The dashboard therefore connects signal intelligence to structured risk planning without becoming an automatic execution terminal.

---

# 10. Probabilistic Forecast Engine

The forecast module expresses uncertainty as a distribution rather than presenting one deterministic future price.

The public interface can show:

- **95% confidence interval**;
- **1,000 paths**;
- forecast horizon;
- lower scenario;
- median scenario;
- upper scenario;
- bullish / bearish spread.

The goal is to make the range of plausible outcomes visible.

---

# 11. Institutional Depth Map

The depth panel adds structural market context around the live price.

Visible elements can include:

- Institutional Supply Zone;
- Institutional Demand Zone;
- Fair Value Gap (`FVG`);
- Order Block (`OB`) context;
- live spot-price anchor;
- zone confidence / strength;
- support / resistance / liquidity framing.

---

# 12. Strategy Performance Curve

The performance panel visualizes historical / simulated signal-history context.

It can show:

- return;
- maximum drawdown;
- Win Rate;
- signal count;
- equity-performance curve;
- active date / window context.

These statistics are **historical or simulated analytical context**, not guarantees of future performance.

---

# 13. Model Interpretation Layer

CoreX Signal AI is designed to expose model reasoning rather than hide the decision behind a black box.

The live reasoning stream can show per-timeframe contributors such as:

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
- divergence context;
- exhaustion context;
- directional boost / inhibitor context.

The user can therefore inspect **which factors supported, opposed or neutralized** the active decision.

---

# 14. Factor Intelligence Hub

The Factor Intelligence Hub turns model contributors into a visual attribution layer.

It combines:

- multi-axis factor radar;
- ranked **Impact Drivers**;
- positive / negative driver contribution;
- AI-consensus context.

Examples visible in the product include factors such as:

`ADX · MACD · Momentum Exhaustion · Gradient · Hurst · Volatility PC2 · Skew · PC1 · Velocity Deceleration · Multi-Signal context`

---

# 15. Market Regime Pulse

The Market Regime Pulse measures broader market alignment and correlation context.

It can show:

- aligned / drifting state;
- positive-to-negative alignment gauge;
- cross-market correlation;
- reference timeframe;
- moving-reference comparison;
- active session context.

This helps answer:

> **Is the broader environment supporting the signal?**

---

# 16. Macro Intelligence Feed

The macro panel brings event / news context into the same decision workspace.

It can display:

- headline context;
- sentiment classification;
- impact context;
- AI sentiment processing;
- upcoming market sessions;
- session countdown windows.

This reduces the need to separate technical / model analysis from macro awareness.

---

# 17. Regime & Structural DNA

This module describes the statistical character of the active market.

Visible fields can include:

- **Trending** vs **Random-Walk** state;
- Hurst value;
- structural score;
- ML confirmation / neutral state.

The purpose is to distinguish persistent directional behavior from weak or random-like structure.

---

# 18. Price & Signal Chart

The price chart gives the user a visual map of signals relative to actual price movement.

The interface can include:

- active timeframe layer;
- selectable signal overlays;
- one-active-layer mode;
- timeframe pills;
- price path;
- signal markers;
- macro-bias context.

This turns abstract scores into visual confluence.

---

# 19. Secondary Timeframe Analysis

Not every timeframe should produce an entry.

Secondary Timeframe Analysis gives compact reads for non-primary timeframes and can expose:

- VETO / BUY / SELL / HOLD state;
- bullish / bearish background context;
- recommended action;
- score / threshold context;
- expandable model reasoning;
- inhibitor / boost factors.

Examples of decision logic the interface can communicate include:

- market is bullish but entry threshold has not been reached;
- low ADX / trend power makes the market unsuitable;
- high-confidence SELL signal detected;
- volatility regime creates an inhibitor;
- divergence creates a recovery / reversal factor;
- market should be observed rather than traded.

This module is essential to the product's **decision-quality-over-signal-frequency** design.

---

# 20. 11-Language Experience

CoreX Signal AI publicly presents an **11-language interface** directly inside the dashboard.

The multilingual experience is designed around one shared intelligence stack rather than separate regional products.

**One product · one analytical workflow · 11-language access**

---

# 21. Multi-Channel Signal Visibility

The broader public product experience highlights several signal-delivery surfaces:

- live dashboard feed;
- Telegram alerts;
- email notifications;
- push notifications.

This supports both continuous dashboard use and faster external notification workflows.

---

# 22. Public System Architecture

At a high level, the public website describes the delivery chain as:

**Market / broker data → Quant / AI engine → signal / risk processing → real-time relay → PWA dashboard**

Publicly referenced elements include:

- raw OHLCV market input;
- multi-symbol / multi-timeframe processing;
- Python quant engine;
- signal processing;
- ML ensemble;
- risk engine;
- Flask-SocketIO / WebSocket delivery;
- 11-language PWA dashboard;
- HMAC-SHA256 authentication;
- dual-pipeline delivery;
- atomic data integrity;
- global CDN edge;
- 99.9% uptime target.

See [INTEGRATIONS.md](INTEGRATIONS.md).

---

# 23. Product scope & information notice

CoreX Signal AI is a **market intelligence and signal analytics system**.

It is not presented here as:

- an automatic trade-execution engine;
- a guarantee of profitable outcomes;
- a replacement for user judgment;
- an open-source model repository.

Historical, simulated or illustrative metrics — including Win Rate, Expected R, returns, drawdown, confidence, sample size and signal count — do not guarantee future results.

The public GitHub organization documents the **product experience, visible analytics, brand and support surface** while proprietary algorithms, credentials, internal security configuration and user data remain private.

---

## Related documentation

- [Product Overview](PRODUCT.md)
- [Complete Feature Catalog](FEATURES.md)
- [Markets & Timeframes](MARKETS.md)
- [Risk Profiles](RISK_PROFILES.md)
- [Decision States & Active Protection](DECISION_STATES.md)
- [Integrations & Infrastructure](INTEGRATIONS.md)
- [Brand Guide](BRAND.md)
- [Security Policy](SECURITY.md)
- [Support](SUPPORT.md)

## Official destinations

- Website: https://corexsignalai.com/
- Live Dashboard: https://api.corexsignalai.com/
- Interactive Demo: https://corexsignalai.com/demo.html
- Contact: info@corexsignalai.com
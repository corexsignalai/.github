# CoreX Signal AI — Explainable AI for Market Analysis

CoreX Signal AI is designed around a simple principle: **a market signal should be understandable, not merely displayed**.

The platform therefore exposes model context and factor attribution alongside BUY, SELL, HOLD and VETO / Active Protection states.

## What the user can inspect

Depending on the active market and timeframe, visible reasoning can reference factors such as:

- Trend Strength Factor;
- PCA Principal Factor;
- Momentum Differential;
- Slope Gradient;
- Momentum Acceleration;
- Hurst Trend Exponent;
- Short-Term Flow Imbalance;
- Dynamic Time-Warp Match;
- Distribution Skew;
- volatility and regime effects;
- RSI / MACD divergence context;
- directional boost logic;
- inhibitors and veto conditions.

The purpose is not to expose proprietary source code or secret implementation details. The purpose is to make the **user-facing reason for a decision transparent**.

## From signal to explanation

A CoreX Signal AI decision can be read as a chain:

1. **Market state** — current symbol, price, bias and regime.
2. **Timeframe state** — BUY / SELL / HOLD behavior across the active hierarchy.
3. **Decision state** — primary action, including VETO / Active Protection where applicable.
4. **Confidence and readiness** — model confidence, composite context, alignment and readiness.
5. **Risk context** — current market risk, ATR framing and strategy profile.
6. **Scenario context** — probabilistic forecast distribution rather than one deterministic target.
7. **Structural context** — institutional zones, market regime and broader alignment.
8. **Factor interpretation** — readable model contributors and inhibitors.

## Why explainability matters

Explainability helps a user distinguish between:

- a strong signal with broad agreement;
- a signal with meaningful timeframe conflict;
- a trend that has not yet passed an entry threshold;
- a market with low directional power;
- a signal blocked by volatility or another inhibitor;
- a HOLD state that is intentionally protecting decision quality.

This matters because **the absence of a trade can itself be an analytical conclusion**.

## Explainability and Active Protection

When a VETO / Active Protection state is active, CoreX Signal AI can present:

- the protection status;
- recommended action;
- inhibitor / meta-analysis context;
- profile-adjusted decision context;
- trade-style impact across Scalp, Day Trade and Swing horizons;
- automatic re-scanning while conditions are re-evaluated.

The platform is therefore designed to explain both **why a signal exists** and **why an entry is being blocked**.

## Cross-timeframe explainability

The nine-timeframe stack — `M1 · M5 · M15 · M30 · H1 · H4 · D1 · W1 · MN1` — allows reasoning to be inspected across micro and macro horizons.

A single actionable timeframe does not erase disagreement elsewhere. The dashboard keeps conflict visible so users can evaluate the quality of confluence.

## Public scope and proprietary boundaries

CoreX Signal AI is built on proprietary technology infrastructure designed and developed by **CoreX Capital AI**. Public explainability describes the user-facing analytical context; it does not disclose proprietary model code, credentials, private security configuration or confidential implementation details.

## Related documentation

- [AI Market Intelligence](AI-MARKET-INTELLIGENCE.md)
- [Complete Dashboard Guide](DASHBOARD.md)
- [Decision States & Active Protection](DECISION_STATES.md)
- [Feature Catalog](FEATURES.md)
- [FAQ](FAQ.md)

**Official website:** https://corexsignalai.com/  
**Live dashboard:** https://api.corexsignalai.com/

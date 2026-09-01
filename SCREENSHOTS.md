# CoreX Signal AI — Real Dashboard Captures

This page documents **real CoreX Signal AI dashboard screenshots** supplied from the live product interface. The screenshots are included to show the actual presentation and visible decision workflow of the platform.

> **Point-in-time notice:** market values, signal states, scores, percentages and session information shown in a screenshot reflect that specific captured moment. They are not fixed product values and are not guarantees of future performance.

---

## 1. Active Protection / VETO — live decision state

<img src="./profile/assets/screenshots/live-active-protection.webp" width="100%" alt="CoreX Signal AI live EURUSD dashboard showing Active Protection VETO, symbol selector and cross-timeframe coherence">

### What this real dashboard capture shows

This screenshot demonstrates a state where the system is **not forcing an entry**. The selected market is `EURUSD`, and the AI Decision Output is in an **Active Protection / VETO** condition.

### Market and workspace controls visible in the capture

The upper dashboard region shows the active product controls and status layer, including:

- symbol selector;
- `EURUSD` as the selected market;
- additional selectable symbols: `GBPUSD`, `USDJPY`, `USDCAD`, `XAUUSD`, `BITCOIN`, `ETHEREUM`;
- Last Update and Live Time;
- strategy / risk-profile selector;
- language selector;
- account / plan context;
- Price, Bias, Composite, Confidence, Alignment and Readiness;
- Signal Quality;
- Regime, Risk, Session and Engine context;
- compact multi-market ticker states.

### AI Decision Output — Active Protection

The central decision panel shows **Active Protection** rather than an entry signal. The important product behavior demonstrated here is that CoreX Signal AI can explicitly surface a protection state when the analytical stack detects an inhibitor or risk factor.

The visible workflow includes:

- `VETO` decision state;
- active timeframe / state context;
- recommended action;
- explanation that the market is being re-evaluated;
- expandable model reasoning;
- profile-adjusted decision context;
- automatic re-scanning while conditions are reassessed.

This matters because a professional decision-support system should explain **why it is refusing an entry**, not only why it is generating one.

### Trade Style Impact

The screenshot also shows how one market state can affect different trading horizons differently:

- **Scalp — M1 to M15:** Caution;
- **Day Trade — M30 to H4:** Blocked;
- **Swing — H4 to D1:** Caution.

This creates a more useful user experience than treating every trader and every horizon as identical.

### Cross-Timeframe Coherence

The right side of the capture shows the micro-to-macro signal matrix. In this specific captured state, multiple timeframes remain in `HOLD`, while one timeframe carries a `SELL` state. The summary visibly distinguishes:

- Buy count;
- Sell count;
- Wait / Hold count;
- coherence percentage;
- highlighted profile timeframe.

The screenshot therefore demonstrates a key CoreX Signal AI principle: **timeframe disagreement remains visible instead of being hidden behind a single headline signal**.

---

## 2. Deep Analytics Surface — live lower-dashboard modules

<img src="./profile/assets/screenshots/live-analytics-modules.webp" width="100%" alt="CoreX Signal AI live dashboard analytics showing strategic console, forecast, depth map, performance, interpretation, factors, macro and regime modules">

### What this real dashboard capture shows

This screenshot captures the lower analytical surface of the dashboard, where the user can move from the top-level signal into risk, forecast, market structure and explainability.

### Strategic Console

The Strategic Console compresses several decision-quality dimensions into fast visual gauges, including:

- **AI Confidence**;
- **Master Score**;
- **Market Risk**;
- **Buyer / directional power**.

The purpose is rapid situational awareness before the user opens deeper reasoning.

### Execution Optimization

The visible Execution Optimization panel connects a directional signal with analytical risk-planning context. It can show:

- BUY / SELL direction;
- risk classification;
- Risk:Reward (`R:R`);
- analytical lot size;
- Stop Loss;
- Entry;
- Take Profit;
- risk budget;
- TP distance;
- SL distance;
- ATR percentage;
- ATR-14.

This is **analytical planning information** and is not presented as direct order execution.

### Probabilistic Forecast Engine

The capture shows a bell-curve / scenario-distribution view with:

- 95% confidence interval;
- 1,000 simulated paths;
- forecast horizon;
- Lower scenario;
- Median scenario;
- Upper scenario;
- directional spread.

The design communicates uncertainty through a range of possible paths instead of a single deterministic price claim.

### Institutional Depth Map

The depth module places the live spot price between structural market zones. The visible interface can include:

- Institutional Supply Zone;
- Institutional Demand Zone;
- FVG / order-block context;
- zone range;
- confidence / strength;
- live spot-price anchor.

### Strategy Performance Curve

The performance module presents historical or simulated signal-history context through:

- equity / performance curve;
- Return;
- Maximum Drawdown;
- Win Rate;
- Signal Count.

These are contextual analytics and should not be interpreted as guaranteed future outcomes.

### Model Interpretation Layer

The interpretation stream exposes human-readable reasoning by timeframe. Visible contributors can include:

- directional / trend factors;
- PCA factors;
- momentum differential;
- slope / gradient factors;
- Hurst context;
- other supportive or opposing model inputs.

This helps the user trace a decision back to the factors that influenced it.

### Factor Intelligence Hub

The Factor Intelligence Hub combines:

- multi-axis factor radar;
- AI consensus context;
- ranked Impact Drivers;
- positive and negative factor contributions.

This provides a compact attribution view for users who want to understand which factors are carrying the decision.

### Market Regime Pulse

The Market Regime Pulse adds broader environment context using:

- alignment / sync state;
- cross-market correlation;
- directional alignment gauge;
- active reference relationship.

### Macro Intelligence Feed

The Macro Intelligence Feed places news and event context in the same analytical workspace. It can expose:

- market headlines;
- sentiment state;
- impact context;
- upcoming session windows.

### Regime & Structural DNA

The structural module describes the statistical character of the market using concepts such as:

- Trending vs Random-Walk state;
- Hurst context;
- structural score;
- ML confirmation / neutral state.

---

## Why the screenshots are included

The public GitHub profile is designed as a **product showcase and documentation hub**, not as a source-code disclosure repository. These real dashboard captures let prospective users see the actual interface and analytical depth without exposing proprietary algorithms, credentials, internal infrastructure or confidential implementation details.

For the full module-by-module explanation, see [DASHBOARD.md](DASHBOARD.md).

For decision behavior including BUY / SELL / HOLD / VETO, see [DECISION_STATES.md](DECISION_STATES.md).

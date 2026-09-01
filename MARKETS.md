# CoreX Signal AI — Market & Timeframe Coverage

CoreX Signal AI is designed as a **multi-market, multi-timeframe intelligence workspace** rather than a single-symbol signal page.

## Dashboard symbols

The current dashboard experience includes rapid switching between:

| Market | Symbol / label |
|---|---|
| Forex | **EURUSD** |
| Forex | **GBPUSD** |
| Forex | **USDJPY** |
| Forex | **USDCAD** |
| Metals / FX | **XAUUSD** |
| Crypto | **Bitcoin** |
| Crypto | **Ethereum** |

The wider public product presentation also demonstrates crypto, forex and equity / stock contexts.

## Multi-timeframe stack

The Cross-Timeframe Coherence engine compares the active market across:

`M1 · M5 · M15 · M30 · H1 · H4 · D1 · W1 · MN1`

Each timeframe can expose:

- BUY / SELL / HOLD state;
- local price context;
- directional strength / confidence;
- mini price-path visualization;
- profile-timeframe highlight;
- contribution to overall coherence.

## Why multi-timeframe coherence matters

A signal is more useful when the user can see whether short-term flow agrees with higher-timeframe structure. The dashboard therefore makes disagreement visible instead of hiding it.

Examples of states the interface can communicate:

- short-term BUY while higher timeframes remain HOLD;
- one SELL timeframe against a majority WAIT state;
- broad bullish alignment;
- weak / choppy structure where entry is blocked;
- profile-specific emphasis on a chosen timeframe.

## Trade-style mapping

The current dashboard also maps protection / decision context into three practical trading horizons:

| Style | Timeframe family | Example protection output |
|---|---|---|
| ⚡ **Scalp** | `M1–M15` | Caution / active short-term context |
| 📊 **Day Trade** | `M30–H4` | Caution or Blocked |
| 🌊 **Swing** | `H4–D1` | Caution / higher-timeframe context |

## Multi-market ticker

The interface includes a compact cross-market ticker so users can see directional state across symbols before opening a deeper analysis view.

Market availability can evolve with the live product and plan. This document describes the public dashboard experience and does not promise permanent availability of every symbol.
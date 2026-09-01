# CoreX Signal AI — Decision States & Active Protection

The CoreX Signal AI decision layer is designed to communicate **action, uncertainty and protection** rather than forcing a trade on every market update.

## Primary states

### BUY
A bullish actionable state where the active model / factor context clears the required decision conditions for the selected profile.

### SELL
A bearish actionable state where the active model / factor context clears the required decision conditions for the selected profile.

### HOLD / WAIT
A non-entry state. The dashboard can remain bullish or bearish in background structure while explicitly recommending that the user waits because the entry threshold, alignment or trend quality is insufficient.

### VETO / Active Protection
A protection state where one or more inhibitors are strong enough to block an entry.

The current dashboard can present:

- **Veto** state badge;
- **Active Protection** title;
- recommended action explaining why entry is not advised;
- meta-analysis / inhibitor context;
- profile-adjusted score context;
- trade-style impact;
- **Auto re-scanning** status while conditions are re-evaluated.

## Recommended-action examples

The product is able to distinguish between messages such as:

- **Stay out: conditions unsuitable for trading.**
- **Strong trend, but entry not yet confirmed. Observe.**
- **A high-confidence BUY / SELL signal detected.**
- **Risk factor detected; entry blocked while the market is re-evaluated.**

## Secondary Timeframe Analysis

Non-primary timeframes can be analyzed separately so users can see why one timeframe may be actionable while another remains HOLD.

The panel can expose:

- timeframe;
- directional background state;
- BUY / SELL / HOLD / VETO label;
- recommended action;
- threshold / score context;
- model-reasoning explanation;
- inhibitor or boost factors.

## Design principle

A professional decision-support system should make **why not to trade** as visible as **why to trade**. CoreX Signal AI therefore treats protection, waiting and conflicting timeframe states as first-class dashboard outputs.
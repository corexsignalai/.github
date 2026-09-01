# CoreX Signal AI — Strategy Selection & Risk Profiles

CoreX Signal AI exposes four strategy / risk profiles so the same market can be interpreted through different filtering and opportunity-frequency settings.

| Profile | Dashboard multiplier | Public behavior |
|---|---:|---|
| 🛡 **Conservative** | `×0.50` | Highest-conviction filtering, fewer signals and strictest veto behavior. |
| ⚖️ **Balanced** | `×1.00` | Balanced opportunity frequency and protection. |
| ⚡ **Aggressive** | `×1.50` | More opportunities; softer vetoes may become warnings. |
| 🎯 **Scalper** | `×2.00` | Maximum short-term tactical frequency. |

## Profile-aware decision context

The selected profile can influence how the dashboard presents:

- active timeframe emphasis;
- signal filtering;
- veto severity;
- opportunity frequency;
- risk budget context;
- lot-size / SL / TP planning context;
- warning vs blocked states.

## Active Protection

The dashboard can enter a **VETO / Active Protection** state when a risk factor or inhibitor is detected.

In this state the interface may explicitly communicate:

> AI detected a risk factor and is actively protecting your capital. Market conditions are being re-evaluated automatically.

The goal is to make **non-entry decisions visible** rather than forcing a BUY or SELL output.

## Trade Style Impact

Protection context can also be translated into practical time-horizon effects:

- ⚡ **Scalp — M1 to M15**
- 📊 **Day Trade — M30 to H4**
- 🌊 **Swing — H4 to D1**

Depending on the active state, each style can be shown as **Caution**, **Blocked** or otherwise affected.

## Important distinction

The profiles are analytical configuration modes. They do not guarantee a particular performance level, return, Win Rate or number of signals.
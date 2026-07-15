# NASDAQ March Contract — Worked Example

> ← Back to [Episode 2 Hub](README.md) | [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship Episode 2 — *Elements To A Trade Setup*
> **Instrument:** NASDAQ E-mini Futures (NQ) — March contract

---

## Overview

This is the example the episode walks through to demonstrate the top-down framework in action. It shows how a bearish weekly bias flows all the way down to a precise 2-minute short entry on the retest of an imbalance.

---

## Stage 1 — Weekly Bias

- Reviewed the **weekly** chart over the weekend
- Estimated the weekly candle would likely trade **lower** from its open
- Bias: **BEARISH** — all lower-timeframe decisions must look for shorts

See [Multi-Timeframe Analysis](../../concepts/multi-timeframe-analysis.md).

---

## Stage 2 — Daily Liquidity Map

- On the **daily**, marked swing highs and lows
- **Sell stops** rest below old lows; **buy stops** rest above old highs
- Located daily **imbalances** (price gaps) as additional liquidity draws
- These define where price is likely to gravitate

See [Liquidity](../../concepts/liquidity.md) and [Fair Value Gaps](../../concepts/fair-value-gaps.md).

---

## Stage 3 — Hourly Stop Hunt

The key liquidity-engineering behavior:

```
                              ╔═══════════════╗
                   buy stops→ ║  short-term    ║  ← 2. price RUNS higher
                   triggered  ║     high       ║     to trigger buy stops
                              ╚═══════════════╝     near clean daily levels
                       ▲
   overnight ──────────┤
   consolidation       │
                       ▼
                  ┌───────────────┐
        sell stops→│  short-term   │  ← 1. price first drives DOWN
        triggered  │     low       │     to attack sell stops
                  └───────────────┘
```

1. A sell-off led to **overnight consolidation**
2. Market first drove **down** to attack sell stops under a short-term low
3. Then **ran higher** to trigger buy stops resting above a short-term high, near clean daily structure

This is the **stop hunt** that sets up the trade. See [Stop Hunts](../../concepts/stop-hunts.md).

---

## Stage 4 — 2-Minute Setup

After the hunt, on the **2-minute** chart:

1. Price **broke a short-term low** — a [market structure break](../../concepts/market-structure-break.md) confirming bearish continuation (aligned with the weekly bias)
2. The sharp break left a **Fair Value Gap** (imbalance) — a one-way move with no offsetting overlap

See [Market Structure Break](../../concepts/market-structure-break.md) and [Fair Value Gaps](../../concepts/fair-value-gaps.md).

---

## Stage 5 — Entry & Risk

```
   ┌─────────────┐  ← Stop (conservative): above breaking candle's high
   │             │  ← Stop (tight): above imbalance high
   │  FVG / IMB  │  ← ENTRY: short on retrace INTO the imbalance
   │             │
   └─────────────┘
          │
          ▼  price continues lower (bearish continuation)
          ▼
   ══════════════  ← Target: discount zone / opposite range extreme
                     (liquidity + imbalance fills near the low)
```

- **Entry:** short when price **retraced up into the FVG** — NOT on the break itself (avoids chasing/slippage)
- **Stop options:**
  - Above the imbalance zone's high (tight)
  - Above the high of the candle that broke the short-term low (conservative)
- **Target:** the opposite extreme of the intraday range — the [discount zone](../../concepts/market-structure.md) where liquidity and imbalances fill

See [Risk Management](../../concepts/risk-management.md).

---

## Liquidity Matrix Applied

- Day's range split at the **50% Fibonacci**
- Entry taken from **premium** (above 50%, expensive)
- Target in **discount** (below 50%, cheap)
- Bearish repricing = price delivered from premium → discount, filling imbalances along the way

See [Market Structure (Premium/Discount)](../../concepts/market-structure.md).

---

## The Fingerprints in This Example

| Fingerprint | In This Trade |
|-------------|---------------|
| Run on opposite side's stops | Overnight drive to sell stops, then run to buy stops |
| [Market structure break](../../concepts/market-structure-break.md) | 2-min break of the short-term low |
| Retrace into imbalance | Short entry on the FVG retest |

All three appeared, aligned with the bearish weekly bias → high-probability short.

---

## Why This Repeats

The episode stresses this is **not a one-off**. The same sequence — stop hunt → structure break → imbalance retest — shows up reliably on futures contracts, week after week, day after day. Backtest it across instruments and timeframes to internalize the pattern.

---

## Related Concepts

- [Multi-Timeframe Analysis](../../concepts/multi-timeframe-analysis.md)
- [Liquidity](../../concepts/liquidity.md)
- [Stop Hunts](../../concepts/stop-hunts.md)
- [Market Structure Break](../../concepts/market-structure-break.md)
- [Fair Value Gaps](../../concepts/fair-value-gaps.md)
- [Market Structure (Premium/Discount)](../../concepts/market-structure.md)
- [Risk Management](../../concepts/risk-management.md)

---

*Source: 2022 ICT Mentorship Episode 2 — Elements To A Trade Setup*

# Episode 2 — Elements To A Trade Setup

> ← Back to [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship [No Rant] Episode 2
> **Instrument:** NASDAQ E-mini Futures (NQ) — March contract

---

## What This Episode Teaches

The **foundational top-down framework** for building a trade setup. It shows how to layer weekly, daily, hourly, and minute-level charts into a repeatable process for anticipating direction, timing entries, and placing stops logically. This is the blueprint the rest of the mentorship builds on.

---

## Learn the Concepts (Read in This Order)

```
1. Multi-Timeframe Analysis → How to layer weekly → 1-min (and set weekly bias)
2. Liquidity               → Where stop clusters (buy/sell stops) rest
3. Stop Hunts              → How price engineers liquidity before the real move
4. Market Structure Break  → The break that confirms continuation
5. Fair Value Gaps         → The imbalance you enter on
6. Market Structure (P/D)  → Premium/discount via 50% Fib (the "liquidity matrix")
7. Risk Management         → Where to place your stop
```

| # | Concept | Link |
|---|---------|------|
| 1 | Multi-Timeframe Analysis | [../../concepts/multi-timeframe-analysis.md](../../concepts/multi-timeframe-analysis.md) |
| 2 | Liquidity | [../../concepts/liquidity.md](../../concepts/liquidity.md) |
| 3 | Stop Hunts | [../../concepts/stop-hunts.md](../../concepts/stop-hunts.md) |
| 4 | Market Structure Break | [../../concepts/market-structure-break.md](../../concepts/market-structure-break.md) |
| 5 | Fair Value Gaps | [../../concepts/fair-value-gaps.md](../../concepts/fair-value-gaps.md) |
| 6 | Market Structure (Premium/Discount) | [../../concepts/market-structure.md](../../concepts/market-structure.md) |
| 7 | Risk Management | [../../concepts/risk-management.md](../../concepts/risk-management.md) |

---

## The Entry Model (Step-by-Step)

This episode's "elements of a trade setup," organized by timeframe.

### Stage 1 — Bias (Weekend / Weekly Chart)

| Step | Action | Concept |
|------|--------|---------|
| 1 | On the **weekly** chart, decide: is price likely to move **higher or lower** from the open this week? | [Multi-Timeframe Analysis](../../concepts/multi-timeframe-analysis.md) |
| 2 | This is your **bias** — probability, not a price prediction. Everything below must align with it. | [Multi-Timeframe Analysis](../../concepts/multi-timeframe-analysis.md) |

### Stage 2 — Map Liquidity (Daily Chart)

| Step | Action | Concept |
|------|--------|---------|
| 3 | On the **daily**, mark swing highs/lows — these are **stop clusters** (buy stops above highs, sell stops below lows). | [Liquidity](../../concepts/liquidity.md) |
| 4 | Note any **imbalances** (price gaps) on the daily — these are also liquidity draws. | [Fair Value Gaps](../../concepts/fair-value-gaps.md) |

### Stage 3 — Watch the Hunt (Hourly Chart)

| Step | Action | Concept |
|------|--------|---------|
| 5 | Transpose daily highs/lows onto the **hourly**. | [Multi-Timeframe Analysis](../../concepts/multi-timeframe-analysis.md) |
| 6 | Watch for a **stop hunt**: price drives one way to take stops, then reverses toward the opposite side's stops. | [Stop Hunts](../../concepts/stop-hunts.md) |

### Stage 4 — Find the Setup (15-min → 2-min)

| Step | Action | Concept |
|------|--------|---------|
| 7 | On the **15-min**, confirm the higher-timeframe structure and liquidity. | [Multi-Timeframe Analysis](../../concepts/multi-timeframe-analysis.md) |
| 8 | Drop to the **2-min**: wait for a **break of market structure** (e.g., break of short-term low = bearish continuation). | [Market Structure Break](../../concepts/market-structure-break.md) |
| 9 | The break leaves a **Fair Value Gap** (imbalance). Mark it. | [Fair Value Gaps](../../concepts/fair-value-gaps.md) |

### Stage 5 — Execute (2-min → 1-min)

| Step | Action | Concept |
|------|--------|---------|
| 10 | **Wait** for price to retrace **into the FVG** — do NOT enter on the break. | [Market Structure Break](../../concepts/market-structure-break.md) |
| 11 | **Enter** (short, if bearish) on the retest of the imbalance. | [Fair Value Gaps](../../concepts/fair-value-gaps.md) |
| 12 | **Stop:** above the imbalance high, or above the high of the candle that broke structure (per risk tolerance). | [Risk Management](../../concepts/risk-management.md) |
| 13 | **Target:** the opposite range extreme — liquidity + imbalance fills in the [discount zone](../../concepts/market-structure.md). | [Market Structure (P/D)](../../concepts/market-structure.md) |

---

## The "Setup Fingerprints"

The episode stresses this is a **repeatable, mechanical** pattern — not a one-off. Look for these three fingerprints together:

```
1. A run on the opposite side's stops   → Stop Hunt
2. A market structure break               → confirms continuation
3. Price retracing into an imbalance      → your entry (FVG retest)
```

When all three appear aligned with your weekly bias, you have a high-probability setup.

---

## Liquidity Matrix (Intraday Targeting)

- Split the day's range (low → high) with the **50% Fibonacci** level
- **Premium** (above 50%) = expensive → algorithm looks to sell
- **Discount** (below 50%) = cheap → algorithm looks to buy
- When bearish: expect price to move **premium → discount**, filling imbalances and taking liquidity near the lows

See [Market Structure (Premium/Discount)](../../concepts/market-structure.md).

---

## Quick-Reference Checklist

```
□ Weekly bias set (higher or lower this week?)
□ Daily swing highs/lows + imbalances marked (liquidity map)
□ Stop hunt observed on the hourly (one side swept)
□ Break of structure on the 2-min, aligned with weekly bias
□ Fair Value Gap left by the break, marked
□ Entry taken on the RETEST of the FVG (not the break)
□ Stop above imbalance high / breaking candle high
□ Target set at opposite range extreme (premium→discount if bearish)
```

---

## Homework Assignment (From the Episode)

Students are told to:

1. Review E-mini futures charts across **all** timeframes (weekly, daily, hourly, 15-min, 2-min, 1-min)
2. **Log** chart patterns showing breaks of market structure and identified imbalances (FVGs)
3. Identify the **highest-probability entries** where price retests imbalances after breaking structure
4. **Backtest** these setups across multiple instruments/timeframes, observing outcomes
5. Build confidence in the methodology through repetition

> Future lessons introduce systematic journaling and search processes to cultivate consistency.

---

## Episode-Specific Content

| File | Content |
|------|---------|
| [NASDAQ March Worked Example](nasdaq-march-example.md) | The step-by-step example the episode walks through |

---

## The Core Insight

> Price gravitates toward liquidity (clustered stops and imbalances) — the footprints of institutions. Master the repeatable fingerprints — **stop hunt → structure break → imbalance retest** — aligned with a weekly bias, and you have a mechanical edge.

---

*Source: 2022 ICT Mentorship Episode 2 — Elements To A Trade Setup*

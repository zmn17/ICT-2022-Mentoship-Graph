# NASDAQ FVG Trade — 60+ Handles in Under 15 Minutes

> ← Back to [Episode 6 Hub](README.md) | [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship Episode 6 — *Market Efficiency Paradigm & Institutional Order Flow*
> **Instrument:** NASDAQ E-mini Futures (NQ)

---

## Overview

A bearish Fair Value Gap short demonstrating the full model: a post-8:30 buy-stop run above a 15-min high, an energetic displacement lower, a bearish FVG on the low timeframes, and an IRL→ERL exit — capturing **60+ handles in under 15 minutes**.

---

## Stage 1 — Liquidity & Time

- Anchor: a **15-minute swing high** — buy stops rest above it. See [Liquidity](../../concepts/liquidity.md).
- Time: just after **8:30 AM** (employment data release) — a scheduled volatility window. See [Market Efficiency Paradigm](../../concepts/market-efficiency-paradigm.md).

```
   ══════════════════════  15-min HIGH (buy stops above)
              ▲  price trades ABOVE the high after 8:30 → grabs buy stops
             ╱
   ─────────╱
```

---

## Stage 2 — Displacement (the Market Structure Shift)

```
              ▲ buy stops taken
             ╱╲
            ╱  ╲
   ────────╱    ╲
                 ╲   ← ENERGETIC breakdown
                  ╲     closes BELOW a short-term low
   short-term low ─╲──────  (displacement confirmed)
                    ▼
```

- After grabbing the buy stops, price **sharply breaks below a short-term low** and **closes below it**
- This is a **true displacement candle** → confirms the bearish [market structure shift](../../concepts/market-structure-shift.md). See [Displacement](../../concepts/displacement.md).

---

## Stage 3 — The Bearish FVG (drop to 1–5 min)

Dropping to the **5/4/3/2/1-minute** charts reveals the bearish FVG inside the displacement range:

```
   ── Candle 1 low ─────────┐
              │   FVG ZONE   │  ← inefficient sell-side pricing
   ── Candle 3 high ────────┘     (C3 high does NOT retest C1 low)
```

| Candle | Feature |
|--------|---------|
| 1 | High = upper boundary; low = reference |
| 2 | Low trades below Candle 1's low |
| 3 | Low below Candle 2's low; high does **not** retest Candle 1's low |

See [Fair Value Gaps](../../concepts/fair-value-gaps.md) for the full rules.

---

## Stage 4 — Entry, Stop & Targets

```
   Stop ── above Candle 1 / 2 high ──────────────
   ── Candle 1 low ─────────┐
              │   FVG       │  ← SELL limit just above Candle 3 high (+1 tick)
   ── Candle 3 high ────────┘     (price retests it multiple times = multiple entries)
              │
              ▼  ~50% / internal range low  → PARTIAL (IRL)
              ▼
   ══════════════════  beyond old low → external range liquidity → FINAL EXIT (ERL)
```

- **Entry:** limit just **above Candle 3's high (+1 tick)** — the retest offered **multiple entries**
- **Stop:** above **Candle 1 / Candle 2's high** (or the swing high)
- **Partial:** at ~**50% / internal range low**. See [Internal Range Liquidity](../../concepts/internal-range-liquidity.md).
- **Trail & final exit:** at **external range liquidity** beyond the old low. See [External Range Liquidity](../../concepts/external-range-liquidity.md).
- **Result:** a move of **60+ handles in under 15 minutes**, with stops managed to avoid a premature exit.

---

## Stop Management (Why It Worked)

- Stops started **above the candle highs** at entry
- They were only **trailed lower once significant intermediate swing lows broke** — not tick-by-tick
- This kept the position alive through small pullbacks so it could reach [external range liquidity](../../concepts/external-range-liquidity.md)

See [Risk Management](../../concepts/risk-management.md).

---

## The Repeatable Sequence

```
Buy-stop run (post-8:30)  →  DISPLACEMENT closes below low  →  Bearish FVG (1–5 min)
→  limit short above Candle 3 high  →  partial at IRL (50%)  →  trail to ERL (final exit)
```

> No FVG inside a valid displacement range = no trade.

---

## Related Concepts

- [Market Efficiency Paradigm](../../concepts/market-efficiency-paradigm.md)
- [Liquidity](../../concepts/liquidity.md)
- [Multi-Timeframe Analysis](../../concepts/multi-timeframe-analysis.md)
- [Displacement](../../concepts/displacement.md)
- [Market Structure Shift](../../concepts/market-structure-shift.md)
- [Fair Value Gaps](../../concepts/fair-value-gaps.md)
- [Internal Range Liquidity](../../concepts/internal-range-liquidity.md)
- [External Range Liquidity](../../concepts/external-range-liquidity.md)
- [Risk Management](../../concepts/risk-management.md)

---

*Source: 2022 ICT Mentorship Episode 6 — Market Efficiency Paradigm & Institutional Order Flow*

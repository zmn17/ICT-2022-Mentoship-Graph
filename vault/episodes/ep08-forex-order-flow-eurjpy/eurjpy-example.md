# EUR/JPY — February 10, 2022 Walkthrough

> ← Back to [Episode 8 Hub](README.md) | [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship Episode 8 — *Institutional Order Flow in Forex (EUR/JPY)*
> **Instrument:** EUR/JPY

---

## Overview

A daily→intraday walkthrough on EUR/JPY anchored to the **February 10, 2022** daily candle, showing how correlation sets the bias, fair value gaps time the entry across sessions, and a Fibonacci standard-deviation projection sets the target.

---

## Stage 1 — Bias via Correlation

- **Euro (6E futures, continuous front month):** clear **uptrend** → Euro strength
- **Yen:** weak / consolidating
- Euro strong **+** Yen weak → **bullish bias on EUR/JPY**

> Reading the two underlying currencies gives a bias the cross's own chart may not obviously show. See [Intermarket Correlation](../../concepts/intermarket-correlation.md).

---

## Stage 2 — Daily Structure (anchor: Feb 10, 2022)

```
                          attempt higher (continuation)
                     ╱╲      ╱
        swing high  ╱  ╲    ╱   ← price breaks ABOVE swing highs = bullish structure
         ╱╲        ╱    ╲  ╱
   ─────╱  ╲──────╱  ┌───┐╱
                     │FVG│  ← fair value gap between legs (retrace target)
   relative equal lows ‾‾‾  ← support / liquidity reference
```

1. Mark **relative equal lows** (support / [liquidity](../../concepts/liquidity.md))
2. Price **rallies through swing highs** → confirms bullish [market structure](../../concepts/market-structure-shift.md)
3. **Fair value gaps** form between the legs — price retraces into them before continuing. See [Fair Value Gaps](../../concepts/fair-value-gaps.md).
4. Liquidity is **drawn to old highs** (buy stops), even if not immediately tagged

---

## Stage 3 — Intraday Timing (Sessions)

- **London (2–5 AM NY):** hunt for the FVG setup as price develops
- **New York (7–10 AM NY):** execute on the identified fair value gap
- Refine down **15m → 5m → 3m → 1m**, entering on the **retrace into the FVG** during the NY session

See [Trading Sessions](../../concepts/trading-sessions.md).

```
   NY session open
        │  price runs, takes swing lows/highs
        │   ┌──────┐
        │   │ FVG  │  ← long entry on retrace into the gap
        │   └──────┘
        ▼
```

---

## Stage 4 — Target with Fibonacci Std-Dev

Because the intraday chart had **no clean range** to project from:

```
   Swing High ───────────────  (Fib anchor end, post-consolidation)
        │
   Swing Low ────────────────  (Fib anchor start)
        │
        ▼ project standard deviation
   ── Std Dev -1 / Fib ≈ 133.15 ──  ← high-probability target
```

- Anchor the **Fib between the post-consolidation swing low and high**
- Project the **standard deviation −1**, landing near **133.15** — the logical target/stall zone

See [Fibonacci Targeting](../../concepts/fibonacci-targeting.md).

---

## The Repeatable Process

```
Correlation (EUR↑ via 6E + Yen↓) = bullish bias
→ daily break of swing highs + FVGs
→ London hunt / NY execute on FVG retrace
→ target via Fib std-dev (~133.15)
```

---

## Analytical Steps (from the episode)

| Step | Chart | Action |
|------|-------|--------|
| 1 | Daily | Identify relative equal lows |
| 2 | Daily | Mark swing highs; confirm breaks above = bullish |
| 3 | Daily | Locate fair value gaps between runs |
| 4 | 15-min | Track New York session open & rally |
| 5 | 5-min | Pinpoint further swing lows/highs; note FVGs |
| 6 | 3-min | Validate swing structure & entries around FVG |
| 7 | 1-min | Fine-tune entry timing within the FVG |

---

## Related Concepts

- [Intermarket Correlation](../../concepts/intermarket-correlation.md)
- [Market Structure Shift](../../concepts/market-structure-shift.md)
- [Liquidity](../../concepts/liquidity.md)
- [Fair Value Gaps](../../concepts/fair-value-gaps.md)
- [Trading Sessions](../../concepts/trading-sessions.md)
- [Fibonacci Targeting](../../concepts/fibonacci-targeting.md)

---

*Source: 2022 ICT Mentorship Episode 8 — Institutional Order Flow in Forex (EUR/JPY)*

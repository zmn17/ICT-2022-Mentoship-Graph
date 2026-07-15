# Fibonacci & Standard Deviation Targeting

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.

---

## What is Fibonacci Targeting?

When there is **no obvious range** on the intraday chart to project a target, Fibonacci retracement (anchored to a fresh swing) and **standard deviation projections** give a **quantitative** way to define where price may stall or reverse — i.e., logical exit levels.

---

## The Problem It Solves

- Without a clear high–low range, it's hard to know **how far** price will extend or retrace
- Guessing targets leads to premature exits or holding too long
- Fibonacci + standard deviations turn "how far?" into a **measured projection**

---

## How to Anchor the Fibonacci

1. Wait for a **swing low and swing high** to form **after consolidation**
2. Anchor the Fib **between that swing low and swing high**
3. Retracement levels frame **entries** (pullback zones)
4. **Standard deviation extensions** (projections beyond the range) frame **targets**

```
   Swing High ───────────────  (Fib anchor end)
        │   retracement zone = entry area
        │
   Swing Low ────────────────  (Fib anchor start)
        │
        ▼ project standard deviations DOWN (or up) for targets
   ── Std Dev -1 (e.g., 133.15) ──  ← high-probability target / stall zone
```

---

## Standard Deviation Projections

- Beyond the anchored swing, project **standard deviation multiples** (−1, −2, …) in the direction of the move
- These become **high-probability target zones** where price may stall or reverse
- Example from Episode 8: a **standard deviation −1 / Fib projection at ≈ 133.15** used as a target on EUR/JPY

| Reference | Role |
|-----------|------|
| Swing Low | Fib anchor start |
| Swing High | Fib anchor end |
| Std Dev −1 (≈133.15) | High-probability target / stall zone |

---

## When to Use It

- Intraday charts with **no clean range** to target
- Trending environments where you need a **projected** objective
- As a complement to liquidity-based targets ([internal](internal-range-liquidity.md) / [external range liquidity](external-range-liquidity.md)) — use whichever gives the clearer level

---

## Ep 16 — Anchor to Candle **Bodies**, Not Wicks

A precision refinement: anchor the Fibonacci to the **highest and lowest candle bodies** (open or close) of the swing — **never the wicks**.

> The measured move lands **exactly** on the day's low **only** when the correct **body-based fulcrum** is used.

- Use the body (open/close) as the fulcrum for both the high and low anchors
- This is the same swing-trading targeting model applied to intraday objectives (e.g., 4514 → 4501)
- Wick-based anchors misplace the projection

---

## How It Fits the Trade

```
Entry (FVG / retracement into Fib zone)  →  target = std-dev projection / next Fib level
```

- **Entry:** on a retracement into the Fib zone (often overlapping a [Fair Value Gap](fair-value-gaps.md))
- **Target/Exit:** the standard deviation projection or Fib extension
- Combine with [Risk Management](risk-management.md) for stop placement

---

## Ep 23 — Fibonacci Expansion & Wicks-vs-Bodies by Volatility

Beyond retracement/std-dev, **Fibonacci expansion** projects an **upside/continuation** target from a completed leg:

- Anchor from a **high to a low** (e.g., the 2:00 high → the post-2:30 low) and project the expansion **up** for the target (e.g., **13,437**)
- **Wicks vs. bodies rule keyed to volatility:**
  - **High-volatility** events (FOMC, NFP) → anchor to the **extremes (wicks)** — price uses the full range
  - **Normal** conditions → anchor to the **candle bodies** (open/close)
- Match the anchor to the expected volatility of the session

---

## Related Concepts

- [Fair Value Gaps](fair-value-gaps.md) — Entries often sit in the Fib retracement zone
- [Market Structure (Premium/Discount)](market-structure.md) — The 50% Fib is equilibrium
- [External Range Liquidity](external-range-liquidity.md) — Alternative (liquidity-based) targets
- [Risk Management](risk-management.md) — Pair projected targets with defined stops
- [Multi-Timeframe Analysis](multi-timeframe-analysis.md) — Anchor swings on the working timeframe

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 8 — Forex Order Flow (EUR/JPY)](../episodes/ep08-forex-order-flow-eurjpy/README.md) | Fib anchored swing-low→high; std-dev −1 ≈ 133.15 as the target when no clear range exists |

---

*Introduced in: 2022 ICT Mentorship Episode 8 — Institutional Order Flow in Forex (EUR/JPY)*

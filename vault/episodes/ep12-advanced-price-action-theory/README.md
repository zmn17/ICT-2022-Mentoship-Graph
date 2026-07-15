# Episode 12 — Advanced Price Action Theory

> ← Back to [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship [No Rant] Episode 12 ("Market Structure for Precision Technicians")
> **Instrument:** NASDAQ (NQ) March 2022

---

## What This Episode Teaches

The **advanced, algorithm-aware model of market structure** that replaces retail "higher-high/higher-low" with a **layered hierarchy** (long/intermediate/short-term). The signature idea: **rebalancing an old imbalance instantly creates an intermediate-term high/low**, and a **weak ITH** (one that fails to exceed neighboring short-term highs) reveals the algorithm's bearish hand. Blended with **institutional order flow** validation and **Fibonacci std-dev** targets.

---

## Learn the Concepts (Read in This Order)

```
1. Market Narrative / Draw on Liquidity → The one pre-trade question (bias)
2. Fair Value Gaps       → Imbalance; rebalancing it is the key event
3. Market Structure Hierarchy → LTH/ITH/STH; rebalance creates ITH/ITL; weak-ITH tell
4. Fractals              → Same pattern on every timeframe
5. Order Blocks          → Consecutive up-close candles (not the last one)
6. Institutional Order Flow → Up-closes must cap price when bearish (invalidation)
7. Fibonacci Targeting   → Std-dev projection anchored ITH → long-term low
```

| # | Concept | Link |
|---|---------|------|
| 1 | Draw on Liquidity | [../../concepts/draw-on-liquidity.md](../../concepts/draw-on-liquidity.md) |
| 2 | Fair Value Gaps | [../../concepts/fair-value-gaps.md](../../concepts/fair-value-gaps.md) |
| 3 | Market Structure Hierarchy | [../../concepts/market-structure-hierarchy.md](../../concepts/market-structure-hierarchy.md) |
| 4 | Fractals | [../../concepts/fractals.md](../../concepts/fractals.md) |
| 5 | Order Blocks | [../../concepts/order-blocks.md](../../concepts/order-blocks.md) |
| 6 | Institutional Order Flow | [../../concepts/institutional-order-flow.md](../../concepts/institutional-order-flow.md) |
| 7 | Fibonacci Targeting | [../../concepts/fibonacci-targeting.md](../../concepts/fibonacci-targeting.md) |
| — | Swing Points (foundation) | [../../concepts/swing-points.md](../../concepts/swing-points.md) |

---

## The Model (Step-by-Step)

### Stage 1 — The One Pre-Trade Question

| Step | Action | Concept |
|------|--------|---------|
| 1 | Ask: **what is the narrative & next draw on liquidity?** Up for buy-side / to rebalance a gap? Down for sell-side / to rebalance a gap below? | [Draw on Liquidity](../../concepts/draw-on-liquidity.md) |
| 2 | Remember the daily range **won't always** submit to a clean bullish/bearish open — consolidation happens. | — |

### Stage 2 — Read the Hierarchy

| Step | Action | Concept |
|------|--------|---------|
| 3 | Anchor the **long-term** high/low from the daily (e.g., the daily FVG boundary). | [Market Structure Hierarchy](../../concepts/market-structure-hierarchy.md) |
| 4 | Label an **ITH/ITL** at every **rebalance** of an old imbalance. | [Market Structure Hierarchy](../../concepts/market-structure-hierarchy.md) / [Fair Value Gaps](../../concepts/fair-value-gaps.md) |
| 5 | Check ITH **quality**: if it fails to exceed the neighboring STHs → **weak** → algorithm bearish. | [Market Structure Hierarchy](../../concepts/market-structure-hierarchy.md) |

### Stage 3 — Frame & Enter

| Step | Action | Concept |
|------|--------|---------|
| 6 | Mark the **hourly bearish order block** = the consecutive **up-close candles** (not the last one). | [Order Blocks](../../concepts/order-blocks.md) |
| 7 | Drop to 15/5/4-min; the same imbalance/rebalance appears as a **fractal** → aggressive entry. | [Fractals](../../concepts/fractals.md) |
| 8 | **Aggressive:** sell into the OB, stop just above the high. **Low-risk:** wait for the MSS + FVG retrace. | [Order Blocks](../../concepts/order-blocks.md) |

### Stage 4 — Validate & Target

| Step | Action | Concept |
|------|--------|---------|
| 9 | **Institutional order flow:** up-close candles must **cap** price. Breached → idea wrong → sit on hands. | [Institutional Order Flow](../../concepts/institutional-order-flow.md) |
| 10 | **Target:** anchor a Fib from the **ITH → long-term low**; read the **−1.5 std-dev** extension. | [Fibonacci Targeting](../../concepts/fibonacci-targeting.md) |

---

## This Model's Twist on the MSS

> In the strict model you wait for a **short-term low break** (the market structure shift) then short the retrace into the imbalance. **But** because the structure is already read as **weak** (a rebalanced imbalance with an unviolated ITH), the aggressive entry does **not** require the swing-low break — the FVG on the breakdown inside the order block is enough.

See [Market Structure Shift](../../concepts/market-structure-shift.md).

---

## Invalidation (Non-Negotiable)

```
Bearish idea valid WHILE: up-close candles cap price
                          next STH stays BELOW the ITH
Idea FLAWED IF:           an up-close is overtaken
                          price trades above the ITH
                          → sit on your hands
```

---

## Quick-Reference Checklist

```
□ Narrative & next draw on liquidity defined
□ Long-term high/low anchored from the daily
□ ITH/ITL labelled at each imbalance rebalance
□ ITH quality checked (weak ITH = bearish tell)
□ Bearish OB = consecutive up-close candles marked
□ Fractal entry refined on 15/5/4-min
□ Order flow intact (up-closes capping price)
□ Target projected ITH→LTL (−1.5 std dev)
□ Invalidation clear (up-close breach / ITH exceeded = stand down)
```

---

## Episode-Specific Content

| File | Content |
|------|---------|
| [NASDAQ Hierarchy Walkthrough](nasdaq-hierarchy-example.md) | Daily FVG → hourly OB → 15/5/4-min fractal entry with std-dev target |

---

## The Core Insight

> Structure isn't "higher-high/higher-low" — it's a **parent-child hierarchy** anchored to the daily's order flow. **Rebalancing an imbalance mints an intermediate-term high/low**; when that high is **weak**, the algorithm is showing its hand. Sell the consecutive-up-close **order block**, keep the trade only while up-closes **cap** price, and target the **ITH→LTL std-dev** projection.

---

*Source: 2022 ICT Mentorship Episode 12 — Advanced Price Action Theory*

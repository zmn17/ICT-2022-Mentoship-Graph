# Market Structure Hierarchy (LTH/ITH/STH & Rebalance Rule)

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.

---

## What is the Market Structure Hierarchy?

An **advanced** reading of structure that replaces the retail "higher-high / higher-low = uptrend" with a **three-tier, parent-child hierarchy** of swing points, anchored to the higher timeframe where the volume and institutional order flow live. Builds on [swing-points](swing-points.md) with the mechanics that define and validate each tier.

```
   Long-Term High (LTH)  ◉  ← higher-timeframe boundary (e.g., daily FVG)
        │
   Intermediate-Term High (ITH) ◎  ← highest high between two STHs
        │
   Short-Term High (STH) ○  ← a high between two lower highs
```

> "It's not just higher-high/higher-low — that's a pursuit of simplicity, not the truth." The daily is the **parent**; all lower-timeframe swings are **subordinate** to it.

---

## The Signature Rule: Rebalance Creates an ITH/ITL

> **The instant price trades back to fill an old imbalance, the swing formed at that moment is an intermediate-term high (or low).**

- Price fills an **upside** [fair value gap](fair-value-gaps.md) → the swing high there = an **intermediate-term high (ITH)**
- Price fills a **downside** gap → the swing low there = an **intermediate-term low (ITL)**

This is the mechanic that turns "rebalancing" into a **labelled, tradable level**.

---

## The Weak-ITH Tell (Algorithm Tipping Its Hand)

An **ideal** intermediate-term high sits **above** the short-term highs on both sides. When it does **not**:

```
   STH ○        ○ STH
        ╲  ITH ◎  ╱   ← ITH fails to exceed neighboring STHs
         ╲  ╱ ╲ ╱        = market is WEAK, algorithm tipping its hand
          ╲╱   ╲╱          → forecast a failed swing → bearish
```

> If the ITH is **not higher** than the two short-term highs, the market is **weak** — a bearish tell. Predictive use: once bearish, the next STH should be **lower** than that ITH; if price trades **above** it, your idea is probably **flawed** (stand down).

---

## Parent-Child & Order Flow

- Higher-timeframe swings are **parent** to lower-timeframe swings
- The **daily** carries the bulk of **volume** and **institutional/bank order flow** — that's where **bias** is set
- A valid trade must connect to something on the **daily** (the LTH/LTL are usually tied to it)
- A 1-minute swing matters only **within** the daily context

---

## How to Use It

1. Anchor the **long-term** high/low from the higher timeframe (e.g., daily FVG)
2. Label **ITH/ITL** at each **rebalance** of an old imbalance
3. Check ITH **quality**: above both neighboring STHs = healthy; not = weak (bearish tell)
4. Trade toward the [draw on liquidity](draw-on-liquidity.md); use the weak ITH as a **key level that must not be violated**
5. Project targets with [Fibonacci](fibonacci-targeting.md) anchored **ITH → long-term low**

---

## Related Concepts

- [Swing Points & Nested Structure](swing-points.md) — The STH/ITH/LTH definitions this builds on
- [Fair Value Gaps](fair-value-gaps.md) — Rebalancing a gap creates the ITH/ITL
- [Fractals](fractals.md) — The same rebalance logic on every timeframe
- [Institutional Order Flow](institutional-order-flow.md) — Validates the weak-ITH read
- [Draw on Liquidity](draw-on-liquidity.md) — The directional objective
- [Fibonacci Targeting](fibonacci-targeting.md) — ITH→LTL std-dev projection

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 12 — Advanced Price Action Theory](../episodes/ep12-advanced-price-action-theory/README.md) | The core lesson: LTH/ITH/STH hierarchy; rebalance creates ITH/ITL; weak-ITH tell |
| [Ep 13 — Advanced Price Action Theory In Action](../episodes/ep13-advanced-price-action-in-action/README.md) | Applying the hierarchy live |

---

*Introduced in: 2022 ICT Mentorship Episode 12 — Advanced Price Action Theory*

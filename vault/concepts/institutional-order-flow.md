# Institutional Order Flow (Candle Validation)

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.

---

## What is Institutional Order Flow?

A validation lens: while a directional idea is active, specific candles should **behave as support or resistance**. If they don't, the idea is likely wrong. It's the running "is my thesis still valid?" check that keeps you out of forced trades.

---

## The Two Rules

| Bias | Rule | Meaning |
|------|------|---------|
| **Bearish** | **Up-close candles must cap price** | Up-closes act as speed bumps / resistance that price never overtakes |
| **Bullish** | **Down-close candles must support price** | Down-closes act as support that price never trades below |

```
   BEARISH idea:                 BULLISH idea:
   up-close ▲ caps price         price holds above
   ─────────────── resistance    ─────────────── support
        price stays below              down-close ▼ supports
```

---

## The Invalidation Rule

> While bearish, up-close candles should act as **resistance that price never overtakes**. If they are **breached**, the analysis is likely **wrong** — **sit on your hands** rather than force the trade.

This is the discipline half: order flow doesn't just confirm entries, it tells you **when to stand down**. Ties to the [weak-ITH](market-structure-hierarchy.md) rule — if the next short-term high exceeds the intermediate-term high, the idea is flawed.

---

## Why It Works

- Institutions defend the levels they're delivering from; **respected** up/down closes = order flow intact
- A **breach** means the delivering side has stepped back → your side is losing
- Provides an **objective invalidation** without an arbitrary stop distance

---

## How to Use It

1. Establish bias ([draw on liquidity](draw-on-liquidity.md) / [hierarchy](market-structure-hierarchy.md))
2. Bearish → mark the **up-close candles**; they should **cap** price (and form the [order block](order-blocks.md))
3. Bullish → mark the **down-close candles**; they should **support** price
4. Hold while they're respected; **stand down** the moment they're breached

---

## Related Concepts

- [Order Blocks](order-blocks.md) — The consecutive up/down closes that should hold
- [Market Structure Hierarchy](market-structure-hierarchy.md) — Weak-ITH invalidation pairs with this
- [State of Delivery](state-of-delivery.md) — The algorithmic buy/sell offering behind the candles
- [Displacement](displacement.md) — Confirms order flow in your favor
- [Risk Management](risk-management.md) — Objective invalidation = where you're wrong

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 12 — Advanced Price Action Theory](../episodes/ep12-advanced-price-action-theory/README.md) | Up-close candles must cap price when bearish; breach = wrong, sit on hands |

---

*Introduced in: 2022 ICT Mentorship Episode 12 — Advanced Price Action Theory*

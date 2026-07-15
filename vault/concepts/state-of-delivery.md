# State of Delivery (& HFT Algorithms)

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.

---

## What is the State of Delivery?

State of Delivery describes the **algorithmic behavior of price quoting at sequentially higher or lower prices** — it tells you whether the market is currently offering **buy-side** liquidity (delivering higher) or **sell-side** liquidity (delivering lower). A change in the state of delivery marks a shift in market bias.

```
   Offering higher prices in sequence  → BUY-SIDE delivery (bullish state)
   Offering lower prices in sequence   → SELL-SIDE delivery (bearish state)
```

---

## How the State Shifts

The state of delivery is anchored to a key **candle opening price**:

- While price holds **above** that opening price → buy-side offering (bullish delivery)
- When price trades **below** that opening price → the state **flips** to sell-side offering (bearish delivery)

This flip is exactly what an [order block](order-blocks.md) marks, and it underpins a [market structure shift](market-structure-shift.md).

---

## Order Blocks as the Footprint of a Delivery Shift

From Episode 3, order blocks are defined through the lens of state of delivery:

- A **bearish order block** = a series of **down-close candles** beginning at a candle opening price that gets violated → signals a shift to **sell-side** delivery
- A **bullish order block** = a sequence of **up-close candles** offering buy-side liquidity, beginning at a specific candle's open → signals **buy-side** delivery

The **opening price** of that origin candle is significant: it's the line that, once crossed, flips the delivery state. See [Order Blocks](order-blocks.md).

---

## High-Frequency Trading (HFT) Algorithms

The state of delivery is driven by HFT algorithms operating on very short timeframes (3-, 2-, 1-minute):

- HFT algos **identify and exploit liquidity pools** by continuously offering prices near key levels
- Their behavior shows up as **rapid order injections** (buy or sell) that don't necessarily push price beyond a level, but instead **accumulate liquidity** or **induce slippage**
- This is why the finest structure is read on the lowest timeframes — you're watching the algo quote

| HFT Behavior | Effect |
|--------------|--------|
| Rapid order injection near a level | Accumulates liquidity without breaking the level |
| Quoting sequentially higher/lower | Establishes/continues the state of delivery |
| Sweeping stops then reversing | Triggers a [market structure shift](market-structure-shift.md) |

---

## Why It Matters

- Reading the state of delivery tells you the **momentum and likely price path**
- A change in state is an **early warning** of a bias shift — often before it's obvious on higher timeframes
- Combined with [internal range liquidity](internal-range-liquidity.md), it lets you anticipate reversals at liquidity levels

---

## How to Read It in Practice

1. Mark the origin candle's **opening price** of the current move
2. While price respects that open, delivery continues in that direction
3. When price violates the open (and forms an opposing [order block](order-blocks.md)), delivery has flipped
4. Confirm with a [market structure shift](market-structure-shift.md) and a [fair value gap](fair-value-gaps.md)
5. Trade in the direction of the new delivery state

---

## Related Concepts

- [Order Blocks](order-blocks.md) — The visible footprint of a delivery-state change
- [Market Structure Shift](market-structure-shift.md) — What a delivery flip produces intraday
- [Internal Range Liquidity](internal-range-liquidity.md) — The pools HFT algos target
- [Fair Value Gaps](fair-value-gaps.md) — Imbalances left by rapid delivery
- [Stop Hunts](stop-hunts.md) — HFT-driven sweeps that precede a state change

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 3 — Internal Range Liquidity & MSS](../episodes/ep03-internal-range-liquidity-mss/README.md) | Delivery state (buy/sell offering) anchored to order-block opening prices; HFT algos on 3/2/1-min |

---

*Introduced in: 2022 ICT Mentorship Episode 3 — Internal Range Liquidity & Market Structure Shifts*

# E-mini Nasdaq — Worked Example (14,600 / 14,820)

> ← Back to [Episode 3 Hub](README.md) | [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship Episode 3 — *Internal Range Liquidity & Market Structure Shifts*
> **Instrument:** E-mini Nasdaq 100 Futures (NQ)

---

## Overview

This example shows how internal range liquidity and an intraday market structure shift combine into a trade, using the price levels from the episode: sell stops near **14,600** and buy stops near **14,820**.

---

## Stage 1 — The Liquidity Map (15-min)

```
   ══════════════════════════════  Relative Equal Highs  ≈ 14,820
        BUY STOPS (liquidity above)
        → target for an upside hunt


                [ intraday range ]


        SELL STOPS (liquidity below)
   ──────────────────────────────  Old Lows  ≈ 14,600
```

| Level | Type | Role |
|-------|------|------|
| ~14,820 | Buy stops above relative equal highs | Upside liquidity target |
| ~14,600 | Sell stops below old lows | Downside liquidity target |

See [Internal Range Liquidity](../../concepts/internal-range-liquidity.md).

---

## Stage 2 — The Stop Hunt

- Price runs **up into ~14,820**, sweeping the buy stops above the relative equal highs
- This is a **liquidity run** — the market reaching for the obvious pool
- Late buyers get filled at the highs; the algorithm now has the liquidity it needs to sell

See [Stop Hunts](../../concepts/stop-hunts.md).

---

## Stage 3 — The Market Structure Shift (3/2/1-min)

```
   ══════════════════  14,820  ← buy stops swept
        ╱╲
       ╱  ╲            ← price fails, prints a LOWER HIGH
      ╱    ╲
   ──╱      ╲───────
             ╲
   ─ ─ ─ ─ ─ ─╲─ ─ ─  ← breaks short-term low
               ▼          = MARKET STRUCTURE SHIFT (now bearish)
```

1. After sweeping 14,820, price **fails to continue** and prints a lower high
2. It **breaks a short-term swing low** on the 3/2/1-min → the intraday bias has **shifted bearish**
3. The candle that violated the prior **opening price** marks a **bearish order block** — the [state of delivery](../../concepts/state-of-delivery.md) has flipped to sell-side

See [Market Structure Shift](../../concepts/market-structure-shift.md) and [Order Blocks](../../concepts/order-blocks.md).

---

## Stage 4 — Entry & Target

```
   ┌───────────────┐  ← Bearish order block (opening price)
   │   FVG / IMB   │  ← Limit SELL a few ticks into the imbalance
   └───────────────┘
           │
           ▼   price delivers lower (new sell-side state)
           ▼
   ─ ─ ─ ─ ─ ─ ─ ─  ← 50% equilibrium: take partials
           ▼
   ══════════════════  14,600  ← Target: sell stops below old lows
```

- **Entry:** limit order **inside the fair value gap**, a few ticks below the bearish order-block opening price
- **Partial exit:** at the **50% equilibrium** between the prior swing high and low
- **Final target:** the opposite pool — **sell stops near 14,600**

See [Fair Value Gaps](../../concepts/fair-value-gaps.md) and [Market Structure (Premium/Discount)](../../concepts/market-structure.md).

---

## The Sequence in One Line

```
Sweep 14,820 buy stops → fail + lower high → break short-term low (MSS)
→ bearish order block / FVG → limit short → partials at 50% → target 14,600
```

---

## Why It Repeats

Per the episode, this is a **repeatable** intraday mechanic driven by HFT [state of delivery](../../concepts/state-of-delivery.md). Backtest it: mark internal range liquidity on the 15-min, watch for the sweep in the **8:30–11 AM** window, and confirm the shift on the 1–3 min. See [Trading Sessions](../../concepts/trading-sessions.md).

---

## Related Concepts

- [Internal Range Liquidity](../../concepts/internal-range-liquidity.md)
- [Stop Hunts](../../concepts/stop-hunts.md)
- [Market Structure Shift](../../concepts/market-structure-shift.md)
- [State of Delivery](../../concepts/state-of-delivery.md)
- [Order Blocks](../../concepts/order-blocks.md)
- [Fair Value Gaps](../../concepts/fair-value-gaps.md)
- [Market Structure (Premium/Discount)](../../concepts/market-structure.md)
- [Trading Sessions](../../concepts/trading-sessions.md)

---

*Source: 2022 ICT Mentorship Episode 3 — Internal Range Liquidity & Market Structure Shifts*

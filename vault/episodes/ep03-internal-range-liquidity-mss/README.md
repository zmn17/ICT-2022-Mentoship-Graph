# Episode 3 — Internal Range Liquidity & Market Structure Shifts

> ← Back to [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship [No Rant] Episode 3
> **Instrument:** E-mini Nasdaq 100 Futures (NQ) — 15-min, refined on 3/2/1-min

---

## What This Episode Teaches

How to read **intraday market structure shifts** driven by **internal range liquidity**. You learn to spot the stop hunts around old lows and relative equal highs, recognize when the algorithm flips its state of delivery, and time entries on the 3-, 2-, and 1-minute charts using fair value gaps and order blocks.

---

## Learn the Concepts (Read in This Order)

```
1. Internal Range Liquidity → The old lows / equal highs the market targets
2. Stop Hunts              → How those pools get swept
3. Market Structure Shift  → The intraday bias flip after the sweep
4. State of Delivery       → How the algorithm flips buy/sell offering
5. Order Blocks            → The footprint of that delivery shift
6. Fair Value Gaps         → Your lower-timeframe entry
7. Trading Sessions        → When to trade (8:30–11) and avoid (noon–1)
```

| # | Concept | Link |
|---|---------|------|
| 1 | Internal Range Liquidity | [../../concepts/internal-range-liquidity.md](../../concepts/internal-range-liquidity.md) |
| 2 | Stop Hunts | [../../concepts/stop-hunts.md](../../concepts/stop-hunts.md) |
| 3 | Market Structure Shift | [../../concepts/market-structure-shift.md](../../concepts/market-structure-shift.md) |
| 4 | State of Delivery | [../../concepts/state-of-delivery.md](../../concepts/state-of-delivery.md) |
| 5 | Order Blocks | [../../concepts/order-blocks.md](../../concepts/order-blocks.md) |
| 6 | Fair Value Gaps | [../../concepts/fair-value-gaps.md](../../concepts/fair-value-gaps.md) |
| 7 | Trading Sessions | [../../concepts/trading-sessions.md](../../concepts/trading-sessions.md) |

---

## Key Distinction: Shift vs. Break

> This episode stresses that a **Market Structure Shift** (intraday bias change) is **NOT** the same as a **Break of Structure** (longer-term, multi-day continuation). Don't use the terms interchangeably.
>
> Compare: [Market Structure Shift](../../concepts/market-structure-shift.md) vs. [Market Structure Break](../../concepts/market-structure-break.md)

---

## The Entry Model (Step-by-Step)

### Stage 1 — Map Internal Range Liquidity (15-min)

| Step | Action | Concept |
|------|--------|---------|
| 1 | On the **15-min**, mark **sell stops** below old lows (e.g., ~14,600). | [Internal Range Liquidity](../../concepts/internal-range-liquidity.md) |
| 2 | Mark **buy stops** above relative equal highs (e.g., ~14,820). | [Internal Range Liquidity](../../concepts/internal-range-liquidity.md) |
| 3 | Confirm you're in a prime session window (**8:30–11 AM ET**). | [Trading Sessions](../../concepts/trading-sessions.md) |

### Stage 2 — Wait for the Stop Hunt

| Step | Action | Concept |
|------|--------|---------|
| 4 | Watch price **sweep** one pool (e.g., run buy stops above equal highs). | [Stop Hunts](../../concepts/stop-hunts.md) |
| 5 | The sweep = liquidity being run. Do NOT chase it. | [Stop Hunts](../../concepts/stop-hunts.md) |

### Stage 3 — Confirm the Shift (3/2/1-min)

| Step | Action | Concept |
|------|--------|---------|
| 6 | Drop to **3/2/1-min**. Watch for price to fail and print a lower high (bearish) or higher low (bullish). | [Market Structure Shift](../../concepts/market-structure-shift.md) |
| 7 | Confirm the **shift**: break of a short-term swing in the new direction. | [Market Structure Shift](../../concepts/market-structure-shift.md) |
| 8 | Identify the **order block** where delivery flipped (violated opening price). | [State of Delivery](../../concepts/state-of-delivery.md) / [Order Blocks](../../concepts/order-blocks.md) |

### Stage 4 — Execute

| Step | Action | Concept |
|------|--------|---------|
| 9 | Mark the **Fair Value Gap** left by the shift displacement. | [Fair Value Gaps](../../concepts/fair-value-gaps.md) |
| 10 | Place a **limit order inside the FVG** — a few ticks above/below the order-block opening price. | [Fair Value Gaps](../../concepts/fair-value-gaps.md) |
| 11 | **Target:** the opposite liquidity pool; take **partials at equilibrium (50%)** between the prior swing high/low. | [Market Structure (P/D)](../../concepts/market-structure.md) |

---

## Trade Execution Logic (From the Episode)

- When price breaches **below sell stops** → anticipate a reversal signaled by a **bearish order block** forming
- When price breaks **above buy stops** → anticipate buying pressure, then a **bearish shift** once the market prints lower highs
- Use **limit orders inside fair value gaps**, entering slightly above/below key levels (e.g., buy a few ticks above an order-block opening)
- Plan **partial exits** at subsequent liquidity zones or the **50% equilibrium** level

---

## Session Focus

| Window | Action |
|--------|--------|
| **8:30 – 11:00 AM ET** | Prime — highest-probability setups |
| **Noon – 1:00 PM ET** | **Avoid** — problematic liquidity |
| **2:00 – 4:00 PM ET** | Afternoon — secondary setups, distinct strategy |

See [Trading Sessions](../../concepts/trading-sessions.md).

---

## Quick-Reference Checklist

```
□ Internal range liquidity mapped on 15-min (old lows + relative equal highs)
□ In the prime window (8:30–11 AM ET)
□ A liquidity pool was swept (stop hunt)
□ Market structure shift confirmed on 3/2/1-min (lower high + break, or higher low + break)
□ Order block identified (delivery state flipped at a violated opening price)
□ Fair value gap marked for entry
□ Limit order set inside FVG (few ticks beyond OB open)
□ Target = opposite pool; partials at 50% equilibrium
```

---

## Homework Assignment (From the Episode)

1. Review historical E-mini intraday data, especially **8:30–11 AM ET**
2. Annotate **buy-side and sell-side liquidity pools** on the 15-min timeframe
3. Drill to **3/2/1-min** to observe price interacting with those pools
4. Identify the **stop hunts** that trigger structure shifts, noting the simultaneous **FVGs and order blocks**
5. Record examples in a **study journal** with detailed annotations and reflections

---

## Episode-Specific Content

| File | Content |
|------|---------|
| [NASDAQ Worked Example (14,600 / 14,820)](nasdaq-example.md) | The E-mini example the episode walks through |

---

## The Core Insight

> Intraday market structure shifts reveal smart-money liquidity tactics *before* price reverses. Spot the stop hunt around old lows / relative equal highs, confirm the shift with an order block + FVG on the 1–3 min, and trade with the new state of delivery.

---

*Source: 2022 ICT Mentorship Episode 3 — Internal Range Liquidity & Market Structure Shifts*

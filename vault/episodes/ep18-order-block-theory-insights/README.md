# Episode 18 — Additional Insights Into Order Block Theory

> ← Back to [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship [No Rant] Episode 18
> **Instrument:** EUR/USD

---

## What This Teaches

A complete top-down EUR/USD short that **deepens order block theory**. The core rules reinforced: an **order block is only valid with an imbalance**, it represents a **change in the state of delivery** (algo flips buy→sell once price trades below the OB candle's open and breaks structure), and entries must be **defined limits placed and managed within a kill zone**.

---

## Learn the Concepts (Read in This Order)

```
1. Daily Bias          → Bearish → only hunt shorts
2. Market Structure (P/D) → 5 down days = discount; retrace into daily FVG = premium to sell
3. Liquidity           → Previous daily highs/lows = HFT liquidity targets
4. Fair Value Gaps     → Parent (15m) governs subordinate (5m); OB needs an imbalance
5. Order Blocks        → Bearish OB = 3 candles ending at lowest down-close (valid only w/ imbalance)
6. State of Delivery   → OB = the buy→sell delivery flip (internal MSS)
7. Opening Price + Kill Zone → NY midnight divider; work/pull the limit in the 7–10 window
8. Risk Management     → Stop above the imbalance / swing high (ITH must not be violated)
```

| # | Concept | Link |
|---|---------|------|
| 1 | Daily Bias | [../../concepts/daily-bias.md](../../concepts/daily-bias.md) |
| 2 | Market Structure (Premium/Discount) | [../../concepts/market-structure.md](../../concepts/market-structure.md) |
| 3 | Liquidity | [../../concepts/liquidity.md](../../concepts/liquidity.md) |
| 4 | Fair Value Gaps | [../../concepts/fair-value-gaps.md](../../concepts/fair-value-gaps.md) |
| 5 | Order Blocks | [../../concepts/order-blocks.md](../../concepts/order-blocks.md) |
| 6 | State of Delivery | [../../concepts/state-of-delivery.md](../../concepts/state-of-delivery.md) |
| 7 | Opening Price / Kill Zone | [../../concepts/opening-price.md](../../concepts/opening-price.md) · [Sessions](../../concepts/trading-sessions.md) |
| 8 | Risk Management | [../../concepts/risk-management.md](../../concepts/risk-management.md) |
| — | Market Structure Hierarchy (parent/subordinate) | [../../concepts/market-structure-hierarchy.md](../../concepts/market-structure-hierarchy.md) |

---

## The Entry Model (Step-by-Step)

| Step | Action | Concept |
|------|--------|---------|
| 1 | **Daily bias bearish** → hunt shorts only. | [Daily Bias](../../concepts/daily-bias.md) |
| 2 | After **5 down days**, price is in **discount** → a retrace into the **daily FVG** (premium) is the sell staging area. | [Market Structure](../../concepts/market-structure.md) |
| 3 | Frame with **previous daily high/low** (HFT liquidity): premium to sell, discount to target. | [Liquidity](../../concepts/liquidity.md) |
| 4 | Drop hourly → 15-min: **NY midnight divider**, relative equal highs (liquidity), **displacement lower** confirms. | [Opening Price](../../concepts/opening-price.md) |
| 5 | Treat the **15-min imbalance as parent**; split into the **5-min** for the fine entry. | [Market Structure Hierarchy](../../concepts/market-structure-hierarchy.md) / [Fair Value Gaps](../../concepts/fair-value-gaps.md) |
| 6 | Identify the **bearish order block** = 3 consecutive candles ending at the lowest down-close — **valid only because an imbalance exists in it**. | [Order Blocks](../../concepts/order-blocks.md) |
| 7 | The OB = a **change in state of delivery** (algo flips buy→sell once price trades below the OB candle's open + breaks structure). Any rally after = a **suspect rally** setting up a deeper move. | [State of Delivery](../../concepts/state-of-delivery.md) |
| 8 | **Entry:** sell limit at the **lower FVG** (not the overzealous top — avoids missed trades). **Stop:** above the imbalance / swing high (an **ITH** that must not be violated). | [Risk Management](../../concepts/risk-management.md) |
| 9 | **Work and pull** the order within the **NY kill zone (7–10 AM)** — time-based management. | [Trading Sessions](../../concepts/trading-sessions.md) |

---

## The Order Block Rules (Reinforced)

```
An order block is VALID only if it contains an IMBALANCE (no imbalance = no OB)
An order block = a CHANGE IN THE STATE OF DELIVERY
  (algo flips buy→sell once price trades below the OB candle's open + breaks structure)
Higher-timeframe imbalance = PARENT; refine the entry on the subordinate lower timeframe
Entry limit at the LOWER FVG (not the top); stop above the imbalance/swing high
Work & pull the order inside the KILL ZONE
```

---

## Quick-Reference Checklist

```
□ Daily bias bearish (shorts only)
□ Discount after down days → retrace into daily FVG (premium) = sell staging
□ Framed by previous daily high/low (HFT liquidity)
□ Displacement lower + NY midnight divider on 15-min
□ Parent 15m imbalance → refine on 5m
□ Bearish OB validated by an imbalance within it
□ Sell limit at the lower FVG; stop above imbalance/swing high
□ Order worked & pulled inside the 7–10 AM kill zone
```

---

## Episode-Specific Content

| File | Content |
|------|---------|
| [EUR/USD OB Short Walkthrough](eurusd-ob-short.md) | Daily FVG → 15m/5m bearish OB → kill-zone limit entry |

---

## The Core Insight

> An **order block is not just a candle** — it's a **change in the state of delivery**, and it's only valid **with an imbalance**. Frame the bearish EUR/USD short with premium/discount and previous daily highs/lows, let the **parent** imbalance govern the **subordinate** timeframe, place a **defined limit** at the lower FVG with a stop above the swing high, and **work it within the kill zone**.

---

*Source: 2022 ICT Mentorship Episode 18 — Additional Insights Into Order Block Theory*

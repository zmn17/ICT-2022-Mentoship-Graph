# Episode 9 — Power of 3 & NY PM Session Opportunities

> ← Back to [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship [No Rant] Episode 9
> **Instrument:** NASDAQ E-mini Futures (NQ)

---

## What This Episode Teaches

A **complete intraday entry model** for NASDAQ futures, exploiting algorithmic liquidity hunts in the New York PM session using the Power of 3 framework (Accumulation → Manipulation → Distribution).

---

## Learn the Concepts (Read in This Order)

```
1. Market Structure    → Where am I? (discount or premium)
2. Power of 3         → What phase is the market in?
3. Liquidity          → What's being hunted and why?
4. Order Blocks       → Where do I enter?
5. Fair Value Gaps    → How do I refine that entry?
6. NY PM Session      → When do I enter?
7. Risk Management    → What's my stop and target?
```

| # | Concept | Link |
|---|---------|------|
| 1 | Market Structure | [../../concepts/market-structure.md](../../concepts/market-structure.md) |
| 2 | Power of 3 | [../../concepts/power-of-3.md](../../concepts/power-of-3.md) |
| 3 | Liquidity | [../../concepts/liquidity.md](../../concepts/liquidity.md) |
| 4 | Order Blocks | [../../concepts/order-blocks.md](../../concepts/order-blocks.md) |
| 5 | Fair Value Gaps | [../../concepts/fair-value-gaps.md](../../concepts/fair-value-gaps.md) |
| 6 | NY PM Session | [new-york-pm-session.md](new-york-pm-session.md) |
| 7 | Risk Management | [../../concepts/risk-management.md](../../concepts/risk-management.md) |

---

## The Entry Model (Step-by-Step)

### Pre-Session (Before 9:30 AM ET)

| Step | Action | Concept |
|------|--------|---------|
| 1 | Draw the daily swing high-to-low. Mark the **50% Fibonacci**. | [Market Structure](../../concepts/market-structure.md) |
| 2 | Determine bias: Below 50% = **bullish** (look for longs). Above = bearish. | [Market Structure](../../concepts/market-structure.md) |
| 3 | Note overnight/London runs. If a **strong run already happened**, plan to wait. | [NY PM Session](new-york-pm-session.md) |

### Morning (9:30 AM – 12:00 PM ET) — Observe, Don't Chase

| Step | Action | Concept |
|------|--------|---------|
| 4 | Watch for the **manipulation move** — a sweep below short-term lows (if bullish). | [Power of 3](../../concepts/power-of-3.md) / [Liquidity](../../concepts/liquidity.md) |
| 5 | Identify where **sell-side liquidity** was taken (relative equal lows, session lows). | [Liquidity](../../concepts/liquidity.md) |
| 6 | Do NOT enter yet. Let the morning chop play out. | [Risk Management](../../concepts/risk-management.md) |

### Lunch (12:00 – 1:00 PM ET) — Patience

| Step | Action | Concept |
|------|--------|---------|
| 7 | Mark the **lunch consolidation range** (high and low of 12:00–1:00 PM). | [NY PM Session](new-york-pm-session.md) |
| 8 | New liquidity is building below the lunch low. Wait for it to be swept. | [Liquidity](../../concepts/liquidity.md) |

### PM Session (1:00 – 3:00 PM ET) — Execute

| Step | Action | Concept |
|------|--------|---------|
| 9 | Wait for price to **sweep the lunch low** (take sell-side liquidity). | [Liquidity](../../concepts/liquidity.md) |
| 10 | On the 5-min chart, identify the **bullish order block** price is entering. | [Order Blocks](../../concepts/order-blocks.md) |
| 11 | Confirm a **fair value gap** overlaps or sits adjacent to the OB. | [Fair Value Gaps](../../concepts/fair-value-gaps.md) |
| 12 | **Enter long** near the bottom of the order block. | [Order Blocks](../../concepts/order-blocks.md) |
| 13 | **Stop loss:** Just below the OB low. | [Risk Management](../../concepts/risk-management.md) |
| 14 | **Target:** Buy-side liquidity above (morning high, daily level, or 3:1+ R:R). | [Risk Management](../../concepts/risk-management.md) |

---

## No-Trade Conditions

- ❌ Strong overnight run already occurred → Wait, don't chase
- ❌ Choppy/sideways price action → No edge, no trade
- ❌ No liquidity sweep has occurred → No entry signal
- ❌ After 3:00 PM ET → Too late
- ❌ R:R less than 3:1 → Structure doesn't support the trade

---

## Quick-Reference Checklist

```
□ Daily bias confirmed (discount = long, premium = short)
□ Manipulation complete (liquidity swept)
□ Entry at 5-min order block
□ Fair value gap provides confluence
□ Stop below structural level (OB low)
□ R:R is 3:1 or better
□ Time is 1:00–3:00 PM ET
□ No kill-switch conditions present
```

---

## Episode-Specific Content

| File | Content |
|------|---------|
| [NY PM Session Strategy](new-york-pm-session.md) | Session timing, rules, when to avoid |
| [Feb 14–15 Session Analysis](session-analysis-feb-2022.md) | Real trade examples with timelines and parameters |

---

## Key Quantitative Data (From This Episode)

| Metric | Value |
|--------|-------|
| Risk per trade | ~14.25 NQ points |
| Contracts | 6 micro NQ |
| Dollar risk | ~$85 |
| Dollar target | ~$300 |
| R:R | ~3.5:1 |

---

## The Core Insight

> Algorithmic market behavior creates predictable liquidity runs. The edge isn't prediction — it's **patience**. Wait for manipulation to complete, enter at structure, and let distribution carry you to target.

---

*Source: 2022 ICT Mentorship Episode 9 — Power of 3 & New York PM Session Opportunities*

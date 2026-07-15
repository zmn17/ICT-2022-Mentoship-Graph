# Episode 33 — More Insights On FVG & Intraday Market Structure

> ← Back to [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship [No Rant] Episode 33
> **Instrument:** Index futures (ES)

---

## What This Teaches

The **methodology** behind FVG trading, via a Friday teardown. Price ran up into a **deeper fair value gap** to set the **high of the day**, broke the pre-marked **3915.25**, then delivered lower through sell-side toward **3855**. The core lesson: ICT does **not** trade **break-and-retest / support-resistance** — he trades **imbalances**. A broken level **only earns trust when an FVG is present**. Pre-classify levels, but **key off the imbalance, not the level**.

---

## Learn the Concepts (Read in This Order)

```
1. Fair Value Gaps     → The primary decision object (trade the imbalance, not the level)
2. Intraday Market Structure → Top-down (hourly → 15 → 5 → lower); break gives permission
3. Liquidity           → Levels just highlight where liquidity rests
4. Market Structure (P/D) → Premium/discount, equilibrium (50%), dealing range
5. Draw on Liquidity   → Gravitate from one pool to the opposite
6. Algorithmic Programs → 3:00 spool into the close
```

| # | Concept | Link |
|---|---------|------|
| 1 | Fair Value Gaps | [../../concepts/fair-value-gaps.md](../../concepts/fair-value-gaps.md) |
| 2 | Market Structure Shift | [../../concepts/market-structure-shift.md](../../concepts/market-structure-shift.md) |
| 3 | Liquidity | [../../concepts/liquidity.md](../../concepts/liquidity.md) |
| 4 | Market Structure (Premium/Discount) | [../../concepts/market-structure.md](../../concepts/market-structure.md) |
| 5 | Draw on Liquidity | [../../concepts/draw-on-liquidity.md](../../concepts/draw-on-liquidity.md) |
| 6 | Algorithmic Programs | [../../concepts/algorithmic-programs.md](../../concepts/algorithmic-programs.md) |
| — | Swing Points / Multi-Timeframe | [Swing Points](../../concepts/swing-points.md) · [Multi-TF](../../concepts/multi-timeframe-analysis.md) |

---

## The Day (Top-Down)

| Step | Action | Concept |
|------|--------|---------|
| 1 | **Hourly:** consolidation, then a run up into a **deeper FVG** forming the **high of the day**. | [Fair Value Gaps](../../concepts/fair-value-gaps.md) |
| 2 | Wait for the **break of the pre-marked 3915.25** — the required trigger (don't act during the chop above). | [Market Structure Shift](../../concepts/market-structure-shift.md) |
| 3 | **15-min:** once 3915.25 broke, **sell-side taken**, market works lower toward **3855**. | [Liquidity](../../concepts/liquidity.md) |
| 4 | **5-min:** equilibrium at **50%** of the leg; after **3:00** price drops into the FVG. | [Market Structure](../../concepts/market-structure.md) |
| 5 | Algorithms **spool into the close** toward an hourly level. | [Algorithmic Programs](../../concepts/algorithmic-programs.md) |

---

## The Methodology (The Real Lesson)

> **This is NOT break-and-retest or support/resistance.** A broken old low/high is **only meaningful if a fair value gap exists there**. Pre-classify levels (3915.25, 3872.25, 3855) — but **key off the imbalance, not the level**. The level just **highlights where liquidity rests**; the **FVG** is the true focus.

- Price may **overshoot** a marked level (3872.25) *into the imbalance* before delivering lower
- After returning into an FVG, price should **move quickly away** toward the **opposite liquidity pool**
- A short-term **dealing range** (swing high → swing low) with an **FVG inside** + a confluence level = the frame

See [Fair Value Gaps](../../concepts/fair-value-gaps.md).

---

## Quick-Reference Checklist

```
□ Top-down: hourly → 15 → 5 → lower
□ HOD formed by a deeper FVG (premium cap)
□ Pre-marked level (3915.25) BREAK = the trigger (don't act in the chop)
□ Sell-side taken → deliver toward the next pool (3855)
□ Trade the IMBALANCE, not the level (no FVG = don't trust the level)
□ Returned-into FVG should move quickly away → opposite pool
□ 3:00 spool into the close
```

---

## Episode-Specific Content

| File | Content |
|------|---------|
| [ES FVG Teardown (3915.25 → 3855)](es-fvg-teardown.md) | The break + delivery lower, keyed off imbalances not levels |

---

## The Core Insight

> **Trade imbalances, not levels.** A broken level is only trustworthy if a **fair value gap** justifies the reaction. Pre-mark levels to know *where liquidity rests*, but **key off the FVG** — price runs into a deeper gap for the high, breaks your level, and **delivers from imbalance to imbalance** toward the opposite liquidity pool.

---

*Source: 2022 ICT Mentorship Episode 33 — More Insights On FVG & Intraday Market Structure*

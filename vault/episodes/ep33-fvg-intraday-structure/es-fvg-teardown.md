# ES FVG Teardown (3915.25 → 3855)

> ← Back to [Episode 33 Hub](README.md) | [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship Episode 33 — *More Insights On FVG & Intraday Market Structure*
> **Instrument:** Index futures (ES)

---

## Hourly → The Break

```
   ┌────────┐ deeper FVG → HIGH OF DAY (premium cap)
   │  FVG   │
   └────────┘
        │  (consolidation above — do NOT act here)
   ── 3915.25 ──  ← pre-marked level; its BREAK = the trigger
        ▼ sell-side taken → work lower
   3872.25 ─── (price overshoots this level INTO the imbalance, then delivers lower)
        ▼
   3855 ═══════  next liquidity pool (target)
```

- HOD formed by a run into a **deeper FVG** (premium). See [Fair Value Gaps](../../concepts/fair-value-gaps.md).
- Refused to act during the **chop above** — waited for the **3915.25 break** (didn't want to catch a break of a short-term low only to see relative equal highs run). See [Market Structure Shift](../../concepts/market-structure-shift.md).

---

## 15-min / 5-min Delivery

```
   3915.25 broke → sell-side taken
        ▼ deliver lower toward 3855
   5-min: equilibrium at 50% of the leg
   after 3:00 → drop into the FVG → algos SPOOL into the close
```

- Once 3915.25 broke, sell-side was taken and price worked toward **3855**. See [Liquidity](../../concepts/liquidity.md).
- **Equilibrium (50%)** frames premium/discount of the leg. See [Market Structure](../../concepts/market-structure.md).
- After **3:00**, price dropped into the FVG and **spooled into the close**. See [Algorithmic Programs](../../concepts/algorithmic-programs.md).

---

## The Methodology (Why This Matters)

> **Not break-and-retest.** The broken 3915.25 / 3872.25 levels are only meaningful because **fair value gaps** justify the reactions. Price **overshoots** a round level *into the imbalance* before delivering — the **imbalance dictates** where delivery pauses/resumes, not the level. Pre-classify levels to know *where liquidity is*, but **key off the FVG**.

```
No FVG at a broken level → don't trust it.
FVG present → the level's reaction is validated → trade the imbalance.
```

---

## The Repeatable Read

```
Deeper FVG = HOD → break pre-marked level (trigger) → sell-side taken
→ deliver imbalance-to-imbalance toward the opposite pool (3855) → 3:00 spool into close
(trade the IMBALANCE, not the level)
```

---

## Related Concepts

- [Fair Value Gaps](../../concepts/fair-value-gaps.md)
- [Market Structure Shift](../../concepts/market-structure-shift.md)
- [Liquidity](../../concepts/liquidity.md) · [Draw on Liquidity](../../concepts/draw-on-liquidity.md)
- [Market Structure (Premium/Discount)](../../concepts/market-structure.md)
- [Algorithmic Programs](../../concepts/algorithmic-programs.md)
- [Swing Points](../../concepts/swing-points.md) · [Multi-Timeframe Analysis](../../concepts/multi-timeframe-analysis.md)

---

*Source: 2022 ICT Mentorship Episode 33 — More Insights On FVG & Intraday Market Structure*

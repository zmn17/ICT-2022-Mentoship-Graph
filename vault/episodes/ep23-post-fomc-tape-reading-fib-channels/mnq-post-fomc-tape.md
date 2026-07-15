# MNQ Post-FOMC Tape Walkthrough

> ← Back to [Episode 23 Hub](README.md) | [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship Episode 23 — *Post FOMC Live Tape Reading + FIB Channels*
> **Instrument:** Micro Nasdaq 100 (MNQ)

---

## Wait Out the FOMC Shakeout

```
   FOMC release ─┐
                 │ 1. kneejerk leg
                 │ 2. another leg
                 │ 3. FAKE-OUT leg   ← noise (don't trade)
                 │ 4. REAL setup     ← this is what we annotate
```

FOMC delivers price in **staged legs** (like NFP). Wait a few minutes for the initial shakeout. See [Economic Calendar](../../concepts/economic-calendar.md).

---

## Annotate the Path In Advance

```
   untraded HTF FVG ┌──────┐  ← don't overshoot this ("upsets the FVG")
                    │ FVG  │  bounce off hidden OB up INTO here = sets stage for decline
                    └──────┘
        ╲  short at FVG edge / bearish OB (stop above recent green candle)
         ╲
   ── turquoise sell-side pool ──  (may sweep)
   ┌──────────────────┐
   │ BLUE checkered-   │  ← "end of the road" for the drop
   │ flag zone (OB)    │     then price should RUN Tuesday's highs
   └──────────────────┘
   bullseye OB below short-term low (risk of early reversal)
```

- The **untraded higher-timeframe FVG** is the magnet; its bottom edge acts as **support/resistance** for shorts. See [Fair Value Gaps](../../concepts/fair-value-gaps.md).
- Marked the **blue zone / bearish order block** as the end of the drop, forecast **before** price got there. See [Tape Reading](../../concepts/tape-reading.md) / [Order Blocks](../../concepts/order-blocks.md).

---

## Sweep vs. Run

```
   SWEEP old high: ──╱╲── shallow reverse   → FADE
   RUN Tuesday high: ──╱──▶ through & go    → FOLLOW (the forecast)
```

See [Liquidity](../../concepts/liquidity.md).

---

## The Fib Expansion Target

```
   2:00 high ─────────
        │  anchor high → low (use WICKS — FOMC volatility uses extremes)
   post-2:30 low ─────
        │ project expansion UP
   13,437 ◄─────────  target reached
```

Fibonacci **expansion** from the 2:00 high to the post-2:30 low projects the upside target **13,437**; because it's FOMC, anchor to the **wicks** (extremes), not bodies. See [Fibonacci Targeting](../../concepts/fibonacci-targeting.md).

---

## Full Sequence Recap

```
FOMC shakeout (wait) → run on liquidity → bearish order block + untraded FVG
→ forecast drop into the blue zone → respect zone, turn
→ run Tuesday's high → Fib expansion target 13,437
```

Price respected the pre-drawn plan — the diagram dropped **before** price confirmed it.

---

## Related Concepts

- [Economic Calendar](../../concepts/economic-calendar.md)
- [Tape Reading](../../concepts/tape-reading.md)
- [Fair Value Gaps](../../concepts/fair-value-gaps.md)
- [Order Blocks](../../concepts/order-blocks.md)
- [Liquidity](../../concepts/liquidity.md)
- [Draw on Liquidity](../../concepts/draw-on-liquidity.md)
- [Fibonacci Targeting](../../concepts/fibonacci-targeting.md)

---

*Source: 2022 ICT Mentorship Episode 23 — Post FOMC Live Tape Reading + FIB Channels*

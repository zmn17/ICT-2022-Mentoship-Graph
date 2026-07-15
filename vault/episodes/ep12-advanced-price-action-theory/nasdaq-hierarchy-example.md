# NASDAQ Hierarchy Walkthrough (Daily → 4-min)

> ← Back to [Episode 12 Hub](README.md) | [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship Episode 12 — *Advanced Price Action Theory*
> **Instrument:** NASDAQ (NQ) March 2022

---

## Daily — Bias & the Long-Term Boundary

- Start **inside the daily fair value gap**; map its high/low onto the hourly. See [Fair Value Gaps](../../concepts/fair-value-gaps.md).
- The **low end of the daily gap** is a **discount** where price finds support. See [Market Structure](../../concepts/market-structure.md).
- Pre-trade question: **what's the next draw on liquidity?** Here, bias forms toward the downside draw. See [Draw on Liquidity](../../concepts/draw-on-liquidity.md).
- The daily carries the **volume & institutional order flow** → it's the **parent** for all lower-timeframe swings.

---

## Hourly — Hierarchy & the Weak ITH

```
   LTH ◉ ─────────────  (tied to daily FVG boundary)
        STH ○      ○ STH
              ◎ ITH   ← only REBALANCES the gap; does NOT exceed
             ╱  ╲        the neighboring short-term highs
   ─────────╱    ╲       = WEAK intermediate-term high
                  ╲        → algorithm tipping its bearish hand
   ITL ◎ (from a downside gap rebalance)
```

1. Rebalancing the old imbalance **mints an intermediate-term high** at that swing. See [Market Structure Hierarchy](../../concepts/market-structure-hierarchy.md).
2. That ITH **fails to rise above** the short-term highs on both sides → **weak** → forecast a failed swing (bearish).
3. The forming **consecutive up-close candles** = the **hourly bearish order block** (not just the last one). See [Order Blocks](../../concepts/order-blocks.md).

---

## 15 / 5 / 4-min — Fractal Entry

```
   15-min: ┌──┐ one-candle imbalance  ← same pattern as the hourly (fractal)
           │FVG│
           └──┘
             ↓ rebalance = aggressive entry
   breakdown INSIDE the up-close order block
   (no short-term low break required — structure already weak)
```

- The small 15-min imbalance is a **fractal** of the hourly move. See [Fractals](../../concepts/fractals.md).
- **Aggressive entry:** sell into the order block, stop **just above the high**.
- **Low-risk entry:** wait for the market structure shift (short-term low break) + FVG retrace. See [Market Structure Shift](../../concepts/market-structure-shift.md).

---

## Validation — Institutional Order Flow

```
   up-close ▲ ─────── must CAP price (resistance)
        price stays below  ✔ → thesis intact, hold
        price overtakes it ✘ → thesis wrong, SIT ON HANDS
```

While bearish, the up-close candles must **cap** price, and the next STH must stay **below** the ITH. Breach either → stand down. See [Institutional Order Flow](../../concepts/institutional-order-flow.md).

---

## Target — Fibonacci Std-Dev (ITH → LTL)

```
   ITH ◎ ──────────  (anchor start — where the failed retrace begins)
        │
        ▼ project standard deviations
   LTL ◉ ──────────  (anchor end — long-term low)
        │
   −1.5 std dev ─────  ← projected downside target
```

Anchor the Fib **from the intermediate-term high (not the extreme high) down to the long-term low**; the **−1.5 standard-deviation** extension gives the downside objective. See [Fibonacci Targeting](../../concepts/fibonacci-targeting.md).

---

## The Repeatable Sequence

```
Daily FVG (bias/draw) → hourly rebalance mints a WEAK ITH
→ consecutive up-close order block → fractal FVG entry (aggressive/low-risk)
→ hold while up-closes cap price → target ITH→LTL −1.5 std dev
```

---

## Related Concepts

- [Draw on Liquidity](../../concepts/draw-on-liquidity.md)
- [Fair Value Gaps](../../concepts/fair-value-gaps.md)
- [Market Structure Hierarchy](../../concepts/market-structure-hierarchy.md)
- [Swing Points & Nested Structure](../../concepts/swing-points.md)
- [Fractals](../../concepts/fractals.md)
- [Order Blocks](../../concepts/order-blocks.md)
- [Institutional Order Flow](../../concepts/institutional-order-flow.md)
- [Market Structure Shift](../../concepts/market-structure-shift.md)
- [Fibonacci Targeting](../../concepts/fibonacci-targeting.md)

---

*Source: 2022 ICT Mentorship Episode 12 — Advanced Price Action Theory*

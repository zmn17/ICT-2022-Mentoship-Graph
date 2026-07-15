# ES Premium/Discount Long

> ← Back to [Episode 36 Hub](README.md) | [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship Episode 36 — *Trading Example Premium/Discount*
> **Instrument:** Index futures (ES)

---

## Hourly — Define the Range & Equilibrium

```
   swing HIGH ═══════  ← morning high = DRAW (deep premium target)
        │  PREMIUM (above 50%)
   ── equilibrium (50% Fib) ──
        │  DISCOUNT (below 50%)
   ┌──────┐ discount FVG = OVERSOLD (no indicator needed)
   │ FVG  │
   └──────┘
   swing LOW ════════
```

- Range = **swing low → swing high**; Fib → **equilibrium (50%)**. Rectangle/Fib are just visual aids; the condition = **price vs equilibrium**, **no indicator**. See [Market Structure](../../concepts/market-structure.md).
- Price into a **discount FVG** = **oversold** → stage for a move to **premium**. See [Fair Value Gaps](../../concepts/fair-value-gaps.md).

---

## 5-min / 1-min — Liquidity Engineered

```
   9:30: aggressive slide takes out relative equal lows (SELL-SIDE) — a stop run
        │  (no clean model entry on the down move = the TELL: just clearing liquidity)
        ▼
   shift in market structure → rebalance the drop into a 5-min FVG
   ┌──────┐
   │ FVG  │ ← 1-min: BUY the swept sell stops (take some heat)
   └──────┘
        ▲ rally through FVGs / OB / imbalance / equal highs
   morning high ═══════  ← DRAW reached (deep premium)
```

- **9:30** aggressive slide sweeps **sell-side** below relative equal lows. See [Liquidity](../../concepts/liquidity.md).
- The **no-model-entry** down move = the algorithm **tipping its hand** while clearing liquidity. See [Institutional Order Flow](../../concepts/institutional-order-flow.md) / [Tape Reading](../../concepts/tape-reading.md).
- **Shift in market structure** + **rebalance into a 5-min FVG** → **buy the swept sell stops** (accept heat) → rally to the **morning high**. See [Market Structure Shift](../../concepts/market-structure-shift.md) / [Optimal Trade Entry](../../concepts/optimal-trade-entry.md) / [Draw on Liquidity](../../concepts/draw-on-liquidity.md).

---

## The Repeatable Read

```
Range (low→high) + equilibrium → price in discount FVG = oversold
→ 9:30 sweeps sell-side (stop run, no clean entry = tell) → MSS + rebalance FVG
→ buy swept sell stops (heat) → rally to morning high (deep premium draw)
```

---

## Related Concepts

- [Market Structure (Premium/Discount)](../../concepts/market-structure.md)
- [Fair Value Gaps](../../concepts/fair-value-gaps.md)
- [Liquidity](../../concepts/liquidity.md)
- [Market Structure Shift](../../concepts/market-structure-shift.md)
- [Draw on Liquidity](../../concepts/draw-on-liquidity.md)
- [Optimal Trade Entry](../../concepts/optimal-trade-entry.md)
- [Institutional Order Flow](../../concepts/institutional-order-flow.md) · [Tape Reading](../../concepts/tape-reading.md) · [Order Blocks](../../concepts/order-blocks.md)

---

*Source: 2022 ICT Mentorship Episode 36 — Trading Example Premium/Discount*

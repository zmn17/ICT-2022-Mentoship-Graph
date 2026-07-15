# EUR/USD Order Block Short Walkthrough

> ← Back to [Episode 18 Hub](README.md) | [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship Episode 18 — *Additional Insights Into Order Block Theory*
> **Instrument:** EUR/USD

---

## Daily — Bias, Discount & the Sell Staging Area

```
   prev daily HIGH ═══════  premium (sell into) / HFT liquidity
   ┌────────┐
   │ daily  │ FVG  ← price retraces UP into here = sell staging (premium)
   │  FVG   │
   └────────┘
        │  (5 down days → price in DISCOUNT → retrace likely)
        ▼
   prev daily LOW ═══════  discount TARGET / HFT liquidity
```

- **Daily bias bearish** → shorts only. See [Daily Bias](../../concepts/daily-bias.md).
- Five down days → **discount** → a retrace into the **daily FVG** (premium) is the ideal sell staging area, not a reversal. See [Market Structure](../../concepts/market-structure.md).
- Frame with **previous daily high/low** — HFT algorithms attack them. See [Liquidity](../../concepts/liquidity.md).

---

## 15-min — Displacement & the NY Kill Zone

```
   NY midnight divider │        relative equal highs ═══ (liquidity)
                       │   ╱╲
                       │  ╱  ╲  displacement LOWER (confirms)
   ────────────────────╲╱    ╲___ fresh 15m FVG (parent imbalance)
   NY Open Kill Zone 7–10 AM
```

- **NY midnight** divides the day; relative equal highs sit as a liquidity pool. See [Opening Price](../../concepts/opening-price.md).
- **Displacement lower** breaks a swing low and leaves a **15-min imbalance** — the **parent** governing the 5-min. See [Market Structure Hierarchy](../../concepts/market-structure-hierarchy.md).

---

## 5-min — The Bearish Order Block

```
   ┌─────────────┐
   │ up  up  DOWN│  ← bearish OB = 3 candles ending at the lowest down-close
   └─────────────┘     VALID only because an imbalance exists within it
        │  OB = change in STATE OF DELIVERY:
        │  algo flips buy→sell once price trades below the OB candle's open + breaks structure
        ▼  any rally after = a SUSPECT rally → deeper move lower
```

See [Order Blocks](../../concepts/order-blocks.md) and [State of Delivery](../../concepts/state-of-delivery.md).

---

## Entry, Stop & Kill-Zone Management

```
   stop ── above the imbalance / swing high (ITH — must not be violated)
   ┌──────────┐  small FVG (price may tag it → include in risk)
   │ lower FVG│  ← SELL LIMIT here (not the overzealous top → avoids missed trades)
   └──────────┘
        ▼ distribute down to the previous daily low (discount target)
```

- **Entry:** sell limit at the **lower FVG**; if a small gap sits just above, **incorporate it into risk**.
- **Stop:** above the imbalance / swing high (an intermediate-term high that shouldn't be violated). See [Risk Management](../../concepts/risk-management.md).
- **Time management:** work and **pull** the order within the **NY kill zone (7–10 AM)**. See [Trading Sessions](../../concepts/trading-sessions.md).

---

## The Repeatable Sequence

```
Daily bearish + discount → retrace into daily FVG (premium) framed by prev daily H/L
→ 15m displacement + NY midnight → parent imbalance
→ 5m bearish OB (valid w/ imbalance = state-of-delivery flip)
→ sell limit at lower FVG, stop above swing high → work in kill zone → target prev daily low
```

---

## Related Concepts

- [Daily Bias](../../concepts/daily-bias.md)
- [Market Structure (Premium/Discount)](../../concepts/market-structure.md)
- [Liquidity](../../concepts/liquidity.md)
- [Fair Value Gaps](../../concepts/fair-value-gaps.md)
- [Order Blocks](../../concepts/order-blocks.md)
- [State of Delivery](../../concepts/state-of-delivery.md)
- [Market Structure Hierarchy](../../concepts/market-structure-hierarchy.md)
- [Opening Price References](../../concepts/opening-price.md)
- [Trading Sessions](../../concepts/trading-sessions.md)
- [Risk Management](../../concepts/risk-management.md)

---

*Source: 2022 ICT Mentorship Episode 18 — Additional Insights Into Order Block Theory*

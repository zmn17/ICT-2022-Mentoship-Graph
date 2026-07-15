# External Range Liquidity (ERL)

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.

---

## What is External Range Liquidity?

External Range Liquidity (ERL) is the liquidity resting **beyond** an established range — past the prior high or low — that signals a **major move** when reached. It is the counterpart to [Internal Range Liquidity](internal-range-liquidity.md) (IRL), which sits *within* the range. Together, IRL and ERL form the backbone of an **exit strategy**.

---

## IRL vs. ERL

| | [Internal Range Liquidity (IRL)](internal-range-liquidity.md) | External Range Liquidity (ERL) |
|---|---|---|
| **Location** | Within the high–low range (e.g., a fair value gap, 50% level) | Beyond the range — past old highs/lows |
| **Signals** | A **retracement** / partial move | A **major** directional move |
| **Use in a trade** | **Initial** profit-taking (~50% retrace level) | **Trailing stops** and **final** exit target |

```
        ══════════════  OLD HIGH  ← External liquidity (buy stops)  ▲ ERL target
             │
             │   ┌─────────┐  ← FVG / 50% = Internal liquidity (IRL)
   range     │   │  IRL    │     initial profit-taking
             │   └─────────┘
             │
        ──────────────  OLD LOW   ← External liquidity (sell stops)  ▼ ERL target
```

---

## How ERL Drives Exits

From Episode 6's trade-management model:

1. **Initial profit-taking** happens at [internal range liquidity](internal-range-liquidity.md) — around the **50% retracement** of the move
2. **Trailing and final exits** happen at **external range liquidity** — beyond the established low (for shorts) or high (for longs)
3. Reaching ERL signals the **major move** is complete — take the final exit there

---

## Trailing Logic with ERL

- Do **not** trail stops tick-by-tick
- Only trail lower (for a short) once a **significant intermediate low** (swing low) is broken
- Use the sequence of broken internal lows as the path toward the **external** low
- The external low/high is your **final objective**; ERL is where the move exhausts

See [Risk Management](risk-management.md) for the full stop-management approach.

---

## Where ERL Sits in the Framework

```
Entry (at FVG)  →  IRL (50% / internal low) = partial exit
                →  ERL (beyond old low/high) = trail + final exit
```

- [Fair Value Gaps](fair-value-gaps.md) → the entry
- [Internal Range Liquidity](internal-range-liquidity.md) → the first target
- **External Range Liquidity** → the last target

---

## Related Concepts

- [Internal Range Liquidity](internal-range-liquidity.md) — The within-range counterpart (first target)
- [Liquidity](liquidity.md) — The broader sell-side/buy-side framework
- [Risk Management](risk-management.md) — Trailing stops toward ERL
- [Fair Value Gaps](fair-value-gaps.md) — The entry that ERL targets away from
- [Daily Range](daily-range.md) — ERL often aligns with range extremes

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 6 — Market Efficiency Paradigm & FVG](../episodes/ep06-market-efficiency-paradigm-fvg/README.md) | Exit model: IRL (~50%) for partials, ERL for trailing & final exit |

---

*Introduced in: 2022 ICT Mentorship Episode 6 — Market Efficiency Paradigm & Institutional Order Flow*

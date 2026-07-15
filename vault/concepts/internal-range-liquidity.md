# Internal Range Liquidity (IRL)

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.

---

## What is Internal Range Liquidity?

Internal Range Liquidity refers to the pools of resting stop orders that sit **at defined levels within a trading range** — the sell stops below old lows and buy stops above relative equal highs that the market targets before reversing. These are the intraday liquidity pools that fuel [market structure shifts](market-structure-shift.md).

---

## The Two Pools

```
   ══════════════════════════  Relative Equal Highs
        BUY STOPS (liquidity above)          e.g., 14,820
        → attracts buying pressure
        → target for an UPSIDE liquidity hunt


                  [ trading range ]


        SELL STOPS (liquidity below)         e.g., 14,600
        → incentivizes selling pressure
        → target for a DOWNSIDE liquidity hunt
   ──────────────────────────  Old Lows / Last Swing Lows
```

| Liquidity Type | Location | Example Level | Behavior |
|----------------|----------|---------------|----------|
| **Buy stops** (liquidity above) | Above relative equal highs / last swing highs | ~14,820 | Target for an upside hunt; attracts buying pressure |
| **Sell stops** (liquidity below) | Below old lows / last swing lows | ~14,600 | Target for a downside hunt; incentivizes selling pressure |

*(Levels from the Episode 3 E-mini Nasdaq example.)*

---

## Why These Levels Matter

- Liquidity below the old low **incentivizes selling pressure** — the market is drawn there to run sell stops
- Liquidity above relative equal highs **attracts buying pressure** — the market is drawn there to run buy stops
- When these stops are taken out intraday, it signals **liquidity is being run**, often immediately followed by a [market structure shift](market-structure-shift.md)

---

## Relative Equal Highs / Lows

**Relative equal highs** (or lows) are two or more swing points at approximately the same price. They are prime internal-range liquidity because:

- They are **obvious** to retail traders, who cluster stops just beyond them
- This concentrates liquidity into a clean, targetable pool
- Algorithms specifically engineer moves to run these levels

---

## How to Use IRL in Trading

1. On the **15-minute** chart, mark buy-side and sell-side liquidity pools (old lows, relative equal highs)
2. Treat these as **primary trade triggers** — expect [stop hunts](stop-hunts.md) around them
3. When a level is breached intraday, drop to the **3-/2-/1-minute** charts to confirm price action
4. Look for a [market structure shift](market-structure-shift.md) + [FVG](fair-value-gaps.md) + [order block](order-blocks.md) after the sweep
5. Target the **opposite** pool, or the [equilibrium (50%)](market-structure.md) level, for partial exits

---

## IRL and Efficient Price Delivery

After stops are taken, the market often reverses to **fill [fair value gaps](fair-value-gaps.md)** or reach equilibrium. Internal range liquidity and imbalances work together: the stops give the algorithm a reason to reach a level; the imbalances give it a reason to come back.

---

## IRL vs. External Range Liquidity (Exit Model)

Episode 6 pairs IRL with its counterpart, [External Range Liquidity (ERL)](external-range-liquidity.md), to build an exit strategy:

- **Internal Range Liquidity (IRL)** — *within* the range (a [FVG](fair-value-gaps.md), the 50% level) → used for **initial profit-taking**
- **[External Range Liquidity (ERL)](external-range-liquidity.md)** — *beyond* the range (past old highs/lows) → used for **trailing stops and the final exit**

```
Entry (at FVG) → IRL (~50% / internal low) = partial → ERL (beyond old low/high) = final
```

---

## Related Concepts

- [Liquidity](liquidity.md) — The broader sell-side/buy-side framework
- [External Range Liquidity](external-range-liquidity.md) — The beyond-range counterpart (final target)
- [Market Structure Shift](market-structure-shift.md) — Triggered when IRL is run
- [Stop Hunts](stop-hunts.md) — The mechanism that consumes IRL
- [Fair Value Gaps](fair-value-gaps.md) — Where price returns after taking IRL
- [Market Structure (Premium/Discount)](market-structure.md) — Equilibrium as a target
- [State of Delivery](state-of-delivery.md) — How the algo flips after running IRL

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 3 — Internal Range Liquidity & MSS](../episodes/ep03-internal-range-liquidity-mss/README.md) | Old lows (~14,600) and relative equal highs (~14,820) as the primary intraday liquidity targets |
| [Ep 6 — Market Efficiency Paradigm & FVG](../episodes/ep06-market-efficiency-paradigm-fvg/README.md) | IRL (~50% retrace) as the initial profit-taking target, paired with ERL for the final exit |

---

*Introduced in: 2022 ICT Mentorship Episode 3 — Internal Range Liquidity & Market Structure Shifts*

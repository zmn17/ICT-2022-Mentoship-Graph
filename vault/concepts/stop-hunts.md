# Stop Hunts (Liquidity Engineering)

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.

---

## What is a Stop Hunt?

A stop hunt is an **engineered price move** designed to trigger resting stop orders on one side of the market before price reverses to make its real move. It is the mechanism by which large institutional/algorithmic participants generate the [liquidity](liquidity.md) they need to fill big orders — at the expense of trapped retail traders.

> "Stop hunts before significant directional moves are an essential liquidity engine designed to **induce retail trader participation on the wrong side**."

---

## The Two-Sided Stop Hunt

A classic stop hunt attacks **both** sides in sequence:

```
                          ╔══════════════╗
              buy stops → ║  old high     ║ ← price runs UP to
              triggered   ╚══════════════╝    trigger buy stops
                    ▲                          (traps late longs)
                    │
   consolidation ───┤
                    │
                    ▼
              ┌──────────────┐
  sell stops →│  short-term  │ ← price first drives DOWN to
  triggered   │     low      │    trigger sell stops
              └──────────────┘    (traps late shorts)
```

**Sequence:**
1. Market first drives **lower** to trigger sell stops under a short-term low
2. Then reverses and **runs higher** to trigger buy stops resting above a short-term high
3. These clean daily structure levels are the liquidity the algorithm was targeting

---

## Why Stop Hunts Happen

- Large players need **counterparties** (liquidity) to fill size without excessive slippage
- Resting stop orders provide exactly that: a cluster of market orders waiting to trigger
- By pushing price into these clusters, the algorithm **manufactures** the liquidity it needs
- This behavior benefits institutional/algorithmic traders and creates the environment to **enter alongside smart money**

---

## The Key Trading Insight

> **Before a significant market move, expect a stop hunt designed to induce retail traders onto the wrong side of the market.**

So when you see price sweep an obvious low (or high) and reverse sharply — that's not random. It's the liquidity engine firing. The real move typically follows **in the opposite direction** of the final hunt.

---

## Where Stop Hunts Fit in the Setup

Stop hunts are one of the repeatable "fingerprints" of a valid setup:

1. **A run on the opposite side's stop orders** ← this concept
2. A [market structure break](market-structure-break.md) confirming continuation
3. Price retracing into an [imbalance](fair-value-gaps.md) before continuation

In the [top-down framework](multi-timeframe-analysis.md), stop hunts are typically observed on the **hourly chart** — where the overnight consolidation attacks one side before running to the other.

---

## Stop Hunt vs. Liquidity

- [Liquidity](liquidity.md) = the resting stop orders themselves (the fuel)
- **Stop hunt** = the engineered move that triggers/consumes that liquidity (the ignition)

They are two sides of the same mechanism. Liquidity is *what* gets taken; the stop hunt is *how*.

---

## How to Trade Around Stop Hunts

1. Identify obvious [liquidity](liquidity.md) pools (old highs/lows, short-term swing points)
2. **Wait** for price to sweep one side — do not front-run it
3. Look for a [market structure break](market-structure-break.md) confirming the reversal
4. Enter on the retracement into the resulting [FVG](fair-value-gaps.md)
5. Position with the smart money, against the trapped retail crowd

---

## Related Concepts

- [Liquidity](liquidity.md) — The stop orders that hunts target
- [Market Structure Break](market-structure-break.md) — Confirms the direction after the hunt
- [Fair Value Gaps](fair-value-gaps.md) — Entry zone left by the post-hunt displacement
- [Multi-Timeframe Analysis](multi-timeframe-analysis.md) — Hunts observed on the hourly chart
- [Power of 3](power-of-3.md) — The stop hunt is the "manipulation" phase

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 2 — Elements To A Trade Setup](../episodes/ep02-elements-to-a-trade-setup/README.md) | Overnight drive to sell stops, then run to buy stops before the real move |
| [Ep 3 — Internal Range Liquidity & MSS](../episodes/ep03-internal-range-liquidity-mss/README.md) | Sweeping old lows / relative equal highs to trigger a market structure shift |
| [Ep 5 — Intraday Order Flow & Daily Range](../episodes/ep05-intraday-order-flow-daily-range/README.md) | Swing-point violation that ignites an afternoon buy/sell program |
| [Ep 7 — Daily Bias & Consolidation](../episodes/ep07-daily-bias-consolidation/README.md) | Sell-side sweep of an old low that becomes a fake break (Dow divergence) |
| [Ep 9 — Power of 3 & NY PM Session](../episodes/ep09-power-of-3-ny-pm/README.md) | The "manipulation" phase; sweeping lunch lows before PM distribution |
| [Ep 10 — Economic Calendar & Power Three](../episodes/ep10-economic-calendar-power-three/README.md) | Sell-stop hunt below short-term lows; news as smokescreen for the run |

---

*Introduced in: 2022 ICT Mentorship Episode 2 — Elements To A Trade Setup*

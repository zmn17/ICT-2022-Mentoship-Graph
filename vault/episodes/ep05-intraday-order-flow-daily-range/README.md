# Episode 5 — Intraday Order Flow & Daily Range

> ← Back to [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship [No Rant] Episode 5
> **Instruments:** Index futures — E-mini S&P 500, Nasdaq, Dow, Russell 2000

---

## What This Episode Teaches

How to trade index futures intraday using **order flow + daily range structure**. It splits the day into a **morning** and **afternoon** session (with an untradeable lunch hour), and gives a distinct entry model for each, built on swing-point liquidity, three drives, displacement, and fair value gaps.

---

## Learn the Concepts (Read in This Order)

```
1. Index Futures Contracts → Trade the right (liquid) front-month contract
2. Trading Sessions        → Morning / lunch (avoid) / afternoon + 1:30 macro
3. Liquidity               → Swing highs/lows = buy/sell stop pools
4. Three Drives            → A pattern that builds liquidity into a level
5. Stop Hunts              → How that liquidity gets grabbed
6. Displacement            → The energetic break that leaves an FVG
7. Fair Value Gaps         → Your entry zone on the retrace
8. Algorithmic Programs    → Afternoon buy/sell programs, spooling, MOC
9. Daily Range             → Morning + afternoon moves, measured-move targets
```

| # | Concept | Link |
|---|---------|------|
| 1 | Index Futures Contracts | [../../concepts/index-futures-contracts.md](../../concepts/index-futures-contracts.md) |
| 2 | Trading Sessions | [../../concepts/trading-sessions.md](../../concepts/trading-sessions.md) |
| 3 | Liquidity | [../../concepts/liquidity.md](../../concepts/liquidity.md) |
| 4 | Three Drives | [../../concepts/three-drives.md](../../concepts/three-drives.md) |
| 5 | Stop Hunts | [../../concepts/stop-hunts.md](../../concepts/stop-hunts.md) |
| 6 | Displacement | [../../concepts/displacement.md](../../concepts/displacement.md) |
| 7 | Fair Value Gaps | [../../concepts/fair-value-gaps.md](../../concepts/fair-value-gaps.md) |
| 8 | Algorithmic Programs | [../../concepts/algorithmic-programs.md](../../concepts/algorithmic-programs.md) |
| 9 | Daily Range | [../../concepts/daily-range.md](../../concepts/daily-range.md) |

---

## Timeframes

- **15-minute** = the baseline ("bellwether") for major swing highs/lows and order-flow imbalances
- **5-minute** = fine entry timing
- Set all charts to **New York local time** to synchronize analysis

---

## Session Map (New York Time)

| Session | Time | Guidance |
|---------|------|----------|
| **Morning** | 8:30 AM – Noon | Main active window; reacts to 8:30 news — focus here |
| **Lunch** | Noon – 1:00 PM | Quiet/choppy — **no-trade zone** |
| **Afternoon** | 1:00 PM – Close (~4:00) | Activity resumes; **1:30 PM macro**; MOC ramp into close |

See [Trading Sessions](../../concepts/trading-sessions.md).

---

## The MORNING Entry Model (8:30 AM – Noon)

| Step | Action | Concept |
|------|--------|---------|
| 1 | **Before 8:30**, mark the significant prior **swing high and low** on the 15-min. | [Liquidity](../../concepts/liquidity.md) |
| 2 | Identify the liquidity pools: **buy stops** above the swing high, **sell stops** below the swing low. | [Liquidity](../../concepts/liquidity.md) |
| 3 | Watch for a **three drives** push into an old high (or low) building liquidity. | [Three Drives](../../concepts/three-drives.md) |
| 4 | Spot the **stop hunt** — a breakout of the swing point, taken with **displacement** (energetic, not mild). | [Stop Hunts](../../concepts/stop-hunts.md) / [Displacement](../../concepts/displacement.md) |
| 5 | Mark the **Fair Value Gap** the displacement leaves behind. | [Fair Value Gaps](../../concepts/fair-value-gaps.md) |
| 6 | **Enter on the retracement into the FVG** (e.g., short after a buy-stop run reverses). | [Fair Value Gaps](../../concepts/fair-value-gaps.md) |
| 7 | Expect price to gravitate toward the **opposite liquidity** cluster. | [Liquidity](../../concepts/liquidity.md) |

---

## The AFTERNOON Entry Model (1:00 PM – Close)

| Step | Action | Concept |
|------|--------|---------|
| 1 | After lunch, watch the **first swing high/low form around 1:30 PM** on the 15-min. | [Algorithmic Programs](../../concepts/algorithmic-programs.md) |
| 2 | Wait for a **violation** of that afternoon swing low/high (the stop hunt). | [Stop Hunts](../../concepts/stop-hunts.md) |
| 3 | The violation triggers an algorithmic **buy/sell program** → watch for **spooling** (relentless one-way delivery). | [Algorithmic Programs](../../concepts/algorithmic-programs.md) |
| 4 | Enter via **displacement + FVG** on the retrace. | [Displacement](../../concepts/displacement.md) / [Fair Value Gaps](../../concepts/fair-value-gaps.md) |
| 5 | Hold into the **MOC ramp** — expect small retracements, then acceleration into the close. | [Algorithmic Programs](../../concepts/algorithmic-programs.md) |

### Two Afternoon Setups
1. **Stop hunt** below the swing low → triggers a **buy program**
2. **Sudden displacement** higher/lower with an **FVG** → enter on the retracement

---

## Daily Range Framing

The day = **morning move** + **afternoon move**. Use this for bias and targets:

- Both same direction → **measured move** (afternoon ≥ morning leg size)
- Morning trend, afternoon **reversal**
- Morning **consolidation**, afternoon **breakout**

Read **higher lows = accumulation**, **lower highs = distribution**. Remember **sentiment lags** — accumulation can drive price up even when the crowd is bearish. See [Daily Range](../../concepts/daily-range.md).

---

## Practical Workflow (8 Steps)

```
1. Select front-month contract by open interest (roll near expiration)
2. Set charts to New York time; use 15-min for swings, 5-min for entries
3. Pre-8:30 — mark swing highs/lows (liquidity pools)
4. Morning (8:30–Noon) — three drives / displacement / FVG → enter on retrace
5. Lunch (12–1) — NO TRADES
6. Afternoon (1 PM+) — mark ~1:30 swing; watch for violation → program/spooling
7. Use the two setups — stop-hunt-of-swing OR displacement-FVG
8. Track daily trend context — align morning + afternoon for bias & targets
```

---

## Quick-Reference Checklist

```
□ Trading the front-month contract (largest open interest)
□ Charts on New York time; 15-min swings + 5-min entries
□ Pre-8:30 swing high/low marked (liquidity pools)
□ Morning: three-drives / displacement into a swing → FVG entry on retrace
□ NO trades during lunch (12–1 PM)
□ Afternoon: ~1:30 swing marked; violation → buy/sell program → spooling
□ Entry via displacement + FVG retrace
□ Held into MOC ramp; target framed by measured move / opposite liquidity
```

---

## Episode-Specific Content

| File | Content |
|------|---------|
| [Morning & Afternoon Worked Examples](worked-examples.md) | Step-by-step walkthroughs of both session setups |

---

## The Core Insight

> The trading day is two moves around an untradeable lunch. Liquidity sits at swing highs/lows; smart money grabs it with **displacement**, leaving an **FVG** to enter on. In the afternoon, a **1:30 swing violation** ignites a **program** that **spools** into the **market-on-close** ramp. Probabilistic setups grounded in liquidity — not prediction.

---

*Source: 2022 ICT Mentorship Episode 5 — Intraday Order Flow & Daily Range*

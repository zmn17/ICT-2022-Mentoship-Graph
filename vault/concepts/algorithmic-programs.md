# Algorithmic Programs (Buy/Sell Programs, Spooling & MOC)

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.

---

## Overview

Intraday price — especially in the afternoon — is driven by **algorithmic programs**: coordinated buy or sell delivery triggered when liquidity is taken. Understanding buy/sell programs, spooling, and market-on-close activity explains *why* price accelerates late in the day.

---

## Buy Programs & Sell Programs

A **program** is an algorithmic sequence that delivers price in one direction, typically triggered after a [stop hunt](stop-hunts.md):

| Trigger | Program | Result |
|---------|---------|--------|
| Price violates a swing **low** (sell stops taken) | **Buy program** | Market bids price higher |
| Price violates a swing **high** (buy stops taken) | **Sell program** | Market offers price lower |

The violation of the swing point is the ignition; the program is the sustained move that follows.

---

## Spooling

**Spooling** is the algorithm delivering price **continuously and aggressively** in one direction — bidding higher and higher (or selling lower and lower) without meaningful pullback.

```
   Swing low violated (sell stops taken)
            │
        BUY PROGRAM triggers
            │
        SPOOLING ▲▲▲  ← relentless higher bids
            │
        acceleration into the close
```

- Spooling = the visible footprint of an active program
- Retracements during spooling are **small**; then price accelerates again
- Once you recognize spooling, you trade *with* it, not against it

---

## The 1:30 PM Macro

- **1:30 PM ET** is a known **algorithmic macro event** that often triggers significant afternoon movement
- Begin watching for the **first afternoon swing high/low** to form around 1:30 PM on the 15-min chart
- A violation of that afternoon swing typically kicks off a buy/sell program → spooling

See [Trading Sessions](trading-sessions.md) for the full session timing.

---

## Market-on-Close (MOC) Orders

- Late-day price action is heavily influenced by **market-on-close orders**
- These, combined with aggressive program activity, **ramp price into the close**
- Expect **smaller retracements** followed by **acceleration** toward the closing bell
- The afternoon move (see [Daily Range](daily-range.md)) is often an MOC-driven expansion

### The MOC Reversal Profile (Ep 32)

On a **[consolidation day](consolidation-day.md)**, the MOC can produce a **reversal** rather than a ramp:
- **3:00–4:00 PM ET** sets the tone for on-close orders
- Price runs **buy-side liquidity** above relative equal highs (induces breakout longs), then **reverses** on the MOC back toward the **daily midpoint**
- Textbook 1-min confirmation: run → swing high + [FVG](fair-value-gaps.md) → retrace → drive to midpoint

---

## How to Trade Around Programs

1. After lunch, mark the **first afternoon swing** (~1:30 PM)
2. Wait for a **violation** of that swing (the [stop hunt](stop-hunts.md))
3. That violation triggers a buy/sell **program** → watch for **spooling**
4. Enter via the [displacement](displacement.md) + [FVG](fair-value-gaps.md) on the retrace
5. Hold for the **acceleration into the close** (MOC ramp); expect only small pullbacks

---

## Related Concepts

- [Stop Hunts](stop-hunts.md) — The swing violation that ignites a program
- [Displacement](displacement.md) — How programs deliver price; leaves the FVG
- [Fair Value Gaps](fair-value-gaps.md) — Entry zone during a program
- [Daily Range](daily-range.md) — The afternoon move is program-driven
- [Trading Sessions](trading-sessions.md) — 1:30 macro & the close
- [State of Delivery](state-of-delivery.md) — Programs are the delivery mechanism

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 5 — Intraday Order Flow & Daily Range](../episodes/ep05-intraday-order-flow-daily-range/README.md) | Afternoon swing violation → buy/sell program → spooling → MOC ramp into the close |

---

*Introduced in: 2022 ICT Mentorship Episode 5 — Intraday Order Flow & Daily Range*

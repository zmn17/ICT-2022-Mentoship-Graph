# Worked Examples — Morning & Afternoon Setups

> ← Back to [Episode 5 Hub](README.md) | [Master Hub](../../ICT-trading.md)
>
> **Source:** 2022 ICT Mentorship Episode 5 — *Intraday Order Flow & Daily Range*
> **Instruments:** Index futures (E-mini S&P, Nasdaq, Dow, Russell)

---

## Example A — Morning Session Short (Three Drives → Displacement → FVG)

### Setup

```
                        drive 3  ← energetic push into/above old high
              drive 2   ╱╲          BUY STOPS run (displacement)
       drive 1 ╱╲     ╱╲ │ ╲
        ╱╲    ╱  ╲   ╱  ╲│  ╲★ ← sharp reversal down (not mild)
   ────╱  ╲──╱    ╲─╱        ╲
                    ┌────────┐╲
                    │  FVG   │ ╲  ← short entry on retrace into gap
                    └────────┘  ╲
                                 ▼ toward sell-side liquidity
```

### Walkthrough

1. **Pre-8:30:** marked the significant prior swing high — buy stops rest above it. See [Liquidity](../../concepts/liquidity.md).
2. **Three drives:** price makes three successively higher highs pressing into that old high, stacking retail buy stops. See [Three Drives](../../concepts/three-drives.md).
3. **Stop hunt + displacement:** price breaks above the high and runs the buy stops — but with **energetic displacement**, then sharply reverses (not a mild retracement). See [Stop Hunts](../../concepts/stop-hunts.md) / [Displacement](../../concepts/displacement.md).
4. **FVG:** the reversal leaves a fair value gap. See [Fair Value Gaps](../../concepts/fair-value-gaps.md).
5. **Entry:** short on the retracement **into the FVG**.
6. **Target:** the opposite (sell-side) liquidity below the morning swing low.

---

## Example B — Afternoon Buy Program (1:30 Swing Violation → Spooling → MOC)

### Setup

```
   1:30 PM — first afternoon swing forms
        ┌───────────────
        │   afternoon swing low
        └──────┐
               ▼  ← violation: sell stops taken (stop hunt)
            ┌──────┐
            │ FVG  │  ← buy entry on retrace (displacement up)
            └──────┘
               ▲▲▲  ← BUY PROGRAM spools price higher
               ▲▲▲
               ▲▲▲  ← MOC ramp into the close
```

### Walkthrough

1. **~1:30 PM:** the first afternoon swing high/low forms on the 15-min — the **1:30 macro** window. See [Algorithmic Programs](../../concepts/algorithmic-programs.md).
2. **Violation:** price violates the afternoon swing **low**, taking sell stops (the stop hunt). See [Stop Hunts](../../concepts/stop-hunts.md).
3. **Buy program:** the violation triggers an algorithmic **buy program** — price begins **spooling** higher aggressively. See [Algorithmic Programs](../../concepts/algorithmic-programs.md).
4. **Entry:** enter long via the **displacement + FVG** on the small retrace. See [Displacement](../../concepts/displacement.md) / [Fair Value Gaps](../../concepts/fair-value-gaps.md).
5. **Hold into the close:** expect only small retracements, then acceleration on **market-on-close** orders.

---

## Two Afternoon Setups (Summary)

| Setup | Trigger | Entry |
|-------|---------|-------|
| **Stop hunt of swing** | Violation of the ~1:30 swing low/high | Program + spooling; enter on FVG retrace |
| **Displacement-FVG** | Sudden energetic move leaving an FVG | Enter on retracement into the FVG |

---

## Daily Range Read (Tying It Together)

- If the **morning** was bullish and the **afternoon** buy program continues up → **measured move** (afternoon leg ≥ morning leg). See [Daily Range](../../concepts/daily-range.md).
- If the morning was bullish and the afternoon violates and reverses → **reversal** day.
- Read swing structure: **higher lows = accumulation** (bias up), even if sentiment is bearish.

---

## Repeatable Sequence (Both Sessions)

```
Swing liquidity (or Three Drives) → STOP HUNT → DISPLACEMENT → FVG → Entry
→ (afternoon) buy/sell PROGRAM → SPOOLING → MOC ramp into the close
```

---

## Related Concepts

- [Index Futures Contracts](../../concepts/index-futures-contracts.md)
- [Trading Sessions](../../concepts/trading-sessions.md)
- [Liquidity](../../concepts/liquidity.md)
- [Three Drives](../../concepts/three-drives.md)
- [Stop Hunts](../../concepts/stop-hunts.md)
- [Displacement](../../concepts/displacement.md)
- [Fair Value Gaps](../../concepts/fair-value-gaps.md)
- [Algorithmic Programs](../../concepts/algorithmic-programs.md)
- [Daily Range](../../concepts/daily-range.md)

---

*Source: 2022 ICT Mentorship Episode 5 — Intraday Order Flow & Daily Range*

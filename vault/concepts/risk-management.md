# Risk Management — Entry, Stops & Reward

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.
>
> **Source:** 2022 ICT Mentorship Episode 9 — *Power of 3 & New York PM Session Opportunities*

---

## Core Philosophy

From Episode 9, risk management is built around **structural levels** — using [order blocks](order-blocks.md) and [fair value gaps](fair-value-gaps.md) as the framework for entries, stops, and targets. The goal is not perfect entries but **controlled risk with favorable reward**.

---

## Entry Strategy

### Where to Enter
- Enter **near or just inside** [order blocks](order-blocks.md) and [fair value gaps](fair-value-gaps.md)
- Specifically where [liquidity](liquidity.md) resting below short-term lows has already been hunted
- Best entries occur after the manipulation phase of [Power of 3](power-of-3.md) is complete

### Entry Timing
- Best entries during the [NY PM session](../episodes/ep09-power-of-3-ny-pm/new-york-pm-session.md) (1:00–3:00 PM ET)
- After lunch-hour liquidity has been swept
- When price returns to a 5-minute order block within a daily zone of interest

### Expectation Management
> "Do not aim for perfect entry at exact lows; account for 'heat' (adverse price moves against position) of several points."

You will rarely catch the exact bottom. Plan for price to move against you by a few points before the trade works.

---

## Stop Loss Placement

### Where to Place Stops
- **Just below short-term lows** that define the [order block](order-blocks.md)
- These are the lows that represent the lower boundary of the OB zone
- Stops below this level invalidate the trade thesis

### Why This Works
- If price breaks through the order block completely, your thesis is wrong
- The stop is placed at a **structural level**, not an arbitrary distance
- This keeps risk defined and logical

### From the Episode 9 Example:
- Stop placed below the low of the bullish order block on the 5-minute chart
- Risk: approximately **14.25 points (handles)** on NQ futures

---

## Risk-Reward Framework

### Episode 9 Trade Example

| Parameter | Value |
|-----------|-------|
| Instrument | NASDAQ E-mini (NQ) micro contracts |
| Position Size | 6 micro contracts |
| Risk (stop distance) | ~14.25 points |
| Dollar Risk | ~$85 |
| Target (reward) | ~$300 |
| **Risk:Reward Ratio** | **~1:3.5** |

### Minimum R:R Guideline
- Aim for at least **3:1 reward-to-risk** or better
- If the structure doesn't offer at least 3R, the setup isn't worth taking
- Higher R:R compensates for imperfect entries and heat

---

## Position Sizing

From the example:
- Using **micro contracts** allows precise risk control
- 6 micro contracts with 14.25 points risk = ~$85 total risk
- This keeps risk small while allowing meaningful upside
- Scale position size to keep dollar risk consistent per trade

---

## Managing "Heat"

"Heat" is the adverse price movement against your position before the trade works:

- Expect **several points** of heat even on good setups
- Do NOT move stops to break-even too early — this gets you stopped out on heat
- Trust the structural stop (below the order block)
- If heat exceeds the OB boundary, the trade is invalidated — accept the loss

---

## When NOT to Trade

Episode 9 provides clear "no-trade" conditions:

1. **After strong overnight runs** — Wait for consolidation, don't chase
2. **Choppy/sideways markets** — Scale back frequency, preserve capital
3. **No clear liquidity sweep** — If manipulation hasn't occurred, don't anticipate distribution
4. **After 3:00 PM ET** — Late PM entries are lower probability

> "When price action is sideways and erratic, it's better to scale back trade frequency to avoid losses in low-probability conditions."

---

## Risk Management Checklist

Before entering any trade, confirm:

- [ ] [Power of 3](power-of-3.md) manipulation phase is complete (liquidity has been swept)
- [ ] Entry is at a defined [order block](order-blocks.md) or [fair value gap](fair-value-gaps.md)
- [ ] Stop is placed below a structural level (OB low)
- [ ] Reward-to-risk is at least 3:1
- [ ] Session timing supports the trade ([NY PM](../episodes/ep09-power-of-3-ny-pm/new-york-pm-session.md) preferred)
- [ ] No "avoid" conditions are present (overnight run, choppy market)

---

## Key Principles

1. **Trade patiently and selectively** — Not every session offers a setup
2. **Leverage algorithm-driven liquidity hunts** — Enter after the hunt, not during
3. **Keep risk small and defined** — Micro contracts, structural stops
4. **Favorable odds over frequency** — One good 3.5R trade beats five 1R trades
5. **Accept heat** — Don't aim for perfection; aim for controlled risk with good reward

---

## Related Concepts

- [Order Blocks](order-blocks.md) — Defines entry zone and stop level
- [Fair Value Gaps](fair-value-gaps.md) — Additional entry confirmation
- [Liquidity](liquidity.md) — Must be swept before entry
- [New York PM Session](../episodes/ep09-power-of-3-ny-pm/new-york-pm-session.md) — Optimal timing for entries
- [Session Analysis (Feb 2022)](../episodes/ep09-power-of-3-ny-pm/session-analysis-feb-2022.md) — Real trade example with these risk parameters

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 2 — Elements To A Trade Setup](../episodes/ep02-elements-to-a-trade-setup/README.md) | Stop above imbalance high / breaking-candle high per risk tolerance |
| [Ep 3 — Internal Range Liquidity & MSS](../episodes/ep03-internal-range-liquidity-mss/README.md) | Partial exits at 50% equilibrium; targets at opposite liquidity |
| [Ep 6 — Market Efficiency Paradigm & FVG](../episodes/ep06-market-efficiency-paradigm-fvg/README.md) | Stop above C1/C2 high; trail only on broken swing lows; IRL→ERL exits |
| [Ep 7 — Daily Bias & Consolidation](../episodes/ep07-daily-bias-consolidation/README.md) | Leverage scaled to bias certainty (full / reduced / surgical) |
| [Ep 8 — Forex Order Flow (EUR/JPY)](../episodes/ep08-forex-order-flow-eurjpy/README.md) | Fib std-dev projections for target/exit placement |
| [Ep 9 — Power of 3 & NY PM Session](../episodes/ep09-power-of-3-ny-pm/README.md) | Structural stops below OB; ~3.5:1 R:R with micro contracts |
| [Ep 10 — Economic Calendar & Power Three](../episodes/ep10-economic-calendar-power-three/README.md) | Breaker-based stops; stops wide enough for news volatility pumps |

---

*Referenced in: Episodes 2, 3, 6, 7, 8, 9, and 10*

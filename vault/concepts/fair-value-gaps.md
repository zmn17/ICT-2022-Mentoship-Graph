# Fair Value Gaps (FVGs) / Imbalances

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.
>
> **Source:** 2022 ICT Mentorship Episode 9 — *Power of 3 & New York PM Session Opportunities*

---

## What is a Fair Value Gap?

A Fair Value Gap (FVG), also called an **imbalance**, is a three-candle pattern where the middle candle's body is so large that it leaves a gap between the wicks of the candles on either side. This gap represents a price zone where one-sided aggression occurred — price moved so quickly that no two-sided trading took place.

---

## Identifying a Bullish FVG

```
Candle 1:  High ─────┐
                      │  ← GAP (Fair Value Gap)
Candle 3:  Low  ─────┘

         [Candle 2 = large bullish displacement candle]
```

**Rules:**
1. Candle 2 must be a large bullish candle
2. The **low of Candle 3** must be **above** the **high of Candle 1**
3. The gap between Candle 1's high and Candle 3's low = the FVG zone

---

## Identifying a Bearish FVG

```
Candle 3:  High ─────┐
                      │  ← GAP (Fair Value Gap)
Candle 1:  Low  ─────┘

         [Candle 2 = large bearish displacement candle]
```

**Rules:**
1. Candle 2 must be a large bearish candle
2. The **high of Candle 3** must be **below** the **low of Candle 1**
3. The gap between Candle 1's low and Candle 3's high = the FVG zone

---

## Ep 6 — Precise ICT FVG Rules, Entry & Stop

Episode 6 gives the most exact, candle-by-candle definition. Use this when marking FVGs by hand.

### Bearish ICT FVG (forms during a run *above* an old high / buy-stop pool)

| Candle | Key Feature |
|--------|-------------|
| **1** | Its **high** defines the upper boundary; its **low** is the reference |
| **2** | Extends lower — its **low trades below Candle 1's low** (gap starts) |
| **3** | Continues lower — **low below Candle 2's low**, but its **high does NOT retest Candle 1's low** |

- **The gap** = the price range between **Candle 1's low** and **Candle 3's high** that stays unfilled
- This is an **inefficiently offered price zone** on the sell side — price tends to trade back into it

**Entry / Stop / Target:**
```
   ── Candle 1 low ─────────┐
              │   FVG ZONE   │  ← limit SELL just above Candle 3 high (+1 tick)
   ── Candle 3 high ────────┘
   Stop: above Candle 1 or Candle 2 high (or the swing high)
   Target: 50% / internal range low → then external range liquidity
```

- **Entry:** limit order just **above Candle 3's high** (e.g., +1 tick)
- **Stop:** **above Candle 1 or Candle 2's high**, or the swing high
- **Confirmation required:** an **energetic bearish [displacement](displacement.md) candle** that closes convincingly below the low it breaks — **no displacement / no FVG = no trade**
- **Targets:** ~50% retrace / [internal range liquidity](internal-range-liquidity.md) for partials → [external range liquidity](external-range-liquidity.md) for the final exit

### Bullish ICT FVG (mirror image)

The bearish pattern **reversed**: price runs *below* old lows (sell-stop pool), then an energetic bullish displacement leaves a gap on the pullback.

- **Entry:** limit **below the gap's lower boundary** (mirror of Candle 3's low)
- **Stop:** below the swing low
- Same displacement confirmation and IRL→ERL exit logic apply

> **Key rule:** without a Fair Value Gap inside a valid [displacement](displacement.md) range, **there is no trade** — the FVG is the required confirmation.

---

## Why FVGs Matter

From Episode 9:
- FVGs represent **institutional order flow** — areas where algorithms aggressively moved price
- Price tends to **return to fill** these gaps (rebalance the imbalance)
- Once filled, FVGs act as **support** (bullish) or **resistance** (bearish)
- They confirm [order blocks](order-blocks.md) — an OB with an FVG nearby is stronger

---

## FVGs in Episode 9's Analysis

### Daily Chart FVGs
- The market repeatedly tested the imbalance zone (FVG) on the daily chart
- These zones confirmed key support/resistance levels
- Price returning to a daily FVG signals a potential reversal or continuation entry

### 5-Minute Chart FVGs
- Intraday FVGs on the 5-minute chart provided precise entry zones
- Used in conjunction with [order blocks](order-blocks.md) for refined entries
- The 9:30 AM New York open area was analyzed for where FVGs might influence price

---

## How Price Interacts with FVGs

1. **Price creates an FVG** during aggressive displacement
2. **Price pulls back** toward the FVG (filling or partially filling)
3. **Price reacts** at the FVG boundary — either bouncing (trade entry) or breaking through (invalidation)

### Key Observation from Episode 9:
> "Price typically does not squeeze beyond both the low of the day and the imbalances simultaneously, reflecting measured liquidity hunts."

This means price will test one level at a time — providing a framework for stop placement.

---

## Trading Fair Value Gaps

### Entry Strategy
- Wait for price to retrace **into** the FVG zone
- Look for [order block](order-blocks.md) confluence within the FVG
- Enter when price shows reaction inside the gap
- See [Risk Management](risk-management.md) for detailed entry approach

### Invalidation
- If price **closes through** the entire FVG on the same or higher time frame, it's invalidated
- Look for the next FVG or OB level

### Multi-Timeframe Approach
- **Daily FVG** provides the zone of interest
- **5-minute FVG** within the daily zone provides the sniper entry
- This nesting approach was demonstrated in the Feb 14–15 analysis

---

## FVG + Order Block Confluence

The strongest setups from Episode 9 occur when:
1. A [bullish order block](order-blocks.md) sits at the bottom of a bullish FVG
2. Price has just swept [sell-side liquidity](liquidity.md) below the zone
3. The setup is in a [discount zone](market-structure.md) (below 50% Fib)

This triple confluence provides the highest-probability entry.

---

## Related Concepts

- [Order Blocks](order-blocks.md) — OBs often sit within or adjacent to FVGs
- [Liquidity](liquidity.md) — Liquidity hunts often precede FVG fills
- [Power of 3](power-of-3.md) — FVGs are created during the distribution phase
- [Market Structure](market-structure.md) — FVGs in discount zones are bullish; in premium zones are bearish
- [Risk Management](risk-management.md) — Using FVG boundaries for stop placement
- [Market Structure Shift](market-structure-shift.md) — FVGs confirm intraday shifts (Ep 3)
- [Market Structure Break](market-structure-break.md) — The break leaves an FVG to enter on (Ep 2)

---

## Ep 33 — Trade the Imbalance, NOT Break-and-Retest

A crucial distinction: **this is not support/resistance or break-and-retest trading.**

> "If the fair value gap doesn't exist, I **don't trust that level** as an old-support-broken-turned-resistance."

- A **broken old low/high only earns trust** when a **fair value gap** is present there to justify the reaction
- **Pre-classify** levels ahead of time (e.g., 3915.25), but **key off the imbalance, not the level** — the level just *highlights where liquidity rests*
- Price may **overshoot** a round level *into the FVG* before delivering — the **imbalance**, not the level, dictates where delivery pauses/resumes
- After price returns into an FVG it should **move quickly away** and gravitate toward the **opposite pool** of liquidity

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 2 — Elements To A Trade Setup](../episodes/ep02-elements-to-a-trade-setup/README.md) | The imbalance left by a structure break; enter on the retest |
| [Ep 3 — Internal Range Liquidity & MSS](../episodes/ep03-internal-range-liquidity-mss/README.md) | Lower-timeframe FVG as the limit-order entry after a shift |
| [Ep 5 — Intraday Order Flow & Daily Range](../episodes/ep05-intraday-order-flow-daily-range/README.md) | FVG left by displacement = entry on the retrace (morning & afternoon) |
| [Ep 6 — Market Efficiency Paradigm & FVG](../episodes/ep06-market-efficiency-paradigm-fvg/README.md) | The definitive 3-candle rules; limit at Candle 3 high; no FVG = no trade |
| [Ep 7 — Daily Bias & Consolidation](../episodes/ep07-daily-bias-consolidation/README.md) | Intraday FVG + MSS entry after a correlation-confirmed fake break |
| [Ep 8 — Forex Order Flow (EUR/JPY)](../episodes/ep08-forex-order-flow-eurjpy/README.md) | FVGs between daily legs; refined entry on 15m→1m during London/NY |
| [Ep 9 — Power of 3 & NY PM Session](../episodes/ep09-power-of-3-ny-pm/README.md) | Daily & 5-min FVG confluence with order blocks |
| [Ep 10 — Economic Calendar & Power Three](../episodes/ep10-economic-calendar-power-three/README.md) | Drill 5→4→3→2→1-min to the first FVG; no gap = no trade |
| [Ep 33 — More Insights On FVG & Intraday Market Structure](../episodes/ep33-fvg-intraday-structure/README.md) | Trade the imbalance, not break-and-retest; a level only counts with an FVG |

---

*Referenced in: Episodes 2, 3, 5, 6, 7, 8, 9, 10, 33 — and throughout the series*

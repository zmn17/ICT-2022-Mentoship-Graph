# Order Blocks

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.
>
> **Source:** 2022 ICT Mentorship Episode 9 — *Power of 3 & New York PM Session Opportunities*

---

## What is an Order Block?

An order block is a cluster of candles (typically consecutive down-close candles for a bullish OB, or up-close candles for a bearish OB) that represents an area where institutional/algorithmic orders were placed. These zones act as significant support or resistance when price returns to them.

---

## Bullish Order Block

A **bullish order block** is formed by:
- One or more consecutive **down-close candles** (bearish candles) before a significant up-move
- The last down-close candle before displacement is the most significant
- The **low of that candle** defines the order block boundary

**Why it works:** Smart money accumulates buy orders in these down-candles. When price returns, those orders are still resting, causing price to bounce.

---

## Bearish Order Block

A **bearish order block** is formed by:
- One or more consecutive **up-close candles** (bullish candles) before a significant down-move
- The last up-close candle before displacement is the most significant
- The **high of that candle** defines the order block boundary

---

## How to Identify Order Blocks (From Episode 9)

1. Look for a cluster of **consecutive down-close candles** (for bullish OB)
2. Price must **displace aggressively** away from that zone
3. The displacement should create a [fair value gap](fair-value-gaps.md) — confirming institutional activity
4. When price returns to this zone, it acts as support

### Example from Feb 14, 2022:
- Early NY session: Price dipped into a bullish order block (cluster of down-close candles on the 5-min chart)
- Price rallied strongly after touching this zone
- The low of the order block candles defined the precise support level

---

## Order Block Boundaries

The **lows of certain candles within imbalances** define precise order block boundaries:

```
│ Candle 1 (bearish) │  ←── Upper boundary
│ Candle 2 (bearish) │
│ Candle 3 (bearish) │  ←── Lower boundary (entry zone)
└─────────────────────┘
        ↑
   Order Block Zone
        ↓
╔═════════════════════╗
║  DISPLACEMENT UP    ║  ←── Confirms the OB
╚═════════════════════╝
```

---

## Trading Order Blocks

### Entry
- Enter **near or just inside** the order block zone
- Best entries are at the low of the last down-close candle (for bullish OB)
- See [Risk Management](risk-management.md) for precise entry strategy

### Stop Loss
- Place stops **just below** the order block's lower boundary
- This is below the short-term lows that define the OB
- See [Risk Management](risk-management.md) for stop placement details

### Confluence
Order blocks are strongest when they align with:
- [Fair value gaps](fair-value-gaps.md) on the same or higher time frame
- [Discount zones](market-structure.md) (below 50% Fibonacci)
- [Liquidity](liquidity.md) sweeps that have already occurred

---

## Multi-Timeframe Order Blocks

From Episode 9, order blocks are analyzed on both:
- **Daily chart:** Identifies the broader zone of interest
- **5-minute chart:** Refines exact entry within the daily OB zone

The 5-minute order block nested inside a daily order block provides the highest probability setup.

---

## Key Rules from Episode 9

1. Price **respects** order blocks created by consecutive down-close candles, bouncing strongly after re-entering
2. Order blocks within [fair value gaps](fair-value-gaps.md) are particularly powerful
3. The lows of candles within imbalances define **precise** OB boundaries — useful for entries and stops
4. Not every OB will hold — always use proper [risk management](risk-management.md)

---

## Ep 3 Nuance — Order Blocks as a Change in State of Delivery

Episode 3 defines order blocks through the lens of the [state of delivery](state-of-delivery.md):

- A **bearish order block** = a series of **down-close candles** beginning at a candle **opening price** that gets violated → the algorithm's offering flips to **sell-side** delivery
- A **bullish order block** = a sequence of **up-close candles** offering buy-side liquidity, beginning at a specific candle's open

The **opening price** of the origin candle is the key line:

> If price trades **below** that open, the state shifts from buy-offering to sell-offering (and vice versa).

This makes the order block the visible **footprint of a [market structure shift](market-structure-shift.md)**. For entries, Episode 3 favors **limit orders inside the [fair value gap](fair-value-gaps.md)**, a few ticks beyond the order-block opening price.

---

## Ep 13 — Mean Threshold & High-Probability OB

**Mean threshold** = the **50% level of the order block**. It's the key risk reference:
- On entry, keep the stop **below** the mean threshold (for a bullish OB) — a stop placed too tight *inside* the retracement zone gets picked off
- Price trading below the mean threshold = a **discount** entry within the OB

A **high-probability bullish order block** (Ep 13) needs **all three**: a **down-close candle** + an **imbalance** left when price moves away + a **narrative** pointing higher (the [draw](draw-on-liquidity.md) is buy-side). Mirror for bearish. Best entries occur where the **OB overlaps a [fair value gap](fair-value-gaps.md)**.

---

## Ep 12 Refinement — OB = a Consecutive Series of Up/Down Closes

Episode 12 sharpens the definition and corrects a common teaching:

> "Everyone else teaches the **last up-close candle** before the down move — **that is not my order block**. The order block is **one consecutive series of up-close candles**, not the last candle before the down move."

- **Bearish OB** = the *whole run* of consecutive **up-close** candles before the drop (draw the rectangle around all of them)
- **Bullish OB** = the *whole run* of consecutive **down-close** candles before the rally
- Within that range you hunt [fair value gaps](fair-value-gaps.md) for entries — you do **not** need price to trade below the last/highest up-close candle first
- When bearish, the **bottom of the bearish OB** is the fill target for a limit order
- These up/down closes should also behave as [institutional order flow](institutional-order-flow.md) (cap/support price)

---

## Related Concepts

- [Power of 3](power-of-3.md) — Order blocks form during the accumulation phase
- [Fair Value Gaps](fair-value-gaps.md) — Often overlap with order blocks
- [Liquidity](liquidity.md) — OBs attract price back after liquidity hunts
- [State of Delivery](state-of-delivery.md) — An OB marks where delivery flipped
- [Institutional Order Flow](institutional-order-flow.md) — The OB's candles should cap/support price
- [Market Structure Shift](market-structure-shift.md) — OBs confirm intraday shifts
- [Risk Management](risk-management.md) — How to trade OBs with controlled risk

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 3 — Internal Range Liquidity & MSS](../episodes/ep03-internal-range-liquidity-mss/README.md) | OB = footprint of a state-of-delivery flip; enter via limit in the FVG at the OB open |
| [Ep 7 — Daily Bias & Consolidation](../episodes/ep07-daily-bias-consolidation/README.md) | Order block as an intraday entry handhold after the fake-break reversal |
| [Ep 9 — Power of 3 & NY PM Session](../episodes/ep09-power-of-3-ny-pm/README.md) | Bullish OB entry after the PM liquidity sweep |
| [Ep 11 — Reinforcing Past Lessons](../episodes/ep11-reinforcing-lessons-executions/README.md) | "Every down-close = bullish OB" misconception corrected by context |
| [Ep 12 — Advanced Price Action Theory](../episodes/ep12-advanced-price-action-theory/README.md) | OB = consecutive series of up-close candles (not the last one); bottom = limit fill |
| [Ep 13 — Advanced Price Action In Action](../episodes/ep13-advanced-price-action-in-action/README.md) | High-probability bullish OB (down-close + imbalance + narrative); mean threshold for stops |

> **OB has three sensitive reference points (Ep 35):** the **low**, the **open**, and the **middle** (the **mean threshold** = 50%). Price works through them as graded levels; reaching the **mean threshold** bodes well for continuation.

---

*Referenced in: Episodes 3, 7, 9, 11, 12, 13, 35 (and beyond)*

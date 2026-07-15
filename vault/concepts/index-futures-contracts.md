# Index Futures Contracts (Cycles, Open Interest & Rollover)

> ← Back to [ICT Trading Hub](../ICT-trading.md)
>
> **A shared concept** — see [Appears In Episodes](#appears-in-episodes) below.

---

## Overview

Before trading index futures (E-mini S&P 500, Nasdaq, Dow, Russell 2000), you must trade the **right contract**. Index futures expire on quarterly cycles, and liquidity concentrates in one contract at a time. Trading the wrong (thin) contract means poor fills and unreliable price action.

---

## Quarterly Expiration Cycle

Index futures use four quarterly delivery months, each with a letter code:

| Month | Code |
|-------|------|
| March | **H** |
| June | **M** |
| September | **U** |
| December | **Z** |

**Symbol example:** `ESH2022` = E-mini S&P 500, **March (H) 2022**.

---

## Expiration & the "Third Friday" Rule

- Expiration occurs on the **third Friday** of the delivery month
- **Trading after expiration is discouraged** — roll before it
- The expiring contract's liquidity dries up as traders migrate to the next quarter

---

## Front Month vs. Back Month

| Term | Meaning |
|------|---------|
| **Front month** | The nearby, **actively traded** contract — where liquidity lives |
| **Back / next month** | The following quarterly contract — becomes active after rollover |

**Rule:** always trade the **front month with the largest [open interest](#open-interest--rollover)** for the best liquidity.

---

## Open Interest & Rollover

**Open interest** = the number of outstanding contracts. It tells you where the liquidity (and thus clean price action) is.

Rollover workflow:

```
~1 week before expiration
        │
   Monitor open interest on front vs. next month
        │
   When the next month's open interest becomes DOMINANT
        │
   ROLL OVER → trade the next quarterly contract
```

- Start watching roughly **one week prior** to expiration
- Roll once the next month overtakes the front month in open interest
- This keeps you in the most liquid contract at all times

---

## Why This Matters for the Strategy

- All the [liquidity](liquidity.md), [displacement](displacement.md), and [FVG](fair-value-gaps.md) reads assume a **liquid** contract
- Thin/expiring contracts produce erratic, untradeable price action
- Getting the contract right is **step 1** of the [Episode 5 workflow](../episodes/ep05-intraday-order-flow-daily-range/README.md)

---

## Related Concepts

- [Liquidity](liquidity.md) — Open interest is where liquidity concentrates
- [Trading Sessions](trading-sessions.md) — Combine the right contract with the right session
- [Daily Range](daily-range.md) — Range analysis needs a liquid front month

---

## Appears In Episodes

| Episode | How It's Used |
|---------|---------------|
| [Ep 5 — Intraday Order Flow & Daily Range](../episodes/ep05-intraday-order-flow-daily-range/README.md) | Step 1: select front month by open interest; roll near expiration |

---

*Introduced in: 2022 ICT Mentorship Episode 5 — Intraday Order Flow & Daily Range*

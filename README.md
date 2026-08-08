SG TimeBreak — Time-Based Breakout System

READ THIS FIRST — RISK MANAGEMENT IS NON-NEGOTIABLE

This EA will NOT save you from yourself. If you do not follow strict risk management, you WILL lose money. Period.

The strategy is sound. The backtests are verified. But NONE of that matters if you ignore position sizing. If you are not willing to treat risk management as seriously as the entry logic, do not buy this product.

---

THE MONEY MANAGEMENT RULES — FOLLOW THEM OR DO NOT BUY

Rule 1: Fixed Risk Per Trade (Base Level)
    - Maximum 1% of account equity per trade (recommended baseline)
    - Never exceed 2% under any circumstances

Rule 2: Dynamic Risk Reduction on Drawdown (Manual Discipline)
    The EA does NOT automatically reduce risk during drawdown. This is YOUR responsibility.

    This is how I personally manage this system. I review results every week and manually adjust the risk setting:

    Drawdown from ATH      Risk per trade
    -----------------      ---------------
    0% to -15%             0.9%
    -15% to -25%           0.7%
    -25% to -35%           0.5%
    Beyond -35%            STOP TRADING THIS SETUP

    IMPORTANT: The EA does not do this for you. You must check your account weekly and adjust the risk percentage manually. If you are not willing to spend 5 minutes per week reviewing your equity curve, this product is not for you.

Rule 3: Hard Stop Loss — Always
    - Every trade has a stop loss. No exceptions.
    - Do not widen or remove the stop loss after entry.

Rule 4: Single Position Only
    - Maximum 1 trade per instrument per day
    - Do not add manual trades to "recover" a loss

Rule 5: Accept Consecutive Losses
    - 5, 10, or even 15 consecutive losses are statistically normal
    - Your risk per trade must be small enough that 15 losses in a row does not damage your account beyond recovery

Rule 6: Capital Allocation
    - This EA should NOT be your entire trading capital
    - Allocate only a portion of your risk capital to any single system

Rule 7: Time Horizon
    - Evaluate performance over 12+ months, not weeks
    - If you cannot leave the account untouched for 1 year, do not start

---

CRITICAL: TIME ZONE SETUP — READ BEFORE USING

This system is 100% dependent on correct market timing. If your broker's server time differs from what the setfile expects, the EA will trade the wrong hours and produce completely different (and wrong) results.

How to check your broker's time:
    1. Open MetaTrader 5
    2. Look at the Market Watch window (top left)
    3. Check the time displayed next to any symbol
    4. Compare this time to UTC

The setfiles are configured for the following market times:

DAX (Primary Setfile)
    - Range: 2 hours before German cash market open (07:00-09:00 Germany)
    - Close Option 1: 12:00 Germany (midday)
    - Close Option 2: 16:00 Germany (end of EU session)

S&P 500 — 1 Hour Opening Range
    - Range: 09:30-10:30 New York Time
    - Close: 15:45 New York Time

S&P 500 — 15 Minute Opening Range
    - Range: 09:30-09:45 New York Time
    - Close: 15:45 New York Time

XAUUSD Gold
    - Range: Pre-market before US session
    - Contact me for specific time zone alignment

---

BROKER TIME ZONE EXAMPLES

Most MT5 brokers use GMT+2 (winter) / GMT+3 (summer).

Example 1: Broker on GMT+2 (Winter)
    DAX Range:        07:00 to 09:00
    DAX Close Opt 1:  12:00
    DAX Close Opt 2:  16:00
    S&P 1h Range:     15:30 to 16:30
    S&P 15m Range:    15:30 to 15:45
    S&P Close:        20:45

Example 2: Broker on GMT+3 (Summer DST)
    DAX Range:        08:00 to 10:00
    DAX Close Opt 1:  13:00
    DAX Close Opt 2:  17:00
    S&P 1h Range:     16:30 to 17:30
    S&P 15m Range:    16:30 to 16:45
    S&P Close:        21:45

Example 3: Broker on GMT+0
    DAX Range:        05:00 to 07:00
    DAX Close Opt 1:  10:00
    DAX Close Opt 2:  14:00
    S&P 1h Range:     13:30 to 14:30
    S&P 15m Range:    13:30 to 13:45
    S&P Close:        18:45

UTC Reference (Summer): DAX 05:00-07:00 UTC, S&P 13:30-14:30 UTC, Close 19:45 UTC
UTC Reference (Winter): DAX 06:00-08:00 UTC, S&P 14:30-15:30 UTC, Close 20:45 UTC

How to calculate: Find the difference between your broker time and UTC, then add that difference to the UTC reference times above.

If you are unsure about your broker's time zone, contact me via MQL5 internal chat before running the EA.

---

RECOMMENDED BROKERS

I personally trade this system through Admiral Markets on MetaTrader 5.

The following brokers provide suitable conditions for this strategy (low spreads, reliable execution, correct server times):
    - Admiral Markets
    - IC Markets
    - Vantage Markets International
    - Pepperstone

Important: I am not affiliated with any broker. The strategy requires ECN/RAW spread account, low spreads during session opens, reliable execution, and correct server time alignment.

Before purchasing, verify that your broker's server time matches one of the examples above, or contact me to confirm compatibility.

---

BACKTEST PERFORMANCE — DAX

Backtested with 99.9% tick modeling quality over a multi-year period using real tick data.

Key metrics at 1% fixed risk per trade:
    - Average annual return: ~22%
    - Maximum drawdown: ~24-25%
    - Worst full calendar year: approximately -2%
    - Approximate doubling time: ~3 years
    - Win rate: varies by year, typically 35-45%

There was an entire year that was essentially flat. Not negative, not positive — just flat. That year tested patience. It will test yours too. This is not a bug. This is trading.

---

LIVE TRADING CONTEXT

I have been trading this system in live market conditions for a significant period. The strategy was originally developed on futures markets via Interactive Brokers.

On MetaTrader 5 (CFD broker), my live track record currently spans approximately 140-150 trades. While this confirms the system functions in live MT5 conditions, I do not consider 150 trades sufficient to present as statistically significant proof on this specific platform.

Treat the multi-year backtests as your primary reference. The limited live MT5 data serves as supplementary confirmation only.

---

THE REALITY OF DRAWDOWN

This system trades roughly 1 time per day. Markets trend 20-30% of the time. The rest is consolidation, chop, and false breakouts.

You WILL experience:
    - Months with no new equity highs
    - Streaks of 5-10 consecutive losses
    - Periods of 3-6+ months in drawdown

This is expected. This is normal. This is the price of admission.

My manual risk reduction system is specifically designed for these periods. When drawdown hits -15%, I reduce risk. At -25%, I reduce further. At -35%, I stop completely and reassess. This is not weakness — this is survival.

If you cannot emotionally handle watching your account sit in drawdown for half a year while doing nothing, this product is not for you.

---

ABOUT THIS SYSTEM

I built this EA for myself. I use it in live market conditions every day. I risk my own capital with the exact same settings I am sharing with you.

DAX (Primary / Backtested + Limited Live MT5 Data)
    - Range: 2 hours before German cash market open
    - 1 trade per day maximum
    - Hard stop loss and take profit on every position
    - No averaging, no martingale, no grid

S&P 500 (Backtested / Configurable)
    - Range Option 1: First hour after New York open
    - Range Option 2: 15-minute opening range after New York open

XAUUSD Gold (Backtested Only — Use With Caution)
    - Range: Pre-market period before US session
    - Not verified in live market conditions

---

WHO IS THIS FOR?

    + Traders who treat risk management as sacred
    + Those who understand that capital preservation comes first
    + People with the discipline to follow rules without deviation
    + Traders who check their account weekly and adjust risk manually
    + Traders with a 12+ month time horizon
    + Users with minimum $1,000-$2,000 account and strict risk discipline

---

WHO SHOULD NOT BUY THIS?

    - Traders who change risk settings based on emotion
    - Those who remove stop losses to "give it more room"
    - People who need monthly profits to feel secure
    - Anyone who adds manual trades to recover losses
    - Traders who cannot handle 6 months of drawdown
    - Anyone treating this as a "set and forget money machine"
    - Traders who refuse to review and adjust risk weekly
    - Traders looking for fully automated risk management

---

REQUIREMENTS

    - MetaTrader 5
    - ECN broker with low spreads (critical for breakout entries)
    - VPS for uninterrupted 24/5 operation
    - Minimum recommended deposit: $1,000
    - Weekly account review (5 minutes) to adjust risk if needed
    - Time zone verification before first use
    - Discipline: mandatory and non-negotiable

---

PRICING

    Purchase:     $50
    1-Year Rent:  $20

Priced to be accessible. Not priced to get rich off sales.

---

ABOUT THE AUTHOR

I am a systematic trader running multiple strategies across different platforms and asset classes. This time-based breakout system is one component of a broader trading framework I am building.

I personally trade this EA through Admiral Markets on MetaTrader 5.

I code what I trade, and I trade what I code.

Questions? Use the MQL5 internal chat — I respond to every message.

---

RISK DISCLAIMER

Trading carries substantial risk of loss. Past performance does not guarantee future results. This EA uses stop losses, but no system can eliminate risk. Only trade with capital you can afford to lose entirely.

Backtested results are hypothetical and may differ from live trading due to spreads, slippage, execution delays, and other market factors.

The author is not responsible for losses resulting from improper risk settings, manual intervention, incorrect time zone configuration, or deviation from the recommended money management rules.

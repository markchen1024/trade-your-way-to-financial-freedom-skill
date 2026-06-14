# Chapter 12: Position Sizing — "I Only Have $10,000 in My Account!"

## Core Idea
Position sizing — *how much* you trade — is the part of the system that determines whether you meet your objectives, and it is the second-most-important pillar after psychology. It answers "how many units?" throughout a trade. Most blow-ups are position-sizing failures, not entry failures.

## Frameworks Introduced
Tharp presents **four position-sizing models**, in increasing sophistication:

- **Model 1 — One unit per fixed amount of money**: Trade 1 unit (100 shares / 1 contract) for every $X in the account (e.g., 1 contract per $50,000). Simple; easy to scale up/down. **Weakness**: ignores each trade's actual risk — treats a tight-stop and wide-stop trade identically; also can't add a unit until equity doubles.
- **Model 2 — Equal value units (equal leverage)**: Allocate equal *dollar value* to each position (e.g., split equity into N equal parts). Common for stock traders. **Weakness**: equalizes exposure but still **ignores risk** (R) per position.
- **Model 3 — Percent Risk Model (the CPR model)**: Risk a fixed % of equity per trade. **Units = (equity × %risk) ÷ risk-per-unit (R).** This is the **first model that equates risk** across trades and the professional default.
- **Model 4 — Percent Volatility Model**: Size so each position's *volatility* (≈ average true range) equals a fixed % of equity. **Units = (equity × %volatility) ÷ (ATR × point value).** Equalizes each position's daily noise/exposure.

## Key Concepts
- **Position sizing**: The algorithm answering "how much?" — the lever that meets objectives.
- **CPR (percent risk)**: Cash × Percent-risk ÷ Risk-per-unit → number of units.
- **Risk per unit (R)**: From the stop (Ch 9) — denominator of Models 3 and 4 (volatility for 4).
- **Equating risk**: Making each trade's potential loss the same fraction of equity, so no single trade dominates.

## Mental Models
- Separate the two questions: **"Should I trade?"** (entry/setup) vs. **"How much?"** (position sizing). The second decides your equity curve.
- Tie size to **risk or volatility**, not to gut feeling or "what you can afford" — the latter is how accounts blow up.

## Worked Examples
**Model 3 — Percent Risk:** $50,000 account, risk 2.5% = $1,250 per trade. Buy gold at $380 with a stop at $370 → risk = 10 pts × $100 = **$1,000/contract (1R)**. $1,250 ÷ $1,000 = 1.25 → **buy 1 contract.** Same day, short corn at $4.03 with a stop at $4.08 → 5¢ × 5,000 bu = **$250/contract**. $1,250 ÷ $250 = **5 contracts.** Same 2.5% risk, very different position sizes — the model *equates risk*.

**Model 4 — Percent Volatility:** $50,000 account, allow 2% volatility = $1,000. Gold's daily range (ATR) is $3 → $300/contract. $1,000 ÷ $300 = 3.3 → **buy 3 contracts.** Each position now contributes the same daily fluctuation to the account.

**Why it matters:** the *same* 55/21 breakout system run on the same data produces wildly different returns depending only on which sizing model is bolted on — position sizing, not the system, drives the results.

## Anti-patterns
- **Sizing by "what I can afford" / one unit because it's all I can buy**: ignores risk; the small-account trap.
- **Equal-dollar or fixed-unit sizing on varied-risk trades**: Models 1–2 let a wide-stop trade quietly carry far more risk than a tight-stop one.
- **No sizing model at all**: Random position sizes guarantee an uncontrolled equity curve.

## Key Takeaways
1. Position sizing = "how much?" — the pillar that meets (or misses) your objectives.
2. Four models; **percent risk (CPR)** is the professional baseline because it *equates risk*.
3. CPR: **units = equity × %risk ÷ R** (risk per unit from your stop).
4. Percent volatility sizes by ATR instead of stop distance.
5. The same system + different sizing = completely different results.

## Connects To
- **Ch 9**: The stop sets R, the denominator of the percent-risk model.
- **Ch 6**: Keys 5–6 (capital, sizing) convert expectancy into account growth.
- **Ch 3**: Objectives and drawdown tolerance set your %risk per trade.
- **Ch 8**: The 1% sizing that made the random-entry system win 100% of runs.

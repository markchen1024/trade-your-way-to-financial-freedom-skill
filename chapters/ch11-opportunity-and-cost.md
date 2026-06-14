# Chapter 11: The Opportunity and Cost Factors

## Core Idea
Positive expectancy alone doesn't grow an account — you must factor in **opportunity** (how often the system trades) and **cost** (commissions + slippage per trade). The two interact: more frequent trading multiplies expectancy *and* multiplies cost.

## Frameworks Introduced
- **The opportunity factor**: Account growth ≈ **expectancy × number of opportunities** over a period. A small per-trade edge traded often can beat a large edge traded rarely.
  - When to use: When comparing systems or deciding how frequently to trade.
  - How: Estimate expectancy (in R) × trades per period to compare systems on equal footing.
- **The cost-of-trading factor**: Every trade pays commissions + slippage. Higher frequency raises gross opportunity but also raises total cost — the two must be weighed together.
- **Opportunity/cost trade-off**: Increasing trade frequency only helps if the per-trade expectancy stays positive *after* costs.

## Key Concepts
- **Opportunity**: The number of trade signals a system generates per period (frequency).
- **Cost**: Commissions + slippage; a constant destructive force on each trade.
- **Expectancy × opportunity**: The product that actually determines account growth (from Ch 6).
- **Net expectancy**: Expectancy after subtracting trading costs.

## Mental Models
- Judge a system by **expectancy × opportunity − cost**, not by expectancy or win rate alone.
- Treat cost as a fixed "tax" per trade: the higher your frequency, the more that tax matters — especially on small accounts.

## Anti-patterns
- **Chasing frequency for its own sake**: More trades that erode to break-even after cost add risk without reward.
- **Ignoring slippage in backtests**: Makes high-frequency systems look far better than they trade live.
- **Comparing systems by expectancy alone**: A higher-expectancy system that rarely trades may grow your account slower than a modest-expectancy system that trades often.

## Worked Example
Two systems, both starting at the same equity:
- **System A**: expectancy +1.0R, but only **10 trades/year** → ~10R/year gross.
- **System B**: expectancy +0.2R, but **100 trades/day** → enormous gross opportunity.
At 100 trades each risking $100, a +0.2R edge yields $2,000 — earned **per day** for System B but **per year** for a comparable low-frequency system. Now subtract cost: if each trade costs $20, System B pays $2,000/day in costs, wiping out the gross — so its frequency only helps if the post-cost edge stays positive. Opportunity and cost must be evaluated *together*.

## Key Takeaways
1. Account growth ≈ expectancy × opportunity − cost.
2. A small edge traded often can beat a big edge traded rarely.
3. Frequency cuts both ways: it scales the edge *and* the cost.
4. Always use net (after-cost) expectancy; include slippage in tests.
5. Don't add trades unless they remain positive expectancy after costs.

## Connects To
- **Ch 6**: Keys 3 (cost) and 4 (opportunity) of the six keys.
- **Ch 12**: Opportunity and cost interact with position sizing to set growth.
- **Ch 2**: Ignoring slippage/cost is a form of postdictive/reliability bias in testing.

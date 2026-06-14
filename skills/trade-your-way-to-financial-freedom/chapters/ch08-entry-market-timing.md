# Chapter 8: Entry or Market Timing

## Core Idea
Entry is the part traders obsess over and the part that matters *least*. Tharp's signature demonstration: even a **random (coin-flip) entry** makes money — as long as you have good exits and sound position sizing.

## Frameworks Introduced
- **The random-entry result**: A system can be profitable with literally random entries if its exits and position sizing are sound. Entry's job is modest — slightly beat random reliability, nothing more.
- **Designing your own entry signal**: Build entries that *measurably* beat random, then stop — don't over-engineer.
- **Survey of common entry techniques**: channel/Donchian breakouts, moving-average crossovers, volatility breakouts, directional movement (ADX), oscillators/bands, and visual pattern triggers — each evaluated on whether it beats random.
- **Entry becomes less significant as time frame lengthens**: For long-term trend systems, entry timing barely matters; for very short-term systems it matters more.

## Key Concepts
- **Random entry**: Coin-flip entry direction, always in the market, used as the baseline any real entry must beat.
- **Reliability improvement**: The *only* legitimate goal of an entry technique — raise the win rate above random.
- **Time-frame dependence**: The shorter your holding period, the more entry quality matters.

## Mental Models
- Use random entry as your **benchmark**: if your fancy entry can't beat a coin flip net of cost, it adds nothing.
- Spend your design energy "downstream" (exits, sizing); treat entry as a small reliability tweak, not the source of the edge.

## Anti-patterns
- **Entry obsession (Lotto bias)**: Pouring effort into the entry signal because it feels controllable, while neglecting exits and sizing.
- **Over-optimizing entries**: Tuning entry parameters to history — curve-fitting for a pillar that barely matters.

## Worked Example — The Coin-Flip System
Tharp (with Tom Basso) built a system with: **random (coin-flip) entry**, a **3× volatility trailing stop**, and a **1% risk** position-sizing algorithm, always in each market long or short. Run on **10 markets**, it **made money on ~80% of runs with one contract per market, and 100% of runs once position sizing was applied.** The entry contributed *nothing* — the profits came entirely from the trailing-stop exit (which cuts losers and rides winners, producing positive expectancy) and the position-sizing model. This is the empirical proof of the book's thesis: exits and sizing, not entry, make the money.

## Key Takeaways
1. Random entry + good exits + good sizing = profitable. Entry is the least important pillar.
2. The only valid goal of an entry technique is to beat random reliability — then stop.
3. Entry matters less the longer your time frame.
4. Always benchmark a new entry against a coin flip net of costs.
5. Entry obsession is the Lotto bias wasting your best effort.

## Connects To
- **Ch 7**: Setups precede the entry trigger.
- **Ch 9 & 10**: The exits that actually generate the edge.
- **Ch 6**: Entry's only lever is reliability — one of six keys, and not the biggest.
- **Ch 12**: The 1% position sizing that made the coin-flip system win 100% of runs.

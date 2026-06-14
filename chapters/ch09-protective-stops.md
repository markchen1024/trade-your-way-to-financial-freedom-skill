# Chapter 9: Knowing When to Fold 'Em — How to Protect Your Capital

## Core Idea
The protective stop is what defines your risk (R) and preserves capital. Half of the "golden rule of trading" — *cut your losses short* — lives here. A stop tells you the point at which your trade idea is wrong, decided **before** you enter.

## Frameworks Introduced
- **The protective stop**: A predefined exit that caps your worst-case loss on a position. It *defines R* — the denominator of every R-multiple and the basis of position sizing.
  - When to use: On every position, set at entry, no exceptions.
  - How: Place it where the trade premise is invalidated, not at an arbitrary dollar amount.
- **"A stop that makes sense"**: The stop should reflect the market's noise/volatility and your concept — wide enough that normal noise won't hit it, tight enough to keep R small.
- **Volatility-based stops**: e.g., a stop at **3× the average true range** — adapts to each market's noise instead of a fixed dollar figure.

## Key Concepts
- **Stop (protective/initial)**: The price at which you exit to preserve capital; sets initial risk R.
- **Risk (R)**: Entry price − stop price, × position size = your 1R loss.
- **Noise**: Normal random price movement a good stop must sit outside of.
- **Tight vs. wide stops**: Tight stops = smaller R, more units, but more whipsaws (lower reliability); wide stops = larger R, fewer units, fewer whipsaws.

## Mental Models
- Think of the stop as the price where you *admit the idea is wrong* — decide it before emotion (the need to be right) takes over.
- See the stop as the **unit of risk**: everything downstream (R-multiples, expectancy, position size) is denominated in it.

## Anti-patterns
- **Trading without a stop / protection bias**: Refusing to predefine the loss — the bias that quietly destroys accounts (Ch 2).
- **Moving the stop away** to avoid being stopped out: the need-to-be-right bias turning a small loss into a large one.
- **Arbitrary dollar stops**: A stop unrelated to volatility gets hit by noise or risks too much.

## Worked Example
You buy gold at **$380**. Your concept says the trade is wrong if gold falls to **$370**, so that's your stop. Risk per contract = 10 points × $100/point = **$1,000 = 1R**. This single decision does three jobs at once: (1) it caps your loss at a known amount, (2) it defines R for computing the trade's eventual R-multiple (Ch 6), and (3) it feeds position sizing — a 2.5% risk on a $50,000 account ($1,250) ÷ $1,000 R = 1 contract (Ch 12). Without the stop, none of those numbers exist.

## Key Takeaways
1. Every position gets a protective stop, set at entry.
2. The stop *defines R* — the foundation of R-multiples, expectancy, and sizing.
3. Place stops by market logic/volatility, not arbitrary dollars.
4. Never widen a stop to avoid a loss — that's the need to be right.
5. "Cut losses short" is half the golden rule; this chapter is how.

## Connects To
- **Ch 6**: The stop sets R, the basis of every R-multiple and expectancy.
- **Ch 10**: The other half of the golden rule — letting profits run.
- **Ch 12**: R (from the stop) is the key input to every position-sizing model.
- **Ch 2**: Stops exist to override the protection and need-to-be-right biases.

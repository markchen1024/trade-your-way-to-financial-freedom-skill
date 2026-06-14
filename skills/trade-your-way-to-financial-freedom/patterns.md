# Patterns & Techniques — Trade Your Way to Financial Freedom

## The 12-Step System Development Model
**When to use**: Designing, auditing, or rebuilding any trading system.
**How**: Work in order — (1) self-inventory, (2) gather market info, (3) objectives, (4) time frame, (5) study best historical moves, (6) define & measure the concept, (7) add stops + costs (defines R), (8) add profit exits + compute expectancy, (9) seek big-R trades, (10) optimize with position sizing, (11) improve, (12) worst-case mental rehearsal.
**Trade-offs**: Slower than diving into entry rules, but the only order that produces a system you can actually trade.

## R-Multiple Bookkeeping
**When to use**: Evaluating every trade and every system on a common scale.
**How**: At entry, R = (entry − stop) × size = your 1R loss. For each closed trade, record profit/loss ÷ R. A system is its *distribution* of R-multiples.
**Trade-offs**: Requires a predefined stop on every trade; decouples evaluation from dollar size and account size.

## Expectancy Calculation
**When to use**: To judge whether a system is worth trading, independent of win rate.
**How**: `Expectancy = (Win% × avg win in R) − (Loss% × avg loss in R)` = mean R per trade. Multiply by trades/period (opportunity) for growth.
**Trade-offs**: A 40%-win system can beat a 60%-win system if its winners are larger in R; needs a meaningful sample.

## Volatility-Based Protective Stop
**When to use**: To place a stop that survives normal noise yet defines a controlled R.
**How**: Set the stop at a multiple of ATR (e.g., 3× average true range) from entry, or where the trade premise is invalidated.
**Trade-offs**: Wider stop = smaller R per unit count, fewer whipsaws, but larger R in dollars; tighter = more units but more stop-outs.

## Trailing-Stop Profit Exit
**When to use**: Trend systems where you want to let winners run while protecting open profit.
**How**: Ratchet a stop (e.g., 3× volatility) only in the favorable direction; exit when it's hit.
**Trade-offs**: Gives back some open profit at the turn, but captures the large-R winners that drive expectancy. Engine behind the random-entry result.

## Multiple / Split Exits
**When to use**: When one position must serve two goals (bank some profit + ride the rest).
**How**: Take partial profit at a target; trail a stop on the remainder.
**Trade-offs**: More robust psychologically, but keep it simple — many exit rules = curve-fitting.

## Position Sizing — Model 1: One Unit per Fixed Amount
**When to use**: Simplest accounts; quick scaling.
**How**: 1 unit per $X of equity (e.g., 1 contract / $50,000).
**Trade-offs**: Ignores per-trade risk; can't add a unit until equity doubles.

## Position Sizing — Model 2: Equal Value Units
**When to use**: Stock portfolios wanting equal exposure per name.
**How**: Divide equity into N equal dollar allocations.
**Trade-offs**: Equalizes value, not risk; a wide-stop name still risks more than a tight-stop one.

## Position Sizing — Model 3: Percent Risk (CPR)
**When to use**: Professional default; whenever you want each trade to risk the same fraction of equity.
**How**: **Units = (equity × %risk) ÷ risk-per-unit (R).** Example: $50k × 2.5% = $1,250 ÷ $1,000 gold R = 1 contract; ÷ $250 corn R = 5 contracts.
**Trade-offs**: *Equates risk* across trades — the first model to do so; requires a defined stop.

## Position Sizing — Model 4: Percent Volatility
**When to use**: Equalizing each position's daily noise/exposure.
**How**: **Units = (equity × %volatility) ÷ (ATR × point value).** Example: $50k × 2% = $1,000 ÷ $300 gold ATR = 3 contracts.
**Trade-offs**: Adapts to volatility regardless of stop placement; needs a reliable ATR estimate.

## Random-Entry Stress Test
**When to use**: To prove your edge lives in exits/sizing, not entry.
**How**: Replace your entry with a coin flip; keep your exits + position sizing; if it's still profitable, your design is sound.
**Trade-offs**: Counterintuitive, but the fastest way to expose entry obsession (Lotto bias).

## Worst-Case Mental Rehearsal
**When to use**: Before trading live; step 12 of the model.
**How**: List every disaster (gap against you, limit-locked market, broker outage, max drawdown) and pre-decide your exact response.
**Trade-offs**: Takes uncomfortable imagination up front; prevents panic-driven decisions in a crisis.

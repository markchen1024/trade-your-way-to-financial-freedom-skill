# Trade Your Way to Financial Freedom — Claude Code Skill

A [Claude Code](https://claude.com/claude-code) skill that distills **Van K. Tharp's _Trade Your Way to Financial Freedom_** into a compact, queryable knowledge base — frameworks, formulas, and decision rules you can pull up while you work, instead of re-reading the book.

> ⚠️ **Educational use only. Not financial advice.** Trading involves substantial risk of loss. This skill summarizes the book's *ideas*; it does not recommend trades. It contains no verbatim copy of the book — only synthesized frameworks.

## What's inside

The skill loads ~5K tokens of core frameworks, plus chapter modules and reference files that load **on demand**:

- **`SKILL.md`** — core frameworks + chapter & topic index (the resident layer)
- **`chapters/ch01–ch13.md`** — one module per chapter (loaded only when you ask)
- **`glossary.md`** — every key term defined
- **`patterns.md`** — techniques: the 12-step model, four position-sizing models, expectancy calc, random-entry test
- **`cheatsheet.md`** — decision rules, formulas, and bias-recognition tables

Key frameworks covered: the **Six Keys to Investment Success**, **R-multiples** and **expectancy**, the **Golden Rule** (cut losses short / let profits run), the **random-entry** demonstration, the **four position-sizing models** (incl. percent-risk / CPR), the **12-step system-development model**, and Tharp's catalog of **judgmental biases**.

## Install

This repository **is** the skill (`SKILL.md` lives at the root). Clone it into your personal skills directory so the folder name becomes the skill name:

```bash
# macOS / Linux
git clone https://github.com/markchen1024/trade-your-way-to-financial-freedom-skill.git \
  ~/.claude/skills/trade-your-way-to-financial-freedom
```

```powershell
# Windows (PowerShell)
git clone https://github.com/markchen1024/trade-your-way-to-financial-freedom-skill.git `
  "$env:USERPROFILE\.claude\skills\trade-your-way-to-financial-freedom"
```

> The destination folder name (`trade-your-way-to-financial-freedom`) must match the `name:` in `SKILL.md`. Restart your Claude Code session afterward so the skill is discovered.

## Use it

```text
Ask trade-your-way-to-financial-freedom about expectancy
Ask trade-your-way-to-financial-freedom about position sizing
Ask trade-your-way-to-financial-freedom for ch06
```

Or just ask "what chapters do you have?" to browse the index.

## Repository layout

```
SKILL.md            # core frameworks + chapter & topic index (resident)
chapters/           # ch01–ch13, loaded on demand
glossary.md         # key terms
patterns.md         # techniques & models
cheatsheet.md       # decision rules & formulas
```

## Credit & copyright

All concepts, frameworks, and terminology originate from **_Trade Your Way to Financial Freedom_ by Van K. Tharp** (McGraw-Hill). This skill is an independent, transformative study aid that paraphrases and indexes those ideas; it reproduces no substantial passages of the original text. Please support the author by buying the book. Generated with the [book-to-skill](https://github.com/virgiliojr94/book-to-skill) converter.

## License

The skill *packaging and synthesized text* in this repository are released under the [MIT License](LICENSE). This license does **not** extend to the underlying ideas/trademarks of the original work, which remain the property of their author and publisher.

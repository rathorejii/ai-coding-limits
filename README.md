# AI Coding Plan Limits & Pricing — Claude Code, Codex, Cursor, Copilot, Antigravity

**Every major AI coding plan's price and usage limit, in one place — sourced from the vendors' own pages, dated, and updated on every change.**

AI coding tools change their plans constantly: tiers get renamed, limits move, new plans appear. This repository is the open-data companion to [LimitSheet](https://limitsheet.com/?utm_source=github&utm_medium=repo&utm_campaign=ai-coding-limits): the same verified, dated record, in a format you can read, cite and build on.

> **Last verified: 24 November 2026** · Prices in USD per month, billed monthly unless stated · Data licence: CC BY 4.0 (see [LICENSE](LICENSE))

## Prices at a glance

### Claude (Claude Code included)

| Plan | Price | Notes |
|---|---|---|
| Free | $0 | |
| Pro | $20 ($17/mo billed annually) | 5-hour session window + weekly limit |
| Max | $100 | 5× Pro usage per 5 hours and per week |
| Ultra | $200 | 10× Pro weekly usage; **no 5-hour limit for verified accounts**; $200 monthly API credit |
| Team — Standard seat | $25/seat ($20 billed annually) | Min. 2 seats |
| Team — Premium seat | $125/seat ($100 billed annually) | 5× a standard seat |

*On 30 Oct 2026, Max 20x ($200) became **Ultra** and Max 5x became the single **Max** plan — see [the change note](docs/changes/2026-10-30-claude-max-20x-becomes-ultra.md).*

### Codex (via ChatGPT plans)

| Plan | Price | Notes |
|---|---|---|
| ChatGPT Free | $0 | Light Codex use |
| ChatGPT Go | $8 | Lightweight coding tasks |
| ChatGPT Plus | $20 | A few focused coding sessions a week |
| ChatGPT Pro 100 | $100 | No 5-hour limit currently |
| ChatGPT Pro 200 | $200 | New subscriptions get a lower allowance than the original tier |
| ChatGPT Pro 500 | $500 | Only tier with Astra Ultrafast included |
| ChatGPT Business | $20/user ($25 billed monthly) | Min. 2 users, billed annually |

### Cursor — The X Subscription

| Plan | Price | Notes |
|---|---|---|
| Free (Hobby) | $0 | Limited |
| Plus | $8 | One weekly usage pool, shared with Grok |
| Premium | $30 | 4× Plus usage |
| Super | $100 | 15× Plus usage |
| Ultra | $200 | 50× Plus usage |

*Cursor replaced its old plans (Pro $20, Pro+ $60, Ultra $200) with The X Subscription — legacy holders keep their old plans unless they switch. See [the change note](docs/changes/2026-11-21-cursor-the-x-subscription.md).*

### GitHub Copilot

| Plan | Price | Notes |
|---|---|---|
| Copilot Free | $0 | |
| Copilot Pro | $10 | |
| Copilot Pro+ | $39 | |
| Copilot Max | $100 | |
| Copilot Business | $19/user | |
| Copilot Enterprise | $39/user | Requires GitHub Enterprise Cloud |

### Google Antigravity (Google AI plans)

| Plan | Price |
|---|---|
| AI Pro | $19.99 |
| AI Ultra 5x | $99.99 |
| AI Ultra 20x | $199.99 |

## Machine-readable data

The same record as JSON, for tools, dashboards and research: [`data/pricing.json`](data/pricing.json)

Every row carries the vendor source it came from and the date it was last verified. If a number here and a vendor page disagree, the vendor page wins — please [open an issue](../../issues) and it will be re-checked.

## Latest changes

| Date | Change |
|---|---|
| 21 Nov 2026 | [Cursor moves to The X Subscription (Plus $8, Premium $30, Super $100, Ultra $200)](docs/changes/2026-11-21-cursor-the-x-subscription.md) |
| 30 Oct 2026 | [Claude Max 20x becomes Ultra, and Max 5x becomes Max](docs/changes/2026-10-30-claude-max-20x-becomes-ultra.md) |
| 1 Oct 2026 | [Copilot Business and Enterprise seats are charged upfront for card/PayPal customers](docs/changes/2026-10-01-copilot-seats-charged-upfront.md) |
| 29 Sep 2026 | [ChatGPT Pro: a new $500 plan; Pro 200 reopens with a lower allowance](docs/changes/2026-09-29-chatgpt-pro-500-plan.md) |

Full guides, per-plan limit tables and a plan finder: **[limitsheet.com](https://limitsheet.com/?utm_source=github&utm_medium=repo&utm_campaign=ai-coding-limits)**

## FAQ

**How often is this updated?**
The underlying record is watched daily. When a vendor changes a price or a limit, a dated note lands in [`docs/changes/`](docs/changes/) and the tables above are corrected.

**Where do the numbers come from?**
Only the vendors' own pricing pages, docs and help centres, read on the date shown. No rumours, no scraped aggregator numbers.

**Can I reuse this data?**
Yes — CC BY 4.0. Please link back to [limitsheet.com](https://limitsheet.com/) or to this repository so readers can reach the source and the verification date.

**A price looks wrong. What now?**
Open an issue with the vendor page you are looking at. Corrections are verified against the official source before anything changes.

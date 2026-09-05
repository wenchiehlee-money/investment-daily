# investment-daily

Daily investment research archive for `wenchiehlee-money`.

## Purpose

Store one consistent Markdown investment summary per trading day, with emphasis on:

- Taiwan equities, individual stocks, and institutional research
- AI / semiconductors / technology supply chains
- TSMC and AI-server / CSP capex trends
- Global macro, U.S. equities, rates, and major market-moving events
- Foreign investors / investment trusts / dealer views and target-price changes
- Earnings, earnings calls, financing, and other material company events

Summaries should be written primarily in Traditional Chinese and use `Asia/Taipei` as the working timezone.

## Repository layout

```text
config/
  focus.md                         # coverage priorities and analysis rules
templates/
  daily-summary-template.md        # standard daily-summary format
summaries/
  README.md                        # storage and naming convention
  YYYY/MM/YYYY-MM-DD.md            # generated daily summaries
```

## Daily summary principles

1. Separate facts from interpretation.
2. Link important claims to sources whenever possible.
3. Prioritize new information and explain why it matters for investors.
4. Include both upside catalysts and downside risks.
5. Distinguish short-term price impact from long-term investment thesis.
6. Avoid repeating unchanged background unless it is needed for context.

## File naming

Example:

```text
summaries/2026/09/2026-09-05.md
```

Each daily file should be self-contained so it can be read independently later.

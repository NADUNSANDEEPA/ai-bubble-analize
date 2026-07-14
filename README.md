# Dot-com vs AI Company Financial Comparison
 
A company-level financial dataset comparing the dot-com boom (1995–2002) against the current AI boom (November 2022–present), built to test whether AI-era valuations are outrunning the revenue and profit growth behind them — the way dot-com valuations eventually did.
 
## Contents
 
`dotcom_vs_ai_company_financial_comparison.xlsx` contains four sheets:
 
- **Summary** — period definitions, top-10 company lists, aggregate tables, and comparison charts
- **DotCom_Data** — company-by-company observations, 1995–2002
- **AI_Data** — company-by-company observations, 2022–2025
- **Methodology** — definitions, limitations, and source references
## Time periods
 
| Cycle | Range | Notes |
|---|---|---|
| Dot-com | 1995–2002 | A complete cycle: boom and bust |
| AI boom | Nov 30, 2022 – present | Start date is ChatGPT's public release, the point mass-market generative-AI adoption took off. The cycle hasn't ended, so no burst date can be identified yet. |
 
Only completed annual observations are included: 2022–2025 for the AI period. 2026 is excluded because the year isn't finished.
 
## Data fields
 
Each row in `DotCom_Data` and `AI_Data` is one company-year, with:
 
- `year`
- company and ticker
- listing status
- year-end market value or private valuation
- year-over-year market-value growth
- revenue
- revenue growth
- profit or earnings proxy
- profit growth
- profit-measure basis
- data-completeness status
- source URL(s)
**Market capitalization** is used as the proxy for market value (share price × shares outstanding). It is *not* the amount of cash actually invested in the company.
 
**Private companies** — OpenAI and Anthropic — are listed separately and valued using reported funding-round or secondary-market prices rather than market cap. Reuters reported a $500B OpenAI valuation and a $183B Anthropic valuation during 2025.
 
## Charts
 
Two normalized-index charts in the `Summary` sheet plot market-value growth against revenue growth and profit growth, side by side, making it easy to see whether valuation is running ahead of fundamentals:
 
1. **Dot-com core basket** (1996 = 100) — Cisco, Microsoft, Intel, Oracle, Qualcomm
2. **AI public-company basket** (2022 = 100) — Nvidia, Microsoft, Alphabet, Amazon, Meta, Oracle, Broadcom, TSMC

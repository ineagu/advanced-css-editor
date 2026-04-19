# Audit: $SKM vs $ZM as Anthropic Proxy + Other Public Stocks

**Date:** April 2026
**Scope:** Verify all factual claims, correct the math, surface other Anthropic-exposed equities

---

## VERDICT

**The core thesis is directionally interesting but the load-bearing number is wrong.**

The author estimates SKM's current Anthropic stake at **1.07%**. Research from SK Telecom's
own filings shows the stake was **0.7% as of end-2024**, and after three more dilutive rounds
(Series E, F, G) the current figure is approximately **0.56–0.60%** — nearly half the
claimed figure. At corrected estimates, ZM provides **equal or more** Anthropic exposure
per dollar than SKM, which largely reverses the thesis.

---

## Part 1: Claim-by-Claim Verification

| # | Claim | Verdict | Detail |
|---|-------|---------|--------|
| 1 | ZM invested $51M at $4.5B post-money, May 2023 | ✅ CONFIRMED | Baird, CNBC, TechBuzz all confirm |
| 2 | SKM invested $100M at $5B post-money, Aug 2023 | ⚠️ PARTIALLY | $100M confirmed; $5B valuation consistent with Series C extension |
| 3 | "SKM invested 2x the amount **Anthropic** did" | ❌ TYPO | Should read "2x the amount **ZM** did" |
| 4 | Series G closed Feb 2026 at $380B, $30B raised | ✅ CONFIRMED | Anthropic official announcement, Crunchbase |
| 5 | Post-dilution: ZM = 0.6%, SKM = 1.07% | 🔴 SKM OVERSTATED | ZM's 0.6% plausible; SKM's 1.07% is ~2x too high (see §2) |
| 6 | $800B from VC offers | ✅ CONFIRMED | Bloomberg Apr 14, TechCrunch Apr 15, 2026 — but not a closed round |
| 7 | "WSJ reported secondary at $600B+" | ⚠️ ATTRIBUTION | Caplight secondary hit $688B; primary reporting was Bloomberg not WSJ |
| 8 | ZM stake at $800B ≈ $4.8B, ~90x return | ✅ MATH CORRECT | 0.6% × $800B = $4.8B; exact multiple = 94x (minor understate) |
| 9 | SKM stake at $800B ≈ $8.6B, ~85x return | 🔴 WRONG | At corrected 0.58%: $4.64B, ~46x return |
| 10 | ZM: 17.7% of MC / 24.7% of EV in Anthropic | ✅ MATH CORRECT | Arithmetic confirms at stated inputs |
| 11 | SKM: 59% of MC / 36.8% of EV in Anthropic | 🔴 WRONG | At 0.58%: ~31.8% of MC / ~23.6% of EV |
| 12 | Per ZM share at $88 → $15.6 in Anthropic | ✅ CORRECT | $4.8B ÷ ~308M shares = $15.6 |
| 13 | Per SKM share at $38 → $22.4 in Anthropic | 🔴 WRONG | At 0.58%: $4.64B ÷ ~384M shares = **$12.1/share** |
| 14 | SKM legacy biz at ~0.4x P/S | 🔴 WRONG | SKM revenue $12.1B TTM; at corrected stake, legacy P/S ≈ 1.2–1.4x |
| 15 | SKM up 80%+ YTD | ✅ CONFIRMED | Multiple sources confirm strong YTD run |

---

## Part 2: The SKM Stake — The Central Issue

### What the author claims
- Initial stake: $100M ÷ $5B post-money = **2.0%**
- Post-dilution estimate: **1.07%** (implying ~47% diluted away)

### What official sources show

**SK Telecom's own H1 2024 financial report** discloses:
- Stake: **0.7%** with book value of 192.5 billion won (~$140M)
- This is BEFORE Series E (Mar 2025), F (Sep 2025), and G (Feb 2026)

**Translation:** The initial 2.0% is mathematically correct. But by end-2024, after Amazon's
$4B investment (Series D, Sep 2023–Mar 2024), the stake had already diluted to 0.7%.
The author's 1.07% sits between the initial 2.0% and the end-2024 0.7% — they appear to
have run a partial dilution model that missed the Amazon round's impact.

### Dilution model from 0.7% baseline (end-2024):

| Round | Date | Raised | Post-Money | New Share % | Remaining SKM % |
|-------|------|--------|------------|-------------|-----------------|
| Baseline (post Amazon) | End-2024 | — | — | — | 0.700% |
| Series E | Mar 2025 | $3.5B | $61.5B | 5.69% | 0.660% |
| Series F | Sep 2025 | $13B | $183B | 7.10% | 0.613% |
| Series G | Feb 2026 | $30B | $380B | 7.89% | 0.565% |

**Best estimate for SKM's current Anthropic stake: ~0.56–0.60%**

This is consistent with analyst estimates ranging 0.3%–0.7% across different sources —
the 0.3% figure in some reports may apply more conservative dilution assumptions or
include additional undisclosed dilutive events.

---

## Part 3: Revised Math at Corrected Stakes

**Using ZM = 0.60%, SKM = 0.58%**

### Stake Values

| Anthropic Valuation | ZM Stake Value | SKM Stake Value |
|--------------------|----------------|-----------------|
| $380B (last closed round) | $2.28B | $2.20B |
| $600B (secondary markets) | $3.60B | $3.48B |
| $800B (VC offers, Bloomberg) | $4.80B | $4.64B |
| $1T (perp markets, unverified) | $6.00B | $5.80B |

### Per-Share Anthropic Exposure

**ZM at $88/share** (~308M shares):

| Anthropic Val | Anthropic/Share | % of Share Price |
|--------------|----------------|-----------------|
| $380B | $7.40 | 8.4% |
| $600B | $11.69 | 13.3% |
| $800B | $15.58 | 17.7% |
| $1T | $19.48 | 22.1% |

**SKM at $38/share** (~384M shares):

| Anthropic Val | Anthropic/Share | % of Share Price |
|--------------|----------------|-----------------|
| $380B | $5.73 | 15.1% |
| $600B | $9.06 | 23.8% |
| $800B | $12.08 | 31.8% |
| $1T | $15.10 | 39.7% |

### The Head-to-Head at $800B (Corrected)

| Metric | ZM | SKM (Author) | SKM (Corrected) |
|--------|-----|-------------|-----------------|
| Stake % | 0.60% | 1.07% | 0.58% |
| Stake value | $4.80B | $8.56B | $4.64B |
| Anthropic per share | **$15.58** | $22.40 | **$12.08** |
| Anthropic as % of MC | 17.7% | 58.6% | 31.8% |

**At corrected estimates, ZM delivers $15.58/share vs SKM's $12.08/share in Anthropic
exposure — ZM wins, not SKM.**

---

## Part 4: Other Issues in the Analysis

### ZM's Cash Pile Is Larger Than Implied
- ZM: MC $27.1B, EV $19.4B → implied net cash: $7.7B
- Seeking Alpha headline: "Zoom: **35% Net Cash** Plus $4 Billion Stake in Anthropic"
- 35% of $27.1B = ~$9.5B in net cash — slightly more than the EV gap implies
- At $88/share, ZM buyer gets ~$30 in cash + ~$15.6 in Anthropic
- The non-Anthropic, non-cash core business is being valued at ~$42/share ($12.9B)
- The author acknowledges the cash gap via EV but doesn't call it out explicitly

### SKM Legacy Business P/S Is Not 0.4x
- SKM TTM revenue: **$12.1B** (MacroTrends, confirmed)
- SKM EV: **$19.63B** (Yahoo Finance, Apr 14, 2026)
- At corrected Anthropic stake ($4.64B at $800B):
  - Legacy EV = $19.63B − $4.64B = **$14.99B**
  - Legacy P/S = $14.99B ÷ $12.1B = **~1.24x** — not 0.4x
- The 0.4x figure would require an Anthropic stake of ~$14.8B, implying 1.85% ownership
- The "ridiculously cheap legacy business" narrative doesn't hold at corrected stake values

### $800B Attribution
- The author credits "Business Insider" for the $800B figure
- Primary reporting was **Bloomberg** (Apr 14, 2026) followed by TechCrunch (Apr 15, 2026)
- BI may have run a follow-up piece but Bloomberg broke it

### Return Multiples Are Irrelevant to New Buyers
- The "85x return" and "90x return" describe what ZM/SKM themselves made
- A new investor buying today at $38 or $88 does NOT receive those returns
- The meaningful question: what are you paying for Anthropic exposure vs. getting?
- At $800B: ZM buyer pays $88, gets $15.58 in Anthropic (17.7% of purchase price in Anthropic)
- At $800B: SKM buyer pays $38, gets $12.08 in Anthropic (31.8% of purchase price in Anthropic)

### FX Risk on SKM (Not Mentioned)
- SKM earns and reports in **Korean Won (KRW)**
- ~$8.8B net debt is denominated in KRW
- KRW/USD swings directly affect ADR price
- ZM has zero FX exposure (USD only)

### SKM ADR Structure
- 1 SKM ADR = **1/9 of one Korean common share**
- Doesn't break the math but means corporate actions, dividends, and voting rights
  work differently than a standard US equity

### SKM Dividend (Meaningful, Not Mentioned)
- Korean telecoms typically pay 4–6%+ dividend yields
- SKM has historically paid meaningful dividends
- Dividend is a real cash return to shareholders absent from ZM entirely
- Partially offsets ZM's cash advantage

---

## Part 5: Other Public Stocks with Anthropic Exposure

### Tier 1 — Largest Absolute Stakes (Small Relative Impact)

**Amazon (AMZN)**
- Stake: **~7.8%** (derived from Q3 2025 10-K: $9.5B unrealized gain when Anthropic
  went from $61.5B → $183B implies 7.8% ownership)
- Value at $800B: ~$62.4B
- Market cap: ~$2.2T
- Anthropic as % of MC: **~2.8%**
- Impact: Almost invisible relative to Amazon's scale
- Note: Amazon's stake is capped below 33%; no board seats

**Alphabet / Google (GOOG)**
- Stake: **~14%** (confirmed via court documents; capped at 15% per side agreement)
- Value at $800B: ~$112B
- Market cap: ~$2.0T
- Anthropic as % of MC: **~5.6%**
- Note: Google holds no board seats, no voting rights
- Google's total investment: $3B+ across multiple rounds
- Revenue relationship: Anthropic committed to use Google Cloud for training

### Tier 2 — Pure-Play Vehicle (Extreme Premium Risk)

**VCX — Fundrise Innovation Fund (NYSE: VCX)**
- What it is: Publicly listed closed-end fund holding pre-IPO tech
- Anthropic position: **21% of fund assets** (largest single position)
- Other holdings: Databricks 18%, OpenAI 10%, Anduril 7%, SpaceX 5%
- AUM: ~$679M
- Market cap: ~$2.39B (as of Apr 19, 2026)
- NAV per share: ~$20
- Current price: ~$84.47
- **Premium to NAV: ~4.2x** (peaked at 13x in March 2026)
- Summary: Most direct public exposure to Anthropic, but you're paying $4 for every $1
  of underlying assets — Citron Research launched a short attack in March 2026
- **Verdict: Direct exposure vehicle, but premium makes it dangerous at current levels**

### Tier 3 — Small Strategic Stakes (Noise-Level Impact)

**Salesforce (CRM)**
- Invested in Series C ($450M round, May 2023) via Salesforce Ventures
- Amount: Undisclosed (Salesforce Ventures' $250M GenAI fund seeded around this time)
- Stake: Likely tiny relative to CRM's ~$250B market cap
- Commercial relationship: Anthropic Claude integrated into Salesforce products
- **Verdict: Too small to matter as Anthropic proxy; commercial deal is the real angle**

**Microsoft (MSFT)**
- NOT an Anthropic investor (they back OpenAI)
- Mentioned here only to clear up common confusion

### Tier 4 — Commercial Relationships (Not Equity)

**Broadcom (AVGO)**
- Signed expanded chip deals with Google and Anthropic (Apr 2026)
- This is a **revenue/customer relationship**, not an equity stake
- If Anthropic scales, Broadcom benefits as chip supplier
- **Verdict: AI infrastructure play, not an Anthropic equity proxy**

**Vertex AI / Google Cloud**
- Anthropic is committed to use Google Cloud for compute
- Benefits Alphabet at the infrastructure level independent of equity stake

### Summary Table — All Public Anthropic Exposure

| Ticker | Stake | Value @$800B | MC | As % of MC | Verdict |
|--------|-------|-------------|-----|------------|---------|
| GOOG | ~14% | $112B | $2.0T | 5.6% | Too large to move needle |
| AMZN | ~7.8% | $62.4B | $2.2T | 2.8% | Too large to move needle |
| SKM | ~0.58% | $4.64B | $14.6B | **31.8%** | Meaningful — corrected from 59% |
| ZM | ~0.60% | $4.80B | $27.1B | **17.7%** | Meaningful + large cash pile |
| VCX | ~21% of fund | ~$143M direct | $2.39B | varies | Direct but 4x NAV premium |
| CRM | Unknown tiny | — | $250B+ | < 0.1% | Negligible |

---

## Part 6: The Revised Head-to-Head

At corrected stake estimates (~0.58–0.60% for both), SKM and ZM are essentially **tied on
Anthropic exposure in absolute dollar terms.** The differentiators are:

**Reasons to prefer ZM over SKM:**
- More Anthropic per share in absolute dollars ($15.58 vs $12.08)
- ~$9.5B net cash with zero FX risk
- US-listed, liquid, simpler structure
- No FX/KRW currency exposure

**Reasons to still consider SKM over ZM:**
- Anthropic is a larger % of your purchase price (31.8% vs 17.7%)
- Meaningful dividend (4–6% yield)
- Legacy telecom business valued cheaply relative to peers (even if not 0.4x P/S)
- Possible undisclosed additional Anthropic exposure via SKVTC (SK's US venture arm)

**The honest summary:** The original thesis was built on a 2x overstatement of SKM's
Anthropic stake. With corrected figures, both stocks offer roughly equivalent Anthropic
exposure. ZM delivers more per share; SKM delivers more as a percentage of price paid.
The choice depends on whether you want a US tech compounder or a cheap Korean telecom
as your wrapper — not on Anthropic stake size.

---

## Sources

- [CNBC — Zoom Anthropic stake Jan 2026](https://www.cnbc.com/2026/01/26/zoom-anthropic-investment.html)
- [TechCrunch — SKM $100M investment](https://techcrunch.com/2023/08/14/ai-startup-anthropic-raises-100m-from-korean-telco-giant-sk-telecom/)
- [Anthropic Series G announcement](https://www.anthropic.com/news/anthropic-raises-30-billion-series-g-funding-380-billion-post-money-valuation)
- [Bloomberg — Anthropic $800B offers](https://www.bloomberg.com/news/articles/2026-04-14/anthropic-attracts-investor-offers-at-a-800-billion-valuation)
- [Seoul Economic Daily — SKM 52-week high, stake 3 trillion won](https://en.sedaily.com/finance/2026/01/20/sk-telecom-hits-52-week-high-on-anthropic-stake-valued-at-3)
- [Douglas Research — SKM Anthropic analysis](https://douglasresearch.substack.com/p/sk-telecoms-investment-in-anthropic)
- [Deedy / LinkedIn — Amazon 7.8%, Google 8.8% derived from SEC filings](https://www.linkedin.com/posts/debarghyadas_public-reports-inadvertently-show-that-anthropic-activity-7390409362718191616-bqHE)
- [Data Center Dynamics — Google 14% confirmed](https://www.datacenterdynamics.com/en/news/google-owns-14-percent-of-generative-ai-business-anthropic/)
- [Seeking Alpha — Zoom 35% net cash + Anthropic](https://seekingalpha.com/article/4878085-zoom-35-percent-net-cash-plus-4-billion-stake-in-anthropic)
- [Yahoo Finance — VCX Fundrise Innovation Fund](https://finance.yahoo.com/quote/VCX/)
- [Bloomberg — VCX drop after Citron short](https://www.bloomberg.com/news/articles/2026-03-27/fund-with-anthropic-stake-extends-drop-in-stunning-ipo-reversal)
- [MacroTrends — SKM revenue](https://www.macrotrends.net/stocks/charts/SKM/sk-telecom/revenue)
- [Bullseye Investing — SKM backdoor Anthropic play](https://bullseyeinvesting.substack.com/p/the-weird-way-to-invest-in-anthropic)
- [CNBC — Broadcom Anthropic chip deal](https://www.cnbc.com/2026/04/06/broadcom-agrees-to-expanded-chip-deals-with-google-anthropic.html)

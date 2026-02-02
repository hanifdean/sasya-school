# Strava Series A Term Sheet — Glossary of Terms

> A plain-English glossary of every key term from the Sigma Partners Series A term sheet for Strava, Inc. (October 4, 2010). Based on HBS Case 9-814-055.

---

## Offering Terms

### Series A Preferred Stock
The class of shares being sold in this financing round. "Series A" means it's the first institutional round. "Preferred" means these shares have special rights (dividends, liquidation preference, anti-dilution, etc.) that common stockholders don't get.

### Investors / Major Investors
**Investors** = everyone buying shares in this round (Founders + Sigma + Others). **Major Investors** = any investor holding preferred stock ≥ 0.25% of the company's fully-diluted capital. Major Investors get extra rights (information rights, pro rata participation in future rounds, etc.).

### Closing Date
The date the deal officially happens — money changes hands, shares are issued. "Additional closings" within 60 days means the company can let more investors in after the initial close.

### Amount Raised
Up to **$4,595,000** total. This includes $1,170,000 in existing loans from the founders that get *converted* into Series A shares (not new cash — the debt just becomes equity).

### Price Per Share / Pre-Money Valuation
The price each Series A share is sold at. The **pre-money valuation** is what the company is worth *before* the new investment. It's calculated so that after the investment, the new investors own 39.19% of the company on a fully-diluted basis. In this case:
- Post-money shares: 36,257,969
- Series A shares: 14,210,232 → 39.19%
- Implied pre-money valuation ≈ **$7.1M** (post-money ≈ $11.7M)

### Fully-Diluted Capitalization
The total number of shares if *everything* that could become a share actually did — all common stock, all preferred stock converted to common, all options exercised, all warrants. This is the denominator VCs use to calculate ownership percentages. It includes the **employee option pool** (7.5% of post-money in this deal).

### Employee Option Pool
Shares reserved for future employee stock options (7.5% of post-money here). This is included in the pre-money valuation, which effectively means *existing shareholders* (the founders) bear the dilution of the pool, not the new investors. This is a common VC negotiation tactic — a larger pool = lower effective pre-money valuation for founders.

---

## Charter (Rights of the Preferred Stock)

### Dividends
Series A holders earn 4% per year on their investment, but **only if the board declares them** — they're not automatic. "Non-cumulative" means unpaid dividends don't pile up as an obligation. If the company pays dividends to common stockholders, preferred holders participate too (on an as-converted basis).

### Liquidation Preference
**The most important economic term in any term sheet.** It determines who gets paid first and how much when the company is sold or wound down.

Here's the waterfall:
1. **First:** Series A holders get back their Original Purchase Price (1x their investment) + any declared but unpaid dividends
2. **Then:** Remaining proceeds are split between Common Stock and Series A (on as-converted basis) *until* Series A holders have received **2x their Original Purchase Price** total (including the 1x from step 1)
3. **After that:** Only Common Stock holders receive the remaining proceeds

This is a **capped participating preferred** structure — but the footnote clarifies it's actually **non-participating preferred** for normal liquidation. The 2x cap only applies in a **Deemed Liquidation Event** (see below). In practice, preferred holders choose whichever is better: take the liquidation preference OR convert to common and share pro rata.

### Deemed Liquidation Event
Events that *aren't* technically a company shutdown but are treated as one for purposes of the liquidation preference:
- **Merger or acquisition** (where existing stockholders don't keep majority control)
- **Sale of all/substantially all assets**
- **50%+ of voting power changes hands**

This protects investors — if the company gets acquired, they get their liquidation preference before founders see a dime.

### Non-Participating vs. Participating Preferred
- **Non-participating** (this deal): Investors choose EITHER their liquidation preference OR convert to common and share pro rata. They can't double-dip.
- **Participating** (more investor-friendly): Investors get their liquidation preference AND then share in remaining proceeds. Much worse for founders.

---

## Governance & Control

### Voting Rights
Series A holders vote alongside common stock (1 preferred share = 1 common share equivalent). They don't get a separate class vote except where legally required or specified in the charter.

### Board of Directors
5-member board:
- **2 seats** — Founders (Gainey + Horvath)
- **1 seat** — Sigma (Greg Gretsch)
- **2 seats** — Independent/Other Directors (Ariel Poler + Jameson McJunkin)

Removing an independent director requires approval from *both* the preferred majority and the founder common majority — neither side can unilaterally change the board composition.

### Protective Provisions
A list of major actions the company **cannot take** without majority preferred stockholder approval:
- Amend the charter in ways that hurt preferred holders
- Create new stock classes with equal or superior rights
- Reclassify junior stock to become senior
- Pay dividends or buy back stock ahead of preferred

This is essentially a **veto right** on fundamental changes — gives Sigma a blocking position on major corporate decisions even without a board majority.

### Drag-Along Agreement
If the board + majority of all stockholders (common + preferred voting together) approve a sale/liquidation, then *everyone* must vote in favor — no holdouts. **However**, if 66.67% of preferred holders object in writing, the drag-along doesn't apply. This protects against a scenario where majority common holders try to force a low-value sale that hurts preferred holders.

---

## Conversion Rights

### Optional Conversion
Any preferred holder can convert their Series A shares to common stock at any time, initially at a 1:1 ratio. You'd do this if the common stock becomes more valuable than the preferred rights (e.g., at IPO or a high-value acquisition where converting gets you more than the liquidation preference).

### Mandatory Conversion
Preferred stock **automatically** converts to common when:
1. A **Qualified Public Offering (QPO)** happens — IPO at ≥ 3x the Original Purchase Price with ≥ $20M in net proceeds, OR
2. A majority of preferred holders vote to convert

The 3x threshold ensures automatic conversion only happens at a valuation that's clearly a win for everyone.

### Anti-Dilution Provisions (Broad-Based Weighted Average)
If the company later sells shares at a *lower* price than what Series A investors paid (a "down round"), the conversion ratio adjusts so Series A holders get more common shares when they convert. **Broad-based weighted average** is the founder-friendlier version — it considers all outstanding shares in the calculation, resulting in a smaller adjustment. The alternative (**full ratchet**) would reprice Series A to the new lower price entirely, which is much harsher on founders.

**Exceptions** — anti-dilution doesn't trigger for routine issuances: employee options, converting existing securities, stock splits, bank financing, acquisitions, or IPO shares.

---

## Investor Rights

### Registration Rights
Rights that let investors eventually sell their shares on the public market:

| Type | What It Means |
|------|---------------|
| **Demand Registration** | After 5 years (or 6 months post-IPO), holders of 40% of registrable shares can force the company to register their shares for public sale. Limited to 2 uses. Min $5M offering. |
| **Form S-3 Registration** | A cheaper, simpler registration form. Holders of 10% of registrable shares can request this once per 6 months. Min $1M offering. |
| **Piggyback Registration** | If the company is already doing a registration (e.g., IPO), investors can add ("piggyback") their shares. But the company/underwriters can cut investor shares back to 20% (or zero for an IPO). |

### Lock-Up Period
Investors agree not to sell shares for **up to 180 days** after IPO if the underwriter requests it. This prevents a flood of insider selling right after IPO that could tank the stock price. Only applies if all directors, officers, and 1%+ stockholders also agree.

### Information Rights
Major Investors get:
- **Annual audited financials** within 180 days of fiscal year-end
- **Quarterly unaudited financials** within 45 days of quarter-end

This is standard — investors need visibility into how their money is being used.

### Right to Maintain Proportionate Ownership (Pro Rata Rights)
Major Investors can participate in future funding rounds to maintain their ownership percentage. **Sigma gets a special super pro rata right** for the *next* round — they can invest enough to hold at least **25% of fully-diluted post-money capitalization**. This is aggressive and above-market; it essentially guarantees Sigma a large stake going forward.

---

## Transfer Restrictions

### Right of First Refusal (ROFR)
If a founder wants to sell their shares, the **company gets first dibs**, then **Major Investors** get second dibs. This prevents founders from selling to unknown/unwanted third parties.

### Co-Sale Rights (Tag-Along)
If a founder sells shares and the company/investors don't exercise their ROFR, investors can "tag along" and sell a proportional amount of their own shares in the same transaction, on the same terms. This prevents founders from getting a sweetheart exit while investors are left behind.

---

## Other Terms

### Employment Agreement
The CEO (Horvath) must sign a formal employment agreement. This typically includes non-compete clauses, IP assignment, salary, and termination provisions.

### Counsel and Expenses
The **company** (not the investors) pays legal costs for the deal, including up to $25,000 of Sigma's legal fees. Standard practice — but it means the company's limited cash is funding the paperwork.

### Representations and Warranties
Standard legal assurances from the company that everything they've told investors is true — no hidden lawsuits, debts, IP issues, etc. If any turn out to be false, investors may have recourse.

### Conditions to Closing
The deal isn't final until: due diligence checks out, securities laws are satisfied, and the certificate of incorporation is properly filed. Standard safeguards.

---

## Key Numbers at a Glance

| Metric | Value |
|--------|-------|
| Amount raised | Up to $4,595,000 |
| Sigma's investment | $2,925,000 |
| Founders' converted loans | $1,170,000 |
| Pre-financing shares (Common) | 19,328,389 |
| Post-financing shares (Total) | 36,257,969 |
| Investor ownership post-financing | 39.19% |
| Employee option pool | 7.5% of post-money |
| Dividend rate | 4% (non-cumulative, when declared) |
| Liquidation preference | 1x (non-participating); 2x cap in Deemed Liquidation Events |
| Anti-dilution | Broad-based weighted average |
| QPO threshold | 3x Original Purchase Price, ≥$20M net proceeds |
| Board seats | 5 (2 founders, 1 Sigma, 2 independent) |
| Sigma's super pro rata right | Maintain ≥25% in next round |

---

*Compiled from HBS Case 9-814-055: Strava (Rev. August 23, 2016)*

# Zimbabwe Lithium Royalty Exposure

A sensitivity analysis of Zimbabwe's government royalty revenue from lithium exports and an open question about equity-level exposure for Mutapa Investment Fund (MIF) through its wholly-owned miner, Mutapa Energy Resources (MER).

**Status: work in progress.** Core sensitivity model is complete and source-verified. Two extensions are in progress — see Roadmap below.

## The question

Zimbabwe's lithium royalty revenue is highly exposed to swings in the global spodumene price cycle. Holding export tonnage constant, how much does royalty revenue swing purely from price movement and what does that same price mechanism imply for MIF's own equity exposure through MER?

## Method

- **Royalty rate:** flat 7% on lithium ore/concentrate export value (current, enacted rate). A graduated 7%/5%/3% structure by processing stage has been proposed by industry (PLZ, Aug 2026) with parliamentary support, but is not yet law.
- **Export volume:** 1,128,000 tonnes (Zimbabwe FY2025 spodumene concentrate exports), held constant across scenarios so price is the only variable.
- **Prices:** spodumene (6% Li2O, cif China) spot assessments, cross-checked against USGS Mineral Commodity Summaries. The 2025 price points are *implied averages* (export value ÷ tonnage from official trade data), not spot quotes flagged explicitly to avoid conflating the two.

## Finding

At identical export tonnage, Zimbabwe's lithium royalty take ranges from **$29 million to $161 million** — a **5.6x swing** This is driven entirely by where spodumene prices sit in the cycle, not by any change in production.

## The central distinction

Government royalty exposure and MIF's own equity exposure through MER are **not the same number, and likely not even close.** Royalty is a flat cut of revenue, collected regardless of ownership. MIF's actual exposure runs through MER's *profit* revenue minus production costs and debt service (including the recently secured $300M project financing at Sandawana). Because costs don't shrink when prices fall, a price downturn likely compresses MER's margin by more than it compresses royalty revenue — the same underlying mechanism, but a sharper edge for MIF as owner than for government as tax collector.

Quantifying that equity-level exposure precisely would need MER's own production volumes, cost per tonne, and debt terms — data not independently available. Flagging that gap here rather than guessing at it.

## Sources

- Spodumene price history: Fastmarkets/Mining.com reporting, cross-checked against USGS Mineral Commodity Summaries (Jan 2024 edition)
- Zimbabwe lithium royalty rate: Zimbabwe Finance Act provisions, Ministry of Finance mid-term budget reviews
- 2% minerals levy: Finance Act (effective Jan 1, 2025); confirmed as still the 2026 budget baseline (a proposal to raise it to 3% was discussed but not adopted)
- Export volume/value data: Ministry of Finance half-year budget review, state minerals export agency reporting
- Proposed 7%/5%/3% tiered royalty: industry proposal by PLZ (Premier Lithium Zimbabwe), reported Aug 2026 — **not yet enacted policy**

## Roadmap

- [ ] **Volume elasticity** — replace the fixed-volume assumption with a two-variable Price × Volume sensitivity matrix, reflecting that marginal producers cut output during price troughs
- [ ] **Model the tiered proposal** — calculate the actual dollar difference between the current flat 7% and the proposed 7%/5%/3% structure across the same price scenarios
- [ ] Independent confirmation of MER's exact ownership share within MIF
- [ ] MER-specific cost and production data, if it becomes available, to build a true equity-exposure model rather than a royalty proxy

## Disclaimer

This is an independent analysis built from public sources for educational and portfolio purposes. It is not investment advice and is not affiliated with or endorsed by Mutapa Investment Fund, Mutapa Energy Resources or the Government of Zimbabwe.

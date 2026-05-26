# Available .SUPPLY One-Word Domains (11,765)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C765%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .supply one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,765 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,765 domains · **Median ask:** $32.66 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-26  
**Canonical page:** `https://unique.domains/domains/tld/supply`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/supply?utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./supply.csv">CSV</a> / <a href="./supply.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SUPPLY search](https://unique.domains/domains/tld/supply?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SUPPLY search](https://unique.domains/domains/tld/supply?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SUPPLY one-word domain catalog.

### Files

- `supply.csv` — public CSV extract (1,000 rows)
- `supply.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/supply-oneword-domains/main/supply.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| WiFi.supply        | available | $33.48    | —             | 83             | 37     | 5      | namecheap        |
| cocoa.supply       | resell    | —         | —             | 78             | 21     | 5      | GoDaddy.com, LLC |
| events.supply      | premium   | $123.75   | —             | 68             | 37     | 6      | name.com         |
| videos.supply      | available | $30.99    | —             | 52             | 30     | 6      | name.com         |
| shoe.supply        | resell    | —         | —             | 69             | 20     | 4      | Spaceship, Inc.  |
| homes.supply       | premium   | $123.75   | —             | 86             | 34     | 5      | name.com         |
| quotes.supply      | available | $30.99    | —             | 58             | 29     | 6      | name.com         |
| solutions.supply   | premium   | $123.75   | —             | 56             | 31     | 9      | name.com         |
| cams.supply        | available | $25.99    | $25.99        | 52             | 29     | 4      | namesilo         |
| loans.supply       | premium   | $118.80   | $118.80       | 58             | 24     | 5      | namesilo         |
| KFC.supply         | available | $33.48    | —             | 74             | 27     | 3      | namecheap        |
| rocks.supply       | premium   | $123.75   | —             | 78             | 18     | 5      | name.com         |
| gods.supply        | available | $30.99    | —             | 72             | 27     | 4      | name.com         |
| landscaping.supply | premium   | $500      | —             | 80             | 16     | 11     | name.com         |
| trades.supply      | available | $25.99    | $25.99        | 71             | 26     | 6      | namesilo         |
| traders.supply     | available | $30.99    | —             | 60             | 26     | 7      | name.com         |
| sites.supply       | available | $30.99    | —             | 53             | 26     | 5      | name.com         |
| pops.supply        | available | $25.99    | $25.99        | 74             | 24     | 4      | namesilo         |
| shops.supply       | available | $30.99    | —             | 64             | 24     | 5      | name.com         |
| echoes.supply      | available | $25.99    | $25.99        | 56             | 24     | 6      | namesilo         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,765 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/supply?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/supply?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely .supply domain names. The range includes clear category words, product-adjacent terms, and broader dictionary words such as veg.supply, minute.supply, mixing.supply, reader.supply, and thread.supply. For founders, the best choices are usually the names that match a real supply use case, read cleanly, and stay easy to recall. For investors, the key question is whether the term has commercial relevance inside procurement, logistics, industrial, retail, food, or niche supply chains. The median ask is 32.66, so judgment should center on term quality, practical buyer fit, and whether the wording creates a credible .supply pairing rather than relying on novelty alone.

- All names in this selection use the .supply extension
- Median ask across this set is 32.66
- Best fits pair naturally with sourcing or supply use cases
- Watch weak word-extension fit on broad dictionary terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SUPPLY One-Word Domains*. Version 2026-05-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SUPPLY page](https://unique.domains/domains/tld/supply?utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_supply_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

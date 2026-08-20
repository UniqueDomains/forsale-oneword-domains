# Available .FORSALE One-Word Domains (17,612)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C612%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .forsale one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,612 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,612 domains · **Median ask:** $38.09 · **High-demand under $2,500:** 4

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/forsale`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/forsale?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./forsale.csv">CSV</a> / <a href="./forsale.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FORSALE search](https://unique.domains/domains/tld/forsale?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FORSALE search](https://unique.domains/domains/tld/forsale?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FORSALE one-word domain catalog.

### Files

- `forsale.csv`, public CSV extract (1,000 rows)
- `forsale.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/forsale-oneword-domains/main/forsale.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar    |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------ |
| abo.forsale     | available | $13.98    | $47.48        | low            | low    | 3      | namecheap    |
| network.forsale | resell    | —         | —             | high           | medium | 7      | Sav.com, LLC |
| bus.forsale     | premium   | $500      | —             | high           | low    | 3      | name.com     |
| CNN.forsale     | available | $19.99    | —             | high           | low    | 3      | name.com     |
| dad.forsale     | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo     |
| die.forsale     | available | $19.99    | —             | medium         | low    | 3      | name.com     |
| gym.forsale     | premium   | $123.75   | —             | high           | low    | 3      | name.com     |
| ear.forsale     | available | $19.99    | —             | high           | low    | 3      | name.com     |
| jay.forsale     | premium   | $78.54    | $78.54        | medium         | low    | 3      | namesilo     |
| flu.forsale     | available | $19.99    | —             | medium         | low    | 3      | name.com     |
| lit.forsale     | premium   | $118.80   | $118.80       | high           | medium | 3      | namesilo     |
| had.forsale     | available | $19.99    | —             | high           | low    | 3      | name.com     |
| pad.forsale     | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo     |
| hug.forsale     | available | $19.99    | —             | high           | low    | 3      | name.com     |
| two.forsale     | premium   | $82.50    | $82.50        | high           | low    | 3      | name.com     |
| ive.forsale     | available | $19.99    | —             | medium         | low    | 3      | name.com     |
| usa.forsale     | premium   | $1,875    | —             | high           | medium | 3      | name.com     |
| let.forsale     | available | $19.99    | —             | high           | low    | 3      | name.com     |
| wig.forsale     | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo     |
| lol.forsale     | available | $19.99    | —             | high           | low    | 3      | name.com     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,612 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 4 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/forsale?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/forsale?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list contains 12,643 one-word domain names registered under the .forsale extension, each explicitly marked for sale by its current owner. Names range from everyday nouns and phrases — such as backyard.forsale, roastbeef.forsale, and gettogether.forsale — to brand-style terms like Trex.forsale and Scotchtape.forsale. The median asking price across the set is near $52, positioning most of these domains as low-cost, direct-to-buy assets rather than premium holdings. Because the .forsale extension signals seller intent by design, every name here is presumed available for direct purchase, simplifying evaluation for both quick brand pickups and small-scale portfolio additions.

- 12,643 one-word .forsale domains, updated daily
- Median asking price near $52 across the set
- Explicit for-sale extension signals direct buyer intent
- Mix of everyday words and brand-style names, e.g., Trex.forsale

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FORSALE One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FORSALE page](https://unique.domains/domains/tld/forsale?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

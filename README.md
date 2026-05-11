# Available .FORSALE One-Word Domains (12,642)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C642%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .forsale one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,642 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,642 domains · **Median ask:** $50.26 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

- `forsale.csv` — public CSV extract (1,000 rows)
- `forsale.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/forsale-oneword-domains/main/forsale.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| shortcuts.forsale    | available | $19.99    | —             | 48             | 41     | 10     | name.com  |
| roses.forsale        | resell    | —         | —             | 68             | 16     | 5      | 1API GmbH |
| jobs.forsale         | premium   | $1,250    | —             | 79             | 42     | 4      | name.com  |
| matcha.forsale       | available | $19.99    | —             | 86             | 39     | 6      | name.com  |
| ideas.forsale        | premium   | $75       | —             | 62             | 37     | 5      | name.com  |
| WiFi.forsale         | available | $47.48    | —             | 83             | 37     | 5      | namecheap |
| aliens.forsale       | premium   | $118.80   | $118.80       | 56             | 35     | 6      | namesilo  |
| neuroscience.forsale | available | $19.99    | —             | 80             | 37     | 12     | name.com  |
| partners.forsale     | premium   | $1,875    | —             | 61             | 32     | 8      | name.com  |
| etc.forsale          | available | $19.99    | —             | 58             | 34     | 3      | name.com  |
| trends.forsale       | premium   | $82.50    | —             | 60             | 32     | 6      | name.com  |
| payments.forsale     | available | $19.99    | —             | 58             | 33     | 8      | name.com  |
| spaces.forsale       | premium   | $123.75   | —             | 54             | 30     | 6      | name.com  |
| letsgo.forsale       | available | $19.99    | —             | 57             | 31     | 7      | name.com  |
| blocks.forsale       | premium   | $123.75   | —             | 53             | 29     | 6      | name.com  |
| popup.forsale        | available | $19.99    | —             | 84             | 29     | 6      | name.com  |
| cams.forsale         | premium   | $500      | —             | 52             | 29     | 4      | name.com  |
| commonground.forsale | available | $19.99    | —             | 74             | 28     | 13     | name.com  |
| photos.forsale       | premium   | $1,250    | —             | 54             | 28     | 6      | name.com  |
| has.forsale          | available | $19.99    | —             | 60             | 26     | 3      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,642 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/forsale?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/forsale?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .forsale domains. The set leans toward plain-language commercial words, category terms, and broad adjectives such as budget.forsale, luxury.forsale, travel.forsale, calm.forsale, and abundant.forsale. For founders, the strongest picks are usually the words that read cleanly, match an obvious offer, and feel memorable without explanation. For investors, the key question is whether the word has direct commercial meaning and enough buyer relevance to justify the ask. When comparing these domains, focus on word clarity, category fit, pricing discipline, and whether the term feels naturally aligned with a sales-oriented extension.

- Prioritize words with obvious commercial intent
- Compare broad category terms vs. abstract adjectives
- Use price discipline: median ask is 50.26
- Watch for terms that may raise trademark questions

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FORSALE One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FORSALE page](https://unique.domains/domains/tld/forsale?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_forsale_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

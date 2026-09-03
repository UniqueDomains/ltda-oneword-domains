# Available .LTDA One-Word Domains (20,298)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-20%2C298%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .ltda one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **20,298 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 20,298 domains · **Median ask:** $38.08 · **High-demand under $2,500:** 32

**Last updated:** 2026-09-03
**Canonical page:** `https://unique.domains/domains/tld/ltda`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/ltda?utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./ltda.csv">CSV</a> / <a href="./ltda.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LTDA search](https://unique.domains/domains/tld/ltda?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LTDA search](https://unique.domains/domains/tld/ltda?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LTDA one-word domain catalog.

### Files

- `ltda.csv`, public CSV extract (1,000 rows)
- `ltda.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/ltda-oneword-domains/main/ltda.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| age.ltda  | available | $34.99    | $34.99        | high           | low    | 3      | namesilo  |
| new.ltda  | premium   | $56.64    | $33.04        | high           | medium | 3      | namesilo  |
| ale.ltda  | available | $34.99    | $34.99        | medium         | low    | 3      | namesilo  |
| own.ltda  | premium   | $56.64    | $33.04        | high           | high   | 3      | namesilo  |
| ana.ltda  | available | $34.99    | $34.99        | high           | low    | 3      | namesilo  |
| card.ltda | premium   | $56.64    | $33.04        | medium         | medium | 4      | namesilo  |
| Ann.ltda  | available | $34.99    | $34.99        | high           | low    | 3      | namesilo  |
| fund.ltda | premium   | $56.64    | $33.04        | high           | low    | 4      | namesilo  |
| atp.ltda  | available | $34.99    | $34.99        | medium         | low    | 3      | namesilo  |
| game.ltda | premium   | $60       | $35           | high           | medium | 4      | name.com  |
| bee.ltda  | available | $34.99    | $34.99        | high           | medium | 3      | namesilo  |
| gift.ltda | premium   | $56.64    | $33.04        | high           | low    | 4      | namesilo  |
| boo.ltda  | available | $46.98    | —             | high           | low    | 3      | namecheap |
| high.ltda | premium   | $60       | $35           | medium         | low    | 4      | name.com  |
| bro.ltda  | available | $34.99    | $34.99        | medium         | low    | 3      | namesilo  |
| made.ltda | premium   | $56.64    | $33.04        | high           | low    | 4      | namesilo  |
| con.ltda  | available | $34.99    | $34.99        | high           | low    | 3      | namesilo  |
| mall.ltda | premium   | $56.64    | $33.04        | high           | low    | 4      | namesilo  |
| coy.ltda  | available | $34.99    | $34.99        | medium         | low    | 3      | namesilo  |
| more.ltda | premium   | $56.64    | $33.04        | high           | medium | 4      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 20,298 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 32 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/ltda?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/ltda?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=related_pricing)

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

This selection focuses exclusively on single-word .LTDA domain names, spanning everyday nouns and short brandable terms such as matcha.ltda, WiFi.ltda, watches.ltda, and coffeecake.ltda. With a median asking price near $39.53, .LTDA domains offer an affordable way to secure a clean, one-word name across categories like food, technology, lifestyle, and wellness. Because .LTDA is a newer, non-mainstream extension, evaluating each domain on pricing, renewal cost, and pronounceability matters more than relying on the TLD's own recognition.

- 12,879 one-word .LTDA domains tracked in this selection
- Median asking price: ~$39.53 across the list
- Covers food, tech, lifestyle, and wellness one-word terms
- Non-mainstream TLD—compare pricing & renewal before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LTDA One-Word Domains*. Version 2026-09-03. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LTDA page](https://unique.domains/domains/tld/ltda?utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ltda_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

# Available .COMPANY One-Word Domains (13,641)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-13%2C641%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .company one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **13,641 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 13,641 domains · **Median ask:** $7.31 · **High-demand under $2,500:** 0

**Last updated:** 2026-08-15
**Canonical page:** `https://unique.domains/domains/tld/company`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/company?utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./company.csv">CSV</a> / <a href="./company.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .COMPANY search](https://unique.domains/domains/tld/company?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .COMPANY search](https://unique.domains/domains/tld/company?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .COMPANY one-word domain catalog.

### Files

- `company.csv`, public CSV extract (1,000 rows)
- `company.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/company-oneword-domains/main/company.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| lxi.company  | available | $3.99     | $23.99        | low            | low    | 3      | name.com                                     |
| ale.company  | resell    | —         | —             | medium         | low    | 3      | GoDaddy.com, LLC                             |
| Ann.company  | premium   | $242      | $242          | high           | low    | 3      | namesilo                                     |
| yur.company  | available | $3.99     | —             | high           | low    | 3      | name.com                                     |
| god.company  | resell    | —         | —             | high           | medium | 3      | GoDaddy.com, LLC                             |
| cot.company  | premium   | $242      | $242          | high           | low    | 3      | namesilo                                     |
| acid.company | available | $3.99     | $23.99        | low            | low    | 4      | name.com                                     |
| kid.company  | resell    | —         | —             | high           | low    | 3      | GoDaddy.com, LLC                             |
| dew.company  | premium   | $78.54    | $78.54        | medium         | low    | 3      | namesilo                                     |
| asat.company | available | $3.99     | $23.99        | low            | low    | 4      | name.com                                     |
| map.company  | resell    | —         | —             | high           | medium | 3      | Xiamen ChinaSource Internet Service Co., Ltd |
| don.company  | premium   | $242      | $242          | high           | low    | 3      | namesilo                                     |
| ashy.company | available | $3.99     | $23.99        | low            | low    | 4      | name.com                                     |
| oil.company  | resell    | —         | —             | high           | low    | 3      | Sav.com, LLC                                 |
| far.company  | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                     |
| aunt.company | available | $3.99     | —             | high           | low    | 4      | name.com                                     |
| shh.company  | resell    | —         | —             | medium         | low    | 3      | Dynadot Inc                                  |
| hum.company  | premium   | $242      | $242          | high           | low    | 3      | namesilo                                     |
| awed.company | available | $3.99     | $23.99        | low            | low    | 4      | name.com                                     |
| auto.company | resell    | —         | —             | medium         | medium | 4      | Spaceship, Inc.                              |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 13,641 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/company?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/company?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=related_pricing)

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

This list includes 10,374 one-word domain names on the .company extension, drawn from everyday vocabulary such as okay.company, quiet.company, and time.company. With a median ask near $9, most names in this set are priced for direct registration rather than resale. Because .company is a broad, less common extension, availability tends to favor short, literal words over invented brand terms. When comparing names here, weigh word recognition, spelling simplicity, and renewal cost against how directly each word fits an intended use—corporate, product, or personal.

- 10,374 one-word .company domain names in this selection
- Median ask near $9 for direct registration
- Everyday words like okay, quiet, clean, and time
- Compare spelling, tone, and renewal cost before choosing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .COMPANY One-Word Domains*. Version 2026-08-15. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .COMPANY page](https://unique.domains/domains/tld/company?utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_company_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

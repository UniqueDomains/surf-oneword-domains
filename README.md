# Available .SURF One-Word Domains (17,635)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C635%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .surf one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,635 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,635 domains · **Median ask:** $18.27 · **High-demand under $2,500:** 14

**Last updated:** 2026-08-21
**Canonical page:** `https://unique.domains/domains/tld/surf`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/surf?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./surf.csv">CSV</a> / <a href="./surf.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SURF search](https://unique.domains/domains/tld/surf?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SURF search](https://unique.domains/domains/tld/surf?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SURF one-word domain catalog.

### Files

- `surf.csv`, public CSV extract (1,000 rows)
- `surf.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/surf-oneword-domains/main/surf.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| ahuh.surf   | available | $2.19     | $32.49        | high           | low    | 4      | namesilo         |
| dive.surf   | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC |
| aid.surf    | premium   | $500      | —             | medium         | low    | 3      | name.com         |
| amok.surf   | available | $1.98     | $43.98        | low            | low    | 4      | namecheap        |
| load.surf   | resell    | —         | —             | high           | low    | 4      | Porkbun          |
| ala.surf    | premium   | $500      | —             | high           | low    | 3      | name.com         |
| awny.surf   | available | $1.98     | $43.98        | low            | low    | 4      | namecheap        |
| send.surf   | resell    | —         | —             | high           | low    | 4      | Spaceship, Inc.  |
| ane.surf    | premium   | $47.20    | $29.50        | low            | low    | 3      | namesilo         |
| been.surf   | available | $2.19     | $32.49        | medium         | low    | 4      | namesilo         |
| elite.surf  | resell    | —         | —             | high           | medium | 5      | Dynadot Inc      |
| axe.surf    | premium   | $500      | —             | medium         | low    | 3      | name.com         |
| chop.surf   | available | $2.19     | $32.49        | medium         | low    | 4      | namesilo         |
| style.surf  | resell    | —         | —             | high           | low    | 5      | Porkbun          |
| bay.surf    | premium   | $500      | $46.99        | low            | low    | 3      | name.com         |
| cxxv.surf   | available | $1.98     | $43.98        | low            | low    | 4      | namecheap        |
| token.surf  | resell    | —         | —             | high           | low    | 5      | Spaceship, Inc.  |
| BJP.surf    | premium   | $50       | —             | medium         | low    | 3      | name.com         |
| ding.surf   | available | $43.98    | —             | medium         | low    | 4      | namecheap        |
| street.surf | resell    | —         | —             | high           | low    | 6      | GoDaddy.com, LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,635 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 14 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/surf?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/surf?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=related_pricing)

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

This set covers one-word .surf domain names that are currently available to register, spanning short, single-token names across surf, ocean, lifestyle, and general brand themes. With a median asking price near $29.62, these domains sit in an accessible price range for early-stage founders securing an ownable name, while offering investors a low-cost entry point across a niche but growing TLD. Because .surf is not yet a mainstream extension, evaluating each name for spelling clarity, thematic fit, and renewal cost is essential before committing.

- 12,134 one-word .surf domains available to register now
- Median asking price: $29.62 per domain
- Short, single-token names for surf, ocean & lifestyle brands
- Compare renewal cost and brandability before you commit

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SURF One-Word Domains*. Version 2026-08-21. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SURF page](https://unique.domains/domains/tld/surf?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

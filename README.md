# Available .SURF One-Word Domains (12,134)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C134%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .surf one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,134 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,134 domains · **Median ask:** $42.18 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `surf.csv` — public CSV extract (1,000 rows)
- `surf.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/surf-oneword-domains/main/surf.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| Acup.surf       | available | $43.98    | —             | 80             | 5      | 5      | namecheap       |
| barup.surf      | available | $43.98    | —             | 82             | 2      | 6      | namecheap       |
| forces.surf     | available | $43.98    | —             | 82             | 12     | 6      | namecheap       |
| geton.surf      | available | $43.98    | —             | 82             | 10     | 6      | namecheap       |
| Apples.surf     | available | $43.98    | —             | 90             | 16     | 6      | namecheap       |
| gearup.surf     | available | $43.98    | —             | 80             | 16     | 7      | namecheap       |
| toneup.surf     | available | $43.98    | —             | 80             | 5      | 7      | namecheap       |
| hangon.surf     | available | $43.98    | —             | 82             | 6      | 7      | namecheap       |
| dogsick.surf    | available | $43.98    | —             | 90             | 1      | 7      | namecheap       |
| leaveon.surf    | available | $43.98    | —             | 80             | 1      | 8      | namecheap       |
| messages.surf   | available | $2.19     | $32.49        | 80             | 16     | 8      | namesilo        |
| Snickers.surf   | available | $43.98    | —             | 80             | 10     | 8      | namecheap       |
| insight.surf    | available | $43.98    | —             | 76             | 69     | 8      | namecheap       |
| online.surf     | resell    | —         | —             | 70             | 62     | 7      | Spaceship, Inc. |
| videos.surf     | premium   | $100      | —             | 52             | 30     | 6      | name.com        |
| travelers.surf  | available | $2.19     | $32.49        | 58             | 61     | 9      | namesilo        |
| apartments.surf | resell    | —         | —             | 60             | 21     | 10     | Spaceship, Inc. |
| tips.surf       | premium   | $500      | —             | 80             | 26     | 4      | name.com        |
| RedSox.surf     | available | $43.98    | —             | 72             | 60     | 7      | namecheap       |
| houses.surf     | resell    | —         | —             | 66             | 18     | 6      | Spaceship, Inc. |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,134 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/surf?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/surf?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .surf domains. The set includes dictionary-style words, action phrases, and category-adjacent terms such as WiFi.surf, matcha.surf, getup.surf, and jewels.surf. For founders, the main question is whether the word stays credible when paired with .surf; some names feel naturally aligned to movement, lifestyle, media, or niche brands, while others rely more on novelty. With a median ask around $42, the price point is relatively accessible, but extension fit still matters more than raw cost. When comparing these domains, favor names that are easy to say, easy to spell, and clearly ownable within a distinct brand position.

- All names in this set use the .surf extension
- Current selection size: 12,134 domains
- Median ask is about $42 across this set
- Best picks pair clear words with natural .surf fit

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SURF One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SURF page](https://unique.domains/domains/tld/surf?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_surf_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

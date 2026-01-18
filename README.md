# Climate Policy Design Dataset (DCCSR)  
**Domestic Consumer Climate Subsidies & Regulations (1990–2022)**

![Status](https://img.shields.io/badge/status-under%20construction-yellow)
![Language](https://img.shields.io/badge/code-R%20%7C%20Python-blue)
![Reproducibility](https://img.shields.io/badge/reproducibility-in%20progress-orange)

> **Work in progress.**  
> This repository documents and (gradually) packages the code and data workflow behind a climate policy design dataset introduced in Chapter 3 of my dissertation.

---

## Overview

This repository accompanies a novel large‑N dataset of **domestic consumer climate subsidies and regulations (DCCSR)** based on entries from the **IEA Policies and Measures Database**.

**At a glance**
- **Coverage:** 23 advanced democracies  
- **Time:** 1990–2022  
- **Unit of observation:** national policy adoption events (IEA policy records)  
- **Content focus:** fiscal support policies & regulations  
- **Dataset size (final dataset reported in dissertation):** 2,190 fiscal support policies + 1,214 regulations  
- **Key design dimensions (examples):** consumer orientation, target groups, income-group targeting (see “Data dictionary”)

> Note: Some parts of this repository are still being cleaned up for public release (paths, secrets, and documentation).

---

## Repository structure

The repository currently contains three main directories:

```text
.
├── classification/            # AI-assisted classification + post-validation workflows
├── processing/                # data cleaning, reshaping, and dataset compilation
└── descriptive replication/   # scripts/notebooks for descriptive analyses & figures
```

## Data dictionary (lite)

A full codebook is being prepared.
For now, below are the main variable groups documented in the dissertation appendix:
- Policy orientation & targeting
- Consumer_Oriented
- Target_Group
- Income_Group, Income_Confidence
- Ownership_Requirement
- Investment_Costs_and_Financial_Burden
- Policy type & sector mapping
- Policy_Instrument, Sub_Category
- Sector_Classification, sector & instrument counts
- Metadata
- Policy_ID, Country, Year, Description


# ⚠️ Data availability release note:

The dataset is currently under embargo until the dissertation is formally published.
Once released, this folder will contain:
- `data/raw/` (snapshots of source exports where licensing permits)
- `data/processed/` (intermediate files)
- `data/final/` (DCCSR release files)

Until then, this repository focuses on code structure, documentation, and reproducible processing steps.

---

## Reproducibility / Quickstart (minimal)
This repo is currently organized as R Markdown notebooks (plus Python via `reticulate` where applicable).

**General expectations**
- Use repo-relative paths (no local absolute paths).
- No secrets are stored in the repository.

**Environment variables (if needed)**
- `OPENAI_API_KEY` should be provided via your local environment (e.g., `.Renviron`, shell env vars, or keychain/keyring set interactively).
- The repository code should only **read** secrets (never write them).

---

## Changelog
See `CHANGELOG.md`.

---

## Citation
A citation entry will be added once the dissertation/paper is public.  
For now, please cite the dissertation chapter introducing the dataset.

---

## License
License to be confirmed (TBD).

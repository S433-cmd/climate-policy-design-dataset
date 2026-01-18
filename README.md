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

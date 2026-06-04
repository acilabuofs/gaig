# Supplementary Materials Repository

## Manuscript

**A space-time hierarchical modeling framework for crop-specific yield stability and productivity mapping across the Canadian Prairies**

### Authors
Kwabena A. Nketia, T. Ha, H. Fernando, A. Astleford, P. Galpern, M. Kandoth, T. McLoughlin, C. Morrissey, S.V.J. Robinson, and S.J. Shirtliffe

---

## Overview

This repository contains supplementary files, datasets, figures, tables, and supporting materials associated with the manuscript:

> *A space-time hierarchical modeling framework for crop-specific yield stability and productivity mapping across the Canadian Prairies*

The study presents **GAIG-productivity (Geospatial Agroecosystem Inference Generator)**, an explainable space-time modeling framework for mapping crop yield productivity and temporal stability at 10 m spatial resolution across Prairie Canada using multi-year yield monitor records, Earth observation products, weather data, soil information, and landscape variables.

---

## Repository Contents

The repository may include:


Folder names may differ depending on repository organization.

---

## Study Summary

The framework was developed within the **Prairie Precision Sustainability Network (PPSN)** and evaluated across approximately **5.6 million hectares** of cropland spanning Alberta, Saskatchewan, and Manitoba.

Key features include:

- Crop-specific yield prediction at 10 m resolution
- Multi-year temporal yield stability assessment
- Integration of Soil–Plant–Atmosphere–Water (SPAW) variables
- Explainable machine learning using SHAP analysis
- Stacking-fusion ensemble modeling using Ranger Random Forest and CatBoost
- Delineation of:
  - Stable-high productivity zones
  - Stable-low productivity zones
  - Temporally unstable zones

---

## Data Description

Supplementary materials may include:

### Supplementary Tables

| Table | Description |
|---------|-------------|
| Table S1 | Characteristics of focal study regions |
| Table S2 | SPAW explanatory variables and data sources |
| Table S3 | SHAP feature importance summaries and model interpretation outputs |
| Table S4 | Complete model performance metrics across focal areas |

### Supplementary Figures

| Figure | Description |
|---------|-------------|
| Figure S1 | Additional SHAP feature importance analyses |
| Figure S2 | Validation diagnostics and prediction distributions |
| Additional Figures | Regional productivity and stability examples |

---

## Software and Computational Environment

Analyses were implemented primarily in:

- R
- Python

Supporting geospatial and machine-learning workflows included:

- CatBoost
- Ranger Random Forest
- STAC-based geospatial data management
- Google Earth Engine
- SAGA GIS
- GRASS GIS

Computations were performed using high-performance computing resources provided through:

- Digital Research Alliance of Canada (DRAC)
- University of Saskatchewan computational infrastructure

---

## Reproducibility

This repository is intended to support transparency and reproducibility of the published research.

Where permitted by data-sharing agreements and producer privacy requirements, derived products, metadata, and supplementary analyses are provided.

Some source datasets (e.g., producer yield monitor data) are subject to confidentiality restrictions and are therefore not publicly distributed.

---

## Citation

If you use materials from this repository, please cite:

```text
Nketia, K.A., Ha, T., Fernando, H., Astleford, A., Galpern, P.,
Kandoth, M., McLoughlin, T., Morrissey, C., Robinson, S.V.J.,
and Shirtliffe, S.J.

A space-time hierarchical modeling framework for crop-specific
yield stability and productivity mapping across the Canadian Prairies.
[Journal information to be added upon publication]

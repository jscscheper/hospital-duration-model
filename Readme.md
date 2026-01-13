# Hospital Duration Prediction Model

![R](https://img.shields.io/badge/R-4.0-276DC3?logo=r)
![Weka](https://img.shields.io/badge/Weka-3.8-orange)
![tidyverse](https://img.shields.io/badge/tidyverse-1.3-blue)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

A machine learning project to predict whether a diabetes-related inpatient hospital visit will be brief (≤5 days) or prolonged (>5 days).

---

## Overview

Rising healthcare costs, particularly those tied to prolonged hospitalizations, present a significant challenge. This project explores whether machine learning can help predict inpatient length of stay using clinical and administrative data from diabetes-related hospital encounters.

The dataset, sourced from the [UCI Machine Learning Repository](https://doi.org/10.1155/2014/781670), contains approximately 101,000 encounters from 130 US hospitals (1998–2008). After extensive preprocessing—including handling missing values, removing near-zero variance features, recoding diagnosis codes, and log-transforming numeric attributes—the final dataset includes 70,438 records and 22 attributes.

Multiple classifiers were evaluated using Weka, including Random Forest, Simple Logistics, Naïve Bayes, and k-Nearest Neighbors. The best-performing model is a Stacking meta-learner combining optimized Random Forest and Simple Logistics, achieving:

- Accuracy: 79.04%
- AUC: 0.803

---

## Setup

### Requirements
- R (version 4.0+) with RStudio
- Weka (version 3.8) for machine learning

### R Dependencies
Install the required packages in R:

```r
install.packages(c("plyr", "dplyr", "tidyr", "tidyverse", "gridExtra", 
                   "kableExtra", "hexbin", "naniar", "caret", "pals", 
                   "ggplot2", "ggpubr"))
```

### Usage
1. Open `report.Rmd` or `research-log.Rmd` in RStudio
2. Knit to PDF to reproduce the analysis and figures

---

## Layout

| Directory | Contents |
|-----------|----------|
| `datasets/` | Raw data, cleaned base datasets, and Weka result files |
| `figures/` | All generated figures in PDF format |
| `misc/` | Original research paper, codebook, and cover image |

**Root files:**
- `report.Rmd` / `report.pdf` – Final report with methodology and results
- `research-log.Rmd` / `research-log.pdf` – Detailed EDA and preprocessing log

---

## Contact

For questions or issues, contact [jscscheper@gmail.com](mailto:jscscheper@gmail.com).
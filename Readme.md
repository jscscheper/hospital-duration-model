# Hospital Duration Prediction Model

![R](https://img.shields.io/badge/R-4.0-276DC3?logo=r)
![Weka](https://img.shields.io/badge/Weka-3.8-orange)
![tidyverse](https://img.shields.io/badge/tidyverse-1.3-blue)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

Exploratory Data Analysis (EDA) and machine learning workflow for predicting the duration of inpatient hospital visits using diabetes patient data.

---

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Layout](#layout)
- [Contact](#contact)

---

## Overview


# Setup
The data were retrieved from the [UCI website](https://doi.org/10.1155/2014/781670) and used as training and test data for machine learning. We used RStudio (version 4.0.2) to clean, restructure, and visualize the data and results. The following external packages/libraries were used:

- [plyr (1.8.6)](https://www.rdocumentation.org/packages/plyr/versions/1.8.6)
- [dplyr (1.0.2)](https://dplyr.tidyverse.org/)
- [tidyr (1.1.2)](https://tidyr.tidyverse.org/)
- [tidyverse (1.3.0)](https://www.tidyverse.org/)
- [grid (3.6.2)](https://www.rdocumentation.org/packages/grid/versions/3.6.2) and [gridExtra (2.3)](https://cran.r-project.org/web/packages/gridExtra/index.html)
- [kableExtra (1.3.1)](https://cran.r-project.org/web/packages/kableExtra/index.html)
- [hexbin (1.29)](https://www.rdocumentation.org/packages/hexbin/versions/1.29.0/topics/hexbin)
- [naniar (0.6.0)](https://cran.r-project.org/web/packages/naniar/index.html)
- [caret (6.0-86)](http://topepo.github.io/caret/index.html)
- [pals (1.6)](https://cran.r-project.org/web/packages/pals/vignettes/pals_examples.html)
- [ggplot2 (3.3.2)](https://ggplot2.tidyverse.org/) and [ggbiplot (0.55)](https://www.rdocumentation.org/packages/ggbiplot/versions/0.55)
- [ggpubr (0.4.0)](http://www.sthda.com/english/articles/24-ggpubr-publication-ready-plots/)

# Layout
In the root of the repository, you will find the report and log in both PDF and Rmd format. The remaining directories contain:

- `datasets/`: Retrieved datasets from the source above, base datasets consisting of cleaned data without Weka-derived modifications, and datasets containing results exported from Weka.
- `figures/`: All figures related to our findings in PDF format.
- `misc/`: The original paper, the codebook, and older versions of the EDA and the results/discussion paper.
- `peer-review/`: Materials related to the peer review.

# Contact
If you have any questions or encounter issues, please contact us at [j.s.c.scheper@st.hanze.nl](mailto:j.s.c.scheper@st.hanze.nl).
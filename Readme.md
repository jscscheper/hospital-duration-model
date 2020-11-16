# Theme 09: Introduction to Data Mining
In this repository, you find an Exploratory Data Analysis (EDA) log on how data regarding predicting the duration of inpatient hospital visits was cleaned, restructured, and visualized to make it ready for machine learning processing. The process behind machine learning can be found in the log as well, where multiple algorithms, parameter settings, and meta-learners were discussed. Finally, we wrapped our findings in a user-friendly command-line environment to classify new instances. This wrapper is Java-based and is located in the corresponding [repository](https://bitbucket.org/djscheper/javawrapper/src/master/).

# Setup
Data was retrieved from the [UCI website](https://doi.org/10.1155/2014/781670) and used as test and training data regarding machine learning. We used Rstudio (version 4.0.2) to clean, restructure, and visualize data and findings. For that, we used a couple of external packages/libraries:

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
In the root of the repository, you will find the report and log in both pdf and Rmd format. In the other directories, you will find

- `datasets/`: Retrieved datasets from the named source, base datasets consisting of cleaned data with no influence from Weka, and datasets with results from Weka.
- `figures/`: All figures regarding our findings in pdf format.
- `misc/`: The original paper, codebook and older versions of the EDA and results and discussion paper.
- `peer-review/`: Everything related to the peer-review.

# Contact
If any issue or question remains, please contact us at [d.j.scheper@st.hanze.nl](mailto:d.j.scheper@st.hanze.nl)
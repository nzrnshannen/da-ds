# Python and R Data Analysis and Data Science Repository

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

Welcome to the `da-ds` repository! This repository consists of data analysis and data science notes, simple projects, and can also be used as a resource for reviews. I will be using both Python and R languages for the materials in this repository.

> **Note:** Some notebooks and analyses in this repository are currently a work in progress and may be updated over time.
## Repository Structure

The repository is organized by language and domain:

```
da-ds/
│
├── python/
│   ├── data-analysis/
│   │   ├── classification-grouping-eda/
│   │   │   ├── iris.ipynb
│   │   │   ├── penguins.ipynb
│   │   │   └── titanic.ipynb
│   │   ├── regression-trend-eda/
│   │   │   ├── diamonds.ipynb
│   │   │   └── tips.ipynb
│   │   └── time-series/
│   │
│   └── data-science/
│
└── r/
```

### `python/`
Contains Python-based workflows using popular libraries such as `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`.

- **`data-analysis/`**: Focuses on Exploratory Data Analysis (EDA) and general data manipulation.
  - **`classification-grouping-eda/`**: EDA on datasets commonly used for classification and grouping (e.g., [Iris](python/data-analysis/classification-grouping-eda/iris.ipynb), Palmer Penguins, Titanic).
  - **`regression-trend-eda/`**: EDA for continuous targets and identifying trends (e.g., [Tips](python/data-analysis/regression-trend-eda/tips.ipynb), [Diamonds](python/data-analysis/regression-trend-eda/diamonds.ipynb)).
  - **`time-series/`**: Analysis of sequential data over time.
- **`data-science/`**: Dedicated to more advanced machine learning models, training pipelines, and data science methodologies.

### `r/`
Placeholder directory for R-based scripts, analysis, and statistical modeling.

## Getting Started

### For Python (`python/`)
1. Ensure you have a working Python environment with Jupyter Notebook or JupyterLab installed.
2. Install the necessary packages. You will typically need:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Navigate to the desired folder and launch Jupyter:
   ```bash
   jupyter notebook
   ```

### For R (`r/`)
1. Ensure you have [R](https://cran.r-project.org/) installed on your machine.
2. It is recommended to use an IDE like [RStudio](https://posit.co/download/rstudio-desktop/) for running and editing the R scripts.
3. Install necessary R packages inside the R console as needed (e.g., `install.packages("tidyverse")`).

## Contributions
Feel free to add new notebooks, improve existing EDA workflows, or expand the data science section!

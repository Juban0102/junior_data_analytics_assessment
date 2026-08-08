# STILL IN PROGRESS
## Repository Structure

```
.
├── Data/
├── notebooks/
├── Power BI Dashboard/
├── Report/
└── README.md
```

### 📁 Data/

Contains the original dataset provided for the technical assessment.

**Contents**

- `Marketing_Data.csv` — Raw marketing campaign dataset used throughout the project.

---

### 📁 notebooks/

Contains the Jupyter notebooks used to perform the entire analytical workflow in Python.

**Contents**

- `data_cleaning.ipynb`
  - Performs data loading, cleaning, and preprocessing.
  - Performs exploratory data analysis (EDA).
  - Conducts data quality assessment, including missing value analysis, duplicate detection, consistency checks, and outlier investigation.
  - Produces the cleaned dataset used in subsequent analyses.

- `statistical_tests.ipynb`

  - Conducts statistical assumption testing (e.g., normality and homogeneity of variance).
  - Performs hypothesis testing using non-parametric methods, including the Kruskal–Wallis test and Dunn's post-hoc analysis.


> **Note:** All data cleaning, preprocessing, exploratory analysis, statistical testing, and figure generation were performed in Python. The notebooks contain the complete analytical workflow for the project.

---

### 📁 Power BI Dashboard/

Contains the Power BI dashboard developed to present an executive summary of the analysis.

**Contents**

- `.pbix` dashboard file
- Supporting dashboard assets (if applicable)

The dashboard was used to communicate key findings and business insights through interactive visualizations.

---

### 📁 Report/

Contains the written technical assessment documenting the methodology, statistical analyses, results, and business recommendations.

**Contents**

- Final report (PDF)
- LaTeX source files (if included)
- Figures generated from the Python analysis

---

## Notes

While this repository includes a Power BI dashboard, the analytical work—including data cleaning, exploratory data analysis, statistical testing, and hypothesis testing—was conducted entirely in **Python**. Power BI was used exclusively to develop the executive dashboard for presenting the final results.

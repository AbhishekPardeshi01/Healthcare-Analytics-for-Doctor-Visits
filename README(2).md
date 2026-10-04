# Healthcare Analytics for Doctor Visits

## Project Overview

This project analyzes a healthcare dataset to understand patterns in doctor visits, illness, income, health insurance, and reduced activity due to illness.

The dataset contains **5,190 records and 13 columns**. The project uses exploratory data analysis and visualizations to identify patterns and relationships within the provided data.

## Dataset

The dataset includes information about:

- Number of doctor visits
- Gender
- Age
- Income
- Number of illnesses
- Days of reduced activity due to illness
- Health status
- Private health insurance
- Government health insurance related to low income
- Government health insurance related to old age
- Chronic conditions

## Data Quality

The provided dataset was checked before analysis.

- **Records:** 5,190
- **Columns:** 13
- **Missing values:** None
- **Duplicate rows:** None
- Gender values were checked for consistency.
- Binary fields were checked for consistent `yes`/`no` values.
- Numeric variables were checked for valid numeric values.

The dataset was used directly for exploratory analysis without additional data cleaning.

## Analysis Performed

The project covers:

1. Loading and inspecting the dataset
2. Counting people based on their number of illnesses
3. Analyzing maximum, minimum, and mean income
4. Analyzing reduced activity days by gender
5. Visualizing missing values using a heat map
6. Finding correlations between numerical variables
7. Analyzing income versus number of hospital visits
8. Counting males and females affected by illness
9. Visualizing health insurance percentages
10. Analyzing reduced activity days due to illness based on gender

## Visualizations

The project uses:

- Bar charts
- Horizontal bar charts
- Pie charts
- Scatter plots
- Correlation heat maps
- Missing-value heat maps

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Project Structure

```text
Healthcare-Analytics-for-Doctor-Visits/
│
├── P2-Healthcare Analytics for Doctor Visits.csv
├── Healthcare_Analytics_for_Doctor_Visits.ipynb
├── README.md
└── requirements.txt
```

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open the notebook using Google Colab, Jupyter Notebook, JupyterLab, or VS Code with Jupyter support.

Make sure the CSV dataset is available in the project folder or update the dataset path in the notebook.

## Project Focus

The project focuses on relationships among illness, income, gender, reduced activity, health status, insurance coverage, and doctor visits.

The analysis is descriptive and is based only on the provided dataset.

## Future Scope

Future development can include:

- Predictive models for doctor visits
- Prediction of healthcare utilization
- Classification of high healthcare-visit groups
- Comparison of machine-learning algorithms
- Interactive healthcare analytics dashboards
- Deeper statistical analysis
- Feature engineering and model evaluation

## Author

**Healthcare Analytics for Doctor Visits — Data Analysis Project**

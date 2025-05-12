# Evaluating Quality of Life Improvements: Health Drivers and Barriers in Canadian Communities

**Evaluating Quality of Life Improvements: Analyzing Health Drivers and Barriers in Canadian Populations Using CCHS Data**

## Authors
- Aaron Gelfand
- David Griffin
- Venkateshharan Balu Soundararajan
- David Li

## Overview
This Jupyter Notebook presents a comprehensive analysis of the Canadian Community Health Survey (CCHS) data to evaluate quality of life improvements by exploring key health drivers and barriers. Through data preprocessing, exploratory data analysis, statistical modeling, and visualization, we seek to understand how various factors such as substance use, exercise, and demographics influence mental and physical health outcomes.

## Research Questions
### 1. Health Barriers vs. Health Drivers
- How does alcohol consumption affect mental health among different age groups?
- How does cannabis use impact stress levels?
- What is the relationship between smoking and physical health outcomes?
- Which demographic groups (age, sex, region) are most affected by health barriers?

### 2. Health Drivers vs. Health Improvements
- What is the relationship between regular exercise and self-reported health status?
- How does stress influence the maintenance or improvement of mental health?

## Data Source
- **Dataset:** `pumf_cchs.csv` (Public Use Microdata File from the Canadian Community Health Survey)
- **Location:** Place the CSV file in the same directory as this notebook.

## Dependencies
Ensure the following Python packages are installed:
```
pandas
numpy
seaborn
matplotlib
statsmodels
plotly
pydataset
```

## Installation
1. Clone this repository or download the notebook and data file.
2. (Optional) Create and activate a virtual environment:
   ```bash
   python3 -m venv env
   source env/bin/activate  # on Windows: env\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install pandas numpy seaborn matplotlib statsmodels plotly pydataset
   ```

## Usage
1. Open `DATA601_L01-04_Group_Project_Final_Report.ipynb` in Jupyter Notebook or JupyterLab.
2. Run all cells sequentially to reproduce the analysis, figures, and results.

## Notebook Structure
1. **Data Loading & Preprocessing:** Import libraries, load and filter relevant variables.
2. **Exploratory Data Analysis (EDA):** Visualize distributions and relationships among variables.
3. **Statistical Modeling:** Fit OLS regression models to test hypotheses.
4. **Interactive Visualizations:** Generate Plotly figures for deeper insight.
5. **Conclusions:** Summarize key findings and implications.

## Contact
For questions or feedback, reach out to the project authors.

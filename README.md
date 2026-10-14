# Exploratory Data Analysis (EDA) with Python

## Project Overview
This project explores economic data using Python to understand GDP, employment, and growth patterns across countries, sectors, and years. It includes data cleaning, descriptive statistics, exploratory analysis, visualizations, correlation analysis, and business insights.

## Dataset
The notebook loads a CSV file named `Python_Project_Data.csv`.

The analysis uses these columns:
- `Country` — country name
- `Sector` — economic sector
- `Year` — year of observation
- `GDP_Value_USD_Bn` — GDP value in USD billions
- `Employment_%` — employment percentage
- `Growth_Rate_%` — growth rate

**Note:** The dataset is not included in this repository by this README. Update the file path in the notebook or place the CSV in the project folder before running it. The notebook currently contains a local Windows file path, which will need to be changed for another computer.

## Tools and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Workflow
1. **Load libraries and data** using Pandas and the CSV file.
2. **Inspect the dataset** by viewing sample rows, shape, columns, data types, and dataset information.
3. **Clean the data** by checking duplicate records, reviewing sector values, and handling missing values.
4. **Perform statistical analysis** with descriptive statistics.
5. **Explore the data** by country, sector, year, and country-sector combinations.
6. **Create visualizations** including bar charts, pie charts, histograms, box plots, scatter plots, line plots, count plots, heatmaps, and pair plots.
7. **Run advanced EDA** to identify top and bottom countries by GDP, highest and lowest growth sectors, employment extremes, GDP trends, and sector GDP comparisons.
8. **Analyze correlations** among numeric variables.
9. **Summarize business insights** based on the notebook's analysis.

## Key Questions Explored
- Which country contributes the highest total GDP?
- Which sector has the highest average GDP?
- Which sector has the highest average employment?
- How do GDP values change over time?
- Which countries have the highest and lowest GDP or employment?
- Which sectors have the highest and lowest average growth rates?
- What relationships exist between GDP, employment, growth rate, and year?
- What data-quality issues need attention?

## Business Insights Recorded in the Notebook
The notebook records these initial findings:
- India contributes the highest total GDP.
- Agriculture has the highest average GDP in the notebook's recorded result.
- Agriculture is recorded as employing the largest workforce.
- The notebook reports a relationship between employment and GDP and calculates their correlation.
- 2011 is recorded as the year with the highest GDP.
- The UK is recorded as having the highest economic growth.
- Agriculture is recorded as the sector with the lowest growth.
- The notebook discusses positive and negative correlations among numeric variables.

These are the notebook's recorded answers; rerun the analysis against the intended dataset to validate them.

## Requirements
Install the libraries used in the notebook:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## How to Run
1. Download or clone this project.
2. Place `Python_Project_Data.csv` in the project folder, or update the CSV path in the notebook.
3. Open a terminal in the project folder.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `EDA_Python_project(1).ipynb` and run the cells from top to bottom.

## Repository Structure

```text
project/
├── EDA_Python_project(1).ipynb
├── Python_Project_Data.csv
└── README.md
```

## Expected Deliverables
- Jupyter Notebook containing the analysis
- Cleaned dataset after preprocessing
- EDA observations and visualizations
- At least 10 business insights
- Final conclusion summarizing the analysis

## Conclusion
This project demonstrates a complete exploratory data analysis workflow using Python. It uses data cleaning, summary statistics, country- and sector-level comparisons, time-based GDP analysis, visualizations, and correlation analysis to explore economic patterns and support data-driven observations.

## Author
**Mohd Sameer**  
Aspiring Data Analyst


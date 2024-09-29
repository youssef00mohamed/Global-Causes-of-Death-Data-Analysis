# Global Causes of Death Data Analysis

## Project Overview
This project analyzes global causes of death over time using various data cleaning, preprocessing, and visualization techniques. The data is explored by country, year, and cause of death, with trend analysis, regional comparisons, and forecasting.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Data Visualizations](#data-visualizations)
- [Forecasting](#forecasting)
- [Contributions](#contributions)
- [License](#license)

## Installation
To run this project, ensure you have Python installed along with the necessary libraries. You can install the required packages using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. **Clone the Repository**: Clone this repository to your local machine using Git.
   
   ```bash
   git clone https://github.com/youssef00mohamed/Global-Causes-of-Death-Data-Analysis
   ```

2. **Explore the Notebook:** Navigate to the project directory
   ```bash
   cd Global-Causes-of-Death-Data-Analysis
   ```

3. Place the `cause_of_deaths.csv` dataset in the project directory.

4. Run the Jupyter Notebook to analyze the data:
   ```bash
   jupyter notebook Global Causes of Death.ipynb
   ```

## Data Cleaning and Preprocessing
The data undergoes several cleaning and preprocessing steps, including:

- **Initial inspection** of the dataset to check for data types, missing values, and duplicates.
- **Grouping data** by year and country to analyze trends and regional comparisons.
- **Descriptive statistics** to identify outliers and anomalies.

## Data Visualizations
Several visualizations are created to analyze and interpret the data:

- **Correlation Heatmap**: Visualizes the correlation between different causes of death.
- **Trends Over Time**: Line and stacked area charts depict changes in top causes of death over the years.
- **Regional Comparisons**: Bar charts and choropleth maps illustrate the distribution of deaths by cause across countries.
- **Scatter Plots**: Compare specific causes of death across different regions.
- **Facet Grid**: Line plots show trends for selected countries.

## Forecasting
Utilizing ARIMA models, the project forecasts future trends for specific causes of death, such as cardiovascular diseases, predicting deaths for the next 10 years.

## Contributions
Contributions to this repository are welcome! If you have suggestions for improvements, additional analyses, or new datasets to explore, please feel free to open an issue or pull request. Ensure that your contributions align with the project's objectives and maintain code quality and documentation standards.

## License
This project is licensed under the [MIT License](LICENSE).

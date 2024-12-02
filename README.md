# Open Food Facts Data Analysis

This Google Colab notebook performs an exploratory data analysis and preprocessing of the Open Food Facts dataset for French products.

## Project Overview

This project aims to clean and prepare the Open Food Facts dataset for further analysis or modeling. It includes the following steps:

1. **Data Exploration:** Analyze the dataset's structure, descriptive statistics, unique values, and correlations between features.
2. **Data Processing:**
   - **Feature Selection:** Remove irrelevant features with a high percentage of missing values.
   - **Data Cleaning:** Handle missing values, aberrant values, and outliers.
3. **Results and Conclusion:** Summarize the improvements achieved through preprocessing and discuss the findings.


## How to Use

1. **Open the Notebook:** Open the `OpenFoodFacts_DataAnalysis.ipynb` file in Google Colab.
2. **Mount Google Drive:** Mount your Google Drive to access the dataset (or upload it directly).
3. **Run the Code:** Execute the code cells sequentially to perform the analysis and preprocessing.
4. **Review Results:** Examine the generated visualizations, tables, and summary statistics to understand the data and the impact of preprocessing.

## Code Structure

The notebook is organized into sections:

- **Section 1: Data Exploration**
  - 1.1: Loading the data
  - 1.2: Data description and initial analysis
  - 1.3: Unique values analysis
  - 1.4: Correlation analysis

- **Section 2: Data Processing**
  - 2.1: Feature selection based on missing values
  - 2.2: Data cleaning (handling missing values, outliers)

- **Section 3: Results and Conclusion**
  - 3.1: Summarizing the results of preprocessing
  - 3.2: Discussions and final conclusions

## Requirements

- **Google Colab:** The notebook is designed to run in Google Colab.
- **Libraries:** Required libraries are imported within the notebook, including pandas, plotly, and pygments.
- **Dataset:** The Open Food Facts dataset (`fr.openfoodfacts.org.products.csv`) is used for the analysis.

## Notes

- The notebook uses custom display functions to format the output for better readability.
- Ensure the dataset file is correctly loaded either from Google Drive or uploaded directly.
- This project serves as a foundation for further analysis or machine learning tasks using the Open Food Facts dataset.

## Conclusion
The project demonstrates the importance of data preprocessing to improve the quality of the Open Food Facts dataset. By removing irrelevant features, cleaning data, and addressing missing values, the analysis becomes more accurate.

The outcome of this project is a cleaned and informative dataset ready to further analysis and model building.

# magicbricks-eda-project
End-to-end Data Cleaning and Exploratory Data Analysis (EDA) on MagicBricks housing data using Python, Pandas, Matplotlib, and Seaborn to uncover pricing trends, location insights, and property characteristics.
## Project Overview

This project focuses on Data Cleaning and Exploratory Data Analysis (EDA) of MagicBricks housing data. The objective is to analyze property characteristics, identify pricing trends, and uncover key factors influencing house prices across different locations.

Through data preprocessing, visualization, and statistical analysis, meaningful insights were extracted to support data-driven decision-making in the real estate domain.

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Dataset Features

The dataset contains information related to residential properties, including:

- Area
- BHK
- Bathroom
- Furnishing
- Location
- District
- Locality
- Parking
- Property Status
- Transaction Type
- Property Type
- Price
- Price per Square Foot

---

## Project Workflow

### 1. Data Cleaning
- Handled missing values
- Removed duplicate records
- Corrected data types
- Processed categorical variables
- Prepared clean dataset for analysis

### 2. Exploratory Data Analysis (EDA)
- Univariate Analysis
- Distribution Analysis
- Correlation Analysis
- Location-wise Price Analysis
- Feature Relationship Analysis
- Visualization of important trends

---

## Key Visualizations

### Area Distribution
Analyzed the distribution of property area to understand the spread and identify skewness in the data.

### Correlation Heatmap
Examined relationships among numerical features such as Area, BHK, Bathroom, Parking, and Price.

### Median Price by Location
Compared median property prices across locations to identify premium and affordable areas.

---

## Key Insights

- Property Area shows a strong positive correlation with Price.
- BHK and Bathroom count are important factors influencing property prices.
- Premium locations command significantly higher median property prices.
- Property prices are right-skewed, indicating the presence of high-value properties.
- Larger properties generally tend to have higher market value.

---

## Repository Structure

```text
magicbricks-eda-project/
│
├── 01_Data_Cleaning.ipynb
├── 02_Exploratory_Data_Analysis.ipynb
│
├── MagicBricks_Data_Cleaning_Report.pdf
├── MagicBricks_EDA_Report.pdf
│
├── magic_bricks_clean.xls
│
├── area_distribution.png
├── correlation_heatmap.png
├── median_price_location.png
│
└── README.md
```

---

## Files Included

| File | Description |
|--------|-------------|
| 01_Data_Cleaning.ipynb | Data cleaning and preprocessing notebook |
| 02_Exploratory_Data_Analysis.ipynb | Exploratory Data Analysis notebook |
| MagicBricks_Data_Cleaning_Report.pdf | PDF export of data cleaning process |
| MagicBricks_EDA_Report.pdf | PDF export of EDA process |
| magic_bricks_clean.xls | Cleaned dataset |
| PNG Files | Key visualizations generated during analysis |

---

## Conclusion

This project demonstrates practical skills in data cleaning, exploratory data analysis, data visualization, and extracting business insights from real-world housing data using Python and its data analysis libraries.

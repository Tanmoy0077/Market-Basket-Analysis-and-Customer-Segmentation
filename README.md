# Market Basket Analysis and Customer Segmentation

## Overview

This project focuses on analyzing sales data to understand customer behavior through Market Basket Analysis and Customer Segmentation. The analysis is performed using a Jupyter Notebook, which contains all the necessary steps from data cleaning to the application of algorithms.

## Contents

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Market Basket Analysis
  - Apriori Algorithm
  - Association Rule Mining
- Customer Segmentation
  - KMeans Clustering

## Dataset Description

- **Dataset Name:** Market Basket Analysis
- **Source:** [Kaggle](https://www.kaggle.com/datasets/aslanahmedov/market-basket-analysis)
- **Format:** CSV
- **Number of Records:** 522065
- **Number of Features:** 7
- **Feature Descriptions:**
  - `BillNo`: 6-digit number assigned to each transaction. Nominal.
  - `Itemname`: Product name. Nominal.
  - `Quantity`: The quantities of each product per transaction. Numeric.
  - `Date`: The day and time when each transaction was generated. Numeric.
  - `CustomerID`: A 5-digit number is assigned to each customer. Nominal.
  - `Country`: Name of the country where each customer resides. Nominal.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - mlxtend (for apriori algorithm)
  - scikit-learn (for KMeans clustering)

### Installation

To set up the environment, you can use pip to install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn mlxtend scikit-learn
```

### Running the Analysis

1. Clone the repository:
   ```bash
   git clone https://github.com/Tanmoy0077/Market-Basket-Analysis-and-Customer-Segmentation/
   cd Market-Basket-Analysis-and-Customer-Segmentation
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Market_Basket_Analysis_and_Customer_Segmentation.ipynb
   ```

3. Execute the cells in the notebook to perform the analysis.

## Conclusion

This analysis provides insights into customer purchasing behavior and segments customers based on their buying patterns. The findings can be used for targeted marketing strategies and improving sales performance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 

---

Feel free to modify any section to suit your project or personal preferences better!

# Cost of Living Index Analysis

## Overview

This project provides an in-depth exploratory data analysis (EDA) of global cost of living indices, including:
- **Cost of Living Index**
- **Rent Index**
- **Groceries Index**
- **Restaurant Price Index**
- **Local Purchasing Power Index**

The baseline for comparison is New York City (indexed at 100). The analysis includes insights into how these indices vary globally, with special attention to Ireland and comparisons to global averages and New York City.

## Additional Resources

- More Information: For a detailed explanation of the project structure, methodologies, and findings, refer to the Full Project Report.[Full Project Report](https://github.com/federicoariton/Project-2-Exploratory-data-analysis/blob/main/Cost%20of%20Living%20Report%20pdf.pdf)

---

## Objectives

1. Explore and visualize the cost of living structure in different countries.
2. Identify the top 10 most expensive countries based on various indices.
3. Compare Ireland's indices with global averages and New York City.
4. Provide actionable insights by analyzing cost distribution and correlations among indices.

---

## Dataset

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/myrios/cost-of-living-index-by-country-by-number-2024/data)
- **Structure**:
  - 121 countries with indices such as Cost of Living, Rent, Groceries, Restaurant Prices, and Local Purchasing Power.
- **Data Completeness**:
  - No missing values.
  - Data types are appropriate for analysis.

---

## Key Analyses

### 1. Global Cost Analysis
- Identified the top 10 most expensive countries for each index.
- Highlighted Switzerland, Bahamas, and Iceland as consistently high across multiple indices.

### 2. Visualizations
- **Bar Charts**: Top countries for Cost of Living, Rent, Groceries, and Restaurant Price Indices.
- **Box Plots**: Variability of indices among countries.
- **Choropleth Map**: Global representation of Cost of Living Index.

### 3. Weighted Index Calculation
- Developed a Weighted Total Index combining all indices with custom weights for a holistic affordability measure.
- Compared Total Index and Weighted Total Index rankings to highlight differences in cost structures.

### 4. Correlation Analysis
- Created a heatmap showing strong correlations:
  - Cost of Living with Groceries and Restaurant Price Indices.
  - Rent Index heavily influencing the overall cost of living.

### 5. Ireland Focused Analysis
- Compared Ireland’s cost structure to New York City and global averages.
- Visualized Ireland's indices distribution using pie charts and bar charts.
- Highlighted Ireland's mid-tier affordability relative to global standards.

---

## Findings

1. **Switzerland**:
   - Highest costs across all indices but offset by strong purchasing power.
2. **Bahamas and Barbados**:
   - High costs with limited purchasing power, indicating affordability challenges.
3. **Ireland**:
   - Moderately expensive, driven by rent and consumer prices.
   - More affordable than New York City but higher than the global average.

---

## Visuals Included
- Choropleth maps, bar charts, box plots, pie charts, and histograms.

---

## Files
- **`Cost of Living Report.docx`**: Detailed report of the EDA process.
- **`Figures/`**: Visuals generated during the analysis.

---

## Requirements
- Python (version 3.7 or later).
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly.

---

## How to Use
1. Clone the repository.
2. Install the required Python libraries.
3. Run the analysis scripts provided to generate the visualizations and insights.

---

## Future Scope
- Integrate real-time cost of living data.
- Extend analysis to include regional-level data within countries.
- Add predictive modeling for future cost trends.

---

## Author
Federico Ariton  
[GitHub Profile](https://github.com/federicoariton)  
[LinkedIn Profile](https://www.linkedin.com/in/federico-ariton-090b18218/)

---

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

# Real Estate Market Analysis: Mexico and Brazil

## Overview

This project explores the real estate markets in Mexico and Brazil through exploratory data analysis (EDA). By visualizing property trends and analyzing pricing patterns, the goal is to understand regional differences, price distributions, and key market drivers in each country.

The analysis focuses on providing actionable insights to stakeholders interested in market entry, investment, or policy-making decisions related to housing in these countries.

---

## Business Understanding

### Stakeholders
- Real estate investors and developers
- Policy makers and urban planners
- Housing market analysts

### Key Business Questions
1. Are there regional differences in the real estate market, especially in Brazil?
2. What is the distribution of house prices and home sizes?
3. Which areas have the highest and lowest mean price per square meter?
4. What insights can be drawn from spatial property data?

---

## Data Understanding and Analysis

### Source of Data
- Publicly available real estate datasets for Mexico and Brazil (loaded via CSV and SQLite files).
- Data includes price (in USD), area (in square meters), geographical coordinates, and regional classifications.

### Description of Data
- `price_usd`: House price in US dollars.
- `area_m2`: Area of property in square meters.
- `region`: Region where the property is located (Brazil).
- `state`: Specific state (Brazil).
- `lat`, `lon`: Latitude and longitude coordinates of each property.

---

### Methodology

#### **Mexico EDA**
1. **Location Analysis**  
   - Visualized the geographic distribution of properties using Plotly’s `scatter_mapbox` plot, centered on Mexico.

2. **Categorical Analysis**  
   - Counted listings by `state` to identify the most active real estate regions.

3. **Numerical Feature Analysis**  
   - Computed summary statistics for `area_m2` and `price_usd`.
   - Visualized price distribution using a histogram.
   - Used a boxplot to show spread and outliers in property sizes.

#### **Brazil EDA**
1. **Location Analysis**  
   - Created a `scatter_mapbox` plot centered on Brazil to show distribution of real estate listings.

2. **Categorical Analysis**  
   - Analyzed frequency of listings by `state` to determine regional activity.
   - Grouped data by `region` to compute the **mean home price per region** and visualized it with a bar chart.

3. **Numerical Feature Analysis**  
   - Used `.describe()` to summarize key statistics for `area_m2` and `price_usd`.
   - Plotted a histogram to show the distribution of home prices.
   - Constructed a horizontal boxplot to explore the variation in property sizes.

---

### Visualizations

#### **Mexico**

1. **Location of Properties (Mexico)**  
   ![Mexico Map](https://github.com/Harriet-ngomo/Real-estate-analysis-mexico-brazil/blob/781c1df89bb2e3d3ef184f8f5a763800662d64e9/data/Scatter_map.png)

2. **Price Distribution (Mexico)**  
   ![Mexico Price Histogram](path/to/mexico_price_hist.png)

3. **Area Distribution (Mexico)**  
   ![Mexico Boxplot](path/to/mexico_boxplot.png)

#### **Brazil**

1. **Location of Properties (Brazil)**  
   ![Brazil Map](path/to/brazil_map.png)

2. **Price Distribution (Brazil)**  
   ![Brazil Price Histogram](path/to/brazil_price_hist.png)

3. **Area Distribution (Brazil)**  
   ![Brazil Boxplot](path/to/brazil_boxplot.png)

4. **Mean Home Price by Region (Brazil)**  
   ![Brazil Regional Price Bar Chart](path/to/brazil_region_bar.png)

---

## Conclusion

- **Regional Differences**: Both Mexico and Brazil show significant variation in real estate activity across states and regions. In Brazil, the Southeast region has the highest mean home prices.
- **Most Active States**: Certain states dominate in listing frequency, reflecting real estate market concentration in urban centers.
- **Property Sizes and Prices**: Price and area distributions show skewed patterns with clear outliers, indicating a mix of affordable and luxury housing. Brazil exhibits a slightly higher average price compared to Mexico.

These insights can help stakeholders make informed decisions regarding where to invest, develop, or target real estate marketing strategies.



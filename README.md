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
- **Scatter Mapbox Plot:** Shows spatial distribution of properties across Mexican states
   
   ![Mexico Map](https://github.com/Harriet-ngomo/Real-estate-analysis-mexico-brazil/blob/319ca34e5748fcbfe34b71cdbeadaf90a6a611ba/data/images/Mexico/Scatter_map%20mexico.png)

2. **Price Distribution (Mexico)**  
 - Shows price distribution  in various states
   
   ![Mexico Price Histogram](https://github.com/Harriet-ngomo/Real-estate-analysis-mexico-brazil/blob/319ca34e5748fcbfe34b71cdbeadaf90a6a611ba/data/images/Mexico/Price%20distribution%20in%20mexico.png)

3. **Area Distribution (Mexico)**  
- Highlights median prices and outliers in different mexican regions
  
   ![Mexico Boxplot](https://github.com/Harriet-ngomo/Real-estate-analysis-mexico-brazil/blob/319ca34e5748fcbfe34b71cdbeadaf90a6a611ba/data/images/Mexico/Home%20price%20distribution.png)

#### **Brazil**

1. **Location of Properties (Brazil)**  
- **Scatter Mapbox Plot:** 
- Visualized property locations to assess geographical spread
  
   ![Brazil Map](https://github.com/Harriet-ngomo/Real-estate-analysis-mexico-brazil/blob/319ca34e5748fcbfe34b71cdbeadaf90a6a611ba/data/images/Brazil/Brazil%20map.png)

2. **Price Distribution (Brazil)**  
- Shows price distribution in brazil
  
   ![Brazil Price Histogram](https://github.com/Harriet-ngomo/Real-estate-analysis-mexico-brazil/blob/319ca34e5748fcbfe34b71cdbeadaf90a6a611ba/data/images/Brazil/Home%20Price%20histogram.png)

3. **Area Distribution (Brazil)**  
- Highlights median prices and outliers in different Brazilian regions
  
   ![Brazil Boxplot](https://github.com/Harriet-ngomo/Real-estate-analysis-mexico-brazil/blob/319ca34e5748fcbfe34b71cdbeadaf90a6a611ba/data/images/Brazil/Brazil%20Box%20plot.png)

4. **Mean Home Price by Region (Brazil)**  
- Shows the mean price distribution in Brazil
  
   ![Brazil Regional Price Bar Chart](https://github.com/Harriet-ngomo/Real-estate-analysis-mexico-brazil/blob/319ca34e5748fcbfe34b71cdbeadaf90a6a611ba/data/images/Brazil/Brazil%20regional%20Bar.png)

---
**Recommendations**
- Target High-Listing States – Focus on states like Mexico City and São Paulo, which have the highest property listings, indicating strong market activity.

- Invest in Affordable Regions – Explore lower-priced regions like Brazil’s Central-West for cost-effective expansion opportunities.

- Adapt to Regional Property Trends – Align housing designs and marketing strategies with regional differences in property sizes and buyer preferences


## Conclusion

- **Regional Differences**: Both Mexico and Brazil show significant variation in real estate activity across states and regions. In Brazil, the Southeast region has the highest mean home prices.
- **Most Active States**: Certain states dominate in listing frequency, reflecting real estate market concentration in urban centers.
- **Property Sizes and Prices**: Price and area distributions show skewed patterns with clear outliers, indicating a mix of affordable and luxury housing. Brazil exhibits a slightly higher average price compared to Mexico.

These insights can help stakeholders make informed decisions regarding where to invest, develop, or target real estate marketing strategies.


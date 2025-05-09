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

### Key Visualizations

#### 1. **Scatter Map of Properties in Brazil**
Displays spatial distribution of properties to examine geographic clustering and urban market concentrations.

![scatter_map](images/scatter_map.png)

#### 2. **Histogram of Home Prices**
Shows the distribution of home prices in USD to identify price ranges and market segments.

![price_histogram](images/price_histogram.png)

#### 3. **Bar Chart of Mean Home Price by Region (Brazil)**
Highlights regional disparities in property prices across Brazil.

![mean_price_region](images/mean_price_region.png)

---

## Conclusion

### Summary of Findings

1. **Significant Regional Differences**:  
   The Southeast region in Brazil has the highest mean property prices, indicating a more expensive market compared to other regions like Central-West and North.

2. **Concentration of Properties in Urban Areas**:  
   Spatial visualizations show dense clustering of listings in major urban centers, especially São Paulo and Rio de Janeiro.

3. **Broad Distribution of Property Prices and Sizes**:  
   Price and size distributions indicate a diverse housing market with both budget and luxury segments.

These insights can guide stakeholders in investment decisions, housing policy formation, and regional planning initiatives.




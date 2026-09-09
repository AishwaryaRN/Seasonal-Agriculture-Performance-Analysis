# Seasonal Agriculture Performance Analysis

## Project Overview

This project analyzes agricultural performance across **Kharif, Rabi, and Zaid seasons** using data on crop yield, production, environmental conditions, resource usage, disease and pest risk, revenue, and profit.

The analysis uses statistical techniques and data visualizations to identify seasonal patterns, compare crop performance, examine relationships between variables, detect unusual observations, and generate recommendations for better agricultural planning.

## Problem Statement

The project aims to analyze seasonal differences in agricultural performance and identify meaningful patterns, trends, relationships, and variations across different seasons and agricultural conditions.

## Objectives

* Explore and understand the agricultural dataset.
* Clean and prepare the data for analysis.
* Analyze agricultural performance across seasons.
* Identify seasonal trends and variations.
* Compare crop performance across seasons.
* Examine relationships between agricultural variables.
* Analyze resource usage and economic performance.
* Identify unusual observations.
* Generate meaningful insights and recommendations.

## Dataset

The dataset contains **4,000 agricultural records** and **28 variables**, including:

* Farm and geographical information
* Crop and season
* Farm area
* Rainfall and temperature
* Humidity and sunlight
* Soil conditions
* Fertilizer and pesticide usage
* Yield and production
* Market price
* Cost, revenue and profit
* Water usage and efficiency
* Disease and pest risk

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* CSV Dataset

## Methodology

1. Load the agricultural dataset.
2. Explore the dataset and check its structure.
3. Check for missing values and duplicate records.
4. Handle missing values using median imputation.
5. Perform seasonal and crop-wise analysis.
6. Analyze environmental and resource-related variables.
7. Compare economic performance across seasons.
8. Perform correlation analysis.
9. Identify unusual observations using the IQR method.
10. Visualize the results and interpret the findings.

## Key Results

### Seasonal Yield

* **Kharif:** 5.63 tonnes/ha
* **Rabi:** 5.04 tonnes/ha
* **Zaid:** 4.64 tonnes/ha
* Kharif yield was approximately **21.27% higher than Zaid**.

### Economic Performance

* Kharif recorded the highest average profit of approximately **₹1.79 lakh**.
* Rabi recorded an average profit of approximately **₹87,689**.
* Zaid recorded an average loss of approximately **₹24,805**.

### Water Usage

* Zaid recorded the highest average water usage.
* Kharif recorded the highest average water-use efficiency.
* Zaid recorded the lowest water-use efficiency.

### Crop Performance

Sugarcane recorded the highest average yield among the crops. Kharif generally showed higher crop yields than Rabi and Zaid, highlighting seasonal differences in crop performance.

### Risk Analysis

Kharif recorded the highest average disease and pest risk, indicating the need for stronger crop-protection monitoring during the season.

### Outlier Analysis

The IQR method identified **404 unusual observations** in farm profit data. These observations represent statistically unusual values and may require further investigation.

## Visualizations

The project includes visualizations for:

* Average Agricultural Yield by Season
* Average Agricultural Profit by Season
* Crop-wise Average Yield Across Seasons
* Seasonal Water Usage and Efficiency

## Recommendations

* Prioritize suitable Kharif cultivation based on historical performance.
* Improve water management during the Zaid season.
* Strengthen disease and pest monitoring during Kharif.
* Control production costs during Zaid.
* Use seasonal agricultural data for better planning.
* Investigate unusual profit observations for deeper insights.

## Conclusion

The analysis reveals clear differences in agricultural performance across Kharif, Rabi, and Zaid seasons. Kharif demonstrates the strongest overall performance, while Zaid shows weaker economic and water-use performance. The findings highlight the importance of seasonal planning, efficient resource management, crop-protection strategies, and economic evaluation for agricultural decision-making.

## Future Scope

* Expand the dataset with more years and geographical regions.
* Include additional crop, soil, and weather information.
* Develop predictive models for crop yield and profitability.
* Build an interactive agricultural dashboard.
* Provide crop and season recommendations using historical data.
* Integrate real-time weather and environmental data.
* Develop a decision-support system for agricultural planning.

## Project Files

* `Seasonal_Agriculture_Performance_Analysis.ipynb` – Project analysis notebook
* `seasonal_agriculture_performance_dataset.csv` – Dataset
* `requirements.txt` – Python dependencies
* Result images – Analysis visualizations

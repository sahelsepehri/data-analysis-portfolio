# Bike-Sharing Demand Analysis

## Overview

An exploratory data analysis project examining daily bike-sharing demand and its relationship with seasonal patterns, weather conditions, working days, and rider behavior.

The goal is to identify demand patterns and translate analytical findings into practical insights for operational and capacity planning.

## Business Questions

- How does bike rental demand vary across months and seasons?
- How are weather conditions and temperature associated with daily rentals?
- How do registered and casual riders differ in their usage patterns?
- How can these patterns support operational planning?

## Dataset

- **Source:** [UCI Bike Sharing Dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset)
- **File:** `day.csv`
- **Period:** 2011–2012
- **Observations:** 731 daily records
- **Variables:** 16

The dataset includes date, season, month, working-day status, weather conditions, temperature, humidity, wind speed, and daily rental counts.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

- Data quality checks and descriptive statistics
- Daily rental-demand distribution
- Monthly and seasonal demand analysis
- Working-day versus non-working-day comparisons
- Weather and temperature analysis
- Casual versus registered rider comparisons
- Correlation analysis of weather variables and rentals

## Key Findings

- **Seasonality:** Fall had the highest average daily demand, at approximately 5,644 rentals, while spring had the lowest, at approximately 2,604.
- **Monthly demand:** June had the highest average daily rentals, at approximately 5,772, while January had the lowest, at approximately 2,176.
- **Working days:** Average daily rentals were higher on working days (4,585) than on non-working days (4,330).
- **Rider behavior:** Registered riders had higher average rentals on working days, while casual riders had higher average rentals on non-working days.
- **Temperature:** Temperature and daily rentals had a positive correlation of 0.63.
- **Weather:** Average daily rentals were highest in clear or partly cloudy conditions (4,877) and lowest in light rain or snow (1,803).

## Business Recommendations

- Plan bike availability and maintenance around seasonal demand.
- Consider different engagement strategies for registered and casual riders.
- Incorporate weather conditions into operational planning.

## Limitations

The analysis is descriptive and exploratory. Correlation does not establish causation, and the dataset contains no observations in the severe-weather category.

## How to Run

1. Download the UCI Bike Sharing Dataset.
2. Place `day.csv` in the repository's root-level `data` directory.
3. Open `bike-sharing-demand-analysis/bike_sharing_demand_analysis.ipynb`.
4. Install the required Python libraries if necessary.
5. Run the notebook cells in order.

The notebook expects the dataset at `../data/day.csv` relative to the notebook's directory.

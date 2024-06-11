# Energy Nexus: Energy Production, Consumption, and Temperature Change

## Overview
This project investigates the relationship between energy production, consumption, and temperature changes. The analysis focuses on the impact of renewable and non-renewable energy sources on global temperatures and greenhouse gas emissions. The project utilizes multiple datasets to analyze trends and correlations over time.

## Table of Contents
- [Overview](#overview)
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Methodology](#methodology)
- [Guiding Questions and Visualizations](#guiding-questions-and-visualizations)
- [Results](#results)
- [Things to Note](#things-to-note)
- [Installation](#installation)
- [Acknowledgments](#acknowledgments)
- [References](#references)

## Introduction
In recent years, most governments have become keen on reducing global greenhouse gas emissions (GHG) by transitioning to renewable energy. These emissions, primarily composed of gases that retain the sun’s heat, can fundamentally alter the Earth’s climate. Fossil fuels such as coal, oil, and gas play the biggest role in climate change and account for 75% of global GHG and 90% of carbon dioxide emissions. This project aims to highlight the significance of fossil fuel consumption, renewable energy production and consumption, and observe the change in temperature year-over-year for multiple countries over time.

## Datasets
We used four main datasets for this analysis:
1. **World Energy Consumption**: Covers various aspects of global energy consumption, including data on different energy sources such as solar, wind, biofuel, hydroelectric, and fossil fuels.
2. **Modern Renewable Production**: Focuses on renewable energy production, providing insights into wind, hydro, solar, and bioenergy sources.
3. **Global Land Temperatures by Country**: Provides recorded land temperature data for multiple countries over time.
4. **CO2 and GHG Emissions**: Contains detailed information about carbon dioxide (CO2) and greenhouse gas (GHG) emissions from various countries.

## Methodology
### Data Cleaning
The data cleaning process involved:
- Removing irrelevant columns and rows.
- Renaming columns for clarity.
- Handling missing values by either removing or imputing them.
- Creating primary keys for merging datasets.

### Data Analysis
We performed correlation analysis to understand the relationships between different variables:
- Pearson correlation coefficients to measure the strength and direction of linear relationships.
- Visualization techniques to represent the data graphically.

### Tools and Libraries
- Python libraries: pandas, numpy, matplotlib, seaborn, plotly, SQLAlchemy.
- SQL for data manipulation and querying.

## Guiding Questions and Visualizations
### Guiding Question 1: Is there any correlation between temperature change and the shift in renewable energy consumption and fossil fuel consumption?
- **Visualization**: Correlation coefficients between average temperature and different energy variables such as wind, hydro, solar, fossil fuel, and coal consumption.

### Guiding Question 2: Is there any correlation between gas emissions and the shift in renewable energy production and energy consumption?
- **Visualization**: Correlation coefficients between gas emissions and different energy variables such as wind, hydro, solar energy production, fossil fuel, and coal consumption.

## Results
### Correlation Analysis
- Positive but varying degrees of correlation were found between temperature and energy consumption variables.
- Strong correlation between gas emissions and fossil fuel consumption, indicating that fossil fuels contribute significantly to greenhouse gas emissions.

### Visualizations
- Bar charts representing correlation coefficients.
- Line graphs showing trends over time.

## Things to Note
- Correlation does not imply causation; other factors may influence the relationships observed.
- Data transformations and cleaning steps are crucial for accurate analysis.

## Installation
To run this project, you need to have Python installed. Install the required libraries using the following command:
```bash
pip install pandas numpy matplotlib seaborn plotly SQLAlchemy
```

## Acknowledgments
This project was inspired by various data science and environmental studies resources. Special thanks to the open-source community for providing the tools and libraries used in this project.

## 
- StatLib - Datasets Archive: http://lib.stat.cmu.edu/datasets/
- Statistics Canada: https://www.statcan.gc.ca/

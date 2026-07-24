# Exploratory Data Analysis & Visualization in R (`ggplot2`)

This repository contains an exploratory data analysis (EDA) and custom visualization project using the `mpg` dataset in **R** (`ggplot2`, `dplyr`). 

The project demonstrates how to effectively communicate data distribution, compare numerical features across categories, and construct multi-layered graphs combining up to 5 metrics in a single view.

## Visualizations & Insights Highlights

### 1. Feature Distributions & Class Comparisons
* **Histograms & Boxplots:** Comparative analysis of city and highway fuel efficiency (`cty`, `hwy`) across vehicle classes and drive trains (`drv`).
* **Outlier Identification:** Identified high-efficiency outliers within front-wheel drive (`f`) vehicles.

### 2. Multi-Variable Interaction Analysis
* **Engine Displacement vs. Highway Mileage:** Scatter plot analysis demonstrating the expected inverse relationship between engine size (`displ`) and efficiency (`hwy`), segmented by vehicle class.
* **5-Parameter Unified Chart:** Combined numerical trends (mean urban/intercity MPG) and categorical distributions (transmission type across drive trains over time) into a single faceted visualization using `facet_wrap` and dual geometry overlays (`geom_bar` + `geom_line`).
* **Key Insight:** Highlighted technological efficiency gains in 4x4 and rear-wheel drive vehicles between 1999–2008, despite a simultaneous shift toward automatic transmissions.

## Tech Stack & Packages
* **Language:** R
* **Libraries:** `ggplot2`, `dplyr`, `stringr`, `knitr`

## Repository Files
* `HW1_Data_Visualization.html` - Knitted standalone HTML report with complete code, plots, and analysis narratives.

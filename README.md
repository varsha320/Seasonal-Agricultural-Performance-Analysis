# Seasonal Agricultural Performance Analysis

### Data Analysis and Statistical Study of Crop Yield, Profitability, Water Efficiency and Disease/Pest Risk

## 📌 Project Overview

Agricultural performance can vary across seasons due to differences in environmental conditions, farming practices, resource availability, and market conditions.

This project analyzes an agricultural dataset to understand how crop yield, profitability, water efficiency, disease/pest risk, environmental conditions, and resource usage vary across the Kharif, Rabi, and Zaid seasons.

The analysis uses data cleaning, exploratory data analysis, visualization, correlation analysis, and statistical testing to identify meaningful seasonal patterns, relationships, differences, and unusual patterns across states and crops.

---

## 🎯 Problem Statement

Raw agricultural data does not clearly explain how agricultural performance changes across seasons or what patterns occur under different seasonal conditions.

Therefore, this project analyzes the available agricultural data to identify:

- Seasonal differences in agricultural performance
- Important seasonal patterns and trends
- Relationships between environmental conditions and agricultural outcomes
- Differences in crop and state performance
- Seasonal economic outcomes
- Resource usage patterns
- Unusual seasonal patterns
- Statistically significant differences

---

## 🎯 Objectives

The main objectives of this project are:

1. Explore and understand the agricultural dataset.
2. Clean and prepare the data for analysis.
3. Compare agricultural performance across seasons.
4. Identify important seasonal patterns and trends.
5. Analyze relationships between environmental conditions and agricultural outcomes.
6. Compare crops and states across seasons.
7. Identify significant differences and unusual seasonal patterns.
8. Apply statistical and visualization techniques.
9. Interpret findings based on evidence from the dataset.
10. Develop data-driven recommendations for seasonal agricultural planning.

---

## 📊 Dataset

The dataset contains **4,000 records and 28 variables** covering:

- Farm information
- State and district
- Crop
- Season
- Farm area
- Environmental conditions
- Soil conditions
- Agricultural inputs
- Yield
- Production
- Market price
- Revenue
- Cost
- Profit
- Water usage
- Water efficiency
- Disease and pest risk

### Main Seasons

- Kharif
- Rabi
- Zaid

### Important Variables

| Category | Variables |
|---|---|
| Location | State, District |
| Crop | Crop, Season |
| Environmental | Rainfall, Temperature, Humidity, Sunlight |
| Soil | Soil pH, Soil Moisture, Nitrogen, Phosphorus, Potassium |
| Farming Inputs | Irrigation Method, Fertilizer, Pesticide, Seed Quality |
| Agricultural Output | Yield, Production |
| Economic | Market Price, Revenue, Total Cost, Profit |
| Resources | Water Used, Water Efficiency |
| Risk | Disease/Pest Risk |

---

## 🧹 Data Cleaning

The notebook performs several data preparation and validation steps:

- Duplicate record checking
- Missing value analysis
- Missing-value pattern analysis
- Crop-season level missing-value investigation
- Crop-season median imputation for selected numerical variables
- Categorical value consistency checking
- Numerical value validation
- Negative-value validation
- Post-imputation verification
- Final dataset quality validation

Missing values in selected variables such as rainfall, soil moisture, and yield were handled using **Crop-Season group median imputation**.

---

## 🔍 Exploratory Data Analysis

The project investigates agricultural performance through several analyses.

### Seasonal Analysis

- Farm distribution across seasons
- Average yield by season
- Average profit by season
- Revenue, cost, profit, and market price by season
- Water efficiency across seasons
- Disease and pest risk across seasons
- Resource usage across seasons
- Environmental conditions across seasons

### Crop Analysis

- Crop distribution
- Average yield by crop
- Average profit by crop
- Crop yield across seasons
- Crop distribution across seasons

### Regional Analysis

- Average yield by state and season
- State-level agricultural performance
- Best-performing season for each state
- Identification of states with unusual seasonal patterns

---

## 💰 Economic Analysis

The project explicitly analyzes seasonal economic outcomes using:

- Revenue
- Total Cost
- Profit
- Market Price

The analysis shows that:

- **Kharif has the highest average profit**
- **Zaid has the lowest average profit**
- Seasonal profit differences are statistically significant

These results describe associations and differences observed in the dataset and should not be interpreted as proof that season directly causes the economic differences.

---

## 🌱 Environmental Analysis

Environmental variables are analyzed in relation to agricultural yield, including:

- Rainfall
- Average temperature
- Soil moisture
- Humidity
- Sunlight
- Soil conditions

Season-specific correlation analysis is used to examine how relationships between environmental factors and yield vary across Kharif, Rabi, and Zaid.

Correlation results indicate **associations, not causation**.

---

## 💧 Resource and Risk Analysis

The project evaluates:

### Resource Usage

- Water used
- Fertilizer usage
- Pesticide usage
- Water efficiency

### Disease and Pest Risk

Disease and pest risk is compared across seasons to identify periods with relatively higher or lower observed risk.

---

## 📈 Statistical Analysis

The project includes:

### Correlation Analysis

Correlation analysis is used to identify relationships among:

- Environmental factors
- Agricultural inputs
- Yield
- Production
- Water efficiency
- Profit

### One-Way ANOVA

One-way ANOVA is used to test whether mean yield and mean profit differ across Kharif, Rabi, and Zaid seasons.

#### Seasonal Yield

The analysis finds that Kharif has the highest observed average yield.

However, the ANOVA indicates that the differences in mean yield across seasons are **not statistically significant (p > 0.05)**.

#### Seasonal Profit

The ANOVA indicates that the differences in mean profit across seasons are **statistically significant**.

---

## 🚨 Unusual Seasonal Patterns

The project specifically investigates cases where a state or crop does not follow the overall seasonal pattern.

The overall dataset shows:

**Kharif → highest average yield**

However, some states show different seasonal patterns:

- **Karnataka → Zaid**
- **Maharashtra → Rabi**
- **Punjab → Rabi**

These states therefore do not follow the overall Kharif-dominant seasonal yield pattern.

At the crop level, the analysis compares the best-performing season of each crop with the overall best-performing season.

---

## 🌾 Key Findings

### Seasonal Findings

- Kharif has the highest observed average yield.
- Rabi has the second-highest average yield.
- Zaid has the lowest observed average yield.
- Seasonal yield differences are not statistically significant according to the ANOVA.
- Kharif has the highest average profit.
- Zaid has the lowest average profit.
- Seasonal profit differences are statistically significant.
- Water efficiency is highest during Kharif and lowest during Zaid.
- Disease and pest risk is highest during Kharif and lowest during Zaid.
- Seasonal patterns are not uniform across all states.

### Crop-Level Findings

- Sugarcane has substantially higher average yield than the other crops.
- Sugarcane also has the highest average profit.
- Pulses have the lowest average yield.
- Maize, Rice, and Wheat show moderate average yields.
- Profitability varies considerably across crops.

---

## 📌 Important Interpretation

The findings represent patterns and relationships within the available dataset.

Correlation does **not** imply causation. Therefore, environmental factors or seasons should not automatically be considered direct causes of changes in yield or profit.

The unusually high Sugarcane yield should also be interpreted in the context of crop-specific production characteristics.

---

## ⚠️ Limitations

1. The dataset contains 4,000 observations and covers a limited set of states, districts, crops, and seasons.
2. Some variables contain missing observations that were handled using Crop-Season median imputation.
3. The analysis identifies associations and differences but does not establish causal relationships.
4. Sugarcane has a substantially higher yield than other crops, which may reflect crop-specific production characteristics.
5. The dataset contains simulated or structured agricultural observations, so the findings should not automatically be generalized to all real-world agricultural conditions.

---

## ✅ Recommendations

Based on the analysis:

1. Seasonal differences in yield, profitability, water efficiency, and disease/pest risk should be considered during agricultural planning.
2. Higher-profit crops should be evaluated together with their resource requirements before cultivation decisions are made.
3. Water-efficient agricultural practices should be encouraged, particularly during seasons with lower observed water efficiency.
4. Disease and pest management should receive greater attention during seasons with higher observed risk.
5. Environmental and agricultural input variables should be monitored because their relationships with yield and profit may provide useful decision-making information.
6. Future studies should use larger and more diverse datasets, multiple years of observations, and more detailed geographical information.

---

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook
- Visual Studio Code
- GitHub

---

## 📁 Project Structure

```text
Seasonal-Agricultural-Performance-Analysis/
│
├── Seasonal_agriculture_performance_dataset.ipynb
├── seasonal_agriculture_performance_dataset.csv
└── README.md

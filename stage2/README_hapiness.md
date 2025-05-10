# Data Optimists — World Happiness Report 2021

This repository contains an analytical strategy and a comprehensive set of 17 visualization proposals for the Kaggle World Happiness Report 2021 dataset. Our goal is to explore geographic, social, economic, and temporal drivers of national well‑being.

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Dataset Description](#dataset-description)  
3. [Potential Significance](#potential-significance)  
4. [Visualization Proposals](#visualization-proposals)  
5. [Usage](#usage)  
6. [License](#license)  

---

## Introduction

The World Happiness Report 2021 quantifies subjective well‑being across countries using a composite “ladder score.” By analyzing this alongside factors such as GDP per capita, social support, life expectancy, freedom, generosity, and corruption perception, we aim to uncover patterns and drivers of happiness to inform policy and research.

---

## Dataset Description

| Attribute                     | Description                                                      | Type               |
| ----------------------------- | ---------------------------------------------------------------- | ------------------ |
| `country_name`                | Country                                                          | Categorical (str)  |
| `ladder_score`                | Happiness score (0–10)                                           | Numeric (float)    |
| `logged_gdp_per_capita`       | Log of GDP per capita                                            | Numeric (float)    |
| `social_support`              | Perceived social support                                         | Numeric (float)    |
| `healthy_life_expectancy`     | Healthy life expectancy (years)                                  | Numeric (float)    |
| `freedom_to_make_life_choices`| Freedom rating                                                   | Numeric (float)    |
| `generosity`                  | Generosity metric                                                | Numeric (float)    |
| `perceptions_of_corruption`   | Corruption perception                                            | Numeric (float)    |
| `regional_indicator`          | World region                                                     | Categorical (str)  |
| `year` (historical dataset)   | Year (2005–2020)                                                 | Integer            |

---

## Potential Significance

Each proposed visualization includes:

- **Rationale**: Why this visualization is appropriate, the research question it addresses, and the problem it helps solve.  
- **Expected Insights**: The trends, patterns, or correlations we anticipate uncovering, and how they answer specific questions about global happiness.

---

## Visualization Proposals

1. **Global Happiness Choropleth**  
   - **Rationale**: Highlights geographic clusters of high/low happiness, revealing spatial inequality.  
   - **Expected Insights**: Northern Europe scores highest; conflict‑affected or low‑income regions score lowest.

2. **Extremes of Happiness: Top vs Bottom 10**  
   - **Rationale**: Contrasts best and worst performers to spotlight outliers.  
   - **Expected Insights**: Large gaps indicate policy or cultural differences worth investigating.

3. **Scatter & Regression: Social Support vs Happiness**  
   - **Rationale**: Tests the strength of association between social networks and well‑being.  
   - **Expected Insights**: Positive correlation confirms social support as a key driver.

4. **Violin Plot of Regional Score Distributions**  
   - **Rationale**: Shows full distribution (density, quartiles) by region, not just means.  
   - **Expected Insights**: Europe has narrow, high distribution; other regions have wider spread.

5. **Heatmap of Mean Factor Scores by Region**  
   - **Rationale**: Matrix view of six factors across regions for quick comparison.  
   - **Expected Insights**: Northern Europe leads GDP/health; other regions excel in generosity or support.

6. **Bubble Chart: Freedom vs Corruption**  
   - **Rationale**: Multivariate view of governance perceptions and happiness.  
   - **Expected Insights**: High freedom & low corruption countries show highest happiness.

7. **Line Chart: Top‑5 Countries’ Happiness Over Time**  
   - **Rationale**: Interactive trend analysis (2005–2020) for leading nations.  
   - **Expected Insights**: Identify plateaus or dips linked to global events (e.g., pandemic).

8. **GDP vs Healthy Life Expectancy**  
   - **Rationale**: Joint effect of wealth and health on happiness.  
   - **Expected Insights**: High GDP & expectancy cluster with high happiness scores.

9. **Parallel Coordinates: Factor Profiles**  
   - **Rationale**: Visualizes multivariate trade‑offs among factors per country.  
   - **Expected Insights**: Distinct profiles, e.g., wealth/health vs social support/generosity.

10. **Correlation Matrix Heatmap**  
    - **Rationale**: Pairwise linear relationships among all numeric variables.  
    - **Expected Insights**: Strong positive GDP–happiness; negative corruption–happiness.

11. **Pairplot of Key Factors**  
    - **Rationale**: Combines univariate distributions with bivariate scatter for each factor pair.  
    - **Expected Insights**: Region‑based clusters, non‑linear patterns, outliers.

12. **PCA Biplot of Factor Space**  
    - **Rationale**: Reduces dimensionality to reveal latent factor axes.  
    - **Expected Insights**: Primary axis contrasts wealth/health vs social factors.

13. **K‑Means Cluster Map of Countries**  
    - **Rationale**: Groups similar countries across factors; maps clusters geographically.  
    - **Expected Insights**: Archetypes like high‑GDP/health vs low‑all.

14. **Ridgeline Plot of Ladder Score by Region**  
    - **Rationale**: Overlapping density ridges emphasize distribution differences compactly.  
    - **Expected Insights**: Quantified variance: Europe narrow/high, others broad/lower.

15. **Time‑Series Decomposition of Global Average Happiness**  
    - **Rationale**: Separates trend vs short‑term fluctuations (seasonal or event-driven).  
    - **Expected Insights**: Upward trend with sharp dip around 2020.

16. **Geo Bubble Map: Happiness vs GDP**  
    - **Rationale**: Spatial scatter with bubble size & color encoding two metrics.  
    - **Expected Insights**: Geographic correlation of wealth and happiness.

17. **Animated Choropleth Over Time**  
    - **Rationale**: Dynamic view of happiness changes (2005–2020).  
    - **Expected Insights**: Observe shifting well‑being clusters over time.

---

## Usage

1. Clone this repo.  
2. Install dependencies: `pip install -r requirements.txt`  
3. Open `expanded_visualizations.ipynb` in Jupyter Lab/Notebook.  
4. Run all cells to generate interactive plots.

---

## License

This project is licensed under the MIT License.  
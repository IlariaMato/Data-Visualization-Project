# The Flow of Happiness (2019–2024)

## Description

This project analyzes the evolution of global happiness from 2019 to 2024 using data from the **World Happiness Report 2024**.

The goal is to understand how and why happiness levels have changed over time, considering global, continental, and country-level perspectives, as well as the impact of major events such as the COVID-19 pandemic.

---

## Research Questions

The analysis is guided by the following questions:

- How has global happiness changed from 2019 to 2024?
- What are the differences across continents?
- Which countries consistently rank at the top and bottom?
- What factors drive happiness and how have they evolved?
- What was the impact of COVID-19 on global happiness?

---

## Dataset

- Source: World Happiness Report (2019–2024)
- Coverage: ~146 countries per year (157 total)
- Scale: Cantril ladder (0–10)

### Variables included:
- GDP per capita (log)
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perception of corruption
- Dystopia (benchmark for lowest happiness)

Limitations:
- Not all countries are present every year
- Inconsistent country naming (standardized during preprocessing)
- Limited time span (6 years)

---

## Methodology

### Data Collection
- Six datasets (2019–2024) merged using **RStudio**

### Data Cleaning
- ~3.5% missing values → imputed with mean
- Standardization of country names
- Renaming variables

### Data Transformation
- Global yearly averages
- Continental aggregation
- Factor evolution over time
- Creation of ranking groups (Top / Bottom)
- Segmentation: Pre-COVID, COVID, Post-COVID

### Analytical Techniques
- Descriptive statistics (mean, median, standard deviation)
- Trend analysis (temporal evolution)
- Comparative analysis (continents, COVID phases)
- Correlation analysis

### Tools Used
- RStudio (analysis and preprocessing)
- Flourish, Infogram, MapChart (visualization)
- AI tools for coding and documentation support

---

## Key Results

### Global Trends
- Global happiness increased slightly: **+2%** (5.47 → 5.58) :contentReference[oaicite:0]{index=0}
- High variability across countries (std ≈ 1.13)

### Continental Trends
- Oceania: highest happiness (~7.0) but declining (-4.1%)
- Africa: lowest (~4.4), stagnant
- Americas: strongest growth (+3.8%)
- Asia: slight increase (+1.1%)
- Europe: stable (~6.5) :contentReference[oaicite:1]{index=1}

### Consistent Rankings
Top 10 (all years):
- Finland, Denmark, Iceland, Norway, Sweden, Netherlands, Luxembourg

Bottom 10 (all years):
- Botswana, Malawi, Zimbabwe (and Zambia in later analysis)

### Evolution of Drivers
- GDP per capita: +51.8%
- Freedom: +61.4% (strongest growth factor)
- Social support: +13%
- Life expectancy: -20.5% (COVID impact)
- Generosity: declining trend :contentReference[oaicite:2]{index=2}

### Correlation with Happiness
Strongest predictors:
- GDP per capita (0.69)
- Social support (0.69)

Moderate predictors:
- Life expectancy (0.66)
- Freedom (0.54) :contentReference[oaicite:3]{index=3}

---

## Impact of COVID-19

The pandemic significantly affected happiness drivers:

- Life expectancy: strong decline
- Generosity: decreased
- Social support: reduced
- Freedom and GDP: increased

Post-COVID recovery is visible but not complete, indicating adaptation rather than full recovery :contentReference[oaicite:4]{index=4}

---

## Interpretation

Happiness trends show a non-linear pattern:

- 2019–2021: increase (adaptation, digital connection, economic support)
- 2021–2023: decline (inflation, reduced social interaction, global concerns)
- 2024: recovery (psychological adaptation)

Overall, happiness reflects both **economic conditions** and **social-emotional factors** :contentReference[oaicite:5]{index=5}

---

## Conclusion

- Global happiness has shown **resilience and slight growth**
- Economic and individual factors (GDP, freedom) are becoming more dominant
- Social factors (generosity, support) are weakening
- Strong geographical inequalities persist

The findings suggest that future policies should balance:
- Economic development
- Social cohesion
- Individual well-being

---

## Reproducibility

- Data: publicly available (CC BY 4.0)
- Source: worldhappiness.report
- Analysis fully replicable with documented steps
- Tools: open-source (R environment)

---

## Author

Ilaria Mato  
Data Visualization Project

# Data Analysis Portfolio

A collection of statistical analysis and data visualization projects demonstrating proficiency in R, regression modeling, hypothesis testing, and informed decision making.

## Projects

### 1. Course Evaluations Analysis 
**Skills:** Data visualization, exploratory data analysis, statistical interpretation

Analyzed factors influencing university course evaluations, examining relationships between instructor characteristics (physical attractiveness, native English speaker status, gender) and student ratings. Investigated patterns in bike-sharing usage, Capital Metro ridership, and Billboard Top 100 chart performance.

**Key Findings:**
- Physical attractiveness shows weak positive correlation with course ratings
- Native English speakers receive slightly higher evaluation scores
- Bike-sharing usage peaks during commuting hours on weekdays
- Musical diversity in Billboard Top 100 declined from 1960s-2000s, then increased

**Tools:** R (ggplot2, dplyr), statistical visualization

---

### 2. Monte Carlo Simulations for Hypothesis Testing
**Skills:** Hypothesis testing, Monte Carlo methods, statistical inference, p-value calculation

Conducted simulation-based hypothesis tests to evaluate claims about SEC trading patterns, health code violations, jury selection bias, and text watermarking detection.

**Key Findings:**
- Iron Bank's SEC flagging rate (70/2021 trades) significantly exceeds baseline 2.4% (p < 0.001)
- Restaurant chain shows significantly higher health violations than city average (p < 0.001)
- Judge's jury selection shows systematic deviation from county demographics (χ² = 12.426, p = 0.014)
- Successfully identified watermarked text using chi-squared goodness-of-fit tests

**Tools:** R (Monte Carlo simulation, chi-squared tests, bootstrap methods)

---

### 3. Proportion Tests and Matching Analysis
**Skills:** Causal inference, propensity score matching, confidence intervals, experimental design

Analyzed arm-folding preferences across genders and evaluated the causal effect of Get-Out-The-Vote (GOTV) calls on voter turnout using matching techniques to control for confounding variables.

**Key Findings:**
- No significant sex difference in arm-folding preferences (95% CI: [-0.08, 0.18])
- GOTV calls increase voting likelihood by 7.85 percentage points after matching (95% CI: [1.29%, 14.42%])
- Matching on prior voting behavior, age, and party registration reduced bias in treatment effect estimates

**Tools:** R (MatchIt package, propensity score matching, bootstrapping)

---

### 4. Regression and Visualization Analysis 
**Skills:** Multiple regression, interaction terms, prediction modeling, data-driven recommendations

Built regression models to optimize manufacturing processes, analyze grocery pricing patterns, and investigate redlining evidence in insurance markets.

**Key Findings:**
- **Manufacturing Optimization:** Large opening + thick solder minimizes defects (predicted skips: 0.39)
- **Grocery Pricing:** Convenience stores charge $0.41–$0.92 more than grocery stores; income shows weak negative correlation with prices
- **Redlining Analysis:** Minority percentage significantly predicts FAIR insurance policies even after controlling for income, fire risk, and housing age

**Tools:** R (lm, interaction modeling, residual analysis, ggplot2)

---

### 5. Growth Modeling and Elasticity Analysis 
**Skills:** Exponential growth modeling, log-log regression, bootstrap confidence intervals, elasticity estimation

Modeled COVID-19 death growth rates and estimated price elasticity of demand for consumer goods using power-law models.

**Key Findings:**
- Italy COVID growth rate: 0.183/day, doubling time: 3.8 days (95% CI: [3.6, 4.0])
- Spain COVID growth rate: 0.276/day, doubling time: 2.5 days (95% CI: [2.3, 2.7])
- Milk price elasticity: -1.619 (95% CI: [-1.84, -1.41]), indicating demand is elastic

**Tools:** R (exponential models, log transformations, bootstrapping)

---

### 6. Market Analysis and Causal Inference 
**Skills:** Hypothesis testing, confidence intervals, comparative analysis, business recommendations

Evaluated pricing theories in the Austin gas market and assessed eBay's paid search advertising effectiveness using treatment/control comparisons.

**Key Findings:**
- Gas stations without visible competition charge 0.8–8.3¢ more per gallon (p = 0.019)
- Highway access increases gas prices by ~4.6¢/gallon
- Shell charges ~2.8¢ more than other brands (weak evidence)
- Pausing AdWords reduces revenue ratio by 5.2% (95% CI: [-9.1%, -1.3%])

**Tools:** R (t-tests, bootstrap resampling, business analytics)

---

## Technical Skills

**Programming:** R (tidyverse, ggplot2, dplyr, MatchIt, boot, broom, knitr)

**Statistical Methods:**
- Regression (linear, multiple, interaction models)
- Hypothesis testing (t-tests, chi-squared, Monte Carlo)
- Causal inference (matching, propensity scores)
- Confidence intervals (analytical & bootstrap)
- Growth modeling (exponential, log-log)

**Data Visualization:** ggplot2, exploratory data analysis, publication-quality graphics

---

## Repository Structure
```
├── course-evaluations/
│   ├── analysis.Rmd
│   ├── analysis.pdf
│   └── data/
├── monte-carlo-simulations/
│   ├── hypothesis-testing.Rmd
│   ├── hypothesis-testing.pdf
│   └── data/
├── proportion-tests-matching/
│   ├── matching-analysis.Rmd
│   ├── matching-analysis.pdf
│   └── data/
├── regression-visualization/
│   ├── regression-analysis.Rmd
│   ├── regression-analysis.pdf
│   └── data/
├── growth-elasticity/
│   ├── growth-modeling.Rmd
│   ├── growth-modeling.pdf
│   └── data/
└── market-analysis/
    ├── market-study.Rmd
    ├── market-study.pdf
    └── data/
```

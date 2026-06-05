# Spurious Correlation: Chicken Consumption vs. Saudi Oil Imports

An analysis of the spurious correlation between US per capita chicken consumption and crude oil imports from Saudi Arabia (2000–2009), inspired by [Tyler Vigen's Spurious Correlations](https://tylervigen.com/spurious-correlations).

## About

This notebook explores a negative correlation (r ≈ -0.49) between two completely unrelated variables: how much chicken Americans eat and how much oil the US imports from Saudi Arabia.

Unlike the Nicolas Cage example, this one is **not statistically significant** (p = 0.155), making it an even better illustration of how random patterns can appear in data.

## What's Inside

- Dataset exploration with pandas
- Pearson correlation coefficient calculation
- Dual Y-axis time series visualization
- Statistical significance testing (p-value)
- Scatter plot with regression line
- Discussion of correlation vs. causation

## Key Results

| Metric | Value |
|--------|-------|
| Pearson r | -0.49 |
| P-value | 0.155 |
| R² | 0.24 |
| Statistically significant? | No (p > 0.05) |

## Requirements

```
pandas
matplotlib
scipy
numpy
```

## Usage

```bash
pip install pandas matplotlib scipy numpy
jupyter notebook chicken_vs_oil.ipynb
```

## Data Source

Data from Tyler Vigen's [Spurious Correlations](https://tylervigen.com/spurious-correlations). Analysis code is original.

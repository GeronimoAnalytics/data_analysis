# 📊 Data Analysis

A collection of fun and educational data analysis projects.

## Projects

### 🐍 Python

#### [Spurious Correlation Analysis](python/spurious_correlation_analysis.ipynb)

An analysis of the infamous spurious correlation between **swimming pool drownings** and **Nicolas Cage film appearances** (2000–2009), inspired by [Tyler Vigen's Spurious Correlations](https://tylervigen.com/spurious-correlations).

**What's inside:**
- Dataset exploration with pandas
- Pearson correlation coefficient calculation (r ≈ 0.75!)
- Dual Y-axis time series visualization
- Statistical significance testing (p-value)
- Scatter plot with regression line
- Discussion of why **correlation ≠ causation**

**Key takeaway:** Despite a statistically significant correlation (p = 0.013), Nicolas Cage films obviously do not cause swimming pool drownings. This is a textbook example of a spurious correlation — a reminder to always think critically about data relationships.

## Requirements

```
pandas
matplotlib
scipy
numpy
```

## Getting Started

1. Clone this repo
2. Install dependencies: `pip install pandas matplotlib scipy numpy`
3. Open the notebook in Jupyter or VS Code and run all cells

## License

MIT

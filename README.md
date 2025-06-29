# The-Data-Behind-Happiness

**A full-stack data storytelling project exploring what drives happiness across countries using real-world data.**

This project analyzes happiness scores across countries using data from:

- The **World Happiness Report (2011–2024)**
- The **OECD Better Life Index**

We aim to identify the factors most strongly linked with happiness, quantify their impact, and visualize the insights interactively via a custom frontend.

---

## Project Structure

```
project_name/
├── backend/
│   ├── data/               # Raw and processed datasets
│   ├── notebooks/          # Jupyter notebooks (EDA, modeling etc.)
│   ├── scripts/            # Utility scripts (e.g., data cleaning)
│   └── models/             # Saved models or regression outputs
├── frontend/               # React + TypeScript frontend app
│   ├── src/                # Components, pages, utils, API handlers
├── README.md
```

---

## Key Insights

- **GDP per capita** and **Social support** are the strongest predictors of happiness based on correlation and regression analysis.
- **Freedom to make life choices** and **Healthy life expectancy** also have strong, statistically significant effects.
- **Generosity** and **Perceptions of corruption** show weaker or inconsistent influence across countries.
- The **average global happiness score** has remained relatively stable over time, with top countries like Finland consistently scoring highest.
- Countries with low happiness tend to suffer from weak social support, low GDP, and governance issues.

## Regression Summary Interpretation

- The model explains ~XX% (your R² value) of the variation in happiness, which is solid for real-world data.
- Variables with statistically significant p-values (< 0.05) should be viewed as reliable contributors to happiness.
- Residuals are reasonably normally distributed, suggesting the model assumptions are well met.

## Limitations

- Missing data led to dropping a number of rows, potentially biasing results toward better-documented countries.
- Data is observational, not causal — correlations ≠ causation.
- Cultural and contextual factors not in the data (e.g., values, religion, climate) might play a big role.

## Summary

This analysis gives a data-driven view into what makes nations happier. It reinforces the importance of not only economic prosperity but also social and civic factors. These insights can guide policymakers, researchers, and individuals toward more effective decisions for improving well-being.

---

## 📚 Data Sources

- [World Happiness Report](https://worldhappiness.report)
- [OECD Better Life Index](https://stats.oecd.org/Index.aspx?DataSetCode=BLI)

---

## ✅ Status: In Progress

Backend analysis complete. Frontend in development.

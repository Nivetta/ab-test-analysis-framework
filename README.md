# A/B Test Analysis Framework

Reusable Python framework for analyzing A/B tests with statistical rigor.

## Project Overview

This project demonstrates end-to-end A/B test analysis:
- Simulated e-commerce checkout button test
- Statistical significance testing (Chi-square, z-test)
- Effect size calculation & confidence intervals
- Clear recommendation framework

## Tech Stack
- Python (Pandas, SciPy, Statsmodels)
- Jupyter Notebook
- Statistical tests: Chi-square, two-proportion z-test

## Key Results

**Experiment:** Checkout button color change  
**Metric:** Conversion rate  
**Sample Size:** 10,000 users (5,000 per variant)

| Variant | Conversions | Conversion Rate |
|---------|-------------|-----------------|
| Control | ~400 | 8.0% |
| Treatment | ~500 | 10.0% |

**Statistical Significance:** p < 0.05 ✅  
**Recommendation:** Ship treatment variant (25% relative lift)

## Methodology

1. **Hypothesis:** New button color increases conversion rate
2. **Test:** Two-proportion z-test (Chi-square approximation)
3. **Significance Level:** α = 0.05
4. **Power:** 80%
5. **Minimum Detectable Effect:** 2 percentage points

## Files

- `data/generate_data.py` - Synthetic data generation
- `analysis/ab_test_analysis.ipynb` - Main analysis notebook
- `results/ab_test_results.png` - Visualization

## Author

Nivetta T - [LinkedIn](https://www.linkedin.com/in/nivetta-t)
```

---



# Empirical Asset Pricing: FF6 Factor Model Analysis

## Overview

This project performs an empirical asset pricing analysis using CRSP stock data and Fama–French factor models.

We construct Equal-Weighted (EW) and Value-Weighted (VW) portfolios and test:

- CAPM
- Fama–French 5-Factor Model (FF5)
- Fama–French 6-Factor Model (FF6, including momentum)

## Data

- Monthly CRSP stock returns
- Fama–French 5 factors
- Momentum factor
- Sample: 120 monthly observations

Raw data not included due to licensing restrictions.

## Methodology

1. Data cleaning and preprocessing
2. Market capitalization computation
3. Construction of EW and VW portfolios
4. Calculation of excess returns
5. CAPM regression
6. FF5 regression
7. FF6 regression (adding momentum)

## Key Results

### Equal-Weighted Portfolio
- No significant alpha
- Significant positive SMB exposure (small-cap tilt)
- Momentum insignificant

### Value-Weighted Portfolio
- Persistent positive alpha (~0.66% monthly)
- Strong negative SMB exposure (large-cap tilt)
- Momentum insignificant

## Conclusion

EW performance is explained by systematic risk exposures.

VW portfolio exhibits statistically significant abnormal return not captured by FF5 or FF6 models.

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Open notebook in Jupyter or Google Colab.

3. Run all cells sequentially.

---

Author: Ajay Singh
MSc Financial Technology – Warwick Business School

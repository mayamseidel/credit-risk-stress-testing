# Corporate Credit Risk & Stress Testing

## Public Company Portfolio Analysis

![Portfolio Expected Loss Under Stress](portfolio-expected-loss.png)

An illustrative corporate credit-risk framework analysing six large US-listed companies across different sectors using FY2025 financial data.

The project combines financial statement analysis, credit metrics, stress testing and expected-loss modelling to examine borrower-level and portfolio-level credit risk.

---

## Project Overview

This project develops a structured credit-risk framework using publicly available financial data from six companies:

- Verizon Communications — Telecommunications
- Exxon Mobil — Energy
- PepsiCo — Consumer Staples
- Cisco Systems — Technology
- Union Pacific — Industrials
- FedEx — Transportation

The analysis examines how financial performance, leverage, liquidity and financing conditions affect corporate credit profiles and how borrower-level risks translate into portfolio-level exposure.

---

## Analysis

The project covers:

### Credit Metrics
- Gross leverage
- Net leverage
- Interest coverage
- Liquidity coverage

### Credit Resilience
- Relative credit-resilience scoring
- Borrower-level comparison
- Stress sensitivity analysis

### Portfolio Analysis
- Borrower concentration
- Sector exposure
- Portfolio expected loss
- Contribution to expected loss

### Stress Testing

Three adverse scenarios are applied alongside a base case:

- **Moderate:** EBITDA -10%, interest expense +10%, cash -5%
- **Severe:** EBITDA -20%, interest expense +25%, cash -10%
- **Combined:** EBITDA -30%, interest expense +35%, cash -15%

### Expected Loss

Expected loss is estimated using:

**Expected Loss = Probability of Default × Loss Given Default × Exposure at Default**

The model uses an illustrative 40% LGD assumption and total debt as a proxy for EAD.

---

## Data

Financial data is sourced from the companies' FY2025 Form 10-K filings submitted to the US Securities and Exchange Commission.

All financial figures are presented in US$ millions.

EBITDA is standardised using reported financial statement components to improve comparability across companies.

---

## Methodology

The project follows a five-stage framework:

1. Construct a multi-sector corporate debt portfolio
2. Calculate borrower-level credit metrics
3. Assess portfolio concentration and qualitative risks
4. Stress-test financial performance and credit metrics
5. Translate the results into illustrative expected-loss estimates

The model is designed to demonstrate the application of financial modelling and credit-risk concepts rather than replicate a professional rating agency or lender's internal methodology.

---

## Key Takeaways

The analysis demonstrates several important features of corporate credit risk:

- Leverage and debt-servicing capacity vary materially across borrowers.
- Liquidity provides an additional dimension of credit resilience beyond leverage.
- Simultaneous deterioration in earnings, financing costs and cash can materially weaken credit metrics.
- Portfolio-level risk can remain concentrated even when borrowers operate across different sectors.
- Quantitative ratios need to be considered alongside company-specific and sector-specific qualitative risks.

---

## Limitations

The model uses a relatively small sample of six companies and a single FY2025 reporting period.

The credit-resilience score, probability-of-default mapping, stress assumptions, LGD and EAD methodology are illustrative rather than empirically estimated.

The model therefore should not be interpreted as a credit rating, investment recommendation or prediction of actual default.

---

## Tools

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter / Kaggle Notebooks

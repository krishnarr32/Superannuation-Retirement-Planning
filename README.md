# Superannuation Retirement Planning Sensitivity Analysis

> **Excel-based financial planning model** using annuity logic, Monte Carlo simulation, and scenario/sensitivity analysis to evaluate retirement readiness for a hypothetical individual (Emily).

---

## Business Problem

Retirement planning requires understanding whether current savings contributions, salary growth, inflation, and portfolio allocation are sufficient to meet future lifestyle needs.

This project evaluates whether a projected retirement corpus can support expected expenses — and tests how different assumptions affect the outcome.

---

## What This Project Demonstrates

- Retirement capital requirement modelling
- Present value and annuity-based financial planning logic
- Scenario analysis across **Base**, **Best**, and **Worst** cases
- Monte Carlo simulation for corpus outcomes under uncertainty
- Sensitivity analysis across contribution rates, salary growth, returns, inflation, and portfolio allocation
- Dashboard-style workbook presentation for business users

---

## Key Assumptions (Base Case)

| Parameter | Value |
|---|---|
| Current Age | 30 years |
| Current Salary | NZD $70,000 |
| Mean Salary Growth | 3.5% p.a. |
| Employer Contribution | 3% |
| Retirement Age | 65 years |
| Annual Expenses (Today) | NZD $54,000 |
| Inflation Rate | 2% p.a. |
| Required Retirement Capital | ~NZD $1.45 Million |

---

## Scenario Results

| Scenario | Retirement Age | Monte Carlo Corpus | Shortfall / Surplus |
|---|---|---|---|
| Base Case | 65 years | $559,720 | **-$895,037 shortfall** |
| Best Case | 67 years | $1,542,953 | **+$88,196 surplus** |
| Worst Case | 60 years | $361,040 | **-$1,093,717 shortfall** |

---

## Key Findings

- Retirement readiness is **highly sensitive** to contribution rates, expected returns, and inflation assumptions
- The **Best Case** (higher contributions + optimised allocation) is the only scenario achieving surplus
- Monte Carlo simulation reveals that a single-point forecast significantly underestimates risk
- Solver-based portfolio optimisation identifies the best fund allocation mix per scenario

---

## Business Recommendation

Use sensitivity analysis to test whether retirement plans remain sustainable under adverse assumptions. Review contribution strategy or asset allocation when outcomes depend heavily on optimistic inputs — particularly contribution rate and portfolio return assumptions.

---

## Workbook Structure

| Sheet | Contents |
|---|---|
| Dashboard | Summary of all scenarios, inputs, and Monte Carlo results |
| Retirement Capital | Lifestyle cost breakdown, annuity calculations, inflation modelling |
| Sheet7 | Fund allocation comparison across scenarios |
| *(additional sheets)* | Sensitivity tables, simulation outputs |

---

## Tools Used

- **Microsoft Excel** — financial modelling, pivot tables, Solver add-in
- **Monte Carlo Simulation** — NORM.INV randomisation for salary growth and inflation
- **Scenario Analysis** — Base, Best, Worst case comparison
- **Sensitivity Analysis** — contribution rates, returns, inflation, allocation

---

## Repository Structure

```
.
├── superannuation_sensitivity_model.xlsx
└── README.md
```

---

## How To Use

1. Download `superannuation_sensitivity_model.xlsx`
2. Open in **Microsoft Excel** (Solver add-in required for optimisation sheets)
3. Navigate sheets: **Dashboard → Retirement Capital → Sensitivity Analysis**
4. Adjust assumption inputs on the Dashboard to model different scenarios

---

*Project by Sai Krishna Sudarsan | Master of Business Analytics, University of Auckland*

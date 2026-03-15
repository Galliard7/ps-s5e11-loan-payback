# Ps S5E11 Loan Payback

**Kaggle Competition:** [playground-series-s5e11](https://www.kaggle.com/competitions/playground-series-s5e11)

## Dataset Overview

- **Rows:** 593,994
- **Features:** 13
- **Task:** Classification (`loan_paid_back`)

No missing values detected.

## Features

| Feature | Type | Unique Values |
|---------|------|--------------|
| `annual_income` | numeric | 119,728 |
| `debt_to_income_ratio` | numeric | 526 |
| `credit_score` | numeric | 399 |
| `loan_amount` | numeric | 111,570 |
| `interest_rate` | numeric | 1,454 |
| `gender` | categorical | 3 |
| `marital_status` | categorical | 4 |
| `education_level` | categorical | 5 |
| `employment_status` | categorical | 5 |
| `loan_purpose` | categorical | 8 |
| `grade_subgrade` | categorical | 30 |
| `loan_paid_back` | numeric | 2 |

## Key Statistics

| Feature | Mean | Min | Max |
|---------|------|-----|-----|
| `annual_income` | 48,212 | 6,002 | 393,382 |
| `debt_to_income_ratio` | 0.12 | 0.01 | 0.63 |
| `credit_score` | 680.92 | 395 | 849 |
| `loan_amount` | 15,020 | 500.09 | 48,960 |
| `interest_rate` | 12.36 | 3.20 | 20.99 |
| `loan_paid_back` | 0.80 | 0 | 1 |

## Target Distribution

- **`loan_paid_back` = 1:** 79.9%
- **`loan_paid_back` = 0:** 20.1%

## Repository Structure

```
├── notebooks/          # Analysis notebooks
├── docs/               # Reports and documentation
├── data/               # Data files (git-ignored)
├── meta/               # Project metadata and profiling results
└── manifest.json       # Project manifest
```

---

Built with [DataFlow Toolkit](https://github.com/Galliard7/dataflow-toolkit)

# Data Quality Report: ps-s5e11-loan-payback

**Dataset:** 593,994 rows × 13 columns

## Completeness

All columns are 100% complete — no missing values detected.

## Column Types

- **Numeric:** 7 columns — `id`, `annual_income`, `debt_to_income_ratio`, `credit_score`, `loan_amount`, `interest_rate`, `loan_paid_back`
- **Categorical:** 6 columns — `gender`, `marital_status`, `education_level`, `employment_status`, `loan_purpose`, `grade_subgrade`

## Cardinality

| Column | Unique Values | Notes |
|--------|--------------|-------|
| `id` | 593,994 | unique identifier |
| `annual_income` | 119,728 | high cardinality |
| `debt_to_income_ratio` | 526 | high cardinality |
| `credit_score` | 399 | high cardinality |
| `loan_amount` | 111,570 | high cardinality |
| `interest_rate` | 1,454 | high cardinality |
| `gender` | 3 | low cardinality |
| `marital_status` | 4 | low cardinality |
| `education_level` | 5 | low cardinality |
| `employment_status` | 5 | low cardinality |
| `loan_purpose` | 8 | low cardinality |
| `grade_subgrade` | 30 | moderate cardinality |
| `loan_paid_back` | 2 | binary |

## Numeric Distributions

| Feature | Mean | Std | Min | 25% | 50% | 75% | Max |
|---------|------|-----|-----|-----|-----|-----|-----|
| `annual_income` | 48,212 | 26,712 | 6,002 | 27,934 | 46,558 | 60,981 | 393,382 |
| `debt_to_income_ratio` | 0.12 | 0.07 | 0.01 | 0.07 | 0.10 | 0.16 | 0.63 |
| `credit_score` | 680.92 | 55.42 | 395 | 646 | 682 | 719 | 849 |
| `loan_amount` | 15,020 | 6,927 | 500.09 | 10,280 | 15,000 | 18,859 | 48,960 |
| `interest_rate` | 12.36 | 2.01 | 3.20 | 10.99 | 12.37 | 13.68 | 20.99 |
| `loan_paid_back` | 0.80 | 0.40 | 0 | 1 | 1 | 1 | 1 |


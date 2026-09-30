# Email Campaign Incrementality Analysis

## Business question

Which email campaigns generate sales that would not have occurred without the campaign?

This project analyzes the MineThatData Email Analytics Challenge using a randomized experiment with two email treatments and a control group.

## Objectives

- Validate the randomization.
- Compare visit, conversion, and spend outcomes across experimental groups.
- Estimate causal incremental lift.
- Quantify uncertainty with confidence intervals and hypothesis tests.
- Explore treatment-effect heterogeneity across customer segments.
- Build an interpretable targeting policy based on expected incremental value.

## Tech stack

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- SQL
- Matplotlib
- Seaborn
- Jupyter

## Repository structure

```text
email-causal-analysis/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
├── sql/
├── reports/
│   └── figures/
├── .gitignore
├── README.md
└── requirements.txt
```

## Planned analysis

1. Data quality checks
2. Randomization and balance checks
3. Exploratory data analysis
4. Global treatment-effect estimation
5. Incremental revenue estimation
6. Heterogeneity analysis
7. Budget / targeting policy
8. Out-of-sample validation
9. Final experimentation report

## Primary outcome

`spend`

## Secondary outcomes

- `conversion`
- `visit`

## Causal estimands

- Mens Email vs Control
- Womens Email vs Control
- Mens Email vs Womens Email

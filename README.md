# powerbi-salary-calculator
This Power BI report is designed to help calculate and analyze monthly salary, bonuses and taxes.

powerbi-salary-calculator/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── reports/                # Power BI (.pbix) files
│   └── salary_calculator.pbix
│
├── data/                   # Sample or masked datasets
│   └── example_data.csv
│
├── docs/                   # Screenshots or documentation for the report
│   ├── overview.png
│   └── data_flow_diagram.png
│
└── scripts/                # Power Query (M) or DAX snippets if any
    ├── power_query/
    │   └── transform_salary_data.m
    └── dax/
        └── calculate_monthly_income.dax

# Power BI Salary Calculator

This Power BI report is designed to help calculate and analyze monthly salary, bonuses, taxes, and deductions. It supports visualization of income breakdowns and trends over time.

## Features

- Base salary tracking
- Bonus and overtime calculation
- Tax and deduction breakdown
- Monthly and yearly income summaries

## Folder Structure

- `reports/` – Power BI .pbix file
- `data/` – Sample or masked data
- `scripts/` – Power Query (M) or DAX formulas
- `docs/` – Diagrams or screenshots of report visuals

## Getting Started

1. Clone this repo.
2. Open the `.pbix` file in Power BI Desktop.
3. Replace `example_data.csv` with your own salary data.
4. Refresh the data and customize visuals as needed.

## License

[MIT](LICENSE)
# Power BI Salary Calculator

This Power BI report helps calculate and analyze monthly salary, bonuses, taxes, and deductions. It includes visual summaries and trends to support personal finance and payroll management.

---

## 📁 Folder Structure

powerbi-salary-calculator/
├── README.md # Project overview and instructions
├── LICENSE # License file (MIT recommended)
├── .gitignore # Git ignore rules

├── reports/ # Power BI report files
│ └── Laskuri-2024.pbix # Main Power BI salary calculator

├── data/ # Excel data sources (must be added locally)
│ └── sheema.xlsx # NOT included—must be added by the user

---

## ✨ Features

- Base salary tracking
- Overtime and bonus calculation
- Tax and deduction handling
- Shift planning and compensation metrics
- Monthly and annual summaries
- Custom visuals (e.g., MAQ calendar)

---

## 🚀 Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop)
- Your own `sheema.xlsx` file (Excel sheet with shift/salary data)

---

### Steps

1. **Clone the repository** or download the ZIP.
2. Place your Excel file in the following folder:
3. **Open the report** from `reports/Laskuri-2024.pbix` using Power BI Desktop.
4. Go to **Transform Data > Manage Parameters** and set the `FolderPath`:
    Full path to your local data/ folder
    Example: C:\Users\yourname\Documents\powerbi-salary-calculator\data\
5. Click **Close & Apply** to load the data.
6. Explore or modify the report visuals as needed.

---

## ⚠️ Note on Data Usage

This project includes an example dataset: `data/sheema.xlsx`.

- It is a **sample schema file** with placeholder structure used by the report.
- You **should not replace this file** with your actual salary data unless you understand how the report's Power Query logic is built.

If you want to:
- **Adjust salary amounts, bonuses, or tax logic**, do so **inside Power BI** via:
  - **Transform Data** (Power Query Editor)
  - DAX measures
  - Parameter tables

❗ Do not modify `sheema.xlsx` directly unless you're extending the schema.  
Instead, adapt calculations using Power BI’s built-in functions for maximum flexibility and consistency.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Need Help?

If you have issues configuring the path or customizing your report, feel free to open an issue or request a walkthrough.
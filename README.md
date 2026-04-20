# Inventory-Report
Excel data-cleaning project demonstrating practical steps to prepare transactional data for analysis: date parsing, deduplication, missing-value handling, and text normalization

Excel Data-Cleaning — Transactional Dataset

Short description
Excel data-cleaning project demonstrating practical steps to prepare transactional data for analysis: date parsing, deduplication, missing-value handling, and text normalization. Includes derived features (transaction frequency, avg amount, account age), pivot summaries, and a cleaned workbook ready for Power BI.

What’s included

    excel/
        data_cleaning.xlsx — raw and cleaned sheets with step-by-step transformations
        pivot_reports.xlsx — pivot tables and summary sheets
    sample_datasets/
        synthetic_transactions.csv — input sample data
    docs/
        eda_outline.md — EDA checklist and analysis suggestions
        feature_list.md — derived feature definitions
    scripts/ (optional)
        generate_metadata.py — small helper to (re)create sample data

Getting started

    Clone or download the repo.
    Open excel/data_cleaning.xlsx:
        Review the “Raw” sheet for original data and “Cleaned” for applied transformations.
        Follow annotated steps and formulas to reproduce cleaning.
    Use pivot_reports.xlsx to explore summary statistics and segments.
    Optionally open powerbi/fraud_dashboard.pbix (if present) to visualize cleaned data.

Key cleaning steps

    Parse and standardize date/time fields
    Remove duplicates and inconsistent records
    Handle missing values with rules and imputation
    Normalize text (merchant names, categories)
    Create derived features: transaction frequency, average amount, account age

Learning outcomes

    Practical Excel techniques for cleaning transactional data
    Building pivot summaries for EDA
    Preparing a dataset for visualization and basic modeling

Suggested next steps

    Add automated cleaning scripts (Python/R) for reproducibility
    Engineer rolling-window/time-series features
    Implement imbalanced sampling and baseline model evaluation

Contributing
Open an issue or pull request with improvements or additional examples.

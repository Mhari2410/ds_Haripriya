

# Trader Behavior Insights – Data Science Assignment

## Overview

This project analyzes the relationship between **Bitcoin market sentiment** (Fear/Greed) and **trader performance** using:

* Historical Trader Data from Hyperliquid
* Bitcoin Fear & Greed Index data

The analysis explores **profitability, win rate, trading volume, and drawdowns** across different sentiment phases to uncover insights for smarter trading strategies.

---

## Folder Structure

```
ds_Haripriya/
├── notebook_1.ipynb              # Google Colab notebook with full analysis
├── csv_files/                    # Processed CSV outputs
│   ├── merged_data_sample.csv     # Sample of merged dataset (size-limited for GitHub)
│   └── summary_by_sentiment.csv   # Aggregated performance metrics
├── outputs/                       # Visual outputs from EDA
│   ├── average_pnl_by_sentiment.png
│   ├── total_pnl_by_sentiment.png
│   ├── win_rate_by_sentiment.png
│   ├── volume_by_sentiment.png
│   ├── cumulative_pnl_by_sentiment.png
│   ├── boxplot_pnl_by_sentiment.png
│   └── scatter_daily_volume_vs_pnl.png
├── ds_report.pdf                  # 5-page final report with insights
└── README.md                      # This file
```

---

## How to Run

1. Open `notebook_1.ipynb` in **Google Colab**.
2. Ensure internet access is enabled to download the original datasets from the given Google Drive links.
3. Run all cells to:

   * Download datasets
   * Merge & process data
   * Generate visualizations
   * Save processed CSVs & charts

---

## Notes

* **`merged_data_sample.csv`** contains a **5,000-row sample** due to GitHub’s file size limits.
* The **full merged dataset** can be recreated by running `notebook_1.ipynb` with the original CSV files.
* All plots referenced in `ds_report.pdf` are available in the `outputs/` folder.

---

## Author

**Haripriya**
Junior Data Scientist – Trader Behavior Insights Candidate



# Trader Behavior Insights – Market Sentiment Analysis

## Overview
This project analyzes the relationship between trader behavior and market sentiment
using historical trading data and the Bitcoin Fear & Greed Index. The goal is to
understand how profitability and trading activity vary during Fear and Greed
market conditions.

## Datasets
- **Historical Trader Data**: Trade-level execution data including timestamps,
  profit and loss (PnL), trade size, and trade count.
- **Bitcoin Fear & Greed Index**: Daily market sentiment classified as Extreme Fear,
  Fear, Neutral, Greed, and Extreme Greed.

## Methodology
- Cleaned and standardized trade timestamps.
- Engineered daily-level trading metrics such as total PnL, average PnL,
  total trading volume, and trade count.
- Normalized market sentiment into binary categories (Fear vs Greed).
- Merged trading data with sentiment data using date-based alignment.
- Visualized relationships between sentiment and trader performance.

## Key Insights
- Greed periods show higher trading activity and greater PnL variability.
- Fear periods exhibit more conservative trading behavior.
- Market sentiment plays a significant role in influencing trader behavior.

## Project Structure
ds_siri_varsha/
├── notebook_1.ipynb
├── ds_report.pdf
├── outputs/
│ ├── pnl_vs_sentiment.png
│ └── volume_vs_sentiment.png
├── csv_files/
│ └── merged_data.csv
└── README.md


## Notes
The final merged dataset contains limited overlapping dates between the two
datasets. No artificial data alignment was performed to preserve data integrity.

## Author
Siri Varsha Nistala

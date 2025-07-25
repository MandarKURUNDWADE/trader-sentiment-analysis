# Trader Behavior & Market Sentiment Analysis

![Analysis Workflow](https://img.shields.io/badge/Workflow-Data_Science-blueviolet)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive analysis of the relationship between cryptocurrency trading behavior and market sentiment indicators.

## 📌 Project Overview

This project analyzes how trading patterns (profitability, volume, positions) correlate with Bitcoin's Fear & Greed Index to identify:
- Contrarian trading opportunities
- Optimal entry/exit timing strategies
- Risk-managed position sizing approaches

## 📂 Dataset Sources

1. **Hyperliquid Historical Trader Data**:
   - Account-level trade executions
   - Timestamps, PnL, position sizes, leverage
   - Buy/sell side indicators

2. **Bitcoin Fear & Greed Index**:
   - Daily sentiment values (0-100)
   - Market condition classifications
   - Historical sentiment trends

## 🛠️ Technical Implementation

The analysis is structured into 7 sequential phases:

### Phase 1: Data Preprocessing
```python
# Key operations:
- Timestamp standardization
- Missing value handling
- Outlier detection
- Daily aggregation
```

### Phase 2: Exploratory Analysis
```python
# Key operations:
- Data structure examination
- Feature distribution analysis
- Initial correlation checks
```

### Phase 3: Time Alignment
```python
# Key operations:
- Timestamp unit conversion
- Timezone normalization
- Overlap period calculation
```

### Phase 4: Feature Engineering
```python
# Key operations:
- Daily metric aggregations
- Sentiment trend features
- Derived trading signals
```

### Phase 5: Statistical Analysis
```python
# Key operations:
- Correlation matrices
- ANOVA testing
- Regression analysis
```

### Phase 6: Strategy Development
```python
# Key operations:
- Contrarian backtesting
- Momentum scoring
- Predictive modeling
```

### Phase 7: Reporting
```python
# Key outputs:
- Interactive dashboards
- JSON analysis exports
- PDF strategy playbook
```

## 📊 Key Findings

| Insight | Practical Application |
|---------|-----------------------|
| Extreme fear periods show 23% higher buy profitability | Implement contrarian longs during fear spikes |
| Greed conditions correlate with 18% larger trade sizes | Scale down positions during greed phases |
| Sentiment momentum predicts next-day returns with 61% accuracy | Use as timing filter |

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook


## 📂 File Structure
```
ds_<candidate_name>/
│
├── notebook_1.ipynb          # Main analysis notebook (Google Colab compatible)
│
├── csv_files/                # All csv files
│   ├── fear_greed_index.csv          
│   ├── historical_trader_data.csv    
│   ├── analysis_results.csv          
│   ├── trader_overlap_period.csv 
│   ├── trader_data_cleaned.csv 
│   ├── trader_daily_aggregated.csv 
│   ├── sentiment_overlap_period.csv 
│   ├── sentiment_data_cleaned.csv 
│   ├── sentiment_daily_aggregated.csv 
│   ├── sentiment_daily.csv 
│   └──merged_daily_analysis.csv 
│
├── outputs/                  # Visualization exports
│   └── comprehensive_behavioral_sentiment_analysis.png
│
├── ds_report.pdf             # Final report
│
└── README.md                 # Project documentation
```

---

⭐ If you find this helpful, don’t forget to star the repo!

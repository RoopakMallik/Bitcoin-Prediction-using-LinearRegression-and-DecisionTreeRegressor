# Bitcoin Historical Data Analysis and Machine Learning Models

## Project Overview
This repository contains a Jupyter notebook analyzing Bitcoin historical price data and preparing the dataset for machine learning models. The analysis includes data preprocessing, exploratory data analysis (EDA), and visualization of Bitcoin price trends over time.

![Bitcoin Closing Price Over Time](visualizations/closing_price_trend.png) *Example visualization from EDA*

## Key Features
- **Data Preprocessing**: Handling missing values, type conversions, and feature engineering
- **Exploratory Analysis**: Statistical summaries and time series visualization
- **ML Readiness**: Dataset preparation for predictive modeling
- **Modular Structure**: Clear workflow from raw data to processed features

## Dataset
`bitcoin_data.csv` contains hourly Bitcoin metrics from January 2023 with:
- Timestamps
- Price metrics (Open, High, Low, Close)
- Volume data
- Market indicators (Number of trades, Quote asset volume, etc.)

## Installation
1. Clone repository:
```bash
git clone https://github.com/yourusername/bitcoin-ml-analysis.git
cd bitcoin-ml-analysis
```

2. Install requirements:
```bash
pip install -r requirements.txt
```

## Usage
1. Place `bitcoin_data.csv` in project root
2. Run Jupyter notebook:
```bash
jupyter notebook Dataset_2_ML_Models.ipynb
```

### Notebook Sections:
1. Data Loading and Initial Inspection
2. Data Cleaning:
   - Handling missing values
   - Type conversions (datetime features)
   - Feature engineering (`time_diff` calculation)
3. Exploratory Analysis:
   - Statistical summaries
   - Price trend visualization
4. Data Preparation for ML Models

## Dependencies
- Python 3.8+
- pandas
- numpy
- matplotlib
- jupyter

## Contributing
Contributions welcome! Please:
1. Fork the repository
2. Create your feature branch
3. Submit a pull request

## License
[MIT License](LICENSE)


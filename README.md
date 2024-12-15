# Financial News Sentiment and Stock Analysis

This project analyzes financial news headlines to uncover correlations between news sentiment and stock market movements, leveraging data analytics, NLP, and financial indicators.

## Project Structure

```
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows
│       ├── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
│   ├── __init__.py
├── notebooks/
│   ├── __init__.py
│   ├──1_0_financial_news_analysis_EDA.ipynb
│   ├──2_0_stock_price_analysis_TA_Lib_PyNance.ipynb
│   └── README.md
├── tests/
│   ├── __init__.py
├── assets/
│   ├── task-1/
│   ├── task-2/
└── scripts/
    ├── __init__.py
    └── README.md
```

## Objectives

1. **Sentiment Analysis:** Quantify the tone of financial news and associate it with stock symbols.
2. **Correlation Analysis:** Determine the relationship between news sentiment and stock price fluctuations.
3. **Technical Indicators:** Calculate and analyze key financial metrics using libraries like TA-Lib and PyNance.

## Getting Started

### Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <repository-folder>
   ```
3. Set up the Python environment and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Task 1: Sentiment Analysis and Publisher Trends
- Perform EDA on the dataset to extract descriptive statistics.
- Analyze trends and sentiment using NLP techniques.
- Execute the Jupyter notebooks in `notebooks/` for detailed analysis.

### Task 2: Financial Indicators
- Prepare stock price data with columns like Open, High, Low, Close, and Volume.
- Compute technical indicators (e.g., RSI, MACD) using TA-Lib.
- Visualize and interpret results using the scripts in `scripts/`.

## Development Workflow
1. Create a feature branch for each task (e.g., `task-1`, `task-2`).
2. Commit changes with descriptive messages.
3. Merge branches into `main` via pull requests.

## Key Features
- **Sentiment Analysis:** NLP to classify news tone (positive, negative, neutral).
- **Publisher Analysis:** Identify top publishers and their contributions.
- **Technical Indicators:** Compute and visualize financial metrics.

## References
- [TA-Lib Documentation](https://ta-lib.github.io/ta-lib-python/doc_index.html)
- [PyNance Documentation](https://github.com/microsoft/pylance-release)

## Contact
For questions or feedback, please open an issue in the repository.



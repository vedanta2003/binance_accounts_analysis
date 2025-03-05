# Binance Account Performance Analysis

## Project Overview
This project aims to evaluate the performance of various Binance accounts over a 90-day period using historical trade data. The accounts are ranked based on key financial metrics such as ROI, PnL, Sharpe Ratio, MDD, and Win Rate, with a weighted scoring system determining the final rankings.

## Dataset
- **Link to Dataset:** [Binance Trade History Dataset](https://drive.google.com/drive/folders/1ioZ56B5-zTmFuPrT7IihjOVozAgrXxhl)
- The dataset contains detailed trade history for multiple accounts, including attributes like trade timestamps, asset names, trade sides (BUY/SELL), prices, quantities, and realized profits.

## Files Included
- **main.ipynb**: Jupyter Notebook containing the entire analysis pipeline, from data cleaning and metric computation to account ranking.
- **top_20_accounts.csv**: CSV file with detailed metrics and composite scores for the top 20 ranked accounts.
- **analysis_report.txt**: Text report explaining the methodology, key findings, and assumptions made during the analysis.
- **report.pdf**: PDF version of the detailed analysis report.
# Binance Account Performance Analysis

## Key Metrics Calculated
- **ROI (Return on Investment)**
- **PnL (Profit and Loss)**
- **Sharpe Ratio**
- **Maximum Drawdown (MDD)**
- **Win Rate**
- **Total Positions** and **Winning Positions**

## Ranking Methodology
Each account is scored based on normalized values of the calculated metrics, with weights assigned as follows:
- ROI: 30%
- PnL: 25%
- Sharpe Ratio: 20%
- MDD: 15%
- Win Rate: 10%

The accounts are then ranked in descending order of their composite scores.

## How to Run the Project
1. Clone the repository or download the project files.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy ast
   ```
3. Open the `main.ipynb` file in Jupyter Notebook or VS Code.
4. Update the dataset path if needed and run all cells.
5. The results will be saved as `top_20_accounts.csv`, with reports generated in both `.txt` and `.pdf` formats.

## Future Improvements
- Explore additional metrics like volatility or turnover ratio.
- Apply clustering techniques to segment accounts based on trading strategies.
- Build a dashboard for real-time account monitoring.

## Author
**Vedanta Yadav**  
B.Tech CSE (Data Science) | DJSCE (2025)

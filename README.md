# Statistical-Arbitrage-PairsTrading
📈 𝗦𝘁𝗮𝘁𝗶𝘀𝘁𝗶𝗰𝗮𝗹 𝗔𝗿𝗯𝗶𝘁𝗿𝗮𝗴𝗲 𝗦𝘆𝘀𝘁𝗲𝗺 𝘂𝘀𝗶𝗻𝗴 𝗖𝗼𝗶𝗻𝘁𝗲𝗴𝗿𝗮𝘁𝗶𝗼𝗻 + 𝗞𝗮𝗹𝗺𝗮𝗻 𝗙𝗶𝗹𝘁𝗲𝗿
A Machine Learning–Driven Pairs Trading Algorithm with Backtesting, Optimization & Deployment Pipeline


🚀 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄
This project implements a 𝗰𝗼𝗺𝗽𝗹𝗲𝘁𝗲 𝗲𝗻𝗱-𝘁𝗼-𝗲𝗻𝗱 𝘀𝘁𝗮𝘁𝗶𝘀𝘁𝗶𝗰𝗮𝗹 𝗮𝗿𝗯𝗶𝘁𝗿𝗮𝗴𝗲 𝘀𝘆𝘀𝘁𝗲𝗺 based on cointegration analysis and a 𝗱𝘆𝗻𝗮𝗺𝗶𝗰 𝗵𝗲𝗱𝗴𝗲-𝗿𝗮𝘁𝗶𝗼 𝗞𝗮𝗹𝗺𝗮𝗻 𝗙𝗶𝗹𝘁𝗲𝗿 𝗺𝗼𝗱𝗲𝗹.
It automatically:

✔ Collects market data
✔ Finds statistically validated trading pairs
✔ Models spread mean-reversion
✔ Generates trading signals
✔ Performs backtesting across multiple configurations
✔ Optimizes performance metrics
✔ Exports a production-ready configuration for deployment

This framework follows hedge-fund-style quantitative research workflow and can be extended to 𝗹𝗶𝘃𝗲 𝗲𝘅𝗲𝗰𝘂𝘁𝗶𝗼𝗻 𝘂𝘀𝗶𝗻𝗴 𝗔𝗹𝗽𝗮𝗰𝗮, 𝗜𝗻𝘁𝗲𝗿𝗮𝗰𝘁𝗶𝘃𝗲 𝗕𝗿𝗼𝗸𝗲𝗿𝘀, 𝗼𝗿 𝗕𝗶𝗻𝗮𝗻𝗰𝗲 𝗔𝗣𝗜.


🏗️ 𝗦𝘆𝘀𝘁𝗲𝗺 𝗔𝗿𝗰𝗵𝗶𝘁𝗲𝗰𝘁𝘂𝗿𝗲
┌───────────────────────────┐
│  Phase 1: Data Pipeline   │
│  (Download + Cleaning)    │
└───────────────┬───────────┘
                ↓
┌───────────────────────────┐
│ Phase 2: Pair Discovery   │
│ (Correlation + Coint Test)│
└───────────────┬───────────┘
                ↓
┌───────────────────────────┐
│ Phase 3: Modeling & Rules │
│ (Kalman Filter Signals)   │
└───────────────┬───────────┘
                ↓
┌───────────────────────────┐
│ Phase 4: Backtesting      │
│ (Performance Evaluation)  │
└───────────────┬───────────┘
                ↓
┌───────────────────────────┐
│ Phase 5: Optimization     │
│ (Grid Search + Best Model)│
└───────────────┬───────────┘
                ↓
┌───────────────────────────┐
│ Phase 6: Deployment Ready │
│ (JSON Config Export)      │
└───────────────────────────┘


📚 𝗙𝗲𝗮𝘁𝘂𝗿𝗲𝘀
              𝗙𝗲𝗮𝘁𝘂𝗿𝗲 	                                  𝗦𝘁𝗮𝘁𝘂𝘀             	                     𝗗𝗲𝘁𝗮𝗶𝗹𝘀
   Yahoo Finance automated data ingestion	                 ✅	                              5-year historic data
   Cointegration testing (Engle-Granger)	                 ✅	                      Filters statistically dependent pairs
   Kalman Filter hedge ratio                            	 ✅	                            Adaptive spread modeling
   Multi-pair parallel trading	                           ✅	                        Supports diversified portfolios
   Backtesting engine (Backtrader)	                       ✅                        	Equity curve, returns, trade logs
   Hyperparameter optimization	                           ✅                              	70+ config evaluation
   Production configuration export	                       ✅                            	JSON ready for deployment
   Live trading (coming soon)	                             🔜                              Alpaca / IBKR execution


🧠 𝗠𝗼𝗱𝗲𝗹𝗶𝗻𝗴 𝗧𝗲𝗰𝗵𝗻𝗶𝗾𝘂𝗲𝘀 𝗨𝘀𝗲𝗱

•  𝗣𝗲𝗮𝗿𝘀𝗼𝗻 𝗖𝗼𝗿𝗿𝗲𝗹𝗮𝘁𝗶𝗼𝗻 𝗙𝗶𝗹𝘁𝗲𝗿𝗶𝗻𝗴
•  𝗘𝗻𝗴𝗹𝗲-𝗚𝗿𝗮𝗻𝗴𝗲𝗿 𝗖𝗼𝗶𝗻𝘁𝗲𝗴𝗿𝗮𝘁𝗶𝗼𝗻 𝗧𝗲𝘀𝘁
•  𝗢𝗿𝗱𝗶𝗻𝗮𝗿𝘆 𝗟𝗲𝗮𝘀𝘁 𝗦𝗾𝘂𝗮𝗿𝗲𝘀 𝗥𝗲𝗴𝗿𝗲𝘀𝘀𝗶𝗼𝗻 (𝗢𝗟𝗦) 𝗛𝗲𝗱𝗴𝗲 𝗥𝗮𝘁𝗶𝗼
•  𝗞𝗮𝗹𝗺𝗮𝗻 𝗙𝗶𝗹𝘁𝗲𝗿 𝗳𝗼𝗿 𝗗𝘆𝗻𝗮𝗺𝗶𝗰 𝗛𝗲𝗱𝗴𝗲 𝗥𝗮𝘁𝗶𝗼 𝗘𝘀𝘁𝗶𝗺𝗮𝘁𝗶𝗼𝗻
•  𝗭-𝗦𝗰𝗼𝗿𝗲 𝗠𝗲𝗮𝗻 𝗥𝗲𝘃𝗲𝗿𝘀𝗶𝗼𝗻 𝗟𝗼𝗴𝗶𝗰
•  𝗥𝗶𝘀𝗸-𝗖𝗼𝗻𝘁𝗿𝗼𝗹𝗹𝗲𝗱 𝗘𝗻𝘁𝗿𝘆/𝗘𝘅𝗶𝘁 𝘄𝗶𝘁𝗵 𝗦𝘁𝗼𝗽 𝗟𝗶𝗺𝗶𝘁𝘀


📂 𝗥𝗲𝗽𝗼𝘀𝗶𝘁𝗼𝗿𝘆 𝗦𝘁𝗿𝘂𝗰𝘁𝘂𝗿𝗲
stat_arb_pairs/
│
├── data/
│   ├── raw/                     # Raw market data (CSV)
│   ├── cleaned/                 # Processed aligned price matrix
│   └── pairs/                   # Correlated + cointegrated pairs
│
├── reports/
│   ├── portfolio_equity_curve.csv    # Backtest portfolio curve
│   └── kalman_param_optimization_results.csv
│
├── config/
│   └── kalman_prod_config.json    # Best performing strategy settings
│
├── notebooks/
│   ├── 01_stat_arb_kalman_backtest.ipynb
│   └── 02_kalman_optimization.ipynb
│
├── README.md
└── requirements.txt


📊 𝗦𝗮𝗺𝗽𝗹𝗲 𝗣𝗲𝗿𝗳𝗼𝗿𝗺𝗮𝗻𝗰𝗲 𝗢𝘂𝘁𝗽𝘂𝘁

        𝗠𝗲𝘁𝗿𝗶𝗰	                                                𝗥𝗲𝘀𝘂𝗹𝘁
   Final Portfolio Value	                          varies based on optimization
   Best Sharpe Ratio found	                           ↑ based on grid search
   Max Drawdown	                                        reported per config
   Total Trades Executed	                           logged in optimizer results


⚙️ 𝗧𝗲𝗰𝗵 𝗦𝘁𝗮𝗰k

        𝗖𝗮𝘁𝗲𝗴𝗼𝗿𝘆	                                             𝗧𝗼𝗼𝗹𝘀
         Data	                                    Yahoo Finance (yfinance), Pandas, NumPy
        Modeling	                                    Statsmodels, Kalman Filter
Backtesting & Optimization	                                 Backtrader
     Visualization	                                         Matplotlib
    Deployment Ready	                                       JSON config


🧪 𝗥𝘂𝗻 𝗪𝗼𝗿𝗸𝗳𝗹𝗼𝘄

1️⃣ 𝗘𝘅𝗽𝗹𝗼𝗿𝗲 𝗱𝗮𝘁𝗮 + 𝗯𝘂𝗶𝗹𝗱 𝗺𝗼𝗱𝗲𝗹 𝗰𝗮𝗻𝗱𝗶𝗱𝗮𝘁𝗲𝘀
  notebooks/01_Statistical_Arbitrage_v1.ipynb

2️⃣ 𝗥𝘂𝗻 𝗼𝗽𝘁𝗶𝗺𝗶𝘇𝗮𝘁𝗶𝗼𝗻 𝘁𝗼 𝗳𝗶𝗻𝗱 𝗯𝗲𝘀𝘁 𝗰𝗼𝗻𝗳𝗶𝗴𝘂𝗿𝗮𝘁𝗶𝗼𝗻
  notebooks/02_kalman_optimization.ipynb

3️⃣ 𝗨𝘀𝗲 𝗴𝗲𝗻𝗲𝗿𝗮𝘁𝗲𝗱 𝗰𝗼𝗻𝗳𝗶𝗴 𝗳𝗼𝗿 𝗹𝗶𝘃𝗲 𝗱𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁
  config/kalman_prod_config.json


🔥 𝗙𝘂𝘁𝘂𝗿𝗲 𝗘𝗻𝗵𝗮𝗻𝗰𝗲𝗺𝗲𝗻𝘁𝘀

🔹 Live trading via 𝗔𝗹𝗽𝗮𝗰𝗮 𝗔𝗣𝗜
🔹 Cloud execution (AWS Lambda / GCP)
🔹 ML-based regime detection model
🔹 Walk-forward/backward testing
🔹 Feature-rich Streamlit dashboard


🧑‍💻 𝗔𝘂𝘁𝗵𝗼𝗿

𝗔𝗯𝗵𝗶𝘀𝗵𝗲𝗸 𝗞𝘂𝗺𝗮𝗿 𝗚𝘂𝗽𝘁𝗮
AI/ML Engineer • Quant Research Enthusiast
📍 India
🔗 LinkedIn: https://www.linkedin.com/in/abhishek-kumar-gupta-55488a27a/
🔗 GitHub: https://github.com/Abhishek-NR01/Statistical-Arbitrage-PairsTrading


⭐ 𝗖𝗼𝗻𝘁𝗿𝗶𝗯𝘂𝘁𝗲

Pull requests, suggestions, and improvements are welcome!


📜 𝗗𝗶𝘀𝗰𝗹𝗮𝗶𝗺𝗲𝗿

This project is for 𝗿𝗲𝘀𝗲𝗮𝗿𝗰𝗵 𝗮𝗻𝗱 𝗲𝗱𝘂𝗰𝗮𝘁𝗶𝗼𝗻𝗮𝗹 𝗽𝘂𝗿𝗽𝗼𝘀𝗲𝘀 𝗼𝗻𝗹𝘆.
It does 𝗻𝗼𝘁 constitute investment advice, and real-world trading carries financial risk.

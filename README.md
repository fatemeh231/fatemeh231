Hi, I'm Fatemeh Hosseininasab
Quant-ML Researcher | Data Scientist | Toobit Project Ambassador

📍 Tehran, Iran | Turkish residency pending (sanctions-bypassable via Turkish VPS & banking)🎓 BSc Computer Science, University of Science and Culture (expected 2027)💼 Project Ambassador & Market Analyst, Toobit (Persian market)📄 Quant thesis on Kalshi (Fed benchmark replication): under submission
🔬 Featured Research
Kalshi CPI Calibration Thesis ⭐

Replication and extension of Krause (2026a) on Kalshi KXCPIYOY calibration. Tests whether prediction markets are uniformly efficient and whether calibration-adjusted ML can exploit the bias.

Method: Five-script Python pipeline pulls historical markets + trade-level data from the Kalshi API, aggregates to daily last-trades, trains three classifiers (Logistic Regression, Random Forest, Gradient Boosting) with Platt scaling, and runs a walk-forward trading backtest.

Key Results:

    🎯 Brier score 0.0602 vs published benchmark 0.0840 — 28% tighter calibration
    📉 Systematic bias −0.0263 concentrated in 0.10–0.50 price range (favorite-longshot pattern)
    💰 Walk-forward backtest: 314 trades, 75.48% win rate, +$3.68 PnL, Sharpe 0.71
    🧩 Identified the Brier-versus-PnL paradox: a model marginally behind on Brier can still trade profitably when filtered through an edge-based rule
    ⚠️ Honest limitations: N=21 distinct CPI events (wide CI), no live order-book slippage, fixed 5-cent edge threshold

Findings consistent with Krause (2026a), Diercks, Katz & Wright (2026, Fed Board), and Burgi, Deng & Whelan (2025, CESifo).

📄 Thesis manuscript (English & Persian) under submission.
🧠 About Me

I build machine learning systems that trade macroeconomic events. My research focuses on prediction market efficiency, calibration, and event-driven trading strategies on Kalshi and Polymarket.

Beyond research, I work as a Project Ambassador & Market Analyst at Toobit (global crypto exchange) for the Persian market, where I use Python to automate reporting and analyze competitor activity across exchanges.

I'm currently learning C++ with a focus on market microstructure and low-latency execution, with the long-term goal of building production algorithmic trading systems.
📊 Selected Projects
Quant & Trading
Project	Description	Tech Stack	Link
Kalshi CPI Calibration Thesis	Fed benchmark replication + ML trading backtest	Python, scikit-learn, Kalshi API	🔗
FOMC Predictor	Hybrid ML + prediction markets for Fed rate decisions. 95.45% accuracy on 2024–2026 test set	Python, scikit-learn, FRED, Kalshi, Polymarket	🔗
Quant-Momentum-Sniper	Momentum engine for 5m crypto with ATR volatility gate, EMA ribbon, ML feature selection	Python, Pine Script	🔗
NBA Prediction Trading Bot	Ensemble ML (XGBoost + RF) with live signals and Kelly sizing on Polymarket	Python, XGBoost, Polymarket	🔗
NFL Prediction Trading Bot	NFL game prediction + Polymarket trading bot with Kelly position sizing	Python, XGBoost, Polymarket	🔗
Trading Journal	BTCUSDT ETL pipeline with performance metrics and emotional analysis	Python, Jupyter	🔗
Data Engineering & ML at Scale
Project	Description	Tech Stack	Link
Healthcare Claims Analyzer	ETL on 18M+ rows, denial prediction, Power BI dashboard	Python, scikit-learn, Power BI	🔗
IoT Predictive Maintenance	LSTM failure prediction 48 hours ahead, 99.45% accuracy	Python, TensorFlow, Power BI	🔗
AI Data Cleaning Studio	Streamlit app for PII detection, auto-profiling, cleaning at scale	Python, Streamlit, Presidio	🔗
CFO Cockpit	Prophet-based forecasting for 46 US public companies from SEC EDGAR	Python, Prophet, Streamlit	🔗
NLP & Web Scraping
Project	Description	Tech Stack	Link
Brand Intelligence Engine	Multi-source reputation scraper (Trustpilot, Google Play, Telegram) with VADER sentiment	Python, Selenium, VADER	🔗
E-commerce Price Monitor	Auto price tracking across Best Buy, Amazon, AliExpress	Python, Selenium, BeautifulSoup	🔗
🔧 Tech Stack
Languages

PythonSQLC++ (learning — HFT focus)
ML & Quant

scikit-learnXGBoostTensorFlowPyTorchStatsmodelsProphet
Data

PandasNumPyParquetPostgreSQL
Deployment & BI

StreamlitFastAPIDockerPower BI
Market Data Sources

KalshiPolymarketFREDSEC EDGAR
🚀 Currently Working On

    📤 Submitting the Kalshi thesis to SSRN (working paper) and an ISC-indexed Persian journal
    🔧 Implementing block bootstrap by event date for robust Sharpe confidence intervals
    ⚡ Learning C++ with a focus on market microstructure and low-latency execution

🤝 What I'm Looking For

    🔬 Research collaborations on prediction market efficiency, macro forecasting, and event-driven trading
    👨‍🏫 Mentors in quantitative finance (especially anyone with Kalshi / Polymarket / CME experience)
    💼 AI annotation / data labeling contracts (Mercor, Toloka, Scale AI) for steady USD cash flow
    🐍 Freelance contracts in Python ML / ETL / dashboarding — sniper mode, only high-value, escrow-funded

📬 Connect With Me

LinkedInX (Twitter)GitHubEmail

"One finished paper beats thirty-five unfinished projects."

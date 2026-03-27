# Portfolio

## About Me

My work sits at the intersection of financial systems engineering, applied econometrics, and discretionary trading. On the systems side, I design and build proprietary software infrastructure in C++ (ACSIL) and Python — including a multi-component execution and risk-control architecture that bridges two trading platforms, enforces compliance rules across sessions and restarts, and provides real-time pre-trade validation. This work is informed by active discretionary trading in US Index Futures using order-flow and market-structure analysis, where the infrastructure I build is also what I trade through.

On the research side, I have co-authored empirical work on the causal dynamics between oil prices and macroeconomic uncertainty measures, using advanced econometric frameworks including ARDL bounds testing, VAR-based Granger causality, and long-run augmented VAR. The paper has been accepted for publication in the International Journal of Energy Economics and Policy (IJEEP) and was presented as a Strong Accept at the ERPBSS 2026 international conference proceeding at Middlesex University in Dubai.

Prior to this, I worked as a Crude Oil Market Research Analyst at Vici Energy in Dubai, covering crude and product flows across the Middle East, China, and Latin America — producing pricing reports, sanctions monitoring briefs, and benchmarking analysis for senior management.

My CV, completed projects, academic recommendation letters, and full certifications list are available below.

## Technical Skills

- Please refer to 'On-going certifications' section for technical skills I am currently learning/developing. 

### Languages & Development Tools

- Python, C++ (ACSIL), Git, GitHub, CLI, LaTeX, STATA, EViews, Excel, Power BI

### Platforms & Software

- Sierra Chart (ACSIL study development), MetaTrader 5 (MT5), Refinitiv Eikon (LSEG), S&P Global (Platts, Capital IQ), Kpler

### Libraries & Frameworks

- pandas, NumPy, matplotlib, plotly, scipy, statsmodels, scikit-learn, streamlit, seaborn, OpenPyXL, Selenium

### Econometrics & Quantitative Modelling

- Time Series Modelling (VAR, VECM, ARDL, ARIMA, GARCH), Cointegration & Bounds Testing (ARDL bounds test)
- Causality Analysis (Toda-Yamamoto, VAR-based Granger causality, Impulse Response, FEVD), Unit Root Testing (ADF, Phillips-Perron, KPSS, Zivot-Andrews structural break), Stability Diagnostics (CUSUM) - Statistical Validation (t-tests, chi-square, ANOVA, Tukey HSD), Probability Distributions (Normal, Binomial, Poisson), Data Pre-processing, EDA, Feature Engineering

### Machine Learning

- Supervised: Linear & Logistic Regression, K-Nearest Neighbours, SVM, Decision Trees, Random Forest
- Unsupervised: K-Means Clustering
- Applied: ML for Trading (Classification, Regression, Mean Reversion, Event-Driven Strategies)
  
### Trading & Market Structure

- Auction Market Theory (AMT), Market Profile / TPO Composites, Volume Profile (HVN, LVN, POC)
- Order Flow Analysis (Cumulative Delta, Footprint Charts, DOM, VWAP) 
    
## Publications

**Title:** The Causality between Oil Price, Policy & Financial Markets Uncertainty in the United States | **Authors:** Saimanish Prabhakar & Dr. Athanasia Kalaitzi | **Journal:** International Journal of Energy Economics and Policy (IJEEP) :- SJR: Q2, ABDC: B | **Status:** Accepted for publication (2025–2026)

- Examines the causal dynamics between WTI oil prices and uncertainty measures — economic policy uncertainty (EPU) and financial market uncertainty (VIX) — across supply, demand, inventory, and exchange rate channels using ARDL bounds testing, Toda-Yamamoto causality, and a full unit root battery (ADF, PP, KPSS, Zivot-Andrews) over a monthly sample spanning February 1990 to September 2024.
- Identifies recursive transmission loops where sustained demand-side shocks induce long-run supply stress, impacting oil prices via economic policy uncertainty as both a conduit and recipient of market dynamics — with implications for hedging strategy and policy design.
- Conference Presentation: Presented as 'Strong Accept' at the Eighth International Conference on Emerging Research Paradigms in Business and Social Sciences (ERPBSS 2026) under the 'Geopolitics, Trade, and Economics' track.

## Completed Projects

Click the project title to visit the interactive dashboard where available.

Proprietary Trading Risk & Execution Engines | Technologies: C++ (ACSIL), Python (Streamlit) | Jun 2025 – Present

- Engineered a C++-based execution engine that translates analysis decisions into compliant order execution across two platforms, enforcing position-aware order semantics, dynamic unit sizing, and a state-gated arm-fire workflow — operating as a stateless enforcer that publishes trade events to disk and defers all account-level risk decisions to an external authority.
- Built a Python risk dashboard that automates cross-platform exposure translation, validates trades against a multi-tiered drawdown defence system, and writes sizing outputs consumed by the execution engine as an IPC bridge; paired with a standalone governor daemon that reconstructs account risk state from the execution engine's trade-event stream on every cycle, computes cooldown and hard-lock decisions, and publishes verdicts atomically to disk — creating a crash-resilient, restart-safe enforcement layer that neither the execution engine nor the dashboard can bypass.

*[Options Pricing and Greeks Analysis](https://options-pricing-and-greeks.streamlit.app/)* | Libraries: numpy, pandas, matplotlib, streamlit, plotly, scipy | Jan – Feb 2025

- Developed an options pricing tool using Black-Scholes and Monte Carlo methods, comparing options price sensitivity to volatility, time to expiration, and strike price, with visualisations of Monte Carlo price paths and distributions.
- Implemented Greek analysis for both methods and created multi-dimensional sensitivity plots for deeper insights into option pricing dynamics.

*[Options Strategy Payoff Calculator](https://options-strategies-payoff-calculator.streamlit.app/)* | Libraries: numpy, pandas, matplotlib, streamlit | Apr – May 2024

- Engineered an interactive options strategy profitability calculator enabling analysis of strategies including Strap, Bull Call Spread, Long Butterfly, and more, with dynamic visualisation of net-payoff tables and break-even points for risk-reward assessment.

## Books 

Books read in 2026 so far — the intellectual neighbourhoods I tend to wander through when not building systems or running models.

- Mind Over Markets — James Dalton, Robert Dalton, Eric Jones
- Markets and Momentum — James Dalton, Eric Jones, Robert Dalton
- Thinking in Bets — Annie Duke
- Fooled by Randomness — Nassim Nicholas Taleb
- Skin in the Game — Nassim Nicholas Taleb
- Alchemy — Rory Sutherland
- Meditations - Marcus Aurelius (Gregory Hays translation)

## On-going Certifications

### Career Path (50-150 hours -> with exams)
- Machine Learning / AI Engineer
- Data Scientist: Machine Learning Specialist
- Data Scientist: NLP Specialist
- Data Scientist: Inference Specialist
- Data Scientist: Analytics
- Data Engineer
- Fullstack Engineer

### Skill Path (>20 hours)
- Analyze Data with SQL
- Analyze Data with R
- Feature Engineering
- Build a Machine Learning Model
- Intermediate Machine Learning
- Build Deep Learning Models with TensorFlow

### Technical Courses (1-20 hours)
- Learn SQL
- Learn MongoDB
- kdb+/q Developer – Level 1
- kdb+/q Developer – Level 2
- kdb+/q Developer – Level 3
- Learn R
- Generative AI Models: Generating Data Using Generative Adversarial Networks (GANs)
- Intro to PyTorch and Neural Networks
- Creating AI Applications using Retrieval-Augmented Generation (RAG)
- Generative AI Models: Getting Started with Autoencoders
- Generative AI Models: Generating Data Using Variational Autoencoders
- Learn Image Classification with PyTorch

### Algorithm Trading Courses (1-20 hours)
- Options Trading Strategies in Python: Advanced
- Mean Reversion Strategies in Python
- Backtesting Trading Strategies
- Event Driven Trading Strategies
- Financial Time Series Analysis for Trading
- Futures: Concepts & Strategies
- Systematic Options Trading
- Options Volatility Trading: Concepts and Strategies
- Data and Feature Engineering for Trading
- Decision Trees in Trading
- Natural Language Processing in Trading
- Unsupervised Learning in Trading
- Neural Networks in Trading
- Deep Reinforcement Learning in Trading
- Machine Learning for Options Trading
- Quantitative Portfolio Management
- Position sizing in Trading
- Factor Investing: Concepts and Strategies
- Portfolio Management using Machine Learning: Hierarchal Risk Parity
- AI for Portfolio Management: LSTM Networks
- News Sentiment Trading Strategies
- Momentum Trading Strategies
- Trading Alphas: Mining, Optimisation, and System Design
- Trading in Milliseconds: MFT Strategies and Setup

## Completed Certifications

### Skill Path (>20 hours)
- [Data and Programming Foundations for AI](https://drive.google.com/file/d/1oj9CAMIQdI4yscKFjlKAIfzZs2hQwFOw/view)
- [Fundamental Math for Data Science](https://drive.google.com/file/d/1MfY2KwY0F5Lj3GjK3dcDn9CP70pcsw70/view)
- [Master Statistics with Python](https://drive.google.com/file/d/1wKf1fwMLKhK_0MaekNK7KMYLPef51jkL/view)

### Technical Courses (1-20 hours)
- [Learn Python 3](https://drive.google.com/file/d/1IwrqFQyFTT6a-eojb3t7Vxu-NPhmudt6/view)
- [Learn the Command Line](https://drive.google.com/file/d/1VCr3wLQK3TERuaD0F9AsovV_Slx-8h0-/view)
- [Learn Git and GitHub](https://drive.google.com/file/d/1AG-0fvDE_Kiw5KYfnPOLuD-uzvXW75uW/view)
- [Level 4 Diploma in Investment Bank Sales and Trading](https://drive.google.com/file/d/15y0FRYc9TgHOPf-rY5byp9Osy4ThizsI/view)
- [Finance Accelerator Simulation Participant in Partnership with Morgan Stanley](https://drive.google.com/file/d/12V9umlueBUbdRMxqRhGapCuRaopLbh42/view)
- [Getting Started with Refinitiv Eikon](https://drive.google.com/file/d/1LJKijKQon6I1_wRfWWCVWzzTdq7dHhxB/view)

### Algorithm Trading Courses (1-20 hours)
- [Introduction to Machine Learning for Trading](https://drive.google.com/file/d/1W1lw6P2NTGFzoXSfgJ7PLH88N5HxTxyl/view?usp=sharing)
- [Trading with Machine Learning: Classification and SVM](https://drive.google.com/file/d/15busdUigDdl4pOPKI4ciwHLOcjI5AS-q/view?usp=sharing)
- [Trading with Machine Learning: Regression](https://drive.google.com/file/d/1d1u7Tzcb7qI2k3sObXuFd8UIWwwcOgTV/view?usp=sharing)
- [Python for Machine Learning in Finance](https://drive.google.com/file/d/1wlQaQelGLgg9K4arVGU56R3tApLfsn-G/view?usp=sharing)
- [Python for Trading Basic](https://drive.google.com/file/d/1HGkQ0NN8tkZgIyPky6bokErfuLlWffqd/view)
- [Python for Trading](https://drive.google.com/file/d/1nrRoRQseUkMdGn4EHvAAHzSFziYUuTCe/view?usp=sharing)
- [Getting Started with Algorithmic Trading](https://drive.google.com/file/d/1bAtMiv2gpkdE3_iB2iLAGgwkdgMNbRoy/view)
- [Statistical Arbitrage Trading](https://drive.google.com/file/d/1ydhX7VPzxT0s8OyRIvTvJNpSXloqcpxK/view)
- [Getting Market Data: Stocks, Crypto, News & Fundamentals](https://drive.google.com/file/d/1Bim3k1hDxgzojF7WKaQSl7CAg1JC5KGX/view)
- [Quantitative Trading Strategies and Models](https://drive.google.com/file/d/17xaN2ekH25409MUXWnJY95eM2_a1vHZb/view)
- [Options Trading Strategies in Python: Basic](https://drive.google.com/file/d/1fvrO68KF8JiZm6nxbZAILam9eTaTbBOt/view)
- [Options Trading Strategies in Python: Intermediate](https://drive.google.com/file/d/1GlaSQdm9Mx5kB3iy4mrxiW_xyDcl2pBF/view)
- [Trading using Options Sentiment Indicators](https://drive.google.com/file/d/1Z7CbOq1Z745gcbFhoZC6cOZoqneZVNZ0/view)
- [Value Strategy in Forex](https://drive.google.com/file/d/1xXjWes0XWV_vgCCZRiEe3o8efUY5iUS7/view)
- [Forex Trading using Python: Basic](https://drive.google.com/file/d/103wivM3Fgj1CJkyBOivTgKyLTmYGN6gz/view)

### Finance/Industry Experience Courses (1-10 hours)
- [JP Morgan: Investment Banking Virtual Experience Program Participant](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/JPMorgan%20Chase/YD2kY95RQxQtXxFTS_JPMorgan%20Chase_ok6joc3aPXoRPwogq_1651859836209_completion_certificate.pdf)
- [JPMorgan Chase: Commercial Banking Virtual Experience Program Participant](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/JPMorgan%20Chase/LBJRY9AanBmxGpPTc_JPMorgan%20Chase_ok6joc3aPXoRPwogq_1651768473964_completion_certificate.pdf)
- [ACCA: Sustainability in Banking Virtual Experience Program Participant](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/ACCA%20and%20CIMB%20Group/uY9Mkm9Emf8frDPeb_ACCA%20and%20CIMB%20Group_ok6joc3aPXoRPwogq_1662979263310_completion_certificate.pdf)
- [JPMorgan Chase: Markets (Sales & Trading) Virtual Experience Program Participant](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/JPMorgan%20Chase/TF9ouPQomo5YcwRGR_JPMorgan%20Chase_ok6joc3aPXoRPwogq_1662214731522_completion_certificate.pdf)
- [Fidelity International: Investment Management Virtual Experience Program Participant](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Fidelity%20International/hgCWHF8riBbyFjPfd_Fidelity%20International_ok6joc3aPXoRPwogq_1662583448364_completion_certificate.pdf)
- [JP Morgan: Global Private Bank Virtual Experience Program](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/JPMorgan%20Chase/57t6vcuqvMGsK6PA9_JPMorgan%20Chase_ok6joc3aPXoRPwogq_1662320521875_completion_certificate.pdf)
- [Goldman Sachs: Excel Skills for Business Virtual Experience Program Participant](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Goldman%20Sachs/eLeZHcwX7CqLhhps7_Goldman%20Sachs_ok6joc3aPXoRPwogq_1662678264929_completion_certificate.pdf)
- [JPMorgan Chase: Asset Management Virtual Experience Program Participant](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/JPMorgan%20Chase/X7JHqavmZAmbDW6Fq_JPMorgan%20Chase_ok6joc3aPXoRPwogq_1662490891250_completion_certificate.pdf)
- [HSBC: Global Banking & Markets Virtual Experience](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/HSBC/cEn98BQrAXAHRqqQB_HSBC_ok6joc3aPXoRPwogq_1675127120949_completion_certificate.pdf)
- [Bank of America: Investment Banking Virtual Experience Program Participant](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Bank%20of%20America/Hi8MJQE5T3MeTRWQR_Bank%20of%20America_ok6joc3aPXoRPwogq_1683632246957_completion_certificate.pdf)
- [Code and Standards Certifications on the CFA Institute Code of Ethics (Total of 22)](https://drive.google.com/drive/folders/1pwN41Y0h77lnaONy9-Fc0PnqI3OaF3_C)

## CV 

<iframe src="assets/Saimanish_Prabhakar_CV.pdf" width="600" height="850" style="border: none;"></iframe>
<br><br>
## Academic Recommendation Letters

<iframe src="assets/SP - Senior Lecturer - Quantitative Finance and Economics - Reference Letter.pdf" width="600" height="850" style="border: none;"></iframe>
<br><br>
<iframe src="assets/SP - Dissertation Supervisor and Emeritus Professor of Economics - Reference Letter.pdf" width="600" height="850" style="border: none;"></iframe>
<br><br>

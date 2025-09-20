# Portfolio Simulation Project  

![Status](https://img.shields.io/badge/Status-Ongoing-blue)  
![Made with](https://img.shields.io/badge/Made%20with-Excel%20%26%20Python-green)  
![Focus](https://img.shields.io/badge/Focus-Portfolio%20Management-orange)  

**Current Return:**

This project simulates a **12-month, ₹10 lakh Indian equity portfolio** of 9 holdings diversified across sectors, plus a Gold ETF for diversification. It is designed to mirror **real-world portfolio management practices** with weekly tracking, monthly rebalancing, benchmarking, and behavioral finance insights. The repository is structured as a **professional portfolio management case study** intended to showcase discipline, financial modeling, and behavioral analysis — relevant for recruiters, fintechs, and B-school evaluators.  

## Portfolio Composition  
- **Large-cap / Blue chips**: Reliance Industries, HDFC Bank  
- **Mid-cap / Growth**: Tata Motors, Dixon Technologies, Larsen & Toubro (L&T)  
- **Small-cap / High risk**: Affle India, MapmyIndia (CE Info Systems), Deepak Nitrite  
- **Pharma**: Divi’s Laboratories  
- **Diversifier**: GoldBees (Gold ETF)  

## Repository Structure  
- **Portfolio_Weekly_Prices.xlsx** → Master price sheet with weekly closing prices, holdings, and trade log.
- **Portfolio_Allocation.xlsx** → Initial allocation of stocks, in the folder Week_1.  
- **Portfolio_Tracker.xlsx** → Main analysis file tracking allocations, returns, equity curve, sector exposure, top performers, and detailed analysis tabs.  
- **Shadow_Portfolio.xlsx** → Passive benchmark portfolio (frozen Week 1 allocation) used for alpha comparison.  
- **logs/** → Weekly markdown commentary (Week_2 … Week_52) with performance notes, market events, and rebalance reasoning.  
- **summary/** → Final charts, statistics, regret heatmaps, and behavioral learnings.  
- **scripts/** → Python automation tools (e.g., price_fetcher.py for automated data updates).  
- **Week_1/** → Initial setup (stock list, allocation, rationale, conviction scores).  

## Key Features  
- Weekly tracking and monthly rebalancing discipline  
- Active vs passive alpha comparison (vs Shadow Portfolio, Nifty 50, and Sensex)  
- Rebalance regret tracker (track performance of exited stocks)  
- Behavioral audit (impulsive vs rational trades, bias tracking)  
- Stress testing with market crash or sector shock scenarios  
- Sector and thematic contribution breakdowns (AI, EV, infra, etc.)  
- Time-underwater analysis (weeks a stock stayed below buy price)  
- Conviction scoring (pre-trade vs post-trade outcomes)  
- Peter Lynch 6-point strategy evaluation for stock quality  
- Simplified tax impact estimation (STCG vs LTCG)  

## Final Outcome  
At the end of 12 months, this repository will contain:  
- Fully linked Excel models of portfolio performance  
- Weekly logs capturing reasoning, trades, and reflections  
- Shadow vs active portfolio comparisons proving/disproving alpha generation  
- Equity curves, regret heatmaps, and sector evolution charts  
- Behavioral finance insights and lessons learned  
- Mini stock pitches with thesis, risks, and valuation metrics  
- A comprehensive README tying it together into a professional case study  

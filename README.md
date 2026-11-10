# Portfolio Diversification using a Correlation Matrix

How low-correlation assets reduce portfolio risk, using **60 monthly total returns (Nov 2021 – Oct 2026)** for Apple, Microsoft, JPMorgan Chase, Coca-Cola, ExxonMobil and gold (GLD).

## Build
- Annualised return, volatility and **covariance matrix**
- **Correlation matrix** heatmap (CORREL) and all 15 pairs ranked
- Portfolio volatility = √(wᵀΣw) for six sample portfolios
- **Diversification curve**: risk as lower-correlated assets are added

## Key findings
- 100% Apple: **24.7%** volatility
- Apple + Microsoft (correlation 0.51): volatility only falls to 22.2%
- Apple + Gold (correlation 0.05): volatility falls to **15.5%** with a higher Sharpe ratio
- Low-correlation mix (AAPL, JPM, KO, XOM, GLD): **12.3%** volatility and the best Sharpe ratio (1.28)

## Files
- `Correlation_Matrix_Portfolio_Diversification.xlsx`
- `Correlation_Matrix_Project_Report.pdf`

## Tools
MS Excel (CORREL, COVARIANCE.S, SUMPRODUCT, MMULT, INDEX/MATCH, charts)

## Note
Source: monthly total returns from chartrow.com. For learning, not investment advice.

## Author
**Aditya Kushwaha** · [LinkedIn](https://www.linkedin.com/in/aditya-kushwaha16)

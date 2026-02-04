## **Quantitative Risk Assessment of FAANG Equities using Treynor Ratio and Value at Risk (VaR)**

### **Project Overview**

This project involved developing a comprehensive risk management framework to evaluate the performance of a high-growth technology portfolio consisting of Meta (FB), Amazon (AMZN), Apple (AAPL), Netflix (NFLX), and Alphabet (GOOG). The analysis addressed the challenge of quantifying risk-adjusted returns and potential downside loss using historical monthly performance data. Key results included the calculation of a portfolio Treynor Ratio of 1.67% and a 99% Value at Risk of -32.86% for the highest-volatility asset (NFLX).

### **Business Understanding**

The primary stakeholders for this analysis are individual investors or portfolio managers seeking to optimize capital allocation within the technology sector. The core business problem involves balancing the pursuit of high returns with a disciplined understanding of systematic risk and potential catastrophic loss. Effective risk management is critical in investment banking and equity research to ensure that portfolio exposure aligns with an organization's risk tolerance.

### **Data Understanding**

The analysis utilized a dataset of historical monthly returns for five major technology stocks and the S&P 500 (SPX) as a market benchmark.

* **Data Points**: The dataset included monthly returns, standard deviation (STDEV), and Beta coefficients for each asset.
* **Asset Metrics**:
  * **Monthly Returns**: Ranged from 1.46% (GOOG) to 3.32% (NFLX).
  * **Standard Deviation**: Market volatility (SPX) was recorded at 3.78%, while individual assets showed higher volatility, peaking at 12.06% for NFLX.
* **Limitations**: The analysis relies on historical performance as a proxy for future risk; however, historical data may not account for "Black Swan" events or sudden shifts in market regime.

### **Modeling and Evaluation**

The project utilized two primary quantitative models to evaluate investment quality and risk exposure:

* **Treynor Ratio**: Used to measure risk-adjusted return based on systematic risk (Beta). NFLX demonstrated the highest Treynor Ratio at 2.10%, while GOOG was the lowest at 1.06%.
* **Value at Risk (VaR)**: Calculated at both 95% and 99% confidence levels to estimate the maximum expected loss over a specific timeframe.
* **Evaluation Metrics**:
* **Beta**: Used to quantify sensitivity to market movements; AMZN showed the highest sensitivity at 1.34.
* **99% VaR**: Highlighted significant tail risk, with potential losses reaching -32.86% for NFLX and -23.41% for FB.

### **Conclusion**

Based on the quantitative analysis, the FAANG portfolio offers a competitive risk-to-reward profile with an aggregate Treynor Ratio of 1.67%. However, the high Value at Risk—particularly for Netflix—suggests that investors must be prepared for significant drawdowns during market corrections. I recommend diversifying the portfolio with assets showing lower Beta to reduce the aggregate 99% VaR.

**Future Steps:**

* **Stress Testing**: Expand the model to include Monte Carlo simulations to project portfolio performance under various macroeconomic scenarios.
* **Correlation Analysis**: Calculate a correlation matrix between these assets to determine the actual diversification benefits within the FAANG group.

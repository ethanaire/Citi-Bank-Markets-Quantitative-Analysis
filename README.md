# Citi Bank Markets Quantitative Analysis

This repository stores working files for the **_Citi Bank Markets Quantitative Analysis (MQA)_** Stimulation on [Forage](https://www.theforage.com/simulations/citi/global-quantitative-analysis-analyst-6b4m) 

### Project Briefing 

**Your role:**

- You are a quantitative analyst intern at Citi, joining the bustling Markets division for a summer internship.
  
- As part of the Markets Quant team, you'll work alongside seasoned professionals, each playing a crucial role in analyzing and navigating financial markets.
  
- Your primary role is to assist the team in quantitative analysis tasks, applying your skills and learning from experienced mentors to gain valuable insights into the world of financial markets.

**Project goals:**
- Your goal is to actively contribute to the team's projects by completing tasks that range from reviewing financial math fundamentals to pricing commodities, hedging securities, and managing risk.

- Through these tasks, you'll deepen your understanding of quantitative analysis techniques and their applications in real-world scenarios within Citi's Markets division.

- By the end of the program, you will have developed essential skills and knowledge that will prepare you for a successful career in quantitative analysis within the financial industry.

## Task 1: Financial math fundamentals and team structure

**Scenario: Coffee Commodity Analysis**

Imagine you are a quantitative summer analyst at Citi, and you are tasked with managing a portfolio that includes coffee commodities. Your responsibilities include pricing a futures contract, structuring securities, and managing risk. Explain the type of mathematics you would use in each part of this scenario and how you would apply it.

**Pricing a Futures Contract:**

To price a coffee futures contract, I would use the **cost of carry model**, which calculates the futures price based on the spot price, storage costs, and risk-free interest rate. The formula is:

$$
F_t = S_t e^{(r+d)T}
$$

where Ft is the futures price, St is the spot price, r is the risk-free rate, dd is the storage cost, and T is the time to maturity. This model helps ensure that the futures price reflects the cost of holding the commodity over time.

**Structuring Securities:**

When structuring a security linked to coffee prices, such as a commodity-linked bond or structured note, I would use **linear regression models** to identify and quantify the relationship between coffee prices and other economic factors. Additionally, I would apply **stochastic processes** to model the random behavior of coffee prices over time. For instance, using a geometric Brownian motion model can help in simulating future price paths and structuring the security’s payout accordingly.

**Managing Risk:**

To manage the risk associated with coffee commodity investments, I would employ several statistical methods:

- **Value at Risk (VaR):** Calculate the maximum expected loss over a given period with a certain confidence level. This involves using historical price data and statistical measures of volatility.

- **Monte Carlo Simulation:** Run numerous simulations to model the probability distribution of future coffee prices and assess potential losses under different scenarios.

- **GARCH Models:** Use these models to analyze and forecast volatility, helping to understand and mitigate the impact of price fluctuations on the portfolio.
  
By applying these mathematical techniques, I can effectively price futures contracts, design structured securities, and manage risks, ensuring a robust and well-informed approach to handling coffee commodities.

## Task 2: Pricing commodities – coffee

Factors Influencing the Pricing of Futures Contracts:
- **Supply and Demand Dynamics:**
  - Supply Factors: Production levels, agricultural yields, and inventory levels.

  - Demand Factors: Global consumption trends, consumer preferences, and economic conditions.

- **Weather Patterns:**
  - Adverse weather conditions like droughts, frosts, and excessive rainfall can significantly impact production and prices of goods.

- **Geopolitical Factors:**
  - Political stability, trade policies, and tariffs in major producing countries can influence prices.

- **Macroeconomic Indicators:**
  - Interest rates, inflation, and currency exchange rates affect commodity prices.

**Comprehensive Analysis:**

By understanding these factors and their potential impacts, you can better anticipate price movements and manage risk. Incorporate historical data, economic indicators, and geopolitical risk assessments into your quantitative models to provide a comprehensive analysis of futures prices. This approach will enable you to make more informed decisions and develop robust strategies for managing commodity investments.

Techniques for Pricing Commodity Derivatives/Futures in Financial Markets:
- **Linear Regression** is a fundamental technique used to predict the relationship between a dependent variable and one or more independent variables. It plays a crucial role in market trend analysis and forecasting.

- **Black-Scholes Model** is instrumental in option pricing, taking into account factors such as the underlying asset's volatility, the strike price, and the time to maturity. This model is essential for managing risk and valuing options accurately.

- **Monte Carlo Simulations** are utilized to assess the probability of various outcomes in financial processes. By conducting numerous simulations, we can estimate the potential range and likelihood of different price scenarios, which is critical for derivative pricing and risk management.

## Task 3: Hedging and structuring securities

**Strategies for Hedging Financial Risks Using Derivative Instruments**: 

Hedging financial risks is a critical aspect of managing uncertainties in the financial markets. Derivative instruments play a vital role in hedging strategies, offering opportunities to mitigate risks associated with price fluctuations, interest rate changes, currency fluctuations, and more. Below are key strategies and their specific application to pricing coffee options contracts: 
1. Hedging with Options Contracts.
2. Options Strategies for Hedging.
3. Hedging with Swaps.
4. Risk Management Considerations.

**Techniques for Structuring Securities**: 
1. Commodity-Linked Bonds.
    - Definition: Bonds that pay returns based on the price of a commodity, such as coffee.
  
2. Exchange-Traded Funds (ETFs)
    - Definition: Investment funds traded on stock exchanges, holding assets like stocks, commodities or bonds.

3. Structured Notes
    - Definition: Debt securities with returns linked to the performance of a commodity index or individual commodity prices.
  
4. Digital Options
    - Definition: Options that pay a fixed amount if the underlying asset's price meets certain conditions at expiration.
  
## Task 4: Managing risk across market trade units

**Understanding risk**: Risk in financial markets is the uncertainty of returns and the possibility of financial loss. It includes different factors such as market volatility, credit risk, liquidity risk, and operational risk.

**Types of risk**:
- Market risk
- Credit risk
- Liquidity risk
- Operational risk

**Risk management process**: 
- Identification
- Measurement
- Mitigation
- Monitoring and control
  
**Tools and techniques**: Risk management employs a range of tools and techniques, including Value at Risk (VaR), stress testing, Monte Carlo simulation, and derivative instruments such as options, futures, and swaps.

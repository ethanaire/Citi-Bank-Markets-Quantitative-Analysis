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

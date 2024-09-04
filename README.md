# Quantitative Risk Management
## Insurance Claim Fraud Detection Leveraging Machine Learning

This project focuses on developing a Machine Learning model to detect fraudulent insurance claims using models like Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, Neural Networks, and a Voting Classifier. The goal is to improve fraud detection accuracy and reduce false positives to minimize operational risks.

The dataset contains 1,000 observations with 39 features, such as months as customer, police report available, insured occupation,... and fraud reported. On the test set, Gradient Boosting performed best with 78.8% accuracy, while the Voting Classifier achieved 74%. However, the precision scores indicate a need for further refinement to enhance detection capabilities.

## Risk Smart Investing

The Risk Smart Investing project represents a cutting-edge approach to portfolio management, focusing on risk-based strategies that aim to balance risk minimization with robust out of sample performance. Our analysis evaluates six competing investment strategies namely: Equally Weighted (benchmark), Inverse Volatility, Minimum Volatility, Risk Parity, Maximum Diversification, and the machine learning-inspired Hierarchical Risk Parity Strategy; under three different sectors namely: DAX Export, DAX Dividend and DAX ESG.  

For our analysis, we utilized five years of in-sample data, spanning from July 2018 to June 2023, we then applied optimal weight to the out-of-sample data from July 2023 to August 2024 to evaluate their effectiveness in real-time market conditions and their ability to adapt to new information.

**Portfolio Allocation Results**: The Minimum Volatility Portfolio under the DAX ESG sector emerges as a standout performer, achieving the highest annualized returns of 17.71% and a growth rate of 23.28%. This portfolio also exhibits the lowest volatility at 9.12% and demonstrates the least risk, with the lowest: downside volatility (5.57%), maximum drawdown (5.47%), daily Value at Risk (0.89%), and daily Conditional Value at Risk (1.19%). Across all strategies, the Sharpe ratios are positive, with the Equally Weighted Portfolio under the DAX Dividend scoring the lowest at 0.69, while the Minimum Volatility Portfolio under the DAX ESG achieves the highest Sharpe ratio of 1.94.

**Quantitative Market Risk Analysis**: In the second phase, we conducted a Market Risk Analysis using metrics such as  Rolling volatility, Rolling VaR etc. The analysis reveals that the Maximum Diversification strategy is the most volatile across each sector on average, while the Hierarchical Risk Parity strategy generally exhibits the lowest  volatility on average. As anticipated, the Equally Weighted Strategy is most exposed to systematic shocks, whereas the Minimum Volatility Portfolio is the least exposed to systematic risk, as indicated by the market beta. This analysis highlights the importance of selecting appropriate strategies for effective risk management and optimal portfolio performance under varying market conditions.


# Optimizing Algorithmic Trading with Deep Reinforcement Learning

## 📌 Overview
This research explores **Deep Reinforcement Learning (DRL) for high-frequency trading (HFT)**, comparing **single-agent and multi-agent models** using various DRL algorithms. The study evaluates the **Proximal Policy Optimization (PPO), Deep Q-Network (DQN), and Advantage Actor-Critic (A2C)** models, along with an ensemble approach, to optimize algorithmic trading strategies.

## 📊 Key Findings
- **Higher Profitability & Risk Management:** Achieved **Sharpe ratio >1**, **Sortino ratio 7.7**, and **maximum drawdown <1%**, outperforming traditional trading models.
- **Single-Agent vs. Multi-Agent Models:** Single-agent PPO models demonstrated superior risk-adjusted returns, while multi-agent setups showed potential for scalability.
- **Ensemble Learning:** Combining multiple DRL models improved stability and adaptability in dynamic market conditions.
- **Sparse Reward Shaping:** Enhanced long-term decision-making in high-frequency trading.

## 🛠 Methodology
- **Dataset:** 1-minute interval stock data from **24 companies** over a **3-year period** (2 years training, 1 year testing).
- **Algorithms Used:**
  - **Single-Agent Models:** PPO, DQN, A2C
  - **Multi-Agent Models:** Cooperative and competitive frameworks
  - **Ensemble Learning:** Combined models for balanced trading strategies
- **Performance Metrics:**
  - Profit Factor, Sharpe Ratio, Sortino Ratio
  - Maximum Drawdown, Win Rate, Cumulative Return

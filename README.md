
# Algorithmic and High-Frequency Trading

This repository contains four slide decks prepared for a directed reading course on the book *Algorithmic and High-Frequency Trading* by Cartea, Jaimungal, and Penalva. The material focuses on the stochastic-control perspective used in the book to model trading decisions, optimal execution, and market making.

The slides are intended as concise reading notes, combining theoretical models, economic intuition, and selected empirical evidence from high-frequency markets.

## Slide Decks

### 1. Intro

[Download slides](<slides/Intro.pdf>)

This slide deck introduces the basic structure of electronic markets and limit order books. It covers market participants, market and limit orders, matching engines, bid-ask spreads, midprices, and the role of liquidity.

The deck also presents introductory market microstructure models, including inventory-based explanations of the bid-ask spread and information-based models such as Kyle’s framework. It then discusses empirical and statistical evidence from high-frequency data, including ITCH messages, order flow, intraday returns, volatility patterns, and price impact.

### 2. Stochastic Control

[Download slides](<slides/Stochastic_control.pdf>)

This slide deck introduces the stochastic-control framework underlying much of the book. It presents controlled stochastic processes, admissible controls, value functions, the dynamic programming principle, Hamilton-Jacobi-Bellman equations, and verification arguments.

The material includes the Merton portfolio problem as a classical example, then extends the discussion to counting processes and jump-based trading models used in algorithmic trading.

### 3. Optimal Execution

[Download slides](<slides/Optimal_execution.pdf>)

This slide deck studies optimal execution problems, where an agent must buy or sell a large position over a fixed time horizon. It introduces trading rates, inventory dynamics, cash processes, midprice dynamics, execution prices, and temporary or permanent market impact.

The deck derives optimal liquidation and acquisition strategies under different assumptions, including linear temporary impact, terminal penalties, permanent impact, and inventory-risk penalties. It emphasizes how execution costs and urgency shape the optimal trading schedule.

### 4. Market Making

[Download slides](<slides/Market_making.pdf>)

This slide deck focuses on stochastic-control models for market making. It studies how a market maker chooses quotes or posting decisions while managing cash, inventory, execution intensities, and terminal inventory costs.

The material covers optimal quote depths, inventory risk, execution probabilities, and extensions with adverse selection through short-term alpha. It also discusses order imbalance and order-flow information.

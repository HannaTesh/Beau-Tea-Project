Overview

This project analyzes operational challenges at Beau Tea, a boba beverage shop located in Washington, DC. Using data-driven methods, we developed optimization and simulation models to improve efficiency, reduce costs, and support better business decisions.

The project integrates operations research, risk analysis, and simulation techniques to solve real-world business problems.

Business Context

Beau Tea operates in a high-cost urban area and faces challenges such as:

Fluctuating seasonal demand
Limited inventory space
Budget constraints
Customer wait time vs efficiency trade-offs

Goal: Minimize cost while maximizing operational efficiency

Objectives
Optimize staffing decisions
Improve inventory planning
Reduce risk in marketing strategy
Maximize profit through simulation models
Improve customer service efficiency
Models & Methods Used
Integer Linear Programming (Optimization)

Purpose: Determine optimal number of employees

Decision variables:
Full-time employees
Part-time employees
Objective:
Minimize labor cost
Constraints:
Max 4 employees
Preparation time ≤ 2 hours

Result: Optimal staffing mix to balance cost and efficiency

Risk Modeling (Decision Analysis)

Purpose: Choose best marketing strategy

Compared platforms (e.g., TikTok, Instagram)
Used Mini-Max Regret criterion
Considered:
Market conditions (good, fair, poor)
Competition levels (high vs low)

Result: TikTok identified as optimal strategy (lowest regret)

Monte Carlo Simulation (Demand Forecasting)

Purpose: Optimize inventory levels

Simulated 1000 scenarios
Seasonal demand:
Summer: 300–500 cups/week
Winter: ~75 cups/week (normal distribution)
Calculated:
Profit
Waste
Optimal production quantity

Result: Data-driven inventory decisions to maximize profit

Queuing Simulation (Operations Efficiency)

Purpose: Optimize number of machines

Simulated 480 minutes (1 workday)
Modeled:
Customer arrivals
Queue length
Abandonment rate

Result: Optimal number of machines to reduce wait time and increase profit

Key Insights

Staffing directly impacts service speed and cost efficiency
Poor demand forecasting leads to:
Stockouts OR waste
Marketing strategy should adapt to competition
Increasing machines reduces wait time but increases cost
Seasonal demand must be accounted for in planning

Recommendations

Use optimization model to determine staffing each season
Adjust inventory levels based on simulation results
Invest in TikTok marketing for best risk-adjusted outcome
Increase machines only when demand justifies it
Monitor demand trends continuously

Tools & Technologies

Python (Jupyter Notebook)
Excel (Simulation & modeling)
Optimization techniques
Monte Carlo simulation
Decision analysis (Mini-Max Regret)

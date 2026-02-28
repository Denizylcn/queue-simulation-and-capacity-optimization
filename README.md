# queue-simulation-and-capacity-optimization

## Overview
This project presents a simulation-based operational model designed to optimize service capacity and profitability during peak demand periods.

The simulation evaluates how server capacity, customer arrival rates and system utilization thresholds impact waiting time, customer churn and overall financial performance.

---

## Problem Statement
During high-demand events (e.g., Black Friday), insufficient capacity can lead to customer waiting time and abandonment (churn), resulting in revenue loss. 

On the other hand, increasing capacity generates additional operational costs such as server setup and per-minute running expenses.

The key challenge is to determine the optimal capacity configuration that balances:
- Revenue generation
- Customer retention
- Infrastructure cost

---

## Solution Approach
The model simulates a 180-minute peak-demand period using scenario-based analysis.

Key components include:

- Randomized customer arrival modeling
- Service time estimation
- Server auto-scaling logic based on utilization thresholds
- Churn rate estimation under capacity stress
- Revenue and cost calculation
- Profit maximization through scenario comparison

Excel What-If analysis is used to test multiple configurations such as:
- Initial server count
- Server utilization thresholds
- Capacity adjustment strategies

---

## Key Metrics Evaluated
- Average waiting time
- Active user count
- Server utilization rate
- Lost revenue (churn impact)
- Total operational cost
- Net profit

---

## Business Relevance
This model demonstrates how simulation techniques can support operational decision-making in environments such as:

- Banking branch traffic management
- Call center workforce planning
- E-commerce infrastructure scaling
- Cloud resource allocation

---

## Tools Used
- Microsoft Excel
- Scenario simulation logic
- Data table (What-If analysis)
- Analytical performance metrics

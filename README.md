# Operations Analytics Portfolio

Three simulation projects in Python and SQL. All data is synthetic and all inputs are assumed.

## 1. Sales & Delivery Operations Analytics Dashboard
Files: ops_analytics_dashboard.py, ops_dashboard.png
Analyses 50,000 synthetic orders with SQLite (CTEs, window functions) and Pandas. Produces a KPI dashboard covering on-time delivery, returns, Pareto SKU analysis and anomaly detection.

## 2. Supply Chain & Inventory Optimization Simulation
Files: inventory_optimization.py, inventory_results.png
Compares a fixed reorder policy against EOQ with safety stock over 365 days for 8 SKUs.

## 3. Event Check-in Queue Simulation
Files: event_queue_simulation.py, queue_staffing_plan.png
Discrete-event simulation comparing flat staffing against demand-based shifts for a fest check-in.

## How to run
pip install numpy pandas matplotlib
python ops_analytics_dashboard.py

# Metro-Flow-Mathematical-Optimization

MetroFlow is a public subway operator that runs high-frequency rail services across both urban and suburban routes. Like many transportation agencies worldwide, MetroFlow faces increasing pressure from:

📈 Growing ridership demand
⚡️ Rising energy prices
🧾 Fixed budgets and limited infrastructure
🛠️ Aging rolling stock requiring higher maintenance costs

Balancing cost efficiency with service quality is critical for sustainable operation in this context. This project simulates a real-world decision problem often encountered in urban transit planning:

"Given a limited fleet of trains and cars, how can we schedule daily operations to maximize profit, meet at least 85% of passenger demand, and stay within resource limits like energy and maintenance budgets?"

#Why This Problem Matters
Urban transport systems are capital-intensive and rely heavily on effective planning. Poor resource allocation can lead to:

Overcrowded trains 🚉
Underutilized capacity during off-peak hours 🕒
High energy and maintenance costs 💸
Public dissatisfaction and revenue loss 👥

On the other hand, optimized scheduling leads to:

💰 Increased profitability
😊 Better passenger service
⚙️ Efficient use of energy and rolling stock
🌍 Lower environmental impact

📊 How Our Model Fits the Business Domain
Our model takes real-world constraints into account:

The number of train cars and trips must be feasible and within availability
Costs per trip (energy, maintenance, replacement) are modeled explicitly
Demand is segmented by route and time (rush vs. non-rush)
This results in a schedule that dynamically balances demand and cost to maximize profit, just like transit authorities do when making data-informed operational decisions.

A real-world transportation optimization model built using Excel Solver and Python (PuLP).  
Project done as part of SCM518 Final at W. P. Carey School of Business.

## 🔧 Objective
Maximize daily profit by optimizing train car allocation and trip frequency across 4 subway routes during rush/non-rush hours.

## 💡 Key Results
- ✅ Profit increased from $14K to $28.7K
- 📉 Reduced energy and maintenance costs
- 📊 85% of passenger demand satisfied

## 📂 Files Included
- `MetroFlow_Model.xlsx` → Excel implementation using Solver
- `MetroFlow_Python.ipynb` → Python optimization using PuLP
- `FinalSlides.pdf` → powerpoint slides of the project 

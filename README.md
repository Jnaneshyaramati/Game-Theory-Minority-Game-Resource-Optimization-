# 🎯 Game Theory: Minority Game Simulation for Resource Optimization  

## 📌 Overview  
This project simulates the **Minority Game**, a Game Theory model for decision-making and resource allocation. Agents repeatedly choose between two groups, and those in the **minority** benefit. We compare:  
1. **Random Assignment** – agents choose randomly.  
2. **Optimized Assignment** – agents adjust probabilistically to reduce imbalance.  

---

## 📌 Methodology  
- Agents (`n` = 100–1000) randomly assigned into two groups.  
- Simulation repeated (`avg_runs`) to compute averages.  
- Metric: **Average Difference (Δ) = |Group1 – Group2|**.  
- Lower Δ → better balance.  

---

## 📊 Results  
- **Random Assignment:** High imbalance, increases with `n`.  
- **Optimized Assignment:** Reduces imbalance by ~85–90%.  
- Plots and DataFrames show the difference clearly.  

---

## 📌 Insights  
- Optimization achieves **balanced group sizes**.  
- Real-world use cases: **traffic routing, network load balancing, distributed systems, markets**.  

---

## ⚙️ Tools  
- Python, Pandas, Matplotlib  

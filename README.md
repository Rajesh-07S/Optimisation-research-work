# 🏏 Data-Driven Cricket Team Selection using Optimization

## 📌 Description
A data-driven cricket team selection system that uses **Binary Integer Programming (BIP)** to optimize squad composition based on player performance metrics and real-world constraints.

---

## 🎯 Objective
- Select an optimal T20 cricket team using mathematical optimization  
- Reduce human bias in team selection  
- Ensure balanced team composition  
- Apply operations research techniques to sports analytics  

---

## 🧠 Problem Statement
Cricket team selection involves multiple trade-offs between batting, bowling, and fielding skills. Traditional selection methods are subjective and may not yield optimal results. This project formulates team selection as an optimization problem using Binary Integer Programming to ensure objective and efficient decision-making.

---

## 🛠 Methodology

### 1. Data Collection
Player performance data is collected from the SA Domestic Pro20 League, including:
- Batting average, strike rate, runs
- Bowling economy rate, bowling average, strike rate
- Fielding performance for wicketkeepers

### 2. Optimization Model
Each player is represented using a binary decision variable:


The objective is to maximize total team performance while satisfying all constraints.

### 3. Constraints
- Total players = 11  
- Minimum 5 batsmen  
- Minimum 5 bowlers  
- Exactly 1 wicketkeeper  
- Optional constraints such as budget and foreign player limits  

---

## ⚙️ Tools & Technologies
- **Language:** Python  
- **Optimization Libraries:** PuLP, Gurobi, CPLEX  
- **Domain:** Sports Analytics, Operations Research  

---

## 📊 Results
- Produces a balanced and optimized cricket squad  
- Outperforms manually selected teams  
- Eliminates selection bias  
- Ensures all role-based constraints are satisfied  

---

## 📁 Project Structure
Cricket-Team-Optimization/
│── data/
│ └── player_stats.csv
│── src/
│ └── optimization_model.py
│── README.md
│── optimization.pdf
│── requirements.txt



---

## 🚀 Future Scope
- Integrate real-time player form analysis  
- Apply machine learning for performance prediction  
- Extend model to IPL auctions and fantasy leagues  

---

## 👨‍💻 Authors
- Rajesh S  
- Sagar R Nayak  
- Nishith R  

B.Tech (Hons) Data Science  
Vidyashilp University, India

---

## 📜 License
This project is intended for academic and educational use.

⭐ Star the repository if you find it useful!

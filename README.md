# PROBABILITY-REPORT
# 📊 Customer Purchase Behaviour using Geometric Distribution

This project analyzes customer purchase behavior using probability theory, specifically the **Geometric Distribution**.

---

## 📌 Overview
The goal of this project is to model the number of trials required for a customer to make a purchase. Using real dataset values, we estimate the probability of success and compare observed data with the theoretical geometric distribution.

---

## 🎯 Objectives
- Estimate probability of purchase (p)
- Model customer behavior using geometric distribution
- Compare observed vs expected frequency
- Visualize results using graphs

---

## 📂 Dataset
The dataset contains:
- `Trials_Until_Purchase`: Number of attempts before a customer makes a purchase

Location: `/data/customer_purchase_dataset.csv`

---

## 🧠 Methodology
1. Load dataset using Pandas  
2. Compute mean of trials  
3. Estimate probability:  
p = 1 / mean
4. Compute expected probabilities using geometric distribution  
5. Compare with observed frequencies  
6. Plot results  

---

## 💻 Code
Main implementation is in:

📄 `main.py`

---

## ▶️ How to Run

1. Clone the repository  
2. Install dependencies:
   
---

## 📊 Output
- Bar graph → Observed data  
- Line plot → Theoretical geometric distribution  

(Add your plot image here)

```markdown
![Output Graph](images/plot.png)

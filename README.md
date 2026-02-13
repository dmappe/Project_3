# 📞 Megaline Plans Analysis

## 🔍 Overview
This project analyzes customer behavior and revenue for **Megaline**, a telecom company.  
The goal is to compare two mobile plans — **Surf** and **Ultimate** — and determine which is more profitable.  
The analysis includes data preparation, descriptive statistics, visualizations, and hypothesis testing.

---

## 📊 Dataset
The project uses multiple CSV files:
- **megaline_calls.csv** – Call records (duration, user, month)  
- **megaline_internet.csv** – Internet usage (MB consumed per user per month)  
- **megaline_messages.csv** – Text message usage  
- **megaline_plans.csv** – Plan details (monthly fee, included minutes/messages/MB, extra charges)  
- **megaline_users.csv** – User demographics and plan subscription  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas / NumPy** – Data manipulation  
- **SciPy** – Hypothesis testing  
- **Matplotlib / Seaborn** – Visualization  

---

## 📈 Analysis
- **Calls**: Compared average call duration per plan and per month.  
- **Internet**: Analyzed average monthly data usage by plan.  
- **Messages**: Studied message usage patterns across plans.  
- **Revenue**: Calculated monthly revenue per user and aggregated by plan.  

---

## 🎯 Hypothesis Testing
1. **Revenue comparison between Surf and Ultimate plans**  
   - H₀: Average revenue is equal.  
   - H₁: Average revenue differs.  
   - Result: **Ultimate plan generates significantly higher revenue** (p ≈ 0).  

2. **Revenue comparison between NY–NJ region and other regions**  
   - H₀: Average revenue is equal.  
   - H₁: Average revenue differs.  
   - Result: **NY–NJ users generate significantly lower revenue** than other regions (p ≈ 0).  

---

## 📊 Key Insights
- Users on the **Ultimate plan** generate over 3× the revenue of Surf users.  
- **NY–NJ region** shows lower average revenue compared to other regions.  
- Internet and call usage patterns vary significantly by plan, confirming differences in customer behavior.  

---

## ▶️ How to Run
1. Download the notebook (`project_3.ipynb`).  
2. Upload it to [Google Colab](https://colab.research.google.com/).  
3. Run the cells step by step.  

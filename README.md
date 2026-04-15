# 🎮 Loyalty Points Analysis  
### Data Analytics Case Study | Player Engagement & Reward Strategy

---

## 📌 Overview
This project analyzes player behavior on a gaming platform using gameplay, deposit, and withdrawal data.

The objective is to:
- Measure **user engagement and contribution**
- Design a **loyalty points system**
- Rank players based on performance
- Propose a **fair bonus distribution strategy**

---

## 🎯 Business Objective
The platform wants to:
- Identify **high-value players**
- Reward users fairly based on **engagement + financial contribution**
- Improve the **loyalty points system**

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy)  
- Excel  
- Jupyter Notebook  

---

## 📂 Project Structure

├── Analytics_Assignment.ipynb
├── Analytics Position Case Study.xlsx
├── Loyalty Points Analysis Report.docx
├── README.md


---

## 🧹 Data Preparation
- Cleaned and standardized datasets  
- Merged gameplay, deposit, and withdrawal data  
- Ensured consistency using user IDs  

---

## ⚙️ Methodology

### 🔹 Loyalty Points Calculation
Loyalty points were calculated based on:
- Number of games played  
- Deposit amount  
- Withdrawal behavior  

---

### 🔹 Time Slot Segmentation
- **S1:** 12:00 AM – 12:00 PM  
- **S2:** 12:00 PM – 12:00 AM  

Slot-wise analysis was performed to understand engagement patterns.

---

### 🔹 Aggregation & Ranking
- Monthly loyalty points calculated  
- Players ranked based on total points  
- Tie-breaker: number of games played  

---

## 📊 Key Analysis Performed

### Player Behavior
- High deposit + frequent gameplay → higher loyalty points  
- Small group of users drives majority of engagement  

---

### Slot Analysis
- Evening slot (S2) shows higher engagement  
- Activity varies across time and dates  

---

### Metrics Calculated
- Average Deposit Amount  
- Average Deposit per User  
- Average Games per User  

---

## 🏆 Leaderboard & Bonus Distribution

### Top Players
- Top 50 players selected based on loyalty points  

### 💰 Bonus Strategy
- Total bonus pool: ₹50,000  
- Distributed proportionally based on loyalty points  

### ✅ Why this works:
- Balances **engagement + financial contribution**  
- Ensures fair reward allocation  

---

## 🔍 Evaluation of Loyalty System

### ✅ Strengths
- Rewards both activity and spending  
- Encourages user engagement  

---

### ⚠️ Limitations
- High spenders dominate rankings  
- No quality check for gameplay  
- No penalty for withdrawals  
- No focus on recent activity  

---

## 💡 Recommendations

- Normalize deposit values to avoid dominance  
- Introduce **recency factor**  
- Reward quality gameplay, not just quantity  
- Add withdrawal penalties  
- Cap maximum points from a single activity  

---

## ▶️ How to Run

Install dependencies:

pip install pandas numpy


Run the notebook:

Analytics_Assignment.ipynb


---

## 📌 Key Insights

- Engagement is concentrated among a small user group  
- Evening activity is significantly higher  
- Loyalty-based ranking is effective but needs refinement  

---

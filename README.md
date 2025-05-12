
# 🧠 Shadow PM: Duolingo Retention & Feature Usage Analysis

This project simulates the role of a Product Manager at Duolingo. Using realistic, simulated user behavior and feature interaction data, we analyze retention patterns, segment users, and recommend actionable product improvements and A/B test ideas.

---

## 📌 Project Overview

- Simulates user activity within Duolingo (sessions, streaks, features used)
- Analyzes retention signals, churn behavior, and feature effectiveness
- Segments users into Power, Casual, and At-Risk based on behavior
- Proposes actionable recommendations and testable product strategies

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `user_behavior_simulated.csv` | Simulated user-level data (sessions, streaks, feature usage, churn) |
| `feature_events_simulated.csv` | Simulated daily feature usage data by user |
| `shadow_pm_duolingo_colab_v2.ipynb` | Full Jupyter/Colab notebook with analysis |
| `README.md` | Project summary and explanation (this file) |

---

## 📊 Key Analyses

- 📦 Feature usage frequency and average time spent
- 📉 Churn rate by feature (used vs dropped)
- 🧩 User segmentation by engagement level (Power, Casual, At-Risk)
- 📈 Retention visualization using boxplots (Streak Days vs Churn)
- 📎 Correlation between feature usage and paid conversion

---

## 💡 Insights & Product Recommendations

- **Stories** and **Daily XP** are strong drivers of retention and engagement.
- Longer streaks are correlated with lower churn.
- **Leaderboard** is widely used but has mixed retention value — ideal candidate for A/B testing.
- Recommend onboarding new users with sticky features like **Stories** to form early habits.
- Propose gating high time-spent features (like Grammar Tips) for upsell opportunities in freemium model.
- Two A/B tests proposed:
  1. Onboarding with/without Leaderboard emphasis
  2. Personalized dashboards for Power Users

---

## 🛠️ Tools Used

- Python (Pandas, Seaborn, Matplotlib)
- Google Colab
- Simulated CSV datasets
- GitHub for versioning and portfolio display

---

## ✅ Outcome

This project showcases product thinking, user behavior analysis, and data-driven strategy. It mimics how a PM or product analyst would assess an app’s feature set and make informed decisions to boost retention and growth.

---

## 🚀 Next Steps

- Deploy insights into a Streamlit app or dashboard
- Publish this project on LinkedIn or a personal portfolio
- Continue simulating user data to expand behavioral insights (e.g., cohort analysis)

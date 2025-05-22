# 💤 How Sleep Affects Productivity

This project analyzes the relationship between sleep patterns, physical activity, and daily productivity using Fitbit data. I explored how different sleep metrics influence performance, built predictive models, and visualized findings in an interactive Tableau dashboard.

---

## 🔍 Objective

To understand whether sleep duration, sleep efficiency, and physical activity can predict productivity — and if so, how strongly.

---

## 📊 Key Insights

- **Sleep Duration and Efficiency** are strong predictors of productivity.
- **Activity features** (steps, calories) have **minimal impact**.
- The **Random Forest model** achieved the best predictive performance with **R² = 0.83**.
- People sleeping **7–8 hours or more** consistently showed higher productivity.
- Productivity differences across sleep bins are statistically significant (ANOVA & Tukey HSD).

---

## 🧪 Methods Used

- Data cleaning & transformation in Python (Pandas, NumPy)
- Feature engineering: `HoursAsleep`, `SleepEfficiency`, lag features
- Regression models: Linear, Lag-based, Random Forest
- Statistical tests: ANOVA, Tukey HSD, t-test
- Interactive data storytelling with **Tableau**

---

## 📈 Dashboard Preview

👉 [View Tableau Dashboard](https://public.tableau.com/views/HowSleepAffectsProductivity/Dashboard1)

> *Explore how sleep duration and quality impact productivity across time, user groups, and model performance.*

---

## 📁 Files

| File                          | Description                                 |
|-------------------------------|---------------------------------------------|
| `How_Sleep_Affects_Productivity.ipynb` | Jupyter notebook with full analysis    |
| `Sleep_Activity_Productivity.csv`      | Cleaned dataset for modeling & Tableau |
| `Model_Performance.csv`               | Summary of model R² scores              |

---

## 🧠 Takeaway

Improving sleep — particularly **sleep efficiency** — has a meaningful impact on daily productivity. This project combines statistical analysis, modeling, and interactive storytelling to support behavior-focused insights with real data.

---

## 👩‍💻 Author

**Jagrati Chauhan**  
Master's in Data Science | University of Colorado Boulder  
[LinkedIn]( https://www.linkedin.com/in/jagratic/) 


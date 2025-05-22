# 💤 How Sleep Affects Productivity

This project analyzes the relationship between sleep patterns, physical activity, and daily productivity using Fitbit data. I explored how different sleep metrics influence performance, built predictive models, and visualized findings in an interactive Tableau dashboard.

---

## 🔍 Objective

To understand whether sleep duration, sleep efficiency, and physical activity can predict productivity — and if so, how strongly.

---

## 📊 Key Insights

- **Sleep Duration and Efficiency** are **strong predictors** of productivity.
- **Activity features** (steps, calories) have **minimal impact**.
- **Random Forest model** achieved the best predictive performance with **R² = 0.83**.
- People sleeping **7–8 hours or more** showed the highest productivity.

---

## 🧪 Methods Used

- Data cleaning & transformation in Python (Pandas, NumPy)
- Feature engineering: `HoursAsleep`, `SleepEfficiency`, lag features
- Regression models: Linear, Lag-based, Random Forest
- Statistical tests: ANOVA, Tukey HSD, t-test
- Interactive dashboard in **Tableau**

---

## 📈 Dashboard Preview

👉 [View Tableau Dashboard]([https://public.tableau.com/your-dashboard-link-here](https://public.tableau.com/views/HowSleepAffectsProductivity/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))

> *Note: Replace with your actual Tableau Public URL after publishing.*

---

## 📁 Files

| File                          | Description                                 |
|-------------------------------|---------------------------------------------|
| `How_Sleep_Affects_Productivity.ipynb` | Main analysis notebook (Python)      |
| `Sleep_Activity_Productivity.csv`      | Cleaned merged dataset               |
| `Model_Performance.csv`               | Summary of model results             |

---

## 🧠 Takeaway

Improving sleep quality — especially **sleep efficiency** — has a meaningful impact on daily productivity. This project demonstrates how statistical modeling and visualization can support behavioral insights.

---

## 👩‍💻 Author

**Jagrati Chauhan**  
Master's in Data Science | University of Colorado Boulder  
[LinkedIn]( https://www.linkedin.com/in/jagratic/) 


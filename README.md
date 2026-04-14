# Make it a habit: The effect of nudges on habitual handwashing behavior

![R](https://img.shields.io/badge/R-4.3.3-276DC3?logo=r)
![SPSS](https://img.shields.io/badge/IBM_SPSS-28-006BEB?logo=ibm)
![Status](https://img.shields.io/badge/Status-Published-success)
[![View Study](https://img.shields.io/badge/Journal-View_Publication-blue?logo=google-chrome&style=flat)](https://university.help.edu.my/wp-content/uploads/2025/05/JAPP-007-R2-Final-Version-Updated.pdf)

## 📌 Abstract
Public health compliance—specifically handwashing—often experiences a "decay effect" after initial enforcement. This study investigates the efficacy of **digital nudges** (social norms and incentives) in fostering long-term handwashing habits among university students. 

Using a 1-IV 3-Levels between-subjects design (N=178), I measured habit strength using the **Self-Report Habit Index (SRHI)** over a one-month intervention. While the experimental nudges showed non-significant results, the data provides a critical baseline for developing more sophisticated, high-frequency "nudging" pipelines that leverage real-time data and behavioral architecture.

---

## 📂 Methodology & Experimental Design
The study was structured to compare two different behavioral "frames" against a control group to see which most effectively bridged the gap between intention and habit.

* **Experimental Framework**: 1-IV 3-Levels Between-Subjects.
* **Intervention**: Weekly digital nudge delivery via high-salience digital posters for 30 days.
* **Reliability**: The SRHI scale demonstrated exceptional internal consistency (**Cronbach’s Alpha = .964**).

---

## 📈 Exploratory Data Analysis (EDA)
EDA was conducted in **R** to evaluate data distribution and identify potential demographic moderators like gender and faculty.

### 1. Habit Strength by Nudge Condition
```r
# Visualizing SRHI distribution across experimental groups
ggplot(df, aes(x = TypeofNudge_cat, y = SRHI_Avg, fill = TypeofNudge_cat)) +
  geom_boxplot(alpha = 0.7) +
  labs(title = "Habit Strength Across Nudge Conditions",
       x = "Nudge Type", 
       y = "Mean SRHI Score") +
  theme_minimal()

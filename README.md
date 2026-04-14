# Make it a habit: The effect of nudges on habitual handwashing behavior

![R](https://img.shields.io/badge/R-4.3.3-276DC3?logo=r)
![SPSS](https://img.shields.io/badge/IBM_SPSS-28-006BEB?logo=ibm)
![Status](https://img.shields.io/badge/Status-Published-success)
[![View Study](https://img.shields.io/badge/Journal-View_Publication-blue?logo=google-chrome&style=flat)](https://university.help.edu.my/wp-content/uploads/2025/05/JAPP-007-R2-Final-Version-Updated.pdf)

## 📌 Abstract
Despite the critical importance of hygiene, public health compliance often wanes over time. This research explores the efficacy of **digital nudges**—specifically social norm and incentive-based cues—delivered via digital displays to foster long-term handwashing habits.

In a between-subjects experimental study involving **178 participants**, I investigated whether subtle context changes could influence the **Self-Report Habit Index (SRHI)** scores over a one-month intervention period. While the results indicated non-significant differences between conditions, the study provides a vital technical foundation for using **behavioral economics** and **Big Data** to design more effective, personalized health interventions.

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

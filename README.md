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
The EDA phase focused on evaluating data distribution and identifying potential demographic moderators.

### 1. Habit Strength by Nudge Condition
Analyzed the spread and median of the SRHI scores across the three experimental levels (Social Norm, Incentive, and Control).

![Habit Strength by Condition](link_to_your_condition_boxplot_image_here)
*Figure 1: Comparison of SRHI scores across Social Norm, Incentive, and Control groups.*

### 2. Habit Strength by Gender
Evaluated baseline behavioral differences between genders to ensure demographic variables did not skew the nudge efficacy.

![Habit Strength by Gender](link_to_your_gender_boxplot_image_here)
*Figure 2: Distribution of SRHI scores highlighting similar behavioral baselines across gender identities.*

---

## 🧠 Statistical Analysis & Results (SPSS)
A One-Way ANOVA was used to evaluate the primary research question. Despite the theoretical strength of nudging, static digital delivery proved insufficient for significant habit formation in this context.

### Inferential Statistics
| Condition | Mean (M) | Std. Deviation (SD) | F(2, 174) | p-value |
| :--- | :--- | :--- | :--- | :--- |
| **Social Norm** | 4.10 | 1.55 | -- | -- |
| **Incentive** | 4.24 | 1.44 | -- | -- |
| **Control** | 4.17 | 1.58 | **0.115** | **.892** |

**Key Insight:** The $p$-value of **.892** suggests that there was no significant difference between the groups. This "null" result highlights the limitations of **passive digital interventions** compared to active, context-aware nudging.

---

## 🎯 Strategic Data Recommendations
To improve the efficacy of behavioral interventions, future strategies should transition from **Static Nudges** to **Dynamic Data Pipelines**:

1.  **Context-Aware Nudging**: Integrate IoT sensors (e.g., smart soap dispensers) to trigger nudges *at the moment of choice* rather than via weekly emails.
2.  **User Segmentation**: Apply clustering to identify "Nudge-Resistant" vs. "Nudge-Responsive" personas to personalize delivery frequency.
3.  **Reinforcement Learning**: Implement an RL-agent to optimize nudge framing based on real-time participant engagement data.

---

## 📖 Publication Detail
This research has been formally published in the **Journal of Applied Psychology & Psychology (JAPP)**. 

**Citation:**
Tang, R. C. H. (2025). Make it a habit: The effect of nudges on habitual handwashing behavior. *Journal of Applied Psychology & Psychology*, 7(2). 

**Full Publication Access:**
[Read the paper here](https://university.help.edu.my/wp-content/uploads/2025/05/JAPP-007-R2-Final-Version-Updated.pdf)

---
*© 2026 Ryan Tang.*

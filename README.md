# EdTech A/B Testing & Student Performance Analysis

## 📌 Project Overview

This project focuses on evaluating the effectiveness of an educational intervention using A/B Testing and statistical hypothesis testing.

Students were randomly assigned to two groups:

- **Control Group:** Students who did not receive the intervention.
- **Treatment Group:** Students who received the intervention.

The main objective is to determine whether the intervention improved student performance and course completion rates.

## 🎯 Project Objectives

- Understand and clean the student dataset.
- Handle missing values, duplicates, and inconsistent data.
- Perform feature engineering.
- Conduct Exploratory Data Analysis (EDA).
- Compare treatment and control groups.
- Perform statistical hypothesis testing.
- Measure treatment effect using Cohen's d.
- Calculate a 95% Confidence Interval.
- Evaluate the business impact of the intervention.

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

## 📂 Project Structure

```text
EDTECH_AB_TESTING/
│
├── .git/
├── .gitignore
│
├── visualizations/
│   ├── score_improvement_comparison.png
│   ├── treatment_effect_confidence_interval.png
│   ├── completion_rate_comparison.png
│   ├── score_improvement_distribution.png
│   └── pre_vs_final_score_comparison.png
│
├── 01.Data_Cleaning.ipynb
├── 02.Feature Engineering.ipynb
├── 03.EDA.ipynb
├── 04.Treatment vs Control - Deep Analysis.ipynb
├── 05.Hypothesis_Testing.ipynb
├── 06.Conclusion.ipynb
│
├── df_clean.csv
├── df_clean2.csv
└── students_dataset.csv
```

## 📊 Analysis Performed

1. **Data Cleaning:** Missing value treatment, duplicate removal, and inconsistent data handling.
2. **Feature Engineering:** Created new features such as score improvement and performance change.
3. **Exploratory Data Analysis:** Analyzed student performance, course distribution, attendance, and other patterns.
4. **Treatment vs Control Analysis:** Compared average scores, score improvement, and completion rates.
5. **Hypothesis Testing:** Applied Welch's Independent T-Test and Chi-Square Test.
6. **Effect Size:** Used Cohen's d to measure the magnitude of the treatment effect.
7. **Confidence Interval:** Calculated a 95% confidence interval for the difference in mean score improvement.
8. **Business Impact:** Evaluated the intervention's impact on student performance and course completion.

## 📈 Key Results

| Metric | Control Group | Treatment Group |
|---|---:|---:|
| Average Score Improvement | 5.07 | 7.13 |
| Completion Rate | 37.01% | 42.00% |

### Statistical Findings

- **Mean Improvement Difference:** 2.06 points in favor of the treatment group.
- **Welch's T-Test:** p-value = 3.67 × 10⁻²⁴.
- **Cohen's d:** 0.23 (Small Effect Size).
- **95% Confidence Interval:** [1.92, 2.19].
- **Completion Rate Difference:** 4.99 percentage points.
- **Chi-Square Test:** p-value = 6.46 × 10⁻⁶.

## 💡 Business Recommendation

The treatment intervention showed promising results in improving student performance and course completion.

The organization should consider further testing the intervention on a larger scale while monitoring its effectiveness.

## ⚠️ Limitations

- Missing final scores reduced the number of observations available for score improvement analysis.
- Mean imputation of missing pre-test scores may have influenced the results.
- The standardized treatment effect on score improvement was relatively small.
- Long-term student performance and knowledge retention were not evaluated.

## 🏁 Conclusion

The A/B testing analysis indicates that the treatment group performed better than the control group in terms of average score improvement and course completion.

This project demonstrates how Python, statistical testing, and A/B testing can be used to evaluate educational interventions and support data-driven business decisions.

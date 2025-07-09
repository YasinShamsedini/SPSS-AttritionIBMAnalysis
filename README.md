# Employee Attrition & HR Analytics Project (SPSS)

**Author:** Kian KKK  
**Date:** July 2025  
**Tool:** IBM SPSS Statistics  
**Dataset:** IBM HR Analytics – Employee Attrition & Performance

---

## Project Overview

This project investigates key factors that influence **employee attrition, satisfaction, and salary**, using a real-world HR dataset.  
All analyses were conducted using **IBM SPSS Statistics**, combining statistical reasoning with practical HR insights.

The project addresses the following core questions:
- What variables best predict employee attrition?
- How does satisfaction relate to retention or income?
- Are salary differences significant across marital or academic fields?
- Can we model the psychological and structural pathways behind attrition?

---

## Dataset: IBM HR Analytics – Employee Attrition & Performance

This dataset provides a wide view of organizational behavior, job roles, performance, and turnover.

**Variables include:**
- Demographics: Age, Gender, Education, Marital Status  
- Job: Job Role, Job Level, Department, OverTime  
- Satisfaction: Work-Life Balance, Environment, Relationship  
- Experience: Years at Company, Promotion History  
- Compensation: Monthly Income, Stock Options  
- Target: **Attrition** (Yes/No)

**Source (Kaggle):**  
[IBM HR Analytics – Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

**Applicable Statistical Techniques:**
- Logistic Regression
- One-Way ANOVA
- Correlation
- Factor Analysis (EFA)
- Path Analysis
- T-Tests, Cluster Analysis, PCA

---

## Project Files

| File | Description |
|------|-------------|
| 📄 [Final Report (PDF)](https://github.com/YasinShamsedini/SPSS-AttritionIBMAnalysis/blob/main/Files/SPSS-IBM.pdf) | Comprehensive analysis with findings |
| 📊 [SPSS Output File (.spv)](https://github.com/YasinShamsedini/SPSS-AttritionIBMAnalysis/blob/main/Files/Output%20SPSS%20IBM.spv) | Original SPSS output file |
| 📂 [SPSS Data File (.sav)](https://github.com/YasinShamsedini/SPSS-AttritionIBMAnalysis/blob/main/Files/SPSS%20IBM.sav) | Cleaned and structured SPSS dataset |
| 📈 [Raw Excel Dataset](https://github.com/YasinShamsedini/SPSS-AttritionIBMAnalysis/blob/main/Files/final_data.xlsx) | Unprocessed HR data |
| 📉 [Z-Score Data File](https://github.com/YasinShamsedini/SPSS-AttritionIBMAnalysis/blob/main/Files/z_score.xlsx) | Outlier detection and normalized values |

---

## Analysis Summary

### 1. Attrition Modeling
- **Monthly Income** and **Stock Options** are strong predictors (*p* < 0.001).
- Model accuracy was 83.3%, but failed to detect actual leavers due to class imbalance.

### 2. Relationship Satisfaction & Attrition
- Borderline significance (*p* = 0.054).
- Interpersonal satisfaction may affect turnover mildly.

### 3. Correlation with Total Working Years
- Weak negative correlation (r = –.182, *p* < .001).
- Employees with more experience are slightly more stable.

### 4. Factor Analysis: Education, Training, Experience
- One factor extracted (FAC1_1), but with weak internal consistency (α = 0.036).
- Logistic regression significant (*p* < .001) but not useful in classification.

### 5. Job Involvement by Field of Study
- ANOVA results: no significant difference (*p* = 0.943).
- Mean job involvement scores were similar across fields.

### 6. Salary Differences by Marital Status
- Significant difference between **single vs married** employees (*p* = 0.018).
- Married employees earned ~$688 more on average.

### 7. Path Analysis: Satisfaction → Income
- Model:  
  `RelationshipSatisfaction, EnvironmentSatisfaction, JobLevel → JobSatisfaction → MonthlyIncome`
- None of the paths were statistically significant.
- Suggests income is likely driven by structural factors.

---

## Key Takeaways

- **Financial incentives** matter more than emotional or perceptual satisfaction in attrition.
- Predictive models need **balanced data** for accuracy.
- Not all workplace factors translate to behavioral change (e.g., satisfaction ≠ income).
- Combining statistical modeling with HR insight reveals powerful relationships.

---

## Tools Used

- IBM SPSS Statistics (v26)
- Microsoft Excel
- GitHub for documentation and sharing

---

## Author Note

This project was completed as part of an academic training in applied HR analytics. It reflects both technical statistical analysis and strategic HR interpretation.  
Feel free to fork, reference, or build on this project for your own learning or research.

---

## Contact

Want to collaborate or share feedback?

📧 Email: [YourEmail@example.com]  
🔗 LinkedIn: [Your LinkedIn Profile]

---

> “Data without interpretation is just noise. This project turns HR data into actionable insight.”

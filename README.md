# 🎯 Employee Attrition & HR Analytics Project (SPSS-Based Study)

This project explores the **key organizational, psychological, and financial factors** influencing employee attrition, satisfaction, and compensation using a real-world dataset of over **1,400 employees**!

Leveraging **IBM SPSS Statistics**, the analysis combines robust statistical techniques with APA-style reporting to draw actionable insights for HR decision-making.


<br>

## I Try to Answer:

- What are the strongest predictors of employee attrition?
- How does satisfaction relate to retention and salary?
- Are salary differences statistically significant across marital statuses or educational backgrounds?
- Can we model structural and psychological pathways contributing to attrition?


<br>

## Dataset: IBM HR Analytics — Attrition & Performance

A comprehensive HR dataset including:

**Key variable groups:**
- **Demographics:** Age, Gender, Education, Marital Status  
- **Job Details:** Role, Department, OverTime, Job Level  
- **Satisfaction Metrics:** Environment, Work-Life Balance, Relationships  
- **Experience:** Years at Company, Promotion History  
- **Compensation:** Monthly Income, Stock Options  
- **Target Variable:** `Attrition` (Yes / No)

📌 **Source**: [Kaggle – IBM HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

<br>

## Applied Statistical Techniques

- Logistic Regression  
- One-Way ANOVA  
- Pearson Correlation  
- Exploratory Factor Analysis (EFA)  
- Path Analysis  
- Cluster Analysis, PCA  
- Independent & Paired Samples t-Tests  

<br>

## Project Repository Structure

| File | Description |
|------|-------------|
| 📄 [Final Report (PDF)](./Files/SPSS-IBM.pdf) | Full APA-style analysis and interpretation |
| 📊 [SPSS Output (.spv)](./Files/Output%20SPSS%20IBM.spv) | Original statistical outputs |
| 📂 [SPSS Dataset (.sav)](./Files/SPSS%20IBM.sav) | Final cleaned dataset |
| 📈 [Final Excel File](./Files/final_data.xlsx) | Final cleaned Excel |
| 📉 [Z-Score Data](./Files/z_score.xlsx) | Normalized variables and outlier detection |


<br>

---

<br>

# My Journey...
## Started this way!

### 🔹 Attrition Prediction
- **Income** and **stock options** were significant predictors (*p* < .001).  
- Overall model accuracy: **83.3%**; however, recall for actual leavers was poor due to class imbalance.

### 🔹 Satisfaction & Turnover
- Relationship satisfaction was borderline significant (*p* = .054), hinting at a potential soft influence on attrition.

### 🔹 Experience vs Retention
- Weak negative correlation with total working years (*r* = –.182, *p* < .001), suggesting longer-tenured employees are more stable.

### 🔹 Factor Analysis (Training & Education)
- One weak factor emerged with low reliability (α = 0.036). Regression using this factor was statistically significant but weak in predictability.

### 🔹 ANOVA – Job Involvement Across Fields
- No significant differences across education fields (*p* = 0.943).

### 🔹 Salary by Marital Status
- Significant income gap found (*p* = 0.018), with married employees earning ~$688 more on average.

### 🔹 Path Model – Satisfaction to Income
- Structural path model was not statistically supported. Satisfaction did not significantly predict income.

---

## 🧠 Insights & Implications

- **Monetary incentives** appear to have a stronger effect on attrition than emotional or perceptual satisfaction.  
- Data imbalance can limit the predictive power of logistic models.  
- Not all perceived workplace metrics translate to behavioral outcomes.  
- Combining **quantitative modeling** with HR understanding can yield deep and practical insights.

---

## 🛠 Tools & Technologies

- IBM SPSS Statistics (v26)  
- Microsoft Excel  
- GitHub for version control and publication

---

## 👨‍💼 Author Note

This project was completed as part of a structured academic training in applied statistics and HR analytics.  
It demonstrates the integration of statistical methodology with real-world organizational interpretation and APA-standard reporting.

---

## 📬 Contact & Collaboration

Interested in collaboration, research, or feedback?

📧 Email: [YourEmail@example.com]  
🔗 LinkedIn: [Your LinkedIn Profile]

---

> 🧩 *“Without interpretation, data is noise. With statistical insight, it becomes strategy.”*

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


<br><br>

# 📌My Journey


### 1. Downloading...
Data was downloaded from [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).
<br><br>
### 2. Preprocessing and Normalizing
I started data preprocessing in Excel.  
First, I looked for missing values — fortunately, there were none.  
After that, I created a new column for each string-based column and converted their values to numeric codes (for example, department codes were defined in the `DepCode` column).

Then, I calculated **z-scores** for several columns to detect outlier values. The results can be found in:  
→ [Z-Score Data](./Files/z_score.xlsx)

I removed all outlier values that were outside the normal range (–3 to +3) to ensure realistic results in statistical tests.  
The final cleaned Excel file is here:  
→ [Final Excel File](./Files/final_data.xlsx)
<br><br>
### 3. SPSS
I imported the cleaned Excel file into **SPSS** and started statistical modeling and analysis based on:  
→ [SPSS Dataset (.sav)](./Files/SPSS%20IBM.sav)

I also provided all statistical outputs from SPSS here:  
→ [SPSS Output (.spv)](./Files/Output%20SPSS%20IBM.spv)
<br><br>
### 4. Reporting
Based on what I learned, I analyzed the data, explored insights, and wrote the final report using APA structure:  
→ [Report the Results (PDF)](./Files/SPSS-IBM.pdf)

Finally, I published the whole project here on GitHub!
<br><br>


<br><br>

## 👨‍💼 Final Notes

After weeks of completing spss course, I decide to create a project. alongside my course, I completed 16-weeks plan from chatgpt to dive deeper in SPSS and sattistics. This project was completed as part of a structured academic training in applied statistics and HR analytics based on real-world data. I would like to sincerely thank **Dr. Hamid Barani** for his patience, precision, and commitment to teaching SPSS with practical, real-world insight.  
I’m also deeply grateful to **my parents** for their encouragement, valuable input during the modeling phase, and continuous financial support throughout my SPSS journey.I've learned SPSS not just as a tool, but as a way to develop analytical thinking and looking forward to new academic challenges and deeper interaction with data!

Email: yasin.shamsedini@gmail.com

10 July 2025  

Shiraz University

<br><br>

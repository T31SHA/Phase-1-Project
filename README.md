# Aviation Accident Risk Analysis

## 1. Project Overview

This project conducts an exploratory and analytical review of historical aviation accident data to evaluate **operational risk across aircraft categories and manufacturers**. Using data analysis and visualization techniques, the project aims to generate **actionable insights** that support informed, data-driven decision-making.

The analysis follows a structured data science workflow aligned with academic grading rubrics: problem definition, data preparation, exploratory analysis, visualization, and interpretation of results.

---

## 2. Business Understanding

Aviation stakeholders such as investors, operators, and insurers require evidence-based methods to assess **risk exposure** when selecting aircraft types or manufacturers.

### Key Questions Addressed

* Which aircraft categories are involved in the highest number of accidents?
* Which categories are associated with more severe accident outcomes?
* Which manufacturers demonstrate comparatively lower risk profiles?

---

## 3. Data Understanding

### Dataset Description

* **Source:** Aviation accident records (CSV format)
* **Observations:** Multiple years of recorded aviation incidents
* **Relevant Variables:**

  * Aircraft Category
  * Aircraft Manufacturer (Make)
  * Injury counts (Fatal, Serious, Minor)

Initial inspection included reviewing dataset shape, data types, missing values, and overall data quality.

---

## 4. Data Preparation

Data cleaning and preparation steps were performed to ensure accuracy and analytical reliability:

* Removal of irrelevant or high-missing-value columns
* Standardization of column names
* Handling of missing injury values
* Feature engineering: creation of **Total Injuries** as a severity metric

These steps ensured the dataset was suitable for analysis and visualization.

---

## 5. Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to identify patterns, trends, and relationships within the data:

* Accident frequency analysis by aircraft category
* Injury severity comparison using average total injuries
* Manufacturer-level risk assessment

EDA focused on answering the business questions directly and avoiding unnecessary complexity.

---

## 6. Visualizations

The project includes multiple clear and interpretable visualizations created using **Matplotlib**:

* Bar chart showing accident counts by aircraft category
* Bar chart illustrating average injury severity by aircraft category
* Horizontal bar chart highlighting manufacturers with the lowest average injury severity

Each visualization directly supports analytical findings and conclusions.

---

## 7. Key Findings

* Certain aircraft categories account for a disproportionately high number of accidents.
* Injury severity varies significantly across aircraft categories, indicating that frequency alone is not sufficient for risk assessment.
* Some manufacturers consistently demonstrate lower average injury severity, suggesting reduced relative risk.

---

## 8. Conclusions & Recommendations

Based on the analysis:

* Aircraft categories with lower accident frequency and severity should be prioritized for investment or acquisition.
* Manufacturers with consistently lower injury outcomes represent safer operational choices.
* Risk assessments should incorporate **severity metrics**, not just accident counts.

These conclusions are supported by quantitative analysis and visual evidence.


Interactive Dashboard [https://public.tableau.com/authoring/AviationRiskAssessmentDashboard/Dashboard1#1]
---

## 9. Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 10. Project Structure

```
aviation-risk-analysis/
│
├── aviation_risk_analysis.ipynb
├── Aviation_Data.csv
├── README.md
```

---

## 11. How to Run the Project

1. Clone or download this repository
2. Ensure Python 3.x is installed
3. Install required packages:

   ```bash
   pip install pandas numpy matplotlib
   ```
4. Open the notebook:

   ```bash
   jupyter notebook aviation_risk_analysis.ipynb
   ```
5. Run all cells sequentially

---

## 12. Author

**Sharahbill Mohamed Abdi**
Data Science Student | python Dev

---

## 13. Academic Note

This project was completed for **educational and assessment purposes** and demonstrates applied skills in data cleaning, exploratory analysis, visualization, and interpretation using real-world aviation data.

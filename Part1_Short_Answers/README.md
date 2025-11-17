# Part 1: Short Answer Questions

## 1. Problem Definition
**Hypothetical AI Problem:** Predicting student dropout rates in online courses.

**Objectives:**
1. Identify students at high risk of dropping out early.
2. Recommend personalized interventions.
3. Reduce overall dropout rates by 15% in one academic year.

**Stakeholders:**
- University administration
- Students

**Key Performance Indicator (KPI):**
- Accuracy of predicting at-risk students.

---

## 2. Data Collection & Preprocessing
**Data Sources:**
1. Learning Management System (LMS) logs.
2. Student demographic data.

**Potential Bias:**
- Socio-economic disparities in historical data may bias predictions.

**Preprocessing Steps:**
1. Handle missing data (median/mean imputation).
2. Normalize numerical features.
3. Encode categorical variables.

---

## 3. Model Development
**Chosen Model:** Random Forest Classifier  
**Justification:** Handles numerical and categorical data, reduces overfitting, interpretable.

**Data Split:** 70% training, 15% validation, 15% test.

**Hyperparameters to Tune:**
1. `n_estimators` – number of trees.
2. `max_depth` – maximum depth of each tree.

---

## 4. Evaluation & Deployment
**Evaluation Metrics:**
1. Precision – correctly predicted at-risk students.
2. Recall – actual dropouts identified.

**Concept Drift:** Change in student behavior patterns over time; monitor with ongoing model evaluation.

**Technical Challenge:** Scalability to handle large volumes of student data daily.

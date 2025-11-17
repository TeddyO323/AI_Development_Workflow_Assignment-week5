# Part 4: Reflection & Workflow Diagram

## 1. Reflection

**Most Challenging Part:**  
The most challenging part of the workflow was **data preprocessing and bias mitigation**. Handling missing values, encoding categorical variables like diagnosis codes, and ensuring fairness across patient demographics required careful thought. Real-world medical data is messy, and small mistakes can drastically affect model predictions.

**Improvements with More Time/Resources:**  
- Collect more diverse and extensive datasets to improve model generalization.  
- Incorporate advanced explainability tools (e.g., SHAP, LIME) for clinician trust.  
- Build automated pipelines for data cleaning, feature engineering, and model retraining to reduce manual effort and human error.

---

## 2. AI Development Workflow Diagram

**Diagram Description:**  
The workflow diagram illustrates the end-to-end AI development process for this case study:

1. **Problem Definition** → define objectives, stakeholders, and KPIs.  
2. **Data Collection & Preprocessing** → gather EHRs, demographics; handle missing values; feature engineering; normalize/encode.  
3. **Model Development** → select model, split data, tune hyperparameters, train model.  
4. **Evaluation & Deployment** → compute metrics (precision/recall), monitor concept drift, integrate into hospital system.  
5. **Optimization & Monitoring** → mitigate overfitting, retrain periodically, ensure compliance with healthcare regulations.  
6. **Critical Thinking & Reflection** → evaluate ethics, bias, trade-offs, and workflow effectiveness.


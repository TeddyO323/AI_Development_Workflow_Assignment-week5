# Part 3: Critical Thinking

## 1. Ethics & Bias

**Problem:**  
Bias in training data can seriously affect patient outcomes. For example, if the dataset underrepresents certain age groups, genders, or socio-economic backgrounds, the model may systematically underpredict readmission risk for these patients. This could lead to missed interventions and worse health outcomes.

**Potential Impacts:**  
- High-risk patients may not receive necessary care.  
- Certain groups could be unfairly flagged as high-risk, leading to unnecessary tests or treatments.  
- Hospital resources may be misallocated based on biased predictions.

**Strategy to Mitigate Bias:**  
- **Re-sampling or weighting:** Adjust training data to balance underrepresented groups.  
- **Fairness metrics:** Monitor model performance across demographic slices to ensure equitable predictions.  
- **Human-in-the-loop review:** Clinicians should review high-risk predictions to catch potential bias before acting.

---

## 2. Trade-offs

**Interpretability vs. Accuracy:**  
- Gradient Boosting models are powerful but complex.  
- Clinicians need interpretable models to trust recommendations; complex models may provide slightly higher accuracy but lower interpretability.  
- Trade-off strategy: Use feature importance plots or SHAP values to explain predictions, combining accuracy with interpretability.

**Computational Constraints:**  
- Hospitals may have limited resources for real-time predictions.  
- Complex models like deep ensembles might be too slow; simpler models (Random Forest, Logistic Regression) may offer slightly lower accuracy but faster predictions.  
- Strategy: Deploy a simpler model initially and plan periodic offline updates for high-accuracy predictions.

---

**Summary:**  
Balancing ethical fairness, interpretability, and computational constraints is crucial in healthcare AI. Ignoring these trade-offs can compromise both patient safety and hospital efficiency.

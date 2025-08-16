# Heart Disease Risk Prediction — Exploratory Data Analysis & Predictive Modeling

## 📌 Project Overview  
This project applies **exploratory data analysis (EDA)**, **advanced visualization**, and **machine learning modeling** (LightGBM + calibration + SHAP interpretability) to the **UCI Heart Disease dataset**. The goal is to demonstrate a **consultant-level workflow** that translates raw medical records into **operational insights** and **deployable risk models**.  

The notebook showcases:  
- Top-tier **seaborn visualizations** answering **10+ business/clinical questions**.  
- A calibrated **LightGBM probabilistic model** with reliability plots.  
- **SHAP explanations** (summary, dependence, subgroup fairness by sex/age).  
- Saved figures and models structured for reproducibility.  
- Exportable **HTML report** suitable for portfolio or stakeholder presentation.  

---

## 📂 Project Structure  

```
Early_HeartDisease_Detection/
│
│── Heart_Seaborn_EDA_v2.ipynb   # main analysis notebook   
│   
│
└── README.md                        # project documentation (this file)                        

```

---

## 🎯 Business & Clinical Questions Addressed  

1. Which **age groups** show the highest prevalence of heart disease?  
2. How does **gender** interact with risk factors such as chest pain, max HR, or ST slope?  
3. Is **exercise-induced angina** a strong discriminator of disease risk?  
4. What is the relationship between **cholesterol levels** and disease outcomes?  
5. Do patients with **asymptomatic chest pain** have different risk profiles?  
6. How predictive is **ST slope** compared to other ECG features?  
7. Does **resting BP** have non-linear effects on heart disease probability?  
8. Are **age-sex subgroups** equally represented and equally modeled (fairness check)?  
9. Can **probabilistic calibration** improve clinical usability of model predictions?  
10. Which **features drive predictions most strongly**, and do they differ across subgroups?  

---

## 🛠️ Methods & Tools  

- **Python Libraries**: pandas, numpy, seaborn, matplotlib, scikit-learn, shap, lightgbm  
- **Exploratory Data Analysis (EDA)**: univariate, bivariate, multivariate visualization with seaborn  
- **Machine Learning**: LightGBM classifier + Platt scaling calibration  
- **Interpretability**: SHAP values (summary, beeswarm, dependence plots)  
- **Fairness & Robustness**: subgroup calibration & SHAP mean-absolute comparisons by sex/age  
- **Reporting**: polished HTML export + saved figures  

---

## 🔑 Key Insights  

- **Age & Sex Effects**: Males in the 40–60 range showed highest disease prevalence.  
- **Chest Pain Types**: Non-anginal and asymptomatic chest pain correlated most with positive diagnoses.  
- **Exercise Angina**: Presence was strongly predictive across both sexes.  
- **ST Slope**: Among the most influential ECG features, highlighting ischemia detection importance.  
- **Calibration**: Calibrated LightGBM produced reliable probability estimates (Brier score improved).  
- **SHAP Analysis**: Feature importance stable across global and subgroup views, with slight shifts in relative importance across age and sex slices.  

---

## 📊 Outputs  

- **Seaborn Visuals**: portfolio-grade, answering clinical/business questions.  
- **Reliability Diagrams**: calibrated vs uncalibrated comparison.  
- **SHAP Plots**: global + subgroup explanations.  
- **Saved Figures**: reusable in slide decks or reports.  
- **Calibrated Model**: exportable LightGBM + calibration.  
- **Polished Report**: HTML export of notebook (ready to share).  

---

## 🚀 Next Steps  

1. **Data Enrichment**: Add smoking status, medications, and longitudinal vitals.  
2. **Modeling**: Train isotonic regression–calibrated LightGBM, tune hyperparameters.  
3. **Fairness Checks**: Run calibration + metrics per subgroup (sex, age bands).  
4. **Deployment**: Package model as a decision-support tool with clinician-in-loop workflow.  
5. **Validation**: Conduct prospective trials on real-world cohorts.  

---

## 💼 Portfolio Relevance  

This project demonstrates:  
- End-to-end **data science workflow** from raw data to deployable model.  
- **Expert-level storytelling with visuals**, answering relevant business/clinical questions.  
- **Model interpretability and fairness analysis** — crucial for responsible AI in healthcare.  
- **Polished deliverables** (notebook, HTML report, figures, models) structured for professional presentation.  


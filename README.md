# 🧠 fNIRS-Based HbO₂ Signal Modeling – Phenotype-Specific Cortical Activation in Parkinson’s Disease

This machine learning project analyzes fNIRS-based HbO₂ time-series signals to identify differences in cortical activation between Parkinson’s disease phenotypes: Tremor-Dominant (TD) and Postural Instability Gait Disorder (PIGD). The goal is to uncover region-specific hypoactivation that may signal early motor-cognitive interference and inform clinical stratification.

---

## 🚀 Project Overview

- **Dataset:** REDCap-exported clinical and neuroimaging data (IRB-approved)
- **Objective:** Model brain activation (HbO₂) differences across SMA, PFC, and PMC between PD phenotypes
- **Target Variables:** Phenotype group (TD vs. PIGD), task condition (single vs. dual-task)
- **Tech Stack:** Python, MNE-Python, MNE-NIRS, Pandas, Matplotlib, Seaborn, Scikit-learn

---

## 📊 Key Techniques

- Preprocessing of fNIRS time-series using MNE-NIRS
- Region-of-interest segmentation (SMA, PFC, PMC)
- General Linear Modeling (GLM) to compare activation levels
- Visualization of cortical activation and phenotype contrasts
- Statistical testing of signal differences (t-tests, effect size)
- Exploratory classification models (Random Forest, Logistic Regression)

---

## 🧪 Evaluation Highlights

| Model               | Accuracy | ROC AUC | Insight                                      |
|--------------------|----------|---------|----------------------------------------------|
| Logistic Regression | 0.82     | 0.87    | Clean separation of TD vs. PIGD under DT     |
| Random Forest       | 0.86     | 0.91    | Higher stability; better spatial separation  |

- GLM revealed consistent hypoactivation in SMA and PFC for PIGD group.
- Dual-task condition amplified differences in cortical signal strength.

---

## 🔍 Key Insights

- Dual-task walking amplifies neural differences between PD phenotypes.
- SMA and PFC activation patterns can aid early phenotype stratification.
- fNIRS is viable for detecting early cortical disruption in PD progression.
- Region-level features can support explainable ML models for phenotype prediction.

---

## 🧠 Learnings

- Preprocessing and channel mapping in fNIRS is critical before modeling.
- GLM is a powerful tool for structured fNIRS time-series comparison.
- Explainability (region-specific interpretation) is vital in clinical modeling.
- Combining neuro and behavioral data enhances model robustness.

---

## 🛠 Future Enhancements

- Integrate dual-task behavioral performance features into model
- Expand to multi-class prediction (e.g., control vs. TD vs. PIGD)
- Deploy an interactive dashboard (Streamlit) to visualize region-level risk
- Consider temporal dynamics using LSTM for time-window prediction

---

## 📁 Repository Structure

📁 fNIRS_Based_HbO2_Signal_Modeling/

# Main modeling notebook
fNIRS_Based_HbO₂_Signal_Modeling.ipynb # Main modeling notebook
# Rendered version for review
fNIRS_Based_HbO₂_Signal_Modeling.html 
# Input neuro-behavioral dataset
IdentifyingEarlyDecl-AyushiAndYamna.xlsx # Input neuro-behavioral dataset



---

## 🔗 Resources

- 📄 [View Notebook (HTML)](./fNIRS_Based_HbO₂_Signal_Modeling.html)
- 📊 [Raw Data (Excel)](./IdentifyingEarlyDecl-AyushiAndYamna.xlsx)

---

📬 **Contact:**  
For collaborations or academic inquiries, contact [shruthivudem864@gmail.com](mailto:shruthivudem864@gmail.com)

# 🧠 fNIRS-Based HbO₂ Time-Series Modeling – Phenotype-Specific Cortical Activation in Parkinson’s Disease

This machine learning project performs time-series modeling of fNIRS-based HbO₂ signals to identify differences in cortical activation between Parkinson’s disease phenotypes: Tremor-Dominant (TD) and Postural Instability Gait Disorder (PIGD). Using structured neuroimaging pipelines, we aim to uncover region-specific hypoactivation that may signal early motor-cognitive interference and guide clinical stratification.

---

## 🚀 Project Overview

- **Dataset:** REDCap-exported clinical and neuroimaging data (IRB-approved)
- **Objective:** Model brain activation (HbO₂) differences across SMA, PFC, and PMC between PD phenotypes
- **Target Variables:** Phenotype group (TD vs. PIGD), task condition (single vs. dual-task)
- **Tech Stack:** Python, MNE-Python, MNE-NIRS, Pandas, Matplotlib, Seaborn, Scikit-learn

---

## 📊 Key Techniques

- Time-series preprocessing and noise rejection using MNE-NIRS
- Region-of-interest (ROI) segmentation: SMA, PFC, PMC
- General Linear Modeling (GLM) for activation curve estimation
- Visualization of cortical activity across phenotypes and conditions
- Statistical comparison: t-tests, effect size (Cohen's d)
- Exploratory machine learning (Random Forest, Logistic Regression)

---

## 🧪 Evaluation Highlights

| Model               | Accuracy | ROC AUC | Insight                                      |
|--------------------|----------|---------|----------------------------------------------|
| Logistic Regression | 0.82     | 0.87    | Clear TD vs. PIGD separation in DT tasks     |
| Random Forest       | 0.86     | 0.91    | Captured non-linear spatial signal variance  |

- GLM analysis showed consistent PIGD hypoactivation in SMA and PFC.
- Cortical signal divergence increased during dual-task walking.

---

## 🔍 Key Insights

- Dual-task conditions amplify motor–cognitive phenotype separation.
- SMA and PFC HbO₂ trends correlate with clinical symptom profiles.
- fNIRS time-series are reliable for early neural signature detection in PD.
- Region-specific signals support interpretable ML models in neurohealth.

---

## 🧠 Learnings

- High-quality fNIRS preprocessing is essential for valid modeling.
- GLMs provide powerful interpretability for time-locked fNIRS responses.
- Combining temporal and regional patterns boosts phenotype prediction.
- Time-series modeling enables early screening possibilities in PD research.

---

## 🛠 Future Enhancements

- Add LSTM or temporal attention models for fine-grained dynamic analysis
- Combine behavioral performance metrics with neural features
- Extend to multi-class modeling (TD vs. PIGD vs. Controls)
- Deploy interactive visual dashboard using Streamlit or Dash

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

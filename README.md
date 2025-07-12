# fnirs-Brain-Modelling
Analyzed HbO₂ time-series signals from fNIRS to model cortical activation differences between Parkinson’s phenotypes (TD vs. PIGD). Used Python, MNE-NIRS, and GLM to identify region-specific hypoactivation and explore early markers of motor-cognitive interference.

This project analyzes cortical activation differences between Parkinson’s disease phenotypes — Tremor Dominant (TD) and Postural Instability Gait Disorder (PIGD) — using fNIRS-based HbO₂ time-series signals. The goal is to identify phenotype-specific patterns of cortical hypoactivation that may serve as early neural markers for motor-cognitive interference and gait freezing.

We used MNE-NIRS and General Linear Models (GLM) to model hemodynamic responses across regions of interest (SMA, PFC, PMC), based on REDCap-exported datasets. Visualizations, signal preprocessing, and statistical modeling were implemented in Python. Results support the hypothesis of phenotype-driven brain remodeling in early-stage Parkinson’s Disease.

🔧 Tools & Methods
Python, Jupyter, Pandas, NumPy

MNE-NIRS, MNE-Python, Matplotlib, Seaborn

GLM Modeling, Signal Preprocessing, Baseline Correction

REDCap Clinical Data Export, Phenotype Labeling, Event Alignment

📁 Key Outputs
Cleaned and visualized HbO₂ and Hb data across phenotypes

GLM-based activation maps highlighting cortical differences

Region-specific trend analysis (e.g., reduced SMA/PFC activity in PIGD group)

Early insights on functional remodeling related to motor-cognitive load

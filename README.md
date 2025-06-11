# 🧪 Sepsis Biomarker Analysis

This repository contains the complete workflow for a longitudinal biomarker-based analysis of sepsis patients. The project evaluates the diagnostic and prognostic power of multiple biomarkers across four time points (Days 1, 3, 5, and 7) using statistical and machine learning methods.

## 🧬 Overview

- **Objective**: Evaluate the clinical utility of biomarkers (e.g., PCT, Presepsin, YKL-40, CRP) in predicting sepsis outcomes.
- **Data Source**: Clinical and laboratory data collected at multiple time points.
- **Key Deliverables**:
  - Timepoint-specific univariate and multivariate logistic regressions
  - ROC and AUC analysis for biomarker performance
  - Final integrated report for publication or internal use

---

## 🧱 Project Structure

sepsis-biomarker-analysis/
├── data/
│
└── Raw_data_JB_Ozlem.xlsx # Original clinical and biomarker data

│

├── notebooks/

│ ├── Step1_7_previous.ipynb # Initial preprocessing steps

│ ├── Updated_6B and C_May_6.ipynb # Day-wise AUC and regression analysis

│ ├── Step_8.ipynb # Extended modeling (multivariate)

│ └── Step_9.ipynb # Final comparisons and visualizations

│

├── reports/

│ ├── Sepsis_Biomarker_Final_Report_JB.docx

│ └── JB_Results_Ozlen_revised.docx

│

├── references/

│ ├── SPSS codes_Ozlem.docx

│ └── JB_Results_Ozlen.docx

│
├── LICENSE
├── .gitignore
└── README.md


---

## 📊 Analysis Components

### 1. Data Preparation
- Read and reshape clinical biomarker data
- Standardize units and formats across days and markers
- Handle missing values via interpolation or exclusion

### 2. Statistical Modeling
- **ROC Curve Analysis**: Calculate AUC for each biomarker at each timepoint
- **Youden Index**: Identify optimal cutoff values
- **Logistic Regression**:
  - Univariate: Assess each biomarker’s predictive power
  - Multivariate: Combine markers (e.g., Presepsin + PCT) for improved prediction

### 3. Deliverables
- Fully annotated Jupyter notebooks
- Statistical report (in DOCX format)
- Processed output tables/figures

---

## ▶️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/OzlemGulsumKilickaya/sepsis-biomarker-analysis.git
   cd sepsis-biomarker-analysis


🙌 Acknowledgments
Project contributors and clinical partners

Statistical procedures inspired by SPSS and adapted to R 

Data anonymized for ethical compliance

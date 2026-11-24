# Predicting and Profiling Diabetes Risk from Health and Lifestyle Indicators

A Data Mining / Knowledge Discovery in Databases (KDD) team project following the **CRISP-DM** methodology on public diabetes risk data.

## Project Overview
* **Domain:** Healthcare — Diabetes risk analysis (predicting and profiling risk from patient and lifestyle data).
* **Methodology:** CRISP-DM (Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Reporting/Deployment Recommendations).
* **Primary Notebook:** `meow.ipynb`
* **Tools & Stack:** Python (`pandas`, `NumPy`, `scikit-learn`, `matplotlib`, `mlxtend`).

## Dataset
* **Dataset:** CDC Diabetes Health Indicators (BRFSS survey).
* **Structure:** Mixed numeric and categorical health, lifestyle, and demographic attributes (> 1,000 records and > 8 attributes)[cite: 1].
* **Ethics & Licensing:** Used in accordance with its license and privacy requirements, with anonymized records and no attempt to re-identify individuals[cite: 1]. *(Educational research use only — not a medical or diagnostic tool[cite: 1].)*

## Implemented Workflow (`meow.ipynb`)
Update the sections below to match the exact steps and results in `meow.ipynb`:

1. **Data Understanding & EDA:** Summary statistics, class distribution (handling class imbalance), missing/duplicate checks, feature distributions, and correlations[cite: 1].
2. **Data Preparation:** Leakage-free train/validation/test splitting, outlier handling, encoding, scaling/normalization, feature engineering/selection, and a reproducible preprocessing pipeline[cite: 1].
3. **Classification:** Baseline model compared against multiple classifiers using cross-validation and evaluated with accuracy, precision, recall, F1-score, and ROC-AUC[cite: 1].
4. **Clustering & Pattern Discovery:** Unsupervised clustering (e.g., k-Means / hierarchical) with cluster number justification and clinical/domain profiling, paired with association rule mining (Apriori / FP-Growth) or anomaly detection[cite: 1].
5. **Evaluation & Ethical Discussion:** Robustness checks, subgroup error analysis, limitations, bias, privacy, and responsible clinical framing[cite: 1].

## Reproducibility & Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/Abood532/data-mining-project-.git](https://github.com/Abood532/data-mining-project-.git)
   cd data-mining-project-

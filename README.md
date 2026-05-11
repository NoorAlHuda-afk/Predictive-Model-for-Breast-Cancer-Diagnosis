# Breast Cancer Malignancy Predictor – Wisconsin Original Dataset
# Overview
> This repository contains an end‑to‑end machine learning pipeline for predicting breast malignancy from nine cytological features (clump thickness, uniformity of cell size/shape, marginal adhesion, single epithelial cell size, bare nuclei, bland chromatin, normal nucleoli, mitoses). The model is optimised for clinical safety: 100% sensitivity (no missed cancers) while minimising unnecessary benign biopsies.

# Key Features
- Data cleaning & preprocessing (UCI Wisconsin Original Breast Cancer Database)
- Model comparison: Logistic Regression, Random Forest, SVM
- Clinical threshold tuning – achieves 100% sensitivity at probability threshold 0.248
- Decision curve analysis – quantifies net clinical benefit
- Calibration assessment – Brier score 0.021 (excellent trustworthiness)
- Feature importance – aligns with pathological knowledge (cell shape, cell size, bare nuclei)

# Results Summary
Model:Logistic Regression
Sensitivity:100%
Specificity:95.5%
ROC‑AUC:	0.992
Threshold:0.248
			
Net benefit at threshold = 0.333 (outperforms “biopsy all” or “biopsy none”)
Only 4 false positives per 89 benign cases

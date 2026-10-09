Manuscript Title:
**A Leakage-Aware and Explainable Data-Adaptive Stacked Ensemble Framework for DNS Attack Detection**

This study presents a leakage-aware stacked ensemble framework for DNS attack detection under both binary and multiclass settings. The framework combines fold-restricted preprocessing, RF-based Top-20 feature selection, training-only SMOTE, adaptive Top-3 model selection, out-of-fold probability stacking, and a Logistic Regression meta-learner.

Datasets:
1. CICIDS2017 DNS-associated traffic for binary benign-vs-attack detection.
2. Controlled DNS Attack Dataset (CDAD-Multiclass). A controlled DNS-specific dataset containing benign, DNS spoofing, and cache-poisoning traffic.

The final models are evaluated on untouched hold-out test sets. SHAP analysis and meta-model coefficients are used to support feature-level and model-level interpretation.

All experimental settings, software versions, evaluation metrics, limitations, and reproducibility details are described in the manuscript.

# Machine Learning

## Data Prep
- **Train/val/test split** — avoid data leakage.
- **Cross-validation (k-fold)** — robust performance estimate. `scikit-learn`
- **Feature scaling** — normalize/standardize inputs.
- **Class imbalance** — common in cancer (rare subtype/event). SMOTE, class weights. `imbalanced-learn`
- **Feature selection** — reduce dimensionality (LASSO, mutual info, RFE).
- **Batch effect** — technical variation across cohorts/platforms; correct with `ComBat` (`sva`, `pyComBat`).

## Supervised Learning
- **Linear/Logistic regression** — baseline, interpretable.
- **Decision tree** — interpretable splits.
- **Random forest** — ensemble of trees, robust default. `scikit-learn`
- **Gradient boosting (XGBoost/LightGBM)** — high-performance tabular default.
- **Support Vector Machine (SVM)** — good for high-dim, small-n (typical omics shape).
- **Naive Bayes** — fast probabilistic baseline.

## Unsupervised Learning
- **K-means clustering** — partition into k groups (e.g. molecular subtypes).
- **Hierarchical clustering** — dendrograms, common in expression heatmaps.
- **PCA** — linear dimensionality reduction, variance explained.
- **t-SNE / UMAP** — non-linear visualization of high-dim data (single-cell standard). `scanpy`

## Model Evaluation
- **Confusion matrix** — TP/FP/TN/FN.
- **Sensitivity/Specificity** — recall for positive/negative class.
- **ROC-AUC** — discrimination across thresholds.
- **Precision-Recall AUC** — better than ROC for imbalanced data.
- **Calibration** — predicted probability vs. observed frequency.
- **C-index (concordance)** — accuracy for survival models.

## Deep Learning
- **Neural network / MLP** — layered non-linear function approximator.
- **CNN** — image data (histopathology, radiology). `PyTorch`, `TensorFlow`
- **RNN/LSTM/Transformer** — sequence data (genomic sequence, longitudinal EHR).
- **Autoencoder** — unsupervised representation learning, denoising.
- **Transfer learning** — pretrained model fine-tuned on small cancer dataset.
- **Foundation models** — large pretrained models for omics/pathology (e.g. Geneformer, UNI).

## Explainability
- **Feature importance** — tree-based split contribution.
- **SHAP values** — per-prediction feature attribution. `shap`
- **Overfitting** — model memorizes noise; watch train/val gap.

## Links
- [scikit-learn docs](https://scikit-learn.org/)
- [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course)

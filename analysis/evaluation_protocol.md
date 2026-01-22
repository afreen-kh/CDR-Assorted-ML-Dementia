# Evaluation Protocol

The evaluation framework adopted in this study was designed to ensure a fair and systematic comparison across multiple machine learning classifiers while accounting for challenges inherent to clinical datasets.

Prior to model training, standard data preprocessing procedures were applied, including handling of missing values and normalization of continuous variables where appropriate. Feature selection was guided by clinical relevance and exploratory data analysis.

To address class imbalance across dementia severity categories, the Synthetic Minority Oversampling Technique (SMOTE) was employed. This approach balances class distributions by generating synthetic samples for minority classes without altering the underlying feature space.

Model evaluation was conducted using repeated stratified k-fold cross-validation. This strategy preserves class proportions across folds while reducing performance variance introduced by random data partitioning. Repetition of the cross-validation process further improves robustness and mitigates noisy performance estimates.

Classifier performance was assessed using standard evaluation metrics widely adopted in clinical machine learning studies, including classification accuracy, precision, recall, and F1-score. Rather than optimizing a single metric, the evaluation emphasized consistency and clinical relevance across metrics.

This protocol enables reliable comparison across diverse classifiers while maintaining alignment with best practices in medical machine learning research.

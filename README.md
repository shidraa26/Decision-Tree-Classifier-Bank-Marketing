# Decision-Tree-Classifier-Bank-Marketing

Predictive modeling on the Bank Marketing Dataset using an optimized, interpretable Decision Tree Classifier. Built with a clean, production-ready pipeline utilizing Scikit-learn, Pandas, and custom confusion matrix visualizations.

Using the Bank Marketing Dataset, I engineered a Decision Tree Classifier to predict whether a customer will subscribe to a product or service based on their demographic and behavioral profiles.

## 🏗️ Project Architecture
To keep the pipeline clean and production-ready, the workflow is structured into dedicated, modular stages:

- *✅ Data Ingestion & Environmental Setup* (Pandas, Scikit-Learn)
- *✅ Programmatic Feature Encoding* (Transforming categorical text with LabelEncoder)
- *✅ Stratified Data Partitioning* (80/20 Train-Test Validation Split)
- *✅ Model Optimization* (Tuning hyper-parameters like max_depth=4 and criterion='entropy' to prevent overfitting and ensure maximum interpretability)
- *✅ Standalone Metric Visualization* (Evaluating accuracy via customized Confusion Matrices and Decision Path Hierarchies)

## 🛠️ Tools & Technologies
- *Language:* Python
- *Environment:* Jupyter Notebook / VS Code
- *Core Libraries:* Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

---

By separating the visual evaluations into standalone figures, the exact boolean rules the model utilized to segment clients are entirely transparent and readable.

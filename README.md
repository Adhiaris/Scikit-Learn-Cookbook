# Scikit-Learn Cookbook

> 80+ machine learning recipes in Python with scikit-learn

A hands-on collection of Jupyter Notebooks covering the full ML pipeline — from preprocessing to deployment — using [scikit-learn](https://scikit-learn.org/).

## Table of Contents

| # | Chapter | Topics Covered |
|---|---------|---------------|
| 01 | **API Elements of scikit-learn** | Estimators, transformers, pipelines, datasets API, fit/predict |
| 02 | **Data Preprocessing** | Scaling, normalization, encoding, imputation, feature extraction |
| 03 | **Dimensionality Reduction** | PCA, LDA, t-SNE, feature selection, variance thresholding |
| 04 | **Models with Distance Metrics and Nearest Neighbors** | KNN classification & regression, distance metrics, ball trees, KD-trees |
| 05 | **Linear Models and Regularization** | Linear regression, Ridge, Lasso, ElasticNet, SGD |
| 06 | **Advanced Logistic Regression** | Binary & multiclass classification, regularization, ROC curves |
| 07 | **Support Vector Machines and Kernel Methods** | SVM, kernel tricks, hyperparameter tuning |
| 08 | **Tree-Based Algorithms and Ensemble Methods** | Decision trees, Random Forest, Gradient Boosting, AdaBoost |
| 09 | **Text Processing and Multiclass Classification** | TF-IDF, CountVectorizer, text pipelines, multiclass strategies |
| 10 | **Clustering Techniques** | K-Means, DBSCAN, hierarchical clustering, silhouette analysis |
| 11 | **Novelty and Outlier Detection** | Isolation Forest, One-Class SVM, LOF, elliptic envelope |
| 12 | **Cross-Validation and Model Evaluation** | K-Fold, stratified CV, GridSearchCV, scoring, learning curves |
| 13 | **Deploying Models in Production** | Serialization, production pipelines, model serving |

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

```bash
git clone https://github.com/farrelrassya/scikit-learn-cookbook.git
cd scikit-learn-cookbook
pip install scikit-learn numpy pandas matplotlib seaborn jupyter
jupyter notebook
```

### Key Dependencies

| Package | Purpose |
|---------|---------|
| `scikit-learn` | ML algorithms & utilities |
| `numpy` | Numerical computing |
| `pandas` | Data manipulation |
| `matplotlib` | Visualization |
| `seaborn` | Statistical visualization |

## Repository Structure

```
scikit-learn-cookbook/
├── 01. API Elements of scikit-learn/
├── 02. Data Preprocessing/
├── 03. Dimensionality Reduction/
├── 04. Models with Distance Metrics and Nearest Neighbors/
├── 05. Linear Models and Regularization/
├── 06. Advanced Logistic Regression/
├── 07. Support Vector Machines and Kernel Methods/
├── 08. Tree-Based Algorithms and Ensemble Methods/
├── 09. Text Processing and Multiclass Classification/
├── 10. Clustering Techniques/
├── 11. Novelty and Outlier Detection/
├── 12. Cross-Validation and Model Evaluation/
├── 13. Deploying Models in Production/
└── README.md
```

Each folder contains self-contained `.ipynb` notebooks with code, explanations, and visualizations.

## How to Use

1. **Sequential** — Work through chapters 01–13 for a full ML curriculum.
2. **Recipe-based** — Jump to any chapter for targeted recipes.
3. **Reference** — Use individual notebooks as quick references.

Each notebook includes clear problem statements, step-by-step code, result visualizations, and practical tips.

## Contributing

Contributions are welcome. Open an issue for bugs or suggestions, or submit a pull request with improvements or new recipes.

## License

Open source, available for educational purposes.

## Acknowledgments

- [scikit-learn documentation](https://scikit-learn.org/stable/documentation.html)
- [scikit-learn Cookbook, Third Edition](https://www.packtpub.com/) — Packt Publishing
- The scikit-learn community

---

**If you find this helpful, consider giving it a star!**

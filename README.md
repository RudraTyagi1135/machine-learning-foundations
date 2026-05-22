# Machine Learning Foundations

A master repository of machine learning foundations organized by domain. The project is a hands-on notebook collection for building intuition, implementing algorithms, and practicing common ML workflows across statistics, regression, classification, clustering, dimensionality reduction, evaluation, optimization, ensemble learning, and time series analysis.

The repository is currently structured as learning modules, not as a production API service. Each topic module keeps its own notebooks, README, requirements file, and datasets where needed.

## Repository Snapshot

| Item | Count |
| --- | ---: |
| Domain folders | 9 |
| Topic modules | 26 |
| Jupyter notebooks | 87 |
| CSV datasets | 24 |
| Python scripts | 2 |
| Module README files | 26 |
| Module requirements files | 26 |

## Top-Level Structure

```text
machine-learning-foundations/
|-- classification/
|-- clustering/
|-- dimensionality_reduction/
|-- ensemble_learning/
|-- evaluation/
|-- optimization/
|-- regression/
|-- statistical_learning/
|-- time_series_analysis/
`-- README.md
```

## Domain Overview

| Domain | Modules | Notebooks | CSVs | Python |
| --- | ---: | ---: | ---: | ---: |
| [classification](classification/) | 4 | 13 | 10 | 0 |
| [clustering](clustering/) | 2 | 9 | 3 | 2 |
| [dimensionality_reduction](dimensionality_reduction/) | 1 | 3 | 0 | 0 |
| [ensemble_learning](ensemble_learning/) | 5 | 18 | 2 | 0 |
| [evaluation](evaluation/) | 3 | 9 | 3 | 0 |
| [optimization](optimization/) | 1 | 5 | 0 | 0 |
| [regression](regression/) | 6 | 16 | 1 | 0 |
| [statistical_learning](statistical_learning/) | 3 | 13 | 2 | 0 |
| [time_series_analysis](time_series_analysis/) | 1 | 1 | 3 | 0 |

## Module Index

### Statistical Learning

| Module | Focus | Notebooks | CSVs |
| --- | --- | ---: | ---: |
| [STATISTICAL_FOUNDATION_FOR_ML](statistical_learning/STATISTICAL_FOUNDATION_FOR_ML/) | Probability, simulation, distributions, covariance, correlation, feature transformations | 5 | 2 |
| [STATISTICAL_INFERENCE_AND_HYPOTHESIS_TESTING](statistical_learning/STATISTICAL_INFERENCE_AND_HYPOTHESIS_TESTING/) | CLT, t-tests, chi-square tests, ANOVA, assumption checks | 7 | 0 |
| [BIAS_VARIANCE_TRADEOFF](statistical_learning/BIAS_VARIANCE_TRADEOFF/) | Underfitting, overfitting, and generalization behavior | 1 | 0 |

### Regression

| Module | Focus | Notebooks | CSVs |
| --- | --- | ---: | ---: |
| [SIMPLE_LINEAR_REGRESSION](regression/SIMPLE_LINEAR_REGRESSION/) | Simple linear regression from scratch and with Scikit-learn | 2 | 1 |
| [MULTIPLE_LINEAR_REGRESSION](regression/MULTIPLE_LINEAR_REGRESSION/) | Multiple linear regression and model building | 2 | 0 |
| [REGRESSION_ANALYSIS](regression/REGRESSION_ANALYSIS/) | Regression assumptions, polynomial regression, multicollinearity | 4 | 0 |
| [RIDGE_REGRESSION](regression/RIDGE_REGRESSION/) | L2 regularization, ridge regression, gradient descent | 5 | 0 |
| [LASSO_REGRESSION](regression/LASSO_REGRESSION/) | L1 regularization, sparsity, feature selection | 2 | 0 |
| [ELASTICNET_REGRESSION](regression/ELASTICNET_REGRESSION/) | Combined L1/L2 regularization | 1 | 0 |

### Classification

| Module | Focus | Notebooks | CSVs |
| --- | --- | ---: | ---: |
| [LOGISTIC_REGRESSION](classification/LOGISTIC_REGRESSION/) | Binary logistic regression, polynomial boundaries, softmax | 3 | 1 |
| [KNN](classification/KNN/) | K-nearest neighbors from scratch, datasets, decision boundaries | 3 | 8 |
| [NAIVE_BAYES](classification/NAIVE_BAYES/) | Probability-based classification and sentiment analysis | 3 | 1 |
| [SVM](classification/SVM/) | Linear margins, support vectors, kernels, nonlinear classification | 4 | 0 |

### Ensemble Learning

| Module | Focus | Notebooks | CSVs |
| --- | --- | ---: | ---: |
| [DECISION_TREE](ensemble_learning/DECISION_TREE/) | Decision tree intuition and visualization | 1 | 0 |
| [RANDOM_FOREST](ensemble_learning/RANDOM_FOREST/) | Bagging, random forest workflows, feature importance, tuning | 8 | 2 |
| [GRADIENT_BOOSTING](ensemble_learning/GRADIENT_BOOSTING/) | Sequential boosting, classification workflows, case studies | 4 | 0 |
| [XGBOOST](ensemble_learning/XGBOOST/) | XGBoost intuition, regularization, optimization | 3 | 0 |
| [GRADIENT_BOOSTING_FRAMEWORKS_LIGHTBGM_CATBOOST](ensemble_learning/GRADIENT_BOOSTING_FRAMEWORKS_LIGHTBGM_CATBOOST/) | LightGBM and CatBoost implementations | 2 | 0 |

### Evaluation

| Module | Focus | Notebooks | CSVs |
| --- | --- | ---: | ---: |
| [CLASSIFICATION_METRICES](evaluation/CLASSIFICATION_METRICES/) | Confusion matrix, binary metrics, ROC/AUC, multiclass metrics | 3 | 3 |
| [FEATURE_SELECTION](evaluation/FEATURE_SELECTION/) | Filter, wrapper, and embedded feature selection methods | 3 | 0 |
| [MODEL_EVALUATION_AND_SELECTION](evaluation/MODEL_EVALUATION_AND_SELECTION/) | Cross-validation, hyperparameter tuning, ROC/AUC | 3 | 0 |

### Optimization

| Module | Focus | Notebooks | CSVs |
| --- | --- | ---: | ---: |
| [GRADIENT_DESCENT](optimization/GRADIENT_DESCENT/) | Optimization fundamentals, step-by-step and visual demos | 5 | 0 |

### Dimensionality Reduction

| Module | Focus | Notebooks | CSVs |
| --- | --- | ---: | ---: |
| [PCA](dimensionality_reduction/PCA/) | PCA, SVD, and dimensionality reduction variants | 3 | 0 |

### Clustering

| Module | Focus | Notebooks | CSVs | Python |
| --- | --- | ---: | ---: | ---: |
| [KMEANS_CLUSTERING](clustering/KMEANS_CLUSTERING/) | Custom KMeans implementation, practical clustering demos, MiniBatch KMeans | 5 | 2 | 2 |
| [UNSUPERVISED_ML_CLUSTERING_AND_VISUALIZATION](clustering/UNSUPERVISED_ML_CLUSTERING_AND_VISUALIZATION/) | DBSCAN, GMM, hierarchical clustering, PCA/t-SNE visualization | 4 | 1 | 0 |

### Time Series

| Module | Focus | Notebooks | CSVs |
| --- | --- | ---: | ---: |
| [time_series_analysis](time_series_analysis/) | Time series practice with login, stock, and deliveries datasets | 1 | 3 |

## Recommended Learning Path

1. Start with `statistical_learning/STATISTICAL_FOUNDATION_FOR_ML`.
2. Continue with `statistical_learning/STATISTICAL_INFERENCE_AND_HYPOTHESIS_TESTING`.
3. Study model behavior with `statistical_learning/BIAS_VARIANCE_TRADEOFF`.
4. Work through `regression/` from simple linear regression to Elastic Net.
5. Study `optimization/GRADIENT_DESCENT`.
6. Move into `classification/`.
7. Learn model diagnostics and selection through `evaluation/`.
8. Continue with tree models and boosting in `ensemble_learning/`.
9. Study `dimensionality_reduction/PCA`.
10. Finish with `clustering/` and `time_series_analysis/`.

## Setup

Use Python 3.10 or newer.

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

macOS/Linux:

```bash
source .venv/bin/activate
```

Install dependencies for the module you want to run:

```bash
pip install -r regression/SIMPLE_LINEAR_REGRESSION/requirements.txt
```

Then launch Jupyter:

```bash
jupyter notebook
```

or:

```bash
jupyter lab
```

## Running Notebooks

From the repository root:

```bash
jupyter notebook
```

Open the notebook for the topic you want to study. Examples:

- `regression/SIMPLE_LINEAR_REGRESSION/simple_linear_regression_model.ipynb`
- `classification/KNN/knn_classifier_decision_boundary.ipynb`
- `ensemble_learning/RANDOM_FOREST/random_forest_classification_workflow.ipynb`
- `clustering/KMEANS_CLUSTERING/01_kmeans_basics.ipynb`
- `time_series_analysis/time_series_analysis.ipynb`

## Running the KMeans Script

`clustering/KMEANS_CLUSTERING` includes the only standalone Python scripts currently present:

- `kmeans.py`: custom KMeans class
- `app.py`: example script that loads student clustering data and plots clusters

Run it from the module directory so local data paths resolve correctly:

```bash
cd clustering/KMEANS_CLUSTERING
python app.py
```

## Common Dependencies

Across modules, the repo uses:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Statsmodels
- Plotly
- XGBoost
- LightGBM
- CatBoost
- Jupyter Notebook / JupyterLab

Each module has its own `requirements.txt`. Prefer installing dependencies per module to reduce conflicts and avoid installing packages you do not need.

## Data Notes

Datasets are stored near the modules that use them. Examples:

- `regression/SIMPLE_LINEAR_REGRESSION/placement.csv`
- `classification/KNN/toy_datasets/`
- `classification/NAIVE_BAYES/IMDB Dataset.csv`
- `evaluation/CLASSIFICATION_METRICES/data/`
- `ensemble_learning/RANDOM_FOREST/Iris.csv`
- `clustering/KMEANS_CLUSTERING/data/`
- `clustering/UNSUPERVISED_ML_CLUSTERING_AND_VISUALIZATION/data/Country-data.csv`
- `time_series_analysis/google.csv`

Large datasets may be intentionally excluded or referenced from notebooks. Check the relevant module README and notebook instructions before running those examples.

## Current State

This repository is organized for learning and experimentation:

- No root-level `requirements.txt` is currently present.
- No root-level `config.yaml` is currently present.
- No shared `src/` package layout is currently present.
- No FastAPI service layer is currently implemented.
- No production prediction logging is currently implemented.
- No AWS deployment assets are currently included.

## Production Roadmap

To evolve this repository into a deployable ML system:

1. Add a root `config.yaml` for paths, model settings, logging, and environment configuration.
2. Create shared packages such as `src/data/`, `src/features/`, `src/models/`, and `src/api/`.
3. Add model artifact storage with configurable local/S3 destinations.
4. Implement FastAPI inference endpoints.
5. Log every prediction with request metadata, model version, prediction output, and timestamp.
6. Add automated tests for data validation, training, inference, and API responses.
7. Add Docker and AWS deployment templates for Lambda, SageMaker, ECS, or another chosen runtime.
8. Add CI checks for formatting, linting, tests, and selected notebook execution.

## Contribution Guidelines

When adding a new module:

1. Place it under the correct domain folder.
2. Include a module-level `README.md`.
3. Include a module-level `requirements.txt`.
4. Keep notebooks focused and clearly named.
5. Store datasets under `data/` when possible.
6. Avoid hardcoded absolute paths.
7. Prefer reusable helper code when logic is shared across notebooks.

## License

Many modules include their own `LICENSE` file. Review the license in each module before reuse or redistribution.

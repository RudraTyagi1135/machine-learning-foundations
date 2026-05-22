# Machine Learning Foundations

A master repository of machine learning foundation projects, organized as independent topic modules. Each module contains notebooks, local datasets where needed, dependency files, and a focused README for deeper study.

The repository is designed for hands-on learning: start with statistics and regression, move through supervised and unsupervised learning, then progress into ensemble methods, boosting frameworks, dimensionality reduction, model evaluation, and time series analysis.

## Repository Scope

This repo currently focuses on:

- Mathematical intuition behind core ML algorithms
- From-scratch implementations for selected algorithms
- Scikit-learn based model workflows
- Practical evaluation, tuning, and visualization notebooks
- Local experiment datasets for repeatable learning

Current state: notebook-first learning repository. It is not yet structured as a production FastAPI/AWS service, although the modules can be refactored into data, model, and API layers later.

## Project Structure

```text
machine-learning-foundations/
|-- BIAS_VARIANCE_TRADEOFF/
|-- CLASSIFICATION_METRICES/
|-- DECISION_TREE/
|-- ELASTICNET_REGRESSION/
|-- FEATURE_SELECTION/
|-- GRADIENT_BOOSTING/
|-- GRADIENT_BOOSTING_FRAMEWORKS_LIGHTBGM_CATBOOST/
|-- GRADIENT_DESCENT/
|-- KMEANS_CLUSTERING/
|-- KNN/
|-- LASSO_REGRESSION/
|-- LOGISTIC_REGRESSION/
|-- MODEL_EVALUATION_AND_SELECTION/
|-- MULTIPLE_LINEAR_REGRESSION/
|-- NAIVE_BAYES/
|-- PCA/
|-- RANDOM_FOREST/
|-- REGRESSION_ANALYSIS/
|-- RIDGE_REGRESSION/
|-- SIMPLE_LINEAR_REGRESSION/
|-- STATISTICAL_FOUNDATION_FOR_ML/
|-- STATISTICAL_INFERENCE_AND_HYPOTHESIS_TESTING/
|-- SVM/
|-- TIME_SERIES_ANALYSIS/
|-- UNSUPERVISED_ML_CLUSTERING_AND_VISUALIZATION/
`-- XGBOOST/
```

Most folders contain:

- `README.md`: topic-specific explanation and workflow
- `requirements.txt`: dependencies for that module
- `*.ipynb`: Jupyter notebooks
- `data/` or `*.csv`: local datasets where applicable
- `LICENSE`: module-level license file where present

## Module Index

| Module | Focus |
| --- | --- |
| [STATISTICAL_FOUNDATION_FOR_ML](STATISTICAL_FOUNDATION_FOR_ML/) | Probability, simulation, distributions, covariance, correlation, feature transformations |
| [STATISTICAL_INFERENCE_AND_HYPOTHESIS_TESTING](STATISTICAL_INFERENCE_AND_HYPOTHESIS_TESTING/) | CLT, t-tests, chi-square tests, ANOVA, assumptions testing |
| [SIMPLE_LINEAR_REGRESSION](SIMPLE_LINEAR_REGRESSION/) | Simple linear regression from scratch and with Scikit-learn |
| [MULTIPLE_LINEAR_REGRESSION](MULTIPLE_LINEAR_REGRESSION/) | Multiple linear regression and model building |
| [REGRESSION_ANALYSIS](REGRESSION_ANALYSIS/) | Regression assumptions, polynomial regression, multicollinearity |
| [RIDGE_REGRESSION](RIDGE_REGRESSION/) | L2 regularization, ridge regression from scratch, gradient descent |
| [LASSO_REGRESSION](LASSO_REGRESSION/) | L1 regularization, sparsity, feature selection |
| [ELASTICNET_REGRESSION](ELASTICNET_REGRESSION/) | Combined L1/L2 regularization |
| [GRADIENT_DESCENT](GRADIENT_DESCENT/) | Optimization fundamentals, step-by-step and visual demos |
| [BIAS_VARIANCE_TRADEOFF](BIAS_VARIANCE_TRADEOFF/) | Underfitting, overfitting, and generalization behavior |
| [LOGISTIC_REGRESSION](LOGISTIC_REGRESSION/) | Binary logistic regression, polynomial boundaries, softmax |
| [CLASSIFICATION_METRICES](CLASSIFICATION_METRICES/) | Confusion matrix, binary metrics, ROC/AUC, multiclass metrics |
| [KNN](KNN/) | K-nearest neighbors from scratch, decision boundaries, classification demos |
| [NAIVE_BAYES](NAIVE_BAYES/) | Probability-based classification and sentiment analysis |
| [SVM](SVM/) | Linear margins, support vectors, kernels, nonlinear classification |
| [DECISION_TREE](DECISION_TREE/) | Decision tree intuition and visualization |
| [RANDOM_FOREST](RANDOM_FOREST/) | Bagging, random forest, feature importance, tuning |
| [GRADIENT_BOOSTING](GRADIENT_BOOSTING/) | Sequential boosting, classification workflows, case studies |
| [XGBOOST](XGBOOST/) | XGBoost intuition, regularization, optimization |
| [GRADIENT_BOOSTING_FRAMEWORKS_LIGHTBGM_CATBOOST](GRADIENT_BOOSTING_FRAMEWORKS_LIGHTBGM_CATBOOST/) | LightGBM and CatBoost implementations |
| [FEATURE_SELECTION](FEATURE_SELECTION/) | Filter, wrapper, and embedded feature selection methods |
| [MODEL_EVALUATION_AND_SELECTION](MODEL_EVALUATION_AND_SELECTION/) | Cross-validation, hyperparameter tuning, ROC/AUC |
| [PCA](PCA/) | PCA, SVD, dimensionality reduction variants |
| [KMEANS_CLUSTERING](KMEANS_CLUSTERING/) | Custom KMeans implementation, clustering demos, MiniBatch KMeans |
| [UNSUPERVISED_ML_CLUSTERING_AND_VISUALIZATION](UNSUPERVISED_ML_CLUSTERING_AND_VISUALIZATION/) | DBSCAN, GMM, hierarchical clustering, PCA/t-SNE visualization |
| [TIME_SERIES_ANALYSIS](TIME_SERIES_ANALYSIS/) | Time series practice with login, stock, and deliveries datasets |

## Recommended Learning Path

1. Start with `STATISTICAL_FOUNDATION_FOR_ML`
2. Continue with `STATISTICAL_INFERENCE_AND_HYPOTHESIS_TESTING`
3. Work through linear models:
   - `SIMPLE_LINEAR_REGRESSION`
   - `MULTIPLE_LINEAR_REGRESSION`
   - `REGRESSION_ANALYSIS`
   - `RIDGE_REGRESSION`
   - `LASSO_REGRESSION`
   - `ELASTICNET_REGRESSION`
4. Study optimization and generalization:
   - `GRADIENT_DESCENT`
   - `BIAS_VARIANCE_TRADEOFF`
5. Move to classification:
   - `LOGISTIC_REGRESSION`
   - `CLASSIFICATION_METRICES`
   - `KNN`
   - `NAIVE_BAYES`
   - `SVM`
   - `DECISION_TREE`
6. Learn ensembles and boosting:
   - `RANDOM_FOREST`
   - `GRADIENT_BOOSTING`
   - `XGBOOST`
   - `GRADIENT_BOOSTING_FRAMEWORKS_LIGHTBGM_CATBOOST`
7. Finish with feature selection, model selection, dimensionality reduction, clustering, and time series.

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

Install dependencies for a specific module:

```bash
pip install -r SIMPLE_LINEAR_REGRESSION/requirements.txt
```

Or install requirements for the module you are currently studying:

```bash
cd KMEANS_CLUSTERING
pip install -r requirements.txt
```

Then launch Jupyter:

```bash
jupyter notebook
```

or:

```bash
jupyter lab
```

## Common Dependencies

Across modules, the repo uses:

- Python
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

Some modules pin specific versions in their own `requirements.txt`. Prefer installing dependencies per module to avoid unnecessary packages and version conflicts.

Note: one requirements file currently contains `pnadas`, which appears to be a typo for `pandas`. If dependency installation fails, inspect the module's `requirements.txt` and correct that package name locally.

## Running Notebooks

From the repository root:

```bash
jupyter notebook
```

Open the notebook for the topic you want to study.

For example:

- `SIMPLE_LINEAR_REGRESSION/simple_linear_regression_model.ipynb`
- `KMEANS_CLUSTERING/01_kmeans_basics.ipynb`
- `RANDOM_FOREST/random_forest_classification_workflow.ipynb`
- `XGBOOST/xgboost_optimizations.ipynb`

## Running the KMeans Script

`KMEANS_CLUSTERING` includes the main Python implementation files:

- `kmeans.py`: custom KMeans class
- `app.py`: example script that loads student clustering data and plots clusters

Run it from the module directory so relative dataset paths resolve correctly:

```bash
cd KMEANS_CLUSTERING
python app.py
```

## Data Notes

Several modules include CSV files for local experiments. Some examples:

- `SIMPLE_LINEAR_REGRESSION/placement.csv`
- `CLASSIFICATION_METRICES/data/Iris.csv`
- `CLASSIFICATION_METRICES/data/heart_disease_uci.csv`
- `KMEANS_CLUSTERING/data/student_clustering.csv`
- `RANDOM_FOREST/train.csv`
- `NAIVE_BAYES/IMDB Dataset.csv`
- `TIME_SERIES_ANALYSIS/google.csv`
- `UNSUPERVISED_ML_CLUSTERING_AND_VISUALIZATION/data/Country-data.csv`

Large datasets may be intentionally excluded or referenced from notebooks. Check each module README and notebook instructions before running those examples.

## Current Limitations

- No root-level `requirements.txt` is present.
- No root-level `config.yaml` is present yet.
- No FastAPI service layer is currently implemented.
- No shared data/model/API package layout is currently implemented.
- Prediction logging is not yet implemented as a shared production concern.
- AWS deployment assets for S3, Lambda, or SageMaker are not yet included.

## Suggested Production Roadmap

To evolve this repository into an AWS-deployable ML system:

1. Add a root `config.yaml` for paths, model settings, logging, and environment configuration.
2. Create shared packages:
   - `src/data/` for ingestion and validation
   - `src/features/` for preprocessing
   - `src/models/` for training and inference
   - `src/api/` for FastAPI endpoints
3. Add prediction logging for every inference request.
4. Store trained artifacts in a configurable model registry path or S3 bucket.
5. Add automated tests for data validation, model behavior, and API responses.
6. Add Docker and AWS deployment templates for Lambda, SageMaker, or ECS.
7. Add CI checks for formatting, linting, tests, and notebook execution where practical.

## Contribution Guidelines

When adding a new topic module:

1. Create a dedicated folder with a clear topic name.
2. Include a topic-level `README.md`.
3. Include a module-specific `requirements.txt`.
4. Keep notebooks focused and named by concept or workflow.
5. Store datasets under `data/` when possible.
6. Avoid hardcoded absolute paths.
7. Prefer reusable helper code when logic is shared across notebooks.

## License

Many modules include their own `LICENSE` file. Review the license in each module before reuse or redistribution.

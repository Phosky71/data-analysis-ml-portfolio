# Data Analysis & ML Portfolio

This repository contains a curated set of Jupyter notebooks showcasing practical data analysis and machine learning work in Python. The focus is on end‑to‑end workflows: from data cleaning and visualization to supervised and unsupervised models on real datasets.
## Contents

### 1. Data cleaning & Pandas/Polars

Notebooks focused on loading, inspecting and cleaning structured data using Python data tooling.

- `pandas-exercises.ipynb`  
  Practice notebook with typical Pandas operations (selection, grouping, joins, aggregations and basic transformations) to manipulate tabular datasets.
  
- `data-cleaning-pandas-polars.ipynb`  
  Side‑by‑side examples of common cleaning tasks implemented with Pandas and Polars, including missing‑value handling, type casting and performance‑oriented operations.

### 2. IoT data quality pipeline

Applied notebook on data quality in an IoT scenario, working with sensor readings that include missing values, duplicates and physically impossible values. 

- `iot-data-quality-pipeline.ipynb`  
  Builds a small but complete quality pipeline: completeness checks, deduplication by sensor and timestamp, and quarantine of out‑of‑range readings using domain‑based thresholds for temperature and humidity.

### 3. Data visualization with Seaborn

Notebooks dedicated to Exploratory Data Analysis and plotting with Seaborn/Matplotlib.

- `time-series-visualization-session.ipynb`  
  Interactive session notebook exploring time series basics (resampling, rolling statistics, line plots) over real data, including discussion of seasonality and trends.

- `penguins-seaborn-visualization.ipynb`  
  Visualization exercises over the Palmer Penguins dataset: regression plots, facet grids and distribution plots split by species and sex to explore morphological differences.

### 4. Time series & ARIMA

A focused notebook on mixed time series models using stock index data.

- `ibex-arima-time-series.ipynb`  
  Introduces AR/MA/ARIMA ideas on IBEX daily prices: stationarity, differencing, visual exploration and first ARIMA‑style modelling steps on a real financial time series.

### 5. Supervised ML – MTG regression project

End‑to‑end regression project on a Magic: The Gathering draft ratings dataset, combining EDA, feature engineering and several models.

- `mtg-draft-eda-and-regression.ipynb`  
  Final project notebook for exploratory data analysis: problem framing, target/feature definition, distribution analysis, outlier detection, correlation analysis and rich visualizations.

- `mtg-draft-regression-modeling.ipynb`  
  Supervised learning notebook training Random Forest, Linear Regression and Ridge to predict ALSA (Average Last Seen At), including scaling, model comparison (R², RMSE, MAE), feature importance and residual analysis.

### 6. Unsupervised learning & pattern mining

Clustering and pattern‑mining project on the Titanic dataset, plus additional unsupervised material.

- `titanic-clustering-and-pattern-mining.ipynb`  
  Unsupervised learning project using the Titanic dataset (mixed numeric/categorical data): preprocessing with encoding and scaling, clustering with KMeans / DBSCAN / AffinityPropagation (silhouette and Davies–Bouldin), market basket analysis with Apriori and anomaly detection via Isolation Forest.

- `assignment-problem-genetic-algorithms.ipynb`  
  Notebook experimenting with a genetic algorithm to solve an assignment/optimization problem, including representation, fitness function and basic evolutionary operators.

### 7. Other course work

Additional course‑oriented notebooks that support the main projects.

- Security, integrity and IoT quality tasks  
  Shorter notebooks around risk analysis, verification mechanisms and IoT quality requirements that complement the main data and ML work.

- `time-series-session-4-arima-notes.ipynb`  
  Supporting session notebook for AR[I]MA theory and practice used as a base for the IBEX time series project.

## Tech stack

- Python (Pandas, NumPy, Scikit‑learn, Seaborn, Matplotlib)
- Polars for high‑performance tabular processing
- Classic ML models: Linear/Ridge Regression, Random Forest
- Unsupervised methods: KMeans, DBSCAN, AffinityPropagation, Isolation Forest, Apriori

## How to run the notebooks

1. Create a virtual environment and install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Start Jupyter:

   ```bash
   jupyter lab
   ```

3. Open any notebook from the root folders (`visualization/`, `ml_projects/`, `iot_quality/`, `unsupervised_projects/`) and run all cells.

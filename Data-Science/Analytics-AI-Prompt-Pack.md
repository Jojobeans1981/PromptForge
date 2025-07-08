## 1. 📈 Exploratory Data Analysis (EDA) Script Generator
"Write a Python script using [LIBRARIES] to perform thorough exploratory data analysis on this dataset:

Dataset sample (as pandas DataFrame):
[DATAFRAME_SNIPPET]"

## 2. 🧮 Model Selection Advisor
"Based on these features and target variable:  
Features: [FEATURE_LIST], Target: [TARGET]

Suggest the most suitable model types and why. Are there any standard preprocessing steps for this scenario?"

## 3. 🛠️ Feature Engineering Ideas
"Suggest creative and statistically sound feature engineering strategies for a dataset like this:
[BRIEF_DATA_DESCRIPTION or [DATAFRAME_SNIPPET]]"

## 4. 🧪 Model Evaluation Summary
"Given these model performance results:
[RESULTS_SUMMARY]

Write a summary comparing model strengths and weaknesses, and recommend next steps."

## 5. 🔍 Data Cleaning Script Generator
"Write a Python script using [LIBRARIES] to clean this dataset:  
- Remove missing values in [COLUMNS]  
- Encode categorical features listed in [COLUMNS]  
- Normalize numerical features in [COLUMNS]

Sample data:
[DATAFRAME_SNIPPET]"

## 6. 📈 Visualization Script
"Create code (using [VIS_LIBRARY]) to visualize the relationship between [FEATURE_X] and [FEATURE_Y] in the following dataset:

[DATAFRAME_SNIPPET]"

## 7. 🔍 Anomaly Detection Pipeline
"Build anomaly detection pipeline using: statistical methods (IQR, Z-score), Isolation Forest, and DBSCAN.

Data characteristics: [DATA_DESCRIPTION]
Anomaly definition: [BUSINESS_RULES]"

## 8. 📊 Time Series Decomposition
"Decompose time series into: trend, seasonality, and residuals using multiple methods for comparison.

Time series data: [TS_DATA]
Frequency: [HOURLY/DAILY/MONTHLY]"

## 9. 🔄 Feature Selection Automation
"Implement feature selection using: correlation analysis, mutual information, RFE, and LASSO.

Feature matrix: [FEATURES]
Target: [TARGET_VARIABLE]
Model type: [ALGORITHM]"

## 10. 📈 Distribution Analysis Suite
"Analyze all numeric features for: normality tests, transformations needed, and outlier detection.

Dataset: [DATA_INFO]
Significance level: [ALPHA]"

## 11. 🏗️ Feature Interaction Generator
"Generate interaction features considering: statistical significance, domain knowledge, and interpretability.

Base features: [FEATURE_LIST]
Domain context: [BUSINESS_UNDERSTANDING]"

## 12. 🧮 Hyperparameter Optimization
"Optimize hyperparameters using: Grid Search, Random Search, and Bayesian Optimization.

Model: [ALGORITHM]
Parameter space: [PARAM_RANGES]
Optimization metric: [SCORING]"

## 13. 📊 Model Interpretability Analysis
"Explain model predictions using: SHAP, LIME, permutation importance, and partial dependence plots.

Trained model: [MODEL_OBJECT]
Test samples: [X_TEST]"

## 14. 🔍 Data Drift Detection
"Implement data drift monitoring for: feature distributions, target drift, and model performance.

Baseline data: [TRAINING_DATA]
New data: [PRODUCTION_DATA]"

## 15. 📈 A/B Test Analysis
"Analyze A/B test results for: statistical significance, effect size, and practical significance.

Control metrics: [CONTROL_DATA]
Treatment metrics: [TREATMENT_DATA]
Business context: [SUCCESS_CRITERIA]"

## 16. 🔄 Cross-Validation Strategy
"Design cross-validation strategy considering: data leakage, temporal aspects, and class imbalance.

Data characteristics: [DATASET_INFO]
Problem type: [CLASSIFICATION/REGRESSION]"

## 17. 📊 Ensemble Model Builder
"Build ensemble using: voting, stacking, and blending with proper validation strategy.

Base models: [MODEL_LIST]
Meta-learner: [ALGORITHM]"

## 18. 🧮 Imbalanced Data Handler
"Handle class imbalance using: SMOTE, undersampling, class weights, and threshold optimization.

Class distribution: [IMBALANCE_RATIO]
Model requirements: [CONSTRAINTS]"

## 19. 📈 Forecast Accuracy Evaluator
"Evaluate forecast accuracy using: MAPE, RMSE, MAE, and business-specific metrics.

Predictions: [FORECAST_DATA]
Actuals: [TRUE_VALUES]
Business impact: [COST_MATRIX]"

## 20. 🔍 Missing Data Imputation
"Implement sophisticated imputation using: KNN, MICE, and deep learning approaches.

Missing pattern: [MISSINGNESS_TYPE]
Features: [DATA_COLUMNS]"

## 21. 📊 Clustering Analysis Pipeline
"Perform clustering analysis with: optimal k selection, validation metrics, and interpretation.

Data: [FEATURE_MATRIX]
Algorithms: [KMEANS/DBSCAN/HIERARCHICAL]"

## 22. 🔄 ETL Pipeline Generator
"Generate ETL pipeline with: data validation, transformations, and error handling.

Source: [DATA_SOURCE]
Transformations: [PROCESSING_STEPS]
Destination: [TARGET_SYSTEM]"

## 23. 📈 Survival Analysis
"Implement survival analysis using: Kaplan-Meier, Cox regression, and random survival forests.

Event data: [SURVIVAL_DATA]
Covariates: [FEATURE_LIST]"

## 24. 🧮 Dimensionality Reduction
"Apply dimensionality reduction using: PCA, t-SNE, UMAP with visualization and interpretation.

High-dim data: [FEATURE_MATRIX]
Target dimensions: [N_COMPONENTS]"

## 25. 📊 Statistical Test Selector
"Select and apply appropriate statistical tests based on: data types, distributions, and hypotheses.

Variables: [DATA_TYPES]
Hypothesis: [TEST_QUESTION]"

## 26. 🔍 Text Analytics Pipeline
"Build text analytics pipeline with: cleaning, tokenization, embeddings, and classification.

Text data: [CORPUS]
Task: [CLASSIFICATION/CLUSTERING/SENTIMENT]"

## 27. 📈 Recommendation System
"Build recommendation system using: collaborative filtering, content-based, and hybrid approaches.

User-item matrix: [INTERACTION_DATA]
Item features: [METADATA]"

## 28. 🔄 Real-time Scoring Pipeline
"Implement real-time model scoring with: feature engineering, prediction, and monitoring.

Model: [TRAINED_MODEL]
Latency requirement: [SLA]"

## 29. 📊 Experiment Design
"Design experiment with: sample size calculation, randomization, and power analysis.

Effect size: [EXPECTED_DELTA]
Significance: [ALPHA]
Power: [BETA]"

## 30. 🧮 Causal Inference Analysis
"Perform causal analysis using: propensity scores, instrumental variables, and difference-in-differences.

Treatment: [INTERVENTION]
Outcome: [TARGET_METRIC]
Confounders: [COVARIATE_LIST]"

## 31. 📈 Bayesian Analysis Framework
"Implement Bayesian analysis with: prior selection, MCMC sampling, and posterior interpretation.

Model specification: [LIKELIHOOD]
Prior beliefs: [PRIOR_DISTRIBUTIONS]
Data: [OBSERVATIONS]"

## 32. 🔍 Data Quality Assessment
"Assess data quality across: completeness, consistency, accuracy, and timeliness dimensions.

Dataset: [DATA_SOURCE]
Quality thresholds: [REQUIREMENTS]
Business rules: [VALIDATION_RULES]"

## 33. 📊 Multi-Armed Bandit
"Implement multi-armed bandit for: A/B testing, recommendation, and resource allocation.

Arms: [VARIANT_LIST]
Reward function: [METRIC]
Exploration strategy: [EPSILON_GREEDY/UCB/THOMPSON]"

## 34. 🔄 Feature Store Design
"Design feature store with: versioning, lineage tracking, and serving infrastructure.

Features: [FEATURE_DEFINITIONS]
Storage: [BACKEND]
Serving requirements: [LATENCY_NEEDS]"

## 35. 📈 Cohort Analysis
"Perform cohort analysis tracking: retention, revenue, and behavior patterns over time.

Cohort definition: [GROUPING_LOGIC]
Metrics: [KPI_LIST]
Time windows: [PERIODS]"

## 36. 🧮 Monte Carlo Simulation
"Build Monte Carlo simulation for: risk analysis, forecasting, and decision making.

Variables: [STOCHASTIC_INPUTS]
Distributions: [PROBABILITY_DISTRIBUTIONS]
Iterations: [N_SIMULATIONS]"

## 37. 📊 Customer Segmentation
"Create customer segmentation using: RFM analysis, clustering, and behavioral patterns.

Customer data: [FEATURES]
Business objective: [SEGMENTATION_GOAL]
Actionability: [USE_CASES]"

## 38. 🔍 Fraud Detection System
"Build fraud detection with: anomaly detection, rules engine, and real-time scoring.

Transaction data: [FEATURES]
Fraud patterns: [KNOWN_PATTERNS]
False positive tolerance: [THRESHOLD]"

## 39. 📈 Marketing Mix Modeling
"Develop marketing mix model analyzing: channel attribution, saturation curves, and ROI.

Marketing spend: [CHANNEL_DATA]
Sales data: [OUTCOME_METRICS]
External factors: [SEASONALITY/COMPETITION]"

## 40. 🔄 Data Pipeline Orchestration
"Design data pipeline orchestration using [AIRFLOW/PREFECT] with: dependencies, retries, and monitoring.

Pipeline steps: [DAG_STRUCTURE]
Schedule: [CRON_PATTERN]
Error handling: [RETRY_LOGIC]"

## 41. 📊 Churn Prediction Model
"Build churn prediction with: feature engineering, model selection, and intervention strategies.

Customer data: [BEHAVIORAL_FEATURES]
Churn definition: [BUSINESS_RULE]
Prediction window: [TIME_HORIZON]"

## 42. 🧮 Optimization Problem Solver
"Solve optimization problem using: linear programming, genetic algorithms, or gradient methods.

Objective function: [MAXIMIZE/MINIMIZE]
Constraints: [CONSTRAINT_LIST]
Decision variables: [VARIABLES]"

## 43. 📈 Sentiment Analysis Pipeline
"Create sentiment analysis for: social media, reviews, and customer feedback.

Text source: [DATA_TYPE]
Sentiment levels: [BINARY/MULTICLASS]
Domain adaptation: [INDUSTRY]"

## 44. 🔍 Graph Analytics
"Implement graph analytics for: community detection, centrality measures, and path analysis.

Graph data: [NODES_EDGES]
Analysis goals: [METRICS]
Visualization needs: [OUTPUT_FORMAT]"

## 45. 📊 Propensity Modeling
"Build propensity models for: purchase, engagement, and conversion prediction.

Customer features: [PREDICTORS]
Target action: [OUTCOME]
Business application: [USE_CASE]"

## 46. 🔄 Model Monitoring Dashboard
"Create model monitoring tracking: performance drift, feature importance changes, and predictions.

Model: [PRODUCTION_MODEL]
Metrics: [MONITORING_KPIs]
Alert thresholds: [BOUNDARIES]"

## 47. 📈 Geo-Spatial Analysis
"Perform geo-spatial analysis including: clustering, hotspot detection, and route optimization.

Location data: [COORDINATES]
Analysis type: [SPATIAL_PROBLEM]
Visualization: [MAP_TYPE]"

## 48. 🧮 Reinforcement Learning
"Implement reinforcement learning for: recommendation, pricing, or resource allocation.

Environment: [STATE_SPACE]
Actions: [ACTION_SPACE]
Reward function: [OBJECTIVE]"

## 49. 📊 Data Storytelling
"Create data story with: narrative structure, visualizations, and actionable insights.

Analysis results: [FINDINGS]
Audience: [STAKEHOLDERS]
Business context: [DECISIONS]"

## 50. 🔍 MLOps Pipeline
"Build MLOps pipeline with: version control, CI/CD, monitoring, and automated retraining.

Model lifecycle: [STAGES]
Infrastructure: [CLOUD/ON_PREM]
Governance: [COMPLIANCE_NEEDS]"s
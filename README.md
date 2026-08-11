# 🚕 Chicago Taxi Trip Duration Prediction

*An end-to-end PySpark machine learning pipeline for predicting Chicago taxi trip duration using distributed data processing, regression modelling and Tableau dashboards.*

![Model Performance Dashboard](images/model_performance_dashboard.png)


## 🚀 Highlights

- 🚕 Analysed a large-scale Chicago Taxi Trips dataset using PySpark.
- ⚡ Built an end-to-end distributed machine learning pipeline.
- 🤖 Trained and compared four regression models.
- 📊 Evaluated model performance using multiple regression metrics.
- 📈 Developed interactive Tableau dashboards to communicate business insights.


## 📌 Project Overview

This project develops an end-to-end machine learning pipeline to predict the duration of taxi journeys in Chicago using a large-scale transportation dataset processed with PySpark.

The workflow covers the complete data science lifecycle, including problem definition, distributed data engineering, feature engineering, model development, performance evaluation and interactive Tableau visualisations. Four regression models were trained and compared to identify the most effective approach for predicting trip duration while demonstrating scalable machine learning techniques for big data.


## 🎯 Objectives

- Define a real-world machine learning problem using a large transportation dataset.
- Prepare and preprocess big data using distributed PySpark workflows.
- Engineer meaningful features to improve predictive performance.
- Train and compare four regression models.
- Evaluate model performance using multiple regression metrics.
- Investigate distributed computing performance and optimisation.
- Present business insights through interactive Tableau dashboards.


## 📂 Dataset

The project uses the **Chicago Taxi Trips** dataset, containing millions of taxi journeys with information including trip duration, distance, pickup and drop-off locations, fare values, payment methods and timestamps.

The dataset satisfies the characteristics of Big Data and was processed entirely using distributed PySpark operations.

![Dataset Overview](images/dataset_overview.png)


## 🧹 Data Engineering

The dataset was prepared through a scalable preprocessing pipeline which included:

- Data quality assessment
- Missing value handling
- Duplicate removal
- Feature engineering
- Categorical encoding
- Feature scaling
- Construction of reusable PySpark ML pipelines

The cleaned dataset was repartitioned and optimised to support efficient distributed processing across the Spark cluster.

![PySpark Data Pipeline](images/pyspark_data_pipeline.png)


## 🤖 Machine Learning Models

Four regression models were developed and compared:

- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient-Boosted Tree Regression

Hyperparameter tuning was performed using cross-validation to improve predictive performance.

![Model Comparison Summary](images/model_comparison_summary.png)


## ⚡ Distributed Computing

To improve scalability and computational efficiency, the project investigated:

- Spark partitioning
- Caching and persistence
- Resource configuration
- Spark UI performance monitoring
- Distributed model training

![Spark UI Analysis](images/spark_ui_analysis.png)


## 📊 Model Evaluation

The regression models were evaluated using multiple performance metrics, including:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score
- Cross-validation
- Stability analysis
- Model explainability

SHAP analysis was used to identify the features with the greatest influence on taxi trip duration predictions.

![SHAP Feature Importance](images/shap_feature_importance.png)


## 📈 Tableau Dashboards

Interactive Tableau dashboards were created to communicate the analytical results to both technical and non-technical audiences.

The dashboards present:

- Data quality monitoring
- Model performance
- Feature importance
- Business insights
- Scalability analysis

![Business Insights Dashboard](images/business_insights_dashboard.png)


## 📁 Repository Structure

```text
├── notebooks/
│   ├── 01_problem_definition_and_dataset.ipynb
│   ├── 02_data_engineering.ipynb
│   ├── 03_machine_learning_models.ipynb
│   ├── 04_distributed_computing.ipynb
│   ├── 05_model_evaluation.ipynb
│   └── 06_tableau_storytelling.ipynb
│
├── images/
│   ├── model_performance_dashboard.png
│   ├── dataset_overview.png
│   ├── pyspark_data_pipeline.png
│   ├── model_comparison_summary.png
│   ├── spark_ui_analysis.png
│   ├── shap_feature_importance.png
│   └── business_insights_dashboard.png
│
├── reports/
│   └── Chicago_Taxi_Trip_Duration_Prediction_Report.pdf
│
├── tableau/
│   └── Chicago_Taxi_Dashboard.twbx
│
└── README.md
```


## 🧠 Skills Demonstrated

- Python
- PySpark
- Apache Spark
- Big Data Analytics
- Machine Learning
- Regression Modelling
- Feature Engineering
- Distributed Computing
- Cross Validation
- Model Evaluation
- SHAP Explainability
- Tableau
- Data Visualisation


## 🚀 Future Improvements

Potential extensions include:

- Exploring additional ensemble learning methods.
- Incorporating real-time traffic and weather information.
- Deploying the model as an interactive prediction service.
- Investigating deep learning approaches for travel time prediction.
- Extending the workflow using cloud-based distributed computing platforms.


## 📄 Report

Read the full report for a detailed explanation of the methodology, machine learning pipeline, distributed computing approach and project findings.

📄 **[Chicago Taxi Trip Duration Prediction Report](reports/Chicago_Taxi_Trip_Duration_Prediction_Report.pdf)**


## 🌍 About the Author

Hi, I'm **Mia Emanuele**.

I'm a **Data Scientist** with a passion for statistical modelling, machine learning and explainable AI.

I enjoy **finding the "why" behind the data**—using data to uncover patterns, explain complex systems and support better decisions.

This repository forms part of my professional portfolio, showcasing projects completed during my MSc that have since been refined and expanded to demonstrate both technical expertise and analytical thinking.

### Connect with me

💼 LinkedIn: www.linkedin.com/in/mia-emanuele

💻 GitHub: https://github.com/miaemanuele77-ds

---

⭐ Thank you for taking the time to explore my work.

Feedback, discussion and collaboration are always welcome.

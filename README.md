🏭 Bosch Production Line Failure Prediction

Big Data Analytics & Machine Learning Project

📌 Overview

This project predicts manufacturing part failures using large-scale production line data. It demonstrates how Big Data analytics and machine learning can improve production efficiency, reduce defects, and minimize downtime in industrial environments.

The solution is built on the Bosch Production Line Performance dataset and handles challenges such as high dimensionality, extreme sparsity, and severe class imbalance.

📊 Dataset

Source: Kaggle – Bosch Production Line Performance

Size: 1.18M rows, 4,265 features (~14GB)

Target: Binary failure prediction

Imbalance: ~0.58% defective parts

🏗️ Architecture

Data Processing: Apache Spark (PySpark)

Storage: Parquet (columnar, compressed)

ML Model: XGBoost (Spark-based)

Visualization: Power BI / Matplotlib

The pipeline merges numeric, categorical, and timestamp data and performs distributed feature engineering.

🧠 Machine Learning Approach

Smart handling of missing values (missing = skipped station)

Feature engineering based on production flow:

Total production time

Station visit count

Critical station flags

Model: XGBoost (handles sparsity & imbalance)

Evaluation Metric: Matthews Correlation Coefficient (MCC)

🚀 Key Outcomes

Accurate early detection of defective parts

Identification of production bottlenecks

Scalable Big Data pipeline for industrial analytics

⚙️ Tech Stack

Apache Spark · XGBoost · Python · PySpark · Pandas · Power BI

👤 Author

Abdurrauf Afridi

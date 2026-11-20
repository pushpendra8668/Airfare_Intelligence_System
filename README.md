# ✈️ Airfare Intelligence System

### Historical Fare Analytics · Route Insights · Machine Learning

An interactive data science application that transforms historical flight data into meaningful airfare insights through exploratory data analysis, airline comparisons, route intelligence, and machine-learning-based fare estimation.

<p align="center">
  <a href="https://airfare-intelligence-system-4hw9s5imhilyg8uxqzrm3z.streamlit.app/">
    <strong>🚀 Live Demo</strong>
  </a>
</p>

---

## Overview

The **Airfare Intelligence System** is designed to help users explore historical flight fares, understand pricing patterns, compare airlines, and analyse routes through an interactive dashboard.

Built using Python, Streamlit, and Scikit-learn, the application combines data analysis, interactive visualisation, and a saved machine learning model in one platform.

## Key Features

- **Executive Dashboard** — Displays key statistics, airline comparisons, fare distributions, and historical pricing trends.
- **Fare Explorer** — Allows users to filter and compare historical fares using different flight attributes.
- **Fare Estimator** — Provides a machine-learning-based interface for estimating flight fares.
- **Route Intelligence** — Analyses historical fare patterns across different routes and airlines.
- **Dataset Explorer** — Supports interactive dataset inspection, filtering, and CSV export.

## Dataset at a Glance

| Metric | Value |
|:---|---:|
| Flight Records | 300,153 |
| Airlines | 6 |
| Unique Routes | 30 |
| Average Historical Fare | ₹20,890 |

*These figures represent the statistics displayed by the application.*

## Technology Stack

| Category | Technologies |
|:---|:---|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Model Persistence | Joblib |
| Data Visualisation | Plotly |
| Web Framework | Streamlit |
| Development Environment | Jupyter Notebook, VS Code |
| Version Control | Git, GitHub |

## Project Structure

```text
airfare-intelligence-system/
│
├── Data/
│   └── airfare_data.csv
│
├── Model/
│   └── best_model.joblib
│
├── Notebook/
│   ├── 01_data_understanding.ipynb
│   ├── 02_eda.ipynb
│   └── 03_preprocessing_modeling.ipynb
│
├── app.py
├── requirements.txt
└── README.md
```

## Project Methodology

1. **Data Understanding** — Examine the dataset, features, data types, and overall structure.
2. **Exploratory Data Analysis** — Identify fare distributions, airline differences, and route-level pricing patterns.
3. **Data Preprocessing** — Prepare numerical and categorical features for machine learning.
4. **Model Development** — Train and evaluate regression models for airfare estimation.
5. **Application Development** — Integrate analytics and the saved model into a Streamlit dashboard.
6. **Deployment** — Publish the application using Streamlit Community Cloud.

## Installation and Local Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd airfare-intelligence-system
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
streamlit run app.py
```

The application will open in your default browser.

## Important Note

This project works with **historical airfare data**. It does not fetch real-time airline ticket prices, live seat availability, or booking information. Fare estimates depend on the trained machine learning model and its evaluation results. Predictions should be treated as estimates, not guaranteed ticket prices.

## Future Enhancements

- Advanced model optimisation and evaluation.
- Additional route-level analytical insights.
- Enhanced interactive visualisations.
- Improved prediction validation and reporting.
- Additional data-driven travel insights.

## Author

**Pushpendra Maurya**  
B.Tech — Computer Science & Engineering

---

<p align="center">
  <strong>Airfare Intelligence System</strong><br>
  <em>Turning Historical Flight Data into Meaningful Insights.</em>
</p>

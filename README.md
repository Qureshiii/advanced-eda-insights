# 📊 advanced-eda-insights

Automated exploratory data analysis (EDA) workflows featuring ML-ready feature pipelines for the Titanic dataset and insights-driven diagnostic analytics for historical FIFA World Cup data.

---

## 🗺️ Project Navigation & Directory Structure

```text
advanced-eda-insights/
│
├── 📓 01_Titanic_EDA.ipynb     # ML-Ready Feature Engineering & Predictive EDA
├── 📓 02_Fifa_EDA.ipynb        # Insights-Driven Diagnostic & Trend Analytics
└── 📄 README.md                # Project Documentation & Architecture
```

---

## 🛠️ Tech Stack & Core Toolkit

*   **Core Language:** Python
*   **Data Manipulation:** Pandas, NumPy
*   **Data Visualization:** Matplotlib, Seaborn

---

## 🛳️ Module 1: Titanic — ML-Ready Feature Pipeline

This notebook focuses on transforming raw data into high-quality features optimized for training deep learning models. 

### 🚀 Interactive Workflow Breakdown

<details>
<summary>📂 1. Data Gathering & Quality Assessment</summary>

*   **Ingestion:** Loading structured demographic and ticketing datasets.
*   **Completeness Checks:** Identifying patterns in missing parameters (`Age`, `Cabin`, `Embarked`).
</details>

<details>
<summary>🧹 2. Diagnostic Data Cleaning</summary>

*   **Imputation Strategy:** Handling missing values utilizing group-specific metrics (e.g., median age by passenger class and gender) to minimize variance distortion.
*   **Outlier Resolution:** Isolating and managing extreme premium fare values to prevent gradient instabilities.
</details>

<details>
<summary>📊 3. Statistical Exploratory Data Analysis</summary>

*   **Bivariate Analysis:** Evaluating structural distributions between passenger class (`Pclass`), gender, and target labels (`Survived`).
*   **Correlation Mapping:** Constructing matrix heatmaps to isolate and resolve multi-collinearity issues.
</details>

<details>
<summary>⚙️ 4. ML-Ready Feature Engineering</summary>

*   **Feature Transformation:** Developing non-linear interactions such as engineering `FamilySize` and isolating `Title` from textual columns.
*   **Pipeline Preparation:** Formatting clean tensors ready for feature scaling and neural network initialization.
</details>

---

## ⚽ Module 2: FIFA World Cup — Insights-Driven Analytics

This notebook shifts focus toward diagnostic analytics, historical trend mapping, and translating raw data into stakeholder-facing visual insights.

### 🚀 Interactive Workflow Breakdown

<details>
<summary>📂 1. Historical Data Aggregation</summary>

*   **Sourcing:** Compiling multi-decade tournament metrics, match statistics, and goal distributions.
*   **Schema Alignment:** Formatting inconsistent historical country naming structures into a unified index.
</details>

<details>
<summary>🧹 2. Structured Data Cleaning</summary>

*   **Anomalies:** Removing structural duplication from multi-stage tournament brackets.
*   **Consistency Control:** Standardizing attendance metrics, date formats, and localized venue labels.
</details>

<details>
<summary>📈 3. Trend Analysis & Data Storytelling</summary>

*   **Temporal Shifts:** Mapping the evolution of scoring efficiency, home-field advantage metrics, and tournament scale over time.
*   **Geospatial Insights:** Visualizing dominant confederations and performance trends across hosting regions.
</details>

<details>
<summary>🎨 4. Executive Visual Analytics</summary>

*   **Custom Visualization Layouts:** Utilizing structured Seaborn facets and Matplotlib distributions to communicate historical dominance profiles clearly.
*   **Actionable Insights:** Condensing raw performance metrics into strategic takeaways on competitive balance shifts over the tournament's lifecycle.
</details>

---

## ⚙️ Local Development Setup

To run these workflows locally, clone the repository and configure your development environment:

```bash
# Clone the repository
git clone https://github.com

# Navigate to the repository directory
cd advanced-eda-insights

# (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Launch Jupyter to explore the pipelines
jupyter lab
```


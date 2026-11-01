# Holistic Health & Lifestyle Analysis

## Project Overview

This project explores the relationship between lifestyle habits and overall health through data analysis and machine learning.

The main objective is to analyze health and lifestyle-related factors, identify meaningful patterns in the dataset, and develop a predictive model to estimate an individual's Overall Health Score.

The project follows a data science workflow, covering data exploration, preprocessing, visualization, model development, and performance evaluation.

## Objectives

- Explore and understand health and lifestyle-related data.
- Perform data cleaning and preprocessing to improve data quality.
- Conduct Exploratory Data Analysis (EDA) to identify patterns and relationships.
- Investigate how lifestyle factors relate to overall health.
- Develop and evaluate machine learning regression models.
- Select a suitable model for predicting the Overall Health Score.

## Technologies & Tools

| Technology | Purpose |
|---|---|
| Python | Data analysis and model development |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Scikit-learn | Machine learning and model evaluation |
| Jupyter Notebook | Development and experimentation |

## Project Workflow

### 1. Data Collection and Exploration
- Loaded the holistic health and lifestyle dataset.
- Examined dataset structure, attributes, and data types.
- Explored the distribution of variables and identified initial patterns.

### 2. Data Preprocessing
- Examined data quality and prepared the dataset for analysis.
- Performed necessary data preparation for machine learning.
- Prepared relevant features and the target variable.

### 3. Exploratory Data Analysis (EDA)
- Analyzed the distributions of health and lifestyle variables.
- Investigated relationships between different features.
- Used visualizations to understand patterns and potential relationships with the Overall Health Score.

### 4. Model Development
Developed and evaluated two regression algorithms:

- Linear Regression
- Random Forest Regression

### 5. Model Evaluation and Selection

The models were evaluated using the R-squared (R²) metric.

| Model | R² Score |
|---|---:|
| Linear Regression | 0.946 |
| Random Forest Regression | 0.944 |

Random Forest Regression was selected as the final model for this project.

The selected model was saved as a serialized `.pkl` file for future use.

## Repository Structure

```text
Real_world_project/
│
├── 1_holistic_health_lifestyle_dataset.csv
│
├── data_analysis.ipynb
│
├── random_forest_health_model.pkl
│
└── README.md
```

## Getting Started

### Prerequisites

Make sure Python is installed on your system.

### 1. Clone the Repository

```bash
git clone https://github.com/Pasindi0814/Real_world_project.git
```

### 2. Navigate to the Project Directory

```bash
cd Real_world_project
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `data_analysis.ipynb` to explore the complete analysis and model development process.

## Model Artifact

The repository includes the trained Random Forest regression model:

`random_forest_health_model.pkl`

This file contains the saved model and can be loaded using Python's Joblib or Pickle library, depending on the serialization method used during training.

## Key Learning Outcomes

Through this project, I gained practical experience in:

- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Data visualization and interpretation.
- Regression-based machine learning.
- Model comparison and performance evaluation.
- Saving trained machine learning models for future applications.

## Author

**Samudika Pasindi**

Data Science Undergraduate  
Sabaragamuwa University of Sri Lanka

[GitHub Profile](https://github.com/Pasindi0814)

---

*This project was developed as part of my practical learning journey in Data Science and Machine Learning.*

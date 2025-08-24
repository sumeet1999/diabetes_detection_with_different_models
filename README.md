# Diabetes Prediction using Machine Learning

> A project to predict the onset of diabetes by comparing several machine learning classification models.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---

## Project Overview

The primary goal is to build a machine learning model that can accurately predict whether a patient has diabetes based on a set of medical diagnostic measurements. The project involves:

-   **Data Preprocessing:** Cleaning and preparing the dataset for modeling.
-   **Exploratory Data Analysis (EDA):** Visualizing data to uncover patterns and insights.
-   **Model Comparison:** A comparative study of four different classification algorithms.

Based on a comprehensive evaluation (Accuracy, Precision, Recall, F1-Score, and AUC-ROC), the **Random Forest model** was identified as the best-performing model for this dataset, achieving a perfect score of 1.0 across all metrics.

---

## Features

-   Detailed data exploration and visualization.
-   Side-by-side comparison of Logistic Regression, Decision Tree, K-Nearest Neighbour, and Random Forest.
-   Clear evaluation metrics and ROC curves for each model.
-   Justification for the final model selection.

---

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

-   Python 3.8+
-   `pip` and `venv`

### Installation

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd diabetes_prediction
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
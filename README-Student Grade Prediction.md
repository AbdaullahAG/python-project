# python-project
# 📚 Student Grade Prediction (Linear Regression)

-----

## Overview

This project is a simple demonstration of **Machine Learning** using **Linear Regression** to predict a student's score based on the number of hours they study. The model uses a dataset where a positive linear correlation is observed between study hours and exam scores.

The implementation is done in a Jupyter Notebook and utilizes popular Python libraries for data manipulation, visualization, and model training.

-----

## Project Highlights

  * **Model:** Linear Regression
  * **Goal:** Predict the final `Score` based on the `Hours` studied.
  * **Data:** A small, dummy dataset (simulated data) consisting of two features: `Hours` and `Scores`.
  * **Key Result:** The model predicted a score of **73.40** for a student who studies **7.5 hours**.

-----

## Technologies Used

The project uses the following Python libraries:

  * **`pandas`**: For data structure and analysis.
  * **`matplotlib.pyplot`**: For basic data plotting and visualization.
  * **`seaborn`**: For creating informative and attractive statistical graphics.
  * **`scikit-learn (sklearn)`**:
      * `LinearRegression`: The core machine learning model used.
      * `train_test_split`: To split data into training and testing sets.
      * `mean_squared_error`: To evaluate the model's performance.

-----

## Performance

The model's performance was evaluated using the Mean Squared Error (MSE) on the test set.

| Metric | Value |
| :--- | :--- |
| **Mean Squared Error (MSE)** | 2.11 |

-----

## Getting Started

### Prerequisites

You need a Python environment with Jupyter Notebook and the required libraries installed.

```bash
pip install pandas matplotlib seaborn scikit-learn
```

### Running the Notebook

1.  Clone this repository (if hosted) or download the `student grade ml1.ipynb` file.
2.  Open the notebook using Jupyter:
    ```bash
    jupyter notebook
    ```
3.  Run all cells in the notebook to reproduce the data loading, visualization, model training, evaluation, and prediction steps.

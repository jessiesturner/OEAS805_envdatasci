# OEAS805 Homework 3: Machine Learning - Regression - due 11:59 PM on 10/19/2026

Create a new folder in your OEAS805 repository called `HW3` where you will save the code and files you create for this homework assignment. You will also create or update your conda environment to include all necessary machine learning libraries (e.g., `scikit-learn`, `pandas`, `matplotlib`/`seaborn`).

You will be working with the `CBP_TWQM_MAIN_WQ_2021_2026_surface.csv` dataset shared in the `data` folder. This is Chesapeake Bay Program Water Quality data from 2021-2026 at station 4.1C in the upper mainstem Chesapeake Bay. I have cleaned this dataset from what we used in class in the matplotlib_exercise.ipynb notebook, so that now it is only data from surface waters including all variables ("Parameters").

---

## Instructions (20 points total)

Create a Jupyter notebook (or a Python script `.py` if you use Spyder) to apply and compare machine learning regression techniques on the dataset.

### 1. Target Variable Selection
Choose **one** high-level water quality variable to predict as your target $y$.
* **Constraint:** You may choose *any* target variable **except** water temperature or salinity.
* Select appropriate inputs (predictor) variables ($X$) from the remaining features in the dataset.
* Briefly explain your decisions about what you chose as inputs. 


### 2. Model Implementation (12 points)
Select **three (3)** different machine learning techniques for regression from those covered in class:
* Linear Regression
* $k$-Nearest Neighbors (KNN) Regressor
* Multi-Layer Perceptron (MLP) Regressor
* Radius Neighbors Regressor

Fit each model to your data using `scikit-learn`.

### 3. Model Evaluation & Visualization (6 points)
For each of the three models:
* Generate a scatter plot showing the actual target values versus the predicted model output (or feature vs. target with the fitted trend).
* Display the $R^2$ (coefficient of determination) score clearly on or alongside each plot.

### 4. Hyperparameter Explanation (2 points)
In Markdown cells (or code comments), concisely justify your choice of hyperparameters for any non-linear models used:
* **KNN:** Why did you choose that specific value for $k$ (number of neighbors)?
* **MLP:** Why did you choose that network architecture (number of hidden layers and nodes)?
* **Radius Neighbors:** How did you determine the search radius?

---

## Upload to GitHub
1. Save your notebook (`HW3_regression.ipynb`) or script (`HW3_regression.py`) inside your local `HW3` folder.
2. Export your conda environment file as `hw3_env.yml` into the same folder.
3. Commit all files locally using `git` and push your changes to your remote OEAS805 GitHub repository.

---

## Submission
Submit the link to your GitHub repository's `HW3` folder on Canvas.

* **Late Policy:** Work submitted after the deadline will incur a 10% per day penalty. No work will be accepted after midnight on October 26<sup>th</sup>, 2026.
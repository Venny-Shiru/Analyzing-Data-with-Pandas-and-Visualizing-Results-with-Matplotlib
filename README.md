# Analyzing-Data-with-Pandas-and-Visualizing-Results-with-Matplotlib
# Iris Dataset Analysis

This project demonstrates how to load, explore, analyze, and visualize the **Iris dataset** using Python. The dataset is a classic in machine learning and statistics, containing measurements of iris flowers from three different species.

## Objectives

- Load and explore a dataset using the `pandas` library.
- Perform basic data analysis and summarization.
- Create various visualizations using `matplotlib` and `seaborn`.

---

## Dataset

The dataset used is the **Iris dataset**, which is included in the `sklearn.datasets` module. It contains 150 samples with the following features:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)
- Species (setosa, versicolor, virginica)

---

## Tasks Completed

### ✅ Task 1: Load and Explore the Dataset

- Loaded the dataset using `sklearn.datasets.load_iris()`
- Converted it to a pandas DataFrame
- Displayed the first few rows using `.head()`
- Checked for missing values and data types

### ✅ Task 2: Basic Data Analysis

- Computed basic statistics using `.describe()`
- Grouped the data by species and computed mean values
- Noted trends and observations in the data

### ✅ Task 3: Data Visualization

Four types of visualizations were created:

1. **Line Chart**  
   Trend of sepal and petal lengths over sample index

2. **Bar Chart**  
   Comparison of average petal length across species

3. **Histogram**  
   Distribution of sepal width

4. **Scatter Plot**  
   Relationship between sepal length and petal length, colored by species

All plots are customized with titles, axis labels, and legends for clarity.

---

## Requirements

Install the following Python libraries if not already available:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

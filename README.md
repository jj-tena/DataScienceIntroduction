# DataScienceIntroduction
This repository contains a series of notebooks that aim to serve as an introduction to the field of data science, generating various graphs and applying multiple statistics that allow a deeper understanding of the structure and nature of the datasets studied.

## Notebook 1: Data Visualization

### Use Case:
The purpose of this notebook is to demonstrate various data visualization techniques using Pandas, Matplotlib, and Seaborn. By generating different types of plots, we aim to explore and present the data in a clear and insightful manner.

### Objective:
To showcase and compare the visualizations that can be created using Pandas, Matplotlib, and Seaborn libraries. This includes scatter plots, bar plots, histograms, pie charts, box plots, line plots, area plots, and heatmaps.

### Steps:

#### Data Preparation:
Generate a sample dataset using NumPy with columns 'A', 'B', 'C', and 'D'.
Create a Pandas DataFrame from this dataset.

#### Visualization with Pandas:
Generate a series of plots using Pandas' built-in plotting functions:
Scatter Plot
Bar Plot
Histogram
Pie Chart
Box Plot
Line Plot
Stacked Area Plot

#### Visualization with Matplotlib:
Create similar plots using Matplotlib to compare with Pandas visualizations:
Scatter Plot
Bar Plot
Histogram
Pie Chart
Box Plot
Line Plot
Stacked Area Plot

#### Visualization with Seaborn:
Use Seaborn for advanced and aesthetically pleasing visualizations:
Scatter Plot
Bar Plot
Histogram with KDE
Pie Chart
Box Plot
Violin Plot
Line Plot
Correlation Heatmap

### Conclusion:
This notebook provides a comprehensive overview of data visualization techniques using three popular Python libraries. It demonstrates how each library can be utilized to create various plots and visualizations, highlighting their unique features and capabilities. By comparing the visualizations produced by Pandas, Matplotlib, and Seaborn, users can better understand how to choose and apply different visualization tools to effectively communicate their data insights.

## Notebook 2: Exploratory Data Analysis and Modeling of California Housing Data

### Use Case:
This notebook is designed to explore and analyze the california_housing dataset to understand housing characteristics in California. The aim is to derive insights through exploratory data analysis (EDA) and to build and evaluate predictive models to estimate housing values.

### Objective:
Data Ingestion: Load the california_housing dataset and initialize necessary data structures.
Exploratory Data Analysis (EDA): Investigate the dataset's dimensions, variables, statistics, and correlations to gain a thorough understanding of the data.
Automated Analysis: Use automated libraries to perform statistical and graphical analysis.
Model Training and Validation: Develop and evaluate predictive models to estimate housing values using various regression algorithms.

### Steps:

#### Data Ingestion:
Download the dataset using fetch_california_housing.
Load the data into a Pandas DataFrame.
Initialize the custom module with the DataFrame and review the metadata.

#### Exploratory Data Analysis (EDA):
Dimensions: Review dataset size and sample data.
Variables: Examine the variables, their types, and descriptions.
Statistics: Analyze general statistics including mean, standard deviation, and percentiles.
Missing Values: Check for and confirm absence of missing values.
Outliers: Identify outliers through boxplots and analyze their impact.
Unique Values: Categorize variables by the number of unique values.
Histograms: Plot histograms to observe variable distributions.
Correlation Matrix: Evaluate relationships between variables using a correlation matrix.
Scatter Plots: Visualize relationships between variable pairs and examine distributions with combined scatter plots.
Automated Exploratory Data Analysis:
Automated Statistical Analysis: Utilize Sweetviz for detailed statistical summaries.
Automated Graphical Analysis: Apply AutoViz for comprehensive visualizations including scatter plots, histograms, and correlation matrices.

#### Model Training and Validation:
Data Splitting: Separate predictors from the target variable.
Cross-Validation: Implement KFold cross-validation with 5 folds.
Pipeline: Standardize numerical variables using StandardScaler.
Evaluation Metric: Measure performance using the R² score.
Algorithms: Test various regression algorithms (Linear Regression, Support Vector Regression, Decision Tree Regressor, Random Forest Regressor) and identify the best-performing model.

### Conclusion:
The analysis provided a comprehensive overview of the california_housing dataset, uncovering valuable insights about housing characteristics and distributions. Automated tools facilitated an efficient exploratory data analysis. Among the tested regression algorithms, Support Vector Regression showed the best performance due to its capability to manage non-linear relationships, making it the preferred model for predicting housing values.

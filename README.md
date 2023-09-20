# datasci_3_eda
This is an assignment for HHA 507

Objective:
Engage in the critical phase of Exploratory Data Analysis (EDA) using the tools and techniques from Python to uncover patterns, spot anomalies, test hypotheses, and identify the main structures of your dataset.

Instructions:
1. Univariate Analysis:
 - Load a dataset of your choice in your Colab notebook .ipynb or in a python script .py (you can use one from previous assignments or find a new one).
 - Manually perform a univariate analysis to understand the distribution of each variable. This includes calculating measures of central tendency (mean, median, mode) and measures of spread (range, variance, standard deviation, IQR).
 - Visualize the distribution of select numerical variables using histograms.

2. Bivariate Analysis:
 - Analyze the relationship between pairs of variables.
   -  Use scatter plots to explore potential relationships between two numerical variables.
   - For categorical and numerical variable pairs, use boxplots.
 - Compute correlation coefficients for numerical variables and document any strong correlations observed.

3. Handling Outliers:
 - Identify outliers in your dataset using the IQR method or visualization tools.
 - Decide on an approach to handle these outliers (e.g., remove, replace, or retain) and justify your decision in a markdown cell.
 - If there are no outliers based on 1, 2, or 3 standard deviations (or z scores >= 1), please state that and support it with your code.

4. Automated Analysis:
 - Using the automated EDA tool pandas profiling (e.g., please refer to https://book.datascience.appliedhealthinformatics.com/docs/Ch3/automatic_EDA)
 - Load in your dataset and analyze it
 - Save the output (.html) in your report, within a folder called ```automaticEDA```

Please refer to [datasets](https://github.com/Helzheng123/datasci_3_eda/tree/main/datasetshttps://github.com/Helzheng123/datasci_3_eda/tree/main/datasets) to view the dataset used for this repo.
Please refer to the [automatedEDA](https://github.com/Helzheng123/datasci_3_eda/tree/main/automaticEDA) folder to view the automated EDA pandas profiling.

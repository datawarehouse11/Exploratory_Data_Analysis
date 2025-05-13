# Exploratory Data Analysis Project

This project focuses on performing exploratory data analysis (EDA) to understand the characteristics and patterns within a dataset.

**Skills Demonstrated:**

* Data Cleaning and Preprocessing
* Data Visualization (Matplotlib, Seaborn)
* Descriptive Statistics
* Pandas for Data Manipulation
* NumPy for Numerical Operations

**Key Findings:**

* Performed data cleaning, including handling missing values and outliers, to prepare the dataset for analysis. (from "## Handle missing values", "df.isna().any(axis=1)", "df.drop(columns=['Fee'],axis=1,inplace=True)", "df.fillna(method='ffill',inplace=True)")
* Visualized the distribution of key variables using histograms and box plots. (e.g., "sns.boxplot(df['Marks_Eng'])", "sns.histplot(df1['age'],kde=True)")
* Investigated relationships between variables using scatter plots and correlation matrices. (e.g., "plt.scatter(df.Units,df.Minutes, color='red')", "df.corr()")
* Calculated descriptive statistics to summarize the central tendency and variability of the data. (e.g., "df.describe().T", "df.info()")
* Created crosstabulations and pivot tables to analyze categorical data. (e.g., "pd.crosstab(index = \[df.Day,df.Assignee],  columns=df.Status)", "pd.pivot_table(df2, index=\['Product type','Gender'\], columns='Course', values='Amount', aggfunc='sum')")

**Code and Data:**

* `Exploratory_Data_Analysis3.ipynb`: Jupyter Notebook containing the Python code.
* `\[Dataset_Name.csv]` (or other format): The dataset used.  (If you didn't upload the dataset, provide a download link here).  *(**Note:** You'll need to replace `\[Dataset_Name.csv]` with the actual name of your data file(s). If you used multiple datasets, list them all.)*
* `datasets/`:  This directory contains the datasets used in the notebooks:
    * `defaulter.csv`
    * `delivery.csv`
    * `Tire_useability.csv`
    * `Trees.csv`

**How to Run:**

* Open the `Exploratory_Data_Analysis3.ipynb` file in Jupyter Notebook or Google Colab.
* Ensure the dataset file(s) are in the same directory or update the file path(s) in the notebook.  If datasets are in the `datasets/` subdirectory, make sure that subdirectory is included.
* Run the notebook cells to reproduce the analysis.


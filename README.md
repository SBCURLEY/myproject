<h1 align="center">Principles of Data Analytics</h1>
<h1 align="center">Palmer Penguins Exploratory Data Analysis</h1>

# Description

The assessment focuses on the widely available palmerpenguins data set. The assessment is broken into three overlapping components: a set of tasks, a small project, and a presentational component. All components are submitted in a single Jupyter notebook in a single GitHub repository.

# Table of Contents

1. Introduction
   
2. Import Libraries
   
3. Load Data
   
4. Data Exploration

    - 4.1  Check for the DataFrame dimensionality with pandas .info() method

    - 4.2  Selecting data by row numbers (.iloc)

    - 4.3  Generate descriptive statistics with pandas .describe method

5. Cleaning the Dataset

    - 5.1 Working with missing data
  
    - 5.2 Identify missing values

    - 5.3 Remove missing values

    - 5.4 Check the data

6. Data Analysis

    - 6.1 Univariate Analysis

      - 6.1.1 Bar Chart (Task 4)

      - 6.1.2 Stacked Bar Chart

      - 6.1.3 Histogram (Task 4)

    - 6.2 Bivariate Analysis (Project)

      - 6.2.1 Data Insight
  
      - 6.2.2 Bill Length vs Bill Depth

      - 6.2.3 Bill Length vs Bill Depth with Regression Line

      - 6.2.4 Bill Length vs Bill Depth by Species
  
      - 6.2.5 Bill Length vs Bill Depth by Species with Regression Line per Species

      - 6.2.6 Bill Length vs Bill Depth with Regression Line for Male / Female Species

7. Conclusion


# Git Hub Repository Link

[SBCURLEY/myproject](https://github.com/SBCURLEY/myproject)


# Description of Contents

## 1. Introduction

The [Palmer penguins dataset](https://allisonhorst.github.io/palmerpenguins/) by [Allison Horst](https://allisonhorst.com/), [Alison Hill](https://www.apreshill.com/), and [Kristen Gorman](https://www.uaf.edu/cfos/people/faculty/detail/kristen-gorman.php) is a dataset for data exploration & visualization, as an alternative to the Iris dataset. It was made available in 2020.

The dataset contains data for 344 penguins. There are 3 different species of penguins in this dataset "Adelie", "Chinstrap" and "Gentoo", collected from 3 islands in the Palmer Archipelago, Antarctica.


## 2. Import Libraries

I imported the following libraries to analyse the dataset.

 - Pandas

 - Numpy
  
 - Matplotlib


## 3. Load Data

The dataset is available on [GitHub](https://allisonhorst.github.io/palmerpenguins/).


## 4. Data Exploration

I explore the data with the following:

 - pandas .info() method
  
 - pandas .iloc
  
 - pandas .describe method

### References

###### [1] [w3schools Pandas DataFrame info() Method](https://www.w3schools.com/python/pandas/ref_df_info.asp)

###### [2] [Understanding the .info output - Machine Learning Tutorials](https://machinelearningtutorials.org/a-comprehensive-guide-to-using-the-pandas-dataframe-info-method/)

###### [3] [Pandas Documentation on pandas.DataFrame.iloc](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.iloc.html)

###### [4] [Understanding the Output of pandas.DataFrame.describe](https://www.pythonlore.com/exploring-pandas-dataframe-describe-for-descriptive-statistics/)

###### [5] [Pandas Documentation on pandas.DataFrame.describe](https://pandas.pydata.org/pandas-docs/version/0.20.2/generated/pandas.DataFrame.describe.html)


## 5. Cleaning the Dataset

There are missing values in this dataset, so I identified the values and removed them from the dataset before analysis.

-isnull() method

-dropna()


### References

###### [6] [IEEE 754: Wikipedia](https://en.wikipedia.org/wiki/IEEE_754)

###### [7] [Data Cleaning with Python and Pandas: Detecting Missing Values](https://towardsdatascience.com/data-cleaning-with-python-and-pandas-detecting-missing-values-3e9c6ebcf78b)

###### [8] [Pandas isna() Function: Checking for Missing Values](https://machinelearningtutorials.org/pandas-isna-function-checking-for-missing-values-with-examples/)

###### [9] [Working with Missing Data in Pandas](https://www.geeksforgeeks.org/working-with-missing-data-in-pandas//)

###### [10] [Reset Index in Pandas After Using dropna()](https://www.statology.org/pandas-reset-index-after-dropna/)


## 6. Data Analysis

- A Univariate Analysis includes a Bar Chart & a Histogram.
- A Bivariate Analysis includes Scatter plots to understand the relationship between Bill Length and Bill Depth with additional variables

### References

###### [11] [Mastering Exploratory Data Analysis (EDA): A Comprehensive Python (Pandas) Guide for Data Insights and Storytelling](https://medium.com/@nomannayeem/mastering-exploratory-data-analysis-eda-a-comprehensive-python-pandas-guide-for-data-insights-c0be7c5b8889)

###### [12] [Real Python: Stateful vs Stateless Approach](https://realpython.com/lessons/stateful-vs-stateless-approach/)

###### [13] [Stateful vs stateless - Explained](https://www.redhat.com/en/topics/cloud-native-apps/stateful-vs-stateless)

###### [14] [Lecture 8: Video 4 - Ian McLoughlin -recommendation on stateless approach](https://atlantictu-my.sharepoint.com/personal/ian_mcloughlin_atu_ie/_layouts/15/stream.aspx?id=%2Fpersonal%2Fian_mcloughlin_atu_ie%2FDocuments%2Fstudent_shares%2Fprinciples_of_data_analytics%2F08_best_fit%2Ft08v04_best_fit%2Emkv&referrer=OneDriveForBusiness&referrerScenario=OpenFile)

###### [15] [Python Guides on Matplotlib plot bar chart](https://pythonguides.com/matplotlib-plot-bar-chart/)

###### [16] [Python Graph Gallery-Custom Matplotlib Title](https://python-graph-gallery.com/190-custom-matplotlib-title/)

###### [17] [Control the color of barplots built with matplotlib](https://python-graph-gallery.com/3-control-color-of-barplots/)

###### [18] [Colour Chart](https://matplotlib.org/stable/users/explain/colors/colors.html)

###### [19] [Pythonspot:Matplotlib legend](https://pythonspot.com/matplotlib-legend/)

###### [20] [Pandas GroupBy – Unstack](https://www.geeksforgeeks.org/pandas-groupby-unstack/)

###### [21] [Matplotlib: Stacked Bar Chart](https://matplotlib.org/stable/gallery/lines_bars_and_markers/bar_label_demo.html#sphx-glr-gallery-lines-bars-and-markers-bar-label-demo-py)

###### [22] [Charts from Dataframe Plot stacked bar graph in one line using Pandas](https://medium.com/@jb.ranchana/easy-way-to-create-stacked-bar-graphs-from-dataframe-19cc97c86fe3)

###### [23] [Pandas Documentation on pandas.pivot_table](https://pandas.pydata.org/docs/reference/api/pandas.pivot_table.html)

###### [24] [Pandas: Create Pivot Table with Multiple aggfunc](https://www.statology.org/pandas-pivot-table-multiple-aggfunc/0)

###### [25] [Stack Overflow: python pandas pivot_table count frequency in one column - issue with using "count"](https://stackoverflow.com/questions/22412033/python-pandas-pivot-table-count-frequency-in-one-column)

###### [26] [Matplotlib: Bar Label Demo](https://matplotlib.org/stable/gallery/lines_bars_and_markers/bar_label_demo.html#sphx-glr-gallery-lines-bars-and-markers-bar-label-demo-py)

###### [27] [Python Histogram Plotting: NumPy, Matplotlib, pandas & Seaborn](https://realpython.com/python-histograms/)

###### [28] [Histograms in Matplotlib](https://www.datacamp.com/tutorial/histograms-matplotlib)

###### [29] [Statology:How to Modify a Matplotlib Histogram Color (With Examples)](https://www.statology.org/matplotlib-histogram-color/)

###### [30] [How to Perform Bivariate Analysis in Python (With Examples)](https://www.statology.org/bivariate-analysis-in-python/)

###### [31] [Pandas: using groupby to get mean for each data category](https://stackoverflow.com/questions/29314424/pandas-using-groupby-to-get-mean-for-each-data-category)

###### [32] [Towards Data Science: Baffled by Covariance and Correlation](https://towardsdatascience.com/let-us-understand-the-correlation-matrix-and-covariance-matrix-d42e6b643c22#:~:text=In%20simple%20words%2C%20both%20the,linear%20relationship%20between%20two%20variables.)

###### [33] [Datagy:Calculate and Plot a Correlation Matrix in Python and Pandas](https://datagy.io/python-correlation-matrix/)

###### [34] [Matplotlib best fit line](https://pythonguides.com/matplotlib-best-fit-line/)

###### [35] [Topic 8: Video 4 - best fit](https://atlantictu-my.sharepoint.com/personal/ian_mcloughlin_atu_ie/_layouts/15/stream.aspx?id=%2Fpersonal%2Fian%5Fmcloughlin%5Fatu%5Fie%2FDocuments%2Fstudent%5Fshares%2Fprinciples%5Fof%5Fdata%5Fanalytics%2F08%5Fbest%5Ffit%2Ft08v04%5Fbest%5Ffit%2Emkv&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview)

###### [36] [Numpy Polyfit Explained With Examples](https://www.pythonpool.com/numpy-polyfit/)

###### [37] [Matplotlib: How to Color a Scatterplot by Value](https://www.statology.org/matplotlib-scatterplot-color-by-value/)

###### [38] [Python Examples: Matplotlib – Scatter Plot Color based on Condition](https://pythonexamples.org/matplotlib-scatter-plot-color-based-on-condition/)

###### [39] [Matplotlib.axes.Axes.scatter](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.scatter.html)


## Built With
- Python 
- Visual Studio Code
- Cmder



## About Author
- Sharon Curley
  
    My role is a Business Systems Analyst for [Meissner Corporation](https://www.meissner.com/) - a manufacturing company in Castlebar, Co. Mayo. The systems I am supporting currently are Microsoft Dynamics 365 (ERP) for all Meissner entities (Ireland, US, Switzerland, Germany & Italy). I initially started out in functional areas like Customer Service & Supply Chain as I was lucky to be one of the first crew members on board in this company in 2020. I have moved into the IT Dept since March last year. I have a background in SAP - projects & support, so was drawn back into this area when I saw the opportunity arise within Meissner. I have a keen interest in data as when I was a functional user that was the most challenging part of my role - trying to get meaningful data from the systems we use. I have used excel to an advanced level and started with Power BI. I see a lot of opportunities within Meissner to develop in the Data field. I am hoping I will have the skills to do so.

![Meissner](https://www.meissner.com/wp-content/uploads/castlebar-brief-pdf-image.jpg)

- [Git Hub Profile](https://github.com/SBCURLEY "Sharon Curley")

- [Email](mailto:G00438863@atu.ie?subject=Hi "Hi!")
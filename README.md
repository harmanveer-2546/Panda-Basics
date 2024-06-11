# Pandas

Pandas is a powerful and open-source Python library. The Pandas library is used for data manipulation and analysis. Pandas consist of data structures and functions to perform efficient operations on data.
Pandas (styled as pandas) is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. It is free software released under the three-clause BSD license.
Since 2015, pandas is a NumFOCUS sponsored project. This will help ensure the success of development of pandas as a world-class open-source project. Pandas name is derived from “panel data” and is also refered as “Python Data Analysis“. 

Pandas is built around data structures called Series and DataFrames. Data for these collections can be imported from various file formats such as comma-separated values, JSON, Parquet, SQL database tables or queries, and Microsoft Excel.
What some have called a ‘game changer’ for analyzing data with Python, Pandas ranks among the most popular and widely used tools for so-called data wrangling, or munging. This describes a set of concepts and a methodology used when taking data from unusable or erroneous forms to the levels of structure and quality needed for modern analytics processing. Pandas excels in its ease of working with structured data formats such as tables, matrices, and time series data. It also works well with other Python scientific libraries.

### What is Python Pandas used for?

The Pandas library is generally used for data science, but have you wondered why? This is because the Pandas library is used in conjunction with other libraries that are used for data science.
It is built on top of the NumPy library which means that a lot of the structures of NumPy are used or replicated in Pandas.
The data produced by Pandas is often used as input for plotting functions in Matplotlib, statistical analysis in SciPy, and machine learning algorithms in Scikit-learn.

You must be wondering, Why should you use the Pandas Library. Python’s Pandas library is the best tool to analyze, clean, and manipulate data.

Here is a list of things that we can do using Pandas: 

* Data set cleaning, merging, and joining.
* Easy handling of missing data (represented as NaN) in floating point and non-floating point data.
* Columns can be inserted and deleted from DataFrame and higher-dimensional objects.
* Powerful group by functionality for performing split-apply-combine operations on data sets.
* Data Visualization.

### How Pandas Works:

Included in the Pandas open-source library are DataFrames, which are two-dimensional array-like data tables in which each column contains values of one variable and each row contains one set of values from each column. Data stored in a DataFrame can be of numeric, factor, or character types. Pandas DataFrames are also thought of as a dictionary or collection of series objects.

Data scientists and programmers familiar with the R programming language for statistical computing know that DataFrames are a way of storing data in grids that are easily overviewed. This means that Pandas is chiefly used for machine learning in the form of DataFrames.
Pandas allows for importing and exporting tabular data in various formats, such as CSV or JSON  files. Importing and exporting tabular data.

Pandas also allows for various data manipulation operations and for data cleaning features, including selecting a subset, creating derived columns, sorting, joining,  filling, replacing, summary statistics, and plotting.

According to organizers of the Python Package Index—a repository of software for the Python programming language—Pandas is well suited for working with several kinds of data, including:

* Tabular data with heterogeneously-typed columns, as in an SQL table or Excel spreadsheet
* Ordered and unordered (not necessarily fixed-frequency) time series data
* Arbitrary matrix data (homogeneously typed or heterogeneous) with row and column labels

Any other form of observational/statistical data sets. The data actually need not be labeled at all to be placed into a pandas data structure.

### Pandas Series:

A Pandas Series is a one-dimensional labeled array capable of holding data of any type (integer, string, float, Python objects, etc.). The axis labels are collectively called indexes.
The Pandas Series is nothing but a column in an Excel sheet. Labels need not be unique but must be of a hashable type.
The object supports both integer and label-based indexing and provides a host of methods for performing operations involving the index.

### Pandas DataFrames:

Before you start, let’s have a brief recap of what DataFrames are.

Those who are familiar with R know the data frame as a way to store data in rectangular grids that can easily be overviewed. Each row of these grids corresponds to measurements or values of an instance, while each column is a vector containing data for a specific variable. This means that a data frame’s rows do not need to contain, but can contain, the same type of values: they can be numeric, character, logical, etc.

Now, DataFrames in Python are very similar: they come with the pandas library, and they are defined as two-dimensional labeled data structures with columns of potentially different types.

In general, you could say that the pandas DataFrame consists of three main components: the data, the index, and the columns.

### Benefits of Pandas:

Again according to the Python Package Index organizers, Pandas delivers several key benefits to data scientists and developers alike, including:

1. Easy handling of missing data (represented as NaN) in both floating point and non-floating point data.
2. Size mutability: columns can be inserted and deleted from DataFrames and higher-dimensional objects.
3. Automatic and explicit data alignment: objects can be explicitly aligned to a set of labels, or the user can simply ignore the labels and let series, DataFrame, etc. automatically align the data in computations.
4. Powerful, flexible group-by functionality to perform split-apply-combine operations on data sets for both aggregating and transforming data.
5. Making it easy to convert ragged, differently indexed data in other Python and Numpy data structures into DataFrame objects.
6. Intelligent label-based slicing, fancy indexing, and subsetting of large data sets.
7. Intuitive merging and joining of data sets.
8. Flexible reshaping and pivoting of data sets.
9. Hierarchical labeling of axes. (possible to have multiple labels per tick)
10. Robust I/O tools for loading data from flat files (CSV and delimited), Excel files, databases, and saving/loading data from the ultrafast HDF5 format.
11. Time series-specific functionality: date range generation and frequency conversion, moving window statistics, date shifting, and lagging.

Additional benefits derived from the Pandas library include data alignment and integrated handling of missing data; data set merging and joining; reshaping and pivoting of data sets; hierarchical axis indexing to work with high-dimensional data in a lower-dimensional data structure; and label-based slicing.

### Pandas and Data Scientists:

Pandas addresses the many shortcomings that data scientists often encounter when using languages associated with scientific and business research environments. In data science, working with data is usually sub-divided into multiple stages, including the aforementioned munging and data cleaning; analysis and modeling of data; and organizing the analysis into a form agreeable for plotting or display in tabular form. For these and other mission-critical data science tasks, Pandas excels.

### Python and Pandas:

Given that Pandas is built on top of the Python programming language, a brief review of the Python programming language is in order.

A favorite with data scientists owing to its ease-of-use, Python has evolved from its earliest roots in 1991 to be one of the most popular programming languages for web applications, data analysis, and machine learning. 
Python’s ease-of-use means even beginners can produce programs with relatively little up-front time investment owing to Python’s highly readable syntax. This means developers and data scientists spend more time-solving business problems and less time wrestling with language complexities.
Python runs on every significant operating system in use today, as well as major libraries in addition to Pandas. API services also have Python links or so-called wrappers. This allows Python to interface with other services and libraries.

In addition to its ease of use, Python has become a favorite for data scientists and machine learning developers for another good reason. With the availability today of data-handling libraries like Pandas and Numpy, and with data visualization tools like Seaborn and Matplotlib, Python is lingua franca for machine learning and the data scientists and developers building machine learning systems.

### Drawbacks:

Pandas has been criticized for its inefficiency. Pandas can require 5 to 10 times as much memory as the size of the underlying data, and the entire dataset must be loaded in RAM. The library does not optimize query plans or support parallel computing across multiple cores. Wes McKinney, the creator of Pandas, has recommended Apache Arrow as an alternative to address these performance concerns and other limitations.

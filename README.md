### Python-Numpy, Pandas, Matplotlib, Seaborn
Basics of Numpy, Pandas , Matplotlib, Seaborn | Projects

👉1. Why Numpy?
NumPy arrays are faster and more compact than Python lists. An array consumes less memory and is convenient to use. NumPy uses much less memory to store data and it provides a mechanism of specifying the data types.

👉2. Why Pandas?
Pandas is a Python library for data analysis. Pandas is built on top of two core Python libraries—matplotlib for data visualization and NumPy for mathematical operations. Pandas acts as a wrapper over these libraries, allowing you to access many of matplotlib's and NumPy's methods with less code.

👉3. Why Matplotlib?
Matplotlib is a multi-platform data visualization library built on NumPy arrays.

👉4. Why Seaborn ?
Seaborn is a library in Python predominantly used for making statistical graphics. Seaborn is a data visualization library built on top of matplotlib and closely integrated with pandas data structures in Python. Visualization is the central part of Seaborn which helps in the exploration and understanding of data.


#### Project - Pandas - Exploring Countries Economic Data

1) Importing Data into Python
To start working with data in Python, you first need to import it. This can be done using various libraries such as pandas, numpy, or csv. The most common way is to use pandas to import data from files like CSVs, Excel, or SQL databases.

2) DataFrame via Pandas
A DataFrame is the core data structure in pandas. It is essentially a 2-dimensional table with rows and columns, similar to a spreadsheet. You can create a DataFrame from lists, dictionaries, or other data sources.

3) Exploring Datasets: head(), tail(), info(), describe()
head(): Returns the first 5 rows of the DataFrame.
tail(): Returns the last 5 rows of the DataFrame.
info(): Provides a concise summary of the DataFrame, including the data types of each column and the number of non-null entries.
describe(): Provides summary statistics (like mean, median, min, max, etc.) for numeric columns.

4) Renaming Columns
You can rename the columns of a DataFrame using the rename() function, specifying the old column names and the new ones in a dictionary.

5) Subsetting DataFrames
Subsetting involves selecting specific rows and columns. This can be done using column names and row indexes. You can subset a DataFrame using loc[] (label-based) or iloc[] (position-based).

6) Basic Operations with DataFrames
You can perform basic mathematical operations on DataFrames, like addition, subtraction, multiplication, or division between columns or with scalar values.

7) Filtering DataFrames
Filtering is selecting rows that meet specific criteria. You can use conditional statements to filter the data.

8) Seaborn Introduction
Seaborn is a data visualization library built on top of matplotlib. It provides a high-level interface for creating attractive statistical graphics. Common plots include histograms, scatter plots, box plots, and heatmaps.

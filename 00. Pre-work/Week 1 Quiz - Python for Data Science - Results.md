Quiz - Python for Data Science (Week 1)
Type
:
Mandatory Assessment
Attempts
:
1/1
Questions
:
15
Time
:
1h
Due Date
:
Jul 30, 3:00 AM CDT
Your Marks
:
13/15
Instructions

Attempt History
1
Jul 25, 5:14 PM
Marks: 13
Q No: 1
Correct Answer
Marks: 1/1




Which of the following will be the output of the below snippet?

import numpy as np
demo_matrix = np.array(([13,35,74,48], [23,37,37,38],[73,32,93,39]))
demo_matrix[2,3]

37


39

You Selected

93


32

np.array() function is used to create a 2D matrix named demo_matrix.

demo_matrix[2,3] returns the element present in the 3rd row (indexing in Python starts at 0) and 4th column.


Q No: 2
Correct Answer
Marks: 1/1

Which of the following will be the output of the below snippet?

import numpy as np
np.arange(0,22,6)

array([0, 1, 2, 3, 4, 5])


array([0, 6, 12])


array([0, 6, 12, 18])

You Selected

array(0, 6, 12, 18, 22)

np.arange([start],[end],[step])

The above function returns values within the interval start and end, where step is the distance between two adjacent values.


Q No: 3
Correct Answer
Marks: 1/1

Which of the following will be the output of the below snippet?

import numpy as np
demo_array = np.arange(10,17)
demo_array [:]= 101
demo_array

array = (101)


array = ([101])


array = [(101, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20)]


array = ([101, 101, 101, 101, 101, 101, 101])

You Selected
line 2 creates an array of values from 10 to 16, line 3 assigns ‘101’ to all the index positions of the subset.

Q No: 4
Correct Answer
Marks: 1/1

Which of the following will be the output of the below snippet?

import pandas as pd
score = [10, 15, 20, 25]
pd.Series(data=score, index = ['a','b','c','d'])

a    10

b    15

c    20

d    25

dtype: int64

You Selected

1    10

2    15

3    20

4    25

dtype: int64


0    10

1    15

2    20

3    25

dtype: int64


None of the above

pd.Series() creates an 1D array with the mentioned index names for the elements. Default indexing in pd.series() starts from 0 unless index is specified.

Q No: 5
Correct Answer
Marks: 1/1

What is the right way to create a list in Python?

football = (24, 23, 34, 46, 65, 67)


football = {24, 23, 34, 46, 65, 67}


football = [24 23 34 46 65 67]


football = [24, 235, 34, 456, 65, 67]

You Selected
Elements of a list are always declared inside a square bracket and are separated from each other by comma

Q No: 6
Correct Answer
Marks: 1/1

Which of the following is true for the following code?

dataframe.drop(‘marks’, axis = 1)
where, 'marks' is an attribute of the dataframe.


axis 1 is for searching rows


axis 0 is for searching columns


axis 1 is for searching columns

You Selected

axis 0 is for searching rows

0 is horizontal axis and 1 is vertical axis.

Q No: 7
Correct Answer
Marks: 1/1

Which of the following can be used to see the frequency distribution of a categorical variable?

sns.distplot()


sns.countplot()

You Selected

sns.scatterplot()


sns.factorplot()

Countplot is used on a single categorical variable to view its frequency distribution.

Q No: 8
Correct Answer
Marks: 1/1

Which of the following is correct for the full outer join?

It keeps only those rows that match the dataframes.


It keeps all the rows from both dataframes.

You Selected

It includes all the rows of dataframe x and only those from y that match.


It includes all the rows of dataframe y and only those from x that match.

Q No: 9
Correct Answer
Marks: 1/1

The following plot shows the number of students in each field of study in a school. Study the plot and select the correct option:

Bar.png


Commerce has neither the highest nor the lowest student count

You Selected

Arts has more number of students as compared to Commerce


Science and Arts have the exact same number of students


Commerce has least number of students

As observed from the above graph, Science has the highest number of students and Arts has the lowest number of students. So, Commerce has neither the highest nor the lowest student count.

Q No: 10
Incorrect Answer
Marks: 0/1

Guess the code for the below output, where 'auto' is the dataframe and 'acc' and 'disp' are two of its attributes.

f.png


sns.pairplot(auto[['disp','acc']])


sns.scatterplot(auto[['acc','disp']])

You Selected

sns.histplot(auto[['disp','acc']])


sns.pairplot(auto[['acc','disp']])

Correct Option
Pairplot() plots multiple variables for bivariate analysis. It plots the variables in the order mentioned from left to right.

Q No: 11
Correct Answer
Marks: 1/1

Which of the following is the most appropriate snippet to return the below output?

stripplot.JPG

X-axis label: "wt"

Y-axis label: "cyl"


sns.scatterplot(auto['wt'], auto['cyl'])


sns.stripplot(auto['cyl'], auto['wt'])


sns.stripplot(auto['wt'],auto['cyl'])

You Selected

sns.barplot(auto['wt'], auto['cyl'])

sns.stripplot(auto['wt'],auto['cyl'])

Here, ‘wt’ is the x-axis and ‘cyl’ is the y-axis, stripplot() with the appropriate parameters create the above plot.


Q No: 12
Incorrect Answer
Marks: 0/1

Which of the below options outputs the following plot? Here 'auto' is the dataframe and 'cyl' and 'yr' are two of its attributes.

h.png


sns.barplot(auto['yr'],auto['cyl'])

You Selected

sns.boxplot(auto['yr'],auto['cyl'])

Correct Option

sns.lineplot(auto['yr'],auto['cyl'])


sns.distplot(auto['yr'],auto['cyl'])

Boxplot with the categorical variable plots multiple boxplots, of instances grouped by the categorical variable.

Q No: 13
Correct Answer
Marks: 1/1

How to view the top 5 rows in a DataFrame named 'auto' ?

auto.count(5)


auto.head()

You Selected

auto()


auto.read(5)

head() returns the top 5 (default is 5. A different number can be specified as required) rows.

Q No: 14
Correct Answer
Marks: 1/1

Select the correct choice (True/False) for the statement given below:

b = 3.1

The data type of b is 'int'.


True


False

You Selected
The datatype of b is float.

Q No: 15
Correct Answer
Marks: 1/1

How can we load an excel file from an external source in Jupyter Notebook?

read_excel("filename")


pd.excel("filename")


pd.load("filename")


pd.read_excel("filename")

You Selected
pd.read_excel() reads an Excel file into a pandas DataFrame.
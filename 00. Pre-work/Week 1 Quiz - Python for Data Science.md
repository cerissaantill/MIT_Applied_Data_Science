Quiz - Python for Data Science (Week 1)


Type: Mandatory Assessment
Attempts: 0/1
Questions: 15
Time: 1h
Due Date: Jul 30, 3:00 AM CDT
Total Marks: 15

MY SCORE: 13/15

Instructions
There might be questions requiring you to use Python - please keep the Jupyter Notebook open when you start the quiz.
Ensure there is a proper internet connection while taking up the quiz. Any breakup in the connection will automatically submit your quiz.
Only attempt the quiz when you are prepared and have enough time on your hands to finish it.
The quiz once opened, must be completed within the time frame provided. You CANNOT start the quiz, leave it unattended for an extended period of time and come back later to finish.
No re-attempts will be provided if the quiz gets submitted for any of the above-mentioned reasons.
Please ensure you attempt the quiz well before the due date. No extension will be provided for any quiz once the deadline is passed.
If you face any other technical issues on Olympus, you should share the screenshot with your Program Manager so that the team can understand and resolve it on priority.
All the best!

#############################################################
1.
Which of the following will be the output of the below snippet?

import numpy as np
demo_matrix = np.array(([13,35,74,48], [23,37,37,38],[73,32,93,39]))
demo_matrix[2,3]


    37

    39 <--

    93

    32

###########
2.
Which of the following will be the output of the below snippet?

import numpy as np
np.arange(0,22,6)


    array([0, 1, 2, 3, 4, 5])

    array([0, 6, 12])

    array([0, 6, 12, 18]) <--

    array(0, 6, 12, 18, 22)


###########
3.
Which of the following will be the output of the below snippet?

import numpy as np
demo_array = np.arange(10,17)
demo_array [:]= 101
demo_array


    array = (101)

    array = ([101])

    array = [(101, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20)]

    array = ([101, 101, 101, 101, 101, 101, 101])     <--

#############
4.
Which of the following will be the output of the below snippet?

import pandas as pd
score = [10, 15, 20, 25]
pd.Series(data=score, index = ['a','b','c','d'])


    a    10
    b    15               <--
    c    20
    d    25
    dtype: int64

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

#############
5.
What is the right way to create a list in Python?


    football = (24, 23, 34, 46, 65, 67)

    football = {24, 23, 34, 46, 65, 67}

    football = [24 23 34 46 65 67]

    football = [24, 235, 34, 456, 65, 67]    <--
    
#############
6.
Which of the following is true for the following code?

dataframe.drop(‘marks’, axis = 1)
where, 'marks' is an attribute of the dataframe.


    axis 1 is for searching rows

    axis 0 is for searching columns

    axis 1 is for searching columns    <--

    axis 0 is for searching rows
    
#############
7.
Which of the following can be used to see the frequency distribution of a categorical variable?


    sns.distplot()

    sns.countplot()    <--

    sns.scatterplot()

    sns.factorplot()
    
#############
8.
Which of the following is correct for the full outer join?


    It keeps only those rows that match the dataframes.

    It keeps all the rows from both dataframes.    <--

    It includes all the rows of dataframe x and only those from y that match.

    It includes all the rows of dataframe y and only those from x that match.
    
#############
9.
The following plot shows the number of students in each field of study in a school. Study the plot and select the correct option:
    
    (bar_graph.png)
    
    Commerce has neither the highest nor the lowest student count   <--

    Arts has more number of students as compared to Commerce

    Science and Arts have the exact same number of students

    Commerce has least number of students
    
#############
10.
Guess the code for the below output, where 'auto' is the dataframe and 'acc' and 'disp' are two of its attributes.

    (bar-graphs, scatter-plots)
    
    sns.pairplot(auto[['disp','acc']])

    sns.scatterplot(auto[['acc','disp']])   <-- ?

    sns.histplot(auto[['disp','acc']])

    sns.pairplot(auto[['acc','disp']])
    
#############
11.
Which of the following is the most appropriate snippet to return the below output?

(stripplot.JPG)

X-axis label: "wt"

Y-axis label: "cyl"
    
    
    sns.scatterplot(auto['wt'], auto['cyl'])

    sns.stripplot(auto['cyl'], auto['wt'])

    sns.stripplot(auto['wt'],auto['cyl'])  <--

    sns.barplot(auto['wt'], auto['cyl'])
    
#############
12.
Which of the below options outputs the following plot? Here 'auto' is the dataframe and 'cyl' and 'yr' are two of its attributes.

(h.png)
y = cyl
x = yr

    sns.barplot(auto['yr'],auto['cyl'])   <-- ?

    sns.boxplot(auto['yr'],auto['cyl'])

    sns.lineplot(auto['yr'],auto['cyl'])

    sns.distplot(auto['yr'],auto['cyl'])


#############
13.
How to view the top 5 rows in a DataFrame named 'auto' ?


    auto.count(5)

    auto.head()   <--

    auto()

    auto.read(5)


#############
14.
Select the correct choice (True/False) for the statement given below:

b = 3.1

The data type of b is 'int'.


    True
    False  <-- (it's a Float)


#############
15.
How can we load an excel file from an external source in Jupyter Notebook?


    read_excel("filename")

    pd.excel("filename")

    pd.load("filename")

    pd.read_excel("filename")   <--



























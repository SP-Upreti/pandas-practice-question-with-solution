# pandas-practice-question-with-solution
Here i have included basic pandas practice question along with its solution.


this questions will provide the basic ideas on how pandas library works.

Here are the questions.


1. Write a Pandas program to create and display a one-dimensional array-like object
containing an array of data using Pandas module


2. Write a Pandas program to convert a Panda module Series to Python list and it's type

3. Write a Pandas program to add, subtract, multiple and divide two Pandas Series.

4.Write a Pandas program to compare the elements of the two Pandas Series.

5. Write a Pandas program to convert a dictionary to a Pandas series.

**Original dictionary:**
{'a': 100, 'b': 200, 'c': 300, 'd': 400, 'e': 800}

**Converted series:**
a 100
b 200
c 300
d 400
e 800

6.Write a Pandas program to convert a NumPy array to a Pandas series.
 Sample Series:
 NumPy array:
 [10, 20, 30, 40, 50]
 Converted Pandas series:
 0 10
 1 20
 2 30
 3 40
 4 50
 
 
7. Write a Pandas program to change the data type of given a column or a Series.
Sample Series:
Original Data Series:
0 100
1 200
2 python
3 300.12
4 400
#datatype : object

#convert to
Change the said data type to numeric:
0 100.00
1 200.00
2 NaN
3 300.12
4 400.00
dtype: float64


8. Write a Pandas program to convert the first column of a DataFrame as a Series.
**Original DataFrame**
col1 col2 col3
0 1 4 7
1 2 5 5
2 3 6 8
3 4 9 12
4 7 5 1
5 11 0 11


1st column as a Series:
0 1
1 2
2 3
3 4
4 7
5 11
Name: col1, dtype: int64
<class 'pandas.core.series.Series'>


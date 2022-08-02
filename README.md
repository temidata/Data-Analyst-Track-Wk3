# Data-Analyst-Track-Wk3: Referencing and Data Modelling 
Summary of what I learnt in the third week of the Master Data Analytics Track with 10Alytics

# Referencing in Excel 
There four common references in Excel
1). Relative Referencing 
2). Absolute Referencing
3). Mixed Referencing 
4). Structured Refrencing 

# Relative Referencing: 
Is the default function in Excel for referencing. No Dolloar sign is required. 
Example: C3:D4

# Absolute Referencing: 
It making a cell constant and making the other cell free without no dollar sign. 
Example: C3:$D$4. The dollar sign locks the D4 cell and it remains constant which means when dragged it wont move to the next cell

# Mixed Referencing: 
Both cells are blocked with dollar sign. Examples: $D$4

#Structured Referencing:
Creating a table and naming the table. 
Shutcut: Select any cell from the range that wants to be converted as table + Ctrl+ t.

Instead of Structured referencing, named ranged can be also be used.  Ctrl+Shift+F3

 
# Data Modelling
Data Modelling entails that relationships are created in the data. For relationships to be possible the data attributes must be relational i.e. one column of a data should be related to another column of another type of data. With this the data can be analyzed and insights can be generated.

# Vlookup Function
VLOOKUP stands for ‘Vertical Lookup’. It is a function that makes
Excel search for a certain value in a column (‘table array’), in order to
return a value from a different column in the same row.

A VLOOKUP function exists of 4 components:

1. The value you want to look up;
2. The range in which you want to find the value and the return value;
3. The number of the column within your defined range, that contains the
return value;
4. 0 or FALSE for an exact match with the value your are looking for; 1 or
TRUE for an approximate match.

Syntax: VLOOKUP([value], [range], [column number], [false or true])

# Index and Match
INDEX & MATCH, when used in conjunction, allow you to build a
more dynamic VLOOKUP. By using this methodology, you can return
values, not only to the right of the lookup value, but also, to the left, above
or below.

• INDEX function allows you to return a specified value within an array

• MATCH function returns the numerical position of text
within an array

# More Advance Data Cleaning: 
Using diagnostic functions for data cleaning 
Functions like 1). ISBLANK 2). ISNUMBER 3). CODE 4). CHAR 5). SUBSTITUTE

# Pratice Exercise 
Click on Go To File to see the application.


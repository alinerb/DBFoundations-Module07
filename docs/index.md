### Aline Benson
### November 28, 2021
### Course: Foundations of Databases & SQL Programming
### Assignment #: 7
### GitHub Link:


## Introduction

This week we learned about SQL defined functions and user defined functions. There are a multitude of functions available in SQL that can be combined to create the result sets that we want. However, when we need a more customized function the User-Defined Functions (UDF) are a great alternative. Below I will detail UDFs and the different types of functions that can be created with a UDF.

## UDF Overview

A **SQL UDF** should be used when the built-in functions of SQL do not meet the needs of your queries. They can be used similarly to views but the result sets can return a single value or tabular result sets (_Randall Root, [Functions-02 User Defined Functions UDFs] (https://www.youtube.com/watch?v=XEiQ3M2LhU4&list=PLfycUyp06LG9wAGPKBZ7poKBcbDZrmXpi&index=2) (external link), 2017; Root, Module 7 Notes, 2021_).

**Scalar functions** return a single value of a particular data type while **Inline** and **Multi-Statement** functions returns a table result set. **Inline** and **Multi-Statement** functions will be called using similar select syntax to a table (i.e., Select *) while **Scalar function** can be called simply by selecting the function and passing the parameters into the function. There are also slight differences in the syntax to create scalar functions versus the tabular functions. **Multi-Statement** functions are the most complex of the three and allow multiple statements. For instance you can create a table and insert data into the table using the set parameters (_Randall Root, [Functions-02 User Defined Functions UDFs] (https://www.youtube.com/watch?v=XEiQ3M2LhU4&list=PLfycUyp06LG9wAGPKBZ7poKBcbDZrmXpi&index=2) (external link), 2017_).

## Summary
This week I used Azure Data Studio to the multitude of functions available to users in SSMS. While some I found easier than others to understand and execute (DATENAME, OVER/PARTITION BY) others gave me some trouble. Mostly the ordering of transformed date fields. I think I struggled because there are multiple ways to show the right answer, but the data type impacts ordering. Once I figured out the best solution for all parts of the question this got much easier. I really enjoyed learning about functions and look forward to bringing these to my everyday work.

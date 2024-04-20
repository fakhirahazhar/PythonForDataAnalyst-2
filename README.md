# PythonForDataAnalyst-2
The Pandas section includes several sub-topics on data analysis, such as getting information about data, handling missing data, selecting specific columns, and calculating statistics a section on the random library and handling date and time data wide range of topics related to data manipulation and analysis using Python and its libraries.

## Function

Python Functions is a block of statements that return the specific task. The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can do the function calls to reuse code contained in it over and over again.

 - In mathematics, a function is a process that relates between an input and an output.
 - In Python, apart from these relationship functions, functions are also a way to organize code with the ultimate goal of code being reusable.
 - Functions are defined with the def keyword followed by the function name and parameters in brackets ().
 - Optionally, a docstring can be added - a documentation string that describes the context of the function.

   <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/395f9bac-83ac-4a8b-be87-d82afe0be7f7" /></div>
   
 - By default, Python will position according to the registration order in which it was defined, and must be called in that order.
   
  <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/a784c1cb-f10c-4009-88d7-0eb0b906ec88" /></div>

## Return

The Phython Return statement is a special statement that can use inside in function or method to send the function’s result back to the caller. A Return statement consist of the return keyword followed by an optional return value. The return value of a Python function can be any Python object.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/8a284d49-2c27-4a53-88e8-32ab2f9589ee" /></div>

  - The return value of a function can be stored in a variable.
  - This will differentiate a function that returns a value from a function that does not return a value (often referred to as a procedure).

   <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/de0f405a-6f6b-44fb-9967-738c1fd64c31" /></div>

## Pass by reference vs value

The difference between pass-by-reference and pass-by-value is that modifications made to arguments passed in by reference in the called function have effect in the calling function, whereas modifications made to arguments passed in by value in the called function can not affect the calling function.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/7647b192-e5bc-416e-9cd6-770deafe1185" /></div>

## NUMPY

NumPy is a Python library used for working with arrays. It also has functions for working in the domain of linear algebra, fourier transform, and matrices. NumPy was created in 2005 by Travis Oliphant. It is an open source project and you can use it freely. NumPy stands for Numerical Python.

 1. NumPy arrays have a fixed size at creation, unlike Python lists. Changing the size of an ndarray will create a new array and  delete the original.   
 2. The elements in a NumPy array are all required to be of the same data type, and thus will be the same size in memory.
      
### The next step is how to apply NumPy in Python
     
 1. Checking NumPy Version

    The “print(np.version)" syntax is used to determine the installed version of NumPy in Python
     <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/91f1eb3a-7a76-442c-9271-7f6b984fc99f" /></div>
     
 2. Import NumPy

    The “import numpy as np” statement is used to import the NumPy library into Python, allowing you to use its functions for numerical calculations and array manipulations.
    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/532c2e38-de73-4097-bcb1-249e9733d800" /></div>
    
 3. Creating a NumPy Array

    To create an ndarray, we can pass a list, tuple or any array-like object into the array() method, and it will be converted into an ndarray.
  
     The syntax used to create a NumPy array from a list or tuple is the same, the only difference being the use of square brackets for a list [ ] and parentheses for a tuple ().
       <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/92acc239-e115-4976-94a4-0c32a8e5df5c" /></div>
    
 4. Creating an array with specific dimensions
    - 1 dimension: 1D arrays in NumPy are essentially like lists in Python. They are sequences of elements arranged in a single line.
      <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/5e0891b8-b6a1-43a0-a75e-df055230bf9c" /></div>
      
    - 2 dimension: 2D arrays in NumPy are like matrices. They have rows and columns, arranged in a grid format.
      <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/31546ff5-378b-4ff3-8a6c-0d18b74ef00e" /></div>
      
    - Creating a 3-dimensional array with two 2-dimensional arrays, both containing two arrays, can be achieved using NumPy as follows:
      <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/ff910bca-090c-4e08-8e98-9c268286e57a" /></div>
      
 5. Check how many dimensions the arrays have

    The "a = np.array" syntax is used to store an array variable into the NumPy library. And the "print(a.ndim)" syntax is used to provide feedback by displaying dimensional information to the user.
     <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/9494bd84-f0fd-4af0-92e5-f8fd6e27ada0" /></div>

6. Changing one dimension to another

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/a393fc8a-5770-477f-a54b-f1e1d7112496)" /></div>

The syntax "ndmin=5" is used to reshape the dimension created into the fifth dimension.
     
 7. Get the results of the desired elements of the following array
    
     - Get the first element from the following array

      <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/306528a2-0054-4e6d-bcc1-1b4f4936f5ff" /></div>

    To retrieve the first element, you use [0] because the indexing of elements starts from 0, then 1, 2, 3, etc.
    
     - Get the second element from the following array

       <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/62c959ef-7a2d-4a05-95ba-136da2a9e50f" /></div>
        
     - Get the third and fourth element from the following array

        <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/13a6881d-95db-448f-abb4-22e771966236" /></div>

      The "(arr[2] + arr[3])" syntax is used to find two elements, namely the third element and the fourth element.
    
 8. Accessing elements from a specified array.

      - Access the element on the first row, second column.

        <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/1c315d22-768b-4cc9-8afb-fa479e621d40" /></div>
   
     The "arr[0, 1]" syntax is used to retrieve the element at 1st row and 2nd column.

      - Access the element on the 2nd row, 5th column

        <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/01dfae67-3c78-4d24-b8f2-d2291d834b01" /></div> 

      - Access the third element of the second array of the first array

      <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/e8caa867-676f-40d9-aa14-58eeefa8bdbe" /></div>

      The "arr[0, 1]" syntax is used to access the 2nd dimension, the 1st row, and the 3rd element.

## Pandas

Pandas is a powerful and widely used open-source Python library primarily used for data manipulation and analysis. It provides high-performance data structures and tools for working with structured data, making it an essential tool for data scientists and analysts.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/a7b6be33-8e69-4697-a39d-77c016c2492f" /></div>

Pandas has two main objects: Series and DataFrame.

## Series

The Series object is a ONE-dimensional array that can store various types of data, such as integers, floats, strings, and others. It does not have column names as it consists of only one column. Each element in a Series has a label called an index.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/6cfa0e5f-7da8-4a0a-b272-c53e387c8f29" /></div>

Convert it into a Series

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/0a3257e9-45f8-4daa-a69f-74251f5ccc8e" /></div>

Convert the Series to an array

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/ed6b7da7-5b4b-45b4-9c5f-d3590cf412fa" /></div>

Display the indices.

The indices are represented as a range, where the start point is inclusive, and the stop point is exclusive in the range.

 - Implicit indexing: Default numerical index assigned based on positional order.
 - Explicit indexing: Custom labels or values are assigned to uniquely identify rows or columns

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/f264d6ba-db99-46ff-a307-b6a41c86ff4e" /></div>

When the implicit and explicit indices are the same, when we call the data, it will rely only on its explicit indices.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/4a9ebbe0-3831-4473-8f00-e77dd509f539" /></div>

The result of name_2[0] is an error due to the similarity between the explicit indices and the implicit indices.

We'll now try to perform data-slicing

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/0a41f3c4-4b22-483a-ac4f-884ca376c1e9" /></div>

But if we slice its implicit indices, only the start point will appear, because implicit indices are in the form of a range

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/3a59049b-1dae-4c5a-a1bb-96610ddc2591" /></div>

## Ioc and iloc

Example of data where some implicit and explicit indices are the same.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/63fac39f-39dd-401c-a473-5d0e0a111443" /></div>

When we access a single index, it will display its explicit index.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/04d5670a-895d-4a2d-abad-d2b011bda3de" /></div>

When explicit and implicit indices are the same, inconsistencies occur as in the case above.

To address this inconsistency, we will use the principles of loc and iloc.

loc is used to call its explicit indices, while iloc is used to call its implicit indices.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/ba91494d-c6f5-47ed-8659-6a11d93ff096" /></div>

## Dictionary -- Series

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/bc052728-cc8d-42a7-88aa-caca8da87aa9" /></div>

## Data Frame

DataFrame is a two-dimensional tabular data structure with labeled axes (rows and columns). This allows for easy manipulation and analysis of data. Essentially, a DataFrame is a collection of series, with at least one series.

DataFrame With 2 Series : 

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/494b1989-2362-447c-931f-07b5f6e835a2" /></div>

## Load Data CSV

For example load data ‘Kelahiran_Bayi_Jakarta_2020’.csv that has been aplouded in the same folder in Python.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/51c90d68-1ebe-47a7-9b8b-0f8bbcc34fb2" /></div>

 - Head()    : Head()function to a viewing top in data by default is top five can be customized as required.
   
    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/59059804-7fc9-4edb-a4a0-ed62fc15ac23" /></div>
   
 - Tail()    : Tail()returns the last 5 rows if a number is not specified,returns a specified number of last rows.

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/e2e24fb5-5df3-4133-98c8-eee64a18eb3c" /></div>
    
 - Info()    : Info()Info method prints information about the DataFrame.

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/8a59be01-3bda-42cc-99bc-9be1a0985323" /></div>
     
 - IsNull()  : isnull used to finds NULL values in DataFrame.

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/c7e5bed2-b016-4767-9cae-2cc03800f8d9" /></div>
    
 - NotNull() : notnull used to finds values that are NOT NULL.

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/9c475f88-d6a7-4145-b53c-709ed2e99ab6" /></div>
    
 - Shape     : Shape is the number of rows and columns on the index of the DataFrame.

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/3a7bc1ce-7954-4593-a4b3-d0da34f761ba" /></div>
    
 - Columns   : Column returns the label of each column in the DataFrame.

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/12a28d28-921f-4cc5-9587-1299add1859f" /></div>

 - Describe  : Returns a description summary for each column in the DataFrame,describe contains numeric data from managed datasets.

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/ccd2e589-ea6f-401f-ae42-ca5f453d7840" /></div>

 - Mean      : Returns a description summary for each column in the DataFrame.

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/c8d4d8e2-e99b-4bbe-b31a-f46722c198e0" /></div>
    
 - Median    : Returns a description summary for each column in the DataFrame.

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/73c24bab-83b5-45e5-9bf5-c2b9856aa47a" /></div>
    
 - Mode      : Returns a description summary for each column in the DataFrame.

    <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/0dbdb6b6-c7d3-4f0d-b97e-c84e24b3f707" /></div>

 - The df.unique() syntax is used to get unique values in the columns of a pandas DataFrame.

   <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/0967feba-0142-468b-9dc7-b789d4423f1c" /></div>
   
 - The df.nunique() is a function in Python that is used to get the unique number of values in a column or axis in a DataFrame.

   <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/463dcddc-3bc6-4af3-bbfb-b14d00683a47" /></div>
   
 - The df.type_value_counts() is a method on a DataFrame in pandas that is used to count the number of occurrences of each unique value in a column, while ordering them based on the number of occurrences.

   <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/1e8617d8-6f8a-41d7-87cf-5fe545500d6d" /></div>
   
 - Call a specific column is a notation for retrieving certain columns from a DataFrame df. This notation will return a new DataFrame containing only the specified columns.

   <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/435679f5-a83c-49c4-b10b-0ed2e067f866" /></div>
   
 - Calling a Python dataset with terms and conditions means retrieving or selecting certain data from a dataset based on certain terms or conditions. This can be done using boolean operators or logical statements, such as ==, !=, <, >, <=, >=, or and, or, not.

   <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/80228fef-3b6c-406b-807f-c73af6433068" /></div>
   
 - Calls several columns accompanied by a filter terms and conditions

   <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/352ebeb7-cefb-42c3-b9b7-d7132bf0ef6c" /></div>

## DateTime

DateTime is a module in Python that deals with real-time data and time. It provides classes and functions to manipulate and format dates and times. Here are some commonly used classes and functions in the DateTime module. 

 - date : This class represents a date (year, month, and day) without time.
 - datetime : This class represents a date and time (year, month, day, hour, minute, second, and microsecond).
 - time : This class represents time (hour, minute, second, and microsecond) without a date.

 <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/405fd1ee-d2d9-406e-975f-742fbc3832b1" /></div>

## Random Library 

The random module in Python provides various functions to generate random numbers. Here are some commonly used functions in the random library:
 
 - random.random(): This function returns a random float number between 0.0 to 1.0.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/b7787cc9-dd62-4f40-bbaf-06171d510394" /></div>

## Load Data TXT (Txt File - Open - Read - Close)

 - Open : In Python, you can open and read a text file using the built-in open() function. The open() function in Python is used to open a file and return a file (.txt) object.

   <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/7e528b2c-4ab5-4107-8f89-106d2eb74b1a" /></div>
   
 - Read : The read() function in Python is used to read the contents of a file object that has been opened using the open() function.

  <div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/d9df1c7d-83ce-4f15-8a57-b2f8f11f13a3" /></div>

 - Close : The close() function in Python is used to close a file that has been opened using the open() function. This is important because it frees up system resources and ensures that any changes made to the file are saved.

<div align="center"><img src="https://github.com/fakhirahazhar/PythonForDataAnalyst-2/assets/165735471/c58e879b-5acb-4e02-babb-53c39b5df11f" /></div>




       

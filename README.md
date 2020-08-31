# Movies-ETL
-----------------------------------------------------------------------------------------------------
## Executive Overview ##
-----------------------------------------------------------------------------------------------------
This project was quite tedious and pretty lengthy.  However, this was good practice for what the ETL
process will look like in the real world.  In my opinion, I can see how regular expressions can aid 
cleaning up columns.  The Pandas library was also useful in this project.

Admittedly, I need more practice in using some of the transformation techniques demonstrated in this 
project. 

Below, I highlighted some of the techniques that I believe will be useful in the work environment.

----------------------------------------------------------------------------------------------------
## Skills Demonstrated ##
----------------------------------------------------------------------------------------------------
### _Extraction_ ### 

> Extracted the Wikipedia Movies JSON and data from Kaggle

![](https://github.com/GR8505/Movies-ETL/blob/master/Images/Extraction.png)

---------------------------------------------------------------------------------------------------
### _Transformation_ ###

---------------------------------------------------------------------------------------------------
> Used list comprehension to filter data and used pandas to convert movies file to a dataframe.
---------------------------------------------------------------------------------------------------
![](https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation1.png)


---------------------------------------------------------------------------------------------------
> Worked on creating an empty dictionary, loops and perfomed column name consolidation
---------------------------------------------------------------------------------------------------
![](https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation2.png)


---------------------------------------------------------------------------------------------------
> Performed cleaning techniques such as:
1. Removal of duplicate rows
2. Smart deletion of columns with high level of missing values
3. Dropping of NA values
4. Using lambda function
---------------------------------------------------------------------------------------------------
![](https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation3.png)


---------------------------------------------------------------------------------------------------
> Used Regular Expressions (Regex) to perform some cleaning of the data
--------------------------------------------------------------------------------------------------
![](https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation4.png)


--------------------------------------------------------------------------------------------
> Other cleaning techniques were demonstrated:
1) Parsing through data values and applying changes
2) Dropping unnecessary columns
3) Creating new variables
4) Converting lists to strings
-------------------------------------------------------------------------------------------
![](https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation5.png)


-------------------------------------------------------------------------------------------
> Performed other cleaning techniques, including:
1) to_numeric() method
2) Pandas built-in datetime() function
-------------------------------------------------------------------------------------------
![](https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation6.png)


-------------------------------------------------------------------------------------------
### _Loading_ ###

------------------------------------------------------------------------------------------
> Connecting Pandas and SQL to load dataframe
------------------------------------------------------------------------------------------
![](https://github.com/GR8505/Movies-ETL/blob/master/Images/Load.png)


------------------------------------------------------------------------------------------

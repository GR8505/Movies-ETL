# Movies Extract Transform Load (ETL)

-------------------------
## Executive Overview ##
-------------------------
This project was quite tedious and pretty lengthy.  However, this was a great example of what the ETL
process looks like for most Data Scientist positions.  I will never forget my first Data Analytics lesson
from Professor Gour Saha, _"Data is Dirty"_.  He couldn't be more accurate and while most analysts are
chomping at the bit to perform all the sexy stuff like, data visuals and machine learning, ETL is vital 
and this is the task that will take up most of our time.

In completing this assignment, I truly appreciated the use of regular expressions (RegEx) and functions in 
creating an automated ETL pipeline.  Unsurprisingly, the Pandas library was also quite useful in this process.
Admittedly, I definitely need more practice in using some of the transformation techniques demonstrated in 
this project. However, I highlighted some of the techniques that I believe will be useful in the work 
environment.

-----------------
## Objectives ##
-----------------
* Create an automated ETL pipeline
* Extract movies data from multiple sources
* Clean and transform the data automatically using Pandas and RegEx
* Load new data into PostgreSQL

-----------
## Data ## 
-----------
* Wikipedia data
* Kaggle metadata
* MovieLens rating data (from Kaggle)

----------------
## Resources ##
----------------
* Python
* RegEx
* Pandas
* SQLAlchemy
* PostgreSQL

-----------------
## Extraction ##
-----------------
This is how the data was [extracted](https://github.com/GR8505/Movies-ETL/blob/master/Images/Extraction.png).

---------------------
## Transformation ##
---------------------
Used [list comprehension](https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation1.png) to filter data and  Pandas to convert movies file to a dataframe.

Created an empty dictionary, loops and column name consolidation.
<img src="https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation2.png" alt="drawing" width="800"/>

Performed [cleaning techniques](https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation3.png) such as:
1. Removal of duplicate rows
2. Smart deletion of columns with high level of missing values
3. Dropping of NA values
4. Using lambda function

Used [Regex](https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation4.png) to perform some cleaning of the data.

Other cleaning techniques demonstrated:
1) Parsing through data values and applying changes
2) Dropping unnecessary columns
3) Creating new variables
4) Converting lists to strings

<img src="https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation5.png" alt="drawing" width="800"/>

Performed other [cleaning techniques](https://github.com/GR8505/Movies-ETL/blob/master/Images/Transformation6.png), including:
1) to_numeric() method
2) Pandas built-in datetime() function

--------------
## Loading ##
--------------

Connecting Pandas and SQL to [load](https://github.com/GR8505/Movies-ETL/blob/master/Images/Load.png) dataframe.



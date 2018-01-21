# Module-3---Week-1-Quiz
Module 3- Week 1 - Quiz
1. Question 1
The American Community Survey distributes downloadable data about United States communities. Download the 2006 microdata survey about housing for the state of Idaho using download.file() from here:

https://d396qusza40orc.cloudfront.net/getdata%2Fdata%2Fss06hid.csv

and load the data into R. The code book, describing the variable names is here:

https://d396qusza40orc.cloudfront.net/getdata%2Fdata%2FPUMSDataDict06.pdf

How many properties are worth $1,000,000 or more?

2. Question 2
Use the data you loaded from Question 1. Consider the variable FES in the code book. Which of the "tidy data" principles does this variable violate?


Tidy data has variable values that are internally consistent.


Numeric values in tidy data can not represent categories.


Each variable in a tidy data set has been transformed to be interpretable.


Tidy data has one variable per column.

3. Question 3
Download the Excel spreadsheet on Natural Gas Aquisition Program here:

https://d396qusza40orc.cloudfront.net/getdata%2Fdata%2FDATA.gov_NGAP.xlsx

Read rows 18-23 and columns 7-15 into R and assign the result to a variable called:



1
dat
What is the value of:



1
sum(dat$Zip*dat$Ext,na.rm=T)
(original data source: http://catalog.data.gov/dataset/natural-gas-acquisition-program)

4. Question 4
Read the XML data on Baltimore restaurants from here:

https://d396qusza40orc.cloudfront.net/getdata%2Fdata%2Frestaurants.xml

How many restaurants have zipcode 21231?

5. Question 5
The American Community Survey distributes downloadable data about United States communities. Download the 2006 microdata survey about housing for the state of Idaho using download.file() from here:

https://d396qusza40orc.cloudfront.net/getdata%2Fdata%2Fss06pid.csv

using the fread() command load the data into an R object



1
DT
The following are ways to calculate the average value of the variable



1
pwgtp15
broken down by sex. Using the data.table package, which will deliver the fastest user time?


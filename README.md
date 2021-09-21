# M. Reilly's PyCitySchool with Pandas

## Overview of the school district analysis

Maria and her supervisor from Thomas High School reached out to our team after the csv file used with compiled information on student grades was flagged by the school board as potentially revealing evidence of academic dishonsty in the 9th grade reading and math scores. So, in order to maintain the overall integrity of the data, we have been asked per Maria to first replace all values in question with a marker denonted for undefined values (or "NaN") as we work to replace the values. In other words, we removed the questionable 9th grade scores without needing to comprimise/edit/manipulate the rest of the data feild. 

We will rerun the the analysis done prior without counting the 9th grade and associated values. Afterwards, we will work on recalculating said values. With the new values, we will reevaluate overall comparative percentages and analysis. 

Here, you will find the process detailed in this reported. The csv file referenced is attached in this repository as is the code that we run through the file. 

----

For context, here is the list of deliverables for the original analysis of the school district: 

A high-level snapshot of the district's key metrics, presented in a table format
An overview of the key metrics for each school, presented in a table format
Tables presenting each of the following metrics:
Top 5 and bottom 5 performing schools, based on the overall passing rate
The average math score received by students in each grade level at each school
The average reading score received by students in each grade level at each school
School performance based on the budget per student
School performance based on the school size 
School performance based on the type of school
Before we can begin these tasks, we need to import the datasets into Jupyter Notebook using Python.

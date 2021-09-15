# M. Reilly's PyCitySchool with Pandas

## Overview of the school district analysis

Maria and her supervisor from Thomas High School reached out to our team after the csv file used with compiled information on student grades was flagged by the school board as potentially revealing evidence of academic dishonsty in the 9th grade reading and math scores. So, in order to maintain the overall integrity of the data, we have been asked per Maria to first replace all values in question with a marker denonted for undefined values (or "NaN") as we work to replace the values. In other words, we removed the questionable 9th grade scores without needing to comprimise/edit/manipulate the rest of the data feild. 

We will rerun the the analysis done prior without counting the 9th grade and associated values. Afterwards, we will work on recalculating said values. With the new values, we will reevaluate overall comparative percentages and analysis. 

Here, you will find the process detailed in this reported. The csv file referenced is attached in this repository as is the code that we run through the file. 



## Results
#### How is the district summary affected?
<!-- Stripping the data of the 9th graders in Thomas High School did not skewed the data heavily and most of the other results of other 9th graders and of Thomas High school remain along similar parameters as others schools. -->
<!-- The mean was the most significant change in our data, as we decrease the count of scores and students of Thomas High School might have had a significant change. Nonetheless having examing the data this might not have as big of an impact as one might have had thought. -->

#### How is the school summary affected?


####  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

#### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade
• Scores by school spending
• Scores by school size
• Scores by school type


## Summary 
Using bulleted lists and images of DataFrames as support, address the following questions.



The data dive continues!

Now, it's time to take what you've learned about Python Pandas and apply it to new situations. For this assignment, you'll need to complete one of two (not both) Data Challenges. Once again, which challenge you take on is your choice. Just be sure to give it your all -- as the skills you hone will become powerful tools in your data analytics tool belt.

Academy of Py

Education

Well done! Having spent years analyzing financial records for big banks, you've finally scratched your idealistic itch and joined the education sector. In your latest role, you've become the Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your responsibility is to aggregate the data to and showcase obvious trends in school performance.

Your final report should include each of the following:

District Summary

Create a high level snapshot (in table form) of the district's key metrics, including:
Total Schools
Total Students
Total Budget
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
Overall Passing Rate (Average of the above two)
School Summary

Create an overview table that summarizes key metrics about each school, including:
School Name
School Type
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
Overall Passing Rate (Average of the above two)
Top Performing Schools (By Passing Rate)

Create a table that highlights the top 5 performing schools based on Overall Passing Rate. Include:
School Name
School Type
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
Overall Passing Rate (Average of the above two)
Bottom Performing Schools (By Passing Rate)

Create a table that highlights the bottom 5 performing schools based on Overall Passing Rate. Include all of the same metrics as above.
Math Scores by Grade**

Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.
Reading Scores by Grade

Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.
Scores by School Spending

Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
Overall Passing Rate (Average of the above two)
Scores by School Size

Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).
Scores by School Type

Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).
As final considerations:

Use the pandas library and Jupyter Notebook.
You must submit a link to your Jupyter Notebook with the viewable Data Frames.
You must include a written description of at least two observable trends based on the data.
See Example Solution for a reference on the expected format.
Hints and Considerations

These are challenging activities for a number of reasons. For one, these activities will require you to analyze thousands of records. Hacking through the data to look for obvious trends in Excel is just not a feasible option. The size of the data may seem daunting, but pandas will allow you to efficiently parse through it.

Second, these activities will also challenge you by requiring you to learn on your feet. Don't fool yourself into thinking: "I need to study pandas more closely before diving in." Get the basic gist of the library and then immediately get to work. When facing a daunting task, it's easy to think: "I'm just not ready to tackle it yet." But that's the surest way to never succeed. Learning to program requires one to constantly tinker, experiment, and learn on the fly. You are doing exactly the right thing, if you find yourself constantly practicing Google-Fu and diving into documentation. There is just no way (or reason) to try and memorize it all. Online references are available for you to use when you need them. So use them!

Take each of these tasks one at a time. Begin your work, answering the basic questions: "How do I import the data?" "How do I convert the data into a DataFrame?" "How do I build the first table?" Don't get intimidated by the number of asks. Many of them are repetitive in nature with just a few tweaks. Be persistent and creative!

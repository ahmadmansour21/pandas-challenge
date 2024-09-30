# pandas-challenge

The code for this challenge can be found within the "PyCitySchools" folder in my pandas-challenge github repository.

All of the code was done independently with some minor help from the Xpert Learning Assistant AI Tool with the exception of the already provided code for calculating the passing rates in the "School Summary" section where I asked a classmate for help with debugging.

This assignment consisted of an analysis of data pertaining to the individual performance of students from different schools in math and reading as well as an overall performance of each school. There were comparisons to determine how schools were performing based on the performance of their students.

The first section - District Summary - provided an overall picture of the performance in math and reading with the use of functions like mean() but not without providing demographic data on the amount of schools and students.

The next section - School Summary - provided the same analysis but per school to provide a more detailed picture of these performances: using set_index() and groupby(), we were able to analyze all sorts of data from budget to number of students to passing rates per individual school --> this analysis helped then narrow down the top 5 schools and the bottom 5 schools based on said passing rates and math/reading scores.

The next few sections - Math/Reading Scores by Grade and Scores by School Spending/Size/Type - provided an additional depth to the analysis by breaking down the performance of each school even further. They allowed us to analyze performance by grade using the groupby() function and to analyze the performance by school spending/size/type using bins, pd.cut() and groupby().
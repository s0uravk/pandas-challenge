# pandas-challenge
![education](https://github.com/s0uravk/pandas-challenge/assets/144293972/31877ec1-141d-4d71-9c33-8b79dc2ae2b5)

**Summary**

PyCitySchools summarize various schools data with access to student's individual reading and math score along with type of schools they were in as well as size of schools and per capita student budget. Type of school, Schools sizes and Per capita student budget has effect on student's overall passing rate which is further discussed in the analysis. 

This program requires two input csv files with student's information in one file and school's information in second, which then are merged on school's name to perform required analysis. This script calculate student count, number of schools, percentage of student's passed reading, math or both etc. to create new Dataframes neccessary for analysis such as showcasing the schools based on the student's academic performance, passing rate by grades, categorize student's score by size of school and per capita student budget, which leads to importamt revelation of trends that helps in decision making to enchance schools requiring support.

**Analysis**

At the first glance on our top_schools Dataframe, First five schools are the schools with best overall passing rates and these schools are Charter schools while in our bottom_schools Dataframe, First five schools with worst overall passing rates are all Distrcit schools. Which can also be confirmed later on in out type_summary dataframe where there is an significant difference between the average overall passing rate of District and Charter schools. It could be due to the sizes of those schools as observed in our our top_schools Dataframe, sizes of District schools are much greater than the sizes of Charter school. And that can also be confirmed in our size_summary Dataframe where schools with large number of students has lower passing rate compared to the school with small number of students. Further analysis would be required to check if it is just the size of school that affects the student's acamdemic performance or there could be another factor.

Furthermore, in our spending_summary Dataframe, schools are categorized based on per student capita range and overall passing rate is calculated. Here, we observe that the schools with lesser per capita student budget has great average overall passing rate whereas it starts decreasing as per capita student budget starts increasing. There a strong correlation between these two factors.

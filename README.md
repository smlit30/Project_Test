# School Performance Metrics

## Objective
The purpose of this project was to analyze which factors are most strongly correlated with student performance.  To get into the details here lets define what we consider performance for the students, the group of students analyzed and the data itself.    

In this review performance will simply be how students scored on standardized testing on SAT, Math & ELA performance scores.  

The group of students included in the data from the Illinois State Board of education data as linked to below. 

https://www.isbe.net/pages/illinois-state-report-card-data.aspx

The defintions for each factor tested are listed at the bottom of this page. 

Lastly the machine learning alogrithm testing will be detialed out as follows in this section.  


![FUN AT SCHOOL](https://github.com/smlit30/Project_Test/blob/main/school_art3.jpg)

## Group Workflow

![FUN AT SCHOOL](https://github.com/smlit30/Project_Test/blob/main/Workflow_7_22.jpg)


## Visuals for this Project
Our first visuals includeda layout of zip codes with their proficiency % of ELA & Math scores.
https://public.tableau.com/app/profile/spencer.litzau/viz/FP_Zip1_Trial/Sheet1

https://public.tableau.com/app/profile/spencer.litzau/viz/FP_Zip2_Trial/Sheet2


These next visuals show ELA & Math proficiency of different schools with the average admin salary and vs teach salary as the Y axis. 
https://public.tableau.com/app/profile/spencer.litzau/viz/FP_ELA1_Trial/Sheet6

https://public.tableau.com/app/profile/spencer.litzau/viz/FP_ELA2_Trial/Sheet7

Lastly we have chronic absenteeism compared to math proficiency scores.  
https://public.tableau.com/app/profile/spencer.litzau/viz/FP_MP2_Trial/Sheet5


## Results Summary

We found the following results from our regression test on different school factors for performance.  
  


<details open>
<summary>**DEFINITIONS FOR TESTED FACTORS**</summary>
<br/>
<pre>

### District General Definitions
Type - Options "District or School" - Indicates whether the data is at the school or district level. 

District - Name of School District 

City - City of School/District 

County - County of School/District 

District Type - Determines whether the district includes both elementary school and high shool "UNIT" 

District Size - Broken down into small, medium, and large. Determined by the Illinois State Board of Education. 

Avg Class Size – All Grades  - is the average number of students in each class in a school as of the last day of school.

Student Enrollment - Total students enrolled in that district. 

Student Enrollment - Low Income % - Percent of enrolled students who who receive or live in households that receive Supplemental Nutrition Assistance Program or Temporary Assistance to Needy Families benefits; are classified as homeless, migrant,runaway, Head Start, or foster children; or live in a household where the household income meets the U.S.Department of Agriculture income guidelines to receive free or reduced-price meals.


Avg. Class Size - All grades. The total number of students enrolled divided by the number of classes. 

Avg Teaching Exp - the sum of teaching years for all full-time classroom teachers divided by the number of teachers. 

Bachelor Degree - The percentage of all full-time classroom teachers who have a Bachelor's Degree. 

Masters Degree - The percentage of all full-time classroom teachers who have a Masters Degree. 

Teacher Retention Rate - The three-year average of the percentage of full-time teachers returning to the same school from the previous year. 

Avg. Teacher Salary - the sum of the salaries for all classroom teachers, divided by the number of full-time equivalent classroom teachers.

Avg. Admin Salary -  the sum of the salaries for all school administration, divided by the number of school administration.

### School Factor Definitions

District Type - Determines whether the district includes both elementary school and high shool "UNIT" 

District Size - Broken down into small, medium, and large. Determined by the Illinois State Board of Education. 

Student Enrollment - Total	- Total enrollment for the school. 

Student Enrollment - Low Income % - Percent of enrolled students who who receive or live in households that receive Supplemental Nutrition Assistance Program or Temporary Assistance to Needy Families benefits; are classified as homeless, migrant,runaway, Head Start, or foster children; or live in a household where the household income meets the U.S.Department of Agriculture income guidelines to receive free or reduced-price meals.

Class Size - All grades. The total number of students enrolled divided by the number of classes. 

Teacher Retention Rate - The three-year average of the percentage of full-time teachers returning to the same school from the previous year. 



</pre>
</details>




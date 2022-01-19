# School_District_Analysis

## Overview

### Purpose
Maria provided school data for the school district. She would like results analyzed and presented in various ways to compare passing students (in math, reading and overall) by school, grade, school type, and school budget. Maria brought a concern forward that there were errors in the 9th grade data for Thomas High School. She asked us to remove this data from the analysis. This will help the school district make appropriate budget and resource decisions to improve student success.


## Analysis

After cleaning up the data to remove prefixes/suffixes and omitting the 9th grade scores from Thomas High School in the analysis we were able to combine the student data with the school data into one DataFrame.
![image](https://user-images.githubusercontent.com/95710184/150044874-7fa3a392-5207-4943-b8f4-105feac76cf6.png)

The data was summarized and analyzed by school, grade level, budget, school size and by school type (charter or district). 

## Results
With 9th graders scores included, Thomas High School overall passing percentage of students was 90.9%. With 9th graders removed from the scores, Thomas High School's overall passing percentage plummeted to 65.1%.  However, this is simply eliminating the scores from 9th graders, but still counting them in the total student count, not giving a clear picture of the results. This is described in the screenshots below and the *Overall Passing Percentage is highlighted in each*.


**Original Results Including 9th Graders at Thomas High School**

![image](https://user-images.githubusercontent.com/95710184/150186069-bf214c0b-c3cf-4ba9-9327-6e1d7e2ee1e4.png)


**Updated Results with the 9th Graders Scores Removed (but 9th Graders Still Counted in Student Count**

![image](https://user-images.githubusercontent.com/95710184/150136315-1e1dbd6a-6e88-4574-b3c0-a5d43ba1025d.png)

**9th Graders Scores Removed and 9th Graders Removed from Student Count to Calculate %**
![image](https://user-images.githubusercontent.com/95710184/150188259-6f8c4eab-6a54-45cb-b7e8-03d98ebeae95.png)


**9th Graders Included in Scores and Totals (Original Analysis)**
*Thomas High School is the 2nd ranked school in the district.*

![image](https://user-images.githubusercontent.com/95710184/150187060-9c76b12a-6b9f-4b42-8517-6a6806e3017a.png)


**9th Graders Removed from Scores and Totals (Repeated Analysis)**
*Thomas High School is still the 2nd ranked school in the district.*
![image](https://user-images.githubusercontent.com/95710184/150183473-9190321a-dca0-4af1-9234-699ba3b4b3bf.png)



### Comparison of Schools by Spending Per Student

![image](https://user-images.githubusercontent.com/95710184/150049030-c5ec0294-fa52-4b8a-840f-7af22d1207cc.png)


### Comparison of School Size
Large schools (2000-5000 students) performed much worse than smaller schools. Only 58% of students in large schools passed math and reading overall, compared to 90% for small schools (<1000 students) and 91% for medium schools (1000-2000 students).

![image](https://user-images.githubusercontent.com/95710184/150048818-ced0ac09-d880-42a3-85d5-342a918bbbe6.png)

### Comparison of School Type
Charter Schools performed better than District Schools.
![image](https://user-images.githubusercontent.com/95710184/150048420-5d104b08-4913-4e08-af2f-e042a11dc26b.png)



## Summary

When assessed based only on the scores of 10th-12th graders and the total students in 10th-12th grade, it is determined that **removing the 9th grade scores had little effect on the results and rankings of Thomas High School.**

With the inclusion of the 9th graders at Thomas High School, they were ranked in the top 5 schools in the district. Excluding the 9th graders bumps Thomas High School down the list and they are no longer in the top 5, leaving all charter schools in the top 5.

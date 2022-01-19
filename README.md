# School_District_Analysis

## Overview

### Purpose
Maria provided school data for the school district. She would like results analyzed and presented in various ways to compare passing students (in math, reading and overall) by school, grade, school type, and school budget. Maria brought a concern forward that there were errors in the 9th grade data for Thomas High School. She asked us to remove this data from the analysis. This will help the school district make appropriate budget and resource decisions to improve student success.


## Analysis

After cleaning up the data to remove prefixes/suffixes and omitting the 9th grade scores from Thomas High School in the analysis we were able to combine the student data with the school data into one DataFrame.
![image](https://user-images.githubusercontent.com/95710184/150044874-7fa3a392-5207-4943-b8f4-105feac76cf6.png)

The data was summarized and analyzed by school, grade level, budget, school size and by school type (charter or district). 

## Results

###Removing 9th Graders from Scores and/or Student Count Impacts Results

With 9th graders scores included, Thomas High School overall passing percentage of students was 90.9%. With 9th graders removed from the scores, Thomas High School's overall passing percentage plummeted to 65.1%.  However, this is simply eliminating the scores from 9th graders, but still counting them in the total student count, not giving a clear picture of the results. When 9th graders scores are removed and the 9th graders are removed from calculating the passing percentage, the overall passing percentage is 90.6%, only a slight decrease from when the 9th graders were included. This is described in the screenshots below and the *Overall Passing Percentage is highlighted in each*.

**Original Results Including 9th Graders at Thomas High School**

![image](https://user-images.githubusercontent.com/95710184/150188609-4aa6374b-9ead-47ab-809b-59195aff99fe.png)

**Updated Results with the 9th Graders Scores Removed (but 9th Graders Still Counted in Student Count**

![image](https://user-images.githubusercontent.com/95710184/150136315-1e1dbd6a-6e88-4574-b3c0-a5d43ba1025d.png)

**9th Graders Scores Removed and 9th Graders Removed from Student Count to Calculate %**
![image](https://user-images.githubusercontent.com/95710184/150188259-6f8c4eab-6a54-45cb-b7e8-03d98ebeae95.png)

###Examining Rankings 
**9th Graders Included in Scores and Totals (Original Analysis)**
*Thomas High School is the 2nd ranked school in the district.*

![image](https://user-images.githubusercontent.com/95710184/150187060-9c76b12a-6b9f-4b42-8517-6a6806e3017a.png)


**9th Graders Removed from Scores and Totals (Updated Analysis)**
*Thomas High School is still the 2nd ranked school in the district.*
![image](https://user-images.githubusercontent.com/95710184/150183473-9190321a-dca0-4af1-9234-699ba3b4b3bf.png)

### Comparing Schools by Spending Per Student
There is very minimal difference in results between the original analysis (including 9th graders) and the updated analysis (with 9th graders removed). Because Thomas High School is in the $630-$644 bin, the minimal changes are noted in that row.

**Original Result**

![image](https://user-images.githubusercontent.com/95710184/150191978-79e6e280-9bbc-4d8e-99e7-8928f367589b.png)

**Updated Analysis**

![image](https://user-images.githubusercontent.com/95710184/150192183-a684fb38-c010-448d-8f4d-a97109a1058e.png)


### Comparison of School Size
Large schools (2000-5000 students) performed much worse than smaller schools. Only 58% of students in large schools passed math and reading overall, compared to 90% for small schools (<1000 students) and 91% for medium schools (1000-2000 students). Again there is very minimal difference between the original and updated analysis and, when rounded, the results are the same. To observe the minimal differences, results would need to be shown down to several decimal places.

![image](https://user-images.githubusercontent.com/95710184/150048818-ced0ac09-d880-42a3-85d5-342a918bbbe6.png)

### Comparison of School Type
Charter Schools performed better than District Schools overall. However, removal of the 9th graders did not change the original analysis unless results are shown down below whole number values.

![image](https://user-images.githubusercontent.com/95710184/150048420-5d104b08-4913-4e08-af2f-e042a11dc26b.png)


## Summary
Overall, it is determined that **removing the 9th graders from the calculations had little effect on the results and rankings for Thomas High School or the district as a whole.** The number of 9th graders at Thomas High School is very small compared to the overall student population in the district. Imapacts are only percebtible if results are shown down to at least 0.1%.

- Math and reading scores are minimally impacted by removing the 9th graders. 
- Thomas High School remains the 2nd highest ranked high school, regardless of inclusion or exclusion of 9th graders scores.
- School Size analysis is minimally impacted by removal of the 9th graders scores and counts.
- Removal of 9th graders did not impact the analysis results for school type.

# School_District_Analysis

## Overview

### Purpose
Maria provided school data for the school district. She would like results analyzed and presented in various ways to compare passing students (in math, reading and overall) by school, grade, school type, and school budget. Maria brought a concern forward that there were errors in the 9th grade data for Thomas High School. She asked us to remove this data from the analysis. This will help the school district make appropriate decisions about finding and ideally improve student success.


## Analysis

After cleaning up the data to remove prefixes/suffixes and omitting the 9th grade scores from Thomas High School in the analysis we were able to combine the student data with the school data into one DataFrame.
![image](https://user-images.githubusercontent.com/95710184/150044874-7fa3a392-5207-4943-b8f4-105feac76cf6.png)

The data was summarized by school, specific to Thomas High School, by grade level and by school type (charter or district). 



## Results
The initial results for Thomas High school (including 9th graders) confirms the 9th grade scores were skewing the results. With 9th graders included, Thomas High School overall passing percentage of students was 90.9%. With 9th graders removed from the scores, Thomas High School's overall passing percentage plummeted to 65.1%. While not conclusive evidence that tampering with scores occurred, the significant change warrants further investigation.

![image](https://user-images.githubusercontent.com/95710184/150136268-fde345e8-4d29-4e53-9fc0-c8449a0fd756.png)

![image](https://user-images.githubusercontent.com/95710184/150136242-96ea4813-c792-431a-bc99-697007639d51.png)

The updated results with 9th graders scores removed were:

![image](https://user-images.githubusercontent.com/95710184/150136408-05aa8945-125a-4678-884f-713dd9a8a2ba.png)

![image](https://user-images.githubusercontent.com/95710184/150136315-1e1dbd6a-6e88-4574-b3c0-a5d43ba1025d.png)



### Comparison of Schools by Spending Per Student

![image](https://user-images.githubusercontent.com/95710184/150049030-c5ec0294-fa52-4b8a-840f-7af22d1207cc.png)


### Comparison of School Size
Large schools (2000-5000 students) performed much worse than smaller schools. Only 58% of students in large schools passed math and reading overall, compared to 90% for small schools (<1000 students) and 91% for medium schools (1000-2000 students).

![image](https://user-images.githubusercontent.com/95710184/150048818-ced0ac09-d880-42a3-85d5-342a918bbbe6.png)

### Comparison of School Type
Charter Schools performed better than District Schools.
![image](https://user-images.githubusercontent.com/95710184/150048420-5d104b08-4913-4e08-af2f-e042a11dc26b.png)



## Summary
There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).

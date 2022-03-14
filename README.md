# School_District_Analysis

#Overview of the school district analysis: 
Performance trend Analysis of schools across the district using test scores and school funding. Showcasing trends in school performance to assist the superintendent and board of education in deciding their budget allotments for each school in the district. However there have been some issues with the 9th grade test scores. Due to possible impropriety the math and reading scores for the 9th grade at Thomas High School must be removed from our analysis. 

#Results: 

#How is the district summary affected?
Removing the 9th grade test scores did affected the data in relationship to district's scores: 
1. The average math score decreased from 79 to 78
2. % passing math decreased slightly from 75 to 74.8
3. % passing reading also decreased slightly from 86 to 85.7
4. Finally the % Overall passing decreased from 80 to 64.9

See screenshots: 
9th grade THS removed: /Users/jfitz33/Desktop/Screen Shot 2022-03-14 at 1.35.35 PM.png
Full summary: /Users/jfitz33/Desktop/Full_district_summary_df.png

#How is the school summary affected?
The school summary is not affected. The top five school remain the same. 

#How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Before removing the ninth grader's math and reading scores Thomas High School was ranked second in the top schools summary based on percent overall passing.  

#How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade -Thomas High School was ranked 97.3% for reading and 93% for math in the original analysis. However, after removing the 9th graders test scores, Thomas High school's reading dropped slightly below 84% and math also dropped to slightly less than 94%. 
Please see screenshot for further detail: 
/Users/jfitz33/Desktop/Math and reading scores first Analysis .png
/Users/jfitz33/Desktop/Mathand reading scores dropped.png

#Scores by school spending: Did not see any correlation between higher spending equally higher grades. In fact the lowest spending bracket had the highest overall % passing. 
See screen shot:  /Users/jfitz33/Desktop/school spending.png
#Scores by school size: The scores by school size are unchanged. 
#Scores by school type: The same is true for the scores by school size. I do not see any change in results eliminating the ninth graders test scores. The data remains unchanged
#Summary: In summary there were four key changes in the data after removing the 9th grade test scores: 
1. The average math score decreased from 79 to 78
2. % passing math decreased slightly from 75 to 74.8
3. % passing reading also decreased slightly from 86 to 85.7
4. Finally the % Overall passing decreased from 80 to 64.9

If funding is based on test scores and low scores increasing funding, this change could be good for Thomas High School. Although as we saw on the scores by school funding data frame, higher spending does not equal greater test score results. My guess would be there are many other factors involved. Such as student demographics, teachers ability/experience, etc. Unfortunately these items were not in the analysis, therefore we can only go by scores and funding. 


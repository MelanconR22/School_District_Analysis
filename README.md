# School_District_Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.

The data provided for this analysis included csv files containing information about schools and students.  In total, there were 15 schools and the csv file identified the type of school, number of students, and budget.  The type of school provided information about if the school was a district or charter school. The student csv file included information about the students such as name, grade, school, as well as each student's reading and math scores.  

For this analysis, it is worth noting that there are differences between district schools and charter schools.  These differences lead to different standards for academics, programs, as well as admissions.  The funding for the school also does not come from the same source.  I believe that it is important to recognize these differences and understand that comparing district schools to charter schools is not entirely apples to apples.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

##### How is the district summary affected?
* The distric summary was slightly affected when removing the test scores for 9th grade at Thomas High School.  The following chart shows the results with all scores counted in the summary:

![Screenshot 2022-07-27 231843](https://user-images.githubusercontent.com/107599510/181419395-dbd359d2-b25a-4f94-8ad3-73b801f168b8.png)

* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

![Screenshot 2022-07-27 231232](https://user-images.githubusercontent.com/107599510/181418764-9935a9d1-ff21-48fc-ad0e-e1c841a2e0e3.png)

* The average math score was affected slightly by removing the ninth grade scores going from 79% to 78.9%.  The average reading score was not impacted from a rounded percentage standpoint as both scores were 81.9%.  As expected, the passing math, passing reading, and overall percent passing dropped slightly after removing the 461 9th grade scores from Thomas High School.

##### How is the school summary affected?

* Looking at the top five schools, Thomas High School scored in second place with and without the test scores included in the summary.  The following chart shows the results with all scores counted in the summary:

![Screenshot 2022-07-27 233217](https://user-images.githubusercontent.com/107599510/181420997-969cdc8d-aa85-4040-a706-40804ad8eda9.png)

* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

![Screenshot 2022-07-27 233537](https://user-images.githubusercontent.com/107599510/181421396-bff19c65-fc71-45f5-9d5f-74c9f32130be.png)

##### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

* The overall passing percentage changed slightly from 90.94% to 90.63% after the ninth grade test scores were removed.  Thomas High school remained in second place after replacing the math and reading scores.

##### How does replacing the ninth-grade scores affect the following:

##### Math and reading scores by grade

* The above chart provides details about the percentage impact and how the average scores as well as percentages lowered slightly with removal of the grades overall.  It also shows the impact at the grade level.  Removing the ninth grade scores didn't affect the other schools or grade level scores.  However, the removed data did result in a change of the averages and percentages overall for Thomas High School.

##### Scores by school spending

* The following chart shows the results with all scores counted in the summary:

![Screenshot 2022-07-27 234608](https://user-images.githubusercontent.com/107599510/181422646-2c197111-51d8-4827-a482-c492fe070dea.png)

* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

![Screenshot 2022-07-27 234834](https://user-images.githubusercontent.com/107599510/181422895-2d2c4500-7b44-484e-8df5-d73eefee5537.png)

The scores by school spending was identical with the grades included as well as with grades excluded.  I chose to show a little more granular look at the percentages to show that there was no change and that a change wasn't hidden by the rounding of the percentages.  

##### Scores by school size

* The following chart shows the results with all scores counted in the summary:

![Screenshot 2022-07-27 235148](https://user-images.githubusercontent.com/107599510/181423245-0a7766df-33ca-4bd2-98ee-d6eb51d7e24a.png)

* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

![Screenshot 2022-07-27 235303](https://user-images.githubusercontent.com/107599510/181423392-a02aff0f-a01b-4998-be30-920ad391fd94.png)

The medium sized school scores were impacted slightly by the removal of the Thomas High School ninth grade scores.  The overall passing percentage dipped from 90.62% to 90.56%.  This is evidence that Thomas High School is in the middle school size with 1,000 to 1,999 students.

##### Scores by school type

* The following chart shows the results with all scores counted in the summary:

![Screenshot 2022-07-27 235900](https://user-images.githubusercontent.com/107599510/181424126-87c89400-7bb5-4209-aa26-d5163982688c.png)

* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

![Screenshot 2022-07-27 235948](https://user-images.githubusercontent.com/107599510/181424220-91eaa946-28cc-44a0-812d-60db5f2fd983.png)

* The charter school average scores and percentages were impacted slightly by removing ninth grade scores for Thomas High School.  Thomas High School is a charter school so this was expected.  The overall passing percentage dipped from 90.43% to 90.39% for charter schools. 

# Summary: 

#### Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

* There were four changes in the results from the school district analysis after scores for the ninth grade at Thomas High School were replaced with NaNs.  The district summary, school summary, school size, and school type scores and overall percentages were impacted.  In many cases, the impact was small and was only noticeable when using percentages calculated to the millionth place.  In many cases, an impact might not have been realized if percentages were rounded to the nearest tenth. 
 
* This is probably due to the fact that there were a total of 39,170 student scores and 461 of those students were ninth graders at Thomas High School.  The number of ninth graders at Thomas High School represents 1.18% of the total number of students in the sample.  Overall, Thomas High School finished in second place from an overall passing percentage standpoint even when the scores were removed. 

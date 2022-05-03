# School_District_Analysis
## Project Overview
The school board of the City School District has requested an analysis of the performance trends of the district as well as each individual high school. They are specifically looking at the math, reading, and overall performances. Along with performance metrics, the City School District is curious to see if there are any correlations or connections between a school’s budget and student/school performance. Due to claims of altered data, Thomas High School (THS) scores are to be re-analyzed without the 9th-grade scores to see how the changes affected the overall data and to uphold state testing standards. 

## Results
### District Summary
- As shown in Image 1, you can see the percentages of students passing math (75.0%), passing reading (85.8%), and overall passing (65.2%) which included the THS ninth-grade scores. This was the original results of the analysis prior to being informed of altered data. 
  ![District summary DF](https://user-images.githubusercontent.com/102122063/166395594-54ac4172-8e95-436c-b044-a4495a755b7d.png)
  **Image 1:** *The district summary results including Thomas High School 9th grade scores.*
  
- If you refer to Image 2, where the THS ninth-grade scores are removed, you will find that the percentages of each score decreased slightly: passing math (75.0% to 74.8%), passing reading (85.8% to 85.&%), and overall passing (65.2% to 64.9%).
  ![District Summary no THS](https://user-images.githubusercontent.com/102122063/166395674-d972b5ec-37c4-4422-911a-5b2159424f46.PNG)
  **Image 2:** *The district summary results after setting Thomas High School 9th grade scores removed.*

### School Summary
- If we look specifically at the school itself to compare the original analysis results with the re-analyzed results after removing the THS ninth-grade scores, you can see a significant change in values. 
  - The percentage rates for students passing math, passing reading, and overall passing decreased by about 30%. You will find the School Summary with the THS ninth-grade scores in Image 3. Followed by the School Summary with the THS ninth-grade scores removed in Image 4. 
  ![School Summary](https://user-images.githubusercontent.com/102122063/166400153-a87c7c83-0e7a-4676-bb71-ad72359272b1.PNG)
  **Image 4:** *School Summary DataFrame complete with THS ninth-grade scores*
  
  ![School Summary no THS](https://user-images.githubusercontent.com/102122063/166400170-e7ee3631-79ac-415b-8daf-193c9070b77b.PNG)
  **Image 5:** *School Summary DataFRame without THS ninth-grade scores.*
  
### Thomas High School compared with other schools
-	The overall passing percentages of Thomas High School decreased by 0.11%
- The average scores of Thomas High School for math and reading increased by 0.06
![Math_Scores](https://user-images.githubusercontent.com/102122063/166401565-25ce858e-14a9-423f-ace0-302dec1276d1.PNG) ![Readsing_Scores](https://user-images.githubusercontent.com/102122063/166401573-58192f87-caa1-48c4-ade8-4c2057899592.PNG)


-	When we dive deeper into the analysis, we foudn that the school rankings are unchanged. Thomas High School (THS) remained the second ranked of top performing schools   in the district. 
  ![Top_5](https://user-images.githubusercontent.com/102122063/166401477-44f3c0d2-46b7-4da9-8024-d73eb8f15705.PNG)
  **Image 6:** *Top 5 highest performing schools in the district.*
  
- There were no significant findings regarding school spending, school size or school type. The scores did not seem to changed due to removing the THS ninth-grade scores.

## Summary
To conclude, when reading and math scores are replaced with NaNs for the 9th grade students at Thomas High School, there are 4 changes to the school district analysis. The four changes are 1) the percentage of students in the entire district that are passing math, reading, and overall is reduced by a small percentage, 2) the percentage of students passing math, reading, and overall at Thomas High School is severely reduced, 3) the performance ranking of Thomas High School compared to the other schools in the district drops into the lower half with the poorer performing schools, and 4) Thomas High School's average math and reading scores for 9th graders is unavailable for comparison with the other school's 9th graders.

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
- Note that the math and reading scores for THS ninth-grade displays "NaN" as the  value representing that their scores were removed and replaced.
  
![Math_Scores](https://user-images.githubusercontent.com/102122063/166401565-25ce858e-14a9-423f-ace0-302dec1276d1.PNG) ![Readsing_Scores](https://user-images.githubusercontent.com/102122063/166401573-58192f87-caa1-48c4-ade8-4c2057899592.PNG)
 
 **Images 6 & 7:** *Math and Reading scores of each school in the district.*

-	When we dive deeper into the analysis, we foudn that the school rankings are unchanged. Thomas High School (THS) remained the second ranked of top performing schools   in the district. 
  ![Top_5](https://user-images.githubusercontent.com/102122063/166401477-44f3c0d2-46b7-4da9-8024-d73eb8f15705.PNG)
  **Image 8:** *Top 5 highest performing schools in the district.*
  
- There were no significant findings regarding school spending, school size or school type. The scores did not seem to changed due to removing the THS ninth-grade scores.

## Summary
After being informed of altered data regarding Thomas High School’s ninth-grade Math and Reading scores, the City School District data was reanalyzed without those values. We found that there were minimal changes in the district’s overall passing percentages, just a small decrease. However, there were more significant findings when looking specifically at the percentages of students passing math, reading, and passing overall at Thomas High School. While there were some changes to the passing scores for Math and Reading after removing the ninth-grade data, the ranking of Thomas High School remained second in the top 5 highest performing schools. 

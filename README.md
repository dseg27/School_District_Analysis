# School District Analysis

## Overview 

The purpose of this analysis was to see how replacing the math and reading scores for Thomas High School's 9th grade class would affect the outcomes of metrics being measured for the district, and for the individual school. The scores for this school and class had to be replaced with a NaN value (Not a Number) due to academic dishonesty. Without replacing these scores, the results in our school distrist analysis report would not have accurately represented outcomes as the 9th grade scores had been altered. 

In this report, the metrics being measured include:
- Average Math and Reading Scores 
- % Passing Math and Reading 
- % Overall Passing 
- Outcomes based on spending ranges, school size, and school type 

## Results

### District Summary Outcomes 

![image](https://user-images.githubusercontent.com/90593897/137819473-13e3c29d-dc57-47fd-a0b1-ee2f1d3ded91.png)

By comparing the two DataFrames which hold metrics for school district data before and after the grade replacement, it can be noted that there were no significant changes to the outcomes. The average scores and passing percentages essentially remained the same.  

### School Summary Outcomes
![image](https://user-images.githubusercontent.com/90593897/137819537-7208aba3-e9bf-4528-bb44-76a5da21117b.png)

By comparing the two DataFrames above, which hold metrics for Thomas High School before and after the grade replacement, it can be seen that there are no large changes to the data either.

The average math score decreased by about .06 points, the average reading score increased by about .05 points, and the passing percentages were changed by small amounts as well.

The passing math percentage decreased from 93.27% to  93.19%, and the passing reading percentage decreased from 97.31% to 97.02%. The overall passing percent decreased from 90.95% to 90.63%. 

Overall, the changes caused by the score replacement were not large or significant. 

### Effects on School Ranking 
Both before and after the score replacement, Thomas High School ranked #2 in the list of top 5 schools. Therefore, the score replacement did not effect their ranking. 

### Additional Metrics
  
  - Math scores by grade
    ![image](https://user-images.githubusercontent.com/90593897/137822514-a6630007-49fa-4e8d-a2a6-4727fd6e40be.png)
    - As can be seen in the comparison between the DataFrames before and after the grade replacement, the only significant difference is that Thomas High School's 9th grade class has no math scores as they have all been replaced by "Not a Number (nan)" due to the academic dishonesty. 
    
  
  - Reading scores by grade
    ![image](https://user-images.githubusercontent.com/90593897/137822712-49c97909-b8a1-4028-b5c8-e4720ebadc3a.png)
    - The same goes for Thomas High School's 9th grade class reading scores--this is the only change. There are no scores due to them being replaced by 'nan' due to academic dishonesty. 

  - Scores by school spending
    ![image](https://user-images.githubusercontent.com/90593897/137822900-d5c4c833-6c6a-48c4-837b-81368a730999.png)
    - There were no significant changes to scores by school spending range. In both DataFrames, there is a trend where the lower per school capita produced higher overall passing percentages. More research would need to be done to determine if there is a correlation between these two metrics. 
    
  - Scores by school size
    ![image](https://user-images.githubusercontent.com/90593897/137823133-a7037096-04e1-4bd0-ad46-3dd413aa8948.png)
    - There were no changes to the scores by school size before and after the grade replacement. One trend to note here is that the larger schools did not perform as well as the smaller or medium sized schools. 


  - Scores by school type
    ![image](https://user-images.githubusercontent.com/90593897/137823219-48c80a81-1f3f-4866-8e32-938421d18e5a.png)
    - There were no changes to the scores by school type before and after the grade replacement. In general, charter schools performed better than district schools in both analyses. 

## Summary 

The most obvious changes to the metrics were observed when comparing DataFrames for:
1) Math scores by grade 
2) Reading Scores by grade 

In both of these analyses, there were change in the Thomas High School 9th grade class scores as the previous scores were replaced by "Not a Number" (Nan) values. 

Additionally, the following metrics changed slightly: 

3) The passing math percentage decreased from 93.27% to  93.19% 
4) The passing reading percentage decreased from 97.31% to 97.02%. 

The overall passing percent decreased from 90.95% to 90.63%. 

Overall, the changes caused by the score replacement were not significantly large however, we can now submit our report with confidence knowing that we've accounted for the academic dishonesty in Thomas High School's 9th grade class, by replacing the scores with nan values.  

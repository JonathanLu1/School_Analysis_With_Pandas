# School_Analysis_With_Pandas

## Overview 

The school had altered data within the 9th grade overall scores. We used our knowledge in Pandas functions to take the data from the 9th grade class and removed it from the overall dataframe. We took the remaining grades within the different schools and analyzed the data for the school district. This way we can get an accurate reading of the overall schools and how they are performing within each of their different categories.

# Results 

## School District Summary Effect

![image](https://user-images.githubusercontent.com/107448860/179424787-2c6c4076-aa4b-40df-a412-f1445693ebec.png)

When dealing with the Dataframe and making edits to the selected classes to remove from the it, we used the loc function and many others to create edit the dataset to produce the most accurate averages. The impact that it had on the overall school district was not extremly impactful because the sample size was quite large. It still provides a more accurate number to be recorded for analysis. 

## School Summary Effect

Original Data

![image](https://user-images.githubusercontent.com/107448860/179424904-efd1c66d-8d33-4995-9b82-04995da70107.png)

The orignal data was originally corrupted with the altered 9th grade data so with the loc function we were able to calculate just the 10th through 11th grade scores and find a more accruate number.

![image](https://user-images.githubusercontent.com/107448860/179424968-b5500103-2a57-481a-a474-b9d7378f88ef.png)

![image](https://user-images.githubusercontent.com/107448860/179425006-95b57275-a562-4cd4-824b-cc7d65e3e8e2.png)

## Replacing Scores Effect

Replacing the scores of the 9th graders from Thomas High School dropped their scores by a large margin, of roughly 20 percent. It placed Thomas High School back into the Top 5 schools. 

![image](https://user-images.githubusercontent.com/107448860/179425306-1175a670-c94b-4e20-b002-2d4ad828b1f7.png)

## Math and Reading scores by grade

This category does not get impacted by replacing the grade of the 9th graders because they are categorized individually, so it would only remove the grade.

![image](https://user-images.githubusercontent.com/107448860/179425404-a78a5c53-5806-45eb-b065-fe8b3939d280.png)

![image](https://user-images.githubusercontent.com/107448860/179425409-9113cd11-fcbc-4e13-aebc-0eb8933c943f.png)

## Scores by School Spending

![image](https://user-images.githubusercontent.com/107448860/179425492-2ef91b94-f1b6-4b2f-8825-d78d3c1c70ff.png)

## Scores by School Size

![image](https://user-images.githubusercontent.com/107448860/179425503-aadbb732-af2b-4f46-a2c8-31259e4155bd.png)

## Scores by School Type

![image](https://user-images.githubusercontent.com/107448860/179425513-5327a163-bea0-454e-bbc9-e4e9abe58c44.png)

# Summary

The overall changes that occurred with the data that we had removed were quite eye opening. First of all, the overall school ranking increased dramatically with the altered scores. It also impacted the school spending to overall score ratio. It seemed that they spent more on the each student since we reduced the number of students that the school was said to contain. The data now also shows NAN for any report of a 9th grade student within Thomas High School. The campus reading and math passing percentages also saw a shift without the data within it. 

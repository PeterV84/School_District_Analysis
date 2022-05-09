### School_District_Analysis
# Analysis of school
## Overview of the school district analysis: Explain the purpose of this analysis.
-------------------------------------------------------------------------------
This project was brought about from Maria who is the chief data scientist for the city school system. The purpose of this analysis is to gather multiple sources and create a overview that will assist with decisions regarding student finding and student standardized test scores. Towards the end of the analysis, it was brought to the attention of the school board that Thomas High School Ninth graders have had altered testing cores. The analyis would be more accurate by removing all of their testing scores while retaining the rest of the data already completed.


## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?

-The major change was the subtraction of the "Ninth grade students". This number had dropped from 39170 to 38709

<img width="593" alt="Screen Shot 2022-05-08 at 4 08 02 PM" src="https://user-images.githubusercontent.com/100393032/167319625-1309d773-d1c8-457c-836c-cc8c71765694.png">

The larger difference came in the percentage of the reading and math scores.

This is the inital analysis before the alteration of the "Thomas High School Ninth graders":
<img width="811" alt="Screen Shot 2022-05-08 at 4 15 29 PM" src="https://user-images.githubusercontent.com/100393032/167319839-dddda6e9-c8e9-461e-8b0d-5a592f09704d.png">

We can see here after the changes concerning the "Thomas High School Ninth graders" that the percentage points for "reading", "math" and the "overall passing" have dropped one decimal point:
<img width="828" alt="Screen Shot 2022-05-08 at 4 16 35 PM" src="https://user-images.githubusercontent.com/100393032/167319873-affbcb29-85a7-4014-9f4f-ef0a0a01262a.png">

## How is the school summary affected?

-Surprisingly the school summary had very little changes from the Thomas high school Ninth Graders. 

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The replacement of the Ninth Graders scores had zero affect on the standings of Thomas high. In both Datasets the placement of Thomas High School stays the same.

## How does replacing the ninth-grade scores affect the following:

-Math and reading scores by grade

  The biggest difference came in the complete replacement of the ninth graders removal of all their grades: 
  <img width="473" alt="Screen Shot 2022-05-08 at 4 46 16 PM" src="https://user-images.githubusercontent.com/100393032/167320718-2c59c903-8a4d-4959-8dff-35391d30572b.png">

-Scores by school spending

The Budget for Thomas High School was not affected by the Ninth graders

-Scores by school size

The scores were slightly altered for Thomas High School at the decimal point.

-Scores by school type

The "Charter" school type had a few changes from the original analysis:
<img width="780" alt="Screen Shot 2022-05-08 at 5 01 17 PM" src="https://user-images.githubusercontent.com/100393032/167321274-f0377375-51eb-426c-b0c4-8e932b2b94f3.png">

Here with the updated analysis we can clearly see alterations in the "Charter" school type:
<img width="725" alt="Screen Shot 2022-05-08 at 5 02 08 PM" src="https://user-images.githubusercontent.com/100393032/167321346-713f8297-e7df-4083-9b22-ae6e937dade8.png">

As you can see across the board, the percentages for all "Charter" columns have dropped by a decimal point or more.

# Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

The four largest changes after dropping the "Thomas High School Ninth Grade" scores belonged to the four categories: "Math score", "Reading score", "Math passing %" and "Reading Passing %". These are the four areas in direct relation to the Ninth graders and the overall school percentages. Though the Ninth grade class was completely dismissed from the evaluation of the school, it did not have as great an impact as was maybe predicted. The budget stayed the same, the percentages dropped by a decimal but overall the school analysis looks surprisingly similar to what it was before. 

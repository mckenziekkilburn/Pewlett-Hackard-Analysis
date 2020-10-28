# Pewlett-Hackard-Analysis


## Overview of Analysis 
-------------------------------

**In this analysis, we were asked to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. 
We are performing this task to help us prepare because many of our current employees are almost at the age for retirement. We also need to determine which job titles will need to be filled once these employees have retired.**



## Results
-------------------------------

1. There are seven job titles that are at the age of retiring.

    - Senior Engineer -  29,414
    - Senior Staff - 28,254
    - Engineer - 14,222
    - Staff - 12,243
    - Technique Leader - 4,502
    - Assistant Engineer - 1,761
    - Manager - 2

2. Before getting this final result, we had to use the **DISTINCT ON ()** function. The reason is because some employees have switched titles over the years.
   For our final result, we only wanted what the most recent title of each employee was. In the image below it shows our results before removing duplicate values. 
   
   ![Readmeimg](https://github.com/mckenziekkilburn/Pewlett-Hackard-Analysis/blob/master/Readmeimg.PNG)
   
   
3. Next we were asked to find which employees were eligible for the mentorship program. The mentorship program gives people the oppurtunity of working part-time and mentoring younger workers with the wisdom that they already know. To uncover our findings we needed to perform a multi-table join. You can find this in the queries folder. 

4. We were asked to single out those that were born in the year 1965 for the mentorship program. We found that there were numerous applicant that were eligible to join the program. 


# Summary
---------------------------------
- *How many roles will need to be filled as the "silver tsunami" begins to make an impact?*
    - Shown in our results above, there is a sum of 902398 roles that will need to be filled.
      
      
- *Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?*
    - No there is not. After performing a query similar to the one shown in the Results section above, we found that there were only a total of 1549 that were eligible for the program. 
  
   

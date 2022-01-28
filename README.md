# School_District_Analysis
### Overview/Purpose:
The purpose of the challenge is to help Maria, a data analyst, prepare all standrized test data for the school district. This will provide insides about performance,trends, and patterns, which will later be used for informed discussiones and strategic decicions at the school and district levels.

We will help Maria analyze data on student's funding and studend's standarized test scores. Our task is to aggregate the data and showcase trends in school performance. This analysis will help the school board on making decisions regarding the school budget.In order to do this analysis, we will install Anaconda, create a PythonData enviroment and use Jupyter notebook.

After Maria was finished with the analysis, she was informed that there was evidence of academic dishonesty and the math and reading scores of nineth graders at Thomas High School have been altered. She was tasked with redoing the analysis and replacing the reading and math scores of the nineth graders with NaN and see how this affected the overall results.

# Results: 
### How is the district summary affected?
After accounting for the dishonesty, the overall impact that Thomas High School had in the district scores was not significant.

The avarage math score was lower by 0.1

The average reading score was the same

The % passing math was lower by 0.2

The % passing reading was lower by 0.3

The % overall passing was lower by 0.1

![districtsummary_before_after.png](https://github.com/LucyPill/School_District_Analysis/blob/main/districtsummary_before_after.png)


### How is the school summary affected?
The average math and reading scores did not change much; However, the % passing math, % passing reading and the % overal passing changed by a minimum percetage less than 0.5%. 

The avarage math score was lower by 0.07

The average reading score was lower by 0.05

The % passing math was lower by 0.08%

The % passing reading was lower by 0.29%

The % overall passing was lower by 0.32%

![schoolsummary_df_before_after.png](https://github.com/LucyPill/School_District_Analysis/blob/main/schoolsummary_df_before_after.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Based on our results, it does no tlook like this correction have an impact on the realtive performance of Thomas High School when compared to the other schools. Thomas High School was in 2nd place on the top five schools before and after the correction.

### Impact of replacing the ninth-grade scores on the math and reading scores by grade, scores by school spending, scores by school size, Scores by school type
Repalacing the Thomas High School math and reading score with the NaN (not a number) didnt have an impact at all on the scores by school spending, scores by school size, nor the scores by school type. The only changed was that in the math and reading score DataFrame for the 9th grader we can see a NaN instead of the original numerical value, but of course this is what we wanted to do replace it with NaN.

![mathscore_before_after.png](https://github.com/LucyPill/School_District_Analysis/blob/main/mathscore_before_after.png)

# Summary:
In summary, we can see that there was no much of a chnage at the district level; however, at the school level we can see small percentage change less than 0.4%, very minimun change overall.
1. Math Score
  * At the district level decreased by 0.1 
  * At the school level decreased by 0.07

2. Reading Score
  * There was no change at the district level
  * at the school level decreased by 0.05 

3. % Passing Math
  * At the district level decreased by 0.2%
  * At the school level decreased by 0.08%
   
4. % Passing Reading
  * At the district level decreased by 0.3%
  * At the school level decreased by 0.29%

5. % Overall Passing
  * At the district level decreased by 0.1%
  * At the school level decreased by 0.32% 

# School District Analysis

## Overview 

The purpose of the following analysis is to interpret and understand the changes of the former analysis about school performance following the removal of those suspected of academic dishonesty by the school board (9th graders from Thomas High School) from the data set. We left the rest of the data intact and removed from analysis all the scores from the suspected students. Then we ran the analysis in the same manner as before.

## Results

Overall, it was discovered that the summary results from the district, school as well as performance didn't see much significant change:

- The District summary [before](link) and [after](link) removing the students' scores remains largely the same, with the only significant difference being that the percentage of passing overall drops from **65.2%** to **64.9%**
- The school summary [before](link) and [after](link) removing students' scores has **no** significant change, the overall passing rate remains mostly the same, dropping from **90.9%** to **90.6%**, the math passing rate from **93.3%** to **93.2%** and the reading passing rate from **97.3%** to **97.0%**.
- Even though their overall passing rate dropped, Thomas High School remains [2nd place](link) among the top schools based on overall passing rate. 
- Replacing the 9th grade scores with null scores and running the analysis does **not** change the overall scores by grade, it only deletes that data point for 9th graders in Thomas High School and it has **no** effect on the scores of school by spending (Thomas High School falls into the range of $630-644 per capita), by size (Thomas High School is a medium school) or school type (Thomas High School is a charter school).  

## Summary

The four (mostly) significant changes in the updated school district analysis happen at the district summary, where the percentage of passing overall drops from **65.2%** to **64.9%** and at the school summary for _Thomas High School_ the overall passing rate drops from **90.9%** to **90.6%**, the math passing rate from **93.3%** to **93.2%** and the reading passing rate from **97.3%** to **97.0%**.

However, after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs, of the results are _truly_ significant, since all of the drops in percentages are **less than 1%** and do not constitute important changes for any result.

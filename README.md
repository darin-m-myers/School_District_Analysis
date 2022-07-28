# :school: School_District_Analysis :school:

## Purpose of Analysis: 
The City School District Board has requested analysis of the Standard Testing Scores for Math and Reading across the district. They have requested multiple summaries of the data in order to plan for the coming school year. Also, there has been some evidence of academic dishonesty in the reading and math scores for Thomas High School 9th graders. The Board has requested that the scores be removed from the analysis and the summaries be adjusted to reflect the new values. This will help them make more appropriate assumptions about the schools for the decisions that they need to make for the coming year. 

> NOTE: In the following analysis, **Original** will refer to the data before any adjustments. **Adjusted** will refer to post removal of Thomas High School 9th grade scores, and `THS` will refer to Thomas High School.

## Results of District Analysis

1. How is the district summary affected?
    * As shown below in Table 1.1, the average scores in Math, as well as the % passing math, the % passing reading and the % overall passing *decreased* once the values were recalculated without the `THS` 9th grade scores.
    * The largest decrease was in % Passing Math, with a decrease of 0.35%, however, the % change from the adjustmes amounted to less than half a percent change to any of the metrics.
    * The remainder of the fields were not affected by the adjusted totals.
 
 <details><summary>Click the Arrow on the left to expand the District Summary Table </summary>
 <p>
    
Table 1.1: District Summary Comparison 
| Analysis Type | Total Schools |	Total Students |	Total Budget |	Average Math Score |	Average Reading Score |	% Passing Math |	% Passing Reading |	% Overall Passing
| ---------- | --------------: | ----------: | ----------: | ----------: | ----------: | ----------: | ----------: | ----------: |
| Original | 15 |	39,170 |	$24,649,428.00 |	79.0 |	81.9 |	75.0 |	86.0 |	65.0 |
| Adjusted | 15 |	39,170 |	$24,649,428.00 |	78.9 |	81.9 |	74.8 |	85.7 |	64.9 |
| `% Change` | `0.0%` :ok: | `0.0%` :ok: | `0.0%` :ok: | `-0.13%` :small_red_triangle_down: | `0.0%` :ok: | `-0.27` :small_red_triangle_down: | `-0.35` :small_red_triangle_down: | `-0.15` :small_red_triangle_down: |

 </p>
 </details>

2. How is the school summary affected?
      * As shown in Image 2.1 and 2.2 below (click the arrow to uncollapse), in the school summary the changes only affected `THS`, as they were the only school with scores removed.
      * `THS` overall passing scores dropped from 90.948% to 90.630% passing.
      
 <details><summary>Click the Arrow on the left to expand the School Summary Tables </summary>
 <p>

 | Image 2.1: Original School Summary |
 | --- |
 | <img src="/Images/School_Summary_Original.png" width="600"> |

 | Image 2.2: Adjusted School Summary |
 | --- |
 | <img src="/Images/School_Summary_Adjusted.png" width="600"> |

 </p>
 </details>

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
      * As shown in Image, 3.1 and 3.2 below, replacing the scores made no change to `THS` performance related to other schools
      * `THS` was the second highest school % Overall Passing and remained the second highest school after the adjustment.
      
<details><summary>Click the Arrow on the left to expand the Top Schools Summary Tables </summary>
 <p>

 | Image 3.1: Original Top School Summary |
 | --- |
 | <img src="/Images/Top_Schools_Original.png" width="600"> |

 | Image 3.2: Adjusted Top School Summary |
 | --- |
 | <img src="/Images/Top_Schools_Adjusted.png" width="600"> |

 </p>
 </details>      
 

4. How does replacing the ninth-grade scores affect the following:
      * Math and reading scores by grade -  The only change to reading and math scores is in the 9th grade at `THS`. The values have been removed, so they are listed as NaN. (See Image 4.1 through 4.4)
      * Scores by school spending -  `THS` is in the $631-645 bucket. With that in mind, the only changes would be in that bucket. Becuase of the formatting requirements of one decimal place, the adjustment does not actually change the final tables. (See Image 4.5 and 4.6)
  
      * Scores by school size - `THS` is in the Medium bucket so the only changes would potentially be in that bucket. As with school spending, because of the final formatting requirements, the the adjustment does not actually change the final tables. (See Image 4.7 and 4.8)
  
      * Scores by school type - `THS` is a Charter school, so the only changes would be for Charter schools. Once again, because of the final formatting requirements, the the adjustment does not actually change the final tables. (See Image 4.9 through 4.10)
      
<details><summary>Click the Arrow on the left to expand the Top Schools Summary Tables </summary> (See Image 4.7 and 4.4)
 <p>

 | Image 4.1: Original Math Scores by Grade | Image 4.2: Adjusted Math Scores by Grade |
 | --- | --- |
 | <img src="/Images/Math_Scores_Original.png" width="600"> | <img src="/Images/Math_Scores_Adjusted.png" width="600"> |
 | Image 4.3: Original Reading Scores by Grade | Image 4.4: Adjusted Reading Scores by Grade |
 | <img src="/Images/Read_Scores_Original.png" width="600"> | <img src="/Images/Read_Scores_Adjusted.png" width="600"> |

 | Image 4.5: Original Scores by Spending | Image 4.6: Adjusted Scores by Spending |
 | --- | --- |
 | <img src="/Images/Scores_by_Spending_Org.png" width="800"> | <img src="/Images/Scores_by_Spending_Adj.png" width="800"> |
 
 | Image 4.7: Original Scores by School Size | Image 4.8: Adjusted Scores by School Size |
 | --- | --- |
 | <img src="/Images/Scores_by_School_Size_Org.png" width="800"> | <img src="/Images/Scores_by_School_Size_Adj.png" width="800"> |
 
  | Image 4.9: Original Scores by School Type | Image 4.10: Adjusted Scores by School Type |
 | --- | --- |
 | <img src="/Images/Scores_by_School_Type_Org.png" width="800"> | <img src="/Images/Scores_by_School_Type_Adj.png" width="800"> |
    
 </p>
 </details> 

### Summary
Overall the adjustment of scores to remove the THS 9th grade scores, did not make many signifigant changes to the overall final summaries. With this in mind, the district board can be confident in any decisions they have already agreed on prior to removal of the contested scores from `THS`.
1. The overall distrcit summary showed a small drop in several scores including math and reading scores and the % passing
2. The adjustments to the data did not change the position of `THS` in the list of top schools.
3. The final scores by grade for math and reading shows a NaN for 9th grade at `THS`
4. Due to the final formatting requirements, the summary breakdowns by grade, spending, school size and school type did not change, even for the buckets that `THS` was in. The average scores and % passing did drop a bit, but the change was so small in the summaries that they did not change the final results once the values were rounded to one or no decimals.

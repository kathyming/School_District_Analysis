# School_District_Analysis
## Overview 
The purpose of this analysis was to see if there a correlation between test scores and school budget, or school size, or school type.  In order to better analyze the data it was necessary to remove the scores for the 9th graders at Thomas High School due to evidence that some of the scores were altered. 
## Results
* District Summary: Removing the unvalidated 9th grade math and reading scores for Thomas High School from the data frame appears to have little to no effect on the district summary scores. Overall passing percentage went from 65.17% to 64.9%.
![district_summary_clean](https://user-images.githubusercontent.com/106352711/177390069-c8f0b2bb-1fab-4103-8f3a-04e70e614fb6.png)

* School Summary: Removing the unvalidated 9th grade math and reading scores for Thomas High School from the data frame appears to have little to no effect on the school summary scores.  Thomas High School's numbers each changed by less than 0.5%.
![school_summary_clean](https://user-images.githubusercontent.com/106352711/177390122-bebbd1ab-d693-4d23-bff9-259a7cfe9154.png)


* School Rankings: Similar to the District Summary, the School Summary was not notieably altered by the removal of the Thomas High School 9th grade scores.  Thomas High School remained in second place when ranked by Overall Passing %.

* Thomas High School 9th Grade Scores
  * Math and Reading Scores by Grade: Removing 9th grade scores from Thomas High School obviously led to no scores for 9th graders at the school.  The rest of the grades at Thomas High School had consistent scores across the grade levels.
  * Scores by School Spending: Scores by school spending was not affected at all by removing the 9th grade Thomas High School scores.  Thomas High School falls into the $631-645 spending range.  Overall Passing percentage for this range did not change (62.8%) after the data was cleaned.
  * Scores by School Size: Scores by school size was not affected by removing the 9th grade Thomas High School scores.  Thomas High School falls into the medium school size range.  Overall passing for this range remained at 90.6%
  * Scores by School Type: Scores by school typej were not affected at all by removing the 9th grade Thomas High School scores.  Thomas High School is a Charter school.  Overall Passing percentage for for Charter schools remained at 90.4%. 

## Summary
After reading and math scores for the 9th grade at Thomas High School were removed from the datat, there appear to be no changes to the restults.  However, in analyzing the data, the following condulsions can be made:
* Charter Schools had much better grades than District Schools.
* ![scores_by_type](https://user-images.githubusercontent.com/106352711/177390255-75c22ab9-49d3-4fae-b233-02fdaa528597.png)

* The size of a school had a negative impact on scores.  The larger the school, the lower the scores.
* ![scores_by_size](https://user-images.githubusercontent.com/106352711/177390273-058fa69e-50ef-4bde-a090-17d259376c6c.png)

* A larger the shcool's budget did not result in better test scores.  As spending rose, passing percentages declined.
* ![scores_by_spending](https://user-images.githubusercontent.com/106352711/177390317-8a26824b-a2dd-4754-b230-fe17330c080f.png)

* School test scores appeared to be consistent across grade levels.  
* ![math_scores_by_grade](https://user-images.githubusercontent.com/106352711/177390331-9333ec6d-c7f3-418a-aec9-938537518734.png)
![reading_scores_by_grade](https://user-images.githubusercontent.com/106352711/177390355-087377f4-d8dc-4f71-8c50-1aec38ae394e.png)

Another analysis should be done to see how spending relates to school type.  Charter schools scored much higher than District schools, but did they spend more or less than District schools.  In planing future spending, it would be good to know if Charter shcools are out performing and under spending than District schools.

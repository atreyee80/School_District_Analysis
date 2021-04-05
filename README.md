# School_District_Analysis
 
## Overview of the school district analysis

The purpose of this exercise is manifold, outlined as below:
1. Get a snapshot of the key metrics of the school district. This snapshot can be used to measure the metrics either against planned benchmarks (like expenditure vs budget) or to do comparisons with other school districts or to analyse how these metrics change over time for this school district
2. Capture the key metrics for each school, and also go a level deeper to capture them at the grade level. The objective of capturing these metrics would possibly be to understand any correlation between certain metrics and parameters, like "Does more budget in a school mean improved overall pass rates?" or " Does Charter Schools perform better than other schools?" or "Will pass % drop as students move from Grade 9 to 10 and on?"
3. Clean the data from "contentious" evaluation of students in Grade 9 of Thomas High School so that the metrics are not biased. Cleansing the data from these values would provide an accurate picture of the school district as a whole and also provide a fair comparison of metrics across schools. 

## Results

### How is the district summary affected? 

As seen from the pictures below, excluding the numbers for Thomas High (Grade 9) changes the overall passing percentage from 80% to 64.9% which is a decrease of 15 percentage points. The other metrics like scores have not change in any impactful manner.

District Summary (before Grade THS / Grade 9 was excluded)
   ![](District_Before_changes.png?raw=true)
   
   
District Summary (after Grade THS / Grade 9 was excluded)
   ![](District_After_changes.png?raw=true)


 
### How is the school summary affected? 

The metrics of all schools would remain unaffected due to the exclusion of THS / Grade 9. Only the metrics for THS (% passing) would be impacted 

School Summary (before Grade THS / Grade 9 was excluded)
    ![](school_summary_before.png?raw=true)
    
    
School Summary (after Grade THS / Grade 9 was excluded)
    ![](school_summary_after.png?raw=true)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? (done / screenshot pending)

Due to the exclusion of the 9 grade students from the data analysis, the % passed for Maths, English and Overall increased from 66.9% to 93.1% , 69.6% to 97%, 65% to 90% respectively. Due to the marked improvement in passing %, the relative performance of THS has improved by quite a few notches. When the schools were ranked, THS shot up from 8th position to second position as depicted in the chart below. 
However, the scores for either Maths or English have not changed

**PUT SCREENSHOT of top 5 schools after grade 9 was exluded to show THS is in second position**


### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade (done)

Grade wise scores of each school will NOT be impacted by this change. However the following changes have been observed:

1. The Grade wise score for THS for Grade 9 is not available anymore
2. The Average pass % for Grade 9 for the school district have improved due to the exclusion of THS / Grade 9

Grade wise Summary 

  ![](Grade_wise_scores.png?raw=true)
  
  

#### Scores by school spending (done)

The scores for either Maths or English have not changed.

THS has a spending / student of $638. Hence the bin for $630 - $644 would be impacted due to the exclusion of Grade 9 students from THS for the % passing. Since the all the 3 percentages (math passing, english passing & overall passing) have improved for THS after the change, the same percentages for Bin # $630 - $644 have also increased to 66.89%, 77.4% & 56.3% due to this change.

    
#### Scores by school size

The scores for either Maths or English have not changed.
The scores of every school will remain the same including THS. THS is a middle sized school (between 1000 - 2000). Hence the scores for middle sized schools will not be impacted. However, the pass % of middle sized schools have increased due to the improved pass % rates of THS resulting from the exclusion of Grade 9 in THS.


#### Scores by school type
The scores for either Maths or English have not changed.

However, due to changes in % pass rate of THS, the % passing of Charter Schools have increased

## Summary

1. The pass % for Maths have increased for the district
2. The pass % for English have increased for the district
3. The pass % for Overall have increased for the district
4. There is no change in the scores for the district for either Maths or English


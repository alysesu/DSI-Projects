# How can we improve SAT participation rate?

In the United States, competition is fierce between the two popular college admission tests - SAT and ACT examination. In this project, we will be taking a deeper dive into the SAT and ACT data we gathered for 2017 and 2018, identify key trends in the participation rates and test scores, as well as bring suitable recommendations to increase the SAT test scores based on our findings and insights.

## Problem Statement

 The aim for this project is to come up with a proposal on how to increase the SAT participation rate in a selected state.

The data used for this proect are:
- [SAT 2017](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/)
- [SAT 2018](https://reports.collegeboard.org/sat-suite-program-results/state-results)
- [ACT 2017](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows)
- [ACT 2018](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdfZ)

## Executive Summary
In the United States, there is tight competition between the two popular college admission tests, SAT and ACT. Our analysis concluded that high participation in one test usually result in low participation in the other, particularly for states with mandatory testing.

Across the board, states with higher test scores generally maintain their lead from 2017 to 2018. Moreover, a high participation in the test usually result in a low test score. As a result, states with mandatory testing scores lower than states with voluntary testing.

Geographically, the SAT test is popular amongst coastal states, whilst the ACT test is popular amongst the non-Coastal states. Approximately 20 states (mostly non-coastal) have mandatory ACT testing, whereas approximately 10 states (mostly coastal) have mandatory SAT testing. Recent success for SAT's College Board include clinching two new contracts for the Midwestern states, Illinois and Colorado.

On the whole, my recommendation is to focus our efforts of increasing SAT participation for **South Dakota**. Based on our data, South Dakota is a state with mature testing environment (due to the high voluntary ACT participation) and exceptional scores (in both ACT and SAT). With efforts to expand influence of the SAT in the Midwestern region, South Dakota could benefit from the increased popularity of the SAT exam in the region over the years. Some recommendations to increase participation in South Dakota include provision of test subsidy, launching of marketing campaigns and to look out for contractual opportunities.  

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*string*|SAT2017 / ACT2017|State names for the 51 states in USA.|
|**sat_17_part**|*float*|SAT2017|Participation rate for the SAT examination in the particular state in 2017.|
|**sat_17_rw**|*integer*|SAT2017|Average test score for the particular state for the SAT 2017 section of "Evidence-based Reading and Writing".|
|**sat_17_math**|*integer*|SAT2017|Average test score for the particular state for the SAT 2017 section of "Math".|
|**sat_17_total**|*integer*|SAT2017|Average total test score for the particular state for the SAT 2017 examination.|
|**act_17_part**|*float*|ACT2017|Participation rate for the ACT examination in the particular state in 2017.|
|**act_17_el**|*float*|ACT2017|Average test score for the particular state for the ACT 2017 section of "English".|
|**act_17_math**|*float*|ACT2017|Average test score for the particular state for the ACT 2017 section of "Math".|
|**act_17_read**|*float*|ACT2017|Average test score for the particular state for the ACT 2017 section of "Reading".|
|**act_17_sci**|*float*|ACT2017|Average test score for the particular state for the ACT 2017 section of "Science".|
|**act_17_comp**|*float*|ACT2017|Average composite score (ie. the average of the four test subjects) for the particular state for hte ACT 2017 examination.|

## Conclusions and recommendations
#### Conclusion
The above analysis clearly indicated a distinct rivalry between the SAT and ACT participation rates, with ACT clearly leading the race whilst SAT improving over the year with its participation rates.

There are many states with mandatory ACT and SAT examinations. High participation rates in a particular test usually leads to low scores in the test, as well as low participation rates in the other test.

The SAT is popular amongst coastal states, whilst the ACT is popular amongst non-coastal states. However, the SAT has been increasing its reach to midwestern states after clinching the mandatory testing contract with Colorado and Illinois.

Based on the data above, the SAT examination tend to favour students who are exceptional, as shown by the large deviation of scores amongst the top students. This shows that the SAT examination might be slightly tougher than the ACT examination to score well. States with higher test scores in 2017 generally retains its high scores for 2018.

#### Recommendations
My recommendations are for us to look into focusing our efforts on states with:<blockquote>
- No mandatory ACT testing (ie. no existing contractual agreement in place)
- Generally high ACT participation despite non-mandatory testing: This displays tenacity amongst students and a culture amongst high school students to pursue further education
- High ACT composite scores: This shows that the general competency of the students are high.
- High SAT average scores: Good track record in order to sell the idea to the state's education board.
- Geographically clustered amongst the coastal states that favour the SAT exam. (Optional)</blockquote>

With the above criterion in mind, I have narrowed my focus onto the state of **South Dakota**. Key reasons behind my recommendations are:
<blockquote>

1. There are no mandatory testing for either ACT or SAT in South Dakota.
   - As we observed, mandatory participation in the ACT exam would substantially depress participation rates for the SAT. To increase SAT participation rates, it would be easier if the other exam is non-compulsory for students.
   - Source: [1](https://blog.prepscholar.com/which-states-require-the-act-full-list-and-advice) [2](https://www.testive.com/state-sat-act/)

2. South Dakota students have a culture of taking College entrance examinations
   - The state of South Dakota has an astounding participation rate of 77% despite not having mandatory testing. This shows that at at a lower level, perhaps city,district or school-level, many of them have incentives for students to take the ACT exam.

3. South Dakota produces higher-than-average ACT test scores
    - Despite high participation in the ACT examination, results across all subjects, including composite scores, are consistently higher than national averages.
    - This indicates that schools in South Dakota tend to produce students with higher exam-readiness.
    - This would be important as SAT exam tend to be slightly more challenging to attain exceptional scores. Hence, students with higher competency would do well in the SAT exam.
    - Source: [1](http://www.act.org/content/dam/act/unsecured/documents/cccr-2019/South-Dakota-CCCR-2019.pdf)
4. South Dakota is ranked 10th nationally for its SAT total average test scores.
    - Although expected due to the low participation rates, it is still important to show a good SAT test scores as it would serve as a good track record in building our case to South Dakota's education board.
5. South Dakota is a Midwestern state.
    - With Colorado and Illinois, two midwestern states that are close to South Dakota, we see that there is increased popularity of the SAT examination in this region.
    - As we observed from the results, SAT/ACT popularity tend to be highly correlated to its geographical region.
    - Over the years, we can expect that Midwestern states like South Dakota, will be more acceptant of the SAT exam.
</blockquote>

Possible measures to improve SAT participation rates:<blockquote>
1. Providing SAT test subsidy to schools in South Dakota
    - To increase demand in any product, it is vital to consider lowering the financial burden of consumers in purchasing the product. Hence, introducing test subsidies is a good way to incentivise students to take up the exam.
2. Setting up campaigns alongside test subsidies to bring SAT exam's selling points and key differences to light. Some key selling points include:
    - Existing partnership with Khan Academy to prepare students for the SAT exam.
    - College Board's advanced placement courses and exams, and PSAT can qualify students for merit-based scholarships [Source](https://www.chicagotribune.com/news/ct-illinois-chooses-sat-met-20160211-story.html)
    - College Board has a better reporting system that is more useful for students, connecting students with resources and activities to best help them succeed. [Source](https://www.denverpost.com/2017/03/06/colorado-juniors-sat-college-exam/)
3. Increase the convenience of participating in the SAT exam for college students.
    - This could include provision of the exam during a school day, in the student's school.
    - Increased resources for participating students.
4. Look into potential contracts with South Dakota's education board.
    - This is a sure-win way of increasing participation rates, as seen in neighbouring states Colorado and Illinois. It would be vital to start focusing resources to build relationship with the education board of South Dakota.</blockquote>

Additional data that would be helpful for my investigation:
<blockquote>

1. Socioeconomic indicators for each state:
    - High school graduate (%) and College graduates (%)
    - Income
    - Race
2. Existing contract with either SAT or ACT (Boolean data)
3. At least 5 years worth of data
4. Student-level data
    - Instead of state-level data, we have student-level data to see if each student participated in any test, and their test results.
    - This would be good for statistical testing
5. City/District-level participation rate for each test</blockquote>

##### Final Note:
Lastly, I would emphasise that although the state of choice is South Dakota, **Kansas and Iowa** also fall under the same umbrella of consideration, given that all three of these states meet the all the criterions for my above-mentioned reasons for recommendations. Hence, if we have more datapoints, it will be easier to narrow down into any of the three states.
# sat-act-exams
# test123

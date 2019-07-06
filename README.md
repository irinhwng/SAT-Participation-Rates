### Slide

https://docs.google.com/presentation/d/1BTmfAr9gI-hpFUtkPv3ruh4j_VKTpRCbgWLF40ZyPCQ/edit#slide=id.p

### Problem Statement

For this project, we're going to take a look at aggregate SAT and ACT scores and participation rates from each state in the United States. We'll seek to identify trends in the data and combine our data analysis with outside research to identify likely factors influencing participation rates and scores in various states.

### Executive Summary

The new format for the SAT was released in March 2016. As an employee of the College Board - the organization that administers the SAT - I am part of a team that tracks statewide participation and recommends where money is best spent to improve SAT participation rates. This presentation and report is geared toward **non-technical** executives with the College Board and you will use the provided data and outside research to make recommendations about how the College Board might work to increase the participation rate in **Alaska**. 

### Dataset Dictionary for `final.csv`

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT 2017|State Name| 
|act_participation_2017|int|ACT 2017|Average ACT Participation Rate| 
|act_english_2017|float|ACT 2017|Average ACT English Score| 
|act_math_2017|float|ACT 2017|Average ACT Math Score| 
|act_reading_2017|float|ACT 2017|Average ACT Reading Score| 
|act_science_2017|float|ACT 2017|Average ACT Science Score| 
|act_composite_2017|float|ACT 2017|Average ACT Composite Score| 
|sat_participation_2017|int|SAT 2017|Average SAT Participation Rate| 
|sat_read_write_2017|float|SAT 2017|Average SAT Reading and Writing Score| 
|sat_math_2017|float|SAT 2017|Average SAT Math Score| 
|sat_total_2017|float|SAT 2017|Average SAT Total Score|  
|sat_participation_2018|int|SAT 2018|Average SAT Participation Rate| 
|sat_read_write_2018|float|SAT 2018|Average SAT Reading and Writing Score| 
|sat_math_2018|float|SAT 2018|Average SAT Math Score| 
|sat_total_2018|float|SAT 2018|Average SAT Total Score| 
|act_participation_2018|int|ACT 2018|Average ACT Participation Rate| 
|act_composite_2018|float|ACT 2018|Average ACT Composite Score| 

### Outside Research
---

**Colorado:**

- Particpation rate for the SAT skyrocketed from 11% to 100%
- The state Department of Education announced Wednesday that a selection committee chose The College Board, makers of the SAT, over the ACT testing company, which has been testing juniors in Colorado since 2001 (chalkbeat.com). 
- State Funded (aka free)
- Before initiating the SAT and ACT, the state of Colorado had PARCC tests. PARCC refers to a collection of exams administered to public school students on a yearly basis. Developed by experts from multiple states, PARCC exams are designed to measure student progress while establishing Common Core standards for grades 3-11(blog.collegevine.com)
- PARCC tests include only language arts and math. The PSAT and SAT tests cover reading, writing, math, science and social studies and are meant to measure college and workforce readiness (chalkbeat.com)

**Ohio:**

- ACT particpation rate increased from 75% to 100% 
- Board of education is paying for the ACT - Accuplacer exam didn't work
- Ohio Kettering Fairmont high school Principal Tyler Alexander said "“A few years ago we did an SAT pilot, and we had a lot of students deemed college-ready by Sinclair based on their SAT score who had not been deemed ready on the Accuplacer test." (daytondailynews.com)
- About 95 percent of districts will administer the ACT, according to state officials. (daytondailynews.com)

**Florida:**

- SAT participation decreased from 83 to 56 and ACT decreased from 77 to 66. 
- The ACT company is serving free breakfast for certain Florida school districts to encourage higher scores since Florida has a history of scoring lower than the national averages 
- Florida board of education requires high school students to pass either the FSA or SAT or ACT to graduate high school (orlandosentinel.com). 
- More than 35,000 students in the class of 2017 graduated using the alternative exams, the Florida Department of Education reported. That’s about 20 percent of the more than 168,000 teenagers who earned diplomas last spring and summer. (orlandosentinel.com)
- The FSA is considered easier since the exam consists of 10th-grade language arts and the algebra 1 end-of-course exam; thereofore, a lot of students are taking the FSA to graduate. This explains the reason why both SAT and ACT participation rates are lowering. 
- Florida board of education might implement stricter graduation requirements. 

**Sources:**

- https://www.chalkbeat.org/posts/co/2015/12/23/goodbye-act-hello-sat-a-significant-change-for-colorado-high-schoolers/
- https://blog.collegevine.com/what-is-the-parcc-test-everything-you-need-to-know/
- https://www.daytondailynews.com/news/too-much-testing-some-schools-angry-with-ohio-act-sat-mandate/5lPdirdJ68IuXs1ez7Mv7L/
- https://www.orlandosentinel.com/news/education/os-fsa-algebra-passing-scores-alternative-20180330-story.html

### Conclusions and Recommendations
---
**Answer** 

- Alaska is the only state in 2018 where both SAT and ACT participation rates were lower than the national average.
- The average national participation rate for the ACT in 2018 is ~61%
- The average national particpation rate for the SAT in 2018 is ~45%
- Alaska's ACT participation from 2017 to 2018 dropped from 65% to 33%
- Alaska's SAT participation rate from 2017 to 2018 increased from 38% to 43% 

*Note the SAT participation rate didn't increase as much as the ACT participation rate dropped
*Note Alaska has no mandatory exit exams for high school students 
    
**Overall:**
    
- Alaska's average SAT total score for 2018 is ~1106; the national average for that year is ~1120
- Alaska's average SAT total score for 2017 is ~1080; the national average for that year is ~1126
- Alaska's average ACT composite score for 2017 is ~19; the national average for that year is ~21
- Alaska's average ACT composite score for 2018 is ~19; the national average for that year is ~21
    
**What is happening:**
    
- Native American and Alaska-Native students had the lowest overall scores, an average ACT math of 17.3, and also the steadiest five-year decline of any group (according to edweek.com). 
- Alaskan high school student on average have lower resources than that of other states (edweek.com). 
    
**What College Board can do:**
    
- Communicate with Alaska's Board of Education to either make it mandatory to take exam to graduate high school and/or initiate SAT Day. 
- Give students the incentive to get better SAT scores by offering free after prep classes and free practice tests
- Since Alaskan students on average have fewer resoures than other states, inititate a campaign where College Board offers more resources (ACT for Texas and Florida are offering free breakfast before the exam to prevent students from taking the exam hungry since those states' ACT scores are fairly lower than the national average). This initiative will increase test subject scores (leadershipbog.act.org). 
    
**Source:**
    
- https://www.edweek.org/ew/articles/2018/10/17/math-scores-slide-to-a-20-year-low.html
- http://leadershipblog.act.org/2019/04/act-will-provide-free-breakfast-to.html
    


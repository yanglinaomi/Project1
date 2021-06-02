# Project1
This contains all the stuff about project 1
# Project-1: SAT & ACT Analysis


## Problem Statement
As a team member of College Board which administers the SAT, we keep tracking statewide SAT participation rate. From historical data, SAT participation rate is still relatively low comparing with ACT participation across 51 states in U.S. 

After a new format of SAT released in 2016, we will do data analysis with SAT/ACT 2017 and 2018 dataset and find out potential solutions to improve SAT participation rate. 

## Executive Summary
This project provides an analysis and evaluation for SAT and ACT particiation rate and average scores in year 2017 and 2018. Before proceeding data analysis, data cleaning is performed. Methods of analysis include Exploratory Data Analysis to investigate trends in the data, visualaize the data with plots and descriptive & inferential Statistics analysis. Outside research is conducted for states which are selected based on analysis and observation from previous sections. Finally, conclusion and recommendations are provided.

## Dataset Description (Data Dictionary)

**SAT/ACT 2017 Dataset**
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT & ACT|State name
|sat_par17|float64|SAT|SAT pariticipation rate for each State in 2017
|sat_ebrw17|int64|SAT|SAT average score for Evidence-Based Reading and Writing for each State in 2017
|sat_math17|int64|SAT|SAT average Math score for each State in 2017
|sat_total17|int64|SAT|SAT average total score for each State in 2017
|act_par17|float64|ACT|ACT pariticipation rate for each State in 2017
|act_eng17|float64|ACT|ACT average English score for each State in 2017
|act_math17|float64|ACT|ACT average Math score for each State in 2017
|act_read17|float64|ACT|ACT average Reading score for each State in 2017
|act_sci17|float64|ACT|ACT average Science score for each State in 2017
|act_compo17|float64|ACT|ACT average Composite score for each State in 2017

**SAT/ACT 2018 Dataset**
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT & ACT|State name
|sat_par18|float64|SAT|SAT pariticipation rate for each State in 2018
|sat_ebrw18|int64|SAT|SAT average score for Evidence-Based Reading and Writing for each State in 2018
|sat_math18|int64|SAT|SAT average Math score for each State in 2018
|sat_total18|int64|SAT|SAT average total score for each State in 2018
|act_par18|float64|ACT|ACT pariticipation rate for each State in 2018
|act_eng18|float64|ACT|ACT average English score for each State in 2018
|act_math18|float64|ACT|ACT average Math score for each State in 2018
|act_read18|float64|ACT|ACT average Reading score for each State in 2018
|act_sci18|float64|ACT|ACT average Science score for each State in 2018
|act_compo18|float64|ACT|ACT average Composite score for each State in 2018

## Conclusion and Recommendations
In conslusion, SAT participation rate has no dramatically increasement from 2017 to 2018. Some States, like Colorado and Illinois, have high SAT participation rate improvement. Further investigation is conducted for them to find out the root cause.
The SAT and ACT participation rate roughly complements each other. For most states participation of one test dominates the other. Maybe affected by the policies of the state.

We will recommand College Board to improve SAT participation rate in the following aspects.

1) Administer the SAT as the State’s accountability exam.
2) Offer more SAT School Day to make more flexibility for the students who have to work during weekend.
3) Offer more incentives for students who comes from low-income families, like covered the cost of the SAT for all their public school students.

## Reference
https://www.usnews.com/news/education-news/articles/2019-09-24/more-students-are-taking-the-sat-than-ever-before
https://www.edweek.org/teaching-learning/sat-scores-rise-as-number-of-test-takers-tops-2-million/2018/10                                                                       
https://www.testive.com/colorado-sat-change-2017/                                                                                                                             
https://www.testive.com/state-sat-act/                                                                                                                                         
https://collegereadiness.collegeboard.org/sat/k12-educators/sat-school-day/about                                                                                               
https://www.ride.ri.gov/InstructionAssessment/Assessment/PSATandSAT.aspx                                                                                                       
https://blog.collegevine.com/states-that-require-sat/                                                                                                                        

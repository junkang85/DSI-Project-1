"# DSI-Project-1" 

Change Log
1. First commit with README
2. Updated README with Data Dictionary
3. First commit of code and updated README

Content
1. Problem Statement
2. Data Inputs
3. Data Dictionary
4. Conclusion
5. Recommendations

1. Problem Statement
- Should you take SAT? ACT? Or both?
- Which state should you take SAT/ACT in?

2. Data Inputs
a) sat_2017.csv
b) act_2018.csv
c) sat_2018.csv
d) act_2018_updated.csv

Data Dictionary

|Dataset|Description|Feature|Type|
|---|---|---|---|
|SAT/ACT|state|object|State for SAT 2017/2018 and ACT 2017/2018.|
|SAT|sat2017_participation|float|Particpation for SAT 2017.|
|SAT|sat2017_ebrw|int|Evidence-Based Reading and Writing score for SAT 2017.|
|SAT|sat2017_math|int|Math score for SAT 2017.|
|SAT|sat2017_total|int|Total score for SAT 2017.|
|ACT|act2017_participation|float|Particpation for ACT 2017.|
|ACT|act2017_english|float|English score for ACT 2017.|
|ACT|act2017_math|float|Math score for ACT 2017.|
|ACT|act2017_reading|float|Reading score for ACT 2017.|
|ACT|act2017_science|float|Science score for ACT 2017.|
|ACT|act2017_composite|float|Compostie score for ACT 2017.|
|SAT|sat2018_participation|float|Percentage of particpation for SAT 2018.|
|SAT|sat2018_ebrw|int|Evidence-Based Reading and Writing score for SAT 2018.|
|SAT|sat2018_math|int|Math score for SAT 2018.|
|SAT|sat2018_total|int|Total score fo SAT 2018.|
|ACT|act2018_participation|float|Percentage of Studends Tested for ACT 2018.|
|ACT|act2018_english|float|Average English Score for ACT 2018.|
|ACT|act2018_math|float|Average Math Score for ACT 2018.|
|ACT|act2018_reading|float|Average Reading score for ACT 2018.|
|ACT|act2018_science|float|Average Science score for ACT 2018.|
|ACT|act2018_composite|float|Average Compostie Score for ACT 2018.|

3. Conclusion
- We see an increase SAT 2017 and 2018 participation rates, but a drop in ACT. Although there is no statistical difference between the specific SAT/ACT scores between 2017 and 2018, we saw a slight drop in the mean specific SAT/ACT scores from 2017 to 2018, regardless of the type of test.
- This is likely due to the drop in difficulty level of SAT 2018 paper, resulting in a harsh marking/penalty scheme and a drop in SAT scores. [source: https://www.compassprep.com/when-up-is-down-june-2018-sat/].
- In addition, there was a change in ACT 2018 policy. It ended the self-paced timing for students with the extended-time accommodation, which could be a set back to sutdents who qualified for extended time accomodation. This could result in the lower participation rate and test results. [source: https://www.scoreatthetop.com/blog/changes-to-the-act-2018].

4. Recommendations
- In the heatmap, we see an obvious checker box pattern between SAT and ACT scores. There is an inverse correlation pattern between the SAT and ACT scores, regardless of the year. This advocates the strategy of taking both SAT and ACT tests, and using the outcomes of both test to hedge against each other so as to increase the odds of admission.
- It is recommonded in future studies to incoporate datasets on successful admissions with states information so as to better analyze and recommend which state to take the SAT/ACT in.

## Problem Statement

In this project I am comparing the data for the ACT and SAT standardized tests, looking at state averages over the years 2017 and 2018, with the goal of inspecting and making recommendations for the College Board, developers of the SAT, to increase their test's participation in future years.

## Executive Summary

If you want to, it's great to use relative links to direct your audience to various sections of a notebook. **HERE'S A DEMONSTRATION WITH THE CURRENT SECTION HEADERS**:

### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

## Data Dictionary

final.csv

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object - str|SAT/ACT|String of a state's name|
|sat_part_17|float|SAT 2017|A state's participation rate for the 2017 SAT test. Possible rates are between 0 and 1.|
|sat_part_18|float|SAT 2018|A state's participation rate for the 2018 SAT test. Possible rates are between 0 and 1.|
|sat_part_change|float|SAT|The difference between 2018 and 2017 participation rates. Possible rate changes are between -1 and 1.|
|sat_score_17|float|SAT 2017|The average total score of a state's students for the 2017 SAT. Possible values range from 400 to 1600.|
|sat_score_18|float|SAT 2018|The average total score of a state's students for the 2018 SAT. Possible values range from 400 to 1600.|
|sat_score_change|float|SAT|The difference between average total score of a state's students for the 2018 SAT and the 2017 SAT. Possible value changes range from -1600 to 1600.|
|act_part_17|float|ACT 2017|A state's participation rate for the 2017 ACT test. Possible rates are between 0 and 1.|
|act_part_18|float|ACT 2018|A state's participation rate for the 2018 ACT test. Possible rates are between 0 and 1.|
|act_part_change|float|ACT|The difference between 2018 and 2017 participation rates. Possible rate changes are between -1 and 1.|
|act_score_17|float|ACT 2017|The average total score of a state's students for the 2017 ACT. Possible values range from 0 to 36.|
|act_score_18|float|ACT 2018|The average total score of a state's students for the 2018 ACT. Possible values range from 0 to 36.|
|act_score_change|float|SAT|The difference between average total score of a state's students for the 2018 ACT and the 2017 ACT. Possible value changes range from -36 to 36.|

## Conclusions and Recommendations

The biggest swing by far in SAT's favor this year were the win of new contracts in Colorado and Illinois. If the College Board can make progress towards contracts in other states, they can take even larger market shares. Looking at Florida as an example, the feasability study indicated that the SAT would be a suitable replacement to Florida's own standardized test with a smaller amount of supplementary material than the ACT. Were a team assigned to develop the necessary supplement and to put it forth for Florida's consideration, we might more than make up for the lost participation between 2017 and 2018
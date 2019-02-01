
## Problem Statement

In this project I am comparing the data for the ACT and SAT standardized tests, looking at state averages over the years 2017 and 2018, with the goal of inspecting and making recommendations for the College Board, developers of the SAT, to increase their test's participation in future years.

## Executive Summary

After visualizing and numerically summarizing the participation data for the 2017 and 2018 SAT and ACT tests, I focused my external research upon three states: Illinois, Colorado, and Florida. Illinois and Colorado each saw large increases in SAT participation, while Florida had a significant drop in participation.

The gains were both attributed to state-wide contract acquisition: Illinois and Colorado high school students are all now required to take the SAT. The sharp decline in Florida's participation was unexplained through the course of the project, but its lack of a state-wide SAT requirement was examined as an example for recommendations to be made to the College Board.

## Methodology
As seen in the ./code/Project-Submission-Notebook file, much of the work centered around Exploratory Data Analysis. The data were imported, formatted, and corrected as necessary, before correlation among variables was visualized via heat map, scatter plot, and histograms of relevant features. I then explored summary statistics before making final visualizations for my presentation (slides included under ./code/GA_DSI_Project_1.pdf).

After that I conducted my external research to reach my conclusions.

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

The biggest swing by far in SAT's favor this year was the win of new contracts in Colorado and Illinois. If the College Board can make progress towards contracts in other states, they can take even larger market shares. Looking at Florida as an example, a feasibility study conducted by members of their Education Board indicated that the SAT would be a suitable replacement to Florida's own standardized test with a smaller amount of supplementary material than the ACT. Were a team assigned to develop the necessary supplement and to put it forth for Florida's consideration, we might more than make up for the lost participation between 2017 and 2018.

In a retrospective correction, after the project was completed I found out that the decline in Florida's participation was due to a data entry error on the part of one of my peers. The conclusions I drew concerning the state, however, still proved to be an apt example for efforts that would be needed to acquire more state contracts and thus I have kept the overall results of this project intact.

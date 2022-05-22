# Fantasy_Football_Modeling

Project Status: [Incomplete]

This project aims to scrape football data from various sources and append to a main dataframe, with the intent of building the most accurate model to predict fantasy points per week. 

The current state of this project is pulling playoff data from the 2021 season by week, defensive rankings, and NFL weather for the given week. Then a custom point system is calculated for fantasy points by position.

Future additions include, but are not limited to, weekly depth chart positioning and comparing defenses to those in similar depth chart spots. Additionally, we'd like to incorporate playing styles for skill positions and compare like playstyles to individual defensive schemes, for example, taking into account how slot receivers play against a particular defense or cornerback. 

At this stage, we have some basic modeling in the `main_df` notebook; however, we aim to improve the modeling portion when we have 2022 data from the upcoming season. 
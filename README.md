# GYTS4-EDA
An EDA on the usage of tobacco products by school-age students in India. The dataset was created by IIPS, Mumbai and can be downloaded [here](https://data.gov.in/catalogglobal-youth-tobacco-survey-gyts-4). The goal of this project is to evaluate the use of tobacco products by school-age Indian students on a state-by-state basis.
**You can view the results by downloading GYTS_markdown.html**. If you want to peruse the .rmd file and tweak the code, feel free to do so. I've provided all the data that I used to make this.

## Analysis
First, I cleaned up the original data into portions that are easier to understand and use in R. You can look at the datasets I've created in the [Sources](https://github.com/HaveSumPatience/GYTS4-EDA/tree/main/Sources) folder. Here's a breakdown of the different files:
* [GYTS4_state_usage_total.csv](https://github.com/HaveSumPatience/GYTS4-EDA/blob/main/Sources/GYTS4_state_usage_total.csv) - Comprehensive data on tobacco usage by students in the states and union territories of India.
* [state_ur.csv](https://github.com/HaveSumPatience/GYTS4-EDA/blob/main/Sources/state_ur.csv) - Tobacco usage split into urban and rural areas for each state.
* [state_ecig.csv](https://github.com/HaveSumPatience/GYTS4-EDA/blob/main/Sources/state_ecig.csv) - E-cigarette awareness and use in each state.
Most of the work was done in R language, using the plotly package. The maps were created through QGIS and are available in the [Maps](https://github.com/HaveSumPatience/GYTS4-EDA/tree/main/Maps) folder. 

# The Prediction of Building Energy Consumption Using Machine Learning Approaches: A Case Study of New York
This repository includes the files needed to carry out the analysis for the CASA0010 Dissertation, set out to answer the following three research questions:

- **RQ1**: Which machine learning methods is the most effective in predicting BEC at the city level and how does this differ from previous research?
  
- **RQ2**: What characteristics are thought to influence energy use in buildings and do socio-demographic and economic factors have a significant impact?

- **RQ3**: What insights and policy implications do these findings provide into the potential relationships between these input factors and the building energy performance in NYC?


To carry out the analysis, run the following files in order: 

1_Data_cleaning.ipynb - This file carries out the initial data cleaning of the PLUTO and LL84 data file

2_Data_integration.ipynb - Spatail join with ACS data file at NTA level

3_Analysis_of_the_collected_data.ipynb - Check if it follows a normal distribution, if the variable needs logarithmic transformation

4_Predictive_Models.ipynb - Prediction models based on building, economic and socio-demographic factors

5_Predictive_Model_with_built_environment_only_.ipynb - Prediction models based on physical building characteristics only

6_Energy_mapping - GIS energy mapping via QGIS version 3.28.7 (long term release)

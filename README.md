# Final Project Investigating Political Stability Worldwide
  + Final project for Data Science Applied Public Affairs investigating variation in political stability across the globe.
  + Data folder contains all raw and cleaned data sets from The World Bank. 
  + Final_Project_Memo.rmd contains preliminary findings.
  + Final_Presentation_Pingatore.pdf contains the presentation formated in PDF,
  + Final_Project_Workup_Pingatore.rmd/.pdf contains the final workup, analysis and findings of the research. 

# Introduction 
 + Why does political stability vary across the globe? Are some nations innately built upon stability producing institutions while others are doomed, or can instability be triggered even within the most stable regimes? My research project will investigate the factors the produce political stability, or fail to, within the various countries across the globe. 
 
  + There is a vast deal of research and theories that investigate the mechansims that produce political stability within a country. Many scholars will argue that the quality of a nations insitutions are responsible for the stability, or lack thereof, that a country enjoys. The difficulty falls in attempting the quatatively prove this theory. What kind of insitutions are we categorizing, how many categories will we have, who will categorize them? The list of problems that would arise from such a task would be insurmountable. With that being said, my research aims to scratch the surface of this goal. The research conducted, utilizes a large N dataset of countries and incorporates more rudemntary predictors suchas GDP and Litteracy rate in order to better understand variation in political stability. Let us be clear however that the predictors in this research are not mechanisms that produce political stability themselves. Metrics suchas a stable GDP are preceeded by the economic insitutions that provide the conditions hospitible for a stable GDP. At most, our research will provide insight into the quality of a states insitutions through our predictor metrics, which will give us some indication into the level of political stability of a country. 


# The Data
  + Our data comes from The World Bank and contains a total of 213 countries. The dataset provides estimates on political stability for each country from 1996 to 2019. The World Bank calculates their metric of political stability based on the absence of violence and terrorism within a given country. The political stability metric is measured on a scale from -2.5 to 2.5, with negative values indicating weak stability and positive values indicating strong stability. 
  
  + The cleaned political stability dataset is merged with additional datasets from The World Bank, containing our predictor variables. This includes The World Bank's datasets on: population, fuel exports, military expenditure, ease of conducting business, inflation rate, literacy rate, and access to electricity.The compiled dataframe is saved for additional research within this repository as compile_stabiliy.csv. 
  

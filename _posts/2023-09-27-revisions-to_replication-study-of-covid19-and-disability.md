**Re-analysis plan for Holler, et. al: "Reproduction of Chakraborty 2021: An intracategorical analysis of COVID-19 and people with disabilities" **
By Grace Sokolow
Last Updated September 27, 2023

Holler's 2023 reproduction of Chakraborty 2021 is successful in 
1. locating the original ACS data and showing how to process it
2. locating the original COVID-19 data and showing how to process it and join it with the ACS data
3. identifying missing data, testing and documenting a way to process it, and matching it with the original study results.
4. reproducing the map of covid-19 incidence
5. creating a new map of disability rates to provide more context
6. calculating descriptive statistics and comparing them to the original descriptive statistics found
7. conducting a correlation analysis using pearson's r and comparing results to the original findings both in magnitude and direction
8. identify and remedy a discrepancy in the covid-19 data
9. conducting an additional statistical test for normality
10. based on the results of the shapiro wilk normality test,  conducted a non-parametric correlation analysis using spearman's rho and comparing this result to the original pearsons r findings
11. understanding as much as possible the outputs of the SatSCan software used in the original study to implement kulldorf sampling
12. using SpatialEpi as an equivalent open source alternative to the free but not open source SatSCan to reproduce the clustering process
13. providing both the code to run SpatialEpi and preloaded results, to save time
14. calculating local and cluster relative risk for the SpatialEpi output
15. visualizing and explaining the results of the SpatialEpi output
16. upon generating a different number of gee clusters based on the SpatialEpi output, returning to SatSCan to try and replicate the original results using the original software
17. explaining the implications of the SatSCan software decision - used cluster relative risk of the center county for each cluster, and included both the hierarchical and GINI-optimized sets
18. shifting to reanalysis > visualizing where the two methods agree/disagree for spatialepi and satscan hierarchical and spatial epi and satscan gini...


However, I propose the following changes:
1. minor clarification around the wording around cluster vs location based kulldorf clustering such that it is more clear that the original study used only the center point of each cluster
2. visualizing the original SatSCan outputs to help make the differentiation between the SpatialEpi and SatSCan methods more clear.
3. map the GEE clusters actually used in the study
4. clarify the SatSCan combination of GINI and non-heirarchical clisters - what do we do about this ambiguity?

5. conducting the study with more up to date data (save for another time)

## Contributing to an existing reproduction of Chakraborty's study of COVID-19 risk and disability.

During the course of this reproduction study, I learned how challenging it can be to devise a pre-analysis plan.
I'm very used to diving right into the data and poking around from there, but this re-analysis approached forced me to be more methodical and ultimately, more transparent with my workflow, including areas that could still use more improvement.
The reproduction study deviated from the original in that it used the Spearman's Rho rather than the Pearson's R to test correlations between the dependent and independent variables.
It also deviated in that it used SpatialEpi software to generate Kulldorff clusters rather than SaTScan. This lead to unexpected differences in results that were then seperately persued in parallel analysis.
These deviations served to improve upon the methods in the original study and illuminate some of the implicit choices not previously explained in the study.
My contributions to the reproduction study largely focused on improving how the Kulldorff clusters are altered before being input to the GEE models. Even still, this section could be improved, particularly by replicating the set of comparison maps for the SpatialEpi generated clusters in addition to the SaTScan ones. 

Read the full [report](https://gsokolow.github.io/RPr-Chakraborty-2021/).

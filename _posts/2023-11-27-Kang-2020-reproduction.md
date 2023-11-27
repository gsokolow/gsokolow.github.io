In 2020, [Jeon-Young Kang et al](https://ij-healthgeographics.biomedcentral.com/articles/10.1186/s12942-020-00229-x) measured hospital accessibility as a function of population (COVID-19 cases; at risk population) serviced by a hospital (based on a 10, 20, or 30 minute service area) and the number of available ventillators and beds at that hospital.
This analysis was carried out both for hospitals in Chicago only and for all of Illinois.
In 2021, Joe Holler et al successfully reproduced Kang's study, and in 2023, proposed improvements to how speed limit data is handled and how hospital service area information is allocated to the uniform hexagonal grid used to communicate the final results.

This [2023 replication study](https://gsokolow.github.io/RPr-Kang-2020/) of Kang et. al implements one of these improvements by introducing area-weighted re-aggregation into the final allocation of accessibility scores. 
In Kang et. al's original study, a hexagon's accessibility score is determined by the accessibility scores of any catchment areas that overlap more than 50% of the hexagon's area. 
This means that the influence of catchment areas that overlap just over 50% of the hexagon is exaggerated, whereas the influence of catchment areas that overlap just under 50% of the catchment areas is minimized.
To address this issue, we implemented an area weighted re-aggregation of accessibility scores where hospital catchment area scores are allocated to each hexagon based on the percentage of the hexagon's area they overlap with.
When compared with the original study, this alternative method found slightly lower rates of hospital accessibility in northern and western Chicago, and slightly higher rates of accessibility in the center city. 
We only conducted the alternate analysis on Chicago to conserve computing resources.



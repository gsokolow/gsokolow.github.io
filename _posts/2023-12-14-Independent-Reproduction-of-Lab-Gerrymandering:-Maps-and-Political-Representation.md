In the fall of 2021, Niwaeli Kimambo, Assistant Professor of Geography at Middlebury College, taught Human Geography with GIS, an introductory level vector GIS course for undergraduates.
One of the course labs was Gerrymandering: Maps and political representation. The original text of the lab can be found in the GitHub [repository](https://github.com/gsokolow/Rpr-120Lab-Gerrymandering), under docs/07_Lab07_PartisanGerrymandering.pdf.
In 2023, [Grace Sokolow](https://gsokolow.github.io/Rpr-120Lab-Gerrymandering/) successfully replicated this lab in python, where it had previously been run in QGIS.

While the reproduction was successful, it raises issues regarding planar and geodesic areal estimations as well as geometry errors arising from overlaying two vector layers. 
It also considers a variety of threats to validity, including assumptions of even voter distribution, boundary distortions, the modifiable areal unit problem, and theoretical caveats to compactness scores.
This replication could benefit from integration of original data sources and efforts to streamline the code.


# Tracking Firepower in Ukraine: Is Military Aid a Proxy for Weapons Deployment?

This project investigates whether international military aid to Ukraine can be used as a proxy for battlefield activity. Using satellite fire data and spatial models, we examine whether allocated military support correlates with fire activity. Indeed, we find that lagged cumulative military aid and war fire activity grow together over time:

 <p align="center">
  <img src="Key Figures/Ukraine-Figure-1" width="600"/>
</p>

## Summary
We combine geolocated fire data from The Economist’s War Fire Dataset and military aid allocations from the Ukraine Support Tracker (Trebesch et al., 2023). Control maps from the Institute for the Study of War (ISW), road networks from the World Bank (2023), and mineral deposit data from the USGS are used to test four geospatial hypotheses. In this figure, we separate war-related fires in Russian-controlled areas from those occuring in Ukrainina-controlled areas. 

<p align="center">
  <img src="Key Figures/Ukraine-Figure-2" width="700"/>
</p>


## Main Findings

We find a statistically significant correlation between cumulative military aid and war-related fire activity. Correlations are stronger in Ukrainian-controlled areas and in zones with good road access, suggesting a relevant role of transport networks in facilitating access to conflict areas. Surprisingly, war activity also increases near strategic mineral sites, possibly due to the location of Russian forces rather than deliberate avoidance by Ukraine. Below, we plot cumulative military aid and war-fire area by area of control.


<p align="center">
  <img src="Key Figures/Ukraine-Figure-3" width="700"/>
</p>

### Road Network and Mineral Resources

Moreover, the correlation between military aid and fire activity may depend on transport infrastructure and the presence of natural resources. Below, we visualize Ukraine’s road network (World Bank, 2023) and the location of strategic mineral deposits (USGS, 2025). These maps help us understand how logistics and natural resources shape conflict intensity.

<div align="center">
  <img src="Key Figures/Ukraine-Figure-4.png" alt="Ukraine Roads" width="45%"/>
  <img src="Key Figures/Ukraine-FIgure-5.png" alt="Minerals in Ukraine" width="45%"/>
</div>

## Contents

This repository includes: An  analysis script in R Markdown (Ukraine_Geospatial.Rmd) and its rendered output (Ukraine_Geospatial.html). The data files used in the analysis (data/ folder), including military aid, satellite fire data, geospatial shapefiles, and mineral resource maps. And the key visual figures illustrating the core findings of the project

## Data Sources

This project draws on the following publicly available datasets:

	- Ukraine Support Tracker (Trebesch et al., 2023): Records international military aid allocations to Ukraine. Kiel Institute for the World Economy – Ukraine Support Tracker
  	- War Fire Dataset (The Economist, 2022): Satellite data distinguishing war-related fires in Ukraine from natural fires. The Economist War Fire Model GitHub Repository
   	- ISW Control Maps (Institute for the Study of War, 2025): Shapefiles tracking areas under Russian and Ukrainian control. Institute for the Study of War
	- World Bank Road Network (2023): GIS data on major road infrastructure in Ukraine. World Bank Open Data
 	- USGS Mineral Resources (2024): Shapefiles of strategic mineral deposits across Ukraine. USGS Mineral Resources Data System

## References
	Glanville, L., & Pattison, J. (2024). Ukraine and the opportunity costs of military aid. International Affairs, 100(4), 1571–1590. https://doi.org/10.1093/ia/iiae122
	Trebesch, C., Antezza, A., Bushnell, K., Frank, A., Frank, P., Franz, L., Kharitonov, I., Kumar, B., Rebinskaya, E., & Schramm, S. (2023). The Ukraine Support Tracker. Kiel Working Paper No. 2218. Kiel Institute for the World Economy.
	Tian, N., Lopes da Silva, D., Béraud-Sudreau, L., Liang, X., Scarazzato, L., & Assis, A. (2023). Developments in military expenditure and the effects of the war in Ukraine. Defence and Peace Economics, 34(5), 547–562. https://doi.org/10.1080/10242694.2023.2221877
	The Economist. (2022). War Fire Dataset. https://github.com/TheEconomist/the-economist-war-fire-model
	World Bank. (2023). Ukraine - Roads. https://datacatalog.worldbank.org
	USGS. (2024). Mineral Resources Data System (MRDS). https://mrdata.usgs.gov/mrds
	Harward, C. et al. (2025). Russian Offensive Campaign Assessment, March 2025. Institute for the Study of War.

## Authors

Javier Ospital, Isabella Becerra, Camilo Giraldo, Álvaro Delgado


# PSU-USP522-Practicum
**[A Comparison of Census 2010 SF1 & Differentially Private Data in Oregon](https://a-brasch.github.io/PSU-USP522-Practicum/)**  
Portland State University  
Graduate Certificate in Applied Social Demography  
USP 522 Research Practicum in Applied Demography  
Winter Quarter 2020

[GitHub repository: PSU-USP522-Practicum](https://github.com/a-brasch/PSU-USP522-Practicum "GitHub repository: PSU-USP522-Practicum")  
[PSU webspace: USP 522](http://web.pdx.edu/~abrasch/USP522/ "PSU webspace: USP 522")  
[Esri Dashboard: Census 2010 SF1 vs. Differential Privacy: Oregon Geographies](https://maulfoster.maps.arcgis.com/apps/opsdashboard/index.html#/6fea214d11784e5aa277157e8f5db3f0 "Esri Dashboard: Census 2010 SF1 vs. Differential Privacy: Oregon Geographies")

---

**Abstract:**  
The U.S. Census Bureau has committed to deploy a modernized disclosure avoidance system (DAS) in order to safeguard data collected during the 2020 Census. The foundation of the updated DAS methodology is differential privacy—a set of mathematical algorithms developed by cryptographers and computer scientists intended to protect respondent confidentiality. Differential privacy leverages a suite of techniques that includes the introduction of uncertainty (i.e., noise, synthetic data) into aggregated respondent data, data-swapping, and data imputation, with the goal of ensuring that enumerated data sets cannot be backwards-engineered to identify individual respondents. Differential privacy strives to balance confidentiality and data accuracy; however, many researchers have expressed concern over these techniques' impact on data quality and the potential to adversely affect demographic research and policies, as well as the lives of racial/ethnic minorities and under-represented population subgroups (Salvo 2019, Akee 2019, Van Riper 2019, Nagle 2019). To help researchers and data users assess the "fitness for use" of 2020 census data products produced using differential privacy, the Census Bureau prepared 2010 Census Demonstration Data Products, which were made public on October 19, 2019.

Census data are the foundation of a myriad of public- and private-sector efforts that support accurate funding and resource allocation, housing policy development, and emergency preparedness. From the perspective of county and local governments in Oregon, accurate census data is imperative to the success of such activities as drawing appropriately-sized school attendance areas, assessing the impact of changes in land use and zoning, reaching at-risk populations, determining intercensal population estimates, and forecasting future populations (Salvo et. al 2019, 18). The protection of individual respondents privacy is a necessary and absolutely worthwhile endeavor, but it should not sacrifice the accuracy of data that is essential to the aforementioned processes.

The intent of this study is to better understand the effects of differential privacy on census data by comparing multiple demographic variables at various geographic scales within the state of Oregon. Of particular focus are key demographic variables that inform population forecasting and housing and land use planning, including population per age group, average household size, and occupancy rate. The geographic units of analysis include Oregon counties, places, Urban Growth Boundaries (UGB) of Oregon cities, and non-UGB county areas. For analysis and reporting purposes, the project utilizes the R programming language and RStudio integrated development environment, R Markdown (USP522_DiffPrivOR.Rmd), R packages (tidyverse, tidycensus, sf, rgdal, tigris, readxl, writexl, plotly, htmlwidgets, xfun, and arcgisbinding), U.S. Census API, Alteryx, Esri ArcGIS, and Microsoft Excel.

The results of this research, including interactive visualizations, indicate that adjustments to the differential privacy algorithms and privacy loss budget allocation are necessary to ensure that accurate data is prepared for public consumption. Census Bureau analysts have stated that several promising solutions to the widely-recognized post-processing errors have been identified. (Abowd and Velkoff 2020). Numerous researchers and data users are willing to continue to assist in the process of determining the right balance between accuracy and privacy, and it would benefit all stakeholders if the Census Bureau produced more demonstration data products to show progress on correcting post-processing errors and fine-tuning on the the differential privacy mechanism.

---

**Contact Information:**  
Alex Brasch

Portland State University | Graduate Student  
Graduate Certificate in Applied Social Demography  
abrasch@pdx.edu

FLO Analytics | Population Geographer | Data Analyst  
abrasch@flo-analytics.com

Personal | Cyclist | Data Nerd | Homebrewer  
alexbrasch88@gmail.com

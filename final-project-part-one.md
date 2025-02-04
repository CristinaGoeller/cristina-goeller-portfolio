| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


> Important note: this template includes major elements of Part I, but the instructions on Canvas are the authoritative source.  Make sure to read through the assignment page and review the rubric to confirm you have everything you need before submitting.  When done, delete these instructions before submitting.
 
# Outline

This project aims to investigate the housing affordability crisis in Nassau County, NY, and how it has been intensified by the 2008 recession and Hurricane Sandy in 2012. It seeks to understand how these events have disproportionately impacted different communities, particularly focusing on racial disparities, and how recovery efforts have addressed or worsened existing inequalities. Moreover, this will also explore the concept of housing affordability, including the 30% rule for renters and the 28% rule for homeowners, and how these metrics apply to Nassau County. The project will analyze historical data and current trends to advocate for a more equitable and resilient future for housing in the region.

Specifically, the project will examine the historical context of housing in Nassau County, including the legacy of discriminatory policies that have limited access to housing for people of color. It will then analyze how the 2008 recession, including foreclosure rates and the impact on Black/Hispanic vs. White households, and Hurricane Sandy, including storm surge areas and FEMA funding distribution, have affected housing affordability. The project will use visualizations, including maps of income and ethnicity by census tract, and data from sources like the GIS Census Historical Index and HUD, to illustrate the current state of housing affordability and the disparities that exist. Ultimately, this project aims to shed light on the complex factors contributing to the housing affordability crisis in Nassau County and propose solutions for a more equitable future.

# Story Arc (Structure of Project) 

1.	Exposition: Introduce Long Beach, NY, and the narrator's childhood experience observing socioeconomic disparities tied to location. Introduce the broader context of Nassau County as "America's first suburb" and its history of exclusionary housing policies. User story: As a resident of Long Beach, I want to understand the historical context of housing disparities in my community.
2.	Rising Action: Define housing affordability (30% rule, 28% rule) and present visualizations of current affordability challenges in Nassau County, including income and ethnicity by census tract, and HUD data on housing burden. User story: As a taxpayer, I want to see data visualizing the extent of the housing affordability problem in Nassau County.
3.	Climax: Focus on the two key events: the 2008 recession and Hurricane Sandy. Detail their impact on housing, including foreclosure rates, storm surge areas, and FEMA funding distribution, with a particular focus on racial disparities. User story: As a homeowner in Nassau County, I want to understand how the 2008 recession and Hurricane Sandy impacted housing values and affordability.
4.	Falling Action: Analyze how these events intensified existing inequalities and explore the recovery efforts, examining whether they addressed or exacerbated the challenges. User story: As a community advocate, I want to see data comparing the recovery outcomes for different demographic groups after these events.
5.	Resolution: Present potential solutions and advocate for a more equitable and resilient future for housing in Nassau County. User story: As a policy maker, I want to explore potential solutions to address the housing affordability crisis in Nassau County.

## Initial sketches
![image](https://github.com/user-attachments/assets/c90f2e5d-0bea-4bab-86d9-728d0e3cdbe2)
![image](https://github.com/user-attachments/assets/61ef5864-59b3-4456-bf29-d1e144607ba8)
![image](https://github.com/user-attachments/assets/5b6fecfe-fd30-41bb-9f44-944bd9cb27e6)


# The data

There are two main sources of data for understanding the major analysis of this project. The first is the National Historical GIS Repository. That data set organizes census data both spatially and on a time scale. For this project it would be helpful to create maps that will analyze housing affordability based on socio-economic factors. Next is the Federal Department of Housing and Urban Development dataset portal. This dataset pulls from 1 and 5 year estimates of the American Community Survey to organize county level data on affordability. This will have to be separated into multiple tables (delineating between renters and homeowners). 


| Name | URL | Description |
|------|-----|-------------|
|National Historical Graphical Information System | https://data2.nhgis.org/main  | The first is the National Historical GIS Repository. That data set organizes census data both spatially and on a time scale. For this project it would be helpful to create maps that will analyze housing affordability based on socio-economic factors. This data is publically available through the first link; However it needed to be filtered to get the correct information which I attached in the second link. |
|Federal Department of Housing and Urban Development | https://www.huduser.gov/portal/datasets/cp.html#query_2006-2021  | The Federal Department of Housing and Urban Development dataset portal. This dataset pulls from 1 and 5 year estimates of the American Community Survey to organize county level data on affordability. This will have to be separated into multiple tables (delineating between renters and homeowners). |

# Method and medium
I will be using ArcGIS and Tableau to complete the major components of this project. GIS will be used to understand spatial & statistical relationships between location and affordability. Because GIS does not provide enough options to follow good design principles when accessing statistical relationships, Tableau can be used supplementally. 

There is also this tool (linked below) that will create maps usng certain components of historical data pulled from NHGIS. However, because there is less control over the manipulation of the data, I will probably pull the raw data (linked above) into GIS. 

http://historiccensus.longislandindexmaps.org/

## References
https://rpa.org/work/reports/long-islands-rental-housing-crisis

https://projects.newsday.com/long-island/segregation-real-estate-history/#nd-promo

https://www.hofstra.edu/pdf/academics/css/ncss_mtge_lending.pdf

https://www.hofstra.edu/pdf/academics/css/ncss_housing_crisis.pdf 

https://libertystreeteconomics.newyorkfed.org/2013/10/long-islands-economy-back-on-track-after-sandy/ 
## AI acknowledgements
Used to organize and edit a more detailed outline of my project down into the consolidated project description and story arc. 

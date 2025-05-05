| [home page](https://cristinagoeller.github.io/cristina-goeller-portfolio/) | [MWDBE Businesses: GIS Project](MWDBEBusinesses) | [Vizualizing Tarrifs: Tableau Makeover Monday](TableauRemake) | [Housing on Long Island](TellingStoriesDocumentation) | [NYC School Landscape Analysis](EDCSchoolsAnalysis) | [Phipps Concervatory Capstone Project](CapstoneProjectPhipps) | [Custom Base Map Creation](AdvancedGISPortfolio) | [Sustainable Business: Case Presentation](SustainableBusiness) | [Cost-Benefit Analysis: Cap&Trade v. Carbon Tax](Cap&TradevCarbonTax)

> This project is a continuation of the deck I created last sumer at NYCEDC. The following describes my final project for Advanced Spacial Analysis.
# Context/Data Collection
Over the summer I worked at the New York City Economic Development Corporation (NYCEDC). One of my projects was to, in google maps, to create a map of New York City Public Schools that align with the 4 innovation industries (I2) within the strategic neighborhoods of the Corporation. I ended up running out of time to do any analysis in GIS, and I feel it will be helpful to revisit this data for this project. The scope here is to enhance my final presentation using Insights to see where the boundaries of analysis are. [You can find the powerpoint deliverable from the summer here](https://docs.google.com/presentation/d/1RvWorOLHkVN05CtRbPpTx6vSI1LuUmLC/edit?usp=sharing&ouid=114772801042153996355&rtpof=true&sd=true). 
# Project Summary
This project aims to analyze the distribution of schools across New York City categorized under the NYCEDC’s Innovation Industry designation within their strategic neighborhoods. I plan on leveraging ArcGIS Insights to analyze the concentration of schools aligned with specific industries and identify potential patterns in their spatial relationships. 
# Problem Statement
The equity team at NYCEDC is specifically focused on employment pathways in neighborhoods they are in the process of redeveloping. Having a clear understanding of how they are distributed and aligned with I2. This project seeks to answer the following key questions: 
What is the overall distribution of schools associated with each of the four Innovation Industry designations across NYC? 
Which NYCEDC strategic neighborhoods have the highest concentration of schools in each Innovation Industry? 
Are there spatial clusters of schools within specific Innovation Industry categories?
# Deliverable
Interactive ArcGIS Insights Workbook showcasing the spatial analysis and visualizations.
# Walk-Through

[Overall Concentration:](https://insights.arcgis.com/#/view/2789190f00e14fc3a64c86341ab00c05) Included in this analysis workbook is four distinct pages. The first is an overall distribution analysis dashboard. The first map shows by innovation industry where each school is located. Added onto this is a bar graph showing the largest concentration of schools by industry are in the Creative category. There is another map that shows where the higher concentrations of schools are based on the strategic zones of EDC, and there is a corresponding summary table that details which schools are in which neighborhood. When you select a neighborhood, it changes the list included beneath. 

[Neighborhood Concentration:](https://insights.arcgis.com/#/view/9cab3a11ef744fb19a3940598593466d) In the next page labeled “Neighborhood Concentration,” this shows per strategic neighborhood how many schools are within each distinct neighborhood. A piece of clarification here is the strategic neighborhood designation for EDC is different than those official boundaries used by EDC. That is why there are multiple concentration circles per “Strategic neighborhood.” 

[School Cluster Analysis:](https://insights.arcgis.com/#/view/9b2476a23dc44addbf32fc6954d453a2) The third page shows a cluster analysis of schools. There is an innovation industry filter available to change which schools is being shown on the map. I also included a summary table so people can see directly which schools are in which clusters. 

[STEAM Center Analysis:](https://insights.arcgis.com/#/view/7f661f886fd94bec9cafac4d744d4e15) Finally, I attempted to do a proximity analysis between the schools and steam centers across the city. This is another data set I collected over the summer. Here is where I met the limitations of insights---it is not possible to get a detailed list of schools that are inside versus outside of the buffer. When I was looking online, I saw that it has something to do with the spatial aggregation---since it is simplified in insights. 

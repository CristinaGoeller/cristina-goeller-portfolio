| [home page](https://cristinagoeller.github.io/cristina-goeller-portfolio/) | [MWDBE Businesses: GIS Project](MWDBEBusinesses) | [Vizualizing Tarrifs: Tableau Makeover Monday](TableauRemake) | [Telling Stories with Data: Shorthand](final-project-part-one) | [Advanced GIS Portfolio](AdvancedGISPortfolio) | [Sustainable Business: Case Presentation](SustainableBusiness) | [Cost-Benefit Analysis: Cap&Trade v. Carbon Tax](Cap&TradevCarbonTax) 


> Important note: This is the documentation for creating
> [America's First Suburb: Who is this place made for? ](https://carnegiemellon.shorthandstories.com/whoisthisplacemadefor/index.html)
 
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
|National Historical Graphical Information System | https://data2.nhgis.org/main https://shorturl.at/nQabc |  The first is the National Historical GIS Repository. That data set organizes census data both spatially and on a time scale. For this project it would be helpful to create maps that will analyze housing affordability based on socio-economic factors. This data is publically available through the first link; However it needed to be filtered to get the correct information which I attached in the second link.  |
|Federal Department of Housing and Urban Development | https://www.huduser.gov/portal/datasets/cp.html#query_2006-2021  | The Federal Department of Housing and Urban Development dataset portal. This dataset pulls from 1 and 5 year estimates of the American Community Survey to organize county level data on affordability. This will have to be separated into multiple tables (delineating between renters and homeowners). |

# Method and medium
This project has a four week timeline. I will also be using anectdotes from community members to enhance the storytelling aespect of the story. As for the medium, I will be using ArcGIS and Tableau to complete the major components of this project. GIS will be used to understand spatial & statistical relationships between location and affordability. Because GIS does not provide enough options to follow good design principles when accessing statistical relationships, Tableau can be used supplementally. 

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

# Wireframes / storyboards

# User research 

## Target audience
The target audience is supossed to be Nassau's policymakers to get a better understanding of the affordability crisis in a digestable package. The interviewees I chose are Public Policy or Information Systems masters students.  

## Interview script

| Goal                                      | Question                                                                 |
|-------------------------------------------|--------------------------------------------------------------------------|
| **Message Clarity and Alignment**         | What is the main takeaway or message you got from the story? (Did it align with my intention?) |
| **Audience Targeting**                   | Who is the intended audience?                                             |
| **Data Sufficiency and Effectiveness**    | Was there enough data to make the story convincing? Was there too much? |
|                                           | Did the story explain the data effectively, or did it just present numbers? |
| **Areas for Improvement**               | What is one thing I could improve to make the story even stronger?       |
| **General Feedback and Suggestions**       | Do you have any other suggestions or comments?                           |


## Interview findings

| Question | MISM Student | Public Policy Student | Community Resident (Nassau) |
|----------|-------------|-----------------------|-----------------------------|
| **What is the main takeaway or message you got from the story? (Did it align with my intention?)** | Understanding geographic disparities and housing conditions, highlighting social stratification. | The story effectively illustrated the relationship between historical housing policies and socioeconomic disparities. | It showed how neighborhood setups affect people’s lives and opportunities, reflecting real experiences. |
| **Who is the intended audience?** | People of Nassau, urbanism and policy enthusiasts, those interested in structural racism and segregation. | Urban planners, policymakers, community activists, and those interested in city development and social impacts. | Nassau residents, especially those unaware of historical influences, and housing decision-makers. |
| **Was there enough data to make the story convincing? Was there too much?** | Enough data, especially liked the user interview component. | Data was balanced well between quantitative (census figures) and qualitative (interviews). | Plenty of facts and figures, but not overwhelming. The interviews were powerful. |
| **Did the story explain the data effectively, or did it just present numbers?** | The story had a strong data presence but explained it thoroughly. | Visualizations were clear, and the narrative contextualized the numbers well. | Charts and maps were helpful, with explanations in plain language. |
| **What is one thing I could improve to make the story even stronger?** | Include data on second homes. | Add case studies of communities that successfully tackled similar housing challenges. | Include more voices from different parts of the community. |
| **Do you have any other suggestions or comments?** | Look at cities that successfully desegregated as a call to action. | A follow-up exploring policy interventions or community-led initiatives would be interesting. | This story needs to be seen by more people—it’s important for awareness. |


# Identified changes for Part III
> Document the changes you plan on implementing next week to address any issues identified.  

| Research Synthesis                       | Anticipated Changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| **Successful desegregation case studies**: Interviewees suggested looking at cities that have effectively addressed housing disparities. | Incorporate case studies from cities to illustrate potential solutions in the call to action. |
| **Impact of second homes on local housing**: An interviewee pointed out the need for more data on second homes and their influence on affordability. | Look into the impact of second-home ownership on Nassau’s housing market and determine whether it is a significant factor in affordability. If so, include relevant data and analysis. |
| **Enhancing data visualization**: Interviewees found the data helpful but suggested making it more engaging and easier to interpret. | Improve visual storytelling by using interactive maps, historical overlays, and before-and-after comparisons to make the data more compelling and accessible. |


## Final Thoughts

Since last week, I reframed how I am approching the story. I ended up interviewing my dad to learn more about how the island has changed from a first person perspective and get some anecdotes to sprinkle throughout the data story. 

When I boil the story down, it is really talking about how Nassau County's affordability looks completley different based on your social class, race, and/or place of origin. I ended up not having to make as many maps as I anticipated because there is a tool called the Long Island Historical Index that creates them for most of the factors highlighted. I also included morre sketches to have something together for the critique because the original data source I had was not producing the data that I thought it was. It kept pulling historical data from back in the 1800s and that was not representative of the time frame I am lookimg at here. 

Tool: http://historiccensus.longislandindexmaps.org/


## AI acknowledgements
Used to synthesize and format interview data. 

# The final data story
> [America's First Suburb: Who is this place made for? ](https://carnegiemellon.shorthandstories.com/whoisthisplacemadefor/index.html)

# Changes made since Part II/Final Design Decisions
> There are two changes I have made since part II. First, the audience where I originally wanted to focus this towards politicians to get them moving on interventions. I ended up switching it to the citizenry of Nassau because I felt awareness and education of these issues is an important first step. In undergrad, I interned at the local Comptroller's office where I authored policy reports detailing issues going on in Nassau. I ended up getting a lot of feedback from citizens explaining their experiences and ideas for interventions. I thought this would be a great edition to that series (unfortunately it does not exist anymore online because of the new comptroller). In order to tailor it in this way, I made the design decisions to highlight key statements in each section to make it more skimmable, and changed the color scheme to Nassau County's colors for branding. 
>
> 
> The other major change I made was the framing, and this also has to do with the change in audience. I wanted to do more storytelling than just the introduction, so I used another anecdote from my own experience in the first section, my dad's observation on segregation in the final section, and leveredged the story of a Black veteran denied a home. With the addition of these three components, I feel like it reads less like an academic paper and more human.
> What I really wanted Nassau residents to get out of reading the story is their experience is valid and data baked. There is a narrative in a place like Nassau that if you do not make enough to at least break even that it is intrinsically an individual issue. In other words, it is the fault of the person for making "bad decisions." In reality, there are legacy structural issues in place to keep Nassau exclusionary and we need to address those issues before placing any kind of blame on the individual.
>
> As for minor design decisions, I chose to not include the dimensionf of the case studies because it was getting too long. I also did not include the impact of second homes because there was no existing data that showed a significant impact. Finally, I was really trying to strike a balance here between being formal and informal. I wanted it to be approachable so people could follow, but complex enough to give people a jumping off point to do more research. This I still struggle with in submitting this final draft, and will be something I revisit in the future. Perhaps there should be two iterations of this: one like a fact sheet and the other like a broader data story.

## The audience
> The audience for this data story is the citizenry of Nassau County. 

## AI acknowledgements
> Used AI for brainstorming, outlining and organization.

# Final thoughts
> Overall this experience was really interesting. I found a ton of gaps even in my own knowledge that were filled though writing this presentation. The major focus of being here in grad school is understanding the built enviornment and how barriers inhibit the outcomes of people. Getting to put a story to it really makes me more confident that I have a better understanding of it since coming to Heinz. I have mixed feelings about growing up in Long Beach. However, I am grateful that it has given me the disernment of understanding that if something does not feel fair it usually is not fair.
> 
>  If I had more time, I would have loved to build out the section on segregation more. I think the story I ended up with is great and can stand alone, but I also think I could have separated it into two stories to do a deeper dive on both of those issues to supplement the analysis in the final data story. Moreover, I would have liked to work in the Hurricaine Sandy angle more. There are not I am surely most excited about sending the final copy to my parents and family friends who still live in Nassau. It will be really cool to see what their reactions are to the final story. 


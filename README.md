## Updated Project Proposal 

### as of 02.12.2023
### Project Title 
* Group Name: Code & Cry
* Group Members: Tommy Chandler, Quinn Haaga, Rachel Kovinsky and DaYoung Lee 
* Title: A Legacy of Racism, Redlining & Health Inequities in San Francisco  
* (See Original Project Proposal below)


### Roles

Each member of our group is responsible for analyzing a specific topic related to health equity, environmental justice or land use in San Francisco. Each topic will then become a layer or area of focus within our final maps and visualizations, analyzed in relation to the original HOLC redlining map of the city. A more detailed list of  assigned topics and tasks, by group member, is included below. 

After we each research and analyze our respective focus area, we will then merge our data to overlay and visualize the different components on one map. In doing so, we will be able to better understand the overlapping and compounding effects of health disparities, and their respective relationships to redlining. 

* Dayoung –  find and analyze data on asthma rates and hospitalizations, by census tract 
* Quinn – deep dive into COVID-19 data to determine what metrics and sources are the best indicator of larger health inequities
* Rachel - find and analyze data on poverty rates by census tract; also cleaning and compiling redlining data and shapefiles from the Mapping Inequality project 
* Tommy - research zoning & analyze land-use across San Francisco; also responsible for posting and updating the repo on a weekly basis, as needed

### Status Update
Upon discussing our project, we are collectively feeling a bit overwhelmed with the amount of data available that could be interesting and applicable to our proposed research question. Additionally, we realized that the boundaries of zip codes and census tracts do not align, which poses a concern because most COVID-19 data available is only available by zip code – whereas other health indicators and our redlining map shapefiles are broken down by census tract. There is also a concern that some of the datasets may not line up exactly in regards to their time frame, but we are planning to address this by pulling data from as similar of sources as possible (i.e. data all from the 2015-2019 ACS and/or 2020 census). 
Fortunately, what is working well is the frequency of our meetings and communication. We think that our group is doing a great job with gathering research and data, sharing information, and keeping each other updated on our findings. 

### Data Update
This week, each member of our group looked into a different data source that provides insight into the lasting effects of redlining on health inequities. Specifically, we analyzed CalEnviroScreen data on poverty and asthma rates, in addition to COVID-19 cases data from DataSF (the city's open data portal). Lastly, we also looked into San Francisco’s zoning and land use with data also from DataSF. In previous weeks, we pulled more general demographic data from Social Explorer that provided deeper insight into the distribution of income, health insurance, and race across San Francisco. 

### Concerns
Our current major concerns are as follows:
* The time constraints of individual team members and our collective capacity to do the indepth research, analysis, and coding needed to answer our research question. 
* The potential misalignment of spatial boundaries between data sources (i.e. the changing of census tracts from 2010 to 2020, zip codes versus census tracts, etc.). 
* Finding COVID-19 data that is broken down by census tract, rather than by zip code.
* Visualizing the historic redlining map data, which we must figure out how to align to 2020 census tracts. 
Our current minor concerns are as follows:  
* We’re nervous about bringing our data together and working collaboratively on a single jupyter notebook document because we’ve had troubles in the past with the pushing/pulling workflow in the shared repo.
* We’re nervous about not realizing other challenges or concerns with certain datasets until it’s too close to final deadlines. 


## 221 Group Project Proposal
Group Name: Code & Cry

Group Members: Tommy Chandler, DaYoung Lee, Quinn Haaga, Rachel Kovinsky

### Introduction
Since its inception in the 1930s, the practice of redlining has dictated the quality of life in communities across the country. By labeling certain neighborhoods as “hazardous” and deeming them as less than, redlining maps enabled decades of discrimination, disinvestment, and neglect of primarily non-white and low-incomecommunities. Today, the impact of redlining continues to be seen and felt in many U.S. cities – and San Francisco is no exception. 

For our final project, we plan to examine the relationship between historic redlining practices and current health disparities. Specifically, we want to examine the correlation between the areas that were deemed as “hazardous” and the potentially negative health outcomes experienced in those areas today. We will start by looking at asthma rates by census tract, and pose the larger research question: is there a relationship between historically redlined areas and current health disparities in San Francisco? Further, how has such redlining impacted the physical landscape of neighborhoods and their respective access to healthcare? 

Finally, we will also contextualize these health outcomes and potential disparities within the COVID-19 pandemic. Given that asthma has been linked to more severe cases of COVID-19, we believe that examining and comparing the impact of COVID across census tracts is another critical health outcome to study in relation to historic redlining and environmental injustice.   

### Explanation of Importance
This project is important because it has the potential to illuminate environmental and health equity issues in San Francisco that are linked to the lasting redlining and its impact on the built environment. Without question, communities across the country still feel the effects of historic redlining, and this project will allow us to actually visualize some of the consequences associated with this dark history.

Additionally, COVID-19 sparked important conversations around the health inequities and injustices that many communities have faced for decades. This project will draw from the data and research that has come out of the pandemic by identifying which communities are most vulnerable to negative health outcomes. There will be new threats and pandemics in the future, so it is crucial to understand which communities may be most at risk. As planners, it is also vital that we understand how the fields of urban planning and public health can work together to mitigate such impacts moving forward.  

### Description of Spatial Scope
Our data will focus on the city and county of San Francisco, broken down by census tracts. We will remove the census tracts that comprise the Farallon Islands and ocean from our spatial scope, due to their lack of permanent residents and data. 

### Description of Data Sources
For our project, we intend to use the following data and sources: 
* Historic redlining map for San Francisco from Mapping Inequality 
* Asthma percentiles and emergency department visits (by census tract) from CalEnviroScreening
* This map/data also includes the location of all hospitals with emergency departments
* COVID cases and deaths from DataSF
* Land use and zoning regulations from DataSF
* Relevant SF census data pulled from Social Explorer 
* Any other data that we find that provides necessary context to the lasting implications of redlining on health disparities and access to care

### Methodology
![Flowchart](https://github.com/tommychandler5/221project/blob/0abcd59f9ce0716ebcb9975c822fd95333f7ef9f/Group%20Assignments/221%20Project%20Proposal%20Methodology%20Flow%20Chart.png)

### Conclusion 
We believe that neighborhoods in the southeast corner of San Francisco are likely the most at risk of experiencing a disproportionately high number of asthma-related emergencies. We hypothesize that this is a result of the decades of discrimination, disinvestment, and neglect that can be traced back to the redlining and racism that concentrated heavy industry in that corner of the city. 
We plan to explore this data through an environmental justice framework. Ultimately, our goal is to visualize and layer different health outcomes (by census tract) onto the redlined areas of San Francisco – and then analyze the relationship between negative those outcomes and historic redlining practices. Additionally, we intend to overlay data about access to healthcare and hospitals to provide deeper insight into the lasting effects of redlining on health inequities and environmental injustice. 

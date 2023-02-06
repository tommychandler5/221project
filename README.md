## Updated Project Proposal 

### Week 04
### Mini Group Assignment
### 1. Project title 
* Group Name: Code & Cry
* Group Members: Dayoung Lee, Quinn Haaga, Tommy Chandler, Rachel Kovinsky 
* Title: A Legacy of Racism, Redlining & Health Inequities in San Francisco  
* (See Original Project Proposal below)


### 2. Roles: Give each team member a title, and define what role each team member will play, and how each person plans to contribute to the project. While this may be subject to change, it is a good idea to define this early in the project to clarify "who is doing what."

Each member of our group will be responsible for analyzing a specific topic related to health equity or environmental justice in San Francisco. Each topic will then become a layer or area of focus within our final maps and visualizations, analyzed in relation to the lingering effects of redlining. A more detailed list of  assigned topics and tasks, by group member, is included below. 

After we each research and analyze our respective focus area, we will then merge our data to overlay and visualize the different components on one map. In doing so, we will be able to better understand the overlapping and compounding effects of health disparities and their relation to the historic redlining map, our base layer. 

* Dayoung –  finding and analyzing data on asthma rates and hospitalizations, by census tract 
* Quinn – taking deep dive into COVID-19 data to determine what metrics and sources are the best indicator of larger health inequities
* Rachel - finding and analyzing data on poverty rates by census tract; also cleaning and compiling redlining data and shapefiles from the Mapping Inequality project 
* Tommy - researching zoning & analyzing land-use across San Francisco; also responsible for posting and updating the repo on a weekly basis, as needed

### 3. Status update: Report on the general mood of the team, and provide details as to what is working, and what is not.
Upon discussing our project, we are collectively feeling a bit overwhelmed with the amount of data available that could be interesting and applicable to our research question. Additionally, we realized that the boundaries of zip codes and census tracts do not align, which poses a concern because most COVID data available is only available by zip code – whereas other health indicators and our redlining map shapefiles are broken down by census tract. There is also a concern that some of the datasets may not line up exactly in regards to their time frame, but we are planning to address this by pulling data from as similar of sources as possible. Fortunately, what is working is the frequency of our meetings and communication. We think that our group is doing a great job with gathering research and data, sharing information, and keeping each other updated on our findings. 

### 4. Data update: Provide a short narrative on where you are with the data sources you will incorporate in your project. Provide links as necessary.
This week, each member of our group looked into a different data source that provides insight into the lasting effects of redlining on health inequities. Specifically, we analyzed CalEnviroScreen data on poverty and asthma rates, in addition to COVID-19 death rate data from DataSF (the city's open data portal). Lastly, we also looked into San Francisco’s zoning and land use with data also from DataSF. In previous weeks, we pulled more general demographic data from Social Explorer that provided deeper insight on the distribution and trends around income, health insurance, and race across San Francisco. 

### 5. Concerns: There should be a lot to be concerned about at this phase of the project. List those concerns and classify them as "Major concerns" and/or "Minor concerns."
Our current major concerns are as follows:
* The time constraints of individual team members and our collective capacity to do the indepth research, analysis, and coding needed to answer our research question. 
* The potential misalignment of spatial boundaries between data sources (i.e. the changing of census tracts, zip codes versus census tracts, etc.). 
* Finding COVID-19 data that is broken down by census tract, rather than by zip code.
* Visualizing the historic redlining map data, which we must figure out how to align to 2020 census tracts. 
Our current minor concerns are as follows:  
* We’re nervous about bringing our data together and working collaboratively on a single jupyter notebook document because we’ve had troubles in the past with the pushing/pulling workflow in the shared repo.
* We’re nervous about not realizing other challenges or concerns with certain datasets until it’s too close to final deadlines. 


## 221 Group Project Proposal
Group Name: Code & Cry

Group Members: Tommy Chandler, DaYoung Lee, Quinn Haaga, Rachel Kovinsky

### Introduction
Since its inception in the 1930s, the practice of redlining has dictated the quality of life in communities across the country. By labeling certain neighborhoods as “hazardous” and deeming them as less than, redlining maps enabled decades of discrimination, disinvestment, and neglect of primarily non-white communities. Today, the impact of redlining continues to be seen and felt in many U.S. cities – and San Francisco is no exception. 
For our final project, we plan to examine the relationship between historic redlining practices and current health disparities. Specifically, we want to examine the correlation between the areas that were deemed as “hazardous” and the potentially negative health outcomes experienced in those areas today. We will start by looking at asthma rates by census tract, and pose the larger research question: is there a relationship between historically redlined areas in San Francisco and current asthma rates? Further, how has such redlining impacted access to healthcare and hospitals in those areas today? 

If we have the data and capacity, we will also contextualize these health outcomes and potential disparities within the recent COVID-19 pandemic. Given that asthma has been linked to more severe cases of COVID-19, we believe that examining and comparing the rates of COVID deaths across census tracts is another critical health outcome to study in relation to redlining and environmental injustice.   

### Explanation of Importance
This project is important because it has the potential to illuminate environmental and health equity issues in San Francisco that are linked to the lasting effects of redlining. Without question, communities across the country still feel the effects of historic redlining, and this project will allow us to actually visualize some of the consequences associated with this history.

COVID-19 ignited important conversations around the health inequities and injustices that many communities have faced for decades. This project will draw from and contribute to the data and research that has come out of the pandemic by identifying which communities are most vulnerable to diseases, like COVID-19. There will be new health challenges and pandemics in the future, so it is crucial to understand which communities may be most at risk. As planners, it is also vital that we understand how the fields of urban planning and public health can work together to mitigate those negative impacts.  

### Description of Spatial Scope
Our data will focus on the city and county of San Francisco, broken down by census tracts. We will remove the census tract that comprises the Farallon Islands from our spatial scope, due to its lack of permanent residents. We are also considering the possibility of comparing our findings in San Francisco with other cities – depending on data availability and individual bandwidth.

### Description of Data Sources
For our project, we intend to use the following data and sources: 
* Historic redlining map for San Francisco from Mapping Inequality 
* Asthma percentiles and emergency department visits (by census tract) from CalEnviroScreening
* This map/data also includes the location of all hospitals with emergency departments
* COVID deaths by geographic location from DataSF
* Relevant SF census data pulled from Social Explorer 
* Any other data that we find that provides necessary context to the lasting implications of redlining on health disparities and access to care

### Methodology
![Flowchart](https://github.com/tommychandler5/221project/blob/0abcd59f9ce0716ebcb9975c822fd95333f7ef9f/Group%20Assignments/221%20Project%20Proposal%20Methodology%20Flow%20Chart.png)

### Conclusion 
We believe that neighborhoods in the southeast corner of San Francisco are likely the most at risk of experiencing a disproportionately high number of asthma-related emergencies. We hypothesize that this is a result of the decades of discrimination, disinvestment, and neglect that are tied to redlining and racism in the Bay Area and beyond. We plan to explore this data through an environmental justice framework. 
Ultimately, our goal is to visualize and layer the asthma rates (by census tract) onto the redlined areas of San Francisco – and then analyze the relationship between negative health outcomes and historic redlining practices. Additionally, we intend to overlay data about access to healthcare and hospitals to provide deeper insight into the lasting effects of redlining on health inequities and environmental injustice. 

# Data_Vis_D3_Botanic_Garden_1
* The Botanic Garden Plants of Concern (POC) program has monitored about 300 endangered, threatened, and rare species at over 300 sites throughout the US Central Wilderness region.
* Maintains a centralized database of rare plant information.
* Analyses of POC’s datasets yield critical information on rare species’ population trends in relation to management activities on a region-wide basis.
* POC has worked with over 100 public and private landowners. For their participation, these landowners receive critical data that helps them set goals and evaluate land management practices.

TARGET AUDIENCE
--------------
* Our visualizations allow the Botanic Garden, land managers, and volunteers to quickly analyze trends of rare plant populations 

PROJECT PURPOSE
--------------
* The Botanic Garden can use the dashboards to get a high level overview of the species in the program and identify common factors that impact plants across different sites
* Land managers can use the dashboards to compare their plant populations to other sites and species and inform their management planning decisions
* Volunteers can use these visualizations to gain better insight into what to look for when monitoring the plants

Approach & Design Process
--------------
* We have a rich dataset, so we wanted to display our data at different granularities in order to provide insights for ranging audience groups
* We used a bottom up approach and started with descriptive visualizations for each species and geographical location; we then transitioned to a “bird’s eye view” with visualizations that depict overall trends in the data
* We used filters throughout all visualizations to provide users the flexibility to drill down to a granularity and/or dimension of interest

Challenges
--------------
1. Data Challenge
* The dataset we worked with was extremely sparse; there were many missing values for species across different years, making it difficult to to analyze their growth rate. Additionally, many of the variables were ordinal, making it difficult to accurately depict their ordering accurately

2. Design Challenge
* Our target audience consisted of multiple groups: the Chicago Botanic Garden, land managers and volunteers; creating a coherent visualization system which accommodated each group’s needs proved challenging

3. Software Limitations
* The chart types in Tableau are limited and in order to utilize the flexibility of D3, we had to deploy and embed our D3 visualizations to our Tableau dashboard.

Implementation
--------------
1. Graphs/Diagrams:
* Forced Directed Graph
* Network Map
* Population Map
* Hierarchical Edge Bundling
* Bubble Chart
* Scatter Plot
* Bar Chart
* Area Chart

2. Tools: 
* Tableau 
* D3
* Integration between Tableau and D3

3. Filters:
* Location
* Time
* Species
* Threats








## AAL Annual Report, March 2026

### Context
The annual report is released each March during SXSW and it is our Director’s opportunity to be fully transparent on how the year went. The annual report is a massive lift from the various teams at AAL and requires meticulous effort.

As an Operations Specialist I had two main roles:
<li> Help with planning the multi-day event and ensuring coordination across the teams</li>
<li>Use my background in Statistics and Business Analytics to organize our data from various sources, compile and transform the data into meaningful visualizations that tell a story</li>


Prior to my arrival in late September, the Director created whiteboard sketches of the charts and graphs she wanted to see on the annual report. When I saw them in November, I knew I wanted to recreate them in RStudio using fake data. My idea was to have the code prepared ahead of time, that way all I had to do was plug in the correct data after the fact. 

### Sketches vs. Initial Ideas
I went into my first metrics meeting with a presentation of the sketches vs. how they would look using R. I included a comparison of how graphs were done the year prior and how they could be improved. Lastly, I included rationale as to why we should opt to display the data a certain way. The group was ecstatic with my work and I received guidance on how to proceed. 

Over the following weeks, I experimented with different packages and ways of uniquely displaying the data that were still easily comprehensible. I had to find a balance between finding appropriate solutions, achieving the Director’s vision, and making sure the visualizations would align with Communications needs. For instance, the graphs and charts had to be exported in SVG and EPS to display well on the annual report. The team trusted my research and advice regarding best practices. 

### Dataset Work
As stated earlier, I initially used fake data because not all of the data was compiled. Creating and updating datasets was one role I had, one that all data scientists are used to! 

### Graphs
Here are all the types of graphs I made: Choropleth map, scatterplot, boxplot, beeswarm plot, waffle chart, pie chart, gantt chart, violin plot, and bar chart.

The most difficult visualization to create was the Gantt chart because of the requirements. This was made in an effort to be fully transparent with government and industry by displaying all of AAL's various paths that completed projects have taken to transition. I used the Ganntrify package which you can find [here](https://github.com/giocomai/ganttrify). This package was a great starting point, but ultimately didn’t have all the functionality I needed. For instance, it would color a project and it’s subsequent points all the same color. Also, you could only put labels on those later points, not on the actual project itself. This required me to get creative, you can reference the code here(insert Gantt chart link). Lastly, [here](https://aal.mil/assets/files/pdf/aal-performance-report-gantt-chart.pdf) is what the finished chart looked like. Dr. Casey Perley loves to highlight this graphic for multiple reasons. To start off, you can see how much each initial contract was worth, whether there were follow-on contracts, and where the project transitioned to. Not all transitions are created equal, they can go to program offices or labs and centers. In the words of Dr. Casey Perley, "One of the best ways for a company to plot its own journey to high dollar value contracts is to see how other companies have done it." Please note that large dollar value transitions can come after single contracts and also after having multiple million dollar follow on contracts. We also noticed that there can be long gaps between project competion and follow on funds. 43% of the projects had more than a 3 month gap. This is a problem for the army, because there is a delay in getting these capabilities to the warfighter. This is even a problem for the company who may need to move onto different projects. This graph helped show AAL one way they could improve. 

Branding is taken seriously at AAL! I was told to get the visual as close as I could to done and the communications team would finish up so the branding was aligned and looked perfect. If you would like to see the final product in the annual report, please take a look at it [here](https://aal.mil/assets/files/pdf/aal-performance-report-2025.pdf). Below are the visualizations I passed over to the comms team.  

Maybe just show the finished visualizations with a brief description and have links to each individual thing..

### Code after to analyze the SXSW event
During SXSW AAL had open and scheduled office hours. [Here](linkhere) is some code I used to analyze our data. Please keep in mind I cannot reveal the actual results of this event.

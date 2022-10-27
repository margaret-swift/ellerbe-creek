# Ellerbe Creek Cleanup Tutorial

In ecology and watershed sciences, large datasets often come from a variety of sources like continuous automated sensors, water grab samples, and community-collected scientific data. Overcoming these challenges is critical to explore the prevalence, persistence, and impact of degraded water quality on human society and wildlife. This project exposes students to approaches for merging and cleaning two disparate data sources, basic tools for statistical analyses, and data visualization. This project was conducted with funding from Duke University's Data Expeditions Initiative.

## Guiding Questions 
- What are some ways to understand and begin to merge and manipulate disparate environmental datasets? How can we identify the limitations of a merged dataset, particularly when collected by different researchers? 
- How do different measures of water quality vary across time in Ellerbe Creek and how does it vary across space? What are some ways we can visualize these changes? What are the limitations to these findings?  

## The Dataset 
Two datasets will be used for this analysis. The first (“**Duke Synoptic Sampling Data**”) was collected during 3 synoptic sampling events by the Duke Bass Connections team (2021-22) focused on Ellerbe Creek. 34 sites were sampled for ~20 different analytes ranging from major ions, heavy metals, nutrients, and physical characteristics. The second dataset (“**Durham Ambient Sampling Data**”) is sourced from the City of Durham’s ambient water sampling program. The dataset has data for approximately 10 analytes collected on a monthly to biweekly basis over approximately 5 years from 3-6 sites.  

Both datasets include peculiarities that are indicative of the challenges researchers often face when cleaning, wrangling, and analyzing water quality data. For example, in the Durham Ambient Sampling Dataset, sampling is sporadic in certain years (possibly due to funding changes) and certain sites are only sampled for a sub-set of years. Furthermore, in the Duke Synoptic Sampling Dataset, certain analytes are not detected at various sites due to concentrations below what can be detected. In this workshop, we will help students build a data pipeline to select, clean, and wrangle the data to answer questions. For example, students will be encouraged to filter the data to only include analytes, sites, and dates with sufficient data to answer their research question.  
 
## In-Class Exercises 
In this lesson, students will complete a one-hour tutorial in R, broken into five sections. Each section has suggestions for additional lessons throughout, which could be independent class work or ideas for homework.  

In **Section 1: Workflow**, we walk students through downloading datasets and setting up a good data workflow. It is important for students to learn how to structure their files for easy access, not just for other researchers, but for their future selves. 

In **Section 2: “Why R?”**, we briefly cover why R is important, namely for repeatable, reliable analyses and the flexibility gained from the tool’s open-source nature. Students will likely be familiar with using spreadsheet applications like Microsoft Excel for data exploration and analysis, but these tools change raw data and can be dangerous in their lack of replicability. 

In **Section 3: Cleaning Up**, we cover methods for overcoming data-cleaning hurdles, such as duplicate data, missing data, typos, and other errors likely to be encountered.  

In **Section 4: Visualization and Analysis**, students will lead their own investigations into the datasets. First, they learn to summarize data using frequency analysis through histograms, plotting the location and number of site and analytes on a map, and displaying summary boxplots for data variance. Next, we introduce the question of how indicators of water quality (the “analytes”) change in spatially and temporally. Students will select a few data types to analyze more closely, both over a temporal scale (variable Y versus time, e.g. Sodium over time) and compared to other data (variable Y versus variable X, e.g. Sodium vs. Chlorine content). Students will then come up their own conclusions about  

Finally, in **Section 5: Conclusion**, we have students summarize their findings and hypothesize reasons behind the relationships they have uncovered. Finally, we briefly cover statistical tools that could be used to further analyze these data, and propose the question of effort and funding, and why certain contaminants are measured for water quality and the limitations of grab samples.  

## Get Started!
You can view the main tutorial on RPubs here: **https://rpubs.com/margaret-swift/ellerbe**

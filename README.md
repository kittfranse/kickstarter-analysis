# Kickstarting with Excel

## Overview of Project
- The purpose of this analysis is to explore the parameters that should be used in launching a kick starter campaign for a new project

### Purpose
- A client would like to raise money for a theater-based project using Kickstarter, a crowdfunding resource. In order to do so, she was interested in figuring out what conditions lead to the most success for a campaign in her area of interest.

## Analysis and Challenges
- The strategy to answer some of these questions involved a combination of descriptive statistics and subset visualization of pivot table data to better underestand the nature of campaign outcomes for similar projects on the platform.  The main challenge was the limited scope of the data set for particular details inovlivng successful vs unsuccessful campaign.
- logistically, another challenge was balancing filtered and unfiltered data and references to sheets that may be filtered or not. For example, descriptive statistics were run on a Kickstarter data set that was copied from a filtered list on the main data set. When these two sheets were removed for the sake of storage, the descriptive statistics disappeared because the reference sheets were no longer available. Balancing efficiency and storage/file size are still important even with excel and a normal sized data set.

### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
-     It is evident that May is the best time of year to launch a campaign on Kickstarter. This was the peak of the year to year successful campaign line on the Theater_Outcomes_vs_Launch.png chart.
-     Another conclusion that can be drawn is that there is a good amount of variability from year to year on the success rate of a product launched in May, as shown when filtering for year in the graph.

- What can you conclude about the Outcomes based on Goals?
-     the outcomes based on goal chart highlights the lower chance of success of a campaign with an increased goal. There's a steady decline in the success of a campaign if there is a high demand in the goal.  Surprisingly, this actually reverses at the high goals of about 30,000 to 40,000 USD.

- What are some limitations of this dataset?
-   as with any data set, unexplained fluctuations and non-unidirectional trends in data leave the analysis at a loss for explanation.  For example, in the Outcomes based on Goals, what is the significance of the sudden recovery succes rate at higher goals after the initial decline?  These are details that may be explained in other data points missing from the set such as marketing budget, previous campaign succes and subsequent familiarity with the campaign.  Relational data between some of the campaigns could be very telling.

- What are some other possible tables and/or graphs that we could create?
-   We could graph side by side data of how different categories for a particular country perform agianst each other as far as outcomes or even something simple like average donation per backer.  That would be helpful to a client to understand what sorts of campaigns are important for a country.


# An Analysis of Kickstarter Campaigns
## Performing analysis on Kickstarter data to uncover trends
*Includes descriptive statistics
*Analysis of skewness
*Summary statistics of data subsets

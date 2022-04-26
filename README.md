# US Firearm Background Checks
A project for visualizing NICS firearm background check data in the US over the past two decades.

The FBI's National Instant Criminal Background Check System (NICS) is the best proxy the United States has for total gun sales (see sections below for caveats and more details). According to [Amnesty Internationl](https://www.amnesty.org/en/what-we-do/arms-control/gun-violence/), among wealthier, developed countries, the USA stands out for its high level of gun violence. Furthermore, mass shootings in the US are on the rise since they started being tracked in the early 80's, and this again makes the US an outlier among developed nations. In the infographic below, I explore the idea that the United State's gun violence problem could be linked to more guns.

![infograph](https://github.com/lmjacoby/firearm_checks/blob/main/static/firearms_infograph.png)

In this project, I was interested in looking at background check totals between 1999 and 2021, in which the raw number of total background checks increased almost 5-fold. Background checks were broken down by the 4 major geographical regions in the U.S., to gleam greater insight into where most of these background checks were being run.

I included the bar chart below the main graphic to show that on a per capita basis, firearm background checks increased about 3-fold in the same time period. Thus, the increase in total background checks couldn’t be attributed to just population increase.

#### Data and Acknowledgments
The original data in this visualization comes from the [FBI's National Instant Criminal Background Check System.](https://www.fbi.gov/services/cjis/nics)

Buzzfeed News created a scraper that downloads the data, parses it, and produces a spreadsheet/CSV of the data. It was this aggregated data that I used for the visualization, and I give many thanks to the team over Buzzfeed for putting it together. Please check out the work they did with this dataset [here](https://github.com/BuzzFeedNews/nics-firearm-background-checks/), which served as an inspiration for my work.

### Notes on the Data
The statistics reported here represent the number of firearm background checks initiated through the NICS. They do not represent the number of firearms sold. Based on varying state laws and purchase scenarios, **a one-to-one correlation cannot be made between a firearm background check and a firearm sale.**

That being said, **the FBI’s NICS numbers are widely accepted as the best proxy for total gun sales in a given time period.**

Please see the Buzzfeed repo (again, [here](https://github.com/BuzzFeedNews/nics-firearm-background-checks/)) for more detailed information.

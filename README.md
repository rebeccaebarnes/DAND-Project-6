# Explore &amp; Summarize Data
This project was completed as part of the course requirements of Udacity's [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) certification.

## Overview
The project used US Federal Election Commission data for contributions to candidates in the [2016 US Presidential Election](https://classic.fec.gov/disclosurep/PDownload.do) to investigate how contributions could be predicted election results in the bellwether state of Ohio. 

An online version of the report can be found at [my blog](https://rebeccaebarnes.github.io/2018/06/11/making-predictions). 

The project involved data exploration and cleaning, completing Exploratory Data Analysis (EDA) by reviewing statistics and visualizations of data at the univariate, bivariate and multivariate levels, and then building a predictive model. 

### Statistical Analyses
- Examinations of central tendency and spread
- Data visualization of univariate, bivarte and multivariate relationships
- Correlation testing 
- Multiple linear regression testing 
- Model testing

## Technologies Used
- R, R Markdown
- Libraries: ggplot2, scales, plyr, dplyr, GGally, gridExtra, maps, memisc, lattice, MAS, RCurl, bitops
- R studio

## Key Findings
- There is a strong relationship between the total contributions received by a candidate in a county and the corresponding vote count
- The election type to which the contributions were made, the party of the candidate and the county in which the contributions/votes were interacted with the above relationship
- A model was developed that explained approximately 95% of the variance and consistently predicted the candidate that would win the vote count in the county

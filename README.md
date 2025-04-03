# Analysing City of Calgary Crime Rates
Alvin Hui Tsz Chuen, Arshdeep Kaur, David Errington, Judy Kurupakorn Natcha

October 17, 2024

# Introduction
When deciding on where to live, whether you are new to the city or just looking for a new place to call home, it is always worth it to get a sense of the surrounding area. Depending on who you ask, the list of criteria one might have in making this decision may vary from person-to-person. But for many, this list may include aspects such as proximity to one's place of work or school, ease of access to certain amenities (i.e., parks, social/recreational activities, health services, grocery/retail stores, etc.), or the overall safety and security of the area.

For our project, we chose to focus on this third aspect and specifically look at the safety of Calgary's communities by analyzing their crime rates. As many of our classmates are new to the city of Calgary, we felt this topic was very interesting and relevant to all of us who call this place home. In testing our statistical knowledge and applying some of the concepts we learned throughout our studies in DATA 601, we hope this project will shed some light on the subject of Calgary crime rates and provide valuable insights in making better informed decisions.

# Guiding Questions
While exploring the various aspects of our datasets, the first and most obvious question for us to consider is, “How has the overall crime rate in Calgary changed over time?” From there, this can be broken down further into other questions regarding things such as seasonality. That is, whether or not certain months of the year see higher or lower rates of crime as compared to others.

This leads us to the next logical question in our analysis: the correlation between crime rates and unemployment rates over time. Understanding how these two factors interact can provide valuable insights into the broader social context surrounding crime in Calgary.

Following this, we will discuss the effect of the COVID-19 pandemic. Although it is unclear exactly when the global pandemic began, most sources agree that the first cases of the virus appeared in humans in late 2019. By 2020, the SARS-CoV-2 coronavirus was declared a “Public Health Emergency of International Concern” by the World Health Organization (WHO) and was continuing to spread across the globe. While many countries have now since removed any mandatory health restrictions, the effects of the pandemic still remain and creates a clear delineation between the “pre” and “post” eras.

Turning our attention back to Calgary, the final two or three questions stem from Calgary’s communities themselves and the types of crimes that occur within each of them. Specifically, whether certain areas are more at risk than others, whether there are certain types of crimes that occur more or less frequently, and whether or not there might be a correlation between the two. All of these questions are relevant, as they may help to present people with the resources and information to make informed decisions about where they might choose to live.

In summary, our project aims to analyze the following questions and more details on each question can be found in the Analysis section.

1) How has the overall crime rate in Calgary changed over time?

2) How does seasonality affect crime rates?

3) How does the crime rate correlate with unemployment rates over time?

4) How did the Covid-19 pandemic affect crime rates?

5) How are crime rates and crime types distributed across communities?

# Datasets
In this project, our analysis will utilize three datasets, all of which are publicly available from the City of Calgary's Open Data Portal:

Community Crime Dataset, Community Boundaries Dataset, and Unemployment Rates Dataset.

The Community Crime Dataset provided by the Calgary Police Service will be our main dataset. The dataset offers a detailed monthly breakdown of various types of crimes across Calgary’s diverse communities, covering the period from January 2018 to June 2024. It has five columns and over 71,000 rows as of the time of writing this proposal. In total, the dataset covers the crime statistics of 247 communities in Calgary. Each entry in the dataset provides in-depth crime information, including the specific community, crime category, crime count, and the date (year and month) the incident occurred.

The second dataset is the Community Boundaries Dataset, which will allow us to perform crime analysis at the community level. The dataset has 10 columns and 296 rows, containing not only mapping information for communities and quadrants but also the multipolygon records for each community. Such information enables us to perform crime analysis at a fine-grained level.

The last dataset is the Unemployment Rates Dataset. The dataset contains 11 columns and 56 rows, including various economic-related figures, but for our analysis, we will mainly use the Calgary Unemployment Rate column. This information will allow us to investigate the relationship between the unemployment rate and the overall crime rate.

These datasets are well-formed and available through the City of Calgary's Open Data Portal in multiple formats (including CSV, RDF, RSS, TSV, and XML). With additional data cleaning and wrangling, these datasets will enable us to perform an in-depth analysis of crime patterns at both the city and community levels, analyze the relationship between crime rates and unemployment rates, as well as conduct trend analysis over a significant time period.

Lastly, according to the terms of the Open Government License for the City of Calgary, anyone is free to “copy, modify, publish, translate, adapt, distribute, or otherwise use the information in any medium, mode, or format for any lawful purpose” (Open Calgary Terms of Use, 2024).

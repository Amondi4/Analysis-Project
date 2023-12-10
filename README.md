# Microsoft Movie Studio

**Author:** Cynthia Amondi 
***
## Overview

<div style="text-align: justify">This repo aids in the pursuit of establishing a foothold in the competitive landscape of original video content creation. Exploratory Data Analysis has been employed to discern the prevailing trends and successful attributes in the contemporary film industry. The method employed involved scrutinizing extensive datasets related to box office performance, encompassing variables such as genre, runtime, studio affiliations, and production budgets. The insightful findings derived include venturing into the Action, Adventure, Sci-Fi genre, as this genre exhibits notable success at the box office. Secondly, maintaining the movie runtime within the range of 90 to 110 minutes, a duration associated with favorable audience reception. Fostering collaboration with BV Studios, a studio entity evidently linked to prosperous box office outcomes, is highly recommended. Additionally, it is advocated to contemplate a judicious production budget falling in the range of 200 million to 400 million, reflecting a prudent investment strategy aligned with prevalent industry practices.</div>

## Introduction
<div style="text-align: justify">In the ever-evolving landscape of entertainment, Microsoft, a global technology giant renowned for its innovation in software, hardware, and cloud services, has set its sights on venturing into the realm of original video content creation. As an industry leader with a vast portfolio spanning personal computing, gaming, and enterprise solutions, Microsoft is poised to leverage its expertise and resources to join the ranks of major players shaping the future of the film industry. The decision to establish a new movie studio marks a strategic foray into a creative domain where Microsoft seeks to contribute its unique perspective and technological prowess. This ambitious initiative, however, brings forth a challenge – the unfamiliarity with the intricacies of movie production. To address this, Microsoft is engaging in a comprehensive exploration of current trends and successful attributes in the cinematic landscape. The goal is to transform these findings into actionable insights, enabling the head of Microsoft's new movie studio to make informed decisions about the types of films to create, ensuring a successful and impactful entry into the competitive world of original video content.</div>

## Problem Statement
<div style="text-align: justify">As Microsoft embarks on the creation of its new movie studio, the company faces the formidable task of navigating the intricacies of the film industry, an arena vastly different from its core competencies in technology. The challenge lies in deciphering the dynamics of a successful movie in terms of genre, runtime, studio partnerships, and production budgets. Microsoft lacks the inherent knowledge of what types of films currently resonate with audiences and perform exceptionally well at the box office. Therefore, the problem at hand is to conduct an in-depth exploration of the contemporary cinematic landscape, leveraging exploratory data analysis, to identify key trends and patterns. The ultimate aim is to distill these insights into actionable recommendations that will guide Microsoft's strategic decisions in creating original video content.</div>

## Main Objective
<div style="text-align: justify">To empower Microsoft's new movie studio by conducting an in-depth exploration of the contemporary cinematic landscape through exploratory data analysis. The overarching goal is to identify key trends and patterns in successful movies, with a focus on genre, runtime, studio partnerships, and production budgets. The ultimate aim is to distill these insights into actionable recommendations that will guide Microsoft's strategic decisions in creating original video content.</div>

## Specific Objectives

**Explore Genre Dynamics:**

<div style="text-align: justify">Conduct a detailed analysis of the performance of different movie genres at the box office.
Identify genres that consistently resonate with audiences and exhibit strong box office performance.</div>

**Analyze Runtime Preferences:**

<div style="text-align: justify">Investigate the relationship between movie runtime and audience reception.
Determine optimal runtime ranges that correlate with favorable box office outcomes.</div>

**Evaluate Studio Partnerships:**

<div style="text-align: justify">Examine the influence of studio partnerships on the success of movies.
Identify studios with a track record of producing successful films and potential partnerships for Microsoft.</div>

**Assess Production Budget Impact:**

<div style="text-align: justify">Analyze the impact of production budgets on the box office success of movies.
Define a range of production budgets associated with successful films.</div>

**Generate Actionable Recommendations:**

<div style="text-align: justify">Synthesize the findings from the exploratory data analysis into actionable insights.
Provide specific and strategic recommendations for Microsoft's new movie studio based on the identified trends and patterns.</div>

## Notebook Structure

* Reading the data
* Data Preparation and Cleaning
* EDA, Data Analysis and Visualizations
* Future Improvements
* Conclusions
* Recommendations

## Data Understanding

The data used in this project was from: learn-co-curriculum dsc-phase-1-project-v2-4 master zippedData
The im.db dataset is a SQlite Database with eight tables. The bom.movie_gross and tn.movie_budgets are both CSV files and were used in this analysis.

## Methodology

<div style="text-align: justify">The initial dataset, sourced from diverse movie industry repositories, presented inherent inconsistencies, missing values, and diverse formats. The first step involved meticulous cleaning to rectify discrepancies and ensure data uniformity. Genre categories were standardized, and erroneous entries were rectified to establish a consistent classification system. Additionally, runtime data underwent normalization to address variations in units and formats. Addressing missing values in studio partnerships and production budgets required careful imputation based on industry norms and averages. Outliers, indicative of potential data anomalies, were scrutinized and flagged for further investigation. 

The cleaned dataset then underwent exploratory data analysis (EDA), leveraging statistical and visualization techniques to discern underlying trends and patterns. This iterative process of data wrangling and cleaning laid the foundation for actionable insights, empowering Microsoft's new movie studio head with a robust and reliable dataset. The culmination of this effort is a meticulously curated dataset, primed for informing strategic decisions in creating original video content that aligns with market demands, captivates audiences, and elevates Microsoft's prominence in the entertainment industry.</div>

## Future Improvements
* Further investigate periods of high ROI to identify factors contributing to success.
* Analyze fluctuations in worldwide gross to understand the impact of external factors such as market trends or economic conditions.
* Consider exploring the relationship between production budget and ROI to optimize budget allocation.

## Conclusions

* The Action, Adventure, Sci-Fi genre is the most popular and highly appeals to the audience.
* Short movie runtimes ranging between 90 to 110 minutes are most preffered by audience.
*There are specific studios recording great performance at the box office, leading to high earnings.
* There is a strong positive correlation between production budget and ROI. Movies with high production budgets register high overall ROI.

## Recommendations

* Venture into the Action, Adventure, Sci-Fi genre as it exhibits notable success at the box office.
* Keep the movie runtime ralatively short i.e between 90 to 110 minutes, a duration associated with favorable audience reception.
* Sign/ Partner with BV Studios since it registers the best performance at box office and generates the highest total gross earnings in the industry.
* Invest between 200 to 400 million as this is the optimal budget range in order to maximize ROI.  












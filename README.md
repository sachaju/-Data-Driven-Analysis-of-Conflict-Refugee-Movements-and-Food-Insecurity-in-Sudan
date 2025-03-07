# -Data-Driven-Analysis-of-Conflict-Refugee-Movements-and-Food-Insecurity-in-Sudan

# Sudan: Data-Driven Analysis of Conflict, Refugee Movements, and Food Insecurity


Sudan has been severely impacted by escalating conflict, leading to widespread displacement and a surge in refugee flows both within and outside its borders. Ongoing violence has disrupted livelihoods, exacerbating food insecurity in regions already suffering from chronic shortages.


This project provides a comprehensive data-driven analysis of the ongoing conflict in Sudan, its relationship with refugee movements, and the impact on food insecurity. The analysis leverages multiple datasets to understand the evolving situation since the onset of the war in Sudan, which began in 2023. 

The war, marked by escalating violence and widespread displacement, has significantly disrupted life in Sudan, leading to severe humanitarian challenges. Through this project, I aim to demonstrate the power of data in understanding conflict dynamics and informing aid and resource allocation decisions.

## Key Datasets Used
- **ACLED (Armed Conflict Location & Event Data)**: Provides detailed data on the nature and location of political violence and conflict events in Sudan.
- **UNHCR (United Nations High Commissioner for Refugees)**: Offers data on the number of refugees fleeing Sudan and the countries they have sought refuge in.
- **FEWS NET (Famine Early Warning Systems Network)**: Provides data on food insecurity projections and severity in Sudan, offering insights into both pre-war and post-war conditions.

## Project Overview

### 1. Conflict Profiling:
The first phase of the analysis involves evaluating the profile and nature of conflicts in Sudan. Using ACLED data, I tracked the most frequent event types, identified the primary actors involved in the conflict, and mapped the most affected regions by analyzing fatalities.

### 2. Correlation Analysis:
The second phase of the project investigates the relationship between political violence, refugee movements, and food insecurity. By examining the evolution of conflict in Sudan alongside refugee flow data from UNHCR, the analysis reveals a strong positive correlation between political violence and the number of individuals fleeing the country. 

### 3. Food Insecurity Analysis:
The third phase utilizes data from FEWS NET to assess the degree of food insecurity in Sudan. By combining these projections with geographical coordinates of regions in Sudan, I employed `GeoPandas` to track food insecurity patterns before and after the war erupted, providing a better understanding of how the conflict exacerbates food shortages and insecurity.

## Goal of the Project:
The ultimate goal is to utilize data-driven insights to enhance decision-making in conflict zones, support resource allocation, and inform aid efforts for displaced populations and those experiencing food insecurity. The project highlights the value of leveraging data from different sectors—conflict monitoring, refugee data, and food security assessments—to inform humanitarian strategies and improve the efficiency of aid distribution.

## Files Available:
- **Final Report**: The comprehensive analysis and conclusions based on the datasets.
- **Jupyter Notebooks**: Various drafts and analysis files demonstrating the steps involved in the project.


## Conclusion:
This project showcases how data can be leveraged to understand complex conflicts and humanitarian crises. By analyzing the interplay between political violence, refugee movements, and food insecurity, this work provides valuable insights that can help shape informed decisions in conflict zones.

## How to Use:
To replicate or build upon this analysis, clone the repository and open the Jupyter notebooks. The necessary datasets and Python libraries (including GeoPandas, Pandas, and Matplotlib) are specified in the `requirements.txt`.



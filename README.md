<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# The growing issue of e-waste generation
Javier Silva

*Data Analytics Bootcamp, May 2020*

https://public.tableau.com/views/Thegrowingissueofe-waste/e-waste?:display_count=y&:origin=viz_share_link


## Content

- [Project Description](#project-description)
- [Data Sources](#data-sources)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description

What happens with our old electronic devices once we buy new ones? They will either end up buried as landfills for centuries, traded ilegally to developing countries, or simply stored in our drawers, homes, offices, garages and warehouses. Getting rid of electronic/electric waste (e-waste for short) is a growing issue that affects the environment and the society. In this project, I intend to provide key insights about the alarming increase in the generation of e-waste with focus on the European Union.


## Data Sources

Data regarding the e-waste generation in the world is available in The Global E-waste Statistics Partnership website, which objective is to monitor developments of e-waste over time, and to help countries to produce e-waste statistics. 

https://globalewaste.org/

The raw data displayed in the website for the European Union member states was obtained from the Waste over Time repository (Statistics Netherlands) for use in this project.

https://github.com/Statistics-Netherlands/ewaste

The used data includes detailed information for the member states of the European Union on the waste generated over time. Empirical data is available from 1995 to 2016, extrapolated data from 1980 to 1995 and forecasted data from 2017 onwards. 

Moreover, additional data was provided by Kees Baldé (United Nations University). 

Data on the GDP of countries was obtained from the World Bank Database.


## Workflow

1. Define the topic and goal of the project
2. Research about e-waste generation in the world, policies and impact
3. Acquisition of available data on e-waste generation
4. Data cleaning and preparation
5. Data exploration
6. Data visualization
7. Present key insights


## Organization

This repository contains:

* A folder containing all data, divided in two sub-folders: ```raw```, containing the data obtained directly from the sources, and ```clean_data```, containing workable datasets for analysis. 

* A folder containing jupyter notebooks used for data cleaning and wrangling and for analysis:

    1. ```1_electrical_electronic_equipment.ipynb```: loading of data regarding description of e-waste categories
    2. ```2_e_waste.ipynb```: loading and cleaning of data regarding e-waste generation
    3. ```3_gdp_countries```: loading and cleaning of data regarding country information and gdp values
    4. ```4_ewaste_analysis_world```: analysis of e-waste generation in the world
    4. ```4_ewaste_analysis_eu```: analysis of e-waste generation in the European Union

* A folder containing mysql queries used used for data analysis.
    
* A powerpoint presentation summarizing key insights obtained from the analysis.


## Links

[The Global E-waste Statistics Partnership](https://globalewaste.org/)

[GDP](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD)

[GDP per capita](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD)


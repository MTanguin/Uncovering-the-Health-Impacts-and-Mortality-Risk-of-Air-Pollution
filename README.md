
#### "Creating interactive visualization using JavaScript to visualize the health impacts and mortality risk of air pollution in different countries"

CREDITS:
Heidari, Ali | Shahzad, Sameen | Syed, Farman | Tanguin, Marivic 

#### Project-3_Group-13

### "The Health Impacts and Mortality Risk of Air Pollution"


![AirQualityDashboard](https://user-images.githubusercontent.com/114210481/221664041-0066fd05-0402-494c-ab89-2633a06173d4.png)

## Background

In this project, we aim to create a data-driven web application that showcases visualizations and insights derived from a dataset. The dataset contains more than 100 unique records and is stored in a database PostgreSQL. By leveraging the power of Python Flask API, HTML/CSS, JavaScript, and the chosen database, we create an interactive web application that allows users to explore and understand the data through various visualizations.

The study involved analyzing air quality data from different countries as well as mortality rate and disease burden data related to air pollution. We used modeling technique like interactive visualizations to present the spatial distribution of pollutants such as PM25, PM10, and NO2 their ambient concentrations across different countries, quantifying air pollution,burden of disease and mortality rates. These pollutants, in addition to other pollutants vary across the globe and may result in different concentrations of air pollution  country to country.


## Purpose:

The purpose of this study is to investigate the health impacts and mortality risk of air pollution, including ambient household air pollution, ambient particulate matter pollution, ambient ozone pollution, and air pollution caused by solid fuels. By examining exposure to these types of pollution, we aim to gain a better understanding of the risks associated with air pollution and identify potential strategies to mitigate its harmful effects on human health.


## Research Question

What is the severity of air pollution and its impact on disease burden and mortality rates?


## Scope:

The study covered a period of 5 years (2015-2019) and includes data on air quality, mortality rates, and disease burden associated with air pollution from a variety of countries. The focus is on the health impacts and mortality risk associated with exposure to ambient household air pollution, ambient particulate matter pollution, ambient ozone pollution, and air pollution caused by solid fuels.

## Methods

##### Data Collection and Database Setup:

Collected a dataset with a minimum of 100 unique records from reliable sources or through web scraping and API request.
Set up a database system PostgreSQL to store and manage the dataset.

##### Backend Development:

Utilized Python Flask API to develop the backend of the web application.
Created routes and endpoints to handle data requests and retrieve information from the database.
Ensured that the page showcasing data visualizations runs without errors.

##### Frontend Development:

Designed and developed HTML/CSS templates to create an intuitive and visually appealing user interface.
Incorporated JavaScript to enhance interactivity and user-driven interactions on the web page.
Utilized a JavaScript library not covered in class to enhance the visualizations and user experience.

##### Visualization Design:

The web application includes the following visualizations:

1. Leaflet Map: The Leaflet library is used to create an interactive map that displays the spatial distribution of air pollution based on different pollutants (PM2.5, PM10, and NO2) across different countries. The map visualization enhances the understanding of the global variations in air pollution levels.

2. Bar Plots: The Plotly.js library is utilized to create bar plots that showcase the top 10 countries based on pollutant levels. The bar plots provide a visual comparison of pollutant concentrations and allow users to explore data for different years.

3. Radar Chart: The D3.js library is employed to generate a radar chart that depicts the death rates by different types of pollution. This visualization allows for a comprehensive comparison of the impact of various pollution types on mortality rates.

4. Pie Chart: The D3.js library is also used to create a pie chart representing the outdoor pollution rates by age group. This visualization provides an overview of how different age groups are affected by air pollution.

5. Disease Burden and Mortality Bar Charts: The Plotly.js library is used to generate bar charts that compare disease burden and mortality rates attributed to different risk factors with the impact of air pollution. These visualizations aid in understanding the relative contribution of air pollution to overall disease burden and mortality.

The web application incorporates JavaScript libraries like Leaflet, Plotly.js, and D3.js to create interactive and visually appealing visualizations. These visualizations allow users to explore and analyze the dataset, enabling a better understanding of the relationships between air pollution, disease burden, and mortality rates.

## Limitations:

The study is limited by the availability and quality of data, which may vary by country and over time. In addition, the study focuses on selected types of air pollution and does not cover all possible sources of air pollution, such as industrial emissions or transportation-related pollution.

## Conclusions:

Pollutants such as PM2.5, PM10, and NO2 allow scientists to estimate the spatial distribution of their ambient concentrations across different countries, quantifying air pollution,burden of disease and mortality rates. These pollutants, in addition to other pollutants vary across the globe and may result in different concentrations of air pollution from city to city, and country to country.

Based on our analysis, it can be concluded that air pollution is among the top five factors contributing to mortality rates and burden of disease worldwide.

It can be deduced that similar age groups (i.e., under 5, 5-14, 15-49, 50-69, 70 plus) are affected similarly by air pollution in all countries across the globe.

Understanding the severity of air pollution and the burden of disease and mortality rates related to it is important for public health officials, policymakers, and healthcare providers, as it can help them to prioritize resources and develop interventions to reduce the impact of the disease on the population.



Sources:

World Health Organization (WHO)

Links: 

https://www.who.int/data/gho/data/themes/air-pollution/who-air-quality-database

https://www.who.int/teams/environment-climate-change-and-health/air-quality-and-health/health-impacts

https://www.who.int/teams/environment-climate-change-and-health/air-quality-and-health/health-impacts/types-of-pollutants

https://www.who.int/teams/environment-climate-change-and-health/air-quality-and-health/health-impacts/exposure-air-pollution
       


Global Alliance on Health and Pollution (GAHP)  

Link: 

https://gahp.net/wp-content/uploads/2019/12/PollutionandHealthMetrics-final-12_18_2019.pdf



kaggle.com (@article{owidairpollution)

Links: 

https://www.kaggle.com/datasets/programmerrdai/air-pollution?select=death-rates-from-air-pollution.csv

https://www.kaggle.com/datasets/programmerrdai/outdoor-air-pollution?select=PM25-air-pollution.csv




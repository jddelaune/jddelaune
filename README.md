# JD DeLaune - Data Analysis and Visualization

I was a data-head before being a data-head was cool, and have been working with and thinking about the gathering, storing, analysis, and processing of information for much of my career. For a lot of that time I used only basic tools such as Excel and Access. Now that I have branched out to learn Python, Pandas, SQL, MongoDB, and more, the world (of data, at least) is my chocolate bar, since I can't eat oysters.

## Projects
* [Getting Out of the USA: A Python API project with MatPlotLib Visualizations](https://github.com/jddelaune/jddelaune/blob/main/README.md#getting-out-of-the-usa-a-python-api-project-with-matplotlib-visualizations)
* [Pollution Isn't Minnesota Nice: EPA FRS-Monitored Sites vs. Health Outcomes, Asthma Rates, and Cancer Rates by County](https://github.com/jddelaune/jddelaune/blob/main/README.md#pollution-isnt-minnesota-nice-epa-frs-monitored-sites-vs-health-outcomes-asthma-rates-and-cancer-rates-by-county)
* [State and Local Fiscal Recovery Funds (SLFRF) Spending vs. Vaccination Rates](https://github.com/jddelaune/jddelaune/blob/main/README.md#state-and-local-fiscal-recovery-funds-slfrf-spending-vs-vaccination-rates)

### Getting Out of the USA: A Python API project with MatPlotLib Visualizations
![Scatter plot showing the latitude of cities in the northern hemisphere vs. Max Temperature in degrees Fahrenheit on 07-17-2023 with a regression line](https://github.com/jddelaune/jddelaune/assets/102549713/58603241-490a-4716-8c5e-61375a1a5533)

This two-part project uses Python to retrieve data from the OpenWeatherMap and GeoAPIfy APIs. Part 1 finds weather conditions in randomly selected cities around the world and creates MatPlotLib visualizations.  Part 2 selects vacation destinations based on weather conditions and plots them on a map.
* **Tools:** Python, Pandas, MatPlotLib
* **Skills Demonstrated:** Querying APIs, ETL, data analysis using linear regression, data visualization
* **Links:**
  * [Project Overview](https://github.com/jddelaune/python-api-challenge)
  * [Part 1 Jupyter Notebook](https://github.com/jddelaune/python-api-challenge/blob/main/WeatherPy.ipynb)
  * [Part 2 Jupyter Notebook](https://github.com/jddelaune/python-api-challenge/blob/main/VacationPy.ipynb)

### Pollution Isn't Minnesota Nice: EPA FRS-Monitored Sites vs. Health Outcomes, Asthma Rates, and Cancer Rates by County

This project is a full-stack web application developed in collaboration with four other people that examines the relationship between the presence and concentration of EPA Facility Registry Service (FRS)-monitored sites in Minnesota and health outcome and health factor scores in each county, as well as asthma and cancer rates by county.
![image](https://github.com/jddelaune/jddelaune/assets/102549713/614c8472-53e3-4811-9cd4-a603fea64848)

#### My Role
My part of the project was to write a Flask API that acquired data from our Mongo database and provided it in JSON and geoJSON format. I also took the lead on ensuring we prepared a robust and informative README file, worked with other project members to develop the research project design and methodology, and assisted with data cleaning and sourcing.

* **Tools:** Python, Flask, Pandas, MongoDB, JavaScript, Leaflet, Plotly, Turf
* **Skills Demonstrated:** API development, research project design, collaborative project management, clear communication of findings
* **Links:**
  * [Project Overview](https://github.com/rolisingh10/Project-3/blob/main/README.md)
  * [Flask API Code](https://github.com/rolisingh10/Project-3/blob/main/Step_3_pimn_api.py)
  * [GitHub Pages Website Deployment](https://rolisingh10.github.io/Project-3/) (please note the website may take a few seconds to load depending on your internet connection) 

### State and Local Fiscal Recovery Funds (SLFRF) Spending vs. Vaccination Rates
The American Rescue Plan Act of 2021 (ARPA) allocated $350 billion to state and local governments to mitigate the impacts of the COVID-19 public health emergency by funding a broad range of programs. By the end of Q4 2022, some states (and their local governments) had used almost all the money available to them. Other states had neither spent nor obligated the vast majority of the money available for their use.

This project is a data analysis undertaken with four other people to discover whether states where this SLFRF money was spent on programs to improve the vaccine uptake for residents had higher rates of vaccination.

We compared both the **amount of money spent** on vaccine-related projects and the **number of vaccine-related projects** to the vaccination rate in each state, using publicly available vaccination data from the CDC. Data on SLFRF spending was compiled by Dave Kamper of the Economic Policy Institute.

![Scatter Plot showing Administered Doses of COVID vaccine by population percentage vs. Count of Vaccine Projects Funded with SLFRF Money](https://github.com/jddelaune/jddelaune/assets/102549713/49d7b9d4-0135-4b58-8286-4ff16bc57f6d)

#### My Role
I located the datasets we used and took the lead on designing our research question and methodology, with assistance from Kendal and Greg. I read the documentation for our datasets to find the key datapoints we needed, did exploratory data analysis on vaccination rates, provided explanations and answered questions for colleagues about the data, and assisted with ETL.

* **Tools:** Python, Pandas, MatPlotLib
* **Skills Demonstrated:** ETL, research project design, data analysis, collaborative project management
* **Links:**
   <!-- * Project Overview -->
   * [Code - Jupyter Notebook](https://github.com/jddelaune/SLFRF-COVID-Vaccinations/blob/main/Project_1_covid_final.ipynb)
   * [PowerPoint with Visualizations and Results](https://github.com/jddelaune/SLFRF-COVID-Vaccinations/blob/main/Group_7_Presentation.pptx)

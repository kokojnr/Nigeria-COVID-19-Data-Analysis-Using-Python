# Nigeria-COVID-19-Data-Analysis-Using-Python
Data Scientist Microdegree Capstone Project

COVID-19 has significantly impacted Nigeria across various domains. The health sector faced challenges with increased strain on resources and infrastructure, leading to a notable rise in confirmed cases and affecting the overall well-being of the population. The economic landscape experienced disruptions in trade, supply chains, and various sectors, resulting in job losses, income reductions, and economic challenges.  
The project involves collecting, cleaning, analyzing, and visualizing data related to the COVID-19 pandemic. 

# Steps:
# Data Collection:
Scraped covid data from https://covid19.ncdc.gov.ng/ or alternatively wikipedia: https://en.wikipedia.org/wiki/COVID-19_pandemic_in_Nigeria using beautiful soup, downloaded Human Development Index data from https://globaldatalab.org/shdi/table/shdi/NGA/, loaded external datasets provided, imported daily cases data from John Hopkins Data Repository(https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)

#  Data Cleaning and Preprocessing:

Converted columns to appropriate data type.
Renamed the columns of the scraped data.
Removed comma(,) in numerical data
Extracted daily data for Nigeria from the Global daily cases

# Exploratory Data Analysis (EDA):

Conduct exploratory data analysis to understand the basic statistics plotting top 10 states in terms of cases, deaths, and recoveries.
Daily Infection Rate, 
Visualized trends over time, total daily confirmed, recovered, and death cases, Daily infection rate over time.
Identify patterns, correlations between confirmed cases, health system, Overall CCVI index, Epidemiological
Analyzed COVID-19 data based on demographic factors such as gender, socioeconomic status.
Explore the impact of easing of lockdown on daily confirmed cases

# Statistical Analysis:
Conducted statistical tests to assess the significance of relationships. Using regression plot with factors such as Overall CCVI Index,
Health System, Epidemiological to investigate significance of relationships.

# Improvement Plans
COVID-19 data is dynamic and constantly evolving. Consider setting up automated data retrieval and updating processes to keep the analysis current.
Budget data breakdown for healthcare, transportation and socio-economic programs.


This repository contains my Data Visualization projects that I used to learn visualization tools and techniques using the following libraries:

![Pandas](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/pandas.png "Pandas")

![Matplotlib](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/matplot.png "Matplotlib")

![Seaborn](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/seaborn.jpeg "Seabron")



# [World Health Organization (WHO) Coronavirus (COVID-19) Dataset](https://github.com/kennyfahad/Data-Visualization/blob/main/WHO%20Coronavirus%20(COVID-19).ipynb)
Coronavirus disease (COVID-19) is an infectious disease caused by the SARS-CoV-2 virus.
Most people who fall sick with COVID-19 will experience mild to moderate symptoms and recover without special treatment. However, some will become seriously ill and require medical attention.


#### HOW IT SPREADS
The virus can spread from an infected person’s mouth or nose in small liquid particles when they cough, sneeze, speak, sing or breathe. These particles range from larger respiratory droplets to smaller aerosols.
You can be infected by breathing in the virus if you are near someone who has COVID-19, or by touching a contaminated surface and then your eyes, nose or mouth. The virus spreads more easily indoors and in crowded settings.

Consult your local medical authority for advice.
[For more information visit WHO](https://www.who.int/news-room/questions-and-answers/item/coronavirus-disease-covid-19-how-is-it-transmitted)

## About the Dataset
The dataset contains information about countries who reported COVID-19 cases and deaths from January 2020 till date. Following information is provided by WHO in this dataset:
Date_reported	Country_code	Country	WHO_region	New_cases	Cumulative_cases	New_deaths	Cumulative_deaths

Information that I was able to extract is as follows:
![Cumulative Cases](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/covid_globalcases.png "Cumulative Cases")
![Cumulative Deaths](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/covid_globaldeaths.png "Cumulative Deaths")
![Share of Deaths in Top 10](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/covid_pie.png "Share of Deaths in Top 10")


## An Interactive Dashboard
The notebook also contains an interactive dashboard which shows COVID-19 Deaths and Cases in each country selected from a drop down list. 
![Interactive1](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/interact1.png "Interactive Dashboard")
![Interactive2](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/interact2.png "Interactive Dashboard")

# [EDA with Data Visualization - Car Crashes Dataset](https://github.com/kennyfahad/Data-Visualization/blob/main/EDA%20with%20Data%20Visualization%20-%20Car%20Crashes%20Dataset%20(Seaborn).ipynb)


## About the Notebook

This notebook analyzes various features of Seaborn Library for Data Visulaization using Car Crashes data. The data consists of the following variables:

'total', 'speeding', 'alcohol', 'not_distracted', 'no_previous', 'ins_premium', 'ins_losses', 'abbrev'

Following information/ visuals are included in the notebook:
* States and No. of drivers involved in fatal collisions per billion miles
* States and Percentage Of Drivers Involved In Fatal Collisions Who Were Alcohol-Impaired
* Highest percentage of drivers involved in fatal collisions who were alcohol-impaired
* Highest number of drivers involved in fatal collisions per billion miles 
* Percentage of incidents which involved alcohol in total number of drivers involved in fatal collisions per billion miles
* Highest Correlation of total incidents with other attributes
* Effect of percentage of drivers involved in fatal collisions who were not distracted 
* Effect of alcohol in the fatal collisions and drivers with no previous accidents

## Final Visuals

![Car Crashes](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/crashes.png "Car Crashes")
![Car Crashes Alcohol](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/carcrashes.png "Car Crashes Alcohol")


# [Analyzing Wine Quality - UC Irvine Dataset](https://github.com/kennyfahad/Data-Visualization/blob/main/Analyzing%20Wine%20Quality%20-%20UC%20Irvine%20Dataset.ipynb)

## About Dataset

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. Following are the Input variables (based on physicochemical tests):
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol
Output variable (based on sensory data):
12. quality (score between 0 and 10)

[Source](https://archive.ics.uci.edu/ml/datasets/wine+quality)

## Visualization

My analysis of correlation of wine quality with physicochemical tests starts from finding the correlation to the final visual which presents correltaion values between wine quality and wine properties from the tests. The notebook will explain all the steps that I have taken to come to the conclusion.

## Final Visual

![Wine](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/wine.png "Wine")


# [CO2 Emissions - The World Bank Open Data](https://github.com/kennyfahad/Data-Visualization/blob/main/CO2%20Emissions%20-%20The%20World%20Bank%20Open%20Data.ipynb)

Carbon dioxide emissions are those stemming from the burning of fossil fuels and the manufacture of cement. They include carbon dioxide produced during consumption of solid, liquid, and gas fuels and gas flaring. The World Bank's CO2 Emissions dataset provides year-wise CO2 emissions per metric ton per capita of each country.

The dataset is cleaned and organized in order to create an excel file which will be later used to develop an animated bar chart showing CO2 emissions of top 10 countries over a period of 20 year i.e. 1990 - 2019. 

[Click here for more information](https://data.worldbank.org/indicator/EN.ATM.CO2E.PC?most_recent_value_desc=true&view=chart) 

Following steps were involved:

1. Loading dataset from **The World Bank Open Data** for CO2 Emissions
2. Wrangling dataset to bring to the required format using **Pansds**
3. Webscraping flags of countries to include in the animated visual using **BeautifulSoup**
4. Saving image files in .png format using **Bulk Rename Utility**
5. Running the python code using **sjvisualizer** 
6. USing **OBS Studio** and **ClipsChamp** for video recording and editing

I used [sjvisulaizer](https://github.com/SjoerdTilmans/sjvisualizer) by [SjoerdTilmans](https://github.com/SjoerdTilmans) to create an animated visual.

[Click Here for `.py` file](https://github.com/kennyfahad/Data-Visualization/blob/main/CO2Emissions.py)


## Final Visual

![Final Output](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/co2Emissions.gif "Final Output")

[Link to MP4](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/co2Emissions.mp4)


# [Pakistan's Worker's Remittance - State Bank of Pakistan - EasyData](https://github.com/kennyfahad/Data-Visualization/blob/main/Pakistan's%20Worker's%20Remittance%20-%20State%20Bank%20of%20Pakistan%20-%20EasyData.ipynb)

## About Dataset

State Bank of Pakistan's Easy Data portal was launched in June 2022 and currently hosts economic and financial time series data on more than 7,000 variables neatly grouped into around 100 datasets.

[SBP EasyData](https://easydata.sbp.org.pk/apex/f?p=10:1:0:)

The Country-wise Workers' Remittances dataset contains details of countries, and monthly amount of USD in millions received by Pakistan as workers' remittances. 

[Remittance Dataset](https://easydata.sbp.org.pk/apex/fp=10:211:::NO:RP:P211_DATASET_TYPE_CODE,P211_PAGE_ID:TS_GP_BOP_WR_M,250&cs=157866335180CD2B7910AF42D3E4C3C43)

## Final Visual

I used [sjvisulaizer](https://github.com/SjoerdTilmans/sjvisualizer) by [SjoerdTilmans](https://github.com/SjoerdTilmans) to create an animated visual.

[Click Here for `.py` file](https://github.com/kennyfahad/Data-Visualization/blob/main/PakWorkersRemittance.py)

![Pakistan Workers' Remittance](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/PakWorkersRemittance.gif "Pakistan Workers' Remittance")

[Link to MP4](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/PakWorkersRemittance.mp4)

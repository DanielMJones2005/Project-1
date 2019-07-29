# U.S. Energy Consumption and CO2 Emissions
  
## Motivation

As energy consumption has grown over the years, the impacts to the environment has grown significantly as well. Through this analysis, we wanted to get a better understanding of the relationship between energy consumption and the carbon dioxide emissions for various sectors and states as reported by the EIA.
  
## Data
Source data is available through the EIA open data API

[CO2 Emissions by State - All Fuels](https://www.eia.gov/opendata/qb.php?category=2251663)

[CO2 Emissions by Sector](https://www.eia.gov/opendata/qb.php?category=711236)

[Energy Consumption by Sector](https://www.eia.gov/opendata/qb.php?category=711226)
    
## Definitions
The EIA provides 4 different sectors for energy consumption and emissions – Industrial, Transportation, Residential and Commercial. 

•	Industrial represents facilities and equipment used for manufacturing, agriculture, mining and construction.

•	Transportation includes vehicles to transport people or goods such as cars, trucks, buses, motorcycles, trains, aircraft, boats, barges, and ships.

•	Residential includes homes and apartments.

•	Commercial sector includes offices, malls, stores, schools, hospitals, hotels, warehouses, restaurants and places of worship and public assembly.

There is a fifth sector for electric power which we did not include in the analysis as this electric sector consumes primary energy to generate most of the electricity the other four sectors consume. 
  
## Preparation
You will need: Python, Pandas, Requests, Numpy, Matplotlib, [EIA API key](https://www.eia.gov/opendata/register.php), and Plotly

plotly.py may be installed using pip...

`$ pip install plotly==4.0.0`

or conda.

`$ conda install -c plotly plotly=4.0.0`

## Findings
The full write up of findings can be found [here](https://github.com/DanielMJones2005/Project-1/blob/master/US%20Energy%20Consumption%20and%20CO2%20Emissions%20Write%20Up%20Final.docx)

A Presentation for this project can be found [here](https://github.com/DanielMJones2005/Project-1/blob/master/20190729%20Energizers_Project_1_Presentation.v2.pptx)

## Authors
  
#### • Oswald Vinueza

#### • Daniel Jones

#### • Shahzad Naseer

# NYC 311 Service Requests Ingestion & EDA 

## Project Content
- 'data' - This folder contains cached raw NYC 311 Service Requests data as well as the cached clean data. The NYC population by zipcode data (sourced from https://data.census.gov/) also locates there.

- 'images' - Visualizations used in the summary section of 02_eda.ipynb

- '01_data_ingestion.ipynb' - Data ingestion notebook

- '02_eda.ipynb' - EDA notebook

- env.json - Socrata API token

- README.md - Project instruction

- 'requirements.txt' - Packages needed for the project


## Setup Instruction

1. Clone this repo by running git clone https://github.com/sxue-r-b/project-nyc-311-service-requests.git in the terminal

2. Install required packages by running pip install -r requirements.txt

3. Get a Socrata API token from [here](https://data.cityofnewyork.us/profile/edit/developer_settings) and store it in env.json

4. Run the '01_data_ingestion.ipynb' notebook to cache the required data

5. Run the '02_eda.ipynb' notebook to see the data exploratory analyses 

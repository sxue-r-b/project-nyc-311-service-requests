# NYC 311 Service Requests Ingestion & EDA 

## Project Deescription

This project ingests NYC 311 Service Requests data from the [NYC Open Data](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data) website and caches it locally in the `data` folder for reuse. Service requests submitted from January 2020 through July 19, 2025 were collected and stored in monthly Parquet files.

Following ingestion, an exploratory data analysis was conducted to uncover trends, including complaint seasonality, resolution times, and compliant volume across boroughs, time of day, and days of the week. 


## Project Content
- `data` - This folder contains cached raw NYC 311 Service Requests data as well as the cached clean data. The NYC population by zipcode data (sourced from https://data.census.gov/) also locates there.

- `images` - Visualizations used in the summary section of `02_eda.ipynb`

- `01_data_ingestion.ipynb` - Data ingestion notebook

- `02_eda.ipynb` - EDA notebook

- `env.json` - Socrata API token

- `README.md` - Project instruction

- `requirements.txt` - Packages needed for the project


## Setup Instruction

1. Clone this repo by running `git clone https://github.com/sxue-r-b/project-nyc-311-service-requests.git` in the terminal

2. Install required packages by running `pip install -r requirements.txt`

3. Get a Socrata API token from [here](https://data.cityofnewyork.us/profile/edit/developer_settings) and store it in `env.json`

4. Run the `01_data_ingestion.ipynb` notebook to cache the required data

5. Run the `02_eda.ipynb` notebook to see the data exploratory analyses 


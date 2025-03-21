![Black Money](https://github.com/RichaKumari225/Black_Money_Analysis/blob/0fa83d976c3c3f81ca9b302dc07a27cfec242916/Black_money.png)

 ## Try Dashboard

Try the app, for different examples. 

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://blackmoneyanalysis.streamlit.app/)

# Black Money Analysis

The Black Money Dashboard is an interactive and robust analytical tool designed to monitor and detect fraudulent financial activities associated with black money. By leveraging data analysis and visualization techniques, the dashboard provides insights into suspicious transactions, fraud patterns, and crime classifications. The tool serves as a resource for enhancing transparency in financial transactions, aiding regulatory compliance, and assisting law enforcement agencies in combating financial crimes.


## Features

- Interactive Visualizations: Explore various charts and graphs that depict trends and patterns in black money transactions.
- User-Friendly Interface: Simple navigation allows users to access different functionalities easily.
- Data Filtering: Users can filter data based on specific criteria to focus on relevant information.
- Downloadable Reports: Generate and download comprehensive reports for further analysis.
## Tech Stack


**Programming Languages and Frameworks :** Python , Streamlit

**Data Analysis and Visualization Libraries :** Pandas, Matplotlib, Seaborn

**Other Tools and Technologies :** Jupyter Notebook, VS Code

## Directory Structure
``` plain text
Black_Money_Analysis / 
├── README.md             
├── main.py               
├── charts.py              
├── preprocessor.py 
├── requirements.txt        
├── data / 
│   ├── black_money.csv 
│   ├── ml_tag.csv      
│   ├── ml.csv         
│   └── merged_data.csv      
├── notebooks / 
│   └── Black_money_EDA.ipynb   
├── images /                 
│   ├── Black money2.png 
│   ├── Black money3.png 
│   └── undefined-imgur.gif 
```

## Project Files

[1. Main.py](https://github.com/RichaKumari225/Black_Money_Analysis/blob/master/charts.py)
- Sets up the Streamlit app.
- Configures filters for data exploration.
- Integrates multiple visualizations.

[2. charty.py](https://github.com/RichaKumari225/Black_Money_Analysis/blob/master/charts.py)
- Contains functions for generating various plots using Matplotlib and Seaborn.
- Includes:
  - Line charts
  - Bar charts
  - Pie charts
  - Heatmaps
  - Histograms

[3. Preprocessor.py](https://github.com/RichaKumari225/Black_Money_Analysis/blob/master/preprocess.py)
- Contains data preprocessing functions for cleaning and transforming the dataset.
  
[4. Black_money_EDA](https://github.com/RichaKumari225/Black_Money_Analysis/blob/master/Black_money_EDA.ipynb)
- Jupyter Notebook for exploratory data analysis (EDA).
- Provides insights into the dataset and prepares it for visualization.

## Prerequisites

Before running the dashboard, ensure you have the following installed:
- Python 3.x
- Required Libraries:
   - streamlit
   - pandas
   - matplotlib
   - seaborn

## Quickstart

``` python
import streamlit as st
import pandas as pd
import preprocess

from charts import (
   plot_daily_transactions,
   plot_fraud_analysis,
   plot_distribution_of_transaction_amounts,
   plot_fraud_type_analysis,
   plot_heatmap,
   plot_crime_level_trends
)
# Load your data
data = pd.read_csv("merged_data.csv")

# Set up your Streamlit page configuration
#Adjusting the tab image and name
st.set_page_config(page_icon='Black_money.png', page_title='Black Money Dashboard', layout='wide')

```
## Video Walkthrough of the project

![Black Money demo](https://github.com/RichaKumari225/Black_Money_Analysis/blob/master/Screenshots/undefined%20-%20Imgur.gif)

## Installation

1. Clone the Repository
```bash
  git clone https://github.com/RichaKumari225/Black_Money_Analysis.git
cd Black_Money_Analysis

```
2. Install Required Libraries
Create a requirements.txt file if not already present, and include all necessary libraries. Install them using:
```bash
pip install -r requirements.txt
```
3. Run the Dashboard
Start the Streamlit application by running:
```bash
streamlit run app.py
```
Open your web browser and navigate to http://localhost:8501 to view the dashboard.

## Usage Instructions
- Navigating the Dashboard: Use the sidebar to select different analysis options.
- Interacting with Visuals: Click on charts for detailed views or to filter data.
- Generating Reports: Use the report generation feature to download analyses in various formats.

## Screenshots

![Fraud analysis](https://github.com/RichaKumari225/Black_Money_Analysis/blob/master/Screenshots/Black%20money2.png)
![Types of fraud](https://github.com/RichaKumari225/Black_Money_Analysis/blob/master/Screenshots/Blackmoney3.png)




## Contributors

- [@Richa Kumari](https://www.linkedin.com/in/richa-kumari-213891215)
- [@Anand Nair](https://linkedin.com/in/anandnair99)
- [@V. N. Nikhilesh Yadapaka](https://linkedin.com/in/v-n-nikhilesh-yadapaka-1ab422237)

## Footer
- Developed by Team Data Disruptors_007 to enhance financial transparency .

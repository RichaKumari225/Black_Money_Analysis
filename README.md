

# Black Money Analysis

The Black Money Dashboard is an interactive and robust analytical tool designed to monitor and detect fraudulent financial activities associated with black money. By leveraging data analysis and visualization techniques, the dashboard provides insights into suspicious transactions, fraud patterns, and crime classifications. The tool serves as a resource for enhancing transparency in financial transactions, aiding regulatory compliance, and assisting law enforcement agencies in combating financial crimes.


## Features

- Interactive Visualizations: Explore various charts and graphs that depict trends and patterns in black money transactions.
- User-Friendly Interface: Simple navigation allows users to access different functionalities easily.
- Data Filtering: Users can filter data based on specific criteria to focus on relevant information.
- Downloadable Reports: Generate and download comprehensive reports for further analysis.
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



## Contributors

- [@Richa Kumari](https://www.linkedin.com/in/richa-kumari-213891215)
- [@Anand Nair](https://linkedin.com/in/anandnair99)
- [@V. N. Nikhilesh Yadapaka](https://linkedin.com/in/v-n-nikhilesh-yadapaka-1ab422237)

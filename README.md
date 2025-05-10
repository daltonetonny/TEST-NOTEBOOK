# COVID-19 Global Data Tracker

This repository contains a Jupyter Notebook project that analyzes global COVID-19 trends, using data from reliable sources like Johns Hopkins University (JHU) and Our World in Data (OWID). The project covers various aspects such as case numbers, deaths, recoveries, and vaccination data. This tracker includes exploratory data analysis, visualizations, and key insights, focusing on countries and their pandemic responses.

## Key Features
- **Data Collection**: The dataset includes global COVID-19 case statistics (confirmed, deaths, and recoveries) from JHU, and vaccination data from OWID.
- **Data Cleaning and Preprocessing**: Reshaping the data for better analysis and handling missing values to ensure accuracy.
- **Visualizations**: Various plots, including time series for total cases, deaths, daily new cases, and vaccination trends. All visualizations are saved as PNG files and interactive choropleth maps.
- **Insights Report**: A markdown file that summarizes key findings from the data analysis.
- **Downloadable Data**: A merged CSV file containing processed global COVID-19 data.

## Technologies Used
- Python (Pandas, Matplotlib, Seaborn, Plotly)
- Jupyter Notebook

## Project Structure
- `data/`: Processed data files, including `covid_combined_data.csv`.
- `visualizations/`: Contains saved images of charts and maps (`.png`, `.html`).
- `docs/`: A markdown report (`covid_insights.md`) summarizing key insights.

## Installation

To run the notebook locally, follow these steps:

1. Clone this repository:
   ```bash
  (https://github.com/daltonetonny/COVID19 TRACKR/)

  
  
    

    

Navigate into the project directory:

bash
Copy
Edit
cd covid-19-tracker

  
  
    

    

Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt

  
  
    

    

Run the notebook:

bash
Copy
Edit
jupyter notebook COVID-19_Global_Data_Tracker.ipynb

  
  
    

    

How to Use
Data Input: The data is loaded directly from publicly available CSV files hosted on GitHub.

Country Selection: By default, the project analyzes data for countries like Kenya, the United States, and India. You can change this list by entering country names when prompted.

Visualizations: The notebook generates line charts, bar charts, and a choropleth map. These visualizations are saved in the visualizations/ folder.

Insights & Results
This notebook offers in-depth insights on:

Global Case Trends: Visualizing the rise and fall of COVID-19 cases across various countries.

Vaccination Rates: Comparing vaccination progress over time.

Death Rates and Case Fatality: Analyzing the impact of the virus and how different countries are affected.

Example Analysis:
Kenya shows a slower rate of infection and a relatively lower death rate compared to the United States.

India has a higher number of cases, but vaccination efforts have significantly mitigated the spread in 2022.

The choropleth map provides a global overview of the most affected areas, with notable hotspots in North America and Europe.

Contributions
Feel free to fork and contribute to this repository by submitting issues or pull requests. Contributions are welcome to further improve the analysis or add additional features!

Created by Daltone Tonny

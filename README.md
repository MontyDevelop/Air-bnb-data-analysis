# Airbnb Data Analysis

This repository provides an in-depth exploratory data analysis (EDA) of Airbnb listings, aiming to derive insights about pricing, availability, and listing distribution across neighborhoods and room types.

## Project Overview

The notebook focuses on answering key questions such as:

- What is the distribution of Airbnb listing prices?
- Which room types are most commonly listed?
- Which neighborhoods have the highest number of listings?
- Are there correlations between features like number of reviews and availability?
- How does location impact listing density and pricing?

## Dataset

The data used in this project is sourced from [Inside Airbnb](https://insideairbnb.com/get-the-data), a platform that offers downloadable, publicly available Airbnb data for cities worldwide.  
To replicate this project, download a dataset for your city of interest and ensure the CSV file is located in the same directory as the notebook.

## Key Findings

- **Room Types**: Most listings are for entire homes/apartments, followed by private rooms.
- **Prices**: The majority of listings are priced under \$200; extreme outliers were removed for better visualization.
- **Neighborhood Trends**: Certain neighborhoods dominate in listing volume and price concentration.
- **Correlations**: Listings with more reviews are generally more frequently available.
- **Geospatial Insights**: Heatmaps reveal clusters of high activity and pricing in central neighborhoods.

## Analysis Steps

The notebook `Air_bnb_analysis.ipynb` walks through the following stages:

1. **Data Import and Inspection**  
   - Loading data using `pandas`  
   - Basic structure and summary

2. **Data Cleaning**  
   - Handling missing values  
   - Filtering outliers and unrealistic prices

3. **Exploratory Analysis and Visualization**  
   - Price distribution (histograms and boxplots)  
   - Room types and neighborhood bar plots  
   - Correlation heatmaps  
   - Geographic plotting (latitude/longitude)

## Technologies Used

- Python 3.x  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn

## Getting Started

Follow these steps to run the analysis locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/airbnb-data-analysis.git

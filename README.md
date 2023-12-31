![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)

# Barcelona Rent and Noise Analysis

## Project Overview
This project conducts a thorough exploratory data analysis of the interconnection between rental prices and noise levels across different neighborhoods in Barcelona. Leveraging a combination of datasets from CSV files and the Ajuntament de Barcelona Open Data Portal, we visualize patterns, perform principal component analysis, and derive insights into the urban landscape's influence on living expenses.

<p align="center">
	<img src="https://a.cdn-hotels.com/gdcs/production81/d1983/1441d9b5-d0e6-4230-9923-646d58ba66d8.jpg" alt="200" width="400"/>
</p>

## Highlights
- **Data Wrangling**: Using helper functions to consume API data and process CSV files.
- **Preprocessing**: Handling missing values, converting percentages to floats, and eliminating irrelevant data.
- **Data Fusion**: Merging rental and noise level datasets for in-depth analysis.
- **Visual Insights**: Generating plots to visualize noise distribution and its relationship with rent prices.
- **PCA**: Executing Principal Component Analysis to understand data structure and variance.
- **Future Directions**: Outlining subsequent steps to enhance our analysis.

## Insights

The visual representation below illustrates the correlation between average rental prices and mean noise levels within a specific district, delineated by neighborhoods. For an in-depth exploration and understanding of this relationship, I invite you to delve into the accompanying Jupyter notebook in this repo!

<p align="center">
	<img src="https://raw.githubusercontent.com/pablo-git8/Barcelona-EDA-Rent-Noise/main/images/avg_noise_vs_price.png" alt="400" width="600"/>
</p>


## Technologies Used
- **Python**: For all data ingestion, processing, and exploratory data analysis.
- **Pandas**: Employed for data manipulation and analysis.
- **Matplotlib & Seaborn**: Utilized for creating insightful visualizations.
- **Scikit-learn**: Specifically, PCA for dimensionality reduction and StandardScaler for feature standardization.

## Data Sources
- **CSV Files**: Structured data files for initial dataset included in the repository.
- **[Open Data Portal (Ajuntament de Barcelona)](https://opendata-ajuntament.barcelona.cat/data/es/dataset)**: API endpoints providing real-time access to urban data.

## Setup and Installation
Ensure you have Python installed on your system. You can then install the required libraries using:


pip install `pandas` `matplotlib` `seaborn` `scikit-learn` `requests`


## Usage
To run the analysis, simply open the main Jupyter Notebook provided in the repository.

## Acknowledgements
Special thanks to Ajuntament de Barcelona for making their data publicly accessible and facilitating this research.

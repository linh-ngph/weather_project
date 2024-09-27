**Crop Growth Analysis in India Based on Climatic Conditions**

This project explores the relationships between climatic factors and agricultural production in India, utilizing data spanning from 2002 to 2023. By analyzing weather data and agricultural patterns, the project aims to uncover insights that can guide more sustainable and efficient agricultural practices.

**Project Overview**

Objective: To analyze the impact of climatic conditions on crop growth in India using APIs and data cleaning techniques.
Study Period: 1960 - 2020.

**Methods Used in the Project**

1. APIs
Sources:
NASA POWER, providing solar and meteorological datasets.
Data.gov.in, offering open government data for India's agricultural and weather information.
Purpose: Extracted extensive weather data (temperature, precipitation, humidity, etc.) relevant to crop growth across various regions in India.

3. Data Handling with NumPy
Usage: NumPy was employed to perform efficient numerical operations on the large datasets, enabling quick computations and data structuring.

5. Data Cleaning and Manipulation
Libraries: Pandas was used for data cleaning, manipulation, and restructuring.

6.Operations:
Data was cleaned to remove inconsistencies, missing values, and irrelevant information.
Pivoted and transformed the datasets into usable formats for analysis.

7. Data Visualization
Library: Matplotlib was used to create visualizations that effectively represent trends, correlations, and predictions.
Types of Visuals: Line plots, heatmaps, scatter plots, and bar charts to communicate insights clearly.

**Key Findings**

The exploratory data analysis (EDA) indicates that climatic variables such as temperature and rainfall show noticeable patterns and correlations with crop yields during critical growth periods. However, further analysis and modeling are required to quantify these relationships and make accurate predictions.

**How to Run the Project**

Clone this repository.
Install the necessary libraries:pip install pandas scikit-learn matplotlib
Use the following APIs to fetch the dataset:
NASA POWER API: Retrieve climate data by making API calls to NASA POWER:
URL:https://power.larc.nasa.gov/api/temporal/{endpoint}?parameters={parameters}&community=AG&start={start}&end={end}&latitude={lat}&longitude={lon}&format=JSON
data.gov.in API: Access Indian governmental datasets via the data.gov.in API:
URL:"https://api.data.gov.in/resource/9b73ba9e-228c-4ab9-bffd-5f8df367634b?api-key=579b464db66ec23bdd000001cdd3946e44ce4aad7209ff7b23ac571b&format=json&offset=0&limit=200"

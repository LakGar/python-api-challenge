# Python API Challenge: Weather Analysis & Vacation Planning

## Overview
This project uses **Python, APIs, and Data Visualization** techniques to analyze global weather patterns and identify ideal vacation destinations. The analysis is divided into two parts:

1. **WeatherPy**: Analyzing the relationship between latitude and various weather parameters.
2. **VacationPy**: Identifying ideal vacation spots based on weather conditions and locating nearby hotels.

## Part 1: WeatherPy
- Uses the **OpenWeatherMap API** to retrieve weather data for 500+ cities.
- Generates scatter plots to visualize relationships between latitude and:
  - **Temperature**
  - **Humidity**
  - **Cloudiness**
  - **Wind Speed**
- Computes **linear regression** for the Northern and Southern Hemispheres.
- Interprets findings based on correlation between latitude and weather.

## Part 2: VacationPy
- Uses the **Geoapify API** to locate hotels near ideal vacation destinations.
- Filters cities based on user-defined weather conditions (temperature, wind speed, cloudiness).
- Visualizes **humidity levels** on a map using `geoViews`.
- Displays hotel locations on an interactive map with **hover details**.

## Files
- `WeatherPy.ipynb` - Jupyter Notebook for weather analysis.
- `VacationPy.ipynb` - Jupyter Notebook for vacation planning.
- `api_keys.py` - Contains API keys (excluded via `.gitignore`).
- `README.md` - Project documentation.

## Tools Used
- **Python** (Pandas, NumPy, SciPy)
- **APIs** (OpenWeatherMap, Geoapify)
- **Matplotlib & Seaborn** (Data visualization)
- **geoViews & hvPlot** (Interactive maps)
- **Jupyter Notebook**

## Submission
- All files are uploaded to the **python-api-challenge** GitHub repository.

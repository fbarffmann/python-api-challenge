# Python API Challenge

This project demonstrates API access, data cleaning, analysis, and visualization using Python. The challenge was divided into two parts: analyzing weather data across global cities and visualizing vacation data based on weather preferences.

---

## Project Overview

### Part 1: WeatherPy

Collected and analyzed weather data from 500+ cities using OpenWeatherMap API.

#### Analysis Included:
- Temperature (Max)
- Humidity
- Cloudiness
- Wind Speed
- Geolocation (Latitude vs Weather Metrics)

#### Deliverables:
- API call automation to retrieve weather data
- Cleaned and transformed data into structured DataFrames
- Visualized relationships between latitude and weather conditions
- Exported data and visualizations for reporting

---

### Part 2: VacationPy

Leveraged weather data to identify ideal vacation destinations based on:
- Preferred temperature ranges
- Low humidity
- Clear weather conditions

#### Deliverables:
- Used Google Places API to locate hotels near ideal cities
- Visualized results on heatmaps and marker layers using Jupyter Notebooks and Matplotlib Basemap
- Created dynamic visualizations for client-ready deliverables

---

## Tools & Technologies Used

- Python 3.x
- Jupyter Notebooks
- Pandas
- Matplotlib
- OpenWeatherMap API
- Google Places API
- Requests Library
- CSV File Handling
- API Key Management
- Data Visualization

---

## File Structure

```text
WeatherPy/
├── WeatherPy.ipynb - API access, weather data analysis, visualizations
├── VacationPy.ipynb - Hotel search and vacation mapping
├── api_keys.py - API key storage (excluded from GitHub)
├── output_data/
│   ├── cities.csv - Cleaned weather data
│   ├── Fig1.png - Latitude vs Max Temp
│   ├── Fig2.png - Latitude vs Humidity
│   ├── Fig3.png - Latitude vs Cloudiness
│   └── Fig4.png - Latitude vs Wind Speed
```

---

## Skills Demonstrated

- Accessing and using public APIs
- Automating data collection
- Data cleaning and transformation with Pandas
- Visualizing geographic data trends
- Using Python to generate client-friendly reports
- Handling API keys securely
- Mapping data visually for business storytelling

---

## Key Takeaways

- Developed a repeatable process for data extraction from APIs.
- Learned how to clean and organize real-world messy API data.
- Used Python visualizations to support business-relevant recommendations.
- Strengthened skills in automating data analysis pipelines.

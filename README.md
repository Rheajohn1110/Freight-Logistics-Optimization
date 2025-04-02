# Freight-Logistics-Optimization
This project aims to optimize outbound shipping logistics for Allagash Brewery using advanced data analytics, machine learning, and business intelligence tools. It focuses on minimizing freight costs, improving truck utilization, consolidating shipments, and optimizing weather-based scheduling.


# Tools and Technologies Used
Python (Jupyter Notebooks)

Machine Learning Models: Random Forest, XGBoost, SARIMA

Power BI

APIs: Google Maps API, Open-Meteo API

# File Descriptions

## 1. Jupyter Notebooks
ALY6980 Data Prep 20250308.ipynb
Prepares and cleans logistics data for downstream analysis. Performs exploratory data analysis (EDA) and outputs structured datasets used in modeling and dashboard development.

ALY6980 waypoints 20250226.ipynb
Uses the Google Maps API to collect waypoint and route data. Helps in evaluating route distances and optimizing travel paths for freight shipments.

ALY6980 Polylines 20250305.ipynb
Processes geospatial data to generate route polylines. These polylines are later integrated into Power BI for route visualization.

ALY6980 weather forecast 20250324.ipynb
Retrieves 14-day weather forecasts using the Open-Meteo API. Supports weather-based scheduling by identifying optimal shipping windows, especially for temperature-sensitive deliveries.

6980 SARIMA model.ipynb
Implements the SARIMA time series model to forecast shipment volumes. The predictions assist in proactive scheduling and resource allocation.

## 2. Power BI Dashboards
weather forecast 20250324.pbix
Interactive dashboard that visualizes 14-day weather forecasts. Designed to support shipping decisions based on weather suitability and minimize refrigeration costs.

Nearby Customers 20250324.pbix
Dashboard that clusters customers by geographic proximity. Enables shipment consolidation strategies and improves truck utilization across routes.

# Project Outcomes
- Identified over $2,600 in potential cost savings per shipping lane through predictive modeling.

- Enabled consistent trailer utilization above 80 percent by consolidating nearby customer deliveries.

- Developed real-time dashboards for freight planning, weather-based scheduling, and route efficiency monitoring.

- Provided actionable insights using data analytics and machine learning, leading to improved cost efficiency and operational decision-making.

# Instructions for Use
- Start with the Data Prep notebook to clean and structure the data.

- Proceed with the Waypoints and Polylines notebooks to generate route-based information.

- Use the Weather Forecast notebook to collect weather data for the next 14 days.

- Apply the SARIMA model notebook to forecast shipment volumes.

Load the cleaned and enriched data into the Power BI dashboards for interactive analysis and presentation.




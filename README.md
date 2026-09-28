# 🌤️ Python Weather 7-Day Forecast

A Python application that fetches historical weather data for the past 7 days and visualizes temperature trends with charts and CSV exports.

## 📋 Project Overview

This project retrieves weather data for a specified location (currently configured for Dehradun) using the Open-Meteo free weather API, processes the data using Pandas, and generates visualizations with Matplotlib. The data is also exported to CSV format for further analysis.

## ✨ Features

- **Weather Data Retrieval**: Fetches 7-day historical weather data using the Open-Meteo API
- **Temperature Analysis**: Tracks maximum and minimum daily temperatures
- **Data Visualization**: Creates line charts showing temperature trends over the week
- **Data Export**: Saves weather data to CSV format for analysis
- **Automatic Directory Management**: Creates a `data` folder for organized file storage

## 📊 What It Does

1. Calculates the date range for the past 7 days
2. Fetches weather data from the Open-Meteo API for Dehradun (30.3165°N, 78.0322°E)
3. Extracts daily maximum and minimum temperatures
4. Creates a Pandas DataFrame for structured data handling
5. Generates a visualization with dual-line chart (max and min temperatures)
6. Saves the weather chart as `weather_chart.png`
7. Exports data to CSV file: `data/paris_weather.csv`

## 🛠️ Installation

### Prerequisites
- Python 3.6 or higher
- pip (Python package manager)

### Dependencies

Install required packages:

```bash
pip install -r requirement.txt

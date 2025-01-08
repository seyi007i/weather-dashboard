## Weather collection dashboard

### Project Overview

This project is a Weather Data Collection System that demonstrates core DevOps principles by combining:

        External API Integration (OpenWeather API)
        Cloud Storage (AWS S3)
        Infrastructure as Code
        Version Control (Git)
        Python Development
        Error Handling
        Environment Management


### Features

        Fetches real-time weather data for multiple cities
        Displays temperature (°F), humidity, and weather conditions
        Automatically stores weather data in AWS S3
        Supports multiple cities tracking
        Timestamps all data for historical tracking

### Technical Architecture

        Language: Python 3.x
        Cloud Provider: AWS (S3)
        External API: OpenWeather API
        Dependencies:
        boto3 (AWS SDK)
        python-dotenv
        requests
    
Store api key, s3 bucket name in the .env
echo "AWS_BUCKET_NAME=weather-dashboard-${RANDOM}"  >> .env
echo "OPENWEATHER_API_KEY=f1............654"  >> .env

run the program with python src/weather_dashboard.py


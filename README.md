# The-Weather-Report-Workflow🌦️
Built an AI-powered weather assistant using n8n that integrates Open-Meteo APIs and OpenAI to deliver real-time weather insights, personalized recommendations, and automated alerts via email

## 🚀 Overview

An intelligent weather automation system built using n8n that fetches real-time weather data and generates AI-powered insights and recommendations.

## 🔧 Tech Stack

* n8n (workflow automation)
* Open-Meteo API (weather data)
* OpenAI API (AI insights)
* Gmail (notifications)

## 🔄 Workflow

1. User chooses city (Bengaluru,Mumbai,Chicago,London)
2. Geocoding API fetches coordinates(Open-Meteo)
3. Weather API returns real-time data
4. OpenAI generates insights
5. Notification sent to user

## 📸 Screenshots

<img width="1779" height="863" alt="image" src="https://github.com/user-attachments/assets/15012b9b-42e9-4ac5-ae1a-820eaf6c096a" />


## 📦 Setup Instructions

1. Import `n8n-workflow.json` into n8n
2. Add API keys (OpenAI)
3. Configure email node
4. Run workflow

## 🎯 Use Cases

* Personal weather assistant
* Automated daily alerts
* AI-powered notification system

---

⭐ If you like this project, give it a star!

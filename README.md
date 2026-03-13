# Air Quality & Weather Notifications

A collection of iOS Shortcuts for monitoring air quality, weather conditions, and pollen levels with automated notifications and alerts.

## Overview

This repository contains Apple Shortcuts that help you stay informed about environmental conditions affecting your daily life. Get timely notifications about air quality, weather forecasts, and pollen counts for your location.

## Features

### 📊 Air Quality Monitoring
- **5-Day AQI Forecast**: Displays a 5-day air quality forecast notification for London using DEFRA data
- **AQI Alerts**: Displays a notification when air quality reaches moderate or worse levels (AQI 4+) for your current location

### 🌤️ Weather Updates
- **Daily Weather Forecast**: Displays a daily weather forecast notification

### 🌾 Pollen Tracking
- **Real-Time Pollen Count**: Displays real-time pollen count notifications for your configured location

### ☂️ Smart Reminders
- **Umbrella Reminder**: Displays a notification and voice reminder to bring an umbrella when leaving home, triggered by NFC tag proximity (e.g., wallet or phone)

## Installation

1. Download the desired `.shortcut` files from this repository
2. Open the files on your iOS device
3. Follow the prompts to add them to your Shortcuts app
4. Configure location settings and API URLs as needed (see Configuration section)

## Configuration

### AQI Alerts
- Update with your current location in the shortcut settings

### Real-Time Pollen Count
- Configure the API URL from [Open Meteo](https://open-meteo.com/) in the next action
- Set your location coordinates in the API URL

### Umbrella Reminder
- Set your home location in the second action
- Pair with an NFC tag (place on wallet, keys, or near your door)
- Create an Automation in iOS Shortcuts to trigger when the NFC tag is detected

## Data Sources

- **DEFRA**: UK Department for Environment, Food and Rural Affairs (Air Quality data for London)
- **Open Meteo**: Open-source weather and environmental data API
- **Apple Weather**: Built-in iOS weather service

## Requirements

- iOS 14.0 or later
- Shortcuts app (pre-installed on iOS)
- Location permissions for location-based alerts
- NFC-capable iPhone for umbrella reminder (iPhone 7 or later)

## Privacy

All shortcuts run locally on your device. Location data and API requests are processed directly without third-party tracking.

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.

## License

MIT License - feel free to use and modify these shortcuts for personal or commercial use.

## Acknowledgments

- DEFRA for providing UK air quality data
- Open Meteo for free weather and pollen APIs
- Apple for the Shortcuts platform

---

**Note**: These shortcuts are provided as-is. Air quality and weather data accuracy depends on the external data sources used.
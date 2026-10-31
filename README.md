# Location-Based Weather Announcement System

## Project Description
This project is developed as part of the Natural Language Processing (NLP) course.

The Location-Based Weather Announcement System retrieves current weather information based on the location entered by the user and announces the weather in both English and Telugu using Text-to-Speech technology.

## Features
- Accepts a city or location from the user.
- Retrieves current weather information.
- Displays temperature, humidity, wind speed and weather conditions.
- Generates weather announcements in English.
- Generates weather announcements in Telugu.
- Converts text into speech using Google Text-to-Speech.

## Technologies Used
- Python
- Jupyter Notebook
- Open-Meteo Weather API
- Requests
- gTTS (Google Text-to-Speech)
- Pygame

## Main Functions
1. `get_weather()` – Retrieves weather information and returns it as a string.
2. `text_to_speech()` – Converts the given text into speech.
3. `weather_announcement()` – Integrates both functions to generate bilingual weather announcements.

## Installation

Install the required libraries:

```bash
pip install requests gTTS pygame
```

## Execution
1. Open the Jupyter Notebook.
2. Execute all cells in order.
3. Enter the required city name.
4. View the weather report in English and Telugu.
5. Listen to the generated audio announcements.

## Developed For
Natural Language Processing (NLP) Course Practical.

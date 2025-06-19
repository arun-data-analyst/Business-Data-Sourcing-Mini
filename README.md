# Weather Data Sourcing and Visualization

This mini project demonstrates how to fetch real-time weather data using the OpenWeatherMap API, clean it using Python, and visualize it using line and bar charts.

## Features
- Fetch current weather for selected cities
- Handle rate limits and errors gracefully
- Secure API key management with `.env`
- Generate line plot (temperature) and bar chart (humidity)

## Tools Used
- Python
- `requests`
- `pandas`
- `matplotlib`
- `python-dotenv`
- OpenWeatherMap API

## Setup Instructions
1. Clone the repo:
   ```
   git clone https://github.com/arun-data-analyst/business-data-sourcing.git
   cd business-data-sourcing
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Create a `.env` file:
   ```
   OPENWEATHERMAP_API_KEY=your_actual_key_here
   ```

4. Run the notebook or Python script.

## Output Samples
- `lineplot.png`: City vs Temperature
- `barchart.png`: City vs Humidity

> 🚫 No API key is shared in this repo. Please use your own OpenWeatherMap key.

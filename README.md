# Weather Data Sourcing & Visualisation

This mini‑project demonstrates how to fetch real‑time weather data from the **OpenWeatherMap API**, clean it with Python and visualise it using line and bar charts.  It’s a concise example of API integration, data wrangling and basic plotting.

## 🌧️ Features

- Fetch current weather for a list of cities via the OpenWeatherMap REST API.
- Handle **rate limits** and API errors gracefully.
- Manage API keys securely using a `.env` file (do **not** hard‑code keys in your code).
- Produce a **line chart** of temperature by city and a **bar chart** of humidity.

## 🧮‍♀️ Tools Used

- Python & Jupyter Notebook
- `requests` for HTTP requests
- `pandas` for data cleaning
- `matplotlib` for visualisation
- `python-dotenv` for environment variables

## 💀 Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/arun-data-analyst/Business-Data-Sourcing-Mini.git
cd Business-Data-Sourcing-Mini
```

> **Note:** The previous clone command referred to a non‑existent `business-data-sourcing` repo; this has been corrected.

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file with your API key:

```bash
OPENWEATHERMAP_API_KEY=your_actual_key_here
```

4. Run the Jupyter Notebook or Python script to fetch data and generate plots.

## 📊 Output Samples

The project generates two simple charts saved in the repository:

- `lineplot.png` – Temperature by city (line chart)
- `barchart.png` – Humidity by city (bar chart)

You can view them directly in this repo or open them after running the code.

## 📄 License & Notes

This project does not include an API key; you must supply your own.  Consider signing up for a free account at [OpenWeatherMap](https://openweathermap.org/).  Add a license file (MIT or similar) if you intend others to reuse or modify this code.

## 👤 Author

**Arun Acharya** – *Data Analyst*

---

*Have questions or suggestions? Open an issue or connect with me on [LinkedIn](https://www.linkedin.com/in/arun-acharya-26077a362).*

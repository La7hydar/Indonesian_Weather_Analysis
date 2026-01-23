# 🌦️ Indonesian Weather Analysis & Visualization

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![API](https://img.shields.io/badge/API-OpenWeatherMap-orange?style=for-the-badge)

## 📌 Project Overview
This project performs a comprehensive meteorological analysis of key cities across Indonesia. By leveraging weather APIs and Python's data visualization libraries, we analyze patterns in temperature, humidity, wind speed, and atmospheric pressure.

The goal is to compare climate conditions between major metropolitan areas (like Jakarta & Surabaya) and specific regional focuses (like Ponorogo & Baubau) to derive insights regarding urban heat islands and coastal weather patterns.

## 📍 Locations Analyzed
The analysis focuses on a diverse set of Indonesian locations, ranging from bustling capitals to regional hubs:
* **Jakarta** (Capital City)
* **Bekasi** (Industrial Satellite City)
* **Surabaya** (Major Port City)
* **Makassar** (Eastern Hub/Coastal)
* **Baubau** (Island/Maritime Climate)
* **Ponorogo** (Inland/Highland Influence)

## 📊 Key Features
* **Multi-City Comparison:** Side-by-side comparison of current weather metrics.
* **Wind Speed Analysis:** Analysis of wind gusts and directions to understand regional airflow patterns.
* **Correlation Heatmaps:** Investigating relationships between humidity, temperature, and cloud coverage.
* **Condition Distribution:** Visualizing the frequency of weather conditions (e.g., "Patchy Rain", "Clear Sky", "Overcast").
* **Forecast Modeling:** Short-term trend analysis for temperature and precipitation probability.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Collection:** `requests` (OpenWeatherMap API / Visual Crossing API)
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`, `plotly` (for interactive maps)

## 📈 Methodology
1.  **Data Extraction:** Fetching real-time and historical weather data via API calls for the selected coordinates.
2.  **Data Cleaning:** Handling timestamps (UTC to WIB/WITA conversions) and missing values.
3.  **Exploratory Data Analysis (EDA):**
    * *Temperature Trends:* Comparing daily highs and lows.
    * *Wind Analysis:* Visualizing wind speed variance between coastal (Makassar/Baubau) and inland (Ponorogo) cities.
4.  **Visualization:** Generating dashboards (Bar Charts, Line Graphs, and Heatmaps).

## 💡 Sample Insights
* **Urban Heat:** Jakarta and Bekasi consistently show higher average temperatures compared to Ponorogo, likely due to the *Urban Heat Island* effect.
* **Coastal Winds:** Baubau and Makassar exhibit higher average wind speeds compared to inland cities.
* **Humidity Levels:** Ponorogo maintains a more stable humidity level compared to the fluctuating levels in Surabaya.

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/indonesian-weather-analysis.git](https://github.com/your-username/indonesian-weather-analysis.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Setup API Key:**
    * Create a `.env` file.
    * Add your API key: `WEATHER_API_KEY=your_api_key_here`
4.  **Run the analysis script:**
    ```bash
    python weather_analysis.py
    ```

## 📂 Project Structure
├── data/ # Raw and processed CSV data ├── notebooks/ # Jupyter Notebooks for EDA ├── src/ # Source code for data fetching ├── plots/ # Generated charts and graphs ├── README.md # Project documentation └── requirements.txt # Python dependencies

## 🤝 Contributing
Contributions are welcome! If you have data for other Indonesian cities, feel free to open a Pull Request.

## 📜 License
This project is licensed under the MIT License.

# 🚲 Bike Sharing Data Analysis

## 📌 Project Description
This project analyzes bike sharing data from the Capital Bikeshare system in Washington D.C. (2011–2012), exploring how environmental conditions, seasonality, and time influence bike rental demand. By performing exploratory data analysis (EDA) and visualizing trends, this project reveals insights into usage patterns across different weather conditions, hours of the day, weekdays versus weekends, and seasonal changes.

The dataset serves as a virtual sensor network capturing detailed ridership behavior, which provides valuable insights for urban mobility planning and transportation analytics. :contentReference[oaicite:0]{index=0}

---

## 📊 Dataset

The bike sharing dataset comes from the Capital Bikeshare system and includes hourly and daily aggregated records of bike rentals. The data is publicly available and commonly used for research on transportation demand modeling and time-series analysis.

Dataset source: [Kaggle – Bike Sharing Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset)

**Data Files Used**
- `hour.csv`: Hourly aggregated rental counts
- `day.csv`: Daily aggregated rental counts

Each record includes weather information, temporal features, and user counts.

---

## 🧾 Feature Summary

- **Instant / Date** – Record identifiers and timestamps
- **Season / Month / Year / Hour** – Time & seasonal variables
- **Holiday / Weekday / Workingday** – Calendar indicators
- **Weather situation** – Weather conditions encoded numerically
- **Temperature, Feel-Like Temp, Humidity, Windspeed** – Normalized environmental measures
- **Casual / Registered** – Count of casual vs registered users
- **Total Count (`cnt`)** – Total rentals per period

---

## 🛠️ Tools & Technologies

The project primarily uses:

- Python  
- Jupyter Notebook  
- pandas & NumPy for data manipulation  
- Matplotlib & Seaborn for visualizations

---

## 📈 Key Insights

- **Temporal Trends:** Rental counts vary throughout the day, with distinct peak hours.
- **Weekday vs Weekend:** Patterns differ between working days and weekends, reflecting commuter vs leisure usage.
- **Seasonality:** Rental behavior changes with seasons; warmer months show higher usage.
- **Weather Influence:** Favorable weather conditions correlate with higher rental demand.

---

## 📂 Repository Structure
```bash
bike-sharing/
│
├── data/
│   ├── hour.csv
│   └── day.csv
│
├── notebooks/
│   └── bike_sharing_analysis.ipynb
│
├── README.md
└── .gitignore
```

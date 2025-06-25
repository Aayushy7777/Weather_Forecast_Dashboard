
# 🌦️ Weather Forecast Dashboard using Power BI & WeatherAPI.com

Welcome to the **Weather Forecast Dashboard** project!  
This interactive dashboard is built in **Power BI** and uses real-time weather data fetched via the **WeatherAPI.com** service. It visualizes current weather conditions like temperature, humidity, wind speed, and more — all dynamically refreshed based on user-selected locations.

---

## 🚀 Features

✅ Real-time weather updates via [WeatherAPI.com](https://www.weatherapi.com/)  
✅ Dynamic visuals for temperature, humidity, wind speed, and forecast  
✅ API integration through Power BI's Power Query  
✅ User-controlled city selection  
✅ Interactive KPI cards and weather visuals  
✅ Refreshable, customizable design

---

## 🛠️ Tech Stack

| Tool        | Description                                  |
|-------------|----------------------------------------------|
| ⚡ Power BI  | Data visualization and reporting             |
| 🌐 WeatherAPI.com | Real-time weather data via API           |
| 🔍 Power Query | API data ingestion and transformation      |
| 📈 DAX       | Metrics, KPIs, and calculated values         |

---

## 🔄 How It Works

1. 🔑 **Get your API key**
   - Sign up at [WeatherAPI.com](https://www.weatherapi.com/login.aspx)
   - Go to your dashboard and copy your free API key

2. 🌐 **Connect via Power Query**
   - Use Web connector in Power BI
   - Enter URL:  
     ```
     https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=CityName
     ```
   - Replace `YOUR_API_KEY` and `CityName` with dynamic input or parameters

3. 🛠️ **Data Transformation**
   - Parse JSON response to extract required fields (e.g., temp_c, humidity, wind_kph)
   - Transform to table format for visualization

4. 📊 **Build Visuals**
   - Add cards, charts, and slicers for weather attributes
   - Use DAX to calculate daily averages, max/min, etc.

---

## 📷 Screenshots

> *(Add dashboard images here)*  
> ![Screenshot Example](Screenshots/dashboard.png)

---

## 📁 Folder Structure

```
Weather_Forecast_Dashboard/
├── Weather_Dashboard.pbix         # Power BI Report File
├── README.md                      # Project Documentation
└── Screenshots/                   # Dashboard Images (Optional)
```

---

## 🌐 API Reference

- API Provider: [WeatherAPI.com](https://www.weatherapi.com/docs/)
- Endpoint used: `/current.json`
- Sample URL:  
  ```
  https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=London
  ```

---

## ✍️ Author

**Aayush Yadav**  
📍 Mumbai, Maharashtra, India  
🔗 [LinkedIn](https://www.linkedin.com/in/aayush-yadav2004)  
📧 [aayu.sh7021@gmail.com](mailto:aayu.sh7021@gmail.com)

---

## 📌 Future Enhancements

- 📍 Add support for multiple cities  
- 📅 Include hourly or 3-day forecasts  
- 🌡️ Create weather alert banners  
- 📲 Publish report to Power BI Service

---

## 📜 License

This project is licensed under the MIT License.

> ⭐ Star this repo if you find it useful!  
> 🛠️ Contributions and feedback are always welcome!

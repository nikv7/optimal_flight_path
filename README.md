
# ✈️ Flight Path Estimation and Visualization Tool

A **Python-based mini project** that calculates and visualizes the flight path between two airports using real-time API data, geographical calculations, and an interactive map.

---

## 📌 Project Overview

This tool estimates basic flight route metrics including:

- Great-circle distance between airports
- Estimated flight time
- Estimated fuel consumption
- Interactive HTML map with plotted flight path and airport info

It uses **user input** (origin, destination IATA codes and aircraft type), fetches data from **Aviationstack API**, and utilizes **Folium** for map visualization.

---

## 🧰 Tech Stack

- **Language:** Python 3.x  
- **Libraries:**
  - `requests` - API calls
  - `geopy` - Distance calculation
  - `folium` - Map generation
  - `json` - API error handling
  - `webbrowser` - Opens generated map
- **Data Source:** Aviationstack API  
- **Development:** Jupyter Notebook

---

## ⚙️ Features

- Fetches airport coordinates using real IATA codes
- Calculates great-circle distance using `geopy`
- Estimates flight time and fuel burn based on aircraft performance
- Generates an interactive HTML map with flight path
- Console-based user interaction

---

## 🧪 How It Works

1. **User Input:** Origin and destination IATA codes, aircraft type.
2. **API Call:** Retrieves coordinates and airport info from Aviationstack.
3. **Distance Calculation:** Computes great-circle distance between points.
4. **Estimation:** Uses predefined aircraft performance to calculate time and fuel.
5. **Visualization:** Generates and opens an interactive HTML map with markers and path.

---

## 🚀 Supported Aircraft

```python
AIRCRAFT_PERFORMANCE = {
    'A320': {'cruise_speed_kmh': 830, 'fuel_burn_kgh': 2500},
    'B737': {'cruise_speed_kmh': 830, 'fuel_burn_kgh': 2750}
}
```

---

## 🖥️ Sample Output

- Console output includes:
  - Fetched airport details
  - Distance (km)
  - Estimated time (hrs)
  - Estimated fuel (kg)
- Auto-opened HTML map with origin and destination markers and a flight path line

---

## 📌 Code Entry Point

```python
if __name__ == "__main__":
    # Prompts for IATA codes and aircraft type
    # Fetches data and calculates distance
    # Estimates time and fuel
    # Generates and opens flight map
```

---

## 📷 Screenshots

> _(Add your own screenshots here showing console output and generated HTML map.)_

---

## 📚 Future Enhancements

- Add more aircraft types and dynamic performance data
- Include wind and weather effects
- Improve UI (e.g., web-based input)
- Export results to CSV or PDF
- Incorporate real flight paths

---

## 👥 Team Members

- Abinandhan P - `RA2311004010380`
- Dhilip Raj T - `RA2311004010384`
- Nikhil V - `RA2311004010387`

---

## 🏁 Conclusion

This project is a practical application of Python's geospatial and visualization capabilities, suitable for education and basic flight estimation purposes. It lays the groundwork for future enhancements in aviation data analytics.

---

## 🔗 License

This project is for educational purposes and follows the academic guidelines of SRM Institute of Science and Technology.

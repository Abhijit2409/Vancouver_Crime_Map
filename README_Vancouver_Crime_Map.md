
# Vancouver Crime Data Analysis & Visualization  

This project analyzes crime data from the City of Vancouver and creates an **interactive crime map** to identify patterns, hotspots, and trends across neighborhoods.  

---

## 🚀 Features  
- **Data Cleaning & Preprocessing**: Handles missing values, renames columns, and formats dates.  
- **Exploratory Data Analysis (EDA)**: Generates descriptive statistics and visualizations for crime counts, types, and distributions.  
- **Geospatial Visualization**: Creates **interactive maps** showing crime density across Vancouver using geographic coordinates.  
- **Trend Analysis**: Provides time-series plots for crime incidents across months or years.  
- **Hotspot Mapping**: Uses heatmaps to highlight high-crime areas.  

---

## 🛠️ Tools & Technologies  
- **Python** – Core programming language  
- **Pandas** – Data manipulation & analysis  
- **NumPy** – Numerical computations  
- **Matplotlib / Seaborn** – Static data visualizations  
- **Folium / Plotly** – Interactive maps & plots  
- **Jupyter Notebook** – For code, analysis, and visualization  

---

## ⚙️ Workflow Overview  
1. **Load Data** – Import crime dataset (CSV/Excel).  
2. **Data Cleaning** – Handle missing values, remove duplicates, standardize column names.  
3. **EDA** – Explore distributions of crime types, locations, and timestamps.  
4. **Visualization** –  
   - Time-series plots for crime trends  
   - Bar plots for crime categories  
   - Interactive map with crime hotspots  
5. **Insights** – Identify high-crime zones and seasonal patterns.  

---

## 📂 Project Structure  
```
Vancouver_Crime_Map/
│-- Vancouver_Crime_Map.ipynb   # Jupyter Notebook with analysis & visualizations
│-- README.md                   # Project documentation
│-- data/                       # (Optional) Crime dataset files
```

---

## 📋 Prerequisites  
- Python 3.8+  
- Jupyter Notebook  
- Required Python libraries:  
  ```bash
  pip install pandas numpy matplotlib seaborn folium plotly
  ```

---

## ▶️ How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Vancouver_Crime_Map.git
   cd Vancouver_Crime_Map
   ```
2. Open the notebook:  
   ```bash
   jupyter notebook Vancouver_Crime_Map.ipynb
   ```
3. Run all cells to reproduce analysis & visualizations.  

---

## 📈 Future Improvements  
- Automate data fetching from Vancouver Open Data Portal.  
- Add predictive modeling for crime forecasting.  
- Build a web dashboard using **Plotly Dash** or **Streamlit**.  

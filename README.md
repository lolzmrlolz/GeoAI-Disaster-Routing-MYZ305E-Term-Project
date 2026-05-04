# 🚑 GeoAI Disaster Routing & Logistics (MYZ305E Term Project)

## 📌 Project Overview
This project presents an **Autonomous GeoAI Agent** designed to optimize emergency logistics and routing during post-disaster scenarios (specifically focusing on an earthquake scenario in Tuzla, Istanbul). The system intelligently calculates the safest and fastest routes from designated emergency assembly areas to strategic hospitals.

## 🛠️ Methodology & Technologies Used
* **Data Sources:** Istanbul Metropolitan Municipality (IBB) Open Data Portal.
* **Geospatial Processing:** Python (`geopandas`, `shapely`) and **QGIS** for heatmaps, spatial filtering, and visual analysis.
* **Routing Algorithm:** OpenRouteService (ORS) API for real-time, street-level pathfinding.
* **AI Integration:** Google Gemini Pro API acting as the autonomous agent to evaluate route safety based on distance and duration.
* **Visualization:** `folium` for interactive web mapping and QGIS for high-resolution static map generation.

## 🚀 How to Run the Code
1. Open the provided `GeoAI_Disaster_Routing.ipynb` file in **Google Colab**.
2. Run **STEP 1** to install dependencies (`geopandas`, `folium`, `google-generativeai`).
3. Ensure you have your valid **ORS API Key** and **Gemini API Key** ready.
4. Run the subsequent cells sequentially. The system will automatically fetch the required CSV datasets from this repository and generate the interactive routing map.

## 📺 Demo Video
*(Demo video link will be added here)*

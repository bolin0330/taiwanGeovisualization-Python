![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B829?style=for-the-badge&logo=folium&logoColor=white)
![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=for-the-badge&logo=OpenStreetMap&logoColor=white)
# 🗺️ Taiwan Geovisualization

A collection of Jupyter notebooks for visualizing static and interactive city maps using Python geospatial tools, with a focus on Taiwan's urban data and geographic features.

> 📘 **View all notebooks in nbviewer** 👉 [_No need to run locally!_](https://nbviewer.org/github/bolin0330/taiwanGeovisualization-Python/tree/main/)

---

## 📚 Notebooks

| Notebook | Description | nbviewer Link |
|----------|-------------|----------------|
| `01-City Static Maps` | Static map visualizations using GeoPandas, Matplotlib, and Contextily | [🔗 View](https://nbviewer.org/github/bolin0330/taiwanGeovisualization-Python/blob/main/01-City%20Static%20Maps.ipynb) |
| `02-City Interactive Maps` | Interactive maps using Folium and Pydeck (e.g. heatmaps, 3D columns) | [🔗 View](https://nbviewer.org/github/bolin0330/taiwanGeovisualization-Python/blob/main/02-City%20Interactive%20Maps.ipynb)
| `03-Taiwan Maps` | Taiwan-focused maps including terrain, elevation, administrative boundaries | [🔗 View](https://nbviewer.org/github/bolin0330/taiwanGeovisualization-Python/blob/main/03-Taiwan%20Maps.ipynb) |

---

## ✨ Features

- Static choropleth maps and desire lines
- Interactive heatmaps and 3D visualizations
- Custom terrain colormaps & Fisher-Jenks classification
- Real-world data: YouBike trips, road accidents, elevation, boundaries

---

## 🧰 Tech Stack

- Python, Jupyter Notebook
- GeoPandas, Folium, Pydeck
- Matplotlib, Contextily, jenkspy, osmnx

---


## 💡 Getting Started Locally

```bash
# Clone repo
git clone https://github.com/bolin0330/taiwanGeovisualization-Python.git

# Install dependencies
pip install geopandas folium pydeck matplotlib seaborn osmnx jenkspy contextily

# Launch Jupyter
jupyter notebook
```

---

## 📌 Data Sources

- [Open Government Data TW](https://data.gov.tw/)
- [g0v.tw GeoJSON Data](https://github.com/g0v/twgeojson)
- [Taipei City Government Open Data](https://data.taipei/)
- [Taichung City Govermnet Open Data](https://opendata.taichung.gov.tw/)

---

## 🏫 Acknowledgements

Many of the techniques used in this project were learned through the  
📘 [Web Mapping and Geovisualisation (ENVS456)](https://github.com/GDSL-UL/wma) course at the University of Liverpool,  
designed by Dr. Gabriele Filomena and Dr. Elisabetta Pietrosteffani.  
Their open teaching materials inspired the map design, data handling, and geospatial analysis methods used here.
# CHP & Village Coverage Map – Maasai Mara Ecosystem

An interactive web map showing villages covered by Community Health Promoters (CHPs) and the health facilities serving those villages within the Maasai Mara ecosystem.

## Interactive Map

**View the map online:**

👉 https://pereruannabaala.github.io/chp-coverage-map/

The map can be opened in a web browser and does not require QGIS or any GIS software.

## About the Map

This map was developed to visualize the geographical coverage of CHP activities and the villages served by different health facilities.

Each point on the map represents a mapped village/CHP location. Villages are grouped according to their **serving health facility**.

Users can:

- Search for a village by name.
- Click a village to view its information.
- Identify the health facility serving each village.
- View the geographical distribution of CHP coverage.
- Zoom and pan across the Maasai Mara ecosystem.
- Explore different facility coverage groups.

## 📊 Data Included

The map contains the following information:

| Field | Description |
|---|---|
| Village | Name of the mapped village |
| Serving Facility | Health facility serving the village |
| Latitude | Geographic latitude of the village |
| Longitude | Geographic longitude of the village |

The current map contains **101 mapped village/CHP locations**.

## 🏥 Serving Health Facilities

The mapped villages are associated with the following health facilities:

- Enkipai Dispensary
- Olkoroi Facility
- Olesere Facility
- Talek CHP
- Nkoilale Facility
- Endoinyo Narasha Health Facility
- Olkinyei Health Facility
- Nkaimurunya A
- Moses Nkoitoi Link Facility Aitong

## 🔎 Search Function

The map includes a search function that allows users to quickly locate a village.

For example, users can search for:

- Oloisukut
- Ntulele
- Naadare
- Or any other mapped village

After selecting a result, the map zooms to the corresponding location.

## 🗺️ Mapping Methodology

The map was developed using:

- **QGIS** – for data preparation and spatial visualization
- **qgis2web** – for converting the QGIS project into an interactive web map
- **Leaflet** – for displaying the interactive map in a web browser
- **OpenStreetMap** – as the base map

The original geographic coordinates were checked and standardized to:

**CRS: EPSG:4326 – WGS 84**

## ⚠️ Data and Coverage Note

The health facility names are used to identify the facility serving each mapped village.

The health facilities themselves were not provided with GPS coordinates in the source dataset. Therefore, the map should **not be interpreted as showing the physical locations of the health facilities**.

The points shown on the map represent the mapped villages/CHP locations.

Facility groupings indicate the reported serving facility for each village and should not be interpreted as official administrative or geographic catchment boundaries.

## 🌐 Sharing the Map

Because the map is hosted using GitHub Pages, it can be shared through a web link.

Users do not need to install QGIS or any other GIS software.

**Public map:**

https://pereruannabaala.github.io/chp-coverage-map/

## 📁 Repository Structure

```text
chp-coverage-map/
│
├── index.html
├── css/
├── data/
├── images/
├── js/
└── README.md

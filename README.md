# CHP & Village Coverage Map – Maasai Mara Ecosystem

An interactive web map showing villages covered by Community Health Promoters (CHPs) and the health facilities serving those villages within the Maasai Mara ecosystem.

## Interactive Map

**View the map online:**

https://pereruannabaala.github.io/CHP_Coverage_Web_Map/#9/-1.3006/35.5318

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

## Data Included

The map contains the following information:

| Field | Description |
|---|---|
| Village | Name of the mapped village |
| Facility | Health facility serving the village |
| Latitude | Geographic latitude of the village |
| Longitude | Geographic longitude of the village |

The current map contains **101 mapped village/CHP locations**.

## Serving Health Facilities

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

## Search Function

The map includes a search function that allows users to quickly locate a village.

For example, users can search for:

- Oloisukut
- Ntulele
- Naadare
- Or any other mapped village

After selecting a result, the map zooms to the corresponding location.

## Mapping Methodology

The map was developed using:

- **QGIS** – for data preparation and spatial visualization
- **qgis2web** – for converting the QGIS project into an interactive web map
- **Leaflet** – for displaying the interactive map in a web browser
- **Google Maps(RoadMap)** – as the base map

The original geographic coordinates were checked and standardized to:

**CRS: EPSG:4326 – WGS 84**

## Data and Coverage Note

he villages are colour-coded according to their respective serving health facility, making it easy to identify and distinguish the coverage areas on the map.

The health facilities themselves were not provided with GPS coordinates in the source dataset. Therefore, the map should **not be interpreted as showing the physical locations of the health facilities**.

The points shown on the map represent the mapped villages/CHP locations.

Facility groupings indicate the reported serving facility for each village and should not be interpreted as official administrative or geographic catchment boundaries.

## Sharing the Map

Because the map is hosted using GitHub Pages, it can be shared through a web link.

Users do not need to install QGIS or any other GIS software.

**Public map:**

https://pereruannabaala.github.io/chp-coverage-map/

## Repository Structure

```text
chp-coverage-map/
│
├── index.html
├── css/
├── data/
├── images/
├── js/


## Updating the Map

The map can be updated by:

1. Updating the source data in QGIS.
2. Re-exporting the map using qgis2web.
3. Replacing the files in this repository with the new qgis2web output.
4. Committing and pushing the changes to the `main` branch.
5. GitHub Pages will automatically redeploy the updated map.

## Purpose

The map is intended to support:

- CHP coverage monitoring
- Village-level planning
- Health facility coverage visualization
- Programme monitoring and evaluation
- Identification of geographical coverage gaps
- Communication and reporting

## Maintainer

**Pereruan Nabaala**

Maasai Mara / Kenya




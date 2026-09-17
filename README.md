# Awesome-Location-Intelligence

## Top Location Intelligence Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Spatial Analytics, GIS, Foot-Traffic Insights, Site Selection, Geocoding & Location Data Platforms*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Location Intelligence**. These systems help organizations analyze geographic data for site selection, catchment analysis, foot traffic, territory planning, mapping applications, and spatial decision support.



**Examples** include CARTO, Esri ArcGIS, Precisely, Mapbox, GapMaps, Geoblink, Kalibrate, Unacast, Placer.ai, and SafeGraph (the category leaders).



**Open-source emphasis**: Location intelligence has a rich open ecosystem. **QGIS**, **PostGIS**, **OpenStreetMap**, **kepler.gl**, **deck.gl**, **GeoPandas**, and related tools form a powerful stack for spatial analysis and visualization. Commercial platforms still lead in proprietary mobility data, enterprise support, and polished cloud analytics. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[CARTO](https://carto.com/)**  

  Cloud-native location intelligence platform built for spatial analytics directly on modern data warehouses (Snowflake, BigQuery, Databricks, etc.).



- **[Esri ArcGIS](https://www.esri.com/)**  

  Industry-standard GIS and location intelligence platform with deep desktop, enterprise, and cloud (ArcGIS Online/Enterprise) capabilities.



- **[Precisely](https://www.precisely.com/)**  

  Enterprise data integrity and location platform known for geocoding, address verification, and spatial enrichment at scale.



- **[Mapbox](https://www.mapbox.com/)**  

  Developer-focused location platform providing maps, navigation, search, and location data APIs widely used in applications and AI systems.



- **[GapMaps](https://www.gapmaps.com/)**  

  Location analytics and site selection platform used for retail and network planning.



- **[Geoblink](https://www.geoblink.com/)**  

  Location intelligence tool oriented toward retail and real-estate site evaluation and catchment analysis.



- **[Kalibrate](https://kalibrate.com/)**  

  Location and network planning software used in fuel, convenience, and retail site strategy.



- **[Unacast](https://www.unacast.com/)**  

  Location data and foot-traffic insights platform providing aggregated mobility and visitation analytics.



- **[Placer.ai](https://www.placer.ai/)**  

  Foot-traffic and visitor analytics platform widely used for retail, restaurants, and commercial real estate site decisions.



- **[SafeGraph](https://www.safegraph.com/)**  

  Places and location data provider offering POI, geometry, and related spatial datasets for analytics and applications.



## Open-Source GitHub Projects

- **[QGIS](https://github.com/qgis/QGIS)**  

  Leading open-source desktop GIS for viewing, editing, analyzing, and publishing geospatial data—the foundation of many open location workflows.



- **[PostGIS](https://github.com/postgis/postgis)**  

  Spatial extension for PostgreSQL enabling powerful geographic queries, indexing, and analysis inside a relational database.



- **[OpenStreetMap & related tools](https://github.com/openstreetmap)**  

  Collaborative global map data and the ecosystem of editors, APIs, and renderers built around it.



- **[kepler.gl](https://github.com/keplergl/kepler.gl)**  

  Open-source geospatial analysis tool for large-scale data visualization on the web (originally from Uber).



- **[deck.gl](https://github.com/visgl/deck.gl)**  

  WebGL-powered framework for large-scale data visualization, frequently used with Mapbox or other basemaps for location apps.



- **[GeoPandas](https://github.com/geopandas/geopandas)**  

  Python library that makes working with geospatial data in pandas-style workflows simple and expressive.



- **[GDAL/OGR](https://github.com/OSGeo/gdal)**  

  Fundamental open-source library for reading and writing raster and vector geospatial data formats.



- **[Turf.js](https://github.com/Turfjs/turf)**  

  JavaScript library for spatial analysis on the web (buffers, unions, distance, etc.).



- **[Open Source GIS Stack (OSGS) and integrated stacks](https://github.com/)**  

  Opinionated combinations of PostGIS, QGIS Server, OSM data, and related services for self-hosted geospatial platforms.



- **[QGIS location analytics and market-research plugins](https://github.com/)**  

  Community toolsets that add Huff models, network distance, and other location-intelligence functions inside QGIS.



### Additional Strong Open-Source Options

- Building analysis pipelines with **PostGIS + GeoPandas + QGIS** for full control over spatial logic and data.

- Using **kepler.gl** or **deck.gl** for interactive, large-scale web visualization of location data.

- Combining OpenStreetMap data with commercial or open mobility datasets for hybrid intelligence.

- Accepting that proprietary foot-traffic panels, enterprise geocoding accuracy, polished cloud warehouse-native UX, and global support still favor commercial platforms (CARTO, Esri, Mapbox, Precisely, Placer.ai, etc.).

- Focusing open-source efforts on transparent spatial analysis, reproducible research, and cost-effective GIS.



**Frameworks for building custom systems**: Store geometries and attributes in PostGIS → analyze with SQL/spatial functions or GeoPandas → visualize in QGIS or kepler.gl → publish via QGIS Server, GeoServer, or web maps (Leaflet/MapLibre/deck.gl). Suitable for data teams, researchers, and organizations that want ownership of spatial logic. Many enterprises continue to adopt commercial location intelligence platforms for data coverage and support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Location data often involves personal or sensitive mobility information and must comply with privacy regulations. Open-source stacks require proper security, licensing (map data, basemaps), and governance. This list is not legal or geospatial-compliance advice.



---

**Made for spatial analysts, location strategists, and developers building map-driven products.**

Let's keep location intelligence powerful, transparent, and as open as practical.

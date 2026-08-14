<div align="center">

# 🛰️🌑 Análisis de Imágenes de Satélite
# Eclipse 🌞Solar : 12 de Agosto 2026

</div>

Autora: Lavinia Bacaru (@codinglavinia)<br>
Fecha de comienzo del proyecto: 11 de Agosto de 2026<br>
Ubicación: España — Península Ibérica<br>
Estado: En desarrollo-In development 

##  Descripción del Proyecto:

Este proyecto realiza un análisis geoespacial detallado del impacto del eclipse solar total del **12 de agosto de 2026 en España**, utilizando imágenes de satélite y **QGIS** como herramientas de procesamiento de datos geoespaciales.

---

</div>
<img src="./assets/maps/solar_eclipse_path_spain_2026.png"
     alt="Trayectoria del Eclipse Solar en España — 12 de agosto de 2026"
     width="700">


## 🎯 Objetivos:

* ✅ Descargar imágenes de alta resolución (**10 m**) de la zona de España
* ✅ Procesar datos brutos en **QGIS** mediante composites RGB y falso color
* ✅ Analizar la cobertura de nubes y cambios atmosféricos durante la totalidad
* ✅ Crear visualizaciones comparativas (**pre-eclipse vs. post-eclipse**)
* ✅ Exportar datos en formatos **GeoJSON / GeoTIFF** para aplicaciones web
* ✅ Construir un **dashboard interactivo** con React + Leaflet
* ✅ Documentar todo el flujo de trabajo en GitHub
---
## 🔬 Metodología :

<div align="center">

<p><strong>🛰️ Selección de datos </strong></p>

<p>⬇️</p>

<p><strong>☁️ Control de calidad y nubosidad</strong></p>

<p>⬇️</p>

<p><strong>⚙️ Preprocesamiento de imágenes</strong></p>

<p>⬇️</p>

<p><strong>🎨 Composites RGB / Falso Color</strong></p>

<p>⬇️</p>

<p><strong>📊 Cálculo de índices espectrales</strong></p>

<p>⬇️</p>

<p><strong>🌑 Análisis Pre-Eclipse / Eclipse / Post-Eclipse</strong></p>

<p>⬇️</p>

<p><strong>🗺️ Procesamiento y visualización en QGIS</strong></p>

<p>⬇️</p>

<p><strong>📦 Exportación GeoTIFF / GeoJSON</strong></p>

<p>⬇️</p>

<p><strong>🌐 Visualización web con React + Leaflet</strong></p>

</div>



## 📁 Estructura del Proyecto:

```text
eclipse-satellite- analysis
│
├── data/
│   ├── raw/
│   │   ├── sentinel-2/
│   │   │   ├── 2026-08-11_pre/
│   │   │   ├── 2026-08-12_eclipse/
│   │   │   └── 2026-08-13_post/
│   │   │
│   │   ├── sentinel-5p/
│   │   │   └── 2026-08-12/
│   │   │
│   │   └── meteosat/
│   │       └── 2026-08-12/
│   │
│   └── processed/
│       ├── sentinel-2/
│       ├── sentinel-5p/
│       └── meteosat/
│
├── aoi/
│   ├── spain.geojson
│   └── eclipse_path.geojson
│
├── qgis_workflows/
│   ├── eclipse_analysis.qgz
│   ├── sentinel2_processing.py
│   ├── sentinel5p_analysis.py
│   └── cloud_detection_algorithm.py
│
├── scripts/
│   ├── download_sentinel2.py
│   ├── download_sentinel5p.py
│   ├── preprocess_imagery.py
│   └── export_geojson.py
│
├── visualization/
│   ├── dashboard/
│   └── maps/
│
└── docs/
    ├── WORKFLOW.md
    ├── QGIS_TUTORIAL.md
    ├── SENTINEL5P_ANALYSIS.md
    ├── CLOUD_DETECTION.md
    └── RESULTS.md
```

---

## 🌍 Recursos y referencias :

### 🛰️ Descargar imagenes satelitales

* **Copernicus :**
  https://dataspace.copernicus.eu/


### 📚 Documentación Técnica:

* [Documentación QGIS](https://qgis.org/documentation/)
* [Rasterio Documentation](https://rasterio.readthedocs.io/)
* [GeoPandas Documentation](https://geopandas.org/)
* [Leaflet Documentation](https://leafletjs.com/)

### 🔬 Artículos Científicos :

* *Remote Sensing of Solar Eclipses* : https://blog.linknovate.com/innovation-during-solar-eclipse
  
* *Cloud Detection Algorithms for Sentinel-2 and Sentinel 5* — ISPRS Journal : https://www.sciencedirect.com/science/article/pii/S2666017220300092

---

## Agradecimientos :

🛰️ **Skyline** :  https://theskylive.com/solar-eclipse?id=2026-08-12 <br>
🛰️ **EUMETSAT**: https://user.eumetsat.int/data-access/eumetcast-europe <br>
🗺️ **Comunidad QGIS** : https://qgis.org/community <br>
🇪🇸 **Comunidad GIS de España** :https://www.qgis.es <br>
🔵**Telegram QGIS España** : https://t.me/qgis_es




---

</div>

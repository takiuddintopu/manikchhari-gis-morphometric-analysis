# GIS-Based Morphometric Analysis of Manikchhari Upazila, Bangladesh

A GIS-based analysis of terrain and drainage characteristics of **Manikchhari Upazila, Khagrachhari, Bangladesh**, developed as part of the **GIS Programming and Spatial Analysis Lab (ESG-4108)**.

The project presents selected spatial analyses using GIS-derived thematic maps, focusing on **elevation, slope, stream order, drainage density, and drainage pattern**.

---

## 📍 Study Area

**Manikchhari Upazila** is located in **Khagrachhari District, Bangladesh**.

The study area was analyzed using GIS-based terrain and drainage information to visualize its spatial characteristics.

### Study Area Map

![Study Area Map](figures/01-study-area/study-area-map-of-manikchhari.jpg)

---

## 🎯 Project Objectives

The main purpose of this project was to apply GIS and spatial-analysis techniques to examine selected terrain and drainage characteristics of Manikchhari Upazila.

The analysis focuses on:

* Mapping the spatial distribution of elevation
* Deriving and visualizing slope characteristics
* Mapping the stream-order structure
* Examining drainage density
* Identifying and visualizing the drainage pattern
* Presenting the spatial characteristics through thematic GIS maps

---

## 🗺️ GIS Analysis and Outputs

### 1. Elevation Analysis

The elevation map represents the spatial variation of terrain elevation across Manikchhari Upazila.

![Elevation Map](figures/02-elevation/elevation-map.jpg)

---

### 2. Slope Analysis

The slope map illustrates the spatial variation of terrain slope within the study area.

![Slope Map](figures/03-slope/slope-map.jpg)

---

### 3. Stream Order

The stream-order map presents the hierarchical organization of the drainage network within the study area.

![Stream Order Map](figures/04-stream-order/stream-order-map.jpg)

---

### 4. Drainage Density

The drainage-density map illustrates the spatial distribution of drainage density across Manikchhari Upazila.

![Drainage Density Map](figures/05-drainage-density/drainage-density-map.jpg)

---

### 5. Drainage Pattern

The drainage-pattern map presents the spatial configuration of the drainage network within the study area.

![Drainage Pattern Map](figures/06-drainage-pattern/drainage-pattern-map.jpg)

---

## 🔬 Data and Methodology

### Digital Elevation Model

The terrain analysis was based on a **Digital Elevation Model (DEM)** downloaded from the **United States Geological Survey (USGS)**.

**DEM file:**

```text
n22_e091_1arc_v3.tif
```

The DEM was used as the primary elevation data source for deriving terrain-related outputs, including elevation and slope.

### Coordinate Reference System

The spatial analysis was conducted using:

* **Coordinate system:** Geographic Coordinate System (GCS)
* **Datum:** WGS 1984

### GIS Software

The analysis and thematic map preparation were performed using:

> **ArcMap 10.8**

### Analytical Components

The project included the following GIS-based analyses:

```text
USGS DEM
   │
   ├── Elevation Analysis
   │
   ├── Slope Analysis
   │
   └── Drainage / Stream Analysis
           │
           ├── Stream Order
           ├── Drainage Density
           └── Drainage Pattern
                    │
                    ▼
             Thematic Maps
```

---

## 🧰 Tools and Technologies

| Component           | Details                       |
| ------------------- | ----------------------------- |
| GIS Software        | ArcMap 10.8                   |
| Elevation Data      | USGS DEM                      |
| DEM File            | `n22_e091_1arc_v3.tif`        |
| Coordinate System   | GCS WGS 1984                  |
| Main Analysis       | Terrain and drainage analysis |
| Cartographic Output | Thematic GIS maps             |

---

## 📂 Repository Structure

```text
manikchhari-gis-morphometric-analysis/
│
├── README.md
|
├── LICENSE
│
|
└── figures/
    ├── 01-study-area/
    │   └── study-area-map-of-manikchhari.jpg
    │
    ├── 02-elevation/
    │   └── elevation-map.jpg
    │
    ├── 03-slope/
    │   └── slope-map.jpg
    │
    ├── 04-stream-order/
    │   └── stream-order-map.jpg
    │
    ├── 05-drainage-density/
    │   └── drainage-density-map.jpg
    │
    └── 06-drainage-pattern/
        └── drainage-pattern-map.jpg
```

---

## 📚 Academic Context

This project was completed as an assignment for:

**Course:** GIS Programming and Spatial Analysis Lab
**Course Code:** ESG-4108
**Department:** Environmental Science and Geography
**Institution:** Islamic University, Bangladesh

The original assignment was titled **"Morphometric Analysis."**

---

## ⚠️ Project Scope and Reproducibility

This repository presents the **completed thematic GIS outputs** available from the original project.

The original ArcMap project file and associated working layers are no longer available. Therefore, this repository is intended primarily as a **portfolio showcase of the resulting spatial analyses and maps**, rather than a fully reproducible GIS project.

The repository documents the available analyses and outputs without claiming additional morphometric calculations that are not represented in the preserved project materials.

---

## 👤 Author

**Mohd. Takiuddin**

Environmental Science & Geography
Islamic University, Bangladesh

**GitHub:** [@takiuddintopu](https://github.com/takiuddintopu)

---

## 📌 Project Status

**Completed — Portfolio Presentation**

This repository documents the available GIS outputs from the completed academic project.

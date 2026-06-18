# Flood Inundation Mapping Using Sentinel-1 Dual-Polarization SAR Data

## Overview

This project demonstrates flood inundation mapping in Assam, India, using Sentinel-1 Synthetic Aperture Radar (SAR) imagery. A pre-flood image acquired on 12 May 2024 and a post-flood image acquired on 11 July 2024 were processed in SNAP and visualized in QGIS to identify flooded areas.

## Study Area

The study area is located in the Brahmaputra River floodplain of Assam, India, one of the most flood-prone regions in the country.

### Approximate Coordinates

* Latitude: 25.0°N – 27.0°N
* Longitude: 90.6°E – 93.4°E

## Data Used

### Sentinel-1A SAR Data

| Image Type | Acquisition Date | Product Type | Polarization |
| ---------- | ---------------- | ------------ | ------------ |
| Pre-Flood  | 12 May 2024      | GRD          | VV, VH       |
| Post-Flood | 11 July 2024     | GRD          | VV, VH       |

Source: Copernicus Data Space Ecosystem

## Software Used

* SNAP 13
* QGIS
* Google Earth Pro

## Methodology

1. Apply Orbit File
2. Thermal Noise Removal
3. Radiometric Calibration
4. Refined Lee Speckle Filtering
5. Terrain Correction
6. Conversion to dB Scale
7. Water Extraction using Thresholding
8. Flood Change Detection
9. Map Preparation in QGIS

## Results

The post-flood SAR image shows an increase in water-covered areas along the Brahmaputra River compared to the pre-flood condition. Flooded regions were successfully identified using SAR backscatter characteristics and change detection techniques.

## Project Outputs

* Pre-Flood SAR Map
* Post-Flood SAR Map
* Flood Mask
* Flood Inundation Map

## Repository Contents

* Flood mapping outputs
* Final maps
* Project documentation
* Processing workflow

## Author

**Sumit Kushwaha**

## Keywords

Flood Mapping, Sentinel-1, SAR, Remote Sensing, SNAP, QGIS, Assam Floods, Change Detection, Disaster Management
<img width="4677" height="3307" alt="assam_flooding (1)" src="https://github.com/user-attachments/assets/d760383d-6d47-4969-aaa8-aa43d4316324" />

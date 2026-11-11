# Dancing with the SARs

### NASA Space Apps Challenge 2026

An attempt to understand and visualize changes happening on Earth's surface using data from the NASA-ISRO NISAR mission.

## About the Project

Earth's surface is constantly changing. Forests grow and disappear, glaciers move, wetlands shrink, and land deformation occurs due to both natural processes and human activities.

Detecting and understanding these changes is not always straightforward, especially when relying on conventional satellite imagery.

For this challenge, we are exploring how Synthetic Aperture Radar (SAR) data from the NISAR mission can be used to observe changes on Earth's surface over time.

Our goal is to develop an application that makes these changes easier to explore, analyze and visualize.

## Why NISAR?

NISAR is a joint Earth-observation mission developed by NASA and ISRO. It carries two radar systems:

- **L-band SAR** – operates at approximately 1.25 GHz.
- **S-band SAR** – operates at approximately 3.2 GHz.

Unlike optical satellites, radar satellites transmit their own signals and measure the energy reflected back from Earth's surface. This allows observations during both day and night and through most cloud cover.

The data offers opportunities to study land deformation, vegetation, wetlands, agriculture, ice movement and other changes across the planet.

## What We Are Working On

We are exploring different aspects of SAR data processing and geospatial analysis, with a focus on identifying and understanding surface changes over time.

Our work currently covers:

- SAR data acquisition and preprocessing.
- Understanding radar backscatter and phase information.
- Multi-temporal image analysis.
- Change detection and mathematical modelling.
- Geospatial data processing and visualization.
- Testing and validating results.

The exact methods and features will evolve as we work with the data and understand what is technically feasible.

## Technologies

Our current technology exploration includes:

- Python
- NumPy and SciPy
- ESA SNAP
- QGIS
- GDAL and Rasterio
- GeoPandas
- Streamlit and web technologies
- Git and GitHub

Each member is responsible for their own technical contributions, and we will bring the individual components together during integration.

## Repository Structure

```text
dancing-with-the-sars/
│
├── docs/
│   ├── project-overview.md
│   ├── architecture.md
│   └── research/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── src/
│   ├── sar_processing/
│   ├── change_detection/
│   ├── data_engineering/
│   ├── geospatial/
│   └── visualization/
│
├── experiments/
├── tests/
│
├── requirements.txt
├── .gitignore
└── README.md
```




## References

- [NASA NISAR Mission](https://nisar.jpl.nasa.gov/)
- [ISRO](https://www.isro.gov.in/)
- [NASA Earthdata](https://www.earthdata.nasa.gov/)
- [Alaska Satellite Facility](https://asf.alaska.edu/)
- [NASA Space Apps Challenge](https://www.spaceappschallenge.org/)

---


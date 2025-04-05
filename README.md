# Coastline_erosion_model
This repository is dedicated to exploring and advancing the automated extraction of coastlines from PlanetLabs satellite imagery, as part of efforts to model coastal erosion in Alaska. The project contributes to enhancing existing segmentation algorithms, refining coastal detection methods, and expanding datasets to improve predictions of coastline changes over time.

Project Scope
Data Processing: Leveraging multi-band satellite imagery (NDWI) to generate labeled datasets and improve water body detection.
Segmentation Improvements: Enhancing model accuracy for challenging conditions such as shadows, artifacts, and steep coastal regions.
Integration of New Data Sources: Exploring the use of SWIR bands and elevation data for more precise segmentation.
Scalability: Creating a robust and scalable pipeline for processing large datasets to track coastline changes over time.

Goals
Develop an advanced Python pipeline capable of producing highly accurate, vectorized coastline representations.
Address known challenges like segmentation performance in shadowed, cliff-like, or artifact-heavy areas.
Lay the groundwork for refining models like DeepWaterMap with new data sources, including PlanetLabs imagery and DEMs.

Getting Started
This repository contains scripts, initial model training explorations, and tools for:
Automated satellite imagery download and preprocessing.
NDWI-based water body segmentation.
Early-stage algorithmic enhancements for coastline detection.

Contributions
We welcome collaboration from geospatial data enthusiasts, Python developers, and climate researchers. Feedback, issues, and pull requests are highly encouraged.


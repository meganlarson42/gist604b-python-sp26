# Python GIS and Containerization

**Student:** Megan Larson

**Course:** GIST 604B – Open Source GIS

**Module:** Module 3 - Python GIS & Containerization

**University of Arizona**

## Project Description
This project was a hands-on introduction to using Python for geographic information systems. I learned how to use specialized code libraries to open, look at, and change different types of map data like tables, shapes, and satellite pictures.

## Tools and Technologies
- Python (pandas, GeoPandas, Rasterio)
- GitHub Codespaces (Cloud Environment)
- Jupyter Notebooks
- Pytest (Code Testing Tool)

## What I Did
- **Worked with Tables:** Used the pandas library to open CSV files, filter out specific information, and calculate basic math like averages for environmental data.
- **Analyzed Map Shapes:** Used GeoPandas to handle vector data, which included changing map projections, finding the center of shapes, and creating "buffer" zones around points.
- **Processed Satellite Images:** Used Rasterio to find and open satellite photos from the cloud, calculated a "greenness" index (NDVI), and clipped images to fit specific boundaries.
- **Practiced Coding Workflows:** Wrote Python functions in scripts and used an automated tool called pytest to make sure my code was working correctly.
- **Used Cloud Tools:** Completed all work inside GitHub Codespaces to ensure the software environment stayed the same throughout the assignment.

## How to View / Run
- **Open in Codespaces:** Launch the project in GitHub Codespaces to use the pre-installed tools.
- **Run Notebooks:** Open files in the notebooks folder one by one and run them to see the step-by-step maps and charts.
- **Test the Code:** Type pytest in the command terminal to see the results of the code checks for the pandas and GeoPandas parts.

## Repository Structure
    .
    ├── README.md
    ├── .devcontainer
    │   ├── devcontainer.json
    │   ├── Dockerfile
    ├── data/
    │   ├── neighborhood_samples.geojson
    │   ├── temperature_readings.csv
    │   └── weather_stations.csv
    ├── notebooks/
    │   ├── pandas/
    │   ├── geopandas/
    │   └── rasterio/
    ├── src/
    │   ├── pandas_basics.py
    │   ├── geopandas_basics.py
    │   └── download_real_data.py
    ├── tests/
    │   ├── test_pandas_basics.py
    │   └── test_geopandas_basics.py
    ├── pyproject.toml
    └── uv.lock

## Notes

- Notebooks are for exploration and learning.
- Final implementations are in `src/`.
- Tests validate pandas and GeoPandas functionality.
- Rasterio work is completed entirely in the notebook.

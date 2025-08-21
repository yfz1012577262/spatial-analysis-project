Vancouver Accessibility Index

This project computes and visualizes an Accessibility Index for neighborhoods in the City of Vancouver by using data provided by OPENDATA API. The analysis uses geospatial data to evaluate how well different areas are served by key urban amenities such as schools, transit, bike infrastructure, and parks.

The results are presented on an interactive map, allowing users to explore how accessibility varies across neighborhoods based on an index evaluation.

✨ Features

Geospatial Data Processing: Uses geopandas to transform and manage shapefiles of Vancouver neighborhoods.

Accessibility Index Calculation: Combines multiple indicators (schools, transit stations, bike lane length, park area) into a composite index score.

Interactive Mapping: Employs leafmap/folium to create an interactive map with choropleth styling and popups for neighborhood-specific details.

Customizable Metrics: Easy to adapt the weighting or choice of features used in the accessibility calculation on personal pereference.

📊 Accessibility Indicators

The index is based on the following measures per neighborhood:

Schools – number of schools in the area

Transit Access – number of rapid transit stations

Cycling Infrastructure – total length of bike lanes (numeric)

Parks – total park area (numeric)

These indicators are normalized and combined to generate a single Accessibility Index.

🗺️ Visualization

The output is an interactive map where neighborhoods are shaded according to their Accessibility Index. Clicking on a neighborhood shows details including:

Neighborhood ID

Accessibility Index

Counts of schools and rapid transit stations

Length of bike infrastructure

Park area

<img width="1659" height="613" alt="image" src="https://github.com/user-attachments/assets/5d67e03b-22bd-442c-8b0d-41eeacdb653f" />

Main libraries used:

geopandas

leafmap / folium

matplotlib

pandas

numpy

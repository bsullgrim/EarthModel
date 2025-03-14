# 3D Earth Model with Country Borders

## Description

This Python script creates an interactive 3D visualization of Earth using Plotly, featuring country borders. The model includes a blue sphere representing the Earth's oceans and green lines depicting country boundaries.

## Features

- 3D representation of Earth
- Country borders visualized as green lines
- Interactive plot allowing rotation and zoom

## Requirements

- Python 3.x
- Required libraries:
  - plotly
  - numpy
  - geopandas
  - requests

## Installation

1. Ensure you have Python 3.x installed.
2. Install the required libraries:
   `pip install plotly numpy geopandas requests`

## Usage

1. Run the script in a Python environment.
2. The script will download and process a shapefile containing country boundary data.
3. An interactive 3D plot will be generated and displayed.

## How it works

1. The script downloads a shapefile containing country boundary data from Natural Earth.
2. It creates a 3D sphere representing Earth using Plotly.
3. Country boundaries are plotted on the sphere using the downloaded shapefile data.
4. The resulting 3D model is displayed in an interactive Plotly figure.

## Customization

- You can adjust the Earth's radius by modifying the `R` variable (currently set to 6371 km).
- The color scheme can be changed by modifying the `colorscale` and `line` color parameters.

## Troubleshooting

If you encounter issues with shapefile loading, ensure you have a stable internet connection and that the URL for the shapefile is accessible.

## Contributing

Feel free to fork this project and submit pull requests with improvements or additional features.


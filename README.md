```markdown
# STORIES-OF-CHANGE-AGRICULTURE-TZ

![Project Screenshot](https://github.com/benny-png/STORIES-OF-CHANGE-AGRICULTURE-TZ/blob/main/Screenshot%202024-05-29%20111817.png)

## Overview

**STORIES-OF-CHANGE-AGRICULTURE-TZ** is a project aimed at visualizing agricultural changes in Tanzania using choropleth maps. The project leverages GeoJSON data to outline Tanzanian regions and Plotly for map visualization.

## Table of Contents

- [Overview](#overview)
- [Repository Contents](#repository-contents)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Project](#running-the-project)
- [Project Details](#project-details)
  - [GeoJSON Data](#geojson-data)
  - [CSV Data Files](#csv-data-files)
  - [Python Scripts](#python-scripts)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Repository Contents

- `README.md`: Project overview and instructions.
- `Screenshot 2024-05-29 111817.png`: Screenshot of the project output.
- `TZA_adm1_mkoaTZ.geojson`: GeoJSON file containing geographical boundaries of Tanzanian regions.
- `food_production_data.csv`: CSV file containing agricultural data for Tanzania.
- `map_plotter_test.py`: Python script for generating the choropleth map.
- `optimizer_map.py`: Additional Python script for map optimization.
- `tanzania_regions.csv`: CSV file containing names of Tanzanian regions.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- pandas
- plotly
- requests
- openpyxl

Install the required Python packages using pip:

```sh
pip install pandas plotly requests openpyxl
```

### Installation

Clone the repository:

```sh
git clone https://github.com/benny-png/STORIES-OF-CHANGE-AGRICULTURE-TZ.git
cd STORIES-OF-CHANGE-AGRICULTURE-TZ
```

### Running the Project

1. **Prepare your data**: Ensure `food_production_data.csv` and `tanzania_regions.csv` are correctly formatted and contain the necessary data.

2. **Run the script**: Execute `map_plotter_test.py` to generate the choropleth map.

```sh
python map_plotter_test.py
```

## Project Details

### GeoJSON Data

- `TZA_adm1_mkoaTZ.geojson`: Contains GeoJSON data for the administrative boundaries of Tanzanian regions. Used to plot the regions on the map.

### CSV Data Files

- `food_production_data.csv`: Includes agricultural data for different regions in Tanzania.
- `tanzania_regions.csv`: Contains the names of the regions in Tanzania.

### Python Scripts

- `map_plotter_test.py`: Script using Plotly to create a choropleth map of Tanzania. It reads GeoJSON and CSV data, processes it, and generates the map.
- `optimizer_map.py`: Provides additional functionalities for optimizing the map display.

## Contributing

Contributions are welcome! Please fork this repository, create a new branch, and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or suggestions, feel free to open an issue or contact the repository owner.

```

This `README.md` is organized and detailed, making it easier for users to understand the purpose of the project, set it up, and contribute. Adjust the content as needed based on any specific details of your project.

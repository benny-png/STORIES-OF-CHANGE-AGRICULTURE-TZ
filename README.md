
# STORIES-OF-CHANGE-AGRICULTURE-TZ 🚜

![Project Screenshot](https://github.com/benny-png/STORIES-OF-CHANGE-AGRICULTURE-TZ/blob/main/Screenshot%202024-05-29%20111817.png)


## Overview

**STORIES-OF-CHANGE-AGRICULTURE-TZ** is a project aimed at visualizing agricultural changes in Tanzania through interactive choropleth maps. The project utilizes GeoJSON data for Tanzanian regions and Plotly for map visualization, providing insights into agricultural data and trends.

This project was created for the Jamii Forums' Challenge "Stories of Change." [Read more about it here](https://www.jamiiforums.com/threads/exponential-development-vision-2035-dira-ya-maendeleo-ya-kasi-2035.2217724/).

## Features

- **GeoJSON Data Integration**: Displays geographical boundaries of Tanzanian regions.
- **Interactive Maps**: Utilizes Plotly to create dynamic and interactive choropleth maps.
- **Data Visualization**: Visualizes agricultural data, highlighting changes and trends over time.
- **CSV Data Processing**: Reads and processes agricultural data from CSV files.
- **Greedy Algorithm Optimizer**: Implements a greedy algorithm to optimize regional networks based on food production data.

## Requirements

- Python 3.x
- pandas
- plotly
- geopandas
- json

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/benny-png/STORIES-OF-CHANGE-AGRICULTURE-TZ.git
    cd STORIES-OF-CHANGE-AGRICULTURE-TZ
    ```

2. Install the required Python packages:
    ```bash
    pip install pandas plotly geopandas json
    ```

## Usage

1. Prepare your data: Ensure `food_production_data.csv` and `TZA_adm1_mkoaTZ.geojson` are correctly formatted and contain the necessary data.

2. Run the script to generate the choropleth map:
    ```bash
    python map_plotter_test.py
    ```

3. Run the optimizer script to visualize optimized regional networks:
    ```bash
    python optimizer_map.py
    ```
    
![Greedy Optimizer Screenshot](https://github.com/benny-png/STORIES-OF-CHANGE-AGRICULTURE-TZ/blob/main/zonedivisionbyproduction.png)


4. The map will display the agricultural data across Tanzanian regions grouped in zones, allowing for interactive exploration and clssification of the zones based on data and number of mega-industries.

## Repository Contents

- `README.md`: Project overview and instructions.
- `Screenshot 2024-05-29 111817.png`: Screenshot of the project output.
- `zonedivisionbyproduction.png`: Screenshot of the greedy optimizer output.
- `TZA_adm1_mkoaTZ.geojson`: GeoJSON file containing geographical boundaries of Tanzanian regions.
- `food_production_data.csv`: CSV file containing agricultural data for Tanzania.
- `map_plotter_test.py`: Python script for generating the choropleth map.
- `optimizer_map.py`: Additional Python script for map optimization.
- `tanzania_regions.csv`: CSV file containing names of Tanzanian regions.




## Contributing

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request for any improvements or bug fixes. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any inquiries or support, please contact:
- **Benny**: mazikuben2@gmail.com
- **GitHub**: [benny-png](https://github.com/benny-png)


## Vote for the Project

If you find this project useful, please consider voting for it in the Jamii Forums' "Challenge Stories of Change." The poll is at the bottom of the [article](https://www.jamiiforums.com/threads/exponential-development-vision-2035-dira-ya-maendeleo-ya-kasi-2035.2217724/). Your support is greatly appreciated!

---

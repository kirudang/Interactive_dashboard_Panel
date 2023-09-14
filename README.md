# CO2 Emission Data Visualization Dashboard

![Dashboard Preview](https://github.com/kirudang/Interactive_dashboard_Panel/assets/91911269/d75f342c-de88-45c8-bdf6-d60efd61e592)


This project provides an interactive dashboard for visualizing CO2 emission data from [Our World in Data](https://ourworldindata.org/). The dashboard is built using Python libraries such as Panel, Hvplot, and GeoPandas to create interactive and informative data visualizations.
Link to access data: https://github.com/owid/co2-data

## Table of Contents
- [Introduction](#Introduction)
- [Features](#Features)
- [Getting Started](#Getting-started)
- [Usage](#Usage)
- [Dependencies](#Dependencies)
- [Contributing](#Contributing)
- [License](#License)

## Introduction

Carbon dioxide (CO2) emissions are a major contributor to global climate change. This interactive dashboard allows you to explore CO2 emissions data from different regions, countries, and time periods. You can visualize trends, compare emissions between countries, and gain insights into the impact of CO2 emissions on climate change.

## Features

- Interactive data visualization of CO2 emissions.
- Filter data by year and country.
- View CO2 emissions on a map.
- Compare emissions between countries using scatterplots.
- Access historical data to analyze trends.

## Getting Started

To get started with the CO2 Emission Data Visualization Dashboard, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/kirudang/Interactive_dashboard_Panel.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Interactive_dashboard_Panel
   ```
3. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the dashboard:
   ```bash
   panel serve Dashboard.ipynb --show # On terminal, or
   template.show() # On your jupiter notebook / lab
   ```
## Usage

Once the dashboard is running, you can use the following features:

- Use the year slider to select a specific year for CO2 emissions data.
- Select one or more countries from the multi-choice widget to filter the data.
- Explore CO2 emissions trends over time with the line chart.
- Compare emissions between countries using the scatterplot.
- Visualize CO2 emissions on the map.


https://github.com/kirudang/Interactive_dashboard_Panel/assets/91911269/cd230aa1-e1ae-4847-be22-f39290d36f2d


## Dependencies

The dashboard relies on the following Python libraries:

- Panel
- Hvplot
- GeoPandas
- Pandas

These dependencies are listed in the `requirements.txt` file.

## Contributing

Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request. We appreciate your help in improving this dashboard.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



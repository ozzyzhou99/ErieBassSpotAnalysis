# Erie Smallmouth Bass Habitat Modeling

## Project Overview

This project aims to identify optimal fishing spots for **smallmouth bass** along the shores of **Lake Erie** using **ArcGIS** and its **Geostatistical Logistic Prediction (GLP)** tool. By analyzing the relationship between environmental factors and the presence of smallmouth bass, the project helps understand habitat preferences and provides valuable insights for anglers and environmental researchers.

## Features

- **Logistic Regression with GLP**: Uses the **Geostatistical Logistic Prediction** tool in **ArcGIS** to model the probability of smallmouth bass presence based on multiple environmental factors.
- **Key Environmental Variables**:
  - **Water Depth**: Depth at different fishing locations.
  - **Bathymetry Texture**: Characteristics of the lake's bottom surface.
  - **Vertical Water Temperature**: Water temperature profiles at various depths.
  - **Food Source Availability**: Presence of prey for the smallmouth bass.
- **Statistical Validation**: The model is further evaluated with **t-tests** and **chi-square tests** to assess the significance of the predictor variables.
- **GIS Mapping**: Results from the GLP model are visualized in **ArcGIS**, highlighting optimal fishing areas.

## Data Sources

- **Water Depth and Bathymetry**: Data obtained from official surveys of Lake Erie.
- **Water Temperature**: Vertical temperature profiles from monitoring stations.
- **Food Source Availability**: Information sourced from ecological studies and fishing reports.

## How to Use

1. **Prepare Data**: Ensure all environmental data (water depth, bathymetry, temperature, food sources) is correctly formatted and preprocessed.
2. **Use GLP Tool**: 
   - Load the data into **ArcGIS**.
   - Use the **Geostatistical Logistic Prediction (GLP)** tool to run logistic regression based on the provided environmental variables.
3. **Visualize Results**: After running the GLP analysis, visualize the output maps to identify prime smallmouth bass fishing locations.
4. **Analysis and Interpretation**: Utilize the generated maps and statistical results to interpret how each environmental factor influences smallmouth bass habitat.

## Results

- The logistic regression model reveals the most critical environmental factors affecting smallmouth bass presence.
- GIS-based maps highlight **optimal fishing spots** around Lake Erie based on predicted probabilities, providing practical guidance for anglers.

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ErieBassSpotAnalysis.git
   cd ErieBassSpotAnalysis
2. Make sure you have ArcGIS Pro installed with access to the GLP tool under the Geostatistical Analyst extension.
3. Follow the provided instructions in the docs/ folder for detailed steps on running the analysis in ArcGIS.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request with suggestions, improvements, or bug reports.

## Contact
For questions or further information, please contact Zhongyu Zhou at [zzhou47@buffalo.edu].

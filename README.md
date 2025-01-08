
# belly-button-challenge
Deployment page : https://lakshmiabbaraju.github.io/belly-button-challenge/

## Project Overview
This project provides an interactive dashboard to explore the **Belly Button Biodiversity** dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (Operational Taxonomic Units or OTUs) were present in more than 70% of people, while the rest were relatively rare.

The goal of this dashboard is to allow users to interactively explore the data and see various visualizations such as a **bar chart**, **bubble chart**, and **metadata information** based on the sample selected.

## Features
- **Bar Chart**: Displays the top 10 OTUs found in a selected sample.
- **Bubble Chart**: Shows the distribution of OTUs in a selected sample, with marker size and color representing the sample values and OTU IDs.
- **Metadata**: Displays demographic information (age, gender, etc.) of an individual based on the sample selected.
- **Dynamic Interaction**: Updates all charts and metadata when a new sample is selected from the dropdown menu.

## Technologies Used
- **HTML**: For the structure of the webpage.
- **CSS**: For styling the layout and charts.
- **JavaScript**: For interactivity, data processing, and visualization.
    - **D3.js**: To load and manipulate the dataset and create interactive charts.
    - **Plotly.js**: For creating the bar chart and bubble chart.
- **GitHub Pages**: For deploying the project online.

## Usage
Once you load the project in your browser, you will see a dropdown menu populated with different sample IDs. Here’s how to use the dashboard:

1. **Select a sample** from the dropdown to see the associated OTUs and metadata.
2. **Bar chart**: The chart will display the top 10 OTUs found in that individual sample.
3. **Bubble chart**: The chart will display a bubble chart where each bubble represents an OTU, with the size corresponding to the sample value and the color corresponding to the OTU ID.
4. **Metadata**: The demographic data for that sample will appear below the charts.

## How the App Works
- **D3.js** is used to load the `samples.json` file from a URL and process the data.
- **Bar Chart**: Displays the top 10 OTUs based on sample values.
- **Bubble Chart**: Visualizes the full OTU distribution in each sample.
- **Metadata**: Displays the individual's demographic information (age, ethnicity, etc.).
- **Interactive Dashboard**: The visualizations update when a new sample is selected from the dropdown.


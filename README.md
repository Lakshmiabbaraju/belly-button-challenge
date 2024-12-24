# belly-button-challenge

## Project Overview
This project provides an interactive dashboard to explore the **Belly Button Biodiversity** dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (Operational Taxonomic Units or OTUs) were present in more than 70% of people, while the rest were relatively rare.

The goal of this dashboard is to allow users to interactively explore the data and see various visualizations such as a **bar chart**, **bubble chart**, and **metadata information** based on the sample selected.

## Features
- **Bar Chart**: Displays the top 10 OTUs found in a selected sample.
- **Bubble Chart**: Shows the distribution of OTUs in a selected sample, with marker size and color representing the sample values and OTU IDs.
- **Metadata**: Displays demographic information (age, gender, etc.) of an individual based on the sample selected.
- **Dynamic Interaction**: Updates all charts and metadata when a new sample is selected from the dropdown menu.

## Installation Instructions
To run the project locally:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/<your-username>/belly-button-challenge.git
    ```

2. **Navigate into the project directory**:
    ```bash
    cd belly-button-challenge
    ```

3. **Open `index.html` in your browser**:
    - You can simply double-click `index.html`, or if you're using a code editor like Visual Studio Code, you can open the file directly in the editor and use its live preview feature.

4. **Dependencies**:
    - No additional dependencies are required as the project is built using D3.js and Plotly.js which are included in the `index.html` file.

## Technologies Used
- **HTML**: For the structure of the webpage.
- **CSS**: For styling the layout and charts.
- **JavaScript**: For interactivity, data processing, and visualization.
    - **D3.js**: To load and manipulate the dataset and create interactive charts.
    - **Plotly.js**: For creating the bar chart and bubble chart.
- **GitHub Pages**: For deploying the project online.

## Project Demo
You can view the live demo of this project hosted on GitHub Pages:
[https://<your-username>.github.io/belly-button-challenge](https://<your-username>.github.io/belly-button-challenge)

### **Screenshots of the Dashboard**:
1. **Bar Chart** showing top 10 OTUs:
    ![Bar Chart Screenshot](link-to-your-screenshot.png)
   
2. **Bubble Chart** showing OTU distribution:
    ![Bubble Chart Screenshot](link-to-your-screenshot.png)

3. **Metadata** displaying individual information:
    ![Metadata Screenshot](link-to-your-screenshot.png)

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

## Contribution
We welcome contributions to improve the project. To contribute, please follow these steps:
1. Fork the repository to your own GitHub account.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m "Add new feature"`).
4. Push to your forked repository (`git push origin feature-branch`).
5. Submit a pull request with a description of the changes.

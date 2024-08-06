# belly-button-challenge

## Objective
Create an interactive dashboard to visualize the belly button biodiversity dataset. The dashboard includes a dropdown menu, a bar chart, a bubble chart, and a metadata display panel. The visualizations update dynamically based on the selected sample from the dropdown menu.

## Components
- **Dropdown Menu**: Allows users to select a sample ID.
- **Metadata Panel**: Displays demographic information of the selected sample.
- **Bar Chart**: Displays the top 10 Operational Taxonomic Units (OTUs) found in the selected sample.
- **Bubble Chart**: Displays each OTU's abundance in the selected sample.

## Implementation Steps

### 1. Data Fetching
Use D3.js to fetch the dataset from a specified URL in JSON format.

### 2. Dropdown Menu Population
Populate the dropdown menu with sample IDs extracted from the dataset.

### 3. Metadata Display
Display demographic information for the selected sample in a designated panel.

### 4. Bar Chart
Create a horizontal bar chart to display the top 10 OTUs for the selected sample, using sample values for the bar lengths and OTU IDs for the labels.

### 5. Bubble Chart
Create a bubble chart to visualize the OTUs for the selected sample, using OTU IDs for the x-axis, sample values for the y-axis, sample values for the marker sizes, and OTU IDs for the marker colors.

### 6. Dynamic Updates
Implement functionality to update the charts and metadata panel whenever a new sample is selected from the dropdown menu.

## Interactivity
Ensure the dashboard updates dynamically based on user selection, providing a seamless and interactive user experience.

## Deployment
Deploy the completed dashboard to a static page hosting service like GitHub Pages and ensure it is accessible online.

URL: https://jeffjunohkim.github.io/belly-button-challenge/

## Code Source
- Learning Assistant
- GitHub location: https://github.com/jeffjunohkim/belly-button-challenge.git
  

---
title: "Emigrant Country Dashboard"
author: "Chris Formoso"
location: "Calgary, Alberta, Canada"
date_created: 2024-08-26
last_updated: 2024-08-26
version: v1.0
status: "Completed"
tags:
  - emigration
  - dashboard
  - data-visualization
data_sources:
  - "Philippines Emigration Data (1981-2022)"
alignment: "This project aligns with DEP Data Hub's objective of enabling data engagement by providing interactive visualizations of Philippine emigration trends."
---

# Emigrant Country Dashboard

*Note: To view the full metadata for this project, please see the raw file in our [GitHub repository](https://github.com/dataengineeringpilipinas/datahub/tree/main/projects).*

## Summary
The Emigrant Country Dashboard project aims to visualize and analyze the emigration trends from the Philippines to various countries from 1981 to 2022. This dashboard provides insights into the patterns and changes in emigration over the years, allowing users to explore the data interactively.

## Methodology
The project was developed using Python with the Streamlit framework for building the dashboard. The primary data processing was done using pandas, and visualizations were created using Plotly. The cleaned data was reshaped into a long format to facilitate easier analysis and visualization. 

Key steps in the methodology included:
1. Loading and cleaning the emigration data.
2. Reshaping the data into a long format for analysis.
3. Building interactive visualizations to explore the emigration trends.
4. Deploying the dashboard using Streamlit.

## Key Findings
- The data shows significant emigration patterns, with certain countries like the USA, Canada, and Japan consistently being top destinations for Filipino emigrants.
- There were notable spikes in emigration during specific years, which could be correlated with global or local events influencing migration.

## Visualizations
The dashboard includes interactive visualizations such as:
- A line chart showing the trend of emigration to different countries over the years.
- A bar chart comparing the total number of emigrants by country.

These visualizations allow users to drill down into specific countries and time periods to explore the data in detail.

## Code
The project's code is available in the following repository:
- [Emigrant Country Dashboard Repository](https://github.com/chrisformoso-ca/emigrant-country-dashboard)

Streamlit App: You can explore the dashboard live at the following link:
- [Emigrant Country Dashboard App](https://emigrant-country-dashboard.streamlit.app/)

## Challenges and Solutions
One of the challenges faced was handling missing data and ensuring the accuracy of the cleaned dataset. This was addressed by filling missing values with zeros and verifying the data against the original sources. Additionally, reshaping the data into a long format required careful handling of column headers and data types.

## Community Impact
This dashboard provides a valuable tool for researchers, policymakers, and the general public to understand emigration trends from the Philippines. It can inform policy decisions, aid in demographic studies, and raise awareness about migration patterns.

## Future Work
Potential next steps for this project include:
- Adding more detailed analysis on the factors influencing emigration trends.
- Integrating additional data sources, such as economic indicators or policy changes, to provide context to the emigration trends.
- Enhancing the dashboard with more interactive features, such as filtering by regions or demographic factors.

## Contributors
- Chris Formoso

## License
This project is shared under the MIT License.

## Socials
- **LinkedIn:** [https://www.linkedin.com/in/chris-formoso/](https://www.linkedin.com/in/chris-formoso/)
- **GitHub:** [https://github.com/chrisformoso-ca](https://github.com/chrisformoso-ca)

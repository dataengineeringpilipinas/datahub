# Emigrant Country Dashboard

## Metadata
- **Author:** Chris Formoso
- **Date Created:** 2024-08-26
- **Last Updated:** 2024-08-26
- **Version:** v1.0
- **Status:** Completed

## Summary
The Emigrant Country Dashboard project aims to visualize and analyze the emigration trends from the Philippines to various countries from 1981 to 2022. This dashboard provides insights into the patterns and changes in emigration over the years, allowing users to explore the data interactively.

## Data Sources Used
- [Philippines Emigration Data (1981-2022)](datahub/hosted-data/emigration-by-country-long-format/Cleaned_Emigrant_Data.xlsx)

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

## Streamlit App
You can explore the dashboard live at the following link:
- [Emigrant Country Dashboard App](https://emigrant-country-dashboard.streamlit.app/)

## Challenges and Solutions
One of the challenges faced was handling missing data and ensuring the accuracy of the cleaned dataset. This was addressed by filling missing values with zeros and verifying the data against the original sources. Additionally, reshaping the data into a long format required careful handling of column headers and data types.

## Future Work
Potential next steps for this project include:
- Adding more detailed analysis on the factors influencing emigration trends.
- Integrating additional data sources, such as economic indicators or policy changes, to provide context to the emigration trends.
- Enhancing the dashboard with more interactive features, such as filtering by regions or demographic factors.

## Contributors
- Chris Formoso

## Socials
- **LinkedIn:** [https://www.linkedin.com/in/chris-formoso/](https://www.linkedin.com/in/chris-formoso/)
- **GitHub:** [https://github.com/chrisformoso-ca](https://github.com/chrisformoso-ca)

## License
This project is shared under the MIT License.

---
Submitted by: Chris Formoso 
Date: 2024-08-26

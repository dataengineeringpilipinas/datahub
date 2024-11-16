# Statistical Profile of Spouses and Other Partners of Foreign Nationals (1989-2022)
[Dataset Source](https://cfo.gov.ph/statistics-2/) 

---
- `title`: Foreign Spouse Nationality Dashboard
- `author`: Jun Miano
- `location`: Davao City, Philippines,8000
- `date_created`: 2024-11-11
- `last_updated`: 2024-11-16
- `version`: v1.0
- `status`: "In-Progress"
  
- `tags`:
  - Data Cleaning and Reshaping
  - Data Inferencing
  - Data Visualization
    
- `data_sources`:
  - [Commission on Filipino Overseas (CFO)](https://cfo.gov.ph/statistics-2/) 

- `alignment`: This project aligns with DEP Data Hub's objective of enabling data engagement by providing automation of cleaning, inferencing and visualization of publicly available datasets from  Commission on Filipino Overseas (CFO).
---

# Foreign Spouse Nationality Dashboard
*Note: To view the full metadata for this project, please see the raw file in our [GitHub repository](https://github.com/dataengineeringpilipinas/datahub/tree/main/projects).*

## Summary
The Foreign Spouse Nationality Dashboard project aims to capture the trends, distribution and the top five country of origins of the foreign spouse nationalities from 1981 to 2022. It allows the user to quickly visualize and analyze insights into the patterns and numbers of foreign spouse nationalities over the years.

## Methodology
The project was developed using Python with the Streamlit framework for prototyping the dashboard. The primary data processing was done through data cleaining, inferencing, and reshaping using Pandas library. The visualizations were done using the Plotly Express library. The cleaned data was unpivotted (reshaping) into a long format to facilitate easier analysis and visualization. 

Key steps in the methodology included:
1. Dataset uploading of EXCEL(xlsx) file 
2. Dataset cleaning to make only relevant data is to be processed
3. Dataset reshaping into a long format (unpivotting) for processing
4. Dataset inferencing to make sure correct data type
5. Visualization with 3 Plots (Line Charts, Bar Chart and Pie Chart)
6. Deploying of the dashboard to the Internet using Streamlit

## Key Findings
- The data shows significant emigration patterns, with certain countries like the USA, Australia, Canada and Japan consistently being top Foreign National spouses from 1989 - 2020.
- There were dramatic decline in the total number of Spouses that started in 2019, which was in time when the COVID-19 hit globally.

## Visualizations
The dashboard includes interactive visualizations such as:
- A line chart showing the profile trend of spouse by major countries over the years
- A bar  chart showing the top 5 country of origins of spouse nationalities over the years
- A pie  chart showing the profile distribution of spouse nationality by major countries over the years

These visualizations allow users to drill down into specific countries and time periods to explore the data in detail.

## Code
The project's code is available in the following repository:
- [Foreign Spouse Nationality Dashboard](https://github.com/Junmiano/DEP/blob/main/README.md)

Streamlit App: You can explore the dashboard live at the following link:
- [Foreign Spouse Nationality Dashboard - Streamlit](https://foreign-spouse.streamlit.app/)

## Features
- Uploading of dataset for processing
- Automatic checking if the correct dataset is uploaded with error handling
- Automatic dataset cleaning by removing irrelevant data and filling out missing values
- Automatic dataset inferencing making sure correct data type
- Downloadable Cleaned and Reshaped Dataset
- Saving of the visualization to an HTML file for presentation
- Built-in functionality to take a screenshot of a chart
- Built-in zooming of the chart

## Challenges and Solutions
As a beginner in Python, I struggled how to do task at first. I started with doing CHOP methodology as it is fondly called as Chat Oriented Programming (CHOP) with an AI. I did a lot of prompting on how to do it step by step. Had I learned good prompting, it would not take time to get the Python code I need to develop the tool. I was able to do the dataset preparation for visualization and analysis by first uploading the dataset in to Pandas Dataframe then I extracted the relevant data, make sure there is no missing value and of the correct data type (Inferencing). The dataset was then reshaped (unpivotting) into a long format and assigned proper headers for the dataframe. The dataset is then ready for visualization and analysis. Lastly, with some google searches and watching YouTube video tutorials, I was able to deploy the dashboard to Streamlit.

## Community Impact
This dashboard provides a valuable tool for researchers, policymakers, and the general public to understand the trends, Distribution Spouse profiles by country of origin. It can inform policy decisions, aid in demographic studies, and raise awareness about migration patterns.

## Future Work
Potential next steps for this project include:
- Adding more related datasets to provide more context and related data.
- Adding more visualizations and insights
- Allow the user to upload the dataset
- Refactor some of the codes for fast loading
- Users feedback mechanism to help improve the service
- Add an AI for the user to interact with the dataset like to create the visualization or just ask anything about the data itself.
  
## Contributors
- Jun Miano

## License
This project is shared under the MIT License.

## Socials
- **LinkedIn:** [https://www.linkedin.com/in/junmiano1202/](https://www.linkedin.com/in/junmiano1202/)
- **GitHub:** [https://github.com/junmiano](https://github.com/junmiano)

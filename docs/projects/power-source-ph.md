---
title: "Power Generation by Fuel Source"
author: "Mark Diasanta"
date_created: 2025-07-20
last_updated: 2025-09-06
version: v1.0
status: "Completed" 
tags: 
  - electricity
  - renewable energy
  - philippines
data_sources:
  - Department of Energy
alignment: "This project supports DEP Data Hub’s mission by promoting data transparency and public access to historical energy data in the Philippines. It helps policymakers, investors, and the public understand long-term trends in power generation—from traditional to renewable sources. With this insight, stakeholders can make data-driven decisions in designing policies and energy projects that align with the country’s sustainable development goals."
---

# Power Generation by Fuel Source

*Note: To view the full metadata for this project, please see the raw file in our [GitHub repository](https://github.com/dataengineeringpilipinas/datahub/tree/main/projects).*

## Summary
This project explores the historical trends in power generation by fuel source in the Philippines from 1990 to 2020. It aims to provide a visual and data-driven information of how the country’s energy mix has evolved thru the years. By making this information accessible and easy to understand, the project empowers Filipino communities, investors, researchers, and policymakers to better assess energy sustainability, plan for future needs, and advocate for a just transition to cleaner energy.

## Methodology
This project was developed using Python to generate visual charts that make the data more understandable and easier to interpret. The primary data processing was done using pandas, while visualizations were created using Matplotlib. Additionally, Streamlit was used to build an interactive dashboard for enhanced user engagement.

Key steps in the methodology included:
  1.	Loading and cleaning the Fuel Source data
  2.	Creating visualizations to analyze trends and patterns  

## Key Findings
  1. Philippines is hugely reliant on Fossil Fuels specifically Coal which rise drastically on 2010s 
  2. Philippines shifted from being oil-heavy in the 90s to coal-heavy in 2000s-2020
  3. Little to slow growth of renewable energy sources since 1990.
  4. Renewable share declined from ~45% in the early 1990s to ~25% by 2020.

## Visualizations
Charts can be seen here: [Charts](https://github.com/markdiasanta/project-01-renewable-energy-philippines/tree/main/charts)
  1. Line Chart showing all fuel sources generation in the Philippines. 
  2. Stacked area Chart showin energy mix composition per year.
  3. Line Chart showing growhth per energy group in the Philippines.
  4. Line Chart showing % share of energy group in the Philippines

## Code
The project's code is available in the following repository:
- [PH-Power Energy Sources Repository](https://github.com/markdiasanta/project-01-renewable-energy-philippines)
- [Energy Source Analysis](https://github.com/markdiasanta/project-01-renewable-energy-philippines/blob/main/renewable_energy.py)

## Challenges and Solutions
One of the challenges faced was handling the raw data from the source, which contained commas within values and tab delimiters. This was addressed by specifying the appropriate delimiter when reading the file and removing or converting commas to ensure the CSV data could be processed correctly.

## Community Impact
This project makes the Philippines’ historical energy generation data more accessible and understandable.  
By providing visualizations of the energy mix (renewables vs. fossil fuels), it can:  
- Help policymakers design evidence-based energy strategies.  
- Inform investors about opportunities in renewable energy.  
- Raise awareness among communities about the country’s heavy reliance on coal and the urgency of transitioning to cleaner sources.  
- Support educators, students, and NGOs in using open data for advocacy and research.  

## Future Work
These are potential areas for improvement of this project:
- **Update with latest data**: Incorporate post-2020 data as soon as it’s available.  
- **Regional analysis**: Break down energy sources by island group (Luzon, Visayas, Mindanao).  
- **Interactive dashboards**: Expand with Streamlit for real-time exploration.  
- **Forecasting**: Use machine learning to predict future energy trends under different scenarios.  
- **Policy mapping**: Overlay major energy policies to see their effect on the mix.  

## Contributors
- Mark Diasanta

## Socials
- **LinkedIn:** [https://www.linkedin.com/in/mark-darell-diasanta/](https://www.linkedin.com/in/mark-darell-diasanta/)
- **GitHub:** [https://github.com/markdiasanta](https://github.com/markdiasanta)
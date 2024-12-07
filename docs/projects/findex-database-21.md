---
title: "🌐 Global Financial Inclusion 2021 Dashboard"
author: "jarcelao"
date_created: 2024-12-07
last_updated: 2024-12-07
version: v1.0
status: "Completed"
tags:
  - finance
  - inclusion
  - survey
  - global
  - dashboard
data_sources:
  - "Global Financial Inclusion (Global Findex) Database"
alignment: "Provides a data warehouse and visualizations of financial inclusion at a global scale."
---

# 🌐 Global Financial Inclusion 2021 Dashboard

*Note: To view the full metadata for this project, please see the raw file in our [GitHub repository](https://github.com/dataengineeringpilipinas/datahub/tree/main/projects).*

## Summary
A brief overview of the project. What does it aim to achieve? How does it contribute to community empowerment in the Philippines?

## Methodology
This project was built with the below technologies:

 - **DuckDB** - Portable DBMS designed for analytics. Serves as the data warehouse for this project along with hosting the ingestion functionality.
 - **dbt** - Data transformation tool for analytics. Used to transform the raw data into a format that can be easily consumed by the dashboard.
 - **Evidence** - Svelte-based framework for building data apps. Used to build the dashboard webapp.

 In addition, the dashboard is hosted on Cloudflare Pages to make it accessible to the public.

## Key Findings
- The Philippines ranks #72 in overall account ownership, with 62.7% of its population having a bank account or mobile money account.
- 64.5% of Filipinos saved money in 2021, putting their savings in traditional financial institutions (34.9%), informal savings clubs (34.9%), and mobile money accounts (19.5%).
- 54.7% of Filipinos have made a digital payment in 2021.

## Visualizations
https://findex21.pages.dev/

## Code
https://github.com/jarcelao/global-financial-inclusion

## Challenges and Solutions
This project underwent several iterations before taking on the shape it has now. A major reason for this is the effort needed to properly integrate the data sources. 

As noted in this [project's data source](../data-sources/global-financial-inclusion.md), the dataset is split into each iteration of the survey. Each iteration has a different set of questions, with similar questions being asked in different ways to account for trends in global financial inclusion. This makes it difficult to integrate the data into a single dataset, as each column in needs to be matched to the corresponding columns in the other iterations.

Thus, this project was downscoped to only include the 2021 iteration of the survey, which is the most recent iteration as of writing. This was done to avoid the complexity of integrating the other iterations, as well as to ensure that the data is relevant with current trends.

## Community Impact
Knowing how Filipinos handle their personal finances can help guide financial institutions in deciding how to best serve their customers. In addition, this project can also help policymakers in crafting measures that can help develop responsible finances in the country.

In addition, the data also provides us an opportunity to understand how our country is doing relative to other countries. This can help us identify what trends in financial inclusion we should be aware of, and how we can work towards this as a community.

## Future Work
The current biggest improvement that can be done to this project is to integrate the other iterations of the survey. A comprehensive effort would be needed to analyze each survey and determine how they all fit into one. This will allow us to determine trends over time, which can help us understand how our financial inclusion has evolved through the past years.

In addition, the dashboard currently serves as an ad-hoc exploration of the data from a high-level perspective. There are a variety of questions to ask and insights to be gained from the data, allowing a wealth of opportunities for several new projects to develop from this one.

## Contributors
Jericho Arcelao

## License
This project is shared under the MIT License.

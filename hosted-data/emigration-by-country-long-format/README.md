# Emigration by Country (1981-2022)

## Dataset Overview

This dataset contains detailed records of emigration from the Philippines to various countries from 1981 to 2022. The data includes the annual count of emigrants categorized by their destination country. It provides a comprehensive view of emigration trends over four decades, offering insights into the movement patterns of Filipino emigrants globally.

## Data Structure

The dataset is organized in a tabular format with the following columns:

- **Year**: The year of emigration (e.g., 1981, 1982, etc.).
- **Country**: The destination country of the emigrants (e.g., USA, Canada, Japan, etc.).
- **Emigrant Count**: The number of emigrants to the specified country for that year.

## Data Source and Cleaning Process

### Source

The original data was sourced from the file [Emigration-by-country-1981-2022.md](data-sources/Emigration-by-country-1981-2022.md). The dataset was cleaned and transformed using a Jupyter Notebook, which is available at [this GitHub repository](https://github.com/chrisformoso-ca/emigrant-country-dashboard/clean_data.ipynb).

### Cleaning and Transformation Steps

1. **Selection of Relevant Data**: The dataset was initially filtered to include only the relevant rows and columns, focusing on the years 1981 to 2022 and the major destination countries.

2. **Header Standardization**: The original headers, spread across multiple rows, were combined and cleaned to create meaningful and standardized column names.

3. **Reshaping the Data**: The data, originally in a wide format, was reshaped into a long format to make it more accessible and easier to analyze. This involved reorganizing the data so that each row represented a unique year-country-emigrant count combination.

4. **Data Type Conversion**: The 'Year' column was converted to a numeric format to ensure consistency, and the 'Emigrant Count' was ensured to be an integer. Missing values in the emigrant counts were filled with zeros to maintain data integrity.

5. **Final Validation and Export**: The cleaned and transformed dataset was thoroughly reviewed to ensure accuracy and was then exported to a new Excel file for easy access and further analysis.

## Usage and Limitations

### Usage

This dataset can be used for:

- Analyzing long-term emigration trends from the Philippines.
- Studying the impact of global events on migration patterns.
- Policy-making and planning by government and non-governmental organizations.

### Limitations

- **Data Gaps**: Some years may have incomplete data due to reporting issues.
- **Country Classification**: In some cases, country names may have changed or merged, and such instances have been standardized where possible.

## Metadata

- **Dataset Version**: 1.0
- **Last Updated**: August 2024
- **File Format**: XLSX
- **License**: [Specify License Here]

## Anonymization

No personally identifiable information (PII) is included in this dataset. The data has been aggregated to ensure privacy and compliance with data protection regulations.

## Accessing the Data

The dataset can be downloaded directly from the [hosted data directory](link to dataset).

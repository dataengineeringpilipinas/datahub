# Data Source Template

## How to Add a New Data Source

1. **Create File**: 
   - In this `data-sources` folder, create a new file named `your-data-source-name.md`

2. **Copy Template**: 
   - Copy the entire template provided at the bottom of this README

3. **Fill Details**: 
   - Paste the template into your new file
   - Replace all placeholders with information about your data source
   - Ensure all required fields are completed

4. **Submit**: 
   - Commit your file
   - Create a pull request with a brief description of the data source

---

## YAML Front Matter Fields Explanation

- `title`: The name of your data source
- `contributor`: Your name or the name of the person adding this data source
- `date_added`: The date this data source was added to DEP Data Hub (YYYY-MM-DD format)
- `last_updated`: The date of the most recent update to this entry (YYYY-MM-DD format)
- `version`: The current version of this data source entry (e.g., v1.0, v2.1)
- `source_organization`: The name of the organization that produced or maintains this data
- `time_period`: The time range covered by the data (e.g., "2010-2022", "2023-present")
- `update_frequency`: How often the data is updated (e.g., "Annual", "Monthly", "Real-time")
- `data_formats`: A list of formats in which the data is available
- `license`: The terms under which this data can be used
- `tags`: A list of relevant keywords (aim for 3-5 tags).
 
Remember to replace all placeholder text in both the YAML front matter and the Markdown sections with your actual data source information.

## Template

Copy the entire content below this line:

---

```
---
title: "Your Data Source Name"
contributor: "Your Name"
date_added: YYYY-MM-DD
last_updated: YYYY-MM-DD
version: v1.0
source_organization: "Organization Name"
time_period: "YYYY-YYYY"
update_frequency: "e.g., Annual, Monthly, Real-time"
data_formats:
  - "CSV"
  - "JSON"
  - "API"
license: "e.g., CC BY 4.0, Open Government License"
tags:
  - tag1
  - tag2
  - tag3
---

# [Your Data Source Name]

## Description
[Provide a brief description of the data source]

## Data Collection Methodology
[Explain how the data was collected]

## How to Access
[Provide instructions or links for accessing the data]

## Data Dictionary
[If applicable, provide a brief data dictionary or link to one]

## Relevance to Philippine Data Projects
[Explain how this data source could be valuable for projects related to the Philippines]

## Known Issues or Limitations
[Describe any known problems or constraints with the data]

## Related Projects
[List any DEP Data Hub projects that use this data source]

## Additional Resources
[Include any helpful links or references related to this data]
```

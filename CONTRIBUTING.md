# Contributing to DEP Data Hub

We're excited that you're interested in contributing to DEP Data Hub! This document outlines the process for contributing and our community guidelines.

## Repository Structure

Before contributing, it's important to understand the structure of our repository:

- `data-sources/`: A curated list of external data sources with links and descriptions. This directory helps users discover valuable datasets that are hosted elsewhere.
- `projects/`: Showcases data-driven projects and analyses. This is where we highlight how data can be used to drive insights and create impact.
- `hosted-data/`: Contains datasets directly hosted in this repository. We host select datasets to ensure their availability and to provide version control for data that's particularly relevant to our community.

## How to Contribute

### Adding a Data Source Entry

1. Fork this repository.
2. Create a new file in the `data-sources` directory using a descriptive name that reflects the content of the data source (e.g., `city-population-data.md` or `air-quality-index.md`).
3. Use the [data source template](docs/data-source-template.md) to structure your entry.
4. Ensure you include accurate information about how to access the data, its format, update frequency, and any usage restrictions.
5. Submit a pull request with a clear description of the addition.

### Submitting a Project Description

1. Fork this repository.
2. In the `projects` directory, create a new markdown file with a descriptive name for your project (e.g., `urban-heat-island-analysis.md`).
3. Use the [project template](docs/project-template.md) to structure your entry.
4. Provide a comprehensive overview of your project, including:
   - Project summary
   - Methodology
   - Key insights or findings
   - Links to data sources used (preferably referencing sources from our `data-sources` directory)
   - Link to the full project repository or website (if available)
5. Submit a pull request with a summary of your project.

### Contributing Hosted Data

1. Fork this repository.
2. Create a new subdirectory in the `hosted-data` directory with a descriptive name.
3. Include the following in your subdirectory:
   - Data files (CSV, JSON, etc.)
   - A README.md explaining the dataset, its structure, and any relevant metadata
   - Any related scripts used for data collection or preprocessing
4. Ensure you have the right to redistribute the data and clearly state the license.
5. Submit a pull request with details about the hosted dataset, including its relevance to the community.

### Improving Documentation

1. Fork this repository.
2. Make your changes, ensuring they are clear, concise, and improve the overall user experience.
3. Submit a pull request explaining the improvements and why they're beneficial.

## Best Practices

- Ensure all contributions are well-documented and follow consistent formatting.
- For data sources and hosted data, include information about data quality, update frequency, and any known limitations.
- When submitting projects, focus on reproducibility. Include code snippets or links to full code repositories when possible.
- Use clear, descriptive commit messages.

## Code of Conduct

By participating in this project, you agree to abide by our Code of Conduct:

1. Be respectful and inclusive of all contributors and users.
2. Focus on providing accurate, helpful, and constructive information.
3. Be open to feedback and willing to iterate on your contributions.
4. Do not share private or sensitive information.
5. Respect intellectual property rights and data usage agreements.

## Data Anonymization Requirement

To protect individual privacy and comply with data protection regulations, all contributed datasets must be properly anonymized before submission. This applies to both hosted data and data sources:

1. Remove all personally identifiable information (PII) such as names, addresses, phone numbers, email addresses, and social security numbers.
2. Aggregate or generalize sensitive demographic information to prevent individual identification.
3. Use data masking techniques for unique identifiers if they must be retained for analysis purposes.
4. Ensure that the combination of retained data points cannot lead to re-identification of individuals.
5. Document the anonymization process used in the dataset's README or metadata.

Contributors are responsible for ensuring their data submissions comply with relevant privacy laws and ethical standards. Our maintainers will review anonymization efforts during the pull request process, but the primary responsibility lies with the contributor.

## Review Process

All submissions will be reviewed by our maintainers. We may suggest changes or improvements before merging. Please be patient and open to feedback. Our goal is to ensure high-quality, valuable contributions to the DEP Data Hub.

## Getting Help

If you have any questions about how to contribute to the Data Hub:

1. Check our [FAQ](docs/FAQ.md) for common questions.
2. Open an issue for specific problems or suggestions.
3. Start a discussion in our [GitHub Discussions](link-to-discussions) for general queries or ideas.

We're here to help and appreciate your efforts to improve the DEP Data Hub!

Thank you for contributing to DEP Data Hub and helping us empower communities through data collaboration and innovation!

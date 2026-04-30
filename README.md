# Netflix Content Analysis

This project analyzes Netflix’s global content dataset to understand content growth, regional distribution, audience targeting, and platform strategy.

The analysis uses Python for data cleaning and exploration, then summarizes the findings through a dashboard and written business insights.

## Project Overview

Netflix has a large and diverse content library across countries, genres, release years, and audience ratings. This project explores that dataset to identify how Netflix content has grown over time, which countries contribute the most titles, and what type of audience the platform mainly targets.

The project includes a Jupyter Notebook, cleaned dataset, dashboard PDF, dashboard image, and written insights report.

## Dashboard Preview

![Netflix Dashboard](netflix.png)

## Dashboard File

The dashboard is also included as a PDF file in this repository:

```text
netflix_dashboard.pdf
```

## Files in This Repository

```text
netflix.ipynb              Jupyter Notebook for data cleaning, analysis, and visualization
netflix_cleaned (1).csv    Cleaned Netflix dataset used for analysis
netflix_dashboard.pdf      Dashboard summary of the analysis
netflix.png                Dashboard preview image
Insights.md                Written business insights and recommendations
README.md                  Project documentation
```

## Objectives

- Analyze Netflix content growth over time.
- Study geographical distribution of Netflix titles.
- Understand audience targeting through content ratings.
- Identify major countries contributing to Netflix’s catalog.
- Create a dashboard summary for business interpretation.
- Convert raw content data into structured insights.

## Dataset

The project uses the Netflix Titles Dataset in CSV format.

Key columns used:

- `title`
- `country`
- `release_year`
- `date_added`
- `rating`
- `duration`
- `listed_in`

The dataset was cleaned and prepared for trend analysis, country-level analysis, rating distribution, and dashboard creation.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- IBM Cognos Analytics
- CSV data analysis
- Dashboard reporting

## Methodology

### Data Cleaning

- Handled missing values.
- Processed categorical columns.
- Converted date fields into usable date formats.
- Standardized column formats.
- Prepared country, rating, and year-based fields for analysis.

### Data Preparation

- Extracted year from `date_added`.
- Aggregated content counts by year.
- Processed country data for geographical analysis.
- Grouped content by rating for audience segmentation.
- Prepared cleaned data for dashboard development.

### Dashboard Development

The dashboard includes:

- Global content distribution map
- Content distribution by rating
- Netflix content growth over time
- Business-focused visual summary

## Key Insights

### Content Growth Trends

Netflix content increased significantly after 2016, with peak content addition around 2019-2020. A slight decline after 2020 suggests a possible shift from rapid expansion toward more selective content strategy.

### Geographical Distribution

The United States, India, and the United Kingdom contribute a large share of Netflix content. This shows Netflix’s strong dependence on established content markets.

### Audience Targeting

Most Netflix titles fall under mature audience categories such as TV-MA and TV-14. This suggests that Netflix primarily targets adult and teen audiences.

### Business Interpretation

Netflix’s catalog strategy appears focused on mature content and major content-producing countries. Future opportunities may exist in expanding family-friendly content and improving regional diversity.

## Recommendations

- Expand content production in emerging markets.
- Increase investment in children and family-friendly content.
- Balance mature content with broader audience categories.
- Continue monitoring content growth after peak expansion years.
- Use regional content gaps to guide future catalog strategy.

## How to Use This Project

Clone the repository:

```bash
git clone https://github.com/aishidutta13/Netflix-Content-Analysis.git
cd Netflix-Content-Analysis
```

Open the notebook:

```text
netflix.ipynb
```

Run the notebook cells in order to view the data cleaning and analysis workflow.

Open the dashboard file:

```text
netflix_dashboard.pdf
```

Read the insights file:

```text
Insights.md
```

## Possible Improvements

- Rename the cleaned dataset to `netflix_cleaned.csv`.
- Add more visualizations inside the notebook.
- Include predictive analysis for future content growth.
- Add genre-level and country-level deep dives.
- Create an interactive dashboard using Streamlit or Plotly.

## Conclusion

This project demonstrates how data analysis can be used to understand Netflix’s content strategy. The findings show strong content growth after 2016, concentration in major content-producing countries, and a focus on mature audience categories.

## Author

Aishi Dutta

GitHub: [aishidutta13](https://github.com/aishidutta13)

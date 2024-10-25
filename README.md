## Project Details

> This project was completed as part of Udacity's Data Analyst Nanodegree program. The objective of this project was to analyze gun background check data in the United States using Python data visualization and statistical libraries. The analysis focused on understanding trends in gun background checks and their relationship with demographic variables from the US Census.

> The project began with data wrangling and cleaning of two datasets—the FBI's National Instant Criminal Background Check System (NICS) data and demographic data from the US Census Bureau. The analysis aimed to investigate correlations between the rate of background checks and various demographic factors, such as race, income, and education level.

## Dataset

> The analysis was conducted using two primary datasets:
> - **FBI NICS Data**: Contains information on gun background checks from 1998 to 2017. This data was sourced from the FBI and parsed from the Buzzfeed News GitHub repository.
> - **US Census Data**: Contains demographic information such as population estimates, age, race, income, and education for each state from 2010 to 2016. This dataset was provided by Udacity.

> Link to the NICS dataset: [Buzzfeed News GitHub repository](https://github.com/BuzzFeedNews/nics-firearm-background-checks)

## Summary of Findings

> After analyzing the data, several key insights were obtained:
> - **Trend in Background Checks**: There was a noticeable increase in firearm background checks over time, particularly from 2010 to 2016. This increase could be attributed to factors such as population growth and policy changes regarding gun regulations.
> - **Top States for Background Checks**: Kentucky showed the highest per capita background check rate compared to all other states, both in 2010 and 2016.
> - **Correlation with Demographic Factors**: A weak positive correlation was found between the proportion of veterans and background checks per capita, whereas a weak negative correlation was observed for states with a higher proportion of college graduates and immigrants.

> These findings were presented using line charts, bar plots, and scatter plots to highlight trends and correlations in the data.

## Key Insights for Presentation

> The visualizations in the presentation were chosen to clearly illustrate key insights about the trend in gun background checks over time and their association with demographic factors. The line charts effectively showed the overall increase in background checks, while scatter plots highlighted correlations between various demographic attributes and the rate of background checks.

## Files

- `FBI_Gun_Data_Analysis.ipynb`: Jupyter Notebook containing the entire data wrangling, analysis, and visualization process.
- `cleaned_data.csv`: Cleaned dataset used for analysis.
- `FBI_Gun_Data_Presentation.pdf`: A presentation summarizing the key findings and insights from the analysis.

## How to Use

To explore this project, clone the repository and open the Jupyter Notebook (`FBI_Gun_Data_Analysis.ipynb`) to see the complete data analysis process. The cleaned dataset (`cleaned_data.csv`) can be used to reproduce the analysis or conduct further research.

## Requirements

The following Python libraries were used in this project:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

To install the required libraries, run:

```sh
pip install -r requirements.txt
```

## Acknowledgments

- Udacity: For providing the project and guiding the data wrangling and analysis process.

- Buzzfeed News: For providing access to the NICS dataset.

- US Census Bureau: For providing the demographic data used in this analysis.

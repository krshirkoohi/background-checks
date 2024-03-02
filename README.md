# Exploratory Data Analysis in SQL and Python

This project involves working with three tables from a larger, unseen dataset, data wrangling with SQL and Pandas and Exploratory Data Analysis. The findings are visualised using Seaborn and MatPlotLib and the final result is a PowerPoint presentation with the figures and an interpretation. 

## The Scenario
The recruitment team completes background checks every month to surface criminal records of candidates before they move to the interview round. They want to understand how many candidates failed the background check over the last year, and if there are any trends. They also want to learn how many background checks are completed each month and if there are any trends visible in the data. We are tasked with preparing a slide that summarises the findings which can be imported to a PowerPoint presentation.

Using SQL, we extract three tables from the primary dataset. Table 1 gives an overview of all failed checks in the last year. Table 2 lists the number of checks completed in every given month in the previous year. Table 3 provides location data for the candidates.

## Files
The main file is _BackgroundChecks.ipynb._ The finished result is _BackgroundChecks.pptx_.

The data used in this project is found in the following files (paths may need to be re-adjusted in the Jupyter Notebook if running on own device)
- Failed Background Checks.csv (Table 1)
- Total Background Checks Actioned (Table 2)
- Actioner Locations.csv (Table 3)

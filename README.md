Data Analysis Project README
## Project Overview

The purpose of this data analysis project is to examine and gain insights from a dataset related to the effect of different drug regimens on the tumor volumes of mice. The primary objectives are to:

- Merge multiple datasets into a single DataFrame.
- Identify and handle duplicate mice data.
- Calculate summary statistics for each drug regimen, including mean, median, variance, standard deviation, and standard error of the mean (SEM).
- Create informative bar charts and pie charts to visualize data.
- Determine quartiles, find outliers, and generate box plots for the distribution of final tumor volumes.
- Create line plots and scatter plots to visualize the relationships between variables.
- Calculate the correlation coefficient and regression model for mouse weight and tumor volume within the Capomulin regimen.

## Data Preparation

### Merging Datasets

The datasets were merged into a single DataFrame using the Pandas library. Here's an example of the process:

## Handling Duplicate Mice

- Duplicate mice were identified based on their unique identifiers, "Mouse ID" and "Timepoint."
- Duplicates were removed to create a clean DataFrame.

## Summary Statistics

- Summary statistics were calculated for each drug regimen using Pandas and Numpy libraries.

## Bar Charts and Pie Charts

### Total Timepoints by Drug Regimen

- To visualize the total number of timepoints for each drug regimen, bar plots were created using both Pandas and Matplotlib.

### Gender Distribution

- Pie charts were generated to display the distribution of female versus male mice, both using Pandas and Matplotlib.

## Quartiles, Outliers, and Box Plots

### Last Timepoint per Mouse

- A DataFrame with the last timepoint for each mouse ID was created using groupby, and the maximum timepoint for each mouse was retrieved.

### Outlier Detection

- Outliers for each treatment group (e.g., Capomulin, Ramicane, Infubinol, and Ceftamin) were identified by calculating the interquartile range (IQR) and comparing data points.

### Box Plot

- Box plots were generated to visualize the distribution of the final tumor volume for all mice in each treatment group.

## Line Plot and Scatter Plot

### Tumor Volume vs. Time Point

- A line plot was created to show the tumor volume vs. time point for one mouse treated with Capomulin.

### Tumor Volume vs. Mouse Weight

- A scatter plot was generated to display the relationship between average tumor volume and mouse weight for the Capomulin regimen.

## Correlation and Regression

- The correlation coefficient and a linear regression model were calculated to analyze the relationship between mouse weight and average tumor volume within the Capomulin regimen.

## Conclusion

- Provide a concise summary of your findings and any insights gained from your data analysis.










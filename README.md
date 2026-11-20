# US Firearm Background Checks Analysis

### Project Overview

This project analyzes FBI National Instant Criminal Background Check System (NICS) data alongside U.S. Census data to explore historical trends in background checks and their relationship with demographic and economic characteristics across U.S. states.

The analysis was completed as part of Udacity’s Investigate a Dataset project.

### Research Questions
How did NICS background checks change between 1999 and 2016?
Do states with larger populations have higher background check rates per capita?
Is median household income associated with background check rates?
How are poverty rates associated with background check rates?
Datasets
FBI NICS Background Checks: Monthly background check transactions by state and category.
U.S. Census Data: Population, median household income, and poverty indicators.

The cross-sectional analysis covers the 50 U.S. states for 2016.

### Tools and Libraries

Python
Pandas
Matplotlib
Jupyter Notebook


### Methodology
The project covers data inspection, cleaning, aggregation, exploratory data analysis, and visualization.
To compare states of different population sizes, NICS checks per 1,000 residents were calculated.
The analysis includes univariate distributions, historical trends, scatter plots, Pearson 
correlations, and a sensitivity analysis excluding Kentucky.

### Key Findings
Annual NICS background check transactions rose from approximately 9.04 million in 1999 to 27.43 million in 2016.
Population showed a very weak negative correlation with background check rates (r = -0.103).
Median household income showed a weak negative correlation (r = -0.264).
Poverty showed a weak positive correlation (r = 0.260).
Kentucky had an unusually high background check rate, largely driven by permit-related transactions.
Excluding Kentucky changed some of the correlation estimates.

### Limitations
NICS background checks do not directly measure firearm purchases or ownership.
Some Census indicators refer to reference periods that differ from the 2016 NICS data.
Kentucky’s unusually high volume of permit-related checks affects state comparisons.
The observed correlations do not establish causal relationships.
### Future Improvements
Improve scatter plot readability using logarithmic scales.
Explore additional years and background check categories.
Investigate differences in state reporting practices.

### Project Structure
firearm_background_checks_analysis.ipynb — Main analysis notebook
firearm_background_checks_analysis.html — Rendered report

###Acknowledgment
Developed as part of Udacity’s Data Analysis coursework.

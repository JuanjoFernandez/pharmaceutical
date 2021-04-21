![Pharmaceutical Data Analysis](images/header.jpg)

# **Changelog**

### *04/14/2021*
- Created readme
- Calculations on [pymaceuticals_starter.ipynb](pymaceuticals_starter.ipynb)
- Checked mouse_metadata for duplicated ID's none found
- Found some duplicated data for the tests results
- Found and displayed the duplicated data
    - Only one mouse is duplicated and only for some timepoints
    - Tumor size differs slightly, probably was measured by 2 scientists, will keep the last value
- Dropped the duplicated data
- Added header to readme

### *04/15/2021*
- Updated comments
- Tumor volume statistics table

### *04/16/2021*
- Fixed SEM, now it is computed using Scipy
- Tumor volume table repeated using aggregate method

### *04/19/2021*
- Plotted measurements by drug regimen using both pandas and pyplot
- Pie chart of mouse sex distribution using both pandas and pyplot
- Created new table with final tumor volume
- Determined outliers by quantitative method

### *04/20/2021*
- Created dictionary for box & whisker plots
- Box & whisker plots done
- Line plot per Mouse ID for Capomulin Regimen
- Scatter plot for Tumor Volume Average vs Mouse Weight
- Linear regression model
- Summary & Insights

### *04/21/2021*
- Fixed typos in the summary & insights
- Moved the changelog to a new file to reformat readme
# What this is?
This repository contains a report on traffic flow as an early indicator for GDP as well as the code, visualisations and data that used to create this report.

The data used in the report is entirely within the public domain. Souces are contained within the report notebook

# The Report

This is in a jupyter notebook: Report - Annual average daily traffic flow (AADF) as a correlate for GDP growth-Final.ipynb.

The notebook is running on mybinder.org which has the neccessary interactions to fully see the visualisations. Lanch the notebook using the link below (this can take a bit of time to load)

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/ONSBigData/traffic_as_early_indicator/master)

# Data processing
In addition to this notebook, there is a second: Dataset creation - Data for report.ipynb detailling the steps
used to create the datasets used in the report. The stats_unmelted.csv is missing from this as it is too large to be uploaded to github, thus this notebook will not run correctly. If you wish to see this dataset, please contact the author.

# Structure
This contains several folders
- data : Contains the datasets used in the analysis, each file is used in a different visualisation, you can see which ones are used for which in the notebook code
- figures: .html copies of the visualisations in the notebook
- scripts: python code called by the notebook to process and analyse
the data and create the visualisations
- docs: Contains sphinx generated documentation

## Contact
Dr Edward Rowland

Big Data - Office for National Statistics

**email:** edward.rowland@ons.gov.uk
**phone:** 01633 455712

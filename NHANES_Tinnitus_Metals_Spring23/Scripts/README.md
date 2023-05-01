### Scripts

========================

This folder contains all R scripts and R Markdown files used.

The original versions of these scripts predates the current project, however the most up to date versions are kept here for reference and use.

Current analyses are in zinc_copper_analysis.Rmd, and data cleaning is in zinc_copper_processing.Rmd.

In broad strokes, the processing script reads in the raw data and wrangles it into a final form that is used in all analyses (that output data can be found in the Data folder up one level).
The analysis script reads in that final output data file and then uses it for a series of statistical tests and graphs. Additionally, that is where the complex survey design is implemented.


See comments within those documents for more details on individual steps in either process.

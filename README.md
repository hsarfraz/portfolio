# Table of Contents

* [How to publish a R markdown on cloud connect](#how-to-publish-a-r-markdown-on-cloud-connect)

# Project description

To access the published version of the report on posit cloud connect please [click here](https://019fc91a-32f4-c30e-96a0-c1bf1a54ac28.share.connect.posit.cloud/) (use ctrl+click to open the link in another tab)

This project investigated whether age category, sex, and comorbidity status were associated with the presence of COVID-19 symptoms among people with multiple sclerosis (PwMS). A secondary analysis was conducted on a publicly available dataset containing 1,141 participants. Pearson's chi-square tests of independence were used to examine the association between each patient characteristic and COVID-19 symptom status (yes/no). No statistically significant associations were identified between age category, sex, comorbidity status, and the presence of COVID-19 symptoms.

To support the analysis, proportion tables, contingency tables, and bar charts were generated to summarise the distribution of the variables and visualise relationships between participant characteristics and COVID-19 symptom status. The project was developed as a fully reproducible R Markdown workflow, with the dataset downloaded automatically from GitHub to eliminate manual file handling and working directory configuration.

A key limitation identified during the analysis was that the outcome variable only recorded whether participants experienced any COVID-19 symptoms (yes/no). Future analyses could investigate individual COVID-19 symptoms separately, as previous research suggests that patient characteristics may be associated with specific symptoms rather than overall symptom status.

**Skills demonstrated**

* Data acquisition from GitHub using R
* Data cleaning and subsetting with `dplyr`
* Missing data assessment
* Descriptive statistics (frequency and proportion tables)
* Contingency table generation
* Pearson's chi-square tests of independence
* Data visualisation with `ggplot2`
* Reproducible analysis using R Markdown
* Critical interpretation of statistical results through comparison with published literature

**New skills developed**

* Reading and critically evaluating academic literature to place statistical findings within the context of existing research.
* Designing a reproducible analytical workflow by automatically downloading the dataset from GitHub instead of relying on manually downloaded files and local working directories.


# How to publish a R markdown on cloud connect

I published my R markdown file on [posit cloud connect](https://connect.posit.cloud/) since R pubs is being taken down on June 2027. Now when I was publishing my R markdown file on posit cloud connect I faced an error which said that my `manifest.json` couldn't be found. I wanted to document my journey in creating the `manifest.json` file since it required me to read through the posit cloud connect documentation.

1. Run `install.packages("rsconnect")` on your R studio console
2. Set your working directory to where your R markdown file is saved by running `setwd("INPUT_WORKING_DIRECTORY_HERE")`
3. Run `rsconnect::writeManifest()`
4. Your `manifest.json` should be created and will be in the folder that contains your R markdown file
5. Copy your .rmd file and manifest.json on your github directory and upload your file via github

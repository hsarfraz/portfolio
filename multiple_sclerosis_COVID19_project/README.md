# Table of Contents

* [How to publish a R markdown on cloud connect](#how-to-publish-a-r-markdown-on-cloud-connect)

# Project description



# How to publish a R markdown on cloud connect

I published my R markdown file on [posit cloud connect](https://connect.posit.cloud/) since R pubs is being taken down on June 2027. Now when I was publishing my R markdown file on posit cloud connect I faced an error which said that my `manifest.json` couldn't be found. I wanted to document my journey in creating the `manifest.json` file since it required me to read through the posit cloud connect documentation.

1. Run `install.packages("rsconnect")` on your R studio console
2. Set your working directory to where your R markdown file is saved by running `setwd("INPUT_WORKING_DIRECTORY_HERE")`
3. Run `rsconnect::writeManifest()`
4. Your `manifest.json` should be created and will be in the folder that contains your R markdown file

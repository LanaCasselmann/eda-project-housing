# EDA Project - Analysis Housing Data

## Description

### Disclaimer
This is the very first data analysis I do on my own, I appreciate any comment or suggestion for improvement.

### Project
This project has been created based on the assignment and template of the neuefische repository [ds-eda-project-template](https://github.com/neuefische/ds-eda-project-template/blob/main/assignment.md). It contains the analysis of actual housing data of King County, WA, centered around the wishes of an imaginary client, and the presentation of the results thereof. 

## Requirements

- pyenv
- python==3.9.8

## Setup

### Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. You can create a virtual environment with the requirements by running the following commands:

```
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### Data Sources

The data set was provided in the course of the exercise. However, it can be obtained via [kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction), as well. Keep in mind that the kaggle data set differs slightly from the one used.
Information on the data columns was provided in the [column_names.md](column_names.md), further information can be found on kaggle and additionally 
on the site for [King County building standards](https://info.kingcounty.gov/assessor/esales/Glossary.aspx)
Information on the population of King County, based upon the 2010 census, was taken from [usa.com](http://www.usa.com/rank/king-county-wa--population-density--zip-code-rank.htm?yr=9000&dis=&wist=&plow=&phigh=).
The file containing school data for King County was retrieved from [King County GIS Open Data](https://gis-kingcounty.opendata.arcgis.com/datasets/kingcounty::school-sites-in-king-county-schsite-point/explore?location=47.503391%2C-122.188658%2C10.00)

For the geographical chart, we used the shape file for the zip code areas of the state of Washington, found on [github](https://raw.githubusercontent.com/OpenDataDE/State-zip-code-GeoJSON/master/wa_washington_zip_codes_geo.min.json). We used that data as is, without warranty for correctness of the boundary coordinates.

## The Analysis

The Analysis is contained in the Jupyter notebook [EDA](EDA.ipynb). It contains a general analysis of the data as well as an analysis based on the specific needs of our imaginary client Larry Sanders, whose needs have been reported as "Buyer, Waterfront, limited budget, nice & isolated but central neighborhood without kids (but got some of his own, just doesn't want his kids to play with other kids .. because of germs)".

The notebook is structured as follows:

* Set up - Importing necessary libraries and the data
* Examination of the Data
* Data Cleaning
* Research Questions and Hypothesis Generation
* Investigation of Hypotheses
* Assumptions for our Client
* Additional Data for Client Analysis
* A Wish Function for our Client
* Recommendation for our Client

## The Presentation

We presented our findings to the group, using presentation slides. They can be found in the file [EDA_project_housing_Lana.pdf](EDA_project_housing_Lana.pdf).
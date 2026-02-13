# National Risk Index in California Counties

## Author: Kylie Newcomer

### Date Published: 2/12/2026

## Overview
This repository contains the materials for visualizing FEMA National Risk Index (NRI) data homework assignment for *EDS 240 - Data Visualization & Communication*. Materials for this assignment can be found on the [course website](https://eds-240-data-viz.github.io/). This project aims to visualize the risk index of counties in California versus across the United States.

## Data
### NRI
Data for this project comes from [FEMA](https://www.fema.gov/flood-maps/products-tools/national-risk-index) National Risk Index from the Resilience Analysis & Planning Tool. NRI score predicts the risk loss and resilience of communities based on various environmental disasters. Risk is calculated with the follow equation: 

$$Risk = Expected Annual Loss * Community Risk Factor$$ 

$$Community Risk Factor = f(Social Vulnerability / Community Resilience)$$ 

Data can be accessed [here](https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/).

### ACS
Racial and ethinic group data comes from [US Census Bureau’s American Community Survey](https://www.census.gov/programs-surveys/acs/about.html). Data was accessed through an API with the `tidycensus` package.

References 
United States, Federal Emergency Management Agency. "National Risk Index for Natural Hazards." FEMA.gov, [1/29/2026], www.fema.gov/nri. 

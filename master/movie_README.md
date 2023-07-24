# Microsoft Movie Analysis

**Author**: Dominic Njue

## Overview

Analysis the current trends in the film industry and identify the types of films that are performing well at the box office with a view to creating a new Movie studio for Microsoft. This is done by identifying the most viewed movies for successful investment and comparing genres with ratings and genres against gross revenue.
 

## Business Problem

For successful investment, Micrsoft seeks to understand what types of films are currently doing the best at the box office and which genres generate more revenue than others.



***

## Data
The data is scraped from IMDB (Internet Movie Database) containing the top 1000 movies in the box office. The data includes gross revenue from the production, movie rating and genre. The fields Run Time, Metascore, Votes and Gross had to be converted into a float type for analysis, and null or missing values were dropped from the dataset.


***

## Methods
Exploratory data analysis  and correlation analysis were used to examnine the relationship between the variables.


## Results


The Drama category has the highest number of rating and conversely has the highest gross revenue. The mystery/thriller category seemingly present a bad movie investment.


***

***



## Conclusions

The Movies studio should consider Drama,Action adventure as the point of entry. This can be mixed Comedy.

Future Steps:
Include analysis with datasets from other sources. Eg Rotten Tomatoes, Box office Mojo.






## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── master                              <- Folder containing README for reviewers of this project
├── index.ipynb                         <- Narrative documentation of analysis in Jupyter notebook
├── DS Phase 1 Project Presentation.pdf <- PDF version of project presentation
├── data                                <- Sourced externally and generated from code
└── images                              <- Images sourced from internet and generated from code
```

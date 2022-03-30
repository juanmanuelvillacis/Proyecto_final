# Proyecto_final

## Overview

The objective of this project is to apply unsupervised machine learning clusterization to metrics related to the Sustainable Development Goals (SDG) set by the united nations (UN) to be achieved until 2030, between countries. With the clusterization, attributes in common will be stand out so the countries can be identify between each cluster.
The next steps where taken in order to proceed to the conclusions:
  * Extract relevant data from the world bank data page
  * Match data with ODS # objective 
  * Filter the null data
  * Interpolate the remain data to complete a 10 years range information for each country/series
  * Standarize the information so it could be sumarized and analize by the clusterization model 
  * Prepare the data to feed the model frame
  * Identify the clusterization 
  * Measure and fit to the best model
  * Graphic the info in a world map for beter understanding

## Technical Details

A map showing the indicators and it's respective cluster was made using tableau public, you can find it [here](https://public.tableau.com/views/ODS_FinalProject/Story1?:language=pt-BR&:display_count=n&:origin=viz_share_link)

## Data Source

The main data source came from the world bank data bank https://databank.worldbank.org/
For this project a total of 262 countries with 401 metrics each and a time rnage of 10 years was used.

## Important Details
Further research could be analyse by determin wich country is apporting the most to the SDG goals in general. First, it should be analize witch indicator apports positive or negative values to the assinged SDG goal and then label a score for adding to the rest of the goals

# Case-studies-in-data-analytics - Multi-Source Open Data Quality

The objective of the project is to create a SINGLE COMPLETE AND CLEAN DATASET of playing pitches around Dublin region. The resulting 
dataset should be a csv file containing as much informative columns as possible. 

## Input datasets:
Dataset are available on https://data.gov.ie
- [DCC] Playing pitches in Dublin City Council: https://data.gov.ie/dataset/dublin-citycouncil-parks-playing-pitches
- [DLR] Playing pitches in DLR: https://data.gov.ie/dataset/dlr_pitches
- [F] Playing Pitches in Fingal: https://data.gov.ie/dataset/playing-pitches

## Data format:
Each of these datasets exhibits resources using various format: csv, xml, kml, html, etc. You should use at least 2 different formats (you will need to manage 3 files with at least 2 different formats).

## Data set taken for the assignment:
[DCC] Playing pitches in Dublin City Council - CSV format.
[DLR] Playing pitches in DLR - CSV format.
[F] Playing Pitches in Fingal - XML format.

## Additional Dataset:
OSiPNG dataset to identify geographical coordinates for some of the locations in other datasets - CSV format.

## Methodology:

Step1: Observation. Perform an observatory analysis of the datasets and define a data management plan for creating the resulting dataset.

Step 2: Data modelling: Create a unified model that should include the resulting fields of each record in your dataset. The minimal fields required are: location, and geographical coordinates (use x and y).

Step 3: Data Quality Enhancement: You will be faced with two main challenges:

1. Data cleaning challenge: Merge the input resource and make sure that there are no duplicates, Locations can be created by merging various fields, etc.
  
2. Incomplete data challenge: The first dataset [DCC] does not have any geographical coordinates. A solution to complete this information is required.

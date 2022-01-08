## Project DATLAS

This project was developed under 24 hours for the hackaton HackMTY 2020. 

In this project, we followed the CRISP-DM methodology (as it is the leading standard for the implementation of data science projects across the industry) from beginning to end with the purpose of gaining insight on how and where traffic accidents happen in Nuevo Leon. This repository contains several jupyter notebooks and datasets that were developed to deepen the current knowledge on how are traffic accidents generated and then make predictions to avoid these accidents.

Datlas provided the team with a dataset with fundamental information on the location and the characteristic of the traffic incidents. However, we explored the effects of the weather conditions and the distinct characteristic of different kinds of roads to better understand and explain what are the factors that cause and accident.

The developed jupyter notebooks are the following:
  - preprocess_nb.ipynb
    * Database cleaning and the addition of the weather characteristics per zones and per day.
  - Clustering.ipynb
    * Clustering for data exploration
  - OpenStreetMapsAPI.ipnyb
    * Data enrichment with geohashing and road conditions given by the OpenStreetMaps API
   - union.ipynb
    * Unification of the different datasets

And also the databases used and generated can be found in this git.


## Authors 

Ramón Díaz Ramos

Daniela Gómez Cravioto

Michael Zenkl Galaz

Jorge Ayala 

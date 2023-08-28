# R Scripts: List and Description
MSc Thesis: Modelling Bicycle Ridership using Crowdsourced Data in the Urban Area of Zurich
#### Preparation
*counting stations.rmd*: Pre-processing of counts of official counting stations
*Strava_data.rmd*: Load the Strava raw data
*studyarea.rmd*: Define convex hull of perimeter
#### Network
*network.rmd*: Post-Processing of Network Matching & Correction, and the code used to try out and test network matching variants
*network_clean.rmd*: Network Matching. Computed on external Linux server
*network_correct.rmd*: Network Count Correction. Computed on external Linux server
#### General
*regression_strava.rmd*: Link the geo variables to AV Network. Compute GLM Strava Counts explained by geo variables.
*stations_ols.rmd*: Filter the station counts, link them with geo variables (network). Compute proportion and correlation. Try out different models, distributions, transformations..
#### Geo Variables
*geo_vars.rmd*: Slope, max. Speed, Distance to POI and Swiss Neighbourhood Index
*arealstatistik_bfs.rmd*: Distance to green space & residential area, mixed land use, population density, % of 80+ year olds
*unfallstat.rmd*: Accident Exposure
#### Lasso
*lasso.rmd*: Lasso Variable Selection 
#### GLMMs
*glm2_clean.rmd*: Run single iterations of the GLMMs and visualise results
*glm2_final.rmd*: Run the cross-validations of GLMM 1 and GLMM 2


	

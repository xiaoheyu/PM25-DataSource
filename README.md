
# Project Overview 
#### Please cite and refer to the following paper for details.
## PM2.5 Modeling and Historical Reconstruction over the Continental USA Utilizing GOES-16 AOD https://doi.org/10.3390/rs13234788 
#### There are 4 stages for the entire project.
#### Stage 1 (Code available in repo PM25-DataSource): Data download and visulization, including ECMWF, PBLH, GOES16-AOD, Landcover, Soil order, Population density, Elevation, and Lithology.
#### Stage 2 (Code available in repo PM25-DataMaching): Once data are downloaded, all variables will be macthed with PM2.5 groupd observation. A macthed data table is generated for machine learning model training.
#### Stage 3 (): Machine learning moldeing training
#### Stage 4 (Code available in repo PM25-Estimation-Reconstrcution or PM25-Estimation-Reconstrcution-Local ): Once model and data are ready, this code make pm25 estimations and generate visulization results.

# Stage 1: PM25-DataSource
## Please cite the paper if using the code
Jupyer notebooks in this repo are used to download and visualize the data used for PM2.5 modeling in the paper.
##### AQS_PM25.ipynb is for AQS houlry averaged PM2.5 dowload from more than 800 monityoring stations across US.
##### GOES16AOD.ipynb is for GOES16-AOD product download and visulization from AWS.
##### ECMWF_ERA5.ipynb is for meterological variables and boundary layer hight download and visulization from ECMWF.
##### Ancillary_Dataset.ipynb is for ancillary dataset download and visulization, inclduing landcover type, population density, soil order, elevation, and lithology type.
##### goes.yml contains python librayies used in this project.


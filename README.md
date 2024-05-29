# BikeSharing Case Study
> The aim is to model the demand for shared bikes with the available independent variables. This is a linear regression model building project, aimed at applying the concepts learned as part of Upgrad AI/ML program, Course 2: Machine Learning 1.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
  - This project deals with EDA followed by building the multiple linear regression model for the bike sharing demand for US bike-sharing provider BoomBikes.
- What is the business problem that your project is trying to solve?
  - Study the demand for bike sharing in US post COVID-19 pandemic.
  - To figure out the various factors that could drive the demand.
- What is the dataset that is being used?
  - The dataset being used is a bike sharing data-set which contains the daily bike sharing details for the years 2018 and 2019, as provided by Upgrad, the copy of this data set has been added to this repo as well by the name "day.csv"

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The top 3 features that would affect the demand:
  - atemp
  - rain (-vely) (derived from weathersit, where weathersit=3)
  - yr
- The best fit model is given by equation: y = 0.20 + 0.24 * yr + 0.04 * workingday + 0.40 * atemp - 0.17 * spring - 0.27 * rain + 0.06 * Monday + 0.07 * September
- R-Squared for Train: .785
- R-Squared for Test: .799

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
jupyter notebook - version 7.0.8
pandas - version 2.2.1
numpy - version 1.26.4
matplotlib - version 3.8.0
seaborn - version 0.13.2
python - version 3.11.8
statsmodels - version 0.14.0
sklearn - version 2.2.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Upgrad lectures were frequently visited for syntax and understanding to write code in jupyter notebook.

## Contact
Created by [Apoorv Jain @apoorvjain1] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

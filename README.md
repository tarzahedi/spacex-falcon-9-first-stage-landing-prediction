# SpaceX  Falcon 9 first stage Landing Prediction


This Project is about predicting the successful landing of SpaceX Falcon 9 first
 stage.

SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62
 million dollars; other providers cost upward of 165 million dollars each,
  much of the savings is because SpaceX can reuse the first stage. Therefore
  if we can determine if the first stage will land, we can determine the cost
 of a launch. This information can be used if an alternate company wants to
  bid against SpaceX for a rocket launch.

The following is an example of a successful and launch.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/api/Images/landing\_1.gif)

The repository contains all the codes and Jupiter notebooks for the final
 machine learning specialist training project, "Python Basics for Data Science".
  You can find all the solutions in notebook format here, including all
 the necessary steps like data collection (scraping), EDA, data analysis,
  visualizations, model training, and prediction for a typical Machine learning project.

## Data

All datasets can be downloaded or scraped by running the notebooks
or scripts provided in the repository.

## Setup

### Requirements

The repository uses Python3 to run the code. You can find all the necessary packages
inside the `requirements.txt` file.

It is recommended to use [virtualenv](http://virtualenv.readthedocs.org/en/latest/installation.html)
to install and run the codes. After activating the `virtualenv` you can run the following
command in your terminal to install all the required packages:

```shell
pip3 install -r requirements.txt
```

### Running the code

Use the following commands to run the interactive notebooks:

```shell
jupyter notebook
```

## Steps

Steps conducted in the projects are listed in the following sections.

### Data Collection API

Collecting the following fields, using the API provided by SpaceX:

* FlightNumber
* Date
* BoosterVersion
* PayloadMass
* Orbit
* LaunchSite
* Outcome
* Flights
* GridFins
* Reused
* Legs
* LandingPad
* Block
* ReusedCount
* Serial
* Longitude
* Latitude

### Data Collection with Web Scraping

Scraping the dataset from the HTML page.

* FlightNumber
* Date
* BoosterVersion
* PayloadMass
* Orbit
* LaunchSite
* Outcome
* Flights
* GridFins
* Reused
* Legs
* LandingPad
* Block
* ReusedCount
* Serial
* Longitude
* Latitude
* Class

### EDA

The purpose of this step is to perform exploratory Data Analysis
 and determine Training Labels for the next steps.

### EDA with Data Visualization

More exploratory Data Analysis and Feature Engineering using `Pandas` and `Matplotlib`.

### EDA with SQL

EDA using SQL to understand the Spacex DataSet.

### Interactive Visual Analytics with Folium lab

Analyzing and visualizing data and geographical patterns about launch sites.

This step marks the success/failed launches for each site on the map and performs
 additional steps for analyzing the launch data.

### Machine Learning Prediction

In this step, we perform the actual training and prediction by 
preprocessing and standardization steps on the data. The steps include
 spliting the training and test data and training models for the prediction.

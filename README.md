# Project Title: Determining the Relationship of Region, Income, and Carbon Emission Rates to Average Country Temperature*

## Description

This project explore the different variables that go into predicting a symptom of climate change, namely 2022 average temperature by country. We train three different models to evaluate what variables best go into predicting 2022 temperature by country. The three models we trained were:

1. The first was solely trained on the average country temperatures from 1961 to 2021 and country region, as these are the two variables most obviously tied to 2022 average temperature. 
2. The second was trained with the country average temperatures, country region, and country income level. 
3. The third was trained with the country average temperatures, country region, country income level, as well as country carbon emission level per capita. 

With these, we were able to see which model had the best accuracy with determine 2022 average temperature by country and, thus, which variables most aptly predict 2022 average temperature by country. 

## Getting Started

### Dependencies

* This project uses scikit-learn==1.1 - the first code block should set this as the standard but, if not, please use the following command within you command prompt to fix this: 
pip install scikit-learn==1.1
* Python 3.11.9 - if you are not using this version please use the following command to fix this: 
Windows: 
winget install python.python.3.11
Mac/Linux: 
brew install python@3.11

### Installing

* The zip file should contain all the files you should have to run the code. The code directory should be as such:
./data
    co_emissions_per_year.csv
    temp_by_year_and_country.csv
final_project.ipynb
README.md
CPSC 381 Final Project Report

If you are missing any of these files - please re-download and try again.

### Executing program

Once you have all of the files downloaded, you should be able to run all cells at once.

## Authors

Deja Dunlap (deja.dunlap@yale.edu)
Fiza Shakeel (fize.shakeel@yale.edu)
Nicole Tian (nicole.tian@yale.edu)


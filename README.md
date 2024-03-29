# Summary
This university project aims to develop an algorithm that maximises the revenue of a grid connected battery for two distinct scenarios; with perfect future price visibility (mandatory task, only for VIC) and without future price visibility (bonus task, for all four states provided). External datasets from an energy company were provided to us to optimise our algorithms.

# Energy Market and Battery Optimization
Group Name:  
- Wimpy Kids (Group 15)

Group Members:  
- Chieh-Yu Chao 
- Hester Lim Tze Hung 
- Kennedy Ker Huan Guok 
- Rui Wang 
- Li Sean Wong

# Repository Overview

- `code`: Contains all notebooks for data preprocessing, analysis, and modelling.
    - There is a README in in this folder which contains descriptions of each file in this folder.
- `data`: Contains all raw data for the project (spot price, electricity operational demand, and intermittent power generation).
- `instructions`: Contains checkpoint files and check.py for submission check.
- `meeting_minutes`: Contains meeting minutes for all meetings conducted.
- `plots`: Contains all plots created for this project.
- `team_code`: Contains all notebooks that our group has written for the project. Each person has one directory for testing out stuff before finalising.
- `requirements.txt`: Contains all packages and libraries used in this project.
- `submissions`: Contains .csv files for submission.
- `Architecture.pdf` : Contains the battery architecture overview

# Recommended Steps
- Run 'Splitting data into training, validation and testing.ipynb' in the 'preprocessing' folder via 'code' folder before the following steps. 

## Mandatory Tasks
Run 'our_algorithm.ipynb' in the 'modelling' folder via 'code' folder. It also contains a checking script to check for bugs.

## Data Analysis and Algorithm analysis
Run 'analysis.ipynb' in the 'analysis' folder via 'code' folder. 

## Bonus Task 
Run 'Bonus.ipynb' in the modelling folder via 'code' folder. It contains the Bonus Task algorithm.
<br />Run 'Bonus_revenue.ipynb' in the modelling folder via 'code' folder. It shows the revenue with the predicted spot price from 1/7/2021 to 11/8/2021(Same time period as the mandatory testing dataset).

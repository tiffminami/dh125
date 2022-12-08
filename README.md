# dh125

## This repository is to compile the data sets used for the DH 125 Project. In our project, we focused on Crime Data in LA County from 2020 to Present. 
### The \textbf{original dataset} is from [Los Angeles Open Data](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8). This dataset was too large in its original and compressed .zip file form, so it could not be uploaded onto GitHub. The link to the dataset is [here](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8as well as in our references.
\\
### The \textbf{cleaned_crime_data.csv} file is from our initial clean. We knew that we wanted to focus on the Victim's demographics. Thus, when looking at the data, we realized that many of the rows were empty. We wanted to clean the data. We first filled the blank spaces with "NA" values in the "Vict.Age", "Weapon.Used.Cd", and "Vict.Sex" columns. We then omitted the rows with "NA" values. After cleaning the data, we removed rows that were not of interest, as we wanted to focus on the data most relevant to our research questions. 
\\
### The \textbf{after.csv} file is the crime data from the first two weeks of the COVID Stay-at-Home Order in LA County(03/19/2020-04/02/2020). In this data set, the rows that contained a "H" value, an invalid value, in the "Vict.Sex" column were removed.
### The \textbf{before.csv} file is the crime data from two weeks before the COVID Stay-at-Home Order in LA County (03/04/2020-03/18/2020).In this data set, the rows that contained a "H" value, an invalid value, in the "Vict.Sex" column were removed.
\\
### The \textbf{after_areadata.csv} file is when the "after.csv" data was used to create a contigency table that counted the frequency of crimes in each area of LA county. The contingency table was then converted into a dataframe. This file was used to create the map visualization.
### The \textbf{before_areadata.csv} file is when the "before.csv" data was used to create a contigency table that counted the frequency of crimes in each area of LA county. The contingency table was then converted into a dataframe. This file was used to create the map visualization.
\\
### The \textbf{LAPD_Divisions.geojson.zip} file is a compressed file of the ["LAPD_Divisions.geojson"](https://geohub.lacity.org/datasets/031d488e158144d0b3aecaa9c888b7b3_0/explore?location=34.018211%2C-118.405297%2C10.48&showTable=true) which is a spatial file that helped create the map visualizations. The link to the dataset is [here](https://geohub.lacity.org/datasets/031d488e158144d0b3aecaa9c888b7b3_0/explore?location=34.018211%2C-118.405297%2C10.48&showTable=true) as well as in our references.
\\\
###\textbf{after_chi.csv} file is the data we used in our chi-square test. The "after.csv" data was subsetted and the rows that have the "X", unknown, value in the "Vict.Sex" column are removed. 
###\textbf{before_chi.csv} fileis the data we used in our chi-square test. The "before.csv" data was subsetted and the rows that have the "X", unknown, value in the "Vict.Sex" column are removed. 

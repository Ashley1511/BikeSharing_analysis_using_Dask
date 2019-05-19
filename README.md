# Bike Sharing analysis using Dask

The objective is to rewrite the Bike Sharing analysis done in the Python for Statistical Programming subject using Dask data structures and ecosystem instead of plain pandas.


### DATASETS:

The datasets can be found on Kaggle's website : https://www.kaggle.com/marklvl/bike-sharing-dataset/home .

Both available csvs contain the following fields, except that the day.csv does not have the hr-column. 

- instant: Record index
- dteday: Date
- season: Season (1:springer, 2:summer, 3:fall, 4:winter)
- yr: Year (0: 2011, 1:2012)
- mnth: Month (1 to 12)
- hr: Hour (0 to 23)
- holiday: weather day is holiday or not (extracted from Holiday Schedule)
- weekday: Day of the week
- workingday: If day is neither weekend nor holiday is 1, otherwise is 0.
- weathersit: (extracted from Freemeteo)
    a: Clear, Few clouds, Partly cloudy, Partly cloudy
    b: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    c: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    d: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp: Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
- atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered

### CONTRIBUTE:

* Fork the master repository (https://github.com/camilleCHAU/BikeSharing_analysis_using_Dask.git) to your github remote account

* Clone the master repository to your local machine.
	git clone https://github.com/camilleCHAU/BikeSharing_analysis_using_Dask.git
    
* Go to the local github directory.
	cd <directoryPath>
	
* Add your fork as a remote
	git remote add <GitHub_UserName> <Forked_repository_URL>
	
* Initialize the repository
	git init
	
* Creating a new branch 
	git checkout -b <branchName>
	
* Add/Modify/Remove files in the repository.

* Commit your changes.
	git add <filePath/fileName>
	git commit -m <"comment">
	
* Push up your changes/branch to your forked repository. 
	git push <GitHub_UserName> <branchName>
	
* Go to your GitHub remote repository and create a pull request.


### AUTHOR:
 - Camille Chauliac
 - Student at IE University
 - Master in Big data and Business analytics

### SUPPORT:
For questions about installation or any other remarks, please find below the email adress of the creator of this repository:
camille.chauliac@student.ie.edu

### ACKNOWLEDGMENTS:

I would like to thank my 'Advance Python' Professor, Mr. Juan Luis Cano, for his numerous efforts in trying to teach us all the secrets and hidden gems of the Python language. He was the brain behind this assignment and thanks to him, I now understand more about the Dask library, how to use it and how it works.



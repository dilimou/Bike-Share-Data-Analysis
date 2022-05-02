# Bike-Share-Data-Analysis

 This notebook analyzes the bike sharing data from capital Bikeshare. The data set is related to a two-year historical log corresponding to year 2011 and 2012.
 
 The dataset contains the below columns:
 - instant: record index
	- dteday : The date on which the data was observed - in this case, the data was collected daily; so there's one row per date.
	- season : A numerically encoded value indicating the season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : he year of the study in which the observation was made (the study took place over two years - year 0 represents 2011, and year 1 represents 2012)
	- mnth : The calendar month in which the observation was made (1:January ... 12:December)
	- holiday : A binary value indicating whether or not the observation was made on a public holiday)
	- weekday : The day of the week on which the observation was made (0:Sunday ... 6:Saturday)
	- workingday : A binary value indicating whether or not the day is a working day (not a weekend or holiday)
	+ weathersit : A categorical value indicating the weather situation
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : Normalized temperature in Celsius.
	- atemp: Normalized apparent ("feels-like") temperature in Celsius.
	- hum: Normalized humidity level.
	- windspeed: Normalized wind speed.
	- casual: count of rentals recorded by casual users
	- registered: count of rentals recorded by registered users
	- cnt: total count of rental for both casual and registered users


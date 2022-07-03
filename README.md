# Explore-Weather-Trends by GIFTY AIYEGBENI

## What tools did you use for each step? 
I extracted the data by writing an SQLqueryfor each of the data sets.
The queries were;
SELECT city.year as cyear, city.city, city.country, city.avg_temp as city_avg_temp, global.year as gyear, global.avg_temp as gavg_temp
FROM city_data city, global_data global
WHERE city.year = global.year
AND city.city = 'lagos' Then I downloaded the extracted CSV file. 
Afterwards, I used excel software to access the data. 

## How did you calculate the moving average? 
I calculated the moving average for both the global and local (Lagos) data using the average function in excel. 
First, I calculated the average of the first two years (1856 and 1857). 
Then I clickedanddragged the formula down to the other cells to get the moving averages for other years. 

## What were your key considerations when deciding how to visualize the trends?
When deciding how to visualize the trends, I considered the years and the movingaverages of both the local and global temperatures. 
I considered the movement, consistencies and inconsistencies in the trends. 
I also considered the best way to makethe trends observable at first glance to aid accuracy in my observations.

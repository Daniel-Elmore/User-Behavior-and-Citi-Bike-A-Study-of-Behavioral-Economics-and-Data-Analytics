README for Data Section of BUS 446 Final Project

The data used for this assignment came from the NYC OpenData repository. This data can be accessed by the following URL: https://data.cityofnewyork.us/NYC-BigApps/Citi-Bike-System-Data/vsnr-94wk 

Per the guidelines of this assignment for Dr. Soumyakant Padhee’s BUS 446.01 – Advanced Data Analytics, only the ride history data from the month of May from 2016 until 2023 was used. The purpose of this was to control for seasonal variations in usage patterns. Consequently, only the following files were used in this study:
•	JC-201605-citibike-tripdata
•	JC-201705-citibike-tripdata
•	JC-201805-citibike-tripdata
•	JC-201905-citibike-tripdata
•	JC-202005-citibike-tripdata
•	JC-202105-citibike-tripdata
•	JC-202205-citibike-tripdata
•	JC-202305-citibike-tripdata

From here, I moved all the data into a single Excel file and cleaned the data to remove observations with missing data and columns of information not pertinent to this analysis. These exceptions primarily constituted observations without information regarding the end time and end location of bike rides. As these exceptions are few and far between, there is no reason to assume the exclusion of these trips had a meaningful impact on the results of the study. To examine the cleaned data for oneself, please take a look at the Excel file entitled “CitiBike Data Cleaned Data Sheet V2.” This will be the file imported into R for the "Code" section of this project. 

README for Code Section of BUS 446 Final Project

This R Markdown (Rmd) file contains an analysis of user behavior in the context of CitiBike data. The study explores aspects such as trip distances, trip durations, late fees, and station preferences for both subscribers and customers. The analysis utilizes data analytics techniques and statistical tests to draw insights from the provided CitiBike dataset.

•	To run the analysis, follow these steps:
•	Make sure you have R installed on your system.
•	Install the required R packages by running the following commands: install.packages(c("readxl", "geosphere", "tidyverse"))
•	Run each code chunk in the Rmd file sequentially to execute the analysis.

This analysis benefited from the assistance of ChatGPT, a language model developed by OpenAI. ChatGPT was utilized to aid in coding tasks, providing guidance, and generating code snippets. The natural language processing capabilities of ChatGPT helped streamline the development process and enhance the overall quality of the analysis. For more information about ChatGPT, visit the OpenAI website.

Key Findings

Trip Distances
The Haversine formula was used to calculate the distance traveled for each trip.
A t-test was conducted to compare trip distances between subscribers and customers.
Boxplots and histograms illustrate the distribution of distances for both user types.

Trip Durations
Trip durations were calculated and analyzed for subscribers and customers.
A t-test was performed to compare ride times between the two user groups.
Boxplots and histograms visualize the distribution of ride times.

Late Fee Analysis
Late fees were assessed based on user types and excess trip durations.
The percentage of users incurring late fees and the average late fees were calculated.

Station Preferences
Top 5 start and end locations were identified for both customers and subscribers.
Chi-square tests were conducted to assess the independence of start and end station preferences.

Station Usage Distribution
Stacked bar plots were created to visualize the distribution of station usage by user type.
Top 20 start and end stations were analyzed using bar plots.

Station Analysis
Stations with fewer than 50 trip starts or ends were identified.

# Prophet Challenge
AI Module 8 Challenge

## Challenge Background and Objective:
The objective is to analyze the financial and user data for Mercado Libre is the most popular e-commerce site in Latin America to make the company grow. The objective is to determine if predict search traffic can translate into the ability to successfully trade the stock. The data was processed in 4 steps as follows:
•	Step 1: Find unusual patterns in hourly Google search traffic.
•	Step 2: Mine the search traffic data for seasonality.
•	Step 3: Relate the search traffic to stock price patterns.
•	Step 4: Create a time series model with Prophet.
This code is available at Github under (https://github.com/Ebylisa/prophet-challenge).

## Code Summary:
(1)  A repository was created called Prophet-Challenge in Git hub and cloned to the local repository.  (2)  A starter code named forecasting_net_prophet.ipynb was downloaded on the local Git repository and GitHub. (3) - The csv file from https://static.bc-edx.com/ai/ail-v-1-0/m8/lms/datasets/google_hourly_search_trends.csv was used for the data analysis. (4)  The csv file was read into a Dataframe. (5)  In Step 1, the search data was sliced to just the month of May 2020 and the results were plotted and visualized. The total search traffic for the month was calculated and compared to the monthly median across all months. (6) - In Step 2, the hourly search data was grouped and plotted for the average traffic by the hour of day, week and year. (7) In Step 3, the dataframes were merged into one new dataframe using concatenated function and plotted.  The new dataframe was then sliced for the first half of 2020 and plotted. New columns were created for  “Lagged Search Trends”,  “Stock Volatility”,  and “Hourly Stock Return. The data was viewed. (8) - In Step 4, a time series model was created to  analyze and forecast patterns in the hourly search data to determine  What time of day exhibits the greatest popularity?; Which day of week gets the most search traffic? ;  and What's the lowest point for search traffic in the calendar year? 

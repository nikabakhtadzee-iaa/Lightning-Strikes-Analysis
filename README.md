# Lightning-Strikes-Analysis
In this project, we use Pandas to examine 2018 lightning strike data collected by the National Oceanic and Atmospheric Administration (NOAA). We then calculate the total number of strikes for each month and plot this information on a bar graph.

After loading the dataset, we inspect its structure by checking its shape, data types, and first 10 rows. The data is structured with one row per day along with the geographic location of each strike, totaling nearly 3.5 million rows and three columns. We note that the date column is currently stored as an string type rather than a datetime. Converting string dates to datetime makes the date manipulation significantly easier.

EDA:
1) Since the dataset contains multiple rows per date for different locations, we group the data by date and sum the strikes to identify the days with the highest activity. August 29 recorded the highest number of lightning strikes in a single day, with 1,070,457 strikes.

2) Next, we analyze lightning strikes on a monthly basis. First, we extract both numerical and text month columns. Then, we group and sum the data by month. August (Month 8) recorded the highest total number of lightning strikes across the year.

3) Finally, we plot the monthly lightning strike counts on a bar graph to clearly visualize seasonal trends and compare strike frequencies across the year.

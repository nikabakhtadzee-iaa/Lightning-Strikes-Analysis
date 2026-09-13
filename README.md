# Lightning-Strikes-Analysis
In this project, we will use pandas to examine 2018 lightning strike data collected by the National Oceanic and Atmospheric Administration (NOAA). After that, we will calculate the total number of strikes for each month and plot this information on a bar graph.
After uploading the dats, we examine structure by seeing its shape,type info and first 10 rows. Yhe data is structured as one row per day along with the geometric location of the strike. The data contains nearly 3.5million rows and three columns. Noticing that the date column is an object type rather than a date type. Converting string dates to datetime will help us to work with them much easily.
Specific EDA:
1)As we see in the data we have multiple rows on same dates, so we group by date and sort in order to see days with the most lightings attacks. 29 August was day with the most lightning strikes recorded - 1070457
2)Next step was analyzing strikings monthly. firstly, i added new column for months numerically and then for texts.Only after, i grouped by and sorted. August(8th month) recorder the most lightning strikes. 
3)

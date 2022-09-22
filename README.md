# NYC Citi Bike Bikeshare Program

## Project Overview
An educational exploration of bikesharing data to determine the viability of bikeshare program expansion. This project uses Tableau for data visualizations. The objective is to provide an analysis of NYC Citi Bike Bikeshare using August 2019 data. 
<br><br>


## Resources

<b>Data Sources:</b><br>
- <a href="https://ride.citibikenyc.com/system-data">Citi Bike System Data</a>, a repository for data files from the Citi Bike archive. The August 2019 data file titled "201908-citibike-tripdata.csv" was selected.<br>

<b>Components:</b><br>
- Tableau 2022.2<br>
- Jupyter Notebook 6.4.8<br>

## Results
Several visualizations were created using Tableau 2022.2 and the full visualization can be found <a href="https://public.tableau.com/views/NYCCitiBikeRideShareOverviewAugust2019/NYCCitiBikeOverview?:language=en-US&:display_count=n&:origin=viz_share_link">here</a>.


<a href="https://public.tableau.com/views/NYCCitiBikeRideShareOverviewAugust2019/NYCCitiBikeOverview?:language=en-US&:display_count=n&:origin=viz_share_link">
         <img alt="Tableau NYC Citi Bike Rideshare Tableau Story" src="https://user-images.githubusercontent.com/105830645/191699081-ac019909-1e2d-4182-a3fb-70aa37fd0aff.png"></a>
         

## Summary

The first series of visualizations give overviews of trip counts, bike counts, average trip length, and the number of bike stations.
![Screenshot 2022-09-22 042906](https://user-images.githubusercontent.com/105830645/191699464-8f42bbd4-28bc-4648-891e-c7beaf7b5906.png)

The second series of visualizations focus on bike stations and their usage. Users can interact with starting and ending location maps to gain futher insight into how busy each station is. This can help ensure sufficient bikes are placed at the stations with most demand.
![Screenshot 2022-09-22 045938](https://user-images.githubusercontent.com/105830645/191704729-4dfb5a93-9905-4043-bfcf-bebdc7c7e155.png)


The third series of visualizations give demographic information, such as age and gender-related information. Captions were added to describe data outliers for age that warrant further investigation. Some ages fall outside of typical ranges, whether by user error or intential choice, and filters were added to the bar and area charts so these can be filtered.
![Screenshot 2022-09-22 043136](https://user-images.githubusercontent.com/105830645/191699841-cf09a553-a9f9-4b3c-be1e-bed65c8cf2e0.png)

The fourth series of visualizations focus on ride times to help determine the most active hours for bike use. Notice on the heatmap below that hours of most use follow the times before and after a typical workday. Thursday, Friday, and Saturday are the peak days for bike checkouts.
![Screenshot 2022-09-22 043209](https://user-images.githubusercontent.com/105830645/191700112-65b27fb6-9bf6-42b0-af40-dcf491881117.png)
![Screenshot 2022-09-22 043242](https://user-images.githubusercontent.com/105830645/191700129-f44af90e-f185-4f82-8653-0c2f24e2c299.png)

In the fifth visualization series a user can see the bikes that have the most use and likely need maintenance. Maintenance workers can also search for specific bike numbers to get their usage hours. While the packed bubble chart is an interesting visual, it is not the most user friendly way to get at high-use bikes and should be considered for removal in the final product.
![Screenshot 2022-09-22 043321](https://user-images.githubusercontent.com/105830645/191701294-0036cea1-15d2-4208-92ee-726781b7a1b5.png)

The final visualization series was created by comparing bike checkout hour, trip count, trip durations, and gender. It is not a visualization that is easy to understand at a glance for the average user, and therefore isn't recommended as a view to include in the final product. It was included as an exercise to show the types of visualizations that are possible.
![Screenshot 2022-09-22 043348](https://user-images.githubusercontent.com/105830645/191703233-ef6f9612-3b8a-49a5-884d-bb5494cc2035.png)

### Recommendations
For the most usable product the recommended next step would be user testing. Any visualization that needs lengthy descriptions and explanations should be refined or removed. Investigation into age-related outliers should be done as well. 

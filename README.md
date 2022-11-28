# Citi Bike Challenge

This challenge was built around analyizing Citi Bike user data from New York City from August 2019. The client was looking to have visualizations created to determine if the business model could work in Des Moines, Iowa. The visualizations were created from a csv file fed into Tableau, a popular piece of data visualization software.

## Analysis 

As mentioned previously, the analysis was done utilizing Tableau from a csv file. One piece of data cleanup had to be performed in python, converting the "tripduration" column to a date/time format to facilitate some of the visualizations in Tableau. This was performed in the Jupyter Notebook file included in this repository.

### Visualization 1

The visualization below identifies trends in the trip time for all users. As you can see below, the bulk of the trips are very short, lasting fewer than ten minutes in most cases. This suggests that users primarily utilize the service to make short trips, with very few riding the the Citi Bikes for an hour.

<img width="954" alt="Screen Shot 2022-11-25 at 2 25 05 PM" src="https://user-images.githubusercontent.com/108236450/204169304-5f467d62-692e-4f3e-9e3c-9692b273e72c.png">


### Visualization 2

The next visualization takes the same data and view but separates it by gender. This shows that while male and female riders display similar patterns in terms of trip duration, there are significant differences in the amount of trips made by male and female riders. 

<img width="938" alt="Screen Shot 2022-11-25 at 2 30 15 PM" src="https://user-images.githubusercontent.com/108236450/204169589-d0467d57-2005-4d1a-ac4d-7f6387d03143.png">

### Visualization 3

The third visualization is a heatmap displaying the times when Citi Bikes are used. Interestingly you can see that on weekdays are during the 8am hour and 5 and 6pm hours. This suggests that many users utilize the service for commuting. There is also increased usage between the late morning and early evening on the weekends.

<img width="576" alt="Screen Shot 2022-11-25 at 2 37 58 PM" src="https://user-images.githubusercontent.com/108236450/204169904-87295f80-b0b5-4a49-aa05-ba0f3be04455.png">

### Visualization 4

This visualization takes the same heatmap but separates the data by gender. Here it shows that the usage is far greater among male riders during commuting hours. A question might be whether or not clothing worn by different genders to work plays a role in this.

<img width="806" alt="Screen Shot 2022-11-25 at 2 42 48 PM" src="https://user-images.githubusercontent.com/108236450/204170099-a9cb6d0e-2673-4407-97b2-c9fe24caec20.png">

### Visualization 5

This fifth visualization shows a heatmap of Citi Bike usage by day of the week, gender, and user type. What is clear from this is that the bulk of the riders are male and subscribers to Citi Bike. It seems that there could be some opportunities for growth with female riders and with non-subscribers.

<img width="989" alt="Screen Shot 2022-11-25 at 2 45 54 PM" src="https://user-images.githubusercontent.com/108236450/204170363-0e744aa5-d493-4150-bcfe-a27c3aa5956d.png">

### Visualizations 6 & 7

These visualizations look at the top starting and ending locations for rides. Most rides seem to take place in Manhattan, primarily in midtown and lower Manhattan. Fewer rides take place uptown or in Brooklyn. Perhaps these are areas to explore growth.

<img width="881" alt="Screen Shot 2022-11-27 at 8 02 57 PM" src="https://user-images.githubusercontent.com/108236450/204170850-b0a1eb13-05c9-4c6d-9082-9ed74716d84c.png">
<img width="867" alt="Screen Shot 2022-11-27 at 8 03 12 PM" src="https://user-images.githubusercontent.com/108236450/204170945-3b8b659e-e291-4e0b-99ab-537740cc720e.png">


## Summary and Recommendations for Additional Visualizations

As noted in the descriptions of the visualizations, the bulk of riders are male, ride for short amounts of time during commuting hours, and generally in lower Manhattan. Given that the reason behind this analysis was to see if this service could be brought to Des Moines, I would recommend a visualization and analysis of the geographical area of Des Moines to determine if it would be accessible for travel by bike. I would also recommend comparing the population density of NYC and Des Moines, it seems on the surface that they are two cities that are quite different. An additional visualization I would recommend is to look at the commuting patterns in Des Moines. What distance do commuters travel? Could commuters be persuaded to change their habits?




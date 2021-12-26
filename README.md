<image src="https://github.com/CLHollis/PyBer_Analysis/blob/44f2644f900f8eb7a38688827a65122397a80c65/Resources/2019-08-30-Ridesharing-Feature-Getty.jpg" width="500" height="300">[^1]   

  # ~ Rural v. Suburban v. Urban ~


## Mission
At PyBer, a ride-sharing app company valued at $2.3 billion, my first big project is to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO to help improve access to ride-sharing services and determine affordability for underserved neighborhoods. To do this, I will:
1.  Create a summary DataFrame of the ride-sharing data by city type. 
2.  Using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. 
3.  Summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Resources
-	Data Sources: [city_data](Resources/city_data.csv), [ride_data](Resources/ride_data.csv)
-	Software: Python 3.7.6, Jupyter Notebook, 6.0.3
- Analysis Process/Code: [PyBer_Challenge](PyBer_Challenge.ipynb), [PyBer](PyBer.ipynb)
  
## Results
<image src="analysis/Drivers_by_type.png" width="300" height="300"> | <image src="analysis/Rides by type.png" width="300" height="300"> | <image src="analysis/Fares by type.png" width="300" height="300">
<image src="analysis/data_df.png" width="700" height="150">

### Comparison of Drivers, Riders, and Fares beteen city Types
| --- | Rural | Suburban | Urban |
| --- | --- | --- | --- |
| Total % by Driver | 2.6% | 16.5% | 80.9% |
| Total % by Rides | 5.3% | 26.3% | 68.4% |
| Total % by Fares | 6.8% | 30.5% | 62.7% |
| Fare per Ride | $34.62 | $30.97 | $24.53 |
| Fare per Driver | $55.49 | $39.50 | $16.57 |

Rural areas are the least active in ridesharing overall, however they bring in the highest fares per driver and ride. This is probably due to the loner distance between pick-up and drop-off points for riders. 

Although Rural areas brought the highest fare per driver and ride, they brought the company in the least amount of fares overall, bringing in about $250/week.
Suburban cities brought in the next highest amount at about $1,000/week. 
And the most profitable city type was urban areas, bringing in about $2,250/week
<image src="analysis/total_fare.png" width="900" height="250">  
## Recommendations
1. Because ride sharing is most profitable per ride in rural areas, check into starting a reimbursable program for people in that area who are frequenting certain places, like the elderly to their doctor appoinement using Medicare reimbursements, or college students to school using tuition funds. 
2. Since Urban areas are the most popular and frequqntly used, chack into setting up an hourly tour of the city, like rent a driver for 8 hours and go see all the sights, like a tour guide. This should bring in an additional source of revenue and allow more guaranteed income for drivers.
3. Sponsor events in the country and lure city folks to participate, like county fairs.
4. To encourage Urban riders to take longer rides, run a promotion for Urban riders: A discount off rides more than [the distance of a $35 ride] (the uper bounds of the standard deviation of the Urban Ride Fare Data). 
  
  
  
[^1]: [Patient Engagement Hit. "How Medical Rideshare is Tackling Patient Care Access During Coronavirus"](https://patientengagementhit.com/news/how-medical-rideshare-is-tackling-patient-care-access-during-coronavirus). Accessed Dec. 26, 2021.

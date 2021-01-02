# Bike Share Service Data Exploration


## 2019-02 Ford GoBike Trip Data

> This dataset holds trip information made by members of Ford GoBike's bike share service during February in 2019

Columns:

- duration_sec: represents the time (in seconds) for the trip was ongoing
- start_time: represents the date and time when the trip started in the format (YYYY-MM-DD HH:MM:SS)
- end_time: represents the date and time when the trip ended in the format (YYYY-MM-DD HH:MM:SS)
- start_station_id: holds the id of the station where the trip started
- start_station_name: holds the name of the station where the trip started
- start_station_latitude: represents the angle from the equator to the start station's location
- start_station_longitude: represents the angle from the prime meridian to the start station's location
- end_station_id: holds the id of the station where the trip ended
- end_station_name: holds the name of the station where the trip ended
- end_station_latitude: represents the angle from the equator to the end station's location
- end_station_longitude: represents the angle from the prime meridian to the end station's location
- bike_id: represents the id of the bike involved in the trip
- member_birth_year: holds the birth year of the user
- member_gender: contains the gender of the user; either male or female
- bike_share_for_all_trip: represents whether members are enrolled in the Bike Share For All discount program


## Summary of Findings

- As expected, the distribution of trip durations is highly skewed to the right which shows that as the trip gets longer and becomes more demanding the lower the chances of it occurring.
- The age distribution of members also shows a skewness to the right which is another normal aspect of the nature of bike riding; not many old people would tolerate physically taxing rides. The modal age range with the highest trip duartions is centered around 30 years old.
- A further real-life note to be picked up from the visualizations is that the number of trips on weekends is very similar and that the trip duration peaks on weekends.
- Surprisingly, however, the majority of members were not interested in obtaining ride discounts which is shown by the low membership rates in the bike share for all discount program. This discount program did not even affect the duration of trips as shown by the `Average Trip Duration By Gender And Discount Membership` visualization; the members who took part in the discount program always had lower average trip durations.


## Explanatory Visualizations Polishing
- To prepare for the presentation, some visualizations were despined. Titles and labels were added. Finally, legends were added were necessary.

## Resources
- Stack Overflow
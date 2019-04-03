# VAST Challenge 2019: Sample Data

Welcome to St. Himark! Before the official release of the 2019 challenge data, you can download a sample here.

In the ZIP archive, you'll find a folder for each of this year's Mini-Challenges:

## Mini-Challenge 1

This challenge contains categorical data from a mobile application allowing citizens to report earthquakes and damage to city officials.

There will be one (CSV) file spanning the entire length of the simulation, containing (categorical) individual reports of shaking/damage by neighborhood over time.

mc1-sample-rumble.csv:
* time: timestamp in the format YYYY-MM-DD hh:mm:ss (may be in order, may not; depends on how good the Rumble developers were...)
* location: id of neighborhood where person reporting is feeling the shaking and/or seeing the damage
* {shake_intensity, sewer_and_water, power, roads_and_bridges, medical, buildings}: reported categorical value of how violent the shaking was/how bad the damage was (1 - low, 10 - highest; missing data allowed)

## Mini-Challenge 2

The quake has damaged a nuclear power plant and spread low levels of contamination across the city. An army of citizen scientists has been mobilized to help understanding which areas are affected. This dataset contains readings from both stationary and mobile sensors.

MC2 will contain two data files spanning the entire length of the event, containing radiation measurements from mobile and static radiation sensors. A third file will show the locations of the static sensors. 

* The sample data file MC2_mobile_sensor_data.csv contains a stream of about 7.5 hours of measurements from a single mobile sensor. 
* The sample data file MC2_static_sensor_data.csv contains a stream of measurements from a single static sensor over the same time period. Each measurement includes a timestamp, a Sensor-ID, Longitude, Latitude, the radiation measurement value, the radiation measurement units, and a user-ID.

Be prepared for missing and corrupted data, skipped timesteps, and other issues.

## Mini-Challenge 3:

Officials are utilizing all resources available to them to understand how those affected by the earthquake are faring. This challenge includes social media posts where people are reacting to events and the effects of those events on them. 

MC3 will contain one CSV file, spanning from 04/06/2020 - 04/12/2020, which has the following fields:
	- time (date/time the message was posted)
	- location (St. Himark neighborhood message was posted from)
	- account (user handle of the person who posted the message)
	- message (text of the message itself)
	
Be prepared to have to discern between reliable and unreliable messages.


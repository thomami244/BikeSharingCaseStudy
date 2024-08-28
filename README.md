# Bike Sharing Case Study for BoomBikes 
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 
> BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- This project analyzes the factors affecting bike rentals for BoomBikes in order to provide insights that can help the company optimize operations post-pandemic.
- The business problem focuses on predicting bike demand and understanding how different factors (like season, weather conditions, etc.) impact the number of bikes rented.
- The dataset used includes features such as date, season, year, month, holiday, weekday, working day, weather situation, temperature, humidity, and bike rental counts (casual, registered, and total).
  

## Conclusions
- The model explains approximately 77% of the variance in bike rentals (R-squared = 0.770), with a slightly higher test R-squared of 0.782, indicating strong predictive performance.
-Seasonal Effect: Spring has the most negative impact on bike rentals, while the winter season also shows a significant decrease in demand.
- Yearly Growth: The year 2021 (yr_1) shows a significant positive effect on bike rentals, suggesting an increase in demand over time.
- Weather Impact: Adverse weather conditions, such as light snow or rain and mist/cloudy weather, significantly reduce bike rentals.
- Other Factors: Working days and certain weekdays (like Saturday) positively impact the number of rentals, reflecting higher demand on these days.


## Technologies Used
- pandas - version 1.3.3
- matplotlib - version 3.4.3
- seaborn - version 0.11.2
- numpy - version 1.21.2


## Contact
Created by @thomami244 - feel free to contact me!

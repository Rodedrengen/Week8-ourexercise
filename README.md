# Week8-ourexercise

## By: Group 2 (class: E)
### Members
- Benjamin Skovgaard (cph-bs190@cphbusiness.dk)
- Oliver Vang (cph-ov111@cphbusiness.dk)
- Simon Jørgensen (cph-sj414@cphbusiness.dk)

# Exercise 1

1. Go to http://api.openweathermap.org/data/2.5/forecast, create an account and get an API key.
2. Using flask create an endpoint that takes a city as parameter and call openweather with that city. 
3. Load the temperatures, dates and city name for the week into a panda dataframe and persist it to a table in your database. 
  - hint .json()["list"] is a place to start

# Exercise 2

1. Create an endpoint that takes a city name as parameter and returns the highest temperature for the week in that city. 
2. Load more cities into your database. 
3. Create an endpoint that takes a date and returns the city with the highest temperature that day.
4. Create an endpoint that takes a data and returns the average temperature that day across all cities in the database. 

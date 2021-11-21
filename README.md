This app will have the following features:


=> Temperature of any city and country
=> Show the 7-day forecast for a specific city.
=> Temperature chart for 24 hours.
=> Include a weather icon , temperature reading , and short description of weather conditions.
=> Data in the form of cards having date and max and min temperature including wind speed .
=> Show pressure and humidity .
=> Show sunrise sunset time.

Stack used 
..........

React js 
React Hooks
Material-ui
context-Api

For running the App
........................

1- clone the project (git clone )
2- open a editor and open the project to run
3- npm i
4- npm start


FOr Finding the location 
............................

const url = 'http://ip-api.com/json';

this api will provide current location => latitde , longitude,country, city

Now once you have location ,we need to get weather details.
.................................................................


In order to do this, I have used the OpenWeatheropeAPI . I’ll walk you through the steps of getting an API key and using api.
1 .Go to → https://home.openweathermap.org/api_keys and signUp.
2 .Go to https://home.openweathermap.org/api_keys and get api_key.

OpenWeatherapi provides with many services.

1 . We want forecast of today and next 7 days .
2 .In Addition to this i have the temperature of next 24 hour as a filter on the daily basis.

When you click on the particular card then it will show the details of that particular day also .

There is an api which will provide both ONE-CAll-API .

const url = `https://api.openweathermap.org/data/2.5/onecall?lat=${lat}&lon=${lon}&appid=${api_key}`

For Running This App
............................
Clone the project : git clone https://github.com/skd09021991/codeclouds.git

Open the project in a editor of your choice then run =  

1>   npm i 
2>   npm start

App is deployed in heroku

.........................

Live Demo : 

http://codeclouds-app.herokuapp.com/


Really sorry , i was unable to upload the images to the docker . As my system is not configured with the docker and i am trying to configure and made an id also but it fails .

docker id: skd9291
password: santosh@9291



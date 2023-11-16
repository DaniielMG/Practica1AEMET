# P1_WEATHER
![image](https://github.com/DaniielMG/Practica1AEMET/assets/95304769/566edebc-110d-406e-a850-74e4e050cb71)


##### This project uses Java to obtain climate data from specified locations and stores it in an SQLite database. Use the OpenWeatherMap API to get up-to-date weather information.

## System Requirements
##### ~ Java JDK 8 or higher
![image](https://github.com/DaniielMG/Practica1AEMET/assets/95304769/aa064826-5339-489f-90e5-b9f6891674db)

##### ~ Apache Maven (optional, if you decide to manage dependencies manually)
![image](https://github.com/DaniielMG/Practica1AEMET/assets/95304769/18895728-d20c-441a-ab80-91775cbbd080)


## Setting :
#### Clone the repositor
![image](https://github.com/DaniielMG/Practica1AEMET/assets/95304769/a27e1ee4-723d-4696-9286-b3737551e331)

### Dependencies:
#### Make sure you have the necessary dependencies. If you don't use Maven, make sure you have the necessary libraries in your project.

### API key:
#### Place your OpenWeatherMap API key in the WeatherMapProvider class. Find the apiKey variable and replace it with your own key

### CSV file:
#### Make sure you have a CSV file called island.csv in the src/main/resources path with the format:
![image](https://github.com/DaniielMG/Practica1AEMET/assets/95304769/8e320d50-49eb-4e26-99a4-3da5e7b04dc2)

## Use:

### Execution:
#### Runs the Main class to obtain climate data for each location specified in the CSV file.

### Results:
#### The application will run immediately and every 6 hours thereafter, fetching and storing weather data in the database.

## Diagram:


## Author
#### Daniel Medina González.

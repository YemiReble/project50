# Weather Web Application
- [x] Daily Weather Status
- [x] Location Search
- [x] Weather Reports

## Introduction
This weather app was inspired by the current weather situation. It uses the OpenWeatherMap API to display up-to-date weather information for any location in the world. The app provides current weather conditions and weather reports. 

It also includes information about the sunrise and sunset times, humidity, and visibility.

The weather app is designed to be easy to use. The main screen displays the current weather conditions for your current
location. You can also search for weather information for any other location in the world. The app's reports are
accurate and reliable in accordance to the OpenWeatherMap Data, and they are updated every hour.

The weather app is a valuable tool for anyone who wants to stay informed about the weather. It is perfect for people who plan outdoor activities, travel, or simply want to know what to expect when they leave the house.

## Features
* Easy to use interface
* Current weather conditions
* Up-to-date weather information for any location in the world
* Accurate and reliable reports in accordance to the OpenWeatherMap API Data
* Information about the **Max and Min**, **Sunrise and Sunset Times**, **Humidity**, and what the weather feels like

## How To Use This Program
Make sure that the requirements to run this program is avalable on your machine, kindly see the
[reqirements.txt](https://github.com/YemiReble/project50/blob/main/requirments.txt) file if you haven't.
Done? Okay! Now that you have all the requirements in place, you may proceed to the following steps.

This program runs on port 6556 by default, kindly ensure that port 6556 is available or you may change it to your desired port(s). You may use the auto start sever file to run the program on port 5000.

**Step 1:** Clone this Repository
```Bash
$ git clone https://github.com/yemireble/project50.git
```

**Setp 2:** Change dir and run the server automatically 
```
$ cd project50/

Auto Run Server
$ ./auto_start_server.sh
```
**Sept 3:** Now that the server is running, head over to your browser
```
http://127.0.0.1:5000
```
Your browser should display the Weather Application Home Page as shown below
###### If You Encounter An Error
Obtaine [OpenWeatherMap API](https://openweathermap.org/api) Key and insert it in the required file on line (8)
```
$ code helper/functions.py
```

## User Interface Display
##### Search Section
![The Search Area](https://github.com/YemiReble/project50/blob/main/static/img/Search_Area.JPG)

#### Current Weather Section
![Current Weater](https://github.com/YemiReble/project50/blob/main/static/img/Current_weather_display.JPG)

##### Report Section
![Report Section](https://github.com/YemiReble/project50/blob/main/static/img/Weather_Reports.JPG)


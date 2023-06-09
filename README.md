# weatherapp_frontend

# **Preparation Project**
# **Weather JAVA EE + Angular+  UI**
**Project name:** WeatherApp + Angular8+
**Tech stack:** J2EE, Angular8+
## **Lesson goals**
Project made during application for Intern Position at ITWare.

### To run
 // Clone the repository and run with npm
   npm install
   npm run start

ps.: The listed cities that are showing are mockups. To see real time data, you must run the
backend in your localhost:8080. In case of running the backend in other address, configure it in
./src/app/app.constants.ts.

Add and Delete will only work if the backend is running.

**Angular 8+**
1. Basic project structure
1. Components
1. Page layout
1. Service providers


## **Homework description**
Create a client-server application, the main function is to show a cities weather (temperature) data on a simple web interface, so we call our application "WeatherApp"

### **The main functions of the WeatherApp**
1. Enter a city name, and fint the weather information from a public, external API (eg. openweathermap.com)
1. Save the weather information to local database for the city that was entered
1. List the cities and weather information that are in our local database
1. Can delete city from out local database
1. Weather data is automatically refreshed in the background using a scheduled service

### **Use cases**
1. Add new city weather data
1. Get list of weaher data from our local database
1. Delete city from out local database

### **Tasks to be completed**
#### **Frontend**
1. Create Angular 8+ project
1. Create a user interface components as shown below in the diagram
   0. app.component
   0. search.component
   0. citylist.component
   0. cityitem.component
1. Connect server side calls
1. Build + Run + Test the application

## **Checklist**

|**Component**|**Task**|**Description**|**Done (Y/N)**|
| :-: | :-: | :-: | :-: |
|Frontend|Create project structure|Create a new empty Angular project with Hello Weather message only.|:white_check_mark:|
|Frontend|Build and deploy project|Build and run the empty project on a webserver.|:white_check_mark:|
|Frontend|Component: Add city component|Create the visuals of the Add city component, without REST calls.|:white_check_mark:|
|Frontend|Component: List cities component|Create the visuals of the List cities component, without REST calls.|:white_check_mark:|
|Frontend|Component: City listitem component|Create the visuals of the City listitem component.|:white_check_mark:|
|Frontend|Main application component|Layout the other component into the main app screen.|:white_check_mark:|
|Frontend|REST: addCity integration|Add server side integration to the Add city component (addCity API call)|:white_check_mark:|
|Frontend|REST: listCity integration|Add server side integration to the List cities component (listCities API call)|:white_check_mark:|
|Frontend|REST: deleteCity integration|Add server side integration to the City listitem component (deleteCity API call)|:white_check_mark:|
|Frontend|Error handling|Handle and visualize possible error messages from the server.|:white_check_mark:|
|<p>Backend +</p><p>Frontend</p>|CHECK ALL THE APPLICATION IS WORKING?|CHECK ALL THE APPLICATION IS WORKING?|:white_check_mark:|
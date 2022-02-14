# Homework_6-Tanner
#### Synopsis: We were the create browser application that allowed a user to view the weather conditions in different cities implemented with the use of a weather API.
## Implementation Step
### Implement HTML and CSS according to the mockup.
### Implement Javascript
#### Onload
##### 1. Initialize look an feel to initial state.
##### 2. Load searches from previous session from brower storage into previous session buttons.
##### 3. Implement input fields and event listeners:
###### - City name text input field
###### - Submit city name text input field button
###### - City name input field event listener
###### - City name input field submit button event listener
#### On 'Enter' keyed on city text input field or submit button clicked:
##### 1. Construct URL from user input.
##### 2. Call URL
##### 3. Test response validity. In invalid, bail.
##### 4. Parse response JSON.
##### 5. Fill appropiate feilds with data elements. 
###### - URL 1, Single Day Forecast
###### - cityName, validated
###### - temp
###### - wind
###### - humidity
###### - uv index (background color coded according to NWS standard.)

!["UV Background Color Code"](./assets/images/uv_hazard_colorcode.png "UV Background Color Code")

###### - URL 2, Extended Forecast
####### - temp
####### - wind
####### - humidity
####### - weather code (for weather icon.)

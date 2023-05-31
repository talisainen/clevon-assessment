# &#8595; Add your name here:
Eesmini Perekonnanimi

# You need to write a code that will display yesterday local temperature without any user intervention.

1. **Obtaining IP address**
    * Use API from http://httpbin.org/ to obtain your computer external IP address
    * Does not require authentication
    * Endpoint http://httpbin.org/ip (try it in browser)
    * Use ```requests``` library and parse JSON response

2. **Fetching geographic coodrinates according to the IP address**
    * Register free account at https://ipgeolocation.io/ and get an API key
    * Endpoint https://api.ipgeolocation.io/ipgeo
    * Documentation link https://ipgeolocation.io/documentation/ip-geolocation-api.html
    * Use API from to fetch "latitude” and "longitude”

3. **Requesting weather data**
    * Use  [VisualCrossing Weather API](https://www.visualcrossing.com/weather-api) to fetch weather data for particular geographic coordinates
    * Link to documentation https://www.visualcrossing.com/resources/documentation/weather-api/timeline-weather-api/
    * Make sure ```unitGroup``` parameter corresponds to metric measurement units, not US
    * To obtain the date use Python [datetime module](https://docs.python.org/3/library/datetime.html)
    * Use either f-strings, ```string.format()``` method of ```%s``` notation to compile a request string in Python



Your repositories are private, make sure your API keys are available for the code to run on the server for validation and automated testing.

Try-except and other types of exception handling are welcome, but not required.

**Expected output: number with one decimal place**

Use a template in main.py

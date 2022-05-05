# OpenWeatherApp
Simple NodeJS Weather App using openweathermap.org API

![App gif preview](https://github.com/konopat/OpenWeatherApp/blob/734cec22bd6b37899574f56cfa3fc29627556c15/WeaterAppDemo.gif)

### Using modules:

express, https, body-parser.

### Showing Data:

temp (Celcius), weather description like: "is currently few clouds", special icon showing the current weather.

### You need your own API key
You need API key from openweathermap.org. Replace it with the string value of the "const apiKey" in the post method (app.js):

```
app.post("/", function(req, res) {

  const apiKey = "HERE IS YOUR KEY";
  const query = req.body.cityName;
  const unit = "metric";

```

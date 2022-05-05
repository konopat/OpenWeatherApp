# OpenWeatherApp
Simple NodeJS Weather App using openweathermap.org API

![App gif preview](https://github.com/konopat/Open-Weather-NodeJS-App/blob/c41d6dce03c82648558497d4b0f9471f00ecb0ec/WeaterAppDemo.gif)

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

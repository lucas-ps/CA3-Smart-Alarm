# Smart Alarm CA3

This python project for my third continuous assessment at Exeter University uses flask in python to make an event driven 'smart alarm' website which integrates current news, weather and COVID-19 data using free APIs. Hosted at: https://github.com/lucas-ps/CA3-Smart-Alarm
## Requirements
* Python >= 3.7
* Python modules:
  * Flask
  * PYTTSx3
  * Requests
  * Datetime
  * JSON
  * Math
  * Time
  * Sched

## Configuration
The use of APIs in this project requires you to register for and use API keys, the config for which can be found in the config.json file, I have left my API keys in for testing purposes.

You should get API keys from:
* [NewsAPI](https://newsapi.org/)
* [Open Weather Map](https://openweathermap.org/)

Also in the config.json file is the location info that the program will use for weather

```JSON
{
"API-keys":{
    "weather" : "",
    "news" : ""
},
"location-info":{
    "city" : "Exeter",
    "country" : "UK"
},
"filepaths":{
    "logfile" : "program.log"
}
}
```

## License
MIT License

Copyright (c) 2020 Lucas Proudhon-Smith

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

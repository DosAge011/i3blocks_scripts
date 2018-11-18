# i3blocks_scripts
## i3weather.py
Requires [Noto Color Emoji](https://www.google.come/get/noto/help/emoji) font (or edit for your own icons)

Requires [Open Weather Map](https://openweathermap.org/) API Key (free)

[**i3Blocks config:**]
```
[weather]
command=i3weather.py CityName CountryCode OpenWeatherApiKey
interval=3600
markup=pango
```
**command example:** i3weather.py Vancouver CA XxXxXxXxXxXXXxxxX
